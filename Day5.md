#Day 5

##Jason
###CLI SAPI

* `STDOUT` is the standard output for the comp (usually the moniter).
* `STIN` is the standard input for the comp (usually the keyboard)
* `fwrite` tells the computer to output something.
* `fgets` allows the user to input something. Always assumes it is a string.


###The Pragmatic Programmer!!!
This is a must read for all programmers. Techniques and skills aquired on the journey of being a programmer.
####Rubber Duck Debugging
Explaining your code to the rubber duck in order to find mistakes. 

#####Lunch
**Tuesday evening Omar will be going over Mac and sublime tips!!**

###Lindsey
hit her up on linked in!

##Ben
###Random Numbers
Not actually random. Commonly referred to as sudo random numbers.

###Command Line Arguments
* `$argc` - contains a count of all the argument.
* `$argv` - contains an array of all values passed to PHP.
* Theses variables can be passed into your file as variables.

###For Loops
These are used on incremented loops. Any loop that are looping by a number set will most likely use a for loop.
```
for ([start value];[end value];[incrementer]) {
	[command];
}
```
for example
```
for ($i = 0; $i <= 100; $i += 2) {
    echo "\$i has a value of {$i}\n";
}
```
will echo
```
$i has a value of 0
$i has a value of 2
$i has a value of 4
.
.
.
$i has a value of 100
```