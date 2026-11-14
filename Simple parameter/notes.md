# [Create a parameter and apply it to crime statistics to filter the data](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/simple-parameters/4088/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a new Power BI Desktop file, and load the Excel workbook from the folder above.  Use this to create a table showing the number of offences for each offence subgroup:

Offences table
The first few rows of the table.

 
We want to be able to filter this to show only those offences for a particular group:

List of offence groups
The offence groups. It would be nice to be able to type one of these into a parameter box, and see the table change!

 
In Query Editor, create a new parameter called OffenceGroup, and set its default value to Robbery (if for no other reason than that it's the shortest offence group name to type in!):

Parameter created
Your parameter should look something like this.

Still in Query Editor, filter the table of offences to show only those ones for the offence group specified by your parameter:

Offences for given group
After returning to your report, you should now see your table is much shorter!

 
We could do with a title for our report.  Go back to Query Editor, and tell Power BI Desktop that you want to load your parameter into your data model:

Enabling load
In Query Editor, choose to enable loading for your parameter.

 
Set the title of the visual to be an expression:

Expression for title
Click here to set the title to be the value of a field, then choose to show the first value of your parameter (it is of course also the only value of it!).

 
Your table should now display the offence group name as a title:

The table title
The title shows the offence group name.

 
Without leaving Power BI, use this option to change the offence group to Drug offences:

Edit parameter value
You can change the value of a parameter using this option.

 
Refresh your data, and check that your table updates:

Drug offence data
The corresponding data for drug offences.

 
Save this as Was it worth it, then close down the Power BI instance you're using. 

