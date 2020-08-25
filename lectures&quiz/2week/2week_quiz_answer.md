# 2nd_week_quiz (조성국)

## 1. 다음 중 웹에서 실시간 소통 네트워크 기술의 발전을 순서대로 올바르게 나타낸 것은?

1. websocket -> streaming -> long poll -> poll
2. polling -> websocket -> streaming -> long poll
3.  ~~polling -> long polling -> streaming -> websocket~~
4.  streaming  -> websocket -> poll -> long poll



## 2. 다음 중 폴링 방식에 대한 설명으로 옳지 않은 것은?

1. 클라이언트 수가 많아질 수록 부담이 계속해서 가중된다.
2. ~~기존의 http request 방식을 넘어선 실시간 네트워크 통신 기술이다.~~ -> polling 역시 http 기반 위에서 동작한다.
3. CLIENT가 주기적으로 SERVER에게 요청을 보낸다.
4. SERVER는 CLIENT에게 RESPONSE를 주면서 Connection을 끊는다.



## 3. 다음 모식도는 실시간 네트워크 기술 중 어떤 방식을 표현한 것인가?

![streaming](https://t1.daumcdn.net/cfile/tistory/1155F54E50FF71CD0A)

1.  websocket
2.  poll
3.  ~~streaming~~
4.  long poll



## 4. websocket 방식의 문제점과 그것을 해결하는 방법을 간단히 서술하시오. 

 ```text
websocket의 단점은 Websocket을 지원하지 않는 브라우저에서는 화면이 나타나지 않는다는 것이다.
아무리 좋은 기술이라해도 인프라가 받쳐 주지 않을 경우에는 힘을 쓰지 못한다.
이럴 때는 오히려 예전 기술을 활용하는 것으로 문제를 해결할 수 있다.
1. 지원하는 브라우저는 기본적으로 websocket을 사용
2. 지원하지 않는 부라우저는 polling, long-polling, streaming 등 websocket이전의 기술들을 사용하여 실시간 통신을 한다.
항상 최신기술만이 답은 아닐 수도 있다는 교훈을 배워가자.
 ```



## 5. 왜 기업은 API를 open 하는가?

```text
제공하는 기업에서는 자신들의 서비스 사용자가 늘어날 수 있는 새로운 기회가 된다. 
이미 만들어둔 기능을 최대한 많은 사람들이 많은 유저가 사용해 주는게 좋은데, 
신규 서비스가 자신들의 소프트웨어 프로그램을 써준다면 돈안쓰고 광고하는 셈이 되는 것이다.
물론 때로는 지나친 API 요청으로 인해 서버 부하가 심해지고 서버 비용 또한 많이 청구되기도 한다.
때문에 제공 기업측에서는 부분 유료화 모델, 하루에 API요청 제한 등의 장치를 마련하고 있다.
```



## 6. REST API의 가장 주요 특징 2가지는?

-  self-descriptive
-  HATEOAS



## 7. 구글 maps API 사용해보기

- 답안

```html
<iframe
  width="600"
  height="450"
  frameborder="0" style="border:0"
  src="https://www.google.com/maps/embed/v1/place?key={YOUR_KEY}
    &q=Multi-campus,Seoul" allowfullscreen>
</iframe>
```

