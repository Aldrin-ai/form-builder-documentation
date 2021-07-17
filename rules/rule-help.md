<style>
details.colClass > summary {
	font-size: 21px;
	font-weight: bold;
	margin-left: 0px;
	margin-bottom: 15px;
}
details.colClass > * {
	margin-left:15px;
}
</style>

# Rule Documentation
---
### Rule Name
The name of the rule being created

### Clone Rule
Creates a copy of the rule and adds it to the Form Rule collapsable.

### Delete Rule
Deletes the rule that is currently selected:w
<details class=colClass> 
<summary> Blocks (If and Then)</summary>

### If Block
The If block will go check the condition that is given, and if all of the condtions are met, then all of the "then sets" and "then dos" will execute.

### Then Set Block
The block will set a certain field property to a certain target type that can be chosen.This block is executed when the If conditions before it is true. 


</details>

#### Form Element
A field that is apart of the form being edited.

#### Property
The properties from the field chosen in the form element. The properties will change depending on which field that is chosen. 

<details class=colClass>

<summary> Comparison </summary>
<div> 
This field will determine how the property field or field value will be compared to the target.
</div>

##### Number Comparisons

##### String Comparisons

##### Array Comparisons

##### Boolean Comparisons

##### Date Comparisons

##### Time Comparisons

##### Signature Comparisons

</details>
<details class=colClass>
<summary> Target Types </summary>

##### Value

##### Element Property

##### Calculation

</details>

#### Add Condition Statement

### Add Condition

### Add Set Value Action

### Add Event Action

---