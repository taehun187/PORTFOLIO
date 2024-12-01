# 클라우드 AI 서비스 훈련과정 
[과정 소개](https://hrd.work24.go.kr/hrdp/co/pcobo/PCOBO0100P.do?tracseId=AIG20230000412830&tracseTme=3&crseTracseSe=C0061&trainstCstmrId=500020048147#undefined)

## 자바 교육

---

### **1주차: 자바 기본**
**목표:** 자바의 기초 문법 이해 및 환경 설정  

#### **Day 1: 개발 환경 설정과 첫 프로그램**
- JDK와 IDE 설치 (IntelliJ IDEA, Eclipse)
- Hello World 프로그램 작성
- JDK, JRE, JVM의 역할 이해

#### **Day 2: 데이터 타입과 변수**
- 기본 데이터 타입과 변수 선언
- 리터럴과 형 변환 (암시적/명시적)
- 상수와 `final` 키워드

#### **Day 3: 연산자**
- 산술, 비교, 논리 연산자
- 증감 연산자와 삼항 연산자
- 연산자 우선순위

#### **Day 4: 조건문**
- if-else와 중첩 조건문
- switch-case의 사용법
- 조건문을 활용한 간단한 계산기 작성

#### **Day 5: 반복문**
- for, while, do-while의 차이점
- break와 continue 사용법
- 이중 반복문과 실습 문제

#### **Day 6: 배열**
- 1차원 및 다차원 배열 선언과 초기화
- 배열과 반복문 활용
- 배열 요소의 합과 평균 계산하기

#### **Day 7: 실습**
- 숫자 맞히기 게임 (배열과 조건문 활용)

---

### **2주차: 객체지향 프로그래밍 (OOP)**
**목표:** 객체지향 개념과 클래스 사용법 학습  

#### **Day 1: 클래스와 객체**
- 클래스 정의 및 객체 생성
- 필드와 메서드 사용
- `this` 키워드 이해

#### **Day 2: 생성자와 초기화**
- 기본 생성자와 매개변수 생성자
- 생성자 오버로딩
- 초기화 블록 (인스턴스 및 정적 초기화)

#### **Day 3: 메서드와 캡슐화**
- 메서드의 매개변수와 반환값
- 접근 제어자 (`public`, `private`, `protected`)
- getter와 setter 메서드로 캡슐화 구현

#### **Day 4: 상속**
- 클래스 상속 (extends)
- 메서드 오버라이딩
- `super` 키워드 활용

#### **Day 5: 다형성**
- 업캐스팅과 다운캐스팅
- 추상 클래스와 인터페이스
- 다형성의 장점과 활용 예제

#### **Day 6: 디자인 패턴 1: 싱글톤(Singleton)**
- 싱글톤 패턴의 개념 및 구현
  - Lazy Initialization, Thread-safe Singleton
- 프로젝트에 설정 관리 객체로 싱글톤 패턴 적용

#### **Day 7: 실습**
- 은행 계좌 관리 시스템
- 상속과 다형성 활용, 싱글톤으로 설정 클래스 구현

---

### **3주차: 자바 심화**
**목표:** 자바의 고급 문법과 프레임워크 활용  

#### **Day 1: 예외 처리**
- try-catch-finally
- throws 키워드
- 사용자 정의 예외 작성

#### **Day 2: 제너릭 (1)**
- 제너릭의 기본 개념
- 타입 안정성과 재사용성
- 제너릭 클래스와 메서드 작성

#### **Day 3: 컬렉션 프레임워크**
- List, Set, Map 인터페이스 소개
- ArrayList, HashSet, HashMap 사용법
- Iterator와 for-each 활용

#### **Day 4: 디자인 패턴 2: 팩토리(Factory)**
- 팩토리 메서드 패턴 개념
  - 객체 생성 로직 분리
- 프로젝트에 팩토리 클래스 추가
  - `Book` 객체 생성 로직을 팩토리로 분리

#### **Day 5: 파일 입출력**
- File 클래스와 파일 다루기
- FileReader와 FileWriter
- BufferedReader와 BufferedWriter

#### **Day 6: 스트림과 람다 표현식**
- Stream API 개념
- filter, map, collect 메서드
- 람다 표현식과 함수형 인터페이스

#### **Day 7: 실습**
- 멀티쓰레드와 파일 입출력을 활용한 병렬 처리 프로그램
- 팩토리 패턴과 스트림을 활용한 정렬 기능 추가

---

### **4주차: 디자인 패턴 통합 및 프로젝트**
**목표:** 학습한 디자인 패턴과 자바 문법을 프로젝트에 종합 적용  

#### **Day 1: 프로젝트 설계**
- 도서 관리 프로그램의 기능 명세 작성
- 주요 클래스 다이어그램 작성

#### **Day 2: 디자인 패턴 3: 전략(Strategy)**
- 전략 패턴의 개념 및 구현
  - 런타임에 정렬 전략 동적 교체
- 도서 정렬 기준(제목, 저자, 연도)을 전략 패턴으로 변경

#### **Day 3: CRUD 기능 구현**
- 책 추가, 수정, 삭제, 조회 기능 구현
- 검색 조건 추가 (제목, 저자, 출판 연도)

#### **Day 4: 예외 처리와 데이터 저장**
- 입력값 검증과 예외 처리 추가
- 파일 입출력을 통해 데이터 저장 및 불러오기 구현

#### **Day 5: 디자인 패턴 4: 옵저버(Observer)**
- 옵저버 패턴 구현
  - 책 대출 상태 변경 시 알림 전송
- 옵저버 패턴을 프로젝트에 통합

#### **Day 6: 테스트 및 디버깅**
- 유닛 테스트 작성
- 코드 리팩토링 및 오류 수정

#### **Day 7: 프로젝트 발표 및 복습**
- 프로젝트 완성본 정리
- 학습한 디자인 패턴과 주요 개념 복습

---

### **결과물 예시**
- 프로젝트: **도서 관리 시스템**
  - **적용된 디자인 패턴:** 싱글톤, 팩토리, 전략, 옵저버
  - **기능:** CRUD, 정렬, 대출 상태 관리, 알림 기능


## Database 교육 및 JDBC API 실습습
---

### **1주차: Database 기초와 실습**

#### **Day 1: 데이터베이스 기본 개념**
- 데이터베이스의 정의와 역할
- RDBMS와 NoSQL의 차이점
- 기본 SQL 문법 소개
  - `SELECT`, `INSERT`, `UPDATE`, `DELETE`
- 실습:
  - SQLite 또는 MySQL 설치 및 데이터베이스 생성
  - 간단한 테이블 생성과 데이터 삽입

#### **Day 2: SQL 심화**
- 테이블 설계 및 데이터 타입
  - 주요 데이터 타입 (`INT`, `VARCHAR`, `DATE` 등)
- 제약 조건
  - `PRIMARY KEY`, `FOREIGN KEY`, `UNIQUE`, `NOT NULL`
- JOIN 문
  - `INNER JOIN`, `LEFT JOIN`, `RIGHT JOIN`, `FULL JOIN`
- 실습:
  - 관계형 데이터 설계 (예: 사용자와 주문 테이블)
  - JOIN을 활용한 데이터 조회

#### **Day 3: 인덱스와 성능**
- 인덱스의 개념과 중요성
  - 클러스터링 인덱스와 비클러스터링 인덱스
- 트랜잭션과 ACID 특성
  - `COMMIT`, `ROLLBACK`
- 실습:
  - 테이블에 인덱스 추가
  - 트랜잭션을 사용한 데이터 변경

#### **Day 4: ERD 설계**
- ERD(Entity-Relationship Diagram)의 개념
- 관계형 모델링 (1:1, 1:N, N:M 관계)
- 실습:
  - MySQL Workbench 또는 dbdiagram.io를 사용한 ERD 설계
  - 설계한 ERD를 기반으로 테이블 생성

#### **Day 5: 고급 SQL**
- 서브쿼리와 집계 함수
  - `COUNT`, `AVG`, `SUM`, `GROUP BY`, `HAVING`
- 윈도우 함수
  - `ROW_NUMBER`, `RANK`, `PARTITION BY`
- 실습:
  - 집계 및 윈도우 함수를 활용한 데이터 분석 쿼리 작성

#### **Day 6: 데이터베이스와 Java 연동**
- JDBC 개념과 기본 사용법
- Spring Data JPA 개요
  - JPA와 Hibernate의 차이
  - ORM(Object-Relational Mapping)의 기본 개념
- 실습:
  - 간단한 Java 애플리케이션에서 JDBC로 데이터베이스 연결

#### **Day 7: 복습 및 정리**
- 데이터베이스 설계 및 SQL 복습
- 주요 개념 정리 및 Q&A

---

## Git 교육

---

### **Day 1: Git 기본 개념과 로컬 저장소 관리**

#### **이론: Git 개요**
1. **Git의 개념**
   - 버전 관리 시스템(VCS)이란 무엇인가?
   - Git의 특징과 장점
   - Git과 다른 VCS(SVN, Mercurial) 비교
2. **Git 설치 및 초기 설정**
   - Git 설치
   - 사용자 정보 설정 (`git config --global user.name`, `git config --global user.email`)
   - Git 주요 명령어 소개

#### **실습: 로컬 저장소 관리**
1. **Git 저장소 생성 및 초기화**
   - 새로운 Git 저장소 생성 (`git init`)
   - 기존 프로젝트를 Git 저장소로 전환
2. **파일 추가 및 변경 관리**
   - 파일 추적 상태 확인 (`git status`)
   - 파일 스테이징 및 커밋 (`git add`, `git commit`)
3. **Git 로그 및 파일 이력 확인**
   - 커밋 로그 확인 (`git log`, `git log --oneline`)
   - 특정 파일의 변경 이력 확인 (`git blame`)

---

### **Day 2: 브랜치와 협업**

#### **이론: 브랜치의 역할과 중요성**
1. **Git 브랜치의 개념**
   - 브랜치를 사용하는 이유와 장점
   - Git의 기본 브랜치 모델 (`main`, `feature`, `develop`)
2. **브랜치 작업 흐름**
   - 브랜치 생성, 전환, 병합
   - Fast-Forward와 3-way 병합의 차이

#### **실습: 브랜치 관리**
1. **브랜치 생성 및 병합**
   - 새 브랜치 생성 및 전환 (`git branch`, `git checkout`)
   - 병합 과정 실습 (`git merge`)
2. **충돌 해결**
   - 충돌 상황 생성 및 해결 방법
   - 병합 충돌 해결 후 커밋
3. **브랜치 삭제**
   - 로컬 브랜치 삭제 (`git branch -d`, `git branch -D`)

---

### **Day 3: 원격 저장소와 협업**

#### **이론: 원격 저장소**
1. **Git 원격 저장소의 개념**
   - 로컬 저장소와 원격 저장소의 차이점
   - 주요 원격 저장소 서비스(GitHub, GitLab, Bitbucket 등)
2. **Git 원격 명령어**
   - `git remote add`, `git push`, `git pull`, `git fetch`
   - 로컬 브랜치와 원격 브랜치의 관계

#### **실습: 협업 시나리오**
1. **원격 저장소 연결**
   - GitHub에 저장소 생성 및 연결 (`git remote add origin`)
   - 로컬 저장소를 원격으로 푸시 (`git push`)
2. **원격 작업**
   - 원격 브랜치 가져오기 (`git fetch`, `git pull`)
   - 원격 브랜치로 변경 사항 푸시 (`git push`)
3. **Fork와 Pull Request**
   - 다른 저장소를 포크(Fork)하여 작업
   - 변경 사항을 Pull Request로 제출
4. **실제 협업 시뮬레이션**
   - 팀원 간 브랜치 병합 및 충돌 해결 실습

---

### **결과물**
1. **Git 로컬 작업**
   - 파일 버전 관리, 커밋 이력 확인, 브랜치 활용 능력
2. **Git 원격 협업**
   - 원격 저장소 설정, 변경 사항 푸시 및 병합
3. **실제 협업 시나리오**
   - 브랜치와 Pull Request를 활용한 팀 협업 경험

---


## Spring Framework 
---

### **1주차: Spring Framework 기초**
**목표:** Spring Framework의 기본 개념과 환경 설정 익히기  

#### **Day 1: Spring Framework 소개**
- Spring Framework의 특징과 아키텍처
- Spring Boot와의 차이점
- Spring 모듈: IoC, AOP, Data, MVC 등 개요

#### **Day 2: Spring 프로젝트 설정**
- Maven/Gradle 기반 Spring 프로젝트 생성
- IntelliJ IDEA 또는 Eclipse로 프로젝트 설정
- 기본 Spring 의존성 추가 (spring-context, spring-beans)

#### **Day 3: Spring Bean과 ApplicationContext**
- Spring Bean의 개념과 역할
- `ApplicationContext`와 `BeanFactory` 차이점
- XML 및 Java Config로 Bean 등록

#### **Day 4: Bean Lifecycle**
- Spring Bean의 생성 및 소멸 과정
- 초기화 및 소멸 메서드 설정 (`@PostConstruct`, `@PreDestroy`)
- Bean Scope (`singleton`, `prototype` 등)

#### **Day 5: 의존성 주입 (DI)**
- DI의 개념과 이점
- Setter Injection vs Constructor Injection
- `@Autowired`와 `@Qualifier` 사용법

#### **Day 6: 실습**
- 간단한 도서 관리 애플리케이션 구현
  - Bean으로 Service와 Repository 계층 분리
  - 의존성 주입 활용

#### **Day 7: 복습 및 정리**
- 이론 복습 및 주요 개념 정리
- 실습 코드 리뷰 및 개선

---

### **2주차: Spring IoC 심화**
**목표:** IoC 컨테이너와 고급 DI 패턴 익히기  

#### **Day 1: IoC 컨테이너 구조**
- IoC 컨테이너의 내부 동작 방식
- Bean Definition과 Bean Factory Post Processor
- Lazy Initialization과 Eager Initialization

#### **Day 2: 프로파일(Profile) 설정**
- Spring 프로파일의 개념
- `@Profile`을 사용한 환경별 Bean 설정
- YAML/Properties로 환경 설정 관리

#### **Day 3: Bean Post Processor와 이벤트**
- BeanPostProcessor의 역할
- ApplicationContext 이벤트 (`ContextRefreshedEvent`, `ContextClosedEvent`)
- 사용자 정의 이벤트와 리스너 구현

#### **Day 4: Spring Expression Language (SpEL)**
- SpEL의 기본 문법
- Bean 속성 접근과 표현식 활용
- 조건부 로직 및 계산식 작성

#### **Day 5: Java Config와 Component Scan**
- `@Configuration`과 `@Bean`으로 Java Config 작성
- Component Scan 설정 (`@Component`, `@Service`, `@Repository`)
- `@Lazy`, `@Primary` 활용

#### **Day 6: 실습**
- IoC 컨테이너 활용한 사용자 관리 애플리케이션 구현
  - `@Profile`로 개발/운영 환경 분리
  - BeanPostProcessor 활용

#### **Day 7: 복습 및 정리**
- IoC 컨테이너 동작 원리 복습
- 실습 프로젝트 코드 리뷰

---

### **3주차: Spring AOP**
**목표:** AOP 개념과 활용법 익히기  

#### **Day 1: AOP 개념**
- AOP의 핵심 개념 (Aspect, Join Point, Advice, Pointcut)
- Spring AOP vs AspectJ

#### **Day 2: AOP 설정**
- AOP 의존성 추가
- XML 및 Java Config로 AOP 설정
- `@EnableAspectJAutoProxy` 이해

#### **Day 3: Advice 종류**
- `@Before`, `@After`, `@AfterReturning`, `@AfterThrowing`, `@Around` 사용법
- 각 Advice의 실행 순서와 활용 예

#### **Day 4: Pointcut 표현식**
- Pointcut 표현식 문법
- 특정 메서드, 클래스, 패키지 지정
- 복합 조건 작성

#### **Day 5: AOP 활용 사례**
- 로깅, 트랜잭션 관리, 메서드 실행 시간 측정
- AOP를 활용한 권한 검사 구현

#### **Day 6: 실습**
- AOP로 로깅 및 실행 시간 측정 기능 추가
  - Service 계층 메서드에 `@Around` 적용
  - 예외 발생 시 추가 로깅 구현

#### **Day 7: 복습 및 정리**
- AOP 개념과 설정 복습
- 실습 프로젝트에 AOP 기능 통합 및 개선

---

### **4주차: JUnit 5**
**목표:** 단위 테스트와 통합 테스트 작성  

#### **Day 1: JUnit 5 소개**
- JUnit 5의 구조 (`JUnit Platform`, `JUnit Jupiter`, `JUnit Vintage`)
- JUnit 4와 JUnit 5의 차이점
- Maven/Gradle에 JUnit 5 의존성 추가

#### **Day 2: 기본 테스트 작성**
- 테스트 메서드 작성 (`@Test`)
- `@BeforeEach`, `@AfterEach`와 테스트 준비/정리
- `@BeforeAll`, `@AfterAll`로 전역 설정

#### **Day 3: Assertions와 조건부 테스트**
- 주요 Assertions (`assertEquals`, `assertNotNull`, `assertThrows` 등)
- 조건부 테스트 (`@EnabledIf`, `@DisabledIf`)
- 타임아웃 테스트 (`@Timeout`)

#### **Day 4: 테스트 더블과 Mocking**
- Mockito를 활용한 Mock 객체 생성
- `@Mock`, `@InjectMocks`로 의존성 주입
- Service 계층 단위 테스트 작성

#### **Day 5: Spring과의 통합 테스트**
- `@SpringBootTest`로 컨텍스트 로딩 테스트
- `@WebMvcTest`로 컨트롤러 테스트
- `@DataJpaTest`로 Repository 테스트

#### **Day 6: 실습**
- 도서 관리 시스템 단위 테스트 작성
  - Service와 Repository 계층 테스트
  - Mockito를 사용한 Mocking

#### **Day 7: 복습 및 정리**
- JUnit 5의 주요 기능 복습
- 전체 프로젝트에 테스트 코드 통합

---

### **결과물**
1. IoC와 DI를 활용한 도서 관리 시스템  
   - **기능:** 도서 CRUD, 사용자 관리  
   - **적용 기술:** Spring IoC, AOP, JUnit 5

2. AOP를 활용한 로깅 및 권한 관리  
   - **기능:** 메서드 실행 시간 측정, 예외 로깅, 권한 체크  

3. JUnit 5를 활용한 철저한 테스트  
   - **단위 테스트:** Service, Repository 계층  
   - **통합 테스트:** Spring 컨텍스트와 함께 실행  

---


## Network 교육 및 프런트엔드 프로그래밍 언어 교육
---

### **1주차: 네트워크, TCP/IP 4계층 모델, HTTP 프로토콜**

#### **Day 1: 네트워크 기본 개념**
- 네트워크의 정의와 동작 원리
  - 클라이언트-서버 모델, P2P 네트워크
- 네트워크 구성 요소
  - 허브, 스위치, 라우터
- 실습: `ping`, `traceroute` 명령어 사용 및 네트워크 상태 점검

#### **Day 2: TCP/IP 4계층 모델 개요**
- TCP/IP 4계층 모델 소개
  - 애플리케이션, 전송, 인터넷, 네트워크 액세스 계층의 역할
- TCP와 UDP 비교
  - TCP 3-way Handshake, UDP의 특성
- 실습: Wireshark로 TCP/UDP 패킷 캡처 및 분석

#### **Day 3: 인터넷 계층과 전송 계층 심화**
- 인터넷 계층: IP 주소, 서브넷 마스크, ICMP
- 전송 계층: TCP 연결 관리와 흐름 제어
- 실습: Wireshark를 활용한 패킷 분석 (HTTP 패킷 캡처)

#### **Day 4: HTTP 프로토콜 기초**
- HTTP와 HTTPS의 차이
- HTTP 요청(Request)와 응답(Response)의 구조
  - 메서드(GET, POST, PUT, DELETE), 상태 코드(200, 404, 500)
- 실습: Postman으로 HTTP 요청/응답 실습

#### **Day 5: HTTP 헤더와 쿠키/세션**
- HTTP 헤더의 역할과 주요 필드
  - Content-Type, Authorization, Cache-Control
- 쿠키와 세션의 차이와 동작 방식
- 실습: 브라우저 개발자 도구로 HTTP 요청 분석

#### **Day 6: HTTPS와 TLS/SSL**
- HTTPS의 원리와 TLS/SSL 인증서
- 공인 인증서와 개인키의 역할
- 실습: HTTPS 웹사이트의 인증서 세부 정보 확인

#### **Day 7: 복습 및 네트워크 통합 실습**
- TCP/IP 모델과 HTTP 프로토콜의 상관관계 복습
- Wireshark를 활용해 전체 네트워크 트래픽 분석

---

### **2주차: 아파치 톰캣 서버와 웹 기본 기술 (HTML/CSS/JavaScript)**

#### **Day 1: 아파치 톰캣 소개 및 설치**
- 아파치 톰캣의 역할과 구조
  - Catalina, Coyote, Jasper의 역할
- 톰캣 서버 설치 및 환경 설정
- 실습: 톰캣 기본 애플리케이션 실행

#### **Day 2: 톰캣 서버 설정과 서블릿**
- 톰캣 구성 파일(`server.xml`, `web.xml`) 이해
- 서블릿 컨테이너와 요청/응답 흐름
- 실습: 간단한 서블릿 작성 및 배포

#### **Day 3: HTML 기초**
- HTML 문서 구조와 주요 태그
  - `<head>`, `<body>`, `<div>`, `<span>`, `<a>`, `<img>`
- 폼 태그와 입력 요소
  - `<form>`, `<input>`, `<button>`
- 실습: 간단한 HTML 페이지 작성

#### **Day 4: CSS 기초**
- CSS 선택자와 속성
  - 클래스(`.`), 아이디(`#`), 태그 선택자
- 레이아웃 구성
  - 박스 모델, Flexbox, Grid
- 실습: 간단한 페이지 스타일링

#### **Day 5: JavaScript 기초**
- JavaScript 기본 문법
  - 변수, 조건문, 반복문
- DOM(Document Object Model) 조작
  - `document.querySelector()`, `addEventListener()`
- 실습: 버튼 클릭 시 텍스트 변경 기능 구현

#### **Day 6: HTTP와 톰캣 통합 실습**
- 서블릿으로 HTTP 요청 처리
- HTML, CSS, JavaScript를 서블릿과 연계
- 실습: 간단한 동적 웹 애플리케이션 작성

#### **Day 7: 복습 및 프로젝트**
- 톰캣과 HTTP, HTML/CSS/JavaScript 통합 복습
- 프로젝트: 간단한 사용자 관리 페이지 작성

---

### **3주차: React 심화 학습 및 프로젝트**

#### **Day 1: React 기본 개념**
- React의 개요와 특징
  - 컴포넌트 기반 개발, 가상 DOM
- React 프로젝트 생성
  - `create-react-app`을 사용하여 프로젝트 생성
- 실습: React 개발 환경 설정 및 첫 컴포넌트 작성

#### **Day 2: JSX와 컴포넌트**
- JSX 문법 이해
- 함수형 컴포넌트와 클래스형 컴포넌트
- Props와 State의 차이점
- 실습: 컴포넌트를 활용한 간단한 목록 렌더링

#### **Day 3: 이벤트와 상태 관리**
- 이벤트 처리
  - `onClick`, `onChange` 등
- 상태 관리
  - `useState` Hook의 사용법
- 실습: 입력 폼 데이터를 처리하는 컴포넌트 작성

#### **Day 4: React Router**
- React Router의 기본 개념
  - `BrowserRouter`, `Route`, `Link`
- 페이지 간 내비게이션 구현
- 실습: 간단한 다중 페이지 애플리케이션 작성

#### **Day 5: HTTP와 React 연동**
- Fetch API와 Axios를 사용한 HTTP 요청
- React에서 REST API와 연계
- 실습: JSONPlaceholder를 활용한 데이터 가져오기 및 렌더링

#### **Day 6: 프로젝트: React와 톰캣 연계**
- React를 활용한 프런트엔드 구현
- 톰캣에서 REST API로 데이터 제공
- 실습: 간단한 CRUD 웹 애플리케이션 완성

#### **Day 7: 복습 및 최종 프로젝트 발표**
- React, 톰캣, HTTP, 네트워크 주요 개념 복습
- 최종 프로젝트 발표:
  - React로 만든 프런트엔드와 톰캣 백엔드를 연계한 웹 애플리케이션

---

### **결과물**
1. **프로젝트:** React와 톰캣을 연계한 CRUD 웹 애플리케이션
   - **백엔드:** 톰캣에서 REST API 제공
   - **프런트엔드:** React로 데이터 처리 및 렌더링
2. **핵심 기술 습득**
   - 네트워크 및 TCP/IP 4계층 모델의 원리
   - HTTP 프로토콜과 HTTPS의 동작 방식
   - HTML, CSS, JavaScript, React를 활용한 프런트엔드 개발
   - 아파치 톰캣 서버를 활용한 백엔드 구현

---


## Spring Framework의 Web on Servlet Stack 교육육

---

### **Day 1: Spring Web MVC 개요와 설정**
**목표:** Spring Web MVC의 기본 개념과 환경 설정 익히기

#### 이론:
1. **Spring Web MVC 개념**
   - Web on Servlet Stack의 정의와 특징
   - DispatcherServlet의 역할
   - Spring MVC의 요청 처리 흐름
     - DispatcherServlet → HandlerMapping → Controller → ViewResolver
2. **프로젝트 설정**
   - Maven/Gradle을 사용한 Spring Web MVC 프로젝트 생성
   - 필수 의존성 추가 (`spring-webmvc`, `javax.servlet-api` 등)

#### 실습:
1. 간단한 Spring MVC 프로젝트 생성
2. DispatcherServlet 등록
   - `web.xml` 또는 Java Config 기반 등록
3. 간단한 컨트롤러 작성 및 요청 처리
   - `@Controller`와 `@RequestMapping` 사용
4. Hello World 응답 출력

---

### **Day 2: 컨트롤러와 데이터 처리**
**목표:** Spring MVC에서 데이터 전달 및 요청 처리 메커니즘 이해

#### 이론:
1. **컨트롤러 동작 원리**
   - `@RequestMapping`을 사용한 URL 매핑
   - HTTP 메서드 매핑 (`GET`, `POST`, `PUT`, `DELETE`)
   - `@PathVariable`, `@RequestParam`을 사용한 요청 데이터 처리
2. **모델과 데이터 전달**
   - `Model`과 `ModelAndView`의 차이
   - `@ModelAttribute`를 활용한 데이터 바인딩

#### 실습:
1. 사용자 데이터를 처리하는 컨트롤러 작성
   - URL 매핑: `/users/{id}` (PathVariable 활용)
   - Form 데이터 처리: `@RequestParam`으로 입력 값 수집
2. 응답 데이터 전달
   - `Model`을 사용해 데이터 추가
   - ViewResolver로 데이터를 JSP에 출력

---

### **Day 3: View와 Form 처리**
**목표:** Spring MVC의 ViewResolver와 Form 데이터 처리 익히기

#### 이론:
1. **ViewResolver 개념**
   - ViewResolver의 역할과 설정
   - JSP를 활용한 View 생성 (`InternalResourceViewResolver`)
2. **Form 처리**
   - `@ModelAttribute`를 사용한 객체 바인딩
   - `BindingResult`를 활용한 입력 값 검증
   - Spring의 폼 태그 라이브러리 (`<form:input>`, `<form:errors>`)

#### 실습:
1. ViewResolver 설정
   - JSP 디렉토리와 확장자 설정
2. 간단한 회원가입 폼 작성
   - HTML 폼에서 사용자 입력 받기
   - `@ModelAttribute`로 폼 데이터 바인딩
   - 입력 값 검증 로직 추가

---

### **Day 4: 예외 처리와 파일 업로드**
**목표:** Spring MVC의 예외 처리와 파일 업로드 메커니즘 익히기

#### 이론:
1. **예외 처리**
   - Spring MVC의 예외 처리 전략
   - `@ExceptionHandler`를 사용한 로컬 예외 처리
   - `@ControllerAdvice`를 사용한 전역 예외 처리
2. **파일 업로드**
   - MultipartResolver 설정
   - 파일 업로드 처리 흐름
   - 업로드된 파일 저장 및 검증

#### 실습:
1. 예외 처리 구현
   - 특정 컨트롤러에서 `@ExceptionHandler` 적용
   - 전역 예외 처리를 위한 `@ControllerAdvice` 설정
2. 파일 업로드 기능 구현
   - MultipartResolver 등록
   - 업로드된 파일 저장 및 확인

---

### **Day 5: 인터셉터와 필터**
**목표:** Spring MVC에서 요청 처리 흐름을 제어하는 인터셉터와 필터 사용법 익히기

#### 이론:
1. **인터셉터 (HandlerInterceptor)**
   - `HandlerInterceptor`의 역할과 동작
   - PreHandle, PostHandle, AfterCompletion의 활용
2. **필터**
   - Servlet 필터와 Spring의 차이점
   - 필터 체인 설정과 활용
3. **응용**
   - 인증/인가 로직 구현
   - 요청 로깅

#### 실습:
1. 인터셉터 구현
   - 요청 URI를 로깅하는 PreHandle 작성
   - 컨트롤러 처리 후 특정 작업 수행 (PostHandle)
2. 필터 구현
   - Servlet Filter로 요청 IP 확인 및 로깅
   - 인증 검증을 추가하여 특정 URL 보호

---

### **결과물**
1. **기본 Spring Web MVC 애플리케이션**
   - 요청 처리: 컨트롤러, 모델, ViewResolver 설정
   - 데이터 바인딩과 유효성 검사
2. **회원 관리 시스템**
   - 회원 등록/수정/삭제 기능
   - 폼 데이터 처리 및 유효성 검사
   - 예외 처리 및 파일 업로드 기능
3. **인터셉터와 필터**
   - 요청 로깅, 인증/인가 적용

---

## Spring Boot Auto Configuration 교육

---

### **Day 1: Auto Configuration의 개념과 동작 원리**

#### **이론: Auto Configuration의 기본 개념**
1. **Spring Boot Auto Configuration 소개**
   - Auto Configuration이란 무엇인가?
   - 기존 Spring Framework와의 차이점
   - `spring.factories`와 `META-INF` 디렉토리의 역할
2. **자동 설정의 동작 원리**
   - `@SpringBootApplication`과 Auto Configuration
   - `@EnableAutoConfiguration`의 역할
   - `@Conditional` 어노테이션을 통한 조건부 설정
3. **Auto Configuration 클래스**
   - Auto Configuration 클래스의 구성 및 역할
   - 주요 클래스 살펴보기 (예: `DataSourceAutoConfiguration`)

#### **실습: Auto Configuration 이해하기**
1. **Spring Boot 프로젝트 생성**
   - Spring Initializr를 사용하여 기본 프로젝트 생성
   - 주요 의존성 추가 (Web, JPA, H2 Database 등)
2. **자동 설정 확인**
   - `@EnableAutoConfiguration` 활성화 확인
   - `Spring Boot Actuator`를 사용하여 자동 설정된 Bean 확인 (`/actuator/beans`)
3. **기본 설정 덮어쓰기**
   - `application.properties`로 기본 설정 변경
   - `spring.datasource.url` 등 환경 설정 추가

---

### **Day 2: Auto Configuration 커스터마이징과 실습**

#### **이론: Auto Configuration 커스터마이징**
1. **Auto Configuration 커스터마이징**
   - `@ConditionalOnClass`, `@ConditionalOnProperty`를 사용한 조건부 Bean 생성
   - `spring-boot-autoconfigure` 모듈의 구조 살펴보기
2. **사용자 정의 Auto Configuration**
   - 새로운 Auto Configuration 클래스 작성
   - `spring.factories` 파일을 통해 Auto Configuration 등록
3. **자동 설정 비활성화**
   - `@SpringBootApplication(exclude = ...)`로 Auto Configuration 비활성화
   - 특정 Auto Configuration을 제외하는 방법 (`spring.autoconfigure.exclude`)

#### **실습: 사용자 정의 Auto Configuration 구현**
1. **사용자 정의 Auto Configuration 클래스 작성**
   - 특정 조건(`@ConditionalOnProperty`)에 따라 Bean 생성
   - 예: `CustomService`를 자동으로 등록하는 Auto Configuration 작성
2. **spring.factories 파일 추가**
   - `META-INF/spring.factories`에 사용자 정의 Auto Configuration 등록
3. **Auto Configuration 테스트**
   - 조건을 충족하는 경우와 그렇지 않은 경우를 테스트하여 동작 확인
   - Spring Boot 애플리케이션 실행 후 자동 설정 확인 (`/actuator/beans`)

---

### **결과물**
1. **Spring Boot Auto Configuration 동작 원리 이해**
   - 자동 설정 클래스의 역할과 동작 방식
   - 조건부 Bean 등록 원리
2. **Auto Configuration 커스터마이징 능력**
   - 사용자 정의 Auto Configuration 구현
   - 특정 상황에 맞게 자동 설정을 활성화하거나 비활성화
3. **실습을 통한 이해 강화**
   - Actuator를 활용해 자동 설정된 Bean 확인
   - 커스터마이징된 Auto Configuration 적용 및 검증

---


### **Day 1: Spring Data JPA 기본 개념과 설정**

#### **이론: Spring Data JPA 소개와 기본 설정**
1. **Spring Data JPA 개요**
   - JPA와 Hibernate의 차이점
   - Spring Data JPA의 역할과 장점
2. **프로젝트 설정**
   - Spring Initializr를 사용한 기본 프로젝트 생성
   - 필수 의존성 추가 (`spring-boot-starter-data-jpa`, `H2`, `MySQL Driver` 등)
3. **Entity 클래스와 Repository**
   - `@Entity`, `@Id`, `@GeneratedValue`의 역할
   - JPA Repository 계층 (`CrudRepository`, `JpaRepository`)

#### **실습: Spring Data JPA 기본 설정**
1. **H2 데이터베이스 연동**
   - `application.properties` 설정
   - 데이터베이스 초기화 스크립트 작성 (`schema.sql`, `data.sql`)
2. **기본 Entity 및 Repository 작성**
   - `User` 엔티티 생성 (필드: id, name, email)
   - `UserRepository` 생성 후 CRUD 메서드 테스트
3. **Spring Boot 애플리케이션 실행**
   - H2 콘솔로 데이터 확인
   - 기본 CRUD 동작 확인 (`findAll()`, `save()` 등)

---

### **Day 2: JPQL, 메서드 이름 쿼리와 Native Query**

#### **이론: 쿼리 작성**
1. **JPQL (Java Persistence Query Language)**
   - JPQL의 기본 문법과 SQL 차이점
   - JPQL과 `@Query`를 사용한 사용자 정의 쿼리 작성
2. **메서드 이름 기반 쿼리**
   - `findByName`, `findByEmailAndName` 등
   - 키워드 조합으로 동적 쿼리 생성
3. **Native Query**
   - SQL을 직접 실행하는 `@Query(nativeQuery = true)`의 활용

#### **실습: 다양한 쿼리 작성**
1. **JPQL**
   - 사용자 이름으로 검색하는 `findByNameJPQL` 작성
   - JPQL로 사용자 이메일 검색 구현
2. **메서드 이름 기반 쿼리**
   - `findByEmailContaining`과 같은 메서드 작성
   - `findByCreatedDateAfter`로 날짜 기반 검색
3. **Native Query**
   - 복잡한 SQL을 실행하여 특정 조건 데이터를 검색
   - Native Query를 통한 집계 데이터 출력

---

### **Day 3: 관계 매핑과 페이징/정렬**

#### **이론: 연관 관계 매핑**
1. **연관 관계 매핑 개념**
   - `@OneToOne`, `@OneToMany`, `@ManyToOne`, `@ManyToMany`
   - 단방향 vs 양방향 매핑
   - Fetch 전략 (`Lazy` vs `Eager`)
2. **페이징과 정렬**
   - `Pageable`과 `Page` 인터페이스
   - 정렬 옵션 추가 (`Sort` 클래스)

#### **실습: 관계 매핑과 페이징**
1. **관계 매핑**
   - `User`와 `Post` 간의 1:N 관계 매핑
   - 양방향 매핑 구현 및 `@JoinColumn` 활용
2. **페이징 및 정렬**
   - `findAll(Pageable pageable)` 메서드로 페이징 처리
   - 정렬 기능 추가 (`findAll(Sort.by("name").ascending())`)
   - 특정 페이지 데이터 출력 및 확인

---

### **Day 4: 성능 최적화 및 고급 기능**

#### **이론: 성능 최적화**
1. **Fetch 전략 이해**
   - `Lazy Fetch`와 `Eager Fetch`의 차이
   - N+1 문제와 해결 방안
2. **EntityGraph와 JOIN FETCH**
   - `@EntityGraph`를 사용한 페치 조인
   - `@Query`와 `JOIN FETCH`를 통한 성능 최적화
3. **2차 캐시**
   - Hibernate의 2차 캐시 설정과 활용

#### **실습: 성능 최적화**
1. **N+1 문제 해결**
   - `@EntityGraph`로 관계 데이터를 한 번에 로드
   - JPQL로 Fetch Join 작성
2. **캐싱 적용**
   - Hibernate 캐시 설정 (`ehcache` 또는 `hazelcast` 활용)
   - 간단한 데이터 캐싱 테스트

---

### **Day 5: Spring Data JPA 프로젝트**

#### **이론: 프로젝트 설계**
1. **요구사항 분석**
   - 간단한 도서 관리 애플리케이션 설계
   - 기능: 사용자 등록, 도서 대출 관리, 대출 상태 확인
2. **엔티티와 관계**
   - `User`, `Book`, `Loan` 엔티티 설계
   - 사용자와 대출, 도서와 대출 간의 관계 매핑

#### **실습: 프로젝트 구현**
1. **엔티티 작성 및 매핑**
   - `User`와 `Book` 간의 1:N 관계 매핑
   - `Loan` 엔티티를 통해 사용자와 도서를 연결
2. **Repository와 Service 작성**
   - 사용자 등록 및 대출 처리 메서드 구현
   - 도서 대출 상태 조회 메서드 작성
3. **페이징과 정렬**
   - 대출 이력 페이징 처리
   - 도서 이름순 정렬
4. **프로젝트 테스트**
   - REST API를 통해 CRUD 테스트
   - H2 콘솔로 데이터 확인

---

### **결과물**
1. **Spring Data JPA CRUD 구현**
   - 기본적인 CRUD 기능과 다양한 쿼리 작성
2. **연관 관계 매핑 능력**
   - 복잡한 엔티티 관계 설정 및 성능 최적화
3. **프로젝트: 도서 관리 애플리케이션**
   - 사용자, 도서, 대출 관리 기능 구현
   - 페이징, 정렬, 성능 최적화 포함

---

## Spring Security 교육
---

### **Day 1: Spring Security 기본 개념과 설정**

#### **이론: Spring Security 개요**
1. **Spring Security란?**
   - 역할과 주요 기능
   - Spring MVC와의 통합
2. **Authentication과 Authorization**
   - 인증(Authentication)과 권한(Authorization)의 차이
   - SecurityContext와 SecurityContextHolder
3. **Spring Security 프로젝트 설정**
   - `spring-boot-starter-security` 의존성 추가
   - 기본 설정과 `@EnableWebSecurity` 이해

#### **실습: Spring Security 기본 설정**
1. **기본 프로젝트 생성**
   - Spring Initializr로 기본 Spring Security 프로젝트 생성
   - 의존성 추가 (`spring-boot-starter-security`, `spring-boot-starter-web`)
2. **기본 인증 기능 테스트**
   - 애플리케이션 실행 후 기본 로그인 페이지 확인
3. **Custom UserDetailsService 생성**
   - 사용자 정의 사용자 정보 (`UserDetails`) 제공

---

### **Day 2: 인증(Authentication)과 권한 관리**

#### **이론: 인증과 권한 관리**
1. **AuthenticationProvider**
   - `DaoAuthenticationProvider`를 사용한 기본 인증 설정
   - `AuthenticationManager` 동작 원리
2. **권한 관리**
   - `@PreAuthorize`, `@PostAuthorize`
   - `@Secured`와 `@RolesAllowed`의 차이
3. **PasswordEncoder**
   - 비밀번호 암호화와 `BCryptPasswordEncoder`

#### **실습: 인증 및 권한 설정**
1. **커스텀 로그인 구현**
   - 기본 로그인 페이지 커스터마이징
   - 사용자 이름/비밀번호를 통한 인증 처리
2. **권한 기반 접근 제어**
   - `/admin`, `/user` 경로에 권한별 접근 제한 추가
3. **비밀번호 암호화**
   - `BCryptPasswordEncoder`를 사용한 암호화 처리

---

### **Day 3: JWT를 활용한 인증**

#### **이론: JWT (JSON Web Token)**
1. **JWT의 개념과 동작**
   - 토큰 기반 인증의 장점
   - JWT 구조: Header, Payload, Signature
2. **Spring Security에서 JWT 적용**
   - Stateless 인증의 필요성
   - `UsernamePasswordAuthenticationFilter`와 JWT 통합

#### **실습: JWT 기반 인증 구현**
1. **JWT 발급 및 검증**
   - 로그인 시 JWT 발급
   - 요청 시 JWT를 검증하여 인증 처리
2. **Stateless 세션 설정**
   - Spring Security를 Stateless 모드로 전환
   - `SecurityContextHolder`에서 JWT로 사용자 인증
3. **API 보호**
   - JWT 기반으로 보호된 REST API 작성

---

### **Day 4: Spring Security와 CORS**

#### **이론: CORS (Cross-Origin Resource Sharing)**
1. **CORS란 무엇인가?**
   - Cross-Origin 요청이란?
   - CORS 정책의 동작 방식
2. **Spring Security와 CORS**
   - `CorsConfigurationSource`와 `CorsRegistry`
   - CORS와 CSRF의 차이점 및 적용 방법

#### **실습: CORS 설정**
1. **Spring Security에서 CORS 설정**
   - `HttpSecurity.cors()`와 `CorsConfiguration` 활용
   - 특정 도메인과 HTTP 메서드 허용
2. **실제 요청 테스트**
   - 프런트엔드(React 또는 Angular)에서 Spring Boot로 요청 보내기
   - CORS 오류 해결 및 확인
3. **CSRF 설정**
   - CORS와 함께 CSRF 비활성화
   - REST API를 위한 Stateless 모드 테스트

---

### **Day 5: 고급 주제와 최종 프로젝트**

#### **이론: 고급 Spring Security 기능**
1. **필터 체인 이해**
   - Spring Security 필터 체인의 구조
   - 커스텀 필터 추가 (`OncePerRequestFilter`)
2. **OAuth2와 소셜 로그인**
   - Spring Security OAuth2 Client 설정
   - 구글 OAuth2 로그인 구현

#### **실습: 최종 프로젝트**
1. **프로젝트 목표**
   - JWT 인증 기반 REST API
   - 관리자와 일반 사용자의 권한 구분
   - CORS 설정과 외부 프런트엔드 연계
2. **구현 기능**
   - 사용자 등록 및 로그인 API
   - `/admin`과 `/user` 경로에 권한별 접근 제한
   - JWT 기반 인증
   - CORS 설정으로 프런트엔드와 통신 가능
3. **테스트**
   - Postman 또는 프런트엔드 클라이언트를 사용한 API 호출 테스트
   - CORS 및 인증 흐름 확인

---

### **결과물**
1. **Spring Security 기반 인증 및 권한 관리**
   - 사용자 정의 로그인, JWT 인증, 권한 기반 접근 제어
2. **CORS 및 REST API 보안**
   - Cross-Origin 요청 처리
   - Stateless 모드와 CSRF 비활성화
3. **최종 프로젝트: JWT 기반 RESTful API**
   - 권한 관리, CORS 설정, JWT 인증을 포함한 API 완성

---

## Spring Boot Messaging

---

### **Day 1: Spring Messaging 기본 개념과 설정**

#### **이론: Spring Messaging 개요**
1. **Spring Messaging의 개념**
   - 메시징 시스템의 정의와 역할
   - 메시징 패턴: Point-to-Point, Publish-Subscribe
   - Spring Messaging 모듈의 구조 (`@EnableJms`, `MessageConverter`)
2. **Spring Messaging API**
   - `Message`와 `MessageHandler` 개념
   - `@MessageMapping`과 Spring WebSocket 연동
3. **JMS(Java Message Service) 개요**
   - JMS의 주요 개념: Queue, Topic, Message
   - JMS와 Spring 통합

#### **실습: Spring Messaging 프로젝트 생성**
1. **Spring Boot 프로젝트 설정**
   - `spring-boot-starter-activemq`와 `spring-boot-starter-jms` 의존성 추가
2. **간단한 메시지 처리 구현**
   - JMS Queue를 사용한 메시지 송신 및 수신
   - `@JmsListener`로 메시지 리스너 작성
3. **ActiveMQ 설치 및 실행**
   - ActiveMQ 브로커 설치
   - 브로커에 메시지 송신/수신 확인

---

### **Day 2: ActiveMQ와 Kafka 통합**

#### **이론: ActiveMQ와 Kafka**
1. **ActiveMQ**
   - ActiveMQ의 특징과 아키텍처
   - Queue와 Topic의 차이점
   - Spring에서 ActiveMQ 설정 (`ActiveMQConnectionFactory`)
2. **Kafka**
   - Kafka의 기본 아키텍처
   - Topic, Partition, Offset의 개념
   - Producer와 Consumer의 역할
3. **Spring for Apache Kafka**
   - `spring-kafka` 모듈 소개
   - KafkaTemplate과 @KafkaListener

#### **실습: ActiveMQ 통합**
1. **ActiveMQ 연결 설정**
   - Spring Boot에서 `ActiveMQConnectionFactory` 설정
   - 메시지 송신/수신 기능 구현
2. **Kafka 연동**
   - `spring-kafka` 의존성 추가
   - Kafka Producer와 Consumer 작성
   - Kafka 브로커와 Topic 설정
3. **메시징 처리 흐름 테스트**
   - ActiveMQ Queue에 메시지 송신
   - Kafka Topic에서 메시지 소비

---

### **Day 3: 고급 메시징 기능과 실습 프로젝트**

#### **이론: 메시징 시스템의 고급 주제**
1. **MessageConverter**
   - JSON 메시지 변환기 설정
   - `MappingJackson2MessageConverter`를 사용한 메시지 변환
2. **오류 처리**
   - ActiveMQ와 Kafka에서 메시지 재시도 설정
   - Dead Letter Queue(DLQ) 구성
3. **Spring Cloud Stream 소개**
   - Spring Messaging을 활용한 마이크로서비스 통합
   - Binder 개념과 활용

#### **실습: 메시징 시스템 구현**
1. **통합 메시징 애플리케이션**
   - ActiveMQ를 사용하여 주문 생성 메시지 송신
   - Kafka로 주문 처리 결과 메시지 수신
2. **오류 처리 및 DLQ 구성**
   - Kafka Consumer에서 예외 발생 시 DLQ로 메시지 이동
   - ActiveMQ Dead Letter Queue 설정
3. **Spring Cloud Stream 연동**
   - Spring Cloud Stream으로 ActiveMQ와 Kafka 통합
   - 메시지 변환기와 스트림 프로세싱 작성

---

### **결과물**
1. **Spring Messaging 통합 애플리케이션**
   - ActiveMQ와 Kafka를 활용한 메시징 시스템
   - Producer-Consumer 패턴을 구현한 실습 프로젝트
2. **고급 메시징 시스템**
   - 메시지 변환, 오류 처리, Dead Letter Queue 구성
3. **Spring Cloud Stream 기반 메시징**
   - 마이크로서비스 통합 및 확장 가능성 확보

---

## Docker 교육

---

### **Day 1: Docker 기본 개념과 설치**

#### **이론: Docker의 개요**
1. **Docker란 무엇인가?**
   - 컨테이너와 가상 머신의 차이
   - Docker의 주요 특징 (이미지, 컨테이너, 레지스트리)
   - Docker와 DevOps의 관계
2. **Docker 아키텍처**
   - Docker Engine의 구성 요소
   - Docker CLI와 Daemon의 역할
   - 이미지와 컨테이너의 동작 원리

#### **실습: Docker 설치 및 기본 명령어**
1. **Docker 설치**
   - Docker Desktop 설치 (Windows/Mac)
   - Docker Engine 설치 (Linux)
2. **Docker 기본 명령어**
   - Docker 버전 확인 (`docker --version`)
   - Docker 서비스 시작 및 확인 (`docker ps`, `docker info`)
3. **첫 번째 컨테이너 실행**
   - `docker run` 명령으로 간단한 컨테이너 실행 (`hello-world`)
   - `docker run -it ubuntu bash`로 Bash 셸 접속

---

### **Day 2: Docker 이미지와 컨테이너**

#### **이론: Docker 이미지와 컨테이너**
1. **Docker 이미지**
   - Docker 이미지란 무엇인가?
   - Docker Hub와 이미지 레지스트리
   - 이미지 레이어의 개념과 재사용성
2. **Docker 컨테이너**
   - 컨테이너 생성, 실행, 중지, 삭제
   - 컨테이너와 이미지의 관계

#### **실습: 이미지와 컨테이너 관리**
1. **Docker Hub 사용**
   - `docker pull`로 이미지 다운로드
   - `docker images`로 로컬 이미지 확인
2. **컨테이너 생성 및 관리**
   - `docker run`으로 컨테이너 실행
   - 컨테이너 중지 및 재시작 (`docker stop`, `docker start`)
   - 컨테이너 삭제 (`docker rm`)
3. **이미지 생성**
   - Dockerfile 작성
     - 기본 예제: 간단한 Nginx Dockerfile 작성
   - `docker build`로 이미지 생성
   - 이미지 태그와 업로드 (`docker tag`, `docker push`)

---

### **Day 3: 네트워크와 데이터 관리**

#### **이론: Docker 네트워크**
1. **Docker 네트워크의 개념**
   - 기본 네트워크 유형: bridge, host, none
   - 사용자 정의 네트워크
2. **컨테이너 간 통신**
   - 동일 네트워크 내에서의 통신
   - 외부 포트 노출과 NAT

#### **이론: Docker 볼륨**
1. **데이터 관리와 영속성**
   - 컨테이너 스토리지 기본 개념
   - 볼륨(Volumes)과 바인드 마운트(Bind Mount)의 차이
2. **데이터 공유**
   - 다중 컨테이너 간 데이터 공유

#### **실습: 네트워크와 데이터 관리**
1. **네트워크 설정**
   - 사용자 정의 브리지 네트워크 생성 (`docker network create`)
   - 네트워크에 컨테이너 연결 및 통신 테스트
2. **포트 매핑**
   - `-p` 옵션으로 컨테이너 외부 포트 노출 (`docker run -p`)
   - 웹 애플리케이션 실행 및 브라우저에서 확인
3. **볼륨 사용**
   - 볼륨 생성 및 컨테이너에 마운트 (`docker volume create`, `docker run -v`)
   - 데이터 영속성 확인
   - 바인드 마운트를 사용하여 로컬 파일 공유

---

### **Day 4: Docker Compose와 애플리케이션 배포**

#### **이론: Docker Compose**
1. **Docker Compose 개요**
   - 다중 컨테이너 애플리케이션 관리
   - `docker-compose.yml` 파일 구조
2. **Compose와 개발 환경**
   - 개발용 애플리케이션 스택 구성
   - `docker-compose up`과 `docker-compose down`

#### **이론: Docker 배포**
1. **이미지 배포**
   - Docker Hub 또는 개인 레지스트리에 이미지 업로드
   - Docker Swarm 개요
2. **배포 전략**
   - Blue-Green Deployment
   - Rolling Update

#### **실습: Docker Compose 프로젝트**
1. **`docker-compose.yml` 작성**
   - 웹 애플리케이션과 데이터베이스(Nginx + MySQL) 스택 구성
2. **Compose 실행**
   - `docker-compose up`으로 애플리케이션 실행
   - 컨테이너 간 통신 및 데이터베이스 연결 확인
3. **이미지 배포**
   - Docker Hub에 이미지를 푸시하여 공유
4. **최종 테스트**
   - 개발 환경에서 전체 애플리케이션 실행 및 테스트

---

### **결과물**
1. **Docker 기본 사용 능력**
   - 이미지 생성, 컨테이너 실행, 데이터 관리
2. **네트워크와 데이터 관리**
   - 컨테이너 간 통신 및 데이터 영속성 구현
3. **Docker Compose 활용**
   - 다중 컨테이너 애플리케이션 배포 및 관리
4. **최종 프로젝트**
   - Docker Compose를 활용한 Nginx + MySQL 기반 애플리케이션 배포
