# [Use quick measures to reference totals which either ignore or take into account filters](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/quick-measures/4440/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Use the above file to create a table holding the total RuntTimeMinutes for each Certificate:

Totals with no filters quick measures
The total at the bottom is the grand total for all Certificates without any filtering. Future comparisons need to be made against that value.

 
As soon as a slicer or filter is added that total will be modified. To prevent that from happening create a quick measure:

Power BI Quick Measures
This measure will come in handy when comparing sales to total sales.

Now create a second measure dividing the RunTimeMinutes by the new total measure that was created. Add both to the table visual:

Measures unfiltered totals
Make sure the column names are explicit - you don't want report consumers to make false assumptions!

Repeat this process for Total for category (filters applied) and then apply a filter excluding certificate U:

Quick measures
Together quick measures and filters allow a huge range of calculations.

Optionally save this as Can't be censored and close it down.
