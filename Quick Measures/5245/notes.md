# [	Creating Quick measures in Power BI.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/quick-measures/5245/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Open the Power BI file called Movie Data.pbix from the folder above.

Add a table visual with Oscar Wins and Box Office Dollars.

Power BI Table visual
Set the Oscar Wins column to not summarise.

You can stop a column from summarising data by clicking its dropdown in the columns bucket of the field well and choosing the Don't summarize option.

Now we'd like to divide each Sum of Box Office Dollars value by the total. To do this, create two quick measures in the Film table:

Create a quick measure giving the total Sum of Box Office Dollars with filters not applied.

Power BI QUick measures pane
This will be our denominator. Rename this measure as Total Box Office unfiltered.

Create a quick measure to divide the Sum of Box Office Dollars by the previously created quick measure.

Power BI Quick measures pane
Rename this measure as % of unfiltered total and format it as a percentage.

Add the % of unfiltered total measure to the table visual.

Power BI Table visual with a Quick measure for percentage of unfiltered total
Unsurprisingly, the non Oscar winners have the highest percentage!

Add a slicer visual using Oscar Wins and set it to filter between 2 and 10 wins.

Power BI Table visual showing a filtered percentage value
The data being shown makes up 10.44% of the total Box Office value.

 Now create a quick measure to show each Sum of Box Office Dollars value as a percentage of the filtered total.

Create a quick measure for the denominator giving the total value with filters applied.

Create a quick measure to divide the Sum of Box Office Dollars by the previously created denominator.

Power BI Quick measures
Rename the left hand measure as Total Box Office filtered and the remaining measure as % of filtered total.

Format the % of filtered total as a percentage and add to the table visual.

Change the slicer values and observe each % of total measure.

Power BI table with Quick measures
This example shows the percentages for between 3 and 7 Oscar wins.

Save the file as Not so quick.pbix

