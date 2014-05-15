#Day 8

##Jason

###Functions!!!!!!
Functions!!!!!
```
function name($arg_1, $arg_2, /* ..., */ $arg_n) {
	// code goes here
}
```
For example
```
function adder($num_1 , $num_2) {
	echo $num_1 + $num_2;
}

adder(38,4);
```
will output `42`.

**NOTICE**
The variables created inside the function paramaters only exist inside the function. And variables created outside the
function cannot be referenced inside the function. This is referred to as **SCOPE**!!!

We can assign default variable values by assigning it in the paramaters of the function initiation. i.e.
`function($a,$b,$strict = true) {};` will default $strict = true if no variable is assigned when the function is called.

*What do we do when we want to pass an undefined amount of variables into a function??*


**Note**
PHP has a predetermined order of precedence in type casting for comparisons.

####Lunch

###Winslow Swart
Strategic Being

*Core Values
	1. Wisdom

##Ben

###Return
Allows us to get values back from within functions!
**NOTICE**
`return` will cause a function to leave immediately!



