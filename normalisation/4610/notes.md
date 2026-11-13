# [Divide a single table of dinosaurs into 3 separate tables (normalisation)](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/normalisation/4610/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a new Power BI Desktop report, and load the data from the above workbook.

The aim of this exercise is to normalise this set of data into 3 separate tables, then join them together again to get this:

Three linked tables
The aim is to get 3 tables joined together by relationships.

Start by duplicating the original query in Query Editor twice, and renaming the results, to get three identical queries:

Renamed queries
If you choose Reference rather than Duplicate it will be slightly more efficient, as Power Query won't have to repeat the same steps 3 times.

 
For the Periods and Diets queries, remove all but one column, remove duplicate rows and sort the results to get these two queries:

Query showing unique diets	Query showing unique periods
Diets query	Periods query
Add an index column to each of the two tables (call this DietId and PeriodId respectively) to number the rows for each query from 1.

Create two merge queries in succession, to link the dinosaurs table:

to the Diets query by the Diet column; and
to the Periods query by the Period column.
Delete the diet and period columns for your final query, and expand the linked tables to show the diet id and period id from these instead:

Expanding tables
Expand the diets to show the diet id for each dinosaur, for example.

You could now if you like create a quick pair of slicers and a table, to show that your data is working:

Slicers and table
You should now have a sense of fulfilment!

 
Save your report as Normality restored, then close it down.

