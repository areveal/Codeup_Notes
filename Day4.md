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
example
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







