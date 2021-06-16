### Label
The title or name of specified field, .
### Required
Users are required to complete specified field to continue to next field group.
### Hidden
Field is not shown to users, unless a rule dictates otherwise.
### Helper Text
Text that is under the field to help explain what the field is for.
### Additional Info
Text that is hidden to users, until icon next to label is hovered over.
### Is PII Field 
Check if field is sensitive information or Personally Identifiable information. This will be used for filtering private information.
### Default Value
The value that will be used if field is not filled in by the user.
### Disabled
Users cannot use specified field, unless a rule dictates otherwise.
### Auto Clear Value Policy
When specified field is changed by a rule that hides or disables, the field will be cleared, depending on the policy.
- #### Never
	The field will never be cleared, even if a rule hides or disables the field.
- #### When Hidden
	The field will be cleared if a rule hides the field from the user. If the field is unhidden the field will be reset.
- #### When Disabled
	The field will be cleared if a rule disables the field from the user. If the field is enabled again the field will be completely reset.
- #### When Disabled or Hidden
	The field will be cleared if a rule disables or hides the field from the user. If the field is enabled or unhidden the field will reset.