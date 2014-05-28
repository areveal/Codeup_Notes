#Day 17

##Jason

###Scope
* global variables can be declared outside of and refferred inside of functions. (unlike PHP).
* The reverse is not true. Variables defined inside functions cannot be seen outside the function.
* Global functions can be manipulated inside of a function
* Functions can also be called before the function was actually created.
 
####Hoisting
Anything declared with var is subject to hoisting. **BEWARE OF ACCIDENTAL HOISTING**

#### Functiom creation
```
function function_name() {
	code...;
}
```
or
```var function_name = function() {
	code...;
}
```

####IIFE
```
(function() {
	code...;
})();
```
this function will run itself!! **Note the syntax**

###Arrays
```
var array = [...];
```

####Length of Arrays
`array.length` will give you the length of the array
*No such thing as associative arrays in JS.*

###For Each
```
array.forEach(function(element,index,array){
	code...;
});
```

##Ben

####Adding elements
`array.push(element)`: puts element at the end of array
`array.pop()`: takes the last element off the array. returns element popped value
`array.unshift(element)`: puts element at the beginning of the array
`array.shift()`: takes the first element off the array

####Finding elements within arrays
`array.indexOf(element)`: returns the index of the element. *-1 if not found*

####Splice
`array.splice(element,num)`: removes the num of elements starting at element parameter.
`array.splice(element1,0,element2)`: adds element2 before element1.
`array.splice(element1,1,element2)`: replaces element1 with element2.
* Splice isn't limited by the number of insertions or deletions you want to do.

####Other Stuff
* `array.reverse()` : reverses the array;
* `array.sort()` : sorts array alphabetically (or with methods).

**Method Nesting**
* You can nest methods into a chain i.e. `array.reverse().sort()`.

####Join
`array.join(glue)` : same function as implode PHP.

####Splitting
`array.split(delimeter)` : same function as implode in PHP.