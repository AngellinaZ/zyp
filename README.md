﻿# ES6
* 参考[SimplyWenjing/ES6](https://github.com/SimplyWenjing/ES6)思维导图整理
* babel转码

## let
![let](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/let.png)

## const
![const](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/const.png)

## destructuring
* 规则：解构赋值的规则是，只要等号右边的值不是对象或数组，就先将其转为对象。由于undefined和null无法转为对象，所以对它们进行解构赋值，都会报错。
![变量的解构赋值](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/destructuring.png)

## 字符串的扩展
![字符串的扩展](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/String.png)

## 数值的扩展
![数值的扩展](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/Number.png)

## 数组的扩展
![数组的扩展](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/Array.png)

## 对象的扩展
![对象的扩展](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/Object.png)

## Promise
```js
const promise = new Promise ((resolve, rereject) => {
  if (/* 异步操作成功 */){
    return resolve(value);
  } else {
    return reject(error);
  }
})

promise.then((value) => {
  // success
}, (error) => {
  // failure
});
```
![对象的扩展](https://github.com/AngellinaZ/ES6/blob/master/Mind-mapping/Promise.png)

