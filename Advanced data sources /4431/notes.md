# [Use Power BI import option to connect and import entire folder of contents.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/adv-data-models/4431/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Movies come in a variety of different genres - these are currently stored in separate workbooks. Using the Folder data source option combine all the genres into a single data model table:

The files to combine
The files in the above folder that you want to combine (but see hint below).

 
Note that one of the files above has an .xxx extension (and so won't import properly), so after choosing to combine your files be sure to tick the Skip files with errors box.

This will give you 321 films, in 3 different genres.  Return to Power BI proper and create a Table visual to compare their lengths:

Table Visual Power BI
Your table should show the average run time for each genre.

 
It would appear that the shorter the movie, the better it is.  Let's test this hypothesis by adding some truly terrible movies into our data model!  Firstly, rename the file Awful Films.xxx in the above folder to Awful Films.xlsx, then load it into your data model:

Two loaded tables
You now have two tables (which we've renamed), which you should combine as explained below.

  
Use the Append option in query editor to append one of these queries onto the other.  You should now have 326 films in your combined table, not 321:

The combined films
The combined table of films, beginning with the 5 awful ones (at least according to Wise Owl).

Create a column chart based upon the combined table to test your hypothesis:

Hypothesis
It seems as if the hypothesis doesn't stand up in the face of data!

Optionally save this as Are shorter movies better, then close it down.

