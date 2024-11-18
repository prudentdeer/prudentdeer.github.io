---
layout: post
title: CSS의 nth selector(nth-child, nth-of-type)
category: ['Old Posts']
published: false
keywords:
  - nth selector
  - nth-child
  - css selector
  - nth-of-type
---

### 1. CSS nth selector에 대해서

HTML을 작성할 때, 연속된 `<div>`나 `<li>`를 작성할 때 특정 순서의 요소만 선택해야되는 경우가 있다. 
CSS에서는 크게 nth-child, nth-of-type 두 가지 종류의 셀렉터를 제공한다. 
nth-child와 nth-of-type은 자주 쓰지않기 떄문에, 쓸때마다 헷갈리는 경우가 있는데 미리 정리해두도록 한다.

<br/>

### 2. nth-child

의미론적으로 선택자를 잘 만들었기에 이름만 봐도 유추가 어느정도 가능하다.

nth-child의 경우, 부모의 자식이 딸이건 아들이건간에 몇번째 자식인지 우선적으로 따진다.
HTML로 말하면, 자식에 오는 요소들이 `<div>`이건, `<li>`이건, `<p>` 혹은 등등 어떤 것이 오던지간에 몇번째 오는 요소인지를 먼저 선택한다는 것이다.

간단한 예시로 이해해보자.

```html
<style>
  .parent .child:nth-child(3) { background: red; }
</style>

<div class="parent">
    <li class="child">첫번째 자식</li>        // .parent .child:nth-child(1)
    <p class="child">두번째 자식</p>          // .parent .child:nth-child(2)
    <span class="child">세번째 자식</span>    // .parent .child:nth-child(3)
    <div class="child">네번째 자식</div>      // .parent .child:nth-child(4)
    <li class="child">다섯번째 자식</li>      // .parent .child:nth-child(5)
    <div class="child">여섯번째 자식</div>    // .parent .child:nth-child(6)
  </div>
```

parent 아래의 child 요소들은 주석에 표시된 선택자들이 된다. 실제 적용 결과는 아래와 같다.

<style>
  .parent { background-color: #f1f3f5; }
  .parent .child:nth-child(3) { background: red; }
</style>
<body>
  <div class="parent">
    <li class="child">첫번째 자식</li>
    <p class="child">두번째 자식</p>
    <span class="child">세번째 자식</span>
    <div class="child">네번째 자식</div>
    <li class="child">다섯번째 자식</li>
    <div class="child">여섯번째 자식</div>
  </div>
</body>

.parent 의 .child 중 3번째인 '세번째 자식'이 선택된것을 알 수 있다. 

클래스명으로 지정을 했지만 만약에 tag명으로 한다면 결과가 다르다. 또 다른 예시를 보자.

```html
<style>
  .parent li:nth-child(2) { background: red; }
</style>

<div class="parent">
    <li>첫번째 자식</li>
    <p>두번째 자식</p>
    <span>세번째 자식</span>
    <div>네번째 자식</div>
    <li>다섯번째 자식</li>
    <div>여섯번째 자식</div>
  </div>
```

.parent 아래의 li 요소중 두번째인 '다섯번째 자식'에 적용되어야 할 것 같은데, 적용이 되지 않는다.

<style>
  .parent { background-color: #f1f3f5; }
  .parent li:nth-child(2) { background: red; }
</style>
<body>
  <div class="parent">
    <li>첫번째 자식</li>
    <p>두번째 자식</p>
    <span>세번째 자식</span>
    <div>네번째 자식</div>
    <li>다섯번째 자식</li>
    <div>여섯번째 자식</div>
  </div>
</body>

이유는 앞서 말했다시피, nth-child의 경우 타입을 상관하지 않는다. 자식이면 아들이든 딸이든 순서로 우선 선택한다.
따라서 nth-child(2)를 찾으니 '두번째 자식'이 나왔지만, 규칙을 적용하려니 `.parent li`에 해당하지 않는 `<p>`이기 때문에 해당 CSS는 적용되지 않는다는 말이다.

그러면, 나는 .parent 아래의 li 요소들 중 두번째를 선택하고 싶으면 어떻게 할까? 그럴때 `nth-of-type` 선택자를 사용한다.

<br/>

### 3. nth-of-type

nth-of-type의 경우, 아들인지 딸인지 확인하는 것이 우선이다. 그 뒤 순서를 적용한다.
HTML로 말하면, 자식에 오는 요소들 중 `<div>` 중에 몇번째인지, `<li>` 요소들 중에 몇번째인지 선택할 때 사용한다.

이것도 간단한 예시로 이해해보자.

```html
<style>
  .parent span:nth-of-type(2) { background: red; }
</style>

<div class="parent">
    <li>첫번째 자식</li>
    <p>두번째 자식</p>
    <span>세번째 자식</span>
    <div>네번째 자식</div>
    <li>다섯번째 자식</li>
    <span>여섯번째 자식</span>
  </div>
```

.parent 아래의 span 요소중 2번째인 '여섯번째 자식'에 적용된 것을 확인 할 수 있다.

<style>
  .parent { background-color: #f1f3f5; }
  .parent span:nth-of-type(2) { background: red; }
</style>
<body>
  <div class="parent">
    <li>첫번째 자식</li>
    <p>두번째 자식</p>
    <span>세번째 자식</span>
    <div>네번째 자식</div>
    <li>다섯번째 자식</li>
    <span>여섯번째 자식</span>
  </div>
</body>

nth-of-type의 경우, 요소부터 필터링 후, 순서를 체크하여 적용되는 것을 알수있다.

<br/>

### 4. 결론

- nth-child(n): 몇번째 요소인지가 우선필터, 그다음 타입 적용
- nth-of-type(n): 어떤 타입인지가 우선필터, 그다음 n번째에 적용 

정확한 개념을 알고있지 않으면 자주사용하지 않기 때문에 헤멜 수 있다. `nth-child`와 `nth-of-type`의 적용 우선순위를 잘 기억해두자.
