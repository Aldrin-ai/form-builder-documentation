# Form Repeater
[shared fields](/shared-inspector-components.md ':include')
### Custom Error Messages
Give a unique message when a field has come across a certain error
- #### Required Error
	Error is thrown when the field is not completed and it is required to complete
- #### Type Error
	Error is thrown when the data type in the field is not correct.
- #### Min Items Error
	Error is thrown when the list does not meet the minimum item requirement
- #### Max Items Error
	Error is thrown when the list does not meet the maximum item requirement
- #### Message
	The text that will be seen by the user when the error is thrown.

### Subform
The form that will be used for the form repeater.
### Show Count
Show the number of items inside of the form along side the field label
### Display Form Title
If checked the subforms being created will have titles on top of them.
### Form Title Fields
References to different fields in which can be used in form titles.
### Form Title 
The title for the subfrom that is being added, the title may references from the form title fields.
### Default Form Title
If references to the form title fields are not defined, this title will come to be the default title.
### Add Item Button Label
The label for the button that will add items
### Remove Item Button Label
The label for the button that will remove items.
### Hide Add Button
The user will not be able use or see the Add button
### Hide Remove Button
The user will not be able to use or see the remove button
### Allow Reorder
Allow the user to reorder the form
### Minimum Items
The minimum amount of items that the subform have
### Maximum Items
The maximum amount of items that the subform have.
### View Mode
Sets different ways to view the subform
- #### Default

- #### Compact

- #### Table

### Sort Descending
The instances are sorted in descending order by dates unless the sort by filter is in place.
### Sort By
Select a field in which the list of forms will be sorted by.
### Filter
Select a field and the value in which the forms will be filtered by.
### Limit Items
This property limits the amount of forms that may be created inside the repeater.
### Auto Open New Instances
When checked each new form automacally opens a compact version of the form.