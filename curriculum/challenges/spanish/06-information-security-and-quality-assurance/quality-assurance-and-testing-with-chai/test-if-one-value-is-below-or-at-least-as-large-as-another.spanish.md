---
id: 587d824c367417b2b2512c4e
title: Test if One Value is Below or At Least as Large as Another
challengeType: 2
videoUrl: ''
localeTitle: Probar si un valor está por debajo o al menos tan grande como otro
---

## Description
<section id="description"> Como recordatorio, este proyecto se está construyendo sobre el siguiente proyecto de inicio en <a href="https://glitch.com/#!/import/github/freeCodeCamp/boilerplate-mochachai/">Glitch</a> , o clonado desde <a href="https://github.com/freeCodeCamp/boilerplate-mochachai/">GitHub</a> . .isBelow () =&gt; a &lt;b, .isAtLeast =&gt; a&gt; = b </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Todas las pruebas deben pasar
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=8").then(data => {assert.equal(data.state,"passed"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: Elija la aserción correcta - isBelow vs. isAtLeast
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=8").then(data => {  assert.equal(data.assertions[0].method, "isAtLeast", "5 is at least (>=) 5"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: Elija la aserción correcta - isBelow vs. isAtLeast
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=8").then(data => {  assert.equal(data.assertions[1].method, "isAtLeast", "2 * Math.random() is at least 0"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: Elija la aserción correcta - isBelow vs. isAtLeast
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=8").then(data => {  assert.equal(data.assertions[2].method, "isBelow", "1 is smaller than 2"); }, xhr => { throw new Error(xhr.responseText); })'
  - text: Elija la aserción correcta - isBelow vs. isAtLeast
    testString: 'getUserInput => $.get(getUserInput("url") + "/_api/get-tests?type=unit&n=8").then(data => {  assert.equal(data.assertions[3].method, "isBelow", "2/3 (0.6666) is smaller than 1"); }, xhr => { throw new Error(xhr.responseText); })'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
