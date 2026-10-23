# [Using Average and Constant line analytics in Power BI](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/analytics/5230/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Open a blank Power BI file and import data from the Excel file called Running Data 2023.xlsx.

The data is an actual running log for a Wise Owl. Shaun trained for and competed in two Half Iron Mans during 2023. See if you can guess which months he did them in?

Add a line chart with Date on the X-axis and Sum of Distance KM on the Y-axis. Set the Date to use the actual Date and not the Date Hierarchy.

Turning off Date Hierarchy in Power BI
This allows you to see single dates.

Use the Analytics panel to add a Trend line to the chart.

Power BI Trend line
A downwards trend towards the end of the year. Who wants to run in the cold and wet!

On a new page, add a line chart with Month from the Date hierarchy on the X-axis and Sum of Distance KM on the Y-axis.

Use the Analytics panel to add an Average line with the following settings:

Rename as AVG Distance

Switch on Data labels

Data label Style set to Both

Change the font colour to black

Power BI Average line
There are lots of options for Style and Position.

Now add a Y-Axis Constant Line with the following settings:

Rename as Target

Value set to 40

Change the line colour to red

Switch on Data labels

Data label Style set to Both

Change the font colour to black

Power BI Y-Axis Constant Line
Sadly, below target!

On a new page, add a line chart with the actual Date on the X-axis and Sum of Calories on the Y-axis.

Using the Analytics panel, switch on Find anomalies.

Power BI Find anomalies
Anomalies are shown with a marker

When using Find anomalies you can click one to find out more information, although Power BI cannot always find a reason for the anomaly.

 Save the file as Never again.pbix
