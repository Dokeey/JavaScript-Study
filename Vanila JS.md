# JavaScript - 1일차

##1. 기본 실행방법과 실습환경

### 크롬 개발자 도구

- console 탭에서 실시간으로 JavaScript를 테스트, 실행 할 수 있음

- 디버거 공부 추가적으로 하면 좋을듯

### IDE

- Sublime Text, Pycharm 등 으로 선택

## 2. 숫자와 문자

### 수의 표현

- 숫자 : 정수, 실수 등
  - 정수, 실수끼리 계산도 가능

### 수의 연산

- Math

  - ```javascript
    	console.log(Math.pow(3,2)); // 제곱
    	console.log(Math.round(10.6)); // 반올림
    	console.log(Math.ceil(10.2)); // 가장 가까운 윗쪽 정수로 올림
    	console.log(Math.floor(10.2)); // 가장 가까운 아랫쪽 정수로 올림
    	console.log(Math.sqrt(9)); // 제곱근
    	console.log(Math.random()); // 랜덤값
    ```

### 문자

- 특수문자 무시 : \
- typeof : 데이터 형식보기
  - typeof "hello"

### 문자 연산

- ```javascript
  	console.log("Hello \nWorld"); // 줄바꿈
  	console.log("Hello" + " World"); // 문자열 더하기
  	console.log("Hello World".length); // 문자열 길이
  	console.log("Hello World".indexOf("W")); // 문자의 index 찾기
  ```

## 3. 변수

### 변수 사용법

- var로 시작함
  - var a = 1;
  - var a = 1, b = 2;
- 초기화된 변수는 var를 생략하여 제어가능
  - a = 2;

## 4. 비교

### 비교 연산자

- == (equal operator) 추천 X
  - True or False 결과를 출력
  - 1 == "1" : true
- === (strict equal operator) 추천 O
  - 1 === "1" : false
  - 데이터 타입까지 비교

- undefinde : 값이 없는 상태
- null : 의도적으로 값을 없게 만든 상태
- 1을 제외한 모든 숫자를 false로 간주함

### 부정과 부등호

- != : 추천X
- !== : 추천O