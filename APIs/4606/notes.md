# [Use the UK government crime statistics API to show crimes in your area](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/apis/4606/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
The aim of this exercise is to show a chart of street crime by category and status for your latitude and longitude:

Crime for Leicester Square for February 2022
Crime data for Leicester Square in London for February 2022

At the time of writing the figures are only accurate for England, Wales and Northern Ireland, and are only available up to and including February 2022.  You can get more information on the API at the link included in the text file in the above folder.

Start by getting data from the API whose URL is included in the text file in the above folder.  Apply transforms to tidy up the data to get something like this:

Liste of crimes
The first few of 29 crimes at the time of writing (the data may be updated, so your list may look different).

Create four parameters as follows:

Parameter	What it should hold
Latitude	The latitude of the location (set to 51.51081 as a default).
Longitude	The longitude of the location (set to -0.13067 as a default).
Year	The year of interest (set to 2022 as a default).
Month	The month of interest as a two-digit number (02 as a default).
Although these are all numerical values, you'll find it much easier to plug them into the data source formula if you make them text parameters.

Change the source of your query so that it refers to these parameters, and check it still returns the same data.

Parameter list
You should now have 4 parameters and a query (it may be best to add the parameters one by one to the expression for the query Source, since it's easy to get the syntax wrong).

 
If you right-click on any point in Google Maps you can see the latitude and longitude.  Use this fact to change the location for your search to where you live (or work):

Wise Owl HQ
There are far less crimes (it turns out) near our office than in Leicester Square in London!

 
Apply your changes and load the data into Power BI Desktop.  You can now create a chart to illustrate your data:

Crimes by month and type
Theft crimes with no suspect dominated for this month and location, it seems.

Save your report as Taking the you-know-what, and close it down. 

