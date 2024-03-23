# [STEP 1] 문자열 사칙연산 계산기

## 기능 요구사항

1. StringCalculatorApplication
    - [x]  문자열 계산기를 실행한다.
2. CalculatorView
    - [x]  사용자로부터 계산식 문자열을 입력받는다.
    - [x]  사용자에게 계산식의 계산 결과를 출력한다.
    - [x]  계산식 문자열이 null이거나 빈 문자열, 공백, 개행인 경우 예외를 던진다.
    - [x]  계산식 문자열이 올바른 형식이 아닌 경우 예외를 던진다.
        - [x]  피연산자와 연산자가 번갈아가며 등장해야 한다.
        - [x]  피연산자로 시작해서 피연산자로 끝나야 한다.
        - [x]  피연산자와 연산자 사이에는 한 칸의 공백이 존재해야 한다.
        - [x]  피연산자는 정수형이어야 한다.
        - [x]  연산자는 사칙연산 기호(+, -, *, /) 중 하나여야 한다.
3. Calculator
    - [x]  사용자의 입력을 바탕으로 연산자와 피연산자로 이루어진 계산식을 생성한다.
    - [x]  계산식의 계산 결과를 출력기에 전달한다.
    - [x]  하위에서 발생한 예외에 대해 처리한다.
4. Expression
    - [x]  계산식을 연산자와 피연산자 토큰들로 저장한다.
    - [x]  계산식의 계산을 수행하고 결과를 반환한다.
    - [x]  계산식 배열이 null이거나 빈 배열인 경우 예외를 던진다.
5. Operand
    - [x]  피연산자를 정수로 변환하여 저장한다.
    - [x]  피연산자가 정수형이 아닌 경우 예외를 던진다.
6. Operator
    - [x]  사칙 연산자를 저장한다.
    - [x]  두 피연산자를 받아 사칙연산을 수행하고 결과를 반환한다.
    - [x]  연산자가 사칙 연산 기호(+, -, *, /) 이외의 문자인 경우 예외를 던진다.
    - [x]  나눗셈 연산에서 0으로 나누는 경우 예외를 던진다.

<br>

---

## 프로그래밍 요구사항

1. indent(들여쓰기) depth를 2단계에서 1단계로 줄여라.
    - depth의 경우 if문을 사용하는 경우 1단계의 depth가 증가한다. 
    - if문 안에 while문을 사용한다면 depth가 2단계가 된다.
2. 메소드의 크기가 최대 10라인을 넘지 않도록 구현한다.
    - method가 한 가지 일만 하도록 최대한 작게 만들어라.
3. else를 사용하지 마라.

<br>

---

## 실행 결과

<img width="191" alt="image" src="https://github.com/next-step/java-racingcar/assets/49775540/68ad54db-75c4-4a60-8e9c-b46a3666f336">
