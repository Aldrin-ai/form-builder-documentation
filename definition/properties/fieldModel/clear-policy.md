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