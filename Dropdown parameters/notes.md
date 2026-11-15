# [Create a drop list of hair treatments for users to filter their data model by](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/dropdown-parameters/4436/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Rather than give an input box for parameters, we instead want to create a drop down for filtering. Like this in fact:

Dropdown parameter
Choosing a treatment will filter the data brought through into the data model.

Load the data from the Excel sheet in the above folder, removing nulls and promoting headers to get something like this:

Start of table
The first couple of rows and first 3 columns of your final query.

 
Before we create our drop-down parameter we first need to create the drop down list for it. To do this, start by right-clicking on the Usual Treatment column:

New query dynamic drop down
At the bottom of the list choose Add as New Query.

 
This will create an additional query.  Remove any duplicates from this list of usual treatments, and sort it:

The final query
This list will contain each value multiple times, so right-click on it and choose Remove Duplicates (then sort the items into ascending order, as here).

 
You now have a query to use for populating a drop down. Create your parameter:

Creating parameter
Irritatingly you still must choose an initial Current Value (and even more annoyingly it doesn't even give you the drop down you made to help you choose!).

Filter your data to show only customers who have had the specified treatment:

Chosen treatment
Only show treatments which match the one set as the parameter value.

Try changing the value of your parameter to verify that it changes the rows returned from your query, then save your report as Dropping usual treatments.
