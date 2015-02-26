#Front-end Course Questions

## Table of Contents

  1. [General Questions](#general-questions)
  1. [HTML Questions](#html-questions)
  1. [CSS Questions](#css-questions)
  1. [JS Questions](#js-questions)
  1. [Network Questions](#network-questions)
  1. [Coding Questions](#coding-questions)

#### General Questions:

* What did you learn yesterday/this week?


* What is a recent technical challenge you experienced and how did you solve it?


* Talk about your preferred development environment.
 

* Which version control systems are you familiar with?
 

* Can you describe your workflow when you create a web page?
 

* If you have 5 different stylesheets, how would you best integrate them into the site?
 

* Can you describe the difference between progressive enhancement and graceful degradation?
 

* Describe how you would create a simple slideshow page.


* Explain the importance of standards and standards bodies.


* Explain what ARIA and screenreaders are, and how to make a website accessible.



#### HTML Questions:

* What does a `doctype` do?


* What's the difference between standards mode and quirks mode?


* What kind of things must you be wary of when design or developing for multilingual sites?


* What are `data-` attributes good for?


* Consider HTML5 as an open web platform. What are the building blocks of HTML5?



* Describe the difference between a `cookie`, `sessionStorage` and `localStorage`.



#### CSS Questions:

* What is the difference between classes and ID's in CSS?


* What's the difference between "resetting" and "normalizing" CSS? Which would you choose, and why?


* Describe Floats and how they work.


* Describe z-index and how stacking context is formed.


* What are the various clearing techniques and which is appropriate for what context?


* How do you serve your pages for feature-constrained browsers?
  * What techniques/processes do you use?
  

* What are the different ways to visually hide content (and make it available only for screen readers)?


* Have you ever used a grid system, and if so, what do you prefer?

* Have you used or implemented media queries or mobile specific layouts/CSS?

* Any familiarity with styling SVG?


* How do you optimize your webpages for print?


* What are some of the "gotchas" for writing efficient CSS?


* What are the advantages/disadvantages of using CSS preprocessors?
  * Describe what you like and dislike about the CSS preprocessors you have used.
  

* How would you implement a web design comp that uses non-standard fonts?


* Explain how a browser determines what elements match a CSS selector.



* Explain your understanding of the box model and how you would tell the browser in CSS to render your layout in different box models.



* What does ```* { box-sizing: border-box; }``` do? What are its advantages?


* List as many values for the display property that you can remember.


* What's the difference between inline and inline-block?


* What's the difference between a relative, fixed, absolute and statically positioned element?


* The 'C' in CSS stands for Cascading.  How is priority determined in assigning styles (a few examples)?  How can you use this system to your advantage?



* Have you played around with the new CSS Flexbox or Grid specs?


* How is responsive design different from adaptive design?


* Have you ever worked with retina graphics? If so, when and what techniques did you use?



#### JS Questions:

* Explain event delegation


* Explain how `this` works in JavaScript


* Explain how prototypal inheritance works



* Explain why the following doesn't work as an IIFE (Immediately-invoked function expression): `function foo(){ }();`.
  * What needs to be changed to properly make it an IIFE?



* What's the difference between a variable that is: `null`, `undefined` or `undeclared`?
  * How would you go about checking for any of these states?



* What is a closure, and how/why would you use one?



* What's a typical use case for anonymous functions?



* How do you organize your code? (module pattern, classical inheritance?)




* What's the difference between host objects and native objects?



* Difference between: `function Person(){}`, `var person = Person()`, and `var person = new Person()`?



* What's the difference between `.call` and `.apply`?



* Explain `Function.prototype.bind`.



* What's the difference between feature detection, feature inference, and using the UA string?



* Describe event bubbling.




* Why is extending built in JavaScript objects not a good idea?




* Difference between document load event and document ready event?


* What is the difference between `==` and `===`?



* Make this work:
```javascript
duplicate([1,2,3,4,5]); // [1,2,3,4,5,1,2,3,4,5]
```





* Why is it called a Ternary expression, what does the word "Ternary" indicate?



* What is `"use strict";`? what are the advantages and disadvantages to using it?



* Create a for loop that iterates up to `100` while outputting **"fizz"** at multiples of `3`, `"buzz"` at multiples of `5` and **"fizzbuzz"** at multiples of `3` and `5`



* Why is it, in general, a good idea to leave the global scope of a website as-is and never touch it?



* Why would you use something like the `load` event? Does this event have disadvantages? Do you know any alternatives, and why would you use those?




#### Network Questions:

* Do your best to describe the process from the time you type in a website's URL to it finishing loading on your screen.




* Can you explain the difference between `GET` and `POST`?




#### Coding Questions:

*Question: What is the value of `foo`?*
```javascript
var foo = 10 + '20';
```



*Question: How would you make this work?*
```javascript
add(2, 5); // 7
add(2)(5); // 7
```



*Question: What value is returned from the following statement?*
```javascript
"i'm a lasagna hog".split("").reverse().join("");
```





*Question: What is the value of `window.foo`?*
```javascript
( window.foo || ( window.foo = "bar" ) );
```





*Question: What is the outcome of the two alerts below?*
```javascript
var foo = "Hello";
(function() {
  var bar = " World";
  alert(foo + bar);
})();
alert(foo + bar);
```





*Question: What is the value of `foo.length`?*
```javascript
var foo = [];
foo.push(1);
foo.push(2);
```





