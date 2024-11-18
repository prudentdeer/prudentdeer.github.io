---
layout: post
title: Javascript/JQuery array distinct
category: ['Old Posts']
published: false
keywords:
  - javascript
  - jQuery
  - array distinct
  - 배열 중복제거
---

배열에 중복요소가 있는지 체크

```javascript
Array.prototype.distinct = function() {
    var a = this.concat();
    for(var i=0; i<a.length; ++i) {
        for(var j=i+1; j<a.length; ++j) {
            if(a[i] === a[j])
                a.splice(j--, 1);
        }
    }
    return a;
};
```
