#Day 6

##Ben

###Trim
```
trim(fgets(STDIN));
```
allows us to get rid of the return key that must be typed to input data along with any unecessary white space.

##Chris

###Foreach

```
foreach (array_expression as $value) {
    statement
}
```
The array expression is the array you are searching through and the $value is a variable you will be assigning within the foreach loop. 

For example:
```
foreach ($todos as $todo) {
	echo $todo . PHP_EOL;
}
```

This is **SUPER** helpful for iterating through arrays!!

You can also show the value's index by showing `foreach(array_expression as $key => $value)`


##HW

1.  Create an array of fruits (push *fruit.php* to git hub)
	* write a loop that prints the fruits
		* for and foreach
2. Modify the fruit array so that you have `fruitname => color`.
	*print out using foreach loop (i.e. 'Apples are red')

##Snippets
**Tools -> New Snippet -> edit the snippet and save

## Sublime shortcuts
*command + d will allow you to highlight the same word (variables usually) throughout the document.
*command + click will put your cursor over multiple lines