# [Switch the Query editor file target from an Excel sheet to a SQL database.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/adv-data-models/4434/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Open the pbix file called Outdated Movies from the above folder, and have a look at the table visual it contains (already created in report view):

Table visuals power bi
The top 10 movies according to Rotten Tomatoes as of 2016.

What we want to do is update this list to show the current top 10 films on the website. The easiest way to do this is to point the M language instructions at a different data source. First connect to the Rotten Tomatoes website:

Web connection change via M
Since this is a website you may find the answer needs a refresh! As of writing the table we want is Table 2.

Once you have the data, go to the original top 100 table and from the Home tab choose Advanced editor, sadly the old connection won't work but we still get the code:

Power BI
Copy all the steps from 'Reordered columns' down. We don't want a CSV file - instead we want our web connection!

Open up the Advanced editor for your web connection to the Rotten Tomatoes website:

M changing connections if not minds
Paste your M steps in under the already generated code. Remember to add a comma in front of the first line!

Refresh your connection and admire your newly updated list. Sadly there is no short-cut for changing the report visual - you will need to recreate this:

Power BI Change source using M
It is also worth ordering the Title (Rank) column using the Rank column.

Optionally save this as Out with the old, in with the new and then close it down.
