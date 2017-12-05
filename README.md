# vue-overflow-scroll

Scroll automatically when the element is overflow.

support `vue 2.0`

## Installation

### NPM(recommended)

`npm install vue-overflow-scroll -D`

<br>

## Get Started

```js
// ES6
import Vue from 'vue'
import VueOverflowScroll from 'vue-overflow-scroll'

Vue.use(VueOverflowScroll)
```

Directive v-overflow-scroll then can be used in your Component.

```html
<template>
  <div v-overflow-scroll="true" scroll-to="last-child">
    ...
  </div>
<template>
...
```

then when the div can scroll-y,then it can scroll to last child.