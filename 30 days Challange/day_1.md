#  Solution Code

## Problem 2667:

Q. Write a function createHelloWorld. It should return a new function that always returns "Hello World".

``` Javascript

var createHelloWorld = function() {

    
    return function(...args) {
       return "Hello World";
    }
};


  const f = createHelloWorld();
  f(); // "Hello World"