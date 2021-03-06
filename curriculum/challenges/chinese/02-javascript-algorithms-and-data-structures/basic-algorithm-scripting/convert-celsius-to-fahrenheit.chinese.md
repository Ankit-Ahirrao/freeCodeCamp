---
id: 56533eb9ac21ba0edf2244b3
title: Convert Celsius to Fahrenheit
challengeType: 1
isRequired: true
videoUrl: ''
localeTitle: 将摄氏温度转换为华氏温度
---

## Description
<section id="description">从摄氏温度转换为华氏温度的算法是以摄氏度乘以<code>9/5</code>，再加上<code>32</code> 。您将获得一个参数<code>celsius</code>代表着摄氏温度。使用已准备好代表华氏温度的变量<code>fahrenheit</code>，将<code>celsius</code>摄氏温度变量值兑换成华氏温度值，然后存储在<code>farenheit</code>变量里。使用以上提到的算法将摄氏温度转换为华氏温度。不需要过多担心函数和返回语句，因为它们将会在未来的挑战中加以解释。目前，只需使用您已经学过的运算符。 </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: <code>convertToF(0)</code>应该返回一个数字
    testString: 'assert(typeof convertToF(0) === "number", "<code>convertToF(0)</code> should return a number");'
  - text: <code>convertToF(-30)</code>应该返回值<code>-22</code>
    testString: 'assert(convertToF(-30) === -22, "<code>convertToF(-30)</code> should return a value of <code>-22</code>");'
  - text: <code>convertToF(-10)</code>应该返回值<code>14</code>
    testString: 'assert(convertToF(-10) === 14, "<code>convertToF(-10)</code> should return a value of <code>14</code>");'
  - text: <code>convertToF(0)</code>应返回值<code>32</code>
    testString: 'assert(convertToF(0) === 32, "<code>convertToF(0)</code> should return a value of <code>32</code>");'
  - text: <code>convertToF(20)</code>应返回值<code>68</code>
    testString: 'assert(convertToF(20) === 68, "<code>convertToF(20)</code> should return a value of <code>68</code>");'
  - text: <code>convertToF(30)</code>应返回值<code>86</code>
    testString: 'assert(convertToF(30) === 86, "<code>convertToF(30)</code> should return a value of <code>86</code>");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='js-seed'>

```js
function convertToF(celsius) {
  let fahrenheit;
  return fahrenheit;
}

convertToF(30);

```

</div>



</section>

## Solution
<section id='solution'>

```js
function convertToF(celsius) {
  let fahrenheit = celsius * 9/5 + 32;

  return fahrenheit;
}

convertToF(30);
```
</section>
