# [Write a custom function to parse dates, and apply it to the rows of a query](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/custom-functions/4601/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Load the three worksheets from the above workbook, promoting the first row to be the column header for each resulting table:

List of licence numbers
The tables contain UK valid driving licence numbers.

 
Your mission is to create a custom function to extract each person's date of birth from their driving licence number, then apply this custom function to each of your tables. 

Full instructions for how to do this are shown below (if you're feeling brave you could try without these!).

Start by creating a parameter to hold a typical driving licence number:

Creating a parameter
Your parameter will hold text.  When you've created this, right-click on it and choose Reference to create a query referencing its value.

 
Right-click on the query referencing your parameter, and begin the process of extracting the person's date of birth:

Extracting dob
Start by turning the referenced parameter value into a list.

 
Turn the resulting list into a table:

Converting list to table
If you can find a better way to start this query, use it!

 
Extract the person's date of birth.  For UK driving licence numbers the DD, MM and YY of a person's date of birth appear in the string as XXXXXYMMDDYXX.  You can get at the parts you want with a simple split by position:

Split column by position
Use these numbers to get at the columns you want.

 
After a few easy additional transforms you should be able to get the three things you need:

The day, month and year
You'll need to merge the two year columns together, and turn the resulting text back into a number.

If the year is less than 30, we'll assume it's post-millennial, so use a conditional column to add 2000 or 1900 accordingly to the year:

Add in an amount
Create a column containing either 1900 or 2000, depending on the value of the year.

 
Now create a custom column giving the final year:

Custom column
The custom column should add the two year parts together.

 
You can now merge the day, month and year together, using a / as a separator:

Merging columns
Having done this, you should be able to convert the results back into a date.

Finally, you should have derived this person's date of birth!

Person date of birth
The final date of birth for our example licence number.

 
You now want to turn this sequence of steps into a custom function (call it GetBirthDate):

Create custom function
Right-click on the query you've just created, and turn it into a custom function.

 
You should now be able to invoke your custom function to show a date of birth column for each of the 3 imported tables of driving licence numbers:

Invoking custom function
Click on each of the three tables, starting with A-G, and invoke the custom function you've just created.

As a bonus, you could merge the results of the three tables together:

Appending queries
Choose this transform, and choose to append 3 or more queries in the dialog box which appears.

 
You should now be able to see the oldest people represented:

Sorted people
Apply sorting to get these results.

 
This is a training exercise: it would clearly be better to combine the data when you merge it, which would remove the need for a separate custom function!

When you've got this all working, save this report as Have Wise Owl hacked the DVLA and close it down. 
