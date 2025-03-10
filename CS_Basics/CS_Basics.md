## 목차
1. [자료구조](#코드-원리)
- [작동하는 코드](#작동만하는-코드-vs-제대로-작동하는-코드)
- [기본-CS](#프로그램의-원리를-이해하기-위한-computer-science)
2. [과학지도](#과학-지도)
- [컴퓨터-과학은-암기가-아니다](#컴퓨터-과학은-암기-과목이-아니다)
- [책-목차](#책-목차)

## 코드 원리
---
- 프로그램 개발 : 작동이 가능한 프로그램 만들기
- 궁극적인 목표 : 작동하게 만드는 것도 중요하지만, 제대로 작동하게 만드는 것이 궁극적 목표

### 작동'만'하는 코드 vs 제대로 작동하는 코드
---
- 일단 작동만 하도록 만드는 코드는 확실히 쉬워 보이지만, 프로그램 사용자가 생기고 유지보수까지 고려해야 하는 때가 온다면 **겉보기에만 작동하는 것 처럼** 보이는 문제가 발생하고, 이에 따라 버그가 발생할 수 있다.
- 예제 소스 코드를 찾아 복사 붙여넣기 방식으로 문제를 해결하게 되는데, 이러한 작업이 반복된다면 소스 코드는 점점 복잡해지고 미궁속으로 빠지게 된다. 이를 **스파게티 코드** 라고 한다.
- 생성형 AI를 가지고 해결을 한다고 한들 언제나 일관되고 정확한 진단을 하지 않기 때문에 이러한 개발 방법은 오히려 더 어려운 코드를 만드는 원흉이 되기도 한다.
- 뛰어난 개발자는 자신이 작성한 코드가 어떤 과정을 거쳐 실행되는지 명확하고 자세하게 설명할 수 있다. 즉, 문제를 정의하고 해결하는 역량은 프로그램의 실행을 제대로 이해하고 프로그램이 어떠한 과정을 거쳐 실행되는지를 정확하게 설명하는 것이 역량이라고 볼 수 있다.

### 프로그램의 원리를 이해하기 위한 Computer Science
---
- CS : Computer Science라고도 하며, 이는 컴퓨터 과학이라고 한다. 단순 프로그래밍 언어 기초 문법을 포함하여 프레임워크/라이브러리 사용법, 작동 원리를 알기 위해서 기본적으로 알아야 하는 지식이다.

## 과학 지도
---
- 컴퓨터 과학에 대해서 자세히 알고 싶다면 큰 그림을 그리는 것이 중요하다. 이를 알기 위해 컴퓨터 과학 지도를 그려보는 방식도 굉장히 좋다.

### 컴퓨터 과학은 암기 과목이 아니다.
---
- 컴퓨터 과학 지식 학습 목적은 이해와 적용이며, 실무를 위한 개발의 재료를 얼마나 갖추고 있는지에 대해 알아볼 수 있는 지식이다.
- 암기만 했다면 다양한 꼬리물기에 대한 답변도 어려울 것이며, 모든 개념을 알고 있다고 하기에도 많이 부족할 것이다. 그렇기 때문에 프로그램의 실행 원리를 이해하는 것이 실무에도 도움이 되며 이것이 컴퓨터 과학과 한 층 더 가까워 질 수 있는 방향이다.

### 책 목차
---
1. 컴퓨터 구조
- 컴퓨터가 이해하는 정보 (데이터와 명령어), 핵심 부품(CPU, 메모리, 캐시메모리, 보조기억장치, 입출력장치 등)
2. 운영체제
- OS라고 부르기도 하며 윈도우, 맥 OS, Linux, Android, iOS와 같은 프로그램들을 의미한다.
- 커널, 시스템 콜, 프로세스, 스레드, CPU 스케쥴링, 가상 메모리, 파일 시스템 등
3. 자료구조
- 자료를 효율적으로 관리하는 구조적 방법, 즉 데이터를 효율적으로 관리할 수 있는 방법
- 시간 복잡도, 공간 복잡도, 배열, 연결 리스트, 스택, 큐, 해시 테이블, 트리, 그래프 + 알고리즘 등에 대해서 공부
4. 네트워크
- 개발자가 만들고 실행하는 대부분의 프로그램이 서로 통신을 주고 받으며 실행하는 부분에 대해서 학습한다.
- 계층적인 구조 (OSI 7계층, TCP/IP 4계층), 프로토콜 (IP, TCP, UDP, HTTP 등), 프록시, 트래픽 다루기 등
5. 데이터베이스
- DBMS, 데이터베이스, 엔티티, 스키마, 트랜잭션, ACID 원칙, RDBMS, NoSQL 등 데이터베이스에 대한 구조