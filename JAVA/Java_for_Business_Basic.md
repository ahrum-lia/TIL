# Business Java Programming Basic

# 멀티캠퍼스 E-Learning

### 자바의 소개

- 프로그램 개발 순서 : 소스 파일 --*컴파일*---> 실행 파일 ---*실행*----> 컴퓨터

  - C : 소스파일(test.c) -> 실행파일(=머신코드, test.exe) -> 컴퓨터
  - java: 소스파일(test.java) -> 실행파일(=바이트코드, test.class) -> JVM(바이트코드를 기계어 코드로 바꿔줌) -> 컴퓨터

- total progress

  ```
  소스파일 -> 실행파일 -> (여기부터 JVM) Class loader -> Bytecode verifier -> Interpreter 또는 Just-In-Time compiler -> Runtime System (JVM 끝) -> 운영체제 -> Hardware 
  ```

- JDK: JVM + 개발 tool
- JRE: JVM + java 코드 실행에 필요한 api 들 



#### Java 개발환경 설정

1. Oracle 홈페이지에서 jdk 다운로드

2. 다운로드 받은 파일을 설치 후 시스템 변수 설정(개발에 사용할 jdk파일을 등록해주는 과정)

   ```
   변수 이름: JAVA_HOME
   변수 값: jdk디렉토리 위치
   ```

3. Path 설정 : 실행 위치에 프로그램이 존재하지 않아도 실행할 수 있도록 함

   ```
   bin 폴더를 Path 에 추가
   ```



#### Java 개발 도구

- 컴파일러 : javac
- 실행도구 : java (main method 실행해주는 프로그램)
- 압축도구: jar
- 문서 작성 도구: javadoc



#### Java development tool

- 이클립스 사용 : eclipse.org 에서 .zip 파일 다운받아서 압축만 풀어도 됨