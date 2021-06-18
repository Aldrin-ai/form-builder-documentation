# Single line text
[shared fields](/shared-inspector-components.md ':include')
### Custom Error Messages
Give a unique message when a field has come across a certain error
- #### Required Error
	Error is thrown when the field is not completed and it is required to complete
- #### Type Error
	Error is thrown when the data type in the field is not correct.
- #### Minimum Error
	Error is thrown when the text does not meet the minimum length requirement
- #### Maximum Error
	Error is thrown when the text does not meet the maximum length requirement
- #### Message
	The text that will be seen by the user when the error is thrown.

### Default Value
A value set if user does not insert text into field.
### Use Calculated Value
Enables or disables form calculator to be used inside the field.
### Calculated value
Using the form calculator, the value of the field will be set to the output of the form calculator.
### Placeholder
A set of text that is used as a placeholder if text is not written.
### Primitive Type
A data type that reads a specific type of data, EX: String, Integer, Number. Each type has different way to store text and numbers.
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
	The maximum value that the Integer or Number can be
[//]: # (Hello)
### Auto Advance
A setting that will advance to next field after completion of specified field.
### Prefix Label
A text that is positioned behind of the specified field. HTML can be used for the text.
### Suffix Label
A text that is positioned after the specified field. HTML can be used for the text
### Force The Number Pad For Mobile Input
Forces the mobile user to use the number pad.
### Use Input Mask
Enables the ability to create a custom format for the text.
