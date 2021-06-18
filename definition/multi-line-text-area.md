# Multi-Line Text Area

[shared fields](/shared-inspector-components.md ':include')

### Default Value
A value set if user does not insert text into field.
### Use Calculated Value
Enables or disables form calculator inside field
### Calculated Value
Using the form calculator, the content of the field will be set to the output of the form calculator.
### Placeholder
A set of text that is used as a placeholder if text is not written
### Primitive Type
A data type that reads a specific type of data, ex: String, Integer, Number.
- #### String
A data type to store text, words, letters or numbers, but it cannot do math calculations.
	- ##### Minimum Characters
		Minimum amount letters that the string can contain
	- ##### Maximum Characters
		Maximum amount of letters that the string can contain 
	- ##### Pattern
		A format that the field can establish, for example phone numbers (111)-111-1111.
		
- #### Number
A specific primitive type that can be any number whether whole or decimal, in which math calculations may be done with.
- #### Integer
A specific primitive type that can only be a whole number that is positive, 
	- ##### Min Value
	The minimum value that the Integer or Number can be.
	- ##### Max Value
	The maximum value that the integer or number can be
[//]: # (space)
### Rows
The number of lines by row for text area.
### Auto Advance
A setting that will advance to next field after completion of specified field.
### Custom Error Messages
Give a unique message when a field has come across a certain error
- #### Required Error
	Error is thrown when the field is not completed and it is required to complete
- #### Type Error
	Error is thrown when the data type in the field is not correct.
- #### Pattern Error
	Error is thrown when the user text does not follow the pattern set for the field.
- #### Min Length Error
	Error is thrown when the text does not meet the minimum length requirement
- #### Max Length Error
	Error is thrown when the text does not meet the maximum length requirement
- #### Message
	The text that will be seen by the user when the error is thrown.
