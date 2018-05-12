# JS Questions:

* Explain event delegation
    Attaching event listeners to multiple elements - inefficient and memory-intensive
    Instead, attach event listener to a parent container where your elements are nested.
* Explain how `this` works in JavaScript
    this refers to whatever executes the function and it is always read only.
    global: window
    object: object
    function:

* Explain how prototypal inheritance works
    All functions contain prototypes.

* What's the difference between a variable that is: `null`, `undefined` or undeclared?
    undefined is a variable that is declared but does contain value.
    null is an object that has a value of no value or falsy.
    undeclared is a variable that was never declared in the code so it doesn't exist.
  * How would you go about checking for any of these states?
    undeclared vs undefined - no way to check
      - do typeof undefinedVariable === "undefined"
      - nullVariable === null
* What is a closure, and how/why would you use one?

* Can you describe the main difference between a `forEach` loop and a `.map()` loop and why you would pick one versus the other?
    forEach - performs operations on each array element
    map - returns a new array that has contains transformed elements based on an operation
* What's a typical use case for anonymous functions?
    a function that is set to a variable.
    when you want to re-use a function inside another function and is not needed anywhere else.

* How do you organize your code? (module pattern, classical inheritance?)
  module pattern
    loosely coupled function and classes
  classical inheritance
    object-oriented
* What's the difference between host objects and native objects?

* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?

* What's the difference between `.call` and `.apply`?

* Explain `Function.prototype.bind`.

* Explain Ajax in as much detail as possible.

* What are the advantages and disadvantages of using Ajax?

* Explain how JSONP works (and how it's not really Ajax).

* Have you ever used JavaScript templating?
  * If so, what libraries have you used?
    Handlebars
      - use if-else statements to display html elements.
      - use each statements to loop through data and display html elements
      - contains scoping
      - pass in objects
    AngularJS templates
      - can call scope functions
      - declare scope models which will have two way binding in the html
* Explain "hoisting".
  javascript behavior where function declarations and variable declarations are moved to the top of the scope
* Describe event bubbling.
   behavior in which the order of events captured in nested elements.
* What's the difference between an "attribute" and a "property"?
   attribute vs property
* Why is extending built-in JavaScript objects not a good idea?
* Difference between document load event and document DOMContentLoaded event?
* What is the difference between `==` and `===`?
  `==` check if they are equal in value
  `===` check if they are equal in value and type
  type coercion
    true == 1
      - true will convert to 1 and become true.
    boolean == integer
      - boolean will convert to integer
* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```
* Why is it called a Ternary operator, what does the word "Ternary" indicate?
  ternary - composed of three parts

* What is `"use strict";`? what are the advantages and disadvantages to using it?
  use strict
    - throws exceptions on common javascript errors
    - cannot implicitly declare variables
    - cannot assign to a read only variable
* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, **"buzz"** at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`
    -
* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?
* Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?
* Explain what a single page app is and how to make one SEO-friendly.
  - Decrease load time and/or weight
  - Increased chance of over complicating
  - Services over page handling
  - Deferred loading
    - deferr the load time of an ajax process
* What is the extent of your experience with Promises and/or their polyfills?
  Promises are a way to
  Promise.all
    - resolves when all promises resolve or the first promise rejects
  Promise.race
    - resolves when one of the promises resolves or reject in a set of promises
  Promise.finally
    - same as catch or then
  Promise.reject
    - rejects a promise
  Promise.resolve
    - resolves a promise
* What are the pros and cons of using Promises instead of callbacks?

* What are some of the advantages/disadvantages of writing JavaScript code in a language that compiles to JavaScript?
* What tools and techniques do you use debugging JavaScript code?
* What language constructions do you use for iterating over object properties and array items?
* Explain the difference between mutable and immutable objects.
  * What is an example of an immutable object in JavaScript?
  * What are the pros and cons of immutability?
  * How can you achieve immutability in your own code?
* Explain the difference between synchronous and asynchronous functions.
* What is event loop?
  * What is the difference between call stack and task queue?
* Explain the differences on the usage of `foo` between `function foo() {}` and `var foo = function() {}`
* What are the differences between variables created using `let`, `var` or `const`?
  - let - declares a variable where you can change the value
  - const - declares a variable where you can't change the value
  - var - declares a variable
* What are the differences between ES6 class and ES5 function constructors?
* Can you offer a use case for the new arrow `=>` function syntax? How does this new syntax differ from other functions?
* What advantage is there for using the arrow syntax for a method in a constructor?
* What is the definition of a higher-order function?
* Can you give an example for destructuring an object or an array?
* ES6 Template Literals offer a lot of flexibility in generating strings, can you give an example?
* Can you give an example of a curry function and why this syntax offers an advantage?
* What are the benefits of using `spread syntax` and how is it different from `rest syntax`?
* How can you share code between files?
* Why you might want to create static class members?
