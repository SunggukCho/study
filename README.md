# 실력있는 개발자 되기 study 커리큘럼

출처:

- 한재엽 개발자 github Technical Interview Guidelines for Beginners: https://github.com/JaeYeopHan/Interview_Question_for_Beginner

-  어썸인터뷰 https://github.com/MaximAbramchuck/awesome-interview-questions
- https://github.com/leencoln/2017-2018_Junior-Front-end-Interview-Question-List

- 경성대 양희재 교수님 운영체제 강의 http://www.kocw.net/home/search/kemView.do?kemId=978503

등 여러 개발자분들의 공개 자료들을 모아 자체적인 학습을 위해 따로 정리해두었습니다.



# Part 1. 💡 자료구조 [Link](https://github.com/JaeYeopHan/for_beginner/tree/master/DataStructure)

### 1주차 [Link](data_structure/[자료구조_알고리즘]2-1주차_자료구조개요.pdf) [Link](data_structure/[자료구조_알고리즘]2-2주차_순차자료구조.pdf) [Link](data_structure/[자료구조_알고리즘]3_3주차_연결자료구조.pdf)

- 1. 자료구조 개요

  - 수치자료의 표현
  - 문자자료의 표현
  - 논리자료의 표현
  - 포인터 자료의 표현
  - 문자열 자료의 표현

- 2. 순차 자료 구조

  - 리스트
  - 1차원 배열
  - 2차원 배열
  - 3차원 배열
  - 순차자료구조의 문제점
  - Array vs Linked List

- 3. 연결 자료구조

  - 순차자료구조의 문제점과 연결자료구조
  - 노드의 이해
  - 선형 리스트와 연결 리스트의 비교
  - 원형 연결 리스트
  - 이중 연결 리스트
  - 이중 원형 연결 리스트

### 2주차 [Link](data_structure/[자료구조_알고리즘]4-6주차_스택.pdf) [Link](data_structure/[자료구조_알고리즘]7-8주차_큐.pdf)

- 4. 스택(Stack) 

  - 스택의 연산 - push, pop
  - 스택 구현
  - 스택의 장단점
  - 시스템 스택
  - 수식의 표기법

- 5. 큐(Queue)

  - 선형 큐 구조
  - 큐의 연산 - 삽입, 삭제
  - 큐의 검색
  - 포화상태
  - 원형 큐 구조
  - 원형 큐 - 삽입, 삭제
  - 연결 큐 - 삽입, 삭제

### 3주차 [Link](data_structure/[자료구조_알고리즘]10주차_트리.pdf)  [Link](data_structure/[자료구조_알고리즘]11주차_이진트리탐색.pdf)

- 6. 트리(Tree)

  - 이진트리(Binary Tree)
  - 포화이진트리(Full Binary Tree)
  - 완전이진트리(Complete Binary Tree)
  - 편향이진트리(Swkewed Binary Tree)
  - 이진트리의 순회(Binary Tree Traversal)
    - 전위순회 (preorder traversal)
    - 중위순회 (inorder traversal)
    - 후위순회 (postorder traversal)
  - 이진 탐색 트리 (Binary Search Tree)
    - 이진 탐색 트리 연산 - 삽입, 삭제
    - 후계자 선택 방법

- 힙 (Heap) 연산 - 삽입, 삭제

### 4주차 [Link](data_structure/[자료구조_알고리즘]12주차_그래프.pdf)

- Graph

  - Graph 개념, 종류
  - 인접 행렬, 인접 리스트
  - Graph 구현
  - Graph 탐색
    - 깊이 우선 탐색 (Depth First Search: DFS)
    - 너비 우선 탐색 (Breath First Search: BFS)
- Minimum Spanning Tree
    - Kruskal algorithm
    - Prim algorithm

### 5주차 

- Red-Black Tree

  - 정의
  - 특징
  - 삽입
  - 삭제
- 해시 테이블 (Hash Table)

  - Hash Function
  - Resolve Collision
    - Open Addressing
    - Separate Chaining
  - Resize

### 6주차 [Link](data_structure/동적계획법_설명.pdf)

- 동적 계획법
- 퀴즈 풀기
- XML/JSON 구조 살펴보기 https://wikidocs.net/22330

# Part 2. 💡 네트워크 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Network)

교재 위키독스: [Link](https://www.notion.so/2-6b8ff6efbc8f48c18bbe6f0372d9e93b#95a6708d19de43188a5e939143fb8ce5)

### 7주차 

- 프로토콜
  - TCP/IP
  - 라우터/라우팅

- 클라이언트/서버
  - WAS서버
  - DB서버
  - HTTP와 HTTPS

- 인터넷 쿠키와 세션

### 8주차 

- 폴링 방식과 이벤트 방식

- API, OpenAPI

- RESTful API와 철학

- 프록시

- 토렌트, p2p개념

### 9주차

- GET, POST 방식의 차이점
- TCP 3-way-handshake
- TCP 와 UDP 의 차이점
- DNS round robin 방식
- 웹 통신의 큰 흐름
- CORS(Cross-Origin Resource Sharing)는 무엇인가 왜 이러한 방법이 정의 되었으며, 본인이 코드를 작성하면서 CORS와 관련하여서 경험하였던 이슈는 무엇인가
- Wireshark 에 대해 알고 있는가



# Part 3. 💡 운영체제 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/OS)

경성대학교 양희재 교수님 운영체제 강의 듣기

http://www.kocw.net/home/search/kemView.do?kemId=978503

### 10주차  [Link](OS/os01.pdf)

- 고등 운영체제, 인터럽트 기반 운영체제
- 이중모드, 하드웨어 보호
- 운영체제 서비스
- 프로세스 관리

### 11주차 [Link](OS/os02.pdf)

- CPU 스케줄러
  - FCFS
  - SJF
  - SRT
  - Priority scheduling
  - RR

- CPU스케쥴링 알고리즘

### 12주차 [Link](OS/os03.pdf)

- 쓰레드(Thread)
- 프로세스 동기화
- 임계구역 문제
- 세마포
- 생산자-소비자 문제
- 동기화 문제

### 13주차

- 교착상태(Deadlock)
- 모니터

### 14주차 [Link](OS/os04.pdf)

- 주기억장치(메모리) 관리
- 메모리 절약
- 연속 메모리 할당

### 15주차 [Link](OS/os05.pdf)

- 페이징
- 세그먼테이션
- 가상 메모리

### 16주차 [Link](OS/os06.pdf)

- 프레임 할당
- 파일 할당
- 디스크 스케쥴링

---

### 17주차. 강의 들으면서 아래 질문에 대한 답변 토의하고 정리해두기

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


---

아래 part4 & 5의 질문에 대한 답변은 주차별 스터디 내용에는 포함하지 않겠습니다. 

---

# Part4. 💡 개발상식 [Link](https://github.com/JaeYeopHan/Beginner_for_interview/tree/master/Development_common_sense)

- 객체 지향 프로그래밍이란 무엇인가?

  - OOP에 특징에 대해 설명해달라(상속, 캡슐화 등등...)

- 함수형 프로그래밍에 대해 설명해달라

  - 함수형 프로그래밍에 개념에서 순수함수란 무엇인가
  - OOP와 함수형 프로그래밍의 가장 큰 차이점은 무엇인가

- RESTFul API 란?

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

  