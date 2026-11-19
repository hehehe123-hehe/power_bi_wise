# [Use a custom function to combine all of the worksheets in a workbook](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/custom-functions/4602/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
The above workbook contains one worksheet for each film certificate rating:

Certificates
Each worksheet contains a different set of films.

The aim of this exercise is to combine all the films together:

Combined worksheets
The aim of the exercise is to create a list of worksheet names, then separately load date from one worksheet, and finally run this query to load data for each of the worksheets in the original list.

If you're feeling brave, try solving this without the instructions below!

Load up any one of the worksheets, then duplicate this query and rename the results:

Getting list of worksheets
You should end up with two identical queries like this.

 
Delete all but the first step from your List of worksheets query to derive a list of the worksheet names only:

Worksheet names
You'll need to remove the other columns and rename this one.

Create a parameter to hold a typical worksheet name:

Parameter holding sheet name
Here we've chosen to set the parameter value to be U initially, but you could choose any valid worksheet name.

 
Change the query Loading a worksheet data so that it references your parameter, then create a custom function from this query.

Test that your function works by invoking it

Test your function
If this doesn't work, check that you've made your parameter have data type Text.

 
Now apply your custom function to your list of worksheet names, and expand out the results.  You may well get errors for some certificates:

Films sorted by title
Once you've expanded the table resulting from running the custom function and sorted the results by film title, you may well get this.

See if you can solve this (clue: you'll need to go back to the Loading a worksheet data query and amend the Changed Type final step).

Make sure that your final query containing the list of combined films is the only one which loads into your Power BI report, then use this to create a simple chart to prove the data looks sensible:

Final chart
This looks plausible!

 
 Save this query as Reunited films, then close it down.

