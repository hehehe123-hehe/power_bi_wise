# [Use parameters to filter data before it enters the data model.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/parameters/4435/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a model using all the sheets in the above excel file. The aim is to create a parameter to filter the query editor based on a given Genre like so:

Filtering with parameters
Checking the genre column filter in the data model should only show a single value in the list when you are finished.

To start with, create a parameter which will take in a genre entered by the user. Within the query editor choose Manage Parameter on the Home tab.

Parameters query editor
Required will prevent you from leaving the Current Value blank. Choosing Any value from Suggested Values gives your users an input box for the parameter value.

Click the top of the column you want to apply a filter to:

Power BI Parameters filtering
If you want an exact match to the entered value choose Equals - otherwise use Contains to show any values including the entered string.

Set the filter equal to whatever value is currently held within the parameter:

Power BI parameters filtering data
By default this will be the Current value that you entered in earlier.

This will filter the data before it enters your data model, meaning that the only films left should share the same genre:

Power Bi Filtering the data model using parameters
To change the value held in the parameter choose Edit Queries then Edit Parameters from the Home tab within report view.

Optionally save this as Favourite films by genre, then close it down.
