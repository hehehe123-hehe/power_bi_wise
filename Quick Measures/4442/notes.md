# [Using a quick measure list out all the filters applied to a given page.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/quick-measures/4442/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Using the Excel file in the above folder create a chart, a slicer and apply a page filter. The results should look something like this:

Filtered chart
Wouldn't it be nice to have a message box saying which filters had been applied?

From the Home tab choose Quick Measure, then from the bottom of the list choose Concatenated list of values:

Power BI Dynamic header
All the values in the Field column will be concatenated.  The Number of values before truncation box indicates how many are listed before returning etc.

Repeat this for all the columns you have used for filtering, and then insert the newly created measures into cards:

Power BI Dynamic Headers
What would be slightly nicer is having them in one card together, but there isn't a quick measure to do this.

From the Home tab choose New measure and concatenate the two previously created measures together:

Power BI Measure
The UNICHAR(10) returns a line break, so the filters will be listed on two lines.

Put this in a card to create a new dynamic title:

Final dynamic title
The final title shows all of the filtering and slicing choices that you have made.

Optionally save your report as Helpful headlines then close it down.
