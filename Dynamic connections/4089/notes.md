# [Create a parameter which controls which song playlist you load.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/dynamic-connection/4089/)

Create a parameter which controls which song playlist you load
This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Create a new Power BI Desktop file, and load data from the Anyone.xlsx workbook in the above folder.  After a bit of tidying, you should be able to create this table:

Playlist for anyone
A playlist surely acceptable to anyone?

 
In Power Query Editor, create two parameters:

Name	Contents
FilePath	The folder path to where your Excel files are stored (so you can choose to move the workbooks containing your data to any folder, and your report will still work).
Playlist	The name of the Excel workbook to load (including file extension).
Note that the rest of this exercise only works because the 3 workbooks in the above folder have got identical worksheet names and column headings.

Now edit the settings for your first (Source) query step so that it loads data from a file whose path and name are contained in your parameters:

Advanced load options
You'll need to choose Advanced, as here, and then complete the rest of the dialog box.

 
Set the value of your two parameters to the path and name of the Toddlers workbook.  When you go back to your report, you should see an altogether classier playlist:

Toddler playlist
The purple dinosaur wows them every time with this little number.

 
Save this workbook as Wiggle room, then close it down. 

