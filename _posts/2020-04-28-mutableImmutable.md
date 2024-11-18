---
layout: post
title: Primitive type (기본타입) VS Reference type (참조타입)
category: ['Old Posts']
published: false
keywords:
  - javascript
  - javascript Immutable
  - javascript mutable
  - mutable
  - Immutable
  - reference type
  - primitive type
---

### 1. Primitive type과 Reference type이란?

모든 프로그래밍 언어에는 내장 자료형이 있습니다. 각 언어의 내장 자료형은 언어마다 다르며 자바스크립트의 고유 내장 자료형에는 두가지 타입이 있습니다. 크게 Primitive type(기본타입)과 Reference type(참조타입)으로 구성됩니다.

이번 포스팅에서는 두가지 자료형에 대한 차이점과 이해를 하기위해 정리합니다. javascript 뿐만 아니라 다른 프로그래밍 언어의 이해에도 적용될 수 있는 개념이며, 
깊은복사/얕은복사, Mutable/Immutable 등 더 많은 개념을 이해하기위해 기초적으로 필요한 개념이므로 꼭 정리하고 넘어가야 되는 부분입니다.

<br/>

### 2. Primitive type: 기본타입이란?

기본타입 자료형이란 변수에 할당될 때 메모리 상에 고정된 크기로 저장되는 것을 말하며, 변경이 불가능(Immutable)한 특성을 가지고 있습니다.
따라서 기본타입의 크기는 고정되어 있으므로 javascript에서는 stack 메모리 영역에 저장되고, 메모리 영역에 직접접근(Access by value)하게 됩니다.
메모리를 들여다볼 수 있다면, 기본타입으로 할당된 메모리에는 100, 'String data', false, true, null같은 값 자체가 저장되어 있습니다.

Primitive type의 특성을 정리하면 다음과 같습니다.

- 해당하는 자료형: number, string, boolean, undefined, null, symbol
- Immutable (변경불가능)
- 스택메모리에 저장
- Access by value

Primitive type의 예를 들어서 알아보겠습니다.

```javascript
let name = 'JOHN';
let yourName = name;

name = 'DANIEL';

console.log(name); // 'DANIEL'
console.log(yourName); // 'JOHN'
```

1. 먼저 name이라는 변수에 'JOHN'이라는 문자열을 할당했습니다. 
2. 그다음 yourName이라는 변수에 name의 값을 할당했습니다. 
3. 그다음 name변수를 'DANIEL'로 변경합니다. 

console.log 결과에 따르면 name변수는 'DANIEL'을 출력하고, yourName변수는 'JOHN'을 출력합니다. 

yourName의 값이 name과 같이 변경되지 않은 걸로 봐서, yourName에는 `'JOHN'이라는 값 자체`가 저장되어 있는 것을 알 수 있습니다.

<br/>

### 3. Reference type: 참조타입이란?

참조타입 자료형이란 변수에 할당될 때 메모리 상에 크기가 정해지지 않은 상태로 저장되며, 변경이 가능(mutable)한 특성을 가지고 있습니다.
따라서 참조타입의 크기는 고정되지 않고 동적이므로 javascript에서는 heap 메모리 영역에 저장되고, 메모리 영역에 참조접근(Access by reference)하게 됩니다.
메모리를 들여다볼 수 있다면, 참조타입으로 할당된 메모리에는 참조값(어느 지점)이 저장되어 있습니다.

Reference type의 특성을 정리하면 다음과 같습니다.

- 해당하는 자료형: Primitive type이외의 모든 것 (함수, 배열 등등)
- Mutable (변경가능)
- 힙메모리에 저장
- Access by reference

Reference type의 예를 들어서 알아보겠습니다.

```javascript
let car = {
  type: 'SUV',
  name: 'gv80',
};

let myCar = car;

myCar.name = 'Traverse';

console.log(car.name); // Traverse
console.log(myCar.name); // Traverse
```

1. 먼저 car라는 오브젝트를 만들고, type과 name을 할당합니다.
2. 새로운 myCar라는 변수를 만들고, car의 값을 할당했습니다.
3. 그다음 myCar의 name값을 'Traverse'로 변경합니다.

console.log 결과에 따르면 두 객체의 name값 모두 'Traverse'를 출력합니다.

여기서 우리는 car와 myCar객체 모두 같은 값을 참조하고 있는 것을 알 수 있습니다. `객체의 참조값`이 저장되어 있는 것을 보여줍니다.

<br/>

### 4. 항등연산자(===)를 이용한 비교

위의 예시로 부족하다면 한가지 더 예를 들어 설명하겠습니다.

먼저 Pirimitive type(기본타입) 입니다.

```javascript
const myName = 'JOHN';
const yourName = 'JOHN';

myName === myName; // true
```

서로다른 두 변수에 같은 'JOHN'을 선언했습니다. 항등연산자(===) 비교 결과, `true`를 반환합니다. 이는 기본타입 비교기 때문에 `JOHN`과 `JOHN`이 같은가? 라는 질문과 같고, 결과는 true 입니다.

다음 Reference type(참조타입) 입니다.

```javascript
const me = {
  type: 'male',
  name: 'JOHN',
};

const you = {
  type: 'male',
  name: 'JOHN',
};

me === you; // false
```

서로다른 두 변수에 같은 속성/값의 오브젝트를 선언했습니다. 항등연산자(===) 비교 결과, `false`를 반환합니다. 이유는 서로 다른 메모리의 위치를 참조하고 있기 때문에 me객체의 `메모리 참조위치`와 you객체의 `메모리 참조위치`가 같은가? 라는 질문과 같기 때문입니다.

<br/>

### 5. 결론

기본타입과 참조타입의 구분과 개념은 javascript 입문할때도 중요하지만, 더 고급레벨로 가기위해서도 중요합니다. 언어가 다르더라도 기본, 참조의 개념은 비슷비슷 합니다. 두 자료형의 차이를 이해하면 다른언어의 이해에도 도움이 되고 더 나은 코드작성을 할 수 있을거라 생각합니다.
