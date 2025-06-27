# 04. 변수

### 변수란

- 메모리 공간에 붙는 이름


### 식별자

- 식별자나 변수나 같은말
  

### 변수 선언

- var X, const 재선언 X가능(상수), let 재선언 가능
  

### 변수 선언의 실행 시점과 변수 호이스팅

- 변수 선언의 실행은 런타임이 아닌 런타임 이전에 실행된다. 이게 호이스팅이다.

```javascript
console.log(score); //undefined (호이스팅으로 변수선언을 먼저 했는데 할당은 안해줬으니까 암묵적으로 빈 메모리공간에 score라는 이름이 붙음. 이거시 암묵적 할당)

let score; // 변수 선언한게 먼저 인식 (호!이!스!팅!)
score = 80; // 변수에 값을 할당

console.log(score); //80
```


### 값의 할당

```javascript
let score = 80; // 이것이 값의 할당
```


### 값의 재할당

```javascript
let score = 80; // 이것이 값의 할당
score = 100; // 이것이 재할당! (const는 안됨. var는 되는데 var쓰면 잡아감)
```


### 식별자 네이밍 규칙

```javascript
first_name; //스네이크

FirstName; //파스칼케이스

firstName; //카멜케이스

strFirstName; // 헝가리안케이스 ( 앞에 값의 타입을 붙여줌)
```
