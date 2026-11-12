# [A long exercise loading a list of tube stations, transforming and grouping data](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/manipulation-transforms/4607/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
For this exercise you can either get your data from the Excel workbook in the above folder (in which case you will see the exactly the answers shown) or from the following website (in which case your data will be completely up to date):

 https://wiki.openstreetmap.org/wiki/List_of_London_Underground_stations
Initially things don't look promising:

Initial list
You have some work to do!

Apply transforms to get the data in this format:

The final list
The table of stations as loaded into Power BI Desktop.

The stations are sorted by ascending order of latitude (so South to North) and then numbered.

You can either try doing this exercise without any additional help, or see below for some more ideas on how to proceed!

Here are some of the things you need to do (these notes apply if you're using the Excel workbook - the website may have changed).  Note also that there may well be other ways to solve the problems you encounter.

Stage	Notes
Header rows	You'll need to remove the top 7 header rows, then promote the top row to be a header row.
User	Split the user by the : character, then have a look at the columns resulting.  You'll see that Morwen uses a different format to everyone else (you'll need to replace some values and merge the two columns back together to get the final users).
Lat/long	To make these decimal, you'll first need to replace the values for Canada Water station.
Collection date	User parsingphase may have a good name, but s/he doesn't follow the right format for inputting dates.  Assume their data was collected on the first day of the year shown.
Index column	After making the latitude a number and sorting by it you should then be able to add a conditional column.
Rename this original query as Original list, then reference it twice, renaming the results:

The three queries
You now need to make the second and third query do what they say they should!

 
For the Stations by user query, show that Morwen has collected most stations:

Grouping query
Group by the collecting user and count the number of stations, then sort by this count to get these results.

 
For the Stations by line query, split the Line column by comma, using the advanced options to generate additional rows (rather than columns) to get:

The stations by line
The first few stations sorted by line (you'll also need to trim the name of the line to remove any spaces).

 
You can now apply grouping to get the number of stations by line:

Stations by line
Omit the blank line (wonder what happened to Homerton station?) and apply sorting to get these results.  If you want a challenge, you could see if you could find a way to merge the two Hammersmith and City rows!

 
Save this report as Final results, then close it down. 
