myBitacademy
============

비트아카데미 공부정리

#2013년 8월 1일 첫수업 자바수업정리

-자바 실행환경 

*JavaSE :자바 standard edition의 약자로 JDK(JavaDevelopmentTool)이라고도 부른다. 
  그안에 App개발도구, 컴파일러 , 디버거, API문서 , 편집기, 프로파일러등이 있다. 
  
  -JRE(JavaRuntimeEnviroment)자바 실행환경이며 


*JavaEE : 자바 플랫폼, 엔터프라이즈 에디션이라고 불리며 JavaSE와는 별개이다. 

*JavaME : 자바 모바일 플랫폼이다 허나 범용적이지 않으며, 현재 그자리에 Android가 차지하고 있다.

*[Java환경변수 설정법]

-환경변수 새로만들기 

JAVA_HOME이란 변수명, 값:
```java
C:\Program Files\Java\jdk1.7.0_13
```
설정
-환경변수 path에 맨앞쪽에 %JAVA_HOME%\bin;까지 경로를 알려준다.
-명령 프롬프트창에서 javac.exe 실행 후 컴파일 성공하면 정상으로 설정한것이다.

*[JavaSE 버전확인]
-터미널에서 java -version 커멘드 명령어 입력하면 확인 가능.

#[자바main 메소드콘솔창에'Hello!!'출력하기]

-Hello.java 메인클래스
```java
package net.bitacademy.java41;
//엄진영, jinyoung.eom@gmail.com
public class Hello {

  public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Hello!!");
	}
}

```
커멘드 창에서 ...
```console
java -classpath ./bin net.bitacademy.java41.Hello

Hello!!
```

*Java언어로 만든 IDE 이클립스 설치방법
-eclipse.org 접속후 JAVA EE JavaDeveloper 압축다운로드
-압축 풀고 .exe 실행파일 인스톨 
-설치 완료
-설치후 preferences --> web에 CSS, HTML 파일에 케릭터 
  인코딩 UTF-8로 설정
-Hello.java 를 이클립스에서 실행후 Hello!! 가 나오면 성공!! 

