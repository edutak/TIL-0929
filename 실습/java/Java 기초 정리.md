# Java 기초 정리



#### 출력

``` 
System.out.print(); -> 출력
System.out.println();  -> 출력하고 한줄 띄우기
```



## 데이터 타입

#### 기본 타입

```
숫자, 문자열, 논리

숫자
	- 정수 타입 : byte < short < int < long
	- 실수 타입 : float < double
	- byte < short < int < long < float < double

논리
	- true, false
```

#### 타입 변환

자동 타입 변환(promotion), 강제 타입 변환(casting)

**자동(묵시적) 타입 변환**

```
작은 크기를 가지는 타입이 큰 크기를 가지는 타입에 저장될 때 발생
큰 크기 타입 = 작은 크기 타입
ex)
byte byteValue = 10;
int intValue = byteValue; //10

int intValue2 = 200;
double doubleValue = intValue; //200


```

**수동(명시적) 타입 변환**

```
큰 크기의 타입은 작은 크기의 타입으로 자동 타입 변환 불가
강제적으로 큰 데이터 타입을 작은 데이터 타입으로 쪼개어서 저장하는 것을 강제 타입 변환이라 함
작은 크기 타입 = (작은 크기 타입)큰 크기 타입
ex)
int intValue = 103029770;
byte byteValue = (byte)intValue; //강제 타입 변환

```



## 조건문과 반복문

### 조건문 (if문)

**if문**

```java
if(조건식1){
    실행문;
    실행문;
} else if(조건식2){
    실행문;
    실행문;
} else{
    실행문;
}
```

### 반복문(for문, while문)

**for문**

```java
int sum = 0;	//-> sum을 0으로 초기화하고 진행
for(int i=0 ; i<횟수 ; i++){	//i++ -> 반복 할 때마다 i가 1씩 증가 
    sum = sum + (i+1);    
}
System.out.println(sum);
```

