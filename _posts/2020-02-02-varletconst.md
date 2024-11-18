---
layout: post
title: var, let, const의 특징과 차이점
category: ['Old Posts']
published: false
keywords:
  - javascript
  - javascript 변수
  - var
  - let
  - const
  - var, let, const 차이
  - var, let, const 비교
  - javascript 변수 선언
  - javascript 변수 비교
---

### 1. Javascript의 변수선언

Javascript의 변수 선언방식은 `var`, `let`, `const` 로 3가지 방법이 있습니다. ES6이전에는 전부 var(variable)로 선언하면 되었는데, 몇가지 문제점때문에 개선된 방식이 ES6 이후 추가되었습니다. let과 const방식이 추가되었는데, 이번 포스팅에서는 var, let, const 세가지 선언방식의 특징을 알아보고 차이점을 비교해보도록 하겠습니다.

<br/>

### 2. var

- ES6(ESMAScript6) 이전의 문법
- 재선언 가능
- 재할당 가능
- 사용범위(Scope)는 function(함수) 단위

우선 var선언방식의 특징을 정리해 보았습니다.
var선언방식의 가장 큰 특징은 재선언/재할당이 가능한 가장 자유로운 방식이라는 것입니다. 자유로운 대신 위험요소도 많습니다. client의 console창에서 임의 변경이 가능하기도 하고, 코딩할 때 문제가 되기도 합니다. 

재선언과 재할당에 대한 간단한 예를 들어보겠습니다.

```javascript
// 재선언
var number = 1;
var number = 2;
console.log(number); // 2

// 재할당
var age = 12;
age = 13;
console.log(age); // 13
```

위와 같이 재선언과 재할당이 가능하며 아무런 문제가 되지 않습니다.

이번에는 사용범위에 대한 예를 들어보겠습니다.

```javascript
function testFunction() {
  var number = 1;
  
  if (true) { 
    var number = 2; 
    console.log(number); // 2
  } 

  console.log(number); // 2
};
testFunction();
```

위 코드를 살펴보면, 함수단위로 사용범위가 적용되는 것을 알 수 있습니다. 아무생각없이 작성할 수 있는 코드이지만, 잠재적인 위험요소를 가지고 있는 코드입니다.

<br/>

### 2. let

- ES6(ESMAScript6) 이후의 문법
- 재선언 불가
- 재할당 가능
- 사용범위(Scope)는 {}(블록) 단위

두번째, let선언방식의 특징을 정리해 보았습니다.
let선언방식의 가장 큰 특징은 재선언이 불가하고 재할당이 가능한 방식이라는 것입니다. 

재선언과 재할당에 대한 간단한 예를 들어보겠습니다.

```javascript
// 재선언
let number = 1;
let number = 2;
console.log(number); // Uncaught SyntaxError: Identifier 'number' has already been declared

// 재할당
let age = 12;
age = 13;
console.log(age); // 13
```

위와 같이 재선언시 'already been declared'라고 오류가 나는 것을 볼 수 있듯이 let선언방식은 재선언이 되지 않습니다.
반면 재할당은 문제없이 되는 것을 볼 수 있습니다.

이번에는 사용범위에 대한 예를 들어보겠습니다.

```javascript
function testFunction() {
  let number = 1;
  
  if (true) { 
    let number = 2; 
    console.log(number); // 2
  } 

  console.log(number); // 1
};
testFunction();
```

위 코드를 살펴보면, {} (블록)단위로 사용범위가 적용되기 때문에, console에 찍히는 값이 var와 다르단 것을 볼 수 있습니다.

<br/>

### 3. const

- ES6(ESMAScript6) 이후의 문법
- 재선언 불가
- 재할당 불가
- 사용범위(Scope)는 {}(블록) 단위

세번째, const의 선언방식의 특징을 정리해 보았습니다.
const선언방식의 가장 큰 특징은 재선언/재할당이 모두 불가능한 방식이라는 것입니다. 

재선언과 재할당에 대한 간단한 예를 들어보겠습니다.

```javascript
// 재선언
const number = 1;
const number = 2;
console.log(number); // Uncaught SyntaxError: Identifier 'number' has already been declared

// 재할당
const age = 12;
age = 13;
console.log(age); // Uncaught TypeError: Assignment to constant variable.
```

위와 같이 재선언시 'already been declared'라고 오류가 나는 것을 볼 수 있고, 재할당시 'Assignment to constant variable' 오류를 볼 수 있습니다.

이번에는 사용범위에 대한 예를 들어보겠습니다.

```javascript
function testFunction() {
  const number = 1;
  
  if (true) { 
    const number = 2; 
    console.log(number); // 2
  } 

  console.log(number); // 1
};
testFunction();
```

위 코드를 살펴보면, const역시 let과 같이 {} (블록)단위로 사용범위가 적용되기 때문에, console에 찍히는 값이 var와 다르단 것을 볼 수 있습니다.

<br/>

### 4. 결론

기존 `var`로 사용하던 변수선언을 지양하고, 상황에 따라 `let`과 `const` 두가지 방식으로 나누어 사용하는 것이 바람직하다고 생각됩니다.

|선언방식|재선언|재할당|적용범위|
|---|:---:|:---:|---|
|var|O|O|function(함수)|
|let|X|O|{}(블록)|
|const|X|X|{}(블록)|
