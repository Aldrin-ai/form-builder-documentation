<style>
details.colClass > summary {
	font-size: 25px;
	font-weight: bold;
	margin-left: 0px;
	margin-bottom: 15px;
	margin-top: 15px;
}
details.colClass > div {
	font-size: 15px;
	margin-bottom: 5px;
	margin-left:15px;
}
details.colClass > details {
	margin-top: 10px;
	margin-bottom: 10px;
	margin-left: 15px;
	font-size: 15px;
}
details.colClass > details > summary {
	font-weight: bold;
	font-size: 20px;
}
details.colClass > details > details {
	margin-top: 5px;
	margin-bottom: 5px;
	margin-left: 15px;
}
details.colClass > details > details > summary {
	font-weight: bold;
	font-size: 15px;
}
details.colClass > details > details > div {
	margin-left: 20px;
}
details.colClass > details > div {
	margin-left: 15px;
}
details.colClass {
	margin-top: 30px;
}

</style>

# Rule Documentation
---
### Rule Name
The name of the rule being created

### Clone Rule
Creates a copy of the rule and adds it to the Form Rule collapsable.

### Delete Rule
Deletes the rule that is currently selected

### Enabled
The rule will be enabled throughout the form.

### Always True
The If blocks will always be true and will do any then sets or then dos.

<details class=colClass> 
<summary> Blocks (If and Then)</summary>

### If Block
The If block will go check the condition statements that is given, and if all of the condtions are true, then all of the "then sets" and "then dos" will execute.

### Add Condition Statement
This is added to an if block. This will add another true or false condition to the if block.

### Add Condition
Creates another If block, with all of the functions of the if block. 

### Then Set Block
The block will set a certain field property to a certain target type that can be chosen.This block is executed when the If conditions before it is true. 

### Add Set Value Action
If the condition for the blocks are true, then this block will execute. This block will set a certain field's property.

### AND
If the primary condition and the secondary condition are true then the whole condition is true, otherwise false.

### OR 
If either the primary condition or the secondary condition are true or both conditions are true, then the whole condition is true, otherwise false.

</details>



### Form Element
A field that is apart of the form being edited.

### Property
The properties from the field chosen in the form element. The properties will change depending on which field that is chosen. 

<details class=colClass>

<summary> Comparison </summary>
<div> 
This field will determine how the property field or field value will be compared to the target. <b> NOTE: Comparisons will be depended on what data type is being compared to. </b>
</div>

<details>

<summary> Number Comparisons </summary>

<details>
<summary> Equals </summary>
<div> Compares two numeric values and will return true if both numeric values are the same, otherwise false </div>
</details>

<details>
<summary> Does Not Equal </summary>
<div> Compares two numeric values and will return true if both numeric values are the different, otherwise false </div>
</details>

<details>
<summary> Is Less Than </summary>
<div> Compares two numeric values and will return true if primary form element value is less than the secondary value, otherwise false </div>
</details>

<details>
<summary> Is Greater Than </summary>
<div> Compares two numeric values and will return true if primary form element value is greater  than the secondary value, otherwise false </div>

</details>

<details>
<summary> Is Less Than or Equal To </summary>
<div> Compares two numeric values and will return true if primary form element value is less than or equal to the secondary value, otherwise false </div>

</details>

<details>
<summary> Is Greater Than or Equal To </summary>
<div> Compares two numeric values and will return true if primary form element value is greater than or equal to the secondary value, otherwise false </div>

</details>
</details>

<details>
<summary> String Comparisons </summary>

<details>
<summary> Is </summary>
<div> Compares two string values and will return true if the two strings are the same, otherwise false </div>
</details>

<details>
<summary> Is Not </summary>
<div> Compares two string values and will return true if the two strings are not the same, otherwise false.</div>
</details>

<details>
<summary> Contains</summary>
<div> Compares two string values and will return true if the secondary string 
can be found in the primary string, otherwise false </div>
</details>

<details>
<summary> Does Not Contain </summary>
<div> Compares two string values and will return true if the secondary string cannot be found in the primary string, otherwise false </div>
</details>

<details>
<summary>Length Equals</summary>
<div> Compares two string values and will return true if the length of the two strings are the same, otherwise false </div>
</details>

