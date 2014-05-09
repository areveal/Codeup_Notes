#Day 4 5/8/14

###This is pretty cool :)

##Ben B.

###is_bool

```
is_bool($var);
```
tests whether the passed value is a boolean or not.

###|| (double pipe)
```
||
```
The OR combination operator.

###Ternary Operator

This is crazy cool but crazy difficult to use and read!!

This is a shortcut for if else statements
```
[condition] ? [value if true] : [value is false];
```
#####example
```
$age = 22;
echo ($age >= 18) ? "yes!" : "no, try disney!";
```
will echo
```
yes!
```
#####LUNCH BREAK

## Chris

####Would it be possible to nest a ternary operator??
The answer is yes. While it looks atrocious it is possible to nest within ternary operators.
```
$is_admin = true;
$is_logged_on = true;
echo (is_logged_on)?($is_admin)?"You can make edits":"You must be an admin to make changes":"Please log on";
```
will echo
```
You can make edits
```
###While Loops
```
while(condition) {
	[command];
}
```
This command will be carried out **while** the condition is true. Unless the condition becomes false over repetition, the command will continue to run forever in what is called an *infinite loop*. Typically used with an increment or decriment command in order to satisfy the condition over time.

#####example
```
$a = 1;
while ($a <= 5) {
    echo "\$a is equal to {$a}\n";
    $a++;
}
```
will echo the result:
```
$a is equal to 1
$a is equal to 2
$a is equal to 3
$a is equal to 4
$a is equal to 5
```





