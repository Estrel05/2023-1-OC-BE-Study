# __1. 필수 정리 내용__
##  __1.1. MVC(Model, View, Controller)패턴__
프로젝트 구성 요소를 Model, View, Controoller로 분리한 것으로 비즈니스 로직과 화면 작업을 분할 처리하여 효율적이다. 과거에는 View와 Controller가 분리되어 있지 않은 Model1 방식을 사용했다.
* Model, Controller: 비즈니스 로직이나 내부 작업 처리
* View: 화면 출력과 같은 작업 처리<br/><br/>

## __1.2. API(Application Programming Interface)와 서버__
애플리케이션 소프트웨어를 빌드하고 통합하기 위한 인터페이스이다. 프로그램들이 서로 상호작용할 수 있도록 돕는 역할을 한다.
* API의 역할
  * 서버와 데이터베이스의 __출입구__
  * 애플리케이션과 기기 사이의 원활한 통신 지원
  * 모든 접속 __표준화__<br/><br/>

## __1.3. RESTful(Representational State Transfer-ful)__
### __1.3.1. REST__
자원의 표현에 의한 상태 전달을 뜻한다. 아키텍처 스타일로서 API가 갖춰야 할 디자인이라고 생각하면 된다.
* REST의 구성 요소
  * 자원(Resources): URL
  * 메서드(Method): HTTP 메서드
  * 메시지(Message): HTTP header, body, status code, etc.<br/><br>

### __1.3.2. RESTful API__
REST 설계 규칙을 잘 지켜 설계된 API를 말한다. 본래의 의미와는 다르게 일반적으로 REST 아키텍처를 구현하는 웹서비스를 표현하는 용어로 쓰인다. RESTful하게 설계된 API는 요청을 보내는 주소만 보고도 어떤 요청을 하는지 알 수 있다고 한다.<br/><br/>

# __2. WIL1__
## __2.1. Java 개발 환경 구축__
* Java설치
* intellij 설치<br/><br/>

## __2.2. 스프링부트 세팅__
* spring initializr 접속
  * Project - Gradle 선택
  * Language - Java 선택
  * Spring Boot - 정식 버전 중 가장 최신 버전으로 선택
  * Group - 패키지명 입력
  * Artifact - 애플리케이션명 입력
  * Name - Artifact와 동일
  * Description - 설명 입력
  * Package name - Gruop.Artifact
  * Packaging - Jar 선택
  * Java - Java 버전 선택
  * Dependencies - spring web, thymeleaf 선택
  * generate 눌러 설치 후 압축풀기<br/><br/>

## __2.3. 프로젝트 열기__
1. intellij 실행
2. open 선택
3. 압축을 푼 폴더 내의 build.gradle파일 선택
4. open as project 선택<br/><br/>

## __2.4. 웰컴페이지 만들기__
1. src\main\resources\static폴더에 index.html파일 작성
2. main 실행
3. localhost:8080 접속하여 확인<br/><br/>

## __2.5. 빌드와 실행__
1. 터미널 실행
2. 프로젝트 폴더 내의 build\libs폴더로 이동
3. ./gradlew build 입력
4. java -jar "Package name"-0.0.1-SNAPSHOT.jar입력
5. localhost:8080 접속하여 확인