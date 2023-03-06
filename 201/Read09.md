# Javascript : Data Structures Overview

A data structure is a format to organize, manage, and store data. - We should be able to access and modify the data.

JS has primitive and non-primitive data structures.


### Arrays

https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array

A collection of items stored in contiguous memory. Items can be accessed through index number. Index starts at 0. Length property of array is the number of items(elements) the array contains. 

*Javascript*, as a language, allows our arrays to contain elements of different primitive types, such as strings or numbers, and the length can dynamically change.

We can also store other arrays in arrays - multidimensional arrays.

In JS, arrays come with their own native properties and methods. join(), slice(), indexOf(), push(), splice(), flat() ect. *Remember, in JS, properties beginning with a digit need to be accessed with bracket notation*

```
// So we can do: 

let array = [1,2,3];

console.log(array[0])

// but not:

console.log(array.0)
```

I'll write more notes on the native array methods in another notes page.

When we change our array with a method, all the indexes of the elements have to be change to match the updated array. This has a computational cost. Arrays are good for individual values and to delete or add values to the *end* of the structure. But if we want to change any part of our data, we should use a different data structure.

### Objects

Data Structure that allows us to have key-value pairs.

Also called a map, dictionary or hash-table in other programming languages. 

```
let object = {
  one: "wow",
  two: "great",
  three: "object!"
  four: function() {console.log("I'm a function")}
}
```
Can have two keys with the same name.

Objects can store both values and functions. When talking about objects, values are called properties, and functions are called methods.

Methods must be called with dot notation, properties can be called with bracket or dot notation.
```
console.log(object["one"])

// or 

console.log(object.one)

both return "wow". 
```
