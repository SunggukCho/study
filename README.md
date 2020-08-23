# 실력있는 개발자 되기 study 커리큘럼

출처:

- 한재엽 개발자 github Technical Interview Guidelines for Beginners: https://github.com/JaeYeopHan/Interview_Question_for_Beginner

-  어썸인터뷰 https://github.com/MaximAbramchuck/awesome-interview-questions
- https://github.com/leencoln/2017-2018_Junior-Front-end-Interview-Question-List

- 경성대 양희재 교수님 운영체제 강의 http://www.kocw.net/home/search/kemView.do?kemId=978503

등 여러 개발자분들의 공개 자료들을 모아 자체적인 학습을 위해 따로 정리해두었습니다.



# Part 1. 💡 네트워크 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Network)

교재 위키독스: [Link](https://www.notion.so/2-6b8ff6efbc8f48c18bbe6f0372d9e93b#95a6708d19de43188a5e939143fb8ce5)

### 1주차 

- 프로토콜
  - TCP/IP
  - 라우터/라우팅

- 클라이언트/서버
  - WAS서버
  - DB서버
  - HTTP와 HTTPS

- 인터넷 쿠키와 세션

### 2주차 

- 실시간 통신: Polling / Long polling / Streaming / Websocket 개념

- API, OpenAPI

- RESTful API와 철학

- 프록시

- 토렌트, p2p개념

### 3주차 

- GET, POST 방식의 차이점
- 방화벽, 캐시서버
- DNS 와 round robin 방식
- CORS(Cross-Origin Resource Sharing)는 무엇인가
- Wireshark 는 무엇인가 



# Part 2. 💡 운영체제 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/OS)

경성대학교 양희재 교수님 운영체제 강의 듣기

http://www.kocw.net/home/search/kemView.do?kemId=978503

### 4주차  [Link](OS/os01.pdf)

- 고등 운영체제, 인터럽트 기반 운영체제
- 이중모드, 하드웨어 보호
- 운영체제 서비스
- 프로세스 관리

### 5주차 [Link](OS/os02.pdf)

- CPU 스케줄러
  - FCFS
  - SJF
  - SRT
  - Priority scheduling
  - RR

- CPU스케쥴링 알고리즘

### 6주차 [Link](OS/os03.pdf)

- 쓰레드(Thread)
- 프로세스 동기화
- 임계구역 문제
- 세마포
- 생산자-소비자 문제
- 동기화 문제

### 7주차

- 교착상태(Deadlock)
- 모니터

### 8주차 [Link](OS/os04.pdf)

- 주기억장치(메모리) 관리
- 메모리 절약
- 연속 메모리 할당

### 9주차 [Link](OS/os05.pdf)

- 페이징
- 세그먼테이션
- 가상 메모리

### 10주차 [Link](OS/os06.pdf)

- 프레임 할당
- 파일 할당
- 디스크 스케쥴링

## Part 3. 💡 정규표현식

### 11주차 [Link](https://wikidocs.net/4308)

- 정규표현식 시작하기 
  - 정규 표현식의 기초, 메타 문자
  - 파이썬에서 정규 표현식을 지원하는 re 모듈
  - 정규식을 이용한 문자열 검색
  - match 객체의 메서드
  - 컴파일 옵션
  - 백슬래시 문제

### 12주차 [Link](https://wikidocs.net/4309)

- 강력한 정규표현식
  - 그루핑
  - 전방탐색
  - 문자열 바꾸기
  - Greedy vs non- Greedy

---

### 13주차. 강의 들으면서 아래 질문에 대한 답변 토의하고 정리해두기

- 프로세스와 스레드의 차이
- 스케줄러의 종류

  - 장기 스케줄러
  - 단기 스케줄러
  - 중기 스케줄러
- CPU 스케줄러

  - FCFS
  - SJF
  - SRT
  - Priority scheduling
  - RR
- 동기와 비동기의 차이
- 멀티스레드

  - 장점과 단점
- 프로세스 동기화

  - Critical Section
  - 해결책
- 메모리 관리 전략

  - 메모리 관리 배경
  - Paging
  - Segmentation
- 가상 메모리

  - 배경
  - 가상 메모리가 하는 일
  - Demand Paging (요구 페이징)
  - 페이지 교체 알고리즘
- 캐시의 지역성

  - Locality
  - Caching line

<추가 사이트>

#### 정규식 짤 때 도움이 되는 사이트 - [regex101.com](https://regex101.com/)

#### 정규식에 대한 이해와 예제 사이트 - https://regexone.com/


---

아래 part4 & 5의 질문에 대한 답변은 주차별 스터디 내용에는 포함하지 않겠습니다. 

---

# Part4. 💡 개발상식 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Development_common_sense)

- 객체 지향 프로그래밍이란 무엇인가?

  - OOP에 특징에 대해 설명해달라(상속, 캡슐화 등등...)

- 함수형 프로그래밍에 대해 설명해달라

  - 함수형 프로그래밍에 개념에서 순수함수란 무엇인가
  - OOP와 함수형 프로그래밍의 가장 큰 차이점은 무엇인가

- RESTFul API 란?ㅜ

- TDD 란 무엇이며 어떠한 장점이 있는가?

- MVC 패턴이란 무엇인가?

- Git 과 GitHub 에 대해서

- 브라우저는 어떻게 동작하는가? http://d2.naver.com/helloworld/59361

  - 브라우저의 렌더링 과정에 대해서 상세하게 설명해달라

  

## 💡 개발외 질문 목록

- 왜 개발자가 되려고 하는가
- 개발자로서의 본인의 비전을 이야기 해달라
- 비전공자로써 갖고 있는 컴플렉스가 있는가
- 운영체제같은 컴퓨터공학(cs)에 대한 기초지식이 있는가
- 최근에 관심갖거나 공부 하고 싶은 개발 기술은 무엇인가
- 프로젝트 협업 과정을 경험한 적이 있는가
- 공부 방법
  - 개발자가 되기 위해서 어떻게 공부하였는가
  - 학습시 주로 이용하는 웹페이지나, 동영상 강좌 페이지는 어디인가
  - 최근의 읽은 개발 관련 서적은 무엇인가
  - 즐겨 보는 개발 관련 유튜브가 있는가
  - 회사 기술 스택에 맞추어 단기간 내에 언어와 프레임워크를 학습 하여야 할 때, 어떻게 공부하고 해결할 것인가
- 포트폴리오 제작시에 비인기 라이브러리를 사용한 경험이 있는가
- 이러한 비인기 라이브러리에 대한 정보를 어디서 얻는가 왜 활용하였는가
- XML/JSON 구조 살펴보기 https://wikidocs.net/22330
- https://kadamon.tistory.com/21