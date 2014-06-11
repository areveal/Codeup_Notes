#Day 21... kinda

##Ben

###Event listeners
* `e.preventDefault();` this prevents the browser from doing whatever it thinks it needs to do next.
	* use this to keep the brower from jumping.

###Objects
```
//create object
new obj = {};

//creates property
obj.prob = 'something';

//creates function
obj.funct = function() {
	code + this.prop;
}

//calls function on object
obj.funct();
```

##Chris

###js and php

* `json_encode($php_something);` - allows us to encode from php to js

	* `,JSON_PRETTY_PRINT` - makes formatting look better in the transistion. paramater after php variable.

* `json_decode($js_stuff_as_php_variable)` - decodes it back to php

	* optional boolean paramater to set std objects back to associative array. `,true`.