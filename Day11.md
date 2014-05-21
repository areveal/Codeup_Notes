# Day 11 #

## Jason ##

### Exploding and Imploding ###
delimeter - the thing you are exploding/imploding around!!

i.e.

```
$physicists_string = 'Gordon Freeman, Samantha Carter, Sheldon Cooper, Quinn Mallory, Bruce Banner, Tony Stark';

$physicists\_array = explode(', ', $physicists\_string);

print\_r($physicists\_array);
```

will output 
```
Array
(
    [0] => Gordon Freeman
    [1] => Samantha Carter
    [2] => Sheldon Cooper
    [3] => Quinn Mallory
    [4] => Bruce Banner
    [5] => Tony Stark
)
```



##Ben

###Reading Files

`fopen($filename, mode)` - Opens a file, returns a file pointer.
		`r` - reads the file.
		`w` - 
`fread($handle, $length)` - Reads a file to a specific length using file pointer	
`filesize($filename)` - returns the size of a file.... duh
`fclose($handle)` - closes a handle to an open file pointer.


