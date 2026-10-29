# [	Adding a Visual header and Dynamic Tooltip in Power BI Desktop.](https://www.wiseowl.co.uk/power-bi/exercises/power-bi-desktop/tooltips/5228/)

This exercise is provided to allow potential course delegates to choose the correct Wise Owl Microsoft training course, and may not be reproduced in whole or in part in any format without the prior written consent of Wise Owl.

Before you can do this exercise, you'll need to download and unzip this file .
Open the file called Class Days.pbix from the folder shown above.

Add a stacked column chart with Day of Week on the X-axis and Average of Attendees on the Y-axis.

Add a new page and switch to the Format page pane. In the Page information section switch on Allow use as tooltip.

Power BI page settings.
Switching this on will also resize the page to tooltip size.

You can hold Ctrl and scroll your mouse wheel to zoom in to the page.

Add a text box to the new page with the following text:

Hover over a column to see the Average attendees by Gender for each day. You can see the Average attendees by Location in the table below.

Add a table visual to the same page displaying the Location and Average of Attendees columns.

Power BI Visual header page
Position the visuals as you prefer.

On Page 1, select the chart and go to the Header icons section in General formatting. Switch on the Help tooltip and set the Type to Report page and the Page to Page 2.

Power BI Visual header tooltip
The Help tooltip section will only appear once you've turned on the Help tooltip option.

Hover over the question mark icon in the visual header of the chart to see the tooltip.

Power BI Visual header tooltip
The visual header tooltip is very useful!

Now to create the dynamic tooltip! Add a new page and switch on its Allow use as tooltip setting.

Add a Pie chart with Gender in the Legend bucket and Average of attendees in the Values bucket.

Power BI Tooltip page
Resize the chart to fill the page.

On Page 1 select the column chart and go to the General section of the Format visual panel.

Power BI Tooltips settings
Set the Tooltips | Options to use the newly created page.

Hover over different columns to see how the pie chart is affected.

Power BI Dynamic tooltip
Unlike the visual header tooltip, dynamic tooltips change.

To finish off the report hide the two tooltip pages so they are not visible when published.

Save the file as Tooltips are cool.pbix