<details>
<summary> Length Does Not Equal</summary>
<div> Compares two string values and will return true if the length of the two strings are not the same, otherwise false </div>
</details>

<details>
<summary> Length Less Than </summary>
<div> Compares two string values and will return true if the length of the primary string is less than the length of the secondary string, otherwise false </div>
</details>

<details>
<summary> Length greater Than </summary>
<div> Compares two string values and will return true if the length of the primary string is greater than the length of the secondary string, otherwise false </div>

</details>

</details>


<details>
<summary>Array Comparisons</summary>

<details>
<summary> Is </summary>
<div> Compare two arrays and will return true if both lists/arrays are exactly the same, otherwise false. </div>
</details>

<details>
<summary> Is Not </summary>
<div> Compare two arrays and will return true if both lists/arrays are different, otherwise false. </div>
</details>

<details>
<summary> Contains </summary>
<div> Compare two arrays and will return true if the secondary list/array is inside the primary list/array, otherwise false. </div>

</details>

<details>
<summary> Does Not Contain </summary>
<div> Compare two arrays and will return true if the secondary list/array is not contained in the primary list/array, otherwise returns false.
</details>

<details>
<summary> Length Equals </summary> 
<div> Compare two arrays and will return true if the arrays/lists both have the same number of elements, otherwise returns false </div>
</details>

<details>
<summary> Length Does Not Equals </summary>
<div> Compare two arrays and will return true if the arrays/lists have a different number of elements, otherwise returns false </div>
</details>

<details>
<summary> Length Less Than </summary>
<div> Compare two arrays and will return true if the primary array/lists length is less than the length of the secondary array/list, otherwise returns false </div>
</details>

<details>
<summary> Length Greater Than </summary>
<div> Compare two arrays and will return true if the primary array/lists length is greater than the length of the secondary array/list, otherwise returns false </div>
<div> </div>
</details>
</details>


<details>
<summary> Boolean Comparisons </summary>
<details>
<summary> Is </summary>
<div> Compares two booleans and will return true if the boolean states (True or False) of the two booleans are the same, otherwise it will return false. </div> 
</details>

<details>
<summary> Is Not </summary>
<div> Compares two booleans and will return true if the boolean states (True or False) of the two booleans are not the same, otherwise it will return false. </div> 
</details>
</details>

<details>
<summary> Date Comparisons </summary>

<details>
<summary> Equals </summary>
<div> Compares two dates and returns true if the 
two dates are the same dates, otherwise false.</div>
</details>
<details>
<summary> Does Not Equal </summary>
<div> Compares two dates and returns true if the 
two dates are not the same dates, otherwise false.</div>
</details>

<details> 
<summary> Is Before </summary>
<div> Compares two dates and returns true if the primary date is before the second date, otherwise returns false. </div>
</details>

<details>
<summary> Is After </summary>
<div> Compares two dates and returns true if the primary date is after the second date, otherwise returns false. </div>

</details>
</details>

<details>
<summary> Time Comparisons </summary>
<details>
<summary> Equals </summary>
<div> Compares two dates and returns true if the 
two dates are the same dates, otherwise false.</div>
</details>

<details>
<summary> Does Not Equal </summary>
<div> Compares two dates and returns true if the 
two dates are not the same dates, otherwise false.</div>
</details>

<details>
<summary> Is Before </summary>
<div> Compares two dates and returns true if the primary date is before the second date, otherwise returns false. </div>
</details>

<details>
<summary> Is After </summary>
<div> Compares two times and returns true if the primary time is after the second time, otherwise returns false. </div>
</details>
</details>

<details>
<summary> Signature Comparisons </summary>

<details> 
<summary> Signature Completed </summary>
<div> Returns true if signature is completed, otherwise false. </div>
</details>

</details>

</details>

<details class=colClass>
<summary> Target Types </summary>
<div> The different types of values that can be used to compare conditions </div>

<details>
<summary> Value </summary>
<div>A value that can be set by the user</div>
</details>

<details>
<summary> Element Property </summary>
<div>A value that is taken from one of the field's properties.</div>
</details>

<details>
<summary> Calculation </summary>
<div> The value is created by a calculation </div>
</details>
</details>

---
