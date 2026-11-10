# [Load data showing gun ownership rates by country and tidy it up](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/column-transforms/4608/)

Load data showing gun ownership rates by country and tidy it up
This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Load the table of gun ownership data from the workbook in the above folder.  The original source for this is:

https://en.wikipedia.org/wiki/Gun_ownership
Initially the data doesn't look very promising:

The initial table of data
We need to sort out the top rows, and rename some columns.

Skip the top 2 rows, promote the next row to be your header row and rename columns to get:

Renamed columns
Better: we have something to work with!

The Ratio column has a red mark below it, showing you have at least one error.  The problem is that converting it to a number didn't always work, so remove this step:

Remove change of type
Delete this step only (we want to keep the one which renamed the columns).

 
Sort the Ratio column to see what the problem is (it should be the first or last row, depending on how you sort) and solve this:

Replacing values
Replace the <0.1 with just 0.1 using the Replace Values transform, then change the data type of this column to be a decimal number (this shouldn't now generate any errors).

 
Sort your data by this Ratio to see which country has the highest gun ownership rate in the world, then add an index column to number your rows (and rename this column as Order):

Countries sorted
Oh America! The UK is about number 190 (although those gun-toting Falkland Islanders let the side down a bit).

Create a custom column to show the true ratio between the number of firearms and population for each country (multiply by 100 to get the figure as a percentage):

Add custom column
The custom column formula should just be one figure divided by another.

 
This should give something like this:

Calculated ratios
The calculated ratios aren't quite the same as the ones given.

Add another calculated column to show the absolute value of the difference between the two ratios (the one given, and the one you've calculated):

Absolute function
A clue to start you off!

 
Sort by this to show the countries with the largest discrepancies:

Discrepancies list
Most of these have tiny numbers involved, but the figures for Saudi Arabia look like a genuine error.

Load your query into Power BI Desktop, then save this workbook as Smug UK and close it down.
