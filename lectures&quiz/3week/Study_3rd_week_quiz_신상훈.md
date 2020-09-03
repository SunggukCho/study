# 3rd_week_quiz

## CORS & Wireshark _ 신상훈



### 1. 웹 생태계에서 다른 출처로의 리소스 요청을 제한하는 것과 관련된 정책은 두 가지인데, '같은 출처에서만 리소스를 공유할 수 있다' 는 의미를 가진 정책의 이름은 무엇인가 ?

---

```text
Cross Origin Request Sharing은 아니고
SOP - Same Origin Policy
```



### 2. 같은 출처와 다른 출처를 구분하는 URL의 구성 요소가 아닌 것은 ?

1.  Scheme
2. Host
3. ~~Method~~
4. Port



### 3. CORS의 시나리오 중 Preflight Request 케이스의 경우, Simple Request 케이스와 어떤 점이 다른가 ? 또한 요청에 대한 서버의 응답으로 200 OK 를 보내준다면 CORS 정책을 통과한 것이라고 볼 수 있는가 ?

```text
차이점 : 예비 요청을 보내고 받는 과정이 있음
통과한 것이라고 볼 수 있는가 ? : 그건 아니다. 서버는 200OK를 보내줘도 브라우저가 ERROR를 띄울 수 있다.
```



### 4. CORS 정책 위반을 해결할 수 있는 가장 대표적인 방법을 작성하여라

```text
Access-Control-Allow-Origin 세팅
ex) django
Access-Control-Allow-Origin: False 
```



### 5. Credentialed Request(인증된 요청 시나리오) 케이스의 경우 요청에 인증과 관련된 정보를 담을 수 있게 해주는 옵션을 작성하고, 이 옵션에 사용할 수 없는 값을 찾아라.

```text
옵션 이름 : CREDENTIALS
```

1. include - 모든 요청에 인증 정보를 담을 수 있다.
2. ~~different - 다른 요청에 인증 정보를 담을 수 있다.~~
3. omit - 모든 요청에 인증 정보를 담지 않는다.
4. same-origin - 같은 출처 간 요청에만 인증 정보를 담을 수 있다.



### 6. 와이어샤크의 주요기능이 아닌 것은 ?

1. 패킷 캡쳐 데이터를 열거나 저장
2. ~~특정 패킷을 생성해 네트워크로 전송~~
3. 다양한 조건으로 패킷을 필터링하거나 검색
4. 플러그인을 제작해서 자유롭게 기능 생성
5. 다른 LAN 분석툴로부터의 캡쳐 데이터를 저장



### 7. 와이어샤크의 장단점을 자유롭게 기술하시오

```text
장점: 잦은 버전업, 다른 분석툴이 캡쳐한 것도 열어볼 수 있다.
단점: 패킷 생성 후 네트워크 전송 불가, 상용 분석툴 보다 트렌트 기능, threshold기능 등이 약하다. 
```



### 8. 와이어샤크가 가진 필터링 식이 아닌 것은 몇 개인가?

1. eth.addr ==
2. ip.addr ==
3. tcp.port ==
4. ip.src !=
5. not icmp

모두 가능