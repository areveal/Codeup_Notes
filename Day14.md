#Day 14

##Ben

###Text Area

`<textarea name="post_body">value goes here</textarea>` allows user to type text area. Is not self enclosed. 

####Attributes
rows="5" - sets rows to 5.

cols="120" - sets columns to 120.

###Types of Input
There are a lot of them
* hidden

###CheckBoxes
returns string if checked.
If not checked does key does not exist (this is what we will check for).
adding `checked` attribute automatically checks checkbox upon open.

####create an array with checkboxes
`name="...[]"` can be used in checkboxes to create an array. i.e.
```
<p>What operating systems have you used?</p>
<label for="os1"><input type="checkbox" id="os1" name="os[]" value="linux"> Linux</label>
<label for="os2"><input type="checkbox" id="os2" name="os[]" value="osx"> OS X</label>
<label for="os3"><input type="checkbox" id="os3" name="os[]" value="windows"> Windows</label>
```
will return an array of which boxes were checked.

###Radio
If the keys are the same between radio buttons, you will have to choose one of the listed elements. 
If the keys are different names they will allow you to choose multiple options.

##Chris

###