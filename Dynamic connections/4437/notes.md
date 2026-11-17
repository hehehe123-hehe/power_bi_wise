# [Use a dropdown parameter to choose different sets of buildings in M.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/dynamic-connection/4437/)

Use a dropdown parameter to choose different sets of buildings in M
This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
In the above folder are 3 Excel files containing information about the tallest buildings in various countries. The aim is to be able to switch between viewing the top 10 from each file by changing to which file we are connecting:

Power BI Query Editor Dynamic Connection string
To start with either connect to the UK file from scratch, or else open the PBIX file in the above folder.

We need to store the location of each file in a parameter so we can switch between them. To do this, create a parameter and list the file names:

Dropdown parameter
This will create a drop down letting users choose which file to connect to.

 
Choose the Source step of your original query:

Source step
Select your original query and choose this step.

 
Use the Advanced Editor button on the Home tab within Query Editor to replace the file name with your parameter:

M formula for connection
Use the & to concatenate the folder name with the value for the file name stored inside the parameter.

Apply your changes and load them into Power BI, then try changing the value of your parameter to different Excel workbooks:

Power BI Query Editor Dynamic Connection string
You may need to click Apply changes to finish loading the data.

 
Optionally save this report as Tall, Taller, Tallest and then close it down.
