#Day 7
##Jason
Get used to having people review and criticize your code!

###Break and Continue
Using `break` will **exit** the current loop. For example:
```
for ($i = 1; $i <= 100; $i++) {
    echo $i . "\n";
    if ($i == 5) {
        break;
    }
}
```
will ouput:
```
1
2
3
4
5
```
You can break out of **multiple levels** of loops by incuding a number after the break i.e. `break 2` will break out of two levels of nesting.
---
Using `continue` will skip the rest of the loop and move to the next iteration **(go back to the beginning)**. For example
```
for ($i = 1; $i <= 10; $i++) {
    echo $i . "\n";
    if ($i % 2 == 0) {
        continue;
    }
    echo "^ that is an odd number.\n";
}
```
will ouput:
```
1
^ that is an odd number.
2
3
^ that is an odd number.
4
5
^ that is an odd number.
6
7
^ that is an odd number.
8
9
^ that is an odd number.
10
```
### Switch
Using `switch` allows us to go through multiple cases and output a different code for each case. i.e.
```
$value = 'Hello!';

switch (gettype($value)) {
    case 'integer':
        echo '$value is an integer';
        break;
    case 'float':
        echo '$value is a float';
        break;
    case 'boolean':
        echo '$value is a boolean';
        break;
    case 'array':
        echo '$value is an array';
        break;
    case 'null':
        echo '$value is null';
        break;
    case 'string':
        echo '$value is a string';
        break;
}
```
will ouput:
```
$value is a string
```

**dont forget the parts**
* `switch`
* `case`
* `break`
* `default`

