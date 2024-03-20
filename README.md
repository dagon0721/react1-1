# 박상원 201830213

## 3월 20일 강의 내용
### 리액트는 무엇인가?

1-1. 리액트의 정의
사용자 인터페이스를 만들기 위한 자바스크립트 라이브러리  
-> 웹 및 앱 유저 인터페이스를 위한 라이브러리

1-2. 다양한 자바스크리트 UI 프레임워크 : Stack Overflow trends

1-3. 리액트 개념 정리  
1. 복잡한 사이트를 쉽고 빠르게 만들고, 관리하기 위해 만들어진 것이 바로 리액트  
2. 다른 표현으로는 SPA를 쉽고 빠르게 만들 수 있도록 해주는 도구

2-1. 리액트의 장점
1. 빠른 업데이트와 렌더링 속도(Virtual DOM이 이것을 가능케 함)
2. DOM이란 XML, HTML 문서의 각 항목을 계층으로 표현하여 생성, 변형, 삭제할 수 있도록 돕는 인터페이스(W3C의 표준)
3. DOM 조작이 비효율적으로 속도가 느리기에 V DOM이 고안(DOM은 동기식, V DOM은 비동기식 방법 렌더링)


## 3월 13일 강의 내용
### GitHub 사용법

초기화
git init

개인 PC
git config --global user.name ""

공용 PC
git config user.name ""

노드 버전 확인
node -v
npm -v
npx -v

패키지 버전 확인
-v, --version


1. 자바스크립트란 무엇인가?
2. ES6(ECMAScript6) - 표준 ECMA-262
3. 자바스크립트의 자료형

var : 중복 선언 가능, 재할당 가능
let : 중복 선언 불가능, 재할당 가능
const : 중복 선언 불가능, 재할당 불가능
Array type : 배열
Object type

function statement 형: 일반적 함수의 형태
Arrow function expression 형 : 화살표 함수

Ex)


//function statement를 사용
function sum(a, b) {
    return a + b;
}

console.log(sum(10, 20));
// 출력 결과 : 30

//arrow function expression 사용
const multiply = (a, b) => {
    return a + b;
}

console.log(multiply(10, 20));
//출력 결과 : 200