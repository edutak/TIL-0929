# JavaStudy/ 1 /자바 시작하기 



## 자바의 특징

이식성이 높은 언어

객체 지향 언어

객체를 만들기 위한 설계도인 클래스를 작성 후 객체와 객체를 연결해 프로그램을 만든다

## 자바 프로그램 개발 순서

.java 소스 파일 작성

컴파일러로 바이트 코드 파일(.class) 생성

JVM 구동 명령어(java.exe)로 실행



**자바 소스 파일 주의점**

클래스명 앞글자는 대문자이고 파일명과 일치해야하며 숫자가 앞에 올수 없으며 공백을 포함하지않는다

String도 클래스이므로 앞글자 대문자

System도 마찬가지

System.out.println("Hello");

세미콜론 빼먹지 말기(;)



## 프로그램 소스 분석

클래스 : 필드 또는 메소드를 포함하는 블록

메소드 : 어떤 일을 처리하는 실행문들을 모아 놓은 블록

메소드도 개발자 마음대로 정할 수 있지만 main()메소드는 바꿀 수 없다. 그 이유는 java.exe로 JVM 구동시 main()메소드를 제일 먼저 찾아 실행시키기 때문이다

그래서 main()메소드를 진입점(entry point)라고도 함(또한 필수적)



클래스{

메소드{실행문}

메소드2{실행문2}

}



## 주석

// 내용

/*

내용

*/



## 실행문과 세미콜론

실행문은 변수 선언, 값 저장, 메소드 호출에 해당하는 코드를 말함

주의할점 : 세미콜론(;)을 붙여 실행문이 끝났음을 표시해야함

