<style>
details.listClass > summary {
	font-weight: bold;
}
details.listClass > ul {

}
details.listClass > ul > li > a {
	color: lightgray;
}
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

### Event-Based
This condition will only be triggered by and event.

<details class=colClass>
<summary> Event Parameters </summary>

### Name
The name of the parameter 

### Type
The datatype that will be used for the parameter

</details>
<details class=colClass> 
<summary> Blocks (If and Then)</summary>

### If Block
The If block will go check the condition statements that is given, and if all of the condtions are true, then all of the "then sets" and "then dos" will execute.

### Then Set Block
The block will set a certain field property to a certain target type that can be chosen.This block is executed when the If conditions before it is true. 

### Then Do Block
The block will do an event action after the if block conditions are true. 

### Add Set Value Action
If the condition for the blocks are true, then this block will execute. This block will set a certain field's property.

### Add Condition Statement
This is added to an if block. This will add another true or false condition to the if block.

### Add Condition
Creates another If block, with all of the functions of the if block. 

### AND
If the primary condition and the secondary condition are true then the whole condition is true, otherwise false.

### OR 
If either the primary condition or the secondary condition are true or both conditions are true, then the whole condition is true, otherwise false.

</details>



### Form Element
A field that is apart of the form being edited. __NOTE:__ If field is inside a form repeater it will show a __*__ next to its name, the block will prompt the option for which instance will the if block get it's information from.
<details class=listClass>
<summary> 
Fields with links to properties.
</summary>
<ul class=>
<li><a href="#/definition/subform.md"> Subform </a></li>

<li><a href="#/definition/single-text-field.md">Single Line Text field</a></li>

<li><a href="#/definition/multi-line-text-area.md"> Multi-Line Text Area</a></li>

<li><a href="#/definition/display-content.md"> Display Content </a></li>

<li><a href="#/definition/checkbox.md"> Checkbox </a></li>

<li><a href="#/definition/checkbox-list.md"> Checkbox List </a></li>

<li><a href="#/definition/radio.md"> Radio </a></li>

<li><a href="#/definition/select-dropdown.md"> Select Dropdown </a></li>

<li><a href="#/definition/multi-select-dropdown.md"> Multi-Select Dropdown </a></li>

<li><a href="#/definition/date.md"> Date </a></li>

<li><a href="#/definition/date-time.md"> Date/Time </a></li>

<li><a href="#/definition/file.md"> File </a></li>

<li><a href="#/definition/phone.md"> Phone </a></li>

<li><a href="#/definition/form-repeater.md"> Form Repeater </a></li>

<li><a href="#/definition/signature.md"> Signature </a></li>

<li><a href="#/definition/geolocation.md"> Geolocation </a></li>

<li><a href="#/definition/linked-clone.md"> Linked Clone </a></li>

<li><a href="#/definition/button.md"> Button </a></li>

<li><a href="#/definition/color-picker.md"> Color Picker </a></li>
</details>

<details class=colClass>
<summary> Instance to target in repeater</summary>
<div> The index or instance of the form repeater you want to extract the field from. </div>
<details>

<summary> Any Instance</summary>
<div> The form element extracts from any one of the instances.</div>
</details>

<details>
<summary> All Instance </summary>
<div> The form element extracts all of the instances </div>
</details>

<details>
<summary> First Instance </summary>
<div> The form element is extracted from the first instance </div>
</details>

<details>
<summary> Last Instance </summary>
<div> The form element is extracted from the last instance </div>
</details>

<details>
<summary> Instance at Index </summary>
<div> The form element is etracted from specified index in the repeater </div>

</details>
</details>

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
<div> Compares two times and returns true if the 
two dates are the same dates, otherwise false.</div>
</details>

<details>
<summary> Does Not Equal </summary>
<div> Compares two times and returns true if the 
two dates are not the same dates, otherwise false.</div>
</details>

<details>
<summary> Is Before </summary>
<div> Compares two times and returns true if the primary date is before the second date, otherwise returns false. </div>
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

<details>
<summary> Event Parameters* </summary>
<div> The value comes from a event parameter</div>
</details>

</details>


<details class=colClass>
<summary> Events </summary>
<div>  </div>

<details>
<summary> Trigger Event Rules </summary>
<div> Use another event rule to be used as an event</div>
<details>
<summary>Event Rule</summary>
<div>The specific rule that will be triggered</div>
</details>
</details>

<details>
<summary> Create repeater instance </summary>
<div> Create another repeater instance </div>
<details>
<summary>Repeater</summary>
<div>A specific repeater inside of the form</div>
</details>

</details>

<details>
<summary> Open compact repeater </summary>
<div> Open up a compact repeater as an event </div>
<details>
<summary>Repeater</summary>
<div>A specific repeater instance inside of the form</div>
<details>
<summary>Index</summary>
<div>The specified index in which stores the repeater wanted. </div>
</details>

</details>

</details>

<details>
<summary> Close compact repeater </summary>
<div> Close a specific compact repeater</div>
</details>

<details>
<summary> Show alert dialog</summary>
<div> Alerts the user on the rule they triggered</div>
<details>
<summary>Title</summary>
<div>The title of the alert dialog</div>
</details>
<details>
<summary>Message</summary>
<div>The message that will under the title</div>
</details>
<details>
<summary>Accept Event</summary>
<div>The event that will trigger after the accepting</div>
</details>

</details>

<details>
<summary> Show confirm dialog </summary>
<div> Gets the user's confirmation for them </div>
<details>
<summary>Title</summary>
<div>The title of the alert dialog</div>
</details>
<details>
<summary>Message</summary>
<div>The message that will under the title</div>
</details>
<details>
<summary>Accept Event</summary>
<div>The event that will trigger after the accepting</div>
</details>
<details>
<summary> Cancel Event Rule</summary>
<div> The event that will trigger after canceling the confirmation box</div>
</details>
</details>

<details>
<summary> Open URL </summary>
<div> Opens a URL</div>
<details>
<summary>URL</summary>
<div>The URL that will opened</div>
</details>

</details>

<details>
<summary> Send Email </summary>
<div> Sends and email as an event</div>
<details>
<summary>Recipients</summary>
<div>The email addresses that this email will be sent to</div>
</details>
<details>
<summary>Email Subject</summary>
<div> The subject of the email</div>
</details>
<details>
<summary>Email Message</summary>
<div>The content of the email</div>
</details>
<details>
<summary>Attachments</summary>
<div>The files that will be attached to the email</div>
</details>

</details>

<details>
<summary> Create linked form</summary>
<div> </div>
<details>
<summary>Linked Form Id</summary>
<div>The id of the form that will be created.</div>
</details>

</details>

<details>
<summary> Change form status</summary>
<div> Change the status of the form </div>
<details>
<summary>Status ID</summary>
<div>The ID of the status that will be changed</div>
</details>
<details>
<summary>Prompt User</summary>
<div>A prompt to let the user confirm action</div>
</details>
<details>
<summary>Custom Dialog</summary>
<div>A set of text for the prompt</div>
</details>

</details>

<details>
<summary> Duplicate repeater instance </summary>
<div> Duplicates the current instance of the repeater and adds it to the repeater </div>
<details>
<summary>Repeater</summary>
<div>The repeater in which the form will be duplicated from</div>
</details>
<details>
<summary>Index</summary>
<div>The index of the form in the list</div>
</details>
<details>
<summary>Exclude Field ID</summary>
<div>Exclude any fields that will not be duplicated in the repeater</div>
</details>

</details>

</details>

---
