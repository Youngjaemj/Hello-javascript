# 자바스크립트로 무엇을 할 수 있나?

## 자바스크립트로 할 수 있는 것들

- 자바스크립트는 HTML을 제어할 수 있다.


### 첫 번째 프로그램
- ex1.html 을 작성하고 크롬 브라우저로 연다.
<!--
<!DOCTYPE html>
<html>
<body>
<h2>자바스크립트 연습장</h2>
<p id="demo">지금은 몇시인가요?</p>
</body>
</html>
-->


- 개발자 도구 - 콘솔에서 아래 명령을 실행<br/>
var demo = document.getElementById('demo');<br/>
demo.innerHTML = Date();

### 두 번째 프로그램
demo.style.color = "red";<br/>
demo.style.background = "black";

### 세 번째 프로그램
var demo = document.getElementById('demo');<br/>
var size = 10;<br/>
function big() {<br/>
    demo.style.fontSize = size + "px";<br/>
    size = size + 1;    <br/>        
}<br/>
var tid = setInterval(big, 100);






# 자료형이란?

- 어떤 종류의 데이터를 사용하는 것인지 컴퓨터에게 알려주는 것
- 자료형마다 사용 가능한 연산자(Operator)를 따로 가지고 있습니다.
- 자료형이 같아야 연산을 할 수 있습니다!

## 자료형의 종류

Number<br/>
String<br/>
Boolean<br/>
Null<br/>
Undefined

- 그리고 하나의 객채가 더 있습니다.
Object<br/>

## Number Type

- 정수와 실수는 모두 Number 타입입니다.
5;<br/>
3.0;<br/>
-4.8

## 숫자의 연산자

- 4칙연산, 괄호, 나머지 등이 있습니다.
+, -, /, *, (, ), %

## 문자열

"I am string";<br/>
"Hello " + "world";<br/>

- 문자열에도 +가 됩니다.(참고로 문자열은 "Immutable" 특징을 가집니다.)

## typeof 연산자

- 데이터 유형을 알려주는 중요 연산자!!
typeof 5;<br/>
typeof -4.8;<br/>
typeof "5";

## 생각해보기

5 + 4;<br/>
5 + "4";<br/>
5 * "4";

## 불리언

ture;<br/>
false;<br/>
5 > 3;<br/>
5 == 5;<br/>
5 > 5;

## 논리연산자

- 논리연산자에는 &&, ||, ! 등이 있다.
ture;<br/>
!ture;<br/>
ture && false;<br/>
ture || false;
