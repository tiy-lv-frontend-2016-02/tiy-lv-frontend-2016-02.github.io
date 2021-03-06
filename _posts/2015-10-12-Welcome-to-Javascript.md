---
layout: post
title: "Welcome to Javascript"
date: 2015-10-12 17:00:00 -0700
comments: false
published: false
---

# Welcome to JavaScript

> "Learn you a JavaScript, for great good"

JavaScript is an object-oriented computer programming language commonly used to create interactive effects within web browsers.

[The Origin of JavaScript (JS Jabber Podcast)](http://javascriptjabber.com/124-jsj-the-origin-of-javascript-with-brendan-eich/)


## Uses?

- Adding Fancy Page Interactions - [here](http://dev.sencha.com/playpen/ext-core-latest/examples/lightbox/)
- Full Featured Web Apps - [here](http://www.rdio.com/new/)
- Drawing & Animations - [here](http://raphaeljs.com/analytics.html)
- Interactive elements
- Build a full backend - [here](http://nodejs.org/)

## JavaScript Syntax

```js
document.getElementById('header');
```

- `document`: object
- `.`: property accessor
- `getElementById`: property (in this case, a function)
- `()`: function call
- `'header'`: parameter (in this case, a String)
- `;`: end of the statement


## Variables

Declare a variable

```js
var name;
```

Assign a value to a variable (initialize)

```js
name = 'Tim';
```

Shorthand (Declare and assign)

```js
var name = 'Tim';
```


## Statements

```js
var name = "Tim";
```

```js
console.log('Hi, my name is ' + name);
```

## Types
There are two types of "things" in JavaScript:
### Primitives
Primitives are simple values that can be passed around and referenced directly. They are kind of like cash. If you give someone a $5 bill, they have the money and they can use it immediately.

### Objects
Objects are more abstract "things". They are like checks. They're too complex to be passed around or referenced directly, you have to know how to use them to actually get the value out of them.

## Primitives

- String (immutable chunk of characters)

```js
var hello = "Good morning, Tim";
```

- Number (5, -20 or floats like 1.225)

```js
var age = 31;
var pi = 3.14;
var temp = -7;
```

- Boolean (true or false)

```js
var freezingIsFun = true;
var heightsAreAwesome = false;
var is_old = 31 > 30;
```


## Primitives

- Undefined (not yet defined)

```js
var nothing;
```

- Null (empty value)

```js
var nothing = null;
```


## Variables

- Begin with letters, $ or _
- Only contain letters, numbers, $ and _
- Case sensitive
- No reserved words - [here](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Lexical_grammar#Keywords)
- camelCase vs using _
- Choose a convention


## Expressions

> Variables can store the result of an expression

```js
var age = 2014 - 1983;
var greeting = "My name is Tim and I am " + age + " years old";
```

## Loose Typing

```js
// You can change me!
var x;
x = 31;
x = "Tim"
```

```js
// What happens here?
var x = 2 + "Tim";
```


## Comments

```js
var name = "Tim"; // Single Line Comment

/*
  Multi Line
  Comment
*/
var a = 1;
var b = 2;
var c = 1 + 2;
```

## Operators
- = (assignment)
- Number operators (+, -, /, *, ++, --, %)
- Compound assignments (+=, -=, *=, /*)
- String operator (+)

See https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators


## Type Coercion

When comparing values in Javascript using the double equals `==`, it will implictly convert the types and then compare the values only. So the values `Number(5)` and `String("5")` would be consider equal.

When comparing values in Javascript using the triple equals `===` it will not implicitly convert the types, if the values are of differnt types they will not be considered equal.

Implicit type coercion can lead to bugs so always use the triple equals `===` when comparing values.


## Functions

functions are mini programs inside the the main program that can be invoked at any time.

The syntax to declare a function is:

```javascript
function doSomething() {
  // do stuff...
}
```

The syntax to invoke a function is:

```javascript
doSomething();
```

when invoking these sub programs we call functions you can pass data in and get data back out.

To pass data in, you use parameters:

```javascript
function doSomething(parameter1, parameter2) {
  // do stuff...
}

doSomething("foo", 5);
```

To get data back, the function must `return` a value:

```javascript
function doSomething() {
  // do stuff...
  return 5;
}

var response = doSomthing();
```


## Resources

* [The Ultimate Guide to JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
* [Equality comparisons and sameness](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Equality_comparisons_and_sameness)