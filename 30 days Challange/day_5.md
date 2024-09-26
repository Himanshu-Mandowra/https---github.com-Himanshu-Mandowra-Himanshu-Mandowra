#  Solution Code

## Problem 2635:

Q. Given an integer array arr and a mapping function fn, return a new array with a transformation applied to each element.

The returned array should be created such that returnedArray[i] = fn(arr[i], i).

Please solve it without the built-in Array.map method.

``` Javascript

var map = function(arr, fn) {
    const newArray = [];

    for(let i=0; i<arr.length; i++){
        newArray.push(fn(arr[i], i));
    }

    return  newArray;
};