# Calculations

#### Clone Calculation
The calculation is duplicated and aded to the calculation collapsable
#### Delete Calculation
Deletes the calculation currently in use.
### Argument
A variable or section that will be used for the whole calculation.

<details>
	<summary>Field Property</summary>
	<div>Uses properties as values from the fields inside of the form.</div>
</details>

<details>
	<summary>User Value</summary>
	<div>A specific value that is set by the user creating the form. (If value is a number, the value will be recognized as a number)</div>
</details>

<details>
	<summary>Data Source Value</summary>
	<div>Uses a Data Source to find a value for the argument</div>
</details>

<details>
	<summary>Global Value</summary>
	<!-- TODO: Go more indepth with this option -->
	<div>Values that are used outside of properties and fields</div>
</details>

<details>
	<summary>Calculation</summary>
	<div>Uses the value from another calculation</div>
</details>

### Argument Group

A group of arguments and calculations that will be done first 
before the whole calculation will be done.


### Formula
Predefined formulas that can be used to add to the calculation

 
#### Conditional 


<details>
	<summary>If</summary>
	<div>This Formula has the ability to change the returned value depending if the value in the <b>if</b> block is true or false. If the value is true the true block will execute, otherwise the false block will execute.</div>
</details>

#### String

<details>
	<summary>String Length</summary>
	<div>Returns the length of word that is inside of the String Length block</div>>
</details>

#### Array
<details>
	<summary>Array Count</summary>
	<div>Returns the number of items inside of the array blocks that is given.</div>
</details>

<details>
	<summary>First Item</summary>
	<div>Returns the first item of the array that is given or calculated to the block.</div>
</details>

<details>
	<summary>Last Item</summary>
	<div>Returns the last item of the list that is given or calculated to the block.</div>
</details>

<details>
	<summary>Item At Index</summary>
	<div>Returns item from specified position from a specified list. The array block being the list and the array index block being the position </div>
</details>

#### Math

<details>
	<summary>Absolute Value</summary>
	<div>Returns the distance of a given numeric value to 0. (Can be used create negative numbers to positive) </div>
</details>

<details>
	<summary>Round</summary>
	<div>Returns the rounded number of the numeric value given in the block. If decimal place is over or equal to .5 the number will round up to the nearest whole number,otherwise it will round down to the nearest whole number.</div>
</details>

<details>
	<summary>Round Up</summary>
	<div>Returns the rounded number of the numeric value given, but if value is a decimal point over a whole number the value will round up</div>
</details>

<details>
	<summary>Round Down</summary>
	<div>Returns the rounded number of the numeric value given, but if value is a decimal point over a whole number the value will round down to the nearest whole number.</div>
</details>

<details>
	<summary>Maximum</summary>
	<div>Returns the greater value between two values given a block "Value A" and "Value B".</div>
</details>

<details>
	<summary>Minimum</summary>
	<div>Returns the lesser value from two values given a block "Value A" and "Value B".</div>
</details>

#### Date/Time

<details>
	<summary>Age (Now)</summary>
	<div>Returns age of person by giving a date value to calculate the age.</div>
</details>

<details>
	<summary>Age At Date</summary>
	<div>Returns the age of a person at a certain date. The birthdate block will be the date of birth and age at date block will be the date that will calculate the age at that date.</div>
</details>

<details>
	<summary>Age in Years (Now)</summary>
	<div>Returns age, in years, by given birthdate block.</div>
</details>

<details>
	<summary>Age in Years at Date</summary>
	<div>Returns the age, in years, of a person at a certain date. </div>
</details>

<details>
	<summary>Get Date Second</summary>
	<div>Returns the seconds of a date/time field </div>
</details>

<details>
	<summary>Get Date Minute</summary>
	<div>Returns the minutes of a date/time field</div>
</details>

<details>
	<summary>Get Date Hour</summary>
	<div>Returns the hour of a date/time field</div>
</details>

<details>
	<summary>Get Date Day</summary>
	<div>Returns the day of a date and date/time field</div>
</details>

<details>
	<summary>Get Date Month</summary>
	<div>Returns the month of a date and date/time field</div>
</details>

<details>
	<summary>Get Date Year</summary>
	<div>Returns the year of a date and date/time field</div>
</details>

<details>
	<summary>Get Date/Time Difference</summary>
	<div>Returns the difference between two dates in years, days, minutes, and seconds </div>
</details>

<details>
	<summary>Get Formated Date</summary>
	<div>Returns the date from a date/time field or date field</div>
</details>

<details>
	<summary>Get Formated Time</summary>
	<div>Returns the time from a date/time field</div>
</details>



#### Geolocation

<details>
	<summary>Address To Geolocation</summary>
	<div><!-- TODO: Learn what adderss to Geolocation does--></div>
</details>

<details>
	<summary>Get Formatted Address</summary>
	<div>Returns the complete address from the Geolocation field</div>
</details>

<details>
	<summary>Get Address</summary>
	<div>Returns the address text from the Geolocation field</div>
</details>

<details>
	<summary>Get Address 2</summary>
	<div>Returns the 2nd address from the Geolocation field</div>
</details>

<details>
	<summary>Get City</summary>
	<div>Returns the city from the Geolocation field</div>
</details>

<details>
	<summary>Get State</summary>
	<div>Returns the state from the Geolocation field</div>
</details>

<details>
	<summary>Get Zip</summary>
	<div>Returns the Zip code from the Geolocation field</div>
</details>

<details>
	<summary>Get County</summary>
	<div>Returns the County from the Geolocation field</div>
</details>

<details>
	<summary>Get Latitude/Longitutde</summary>
	<div>Returns the Latitude and Longitude from the Geolocation field</div>
</details>

<details>
	<summary>Get Latitude</summary>
	<div>Returns the Latitude from the Geolocation field</div>
</details>

<details>
	<summary>Get Longitude</summary>
	<div>Returns the Longitude from the Geolocation field</div>
</details>

<details>
	<summary>Get Distance</summary>
	<div>Returns the distance between the Geolocation Block A and Geolocation Block B.</div>
</details>
