# [Pass parameters from a query to a stored procedure in a books database](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/stored-procedure-parameters/4598/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file . Once you've done this:
Go into SQL Server Management Studio;
Open the SQL file you've just unzipped (you can press CTRL + O to do this); then
Execute this script.
This will generate the database that you'll need to use in order to do this exercise (note that the database and script are only to be used for exercises published on this website, and may not be reused or distributed in any form without the prior written permission of Wise Owl).

The Books database contains a stored procedure which allows you to add new books:

Adding a book
You could try running this in SQL Server Management Studio (but note that Project Hail Mary by Andy Weir - his sequel - was better).

 
Create a new Power BI report and load the two tables from this database.  You should now be able to create a table listing out the books these contain:

List of books
The list of books and authors in the tables.

 
Add another data source which runs the stored procedure above, using any book / author name as input:

Calling stored procedure
When you load your data it will run this stored procedure, so this book will be included in the returned results.

 
Create parameters to hold the book title, author's first name and author's last name and incorporate these into this data source:

Amended SQL call
There's a lot of punctuation to get right in this.

Try refreshing your data with different parameter values to check it works. 

When you run your query a second time the underlying stored procedure returns an error - you might like to think how you could have done this differently!

Save your report as What about Robert Harris, then close it down.
