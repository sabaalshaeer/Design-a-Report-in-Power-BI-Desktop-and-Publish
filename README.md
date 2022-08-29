# Design-a-Report-in-Power-BI-Desktop
Get started – Sign in
In this task you will setup the environment for the lab by signing in to Power BI.

To open Microsoft Edge, on the taskbar, click the Microsoft Edge program shortcut.

In the Microsoft Edge browser window, navigate to https://powerbi.microsoft.com.

Tip: You can also use the Power BI Service favorite on the Microsoft Edge favorites bar.

Click Sign In (located at the top-right corner).

Enter the account details
Username	admin@LODSA433463.onmicrosoft.com
Password	T!He^4jlfg5?
If prompted to update the password, reenter the provided password, and then enter and confirm a new password.

Important: Be sure to record your new password.

Complete the sign in process.

Leave the Microsoft Edge browser window open.

Get started – Enable Map and filled map visuals
In this task you will enable map and filled map visuals in the environment for the lab by updating the Integration settings in the Power BI Admin portal.

To open the Power BI Admin portal, at the top-right of the browser, click the Settings icon.

Select Admin portal.

Scroll down the page to Integration settings. Click the arrow to expand the Map and filled map visuals option.

Set the Map and filled map visuals option to Enabled.

Click Apply, to apply the changes.

A message will appear at the top-right of the browser stating the Tenant settings changes will be applied within the next 15 minutes.

Leave the Microsoft Edge browser window open.

Get started – Open report
In this task you will setup the environment for the lab by opening the starter report.

Important: If you are continuing on from the previous lab (and you completed that lab successfully), do not complete this task; instead, continue from the next task.

To open the Power BI Desktop, on the taskbar, click the Microsoft Power BI Desktop shortcut.

To close the getting started window, at the top-left of the window, click X.


To sign in to the Power BI service, at the top-right, click Sign In.

Complete the sign in process using the same account used to sign in to the Power BI service.

To open the starter Power BI Desktop file, click the File ribbon tab to open the backstage view.

Select Open Report.

Click Browse Reports.

In the Open window, navigate to the D:\PL300\Labs\06-design-report-in-power-bi-desktop\Starter folder.

Select the Sales Analysis file.

Click Open.

Close any informational windows that may open.

To create a copy of the file, click the File ribbon tab to open the backstage view.

Select Save As.

If prompted to apply changes, click Apply.

In the Save As window, navigate to the D:\PL300\MySolution folder.

Click Save.

In Power BI Desktop, to rename the page, at the bottom-left, right-click Page 1, and then select Rename.

Tip: You can also double-click the page name to rename it.

Rename the page as Overview, and then press Enter.

To add an image, on the Insert ribbon tab, from inside the Elements group, click Image.

In the Open window, navigate to the D:\PL300\Resources folder.

Select the AdventureWorksLogo.jpg file, and then click Open.

Drag the image to position it at the top-left corner, and also drag the guide markers to resize it.

To add a slicer, first de-select the image by clicking an empty area of the report page.

In the Fields pane, select the Date | Year field (not the Year level of the hierarchy).

The labs use a shorthand notation to reference a field. It will look like this: Date | Year. In this example, Date is the table name and Year is the field name.

Notice that a table of year values has been added to the report page.

To convert the visual from a table to a slicer, in the Visualizations pane, select the Slicer.

To convert the slicer from a list to a dropdown, at the top-right of the slicer, click the down-arrow, and then select Dropdown.

Resize and position the slicer so it sits beneath the image and is the same width as the image.


In the Year slicer, open the dropdown list, select FY2020, and then collapse the dropdown list.


The report page is now filtered by year FY2020.

De-select the slicer by clicking an empty area of the report page.

Create a second slicer, based on the Region | Region field (not the Region level of the hierarch).

Leave the slicer as a list, and then resize and position the slicer beneath the Year slicer.

De-select the slicer by clicking an empty area of the report page.

To add a chart to the page, in the Visualizations pane, click the Line and Stacked Column Chart visual type.

Resize and position the visual so it sits to the right of the logo, and so it fills the width of the report page.

Drag and drop the following fields into the visual:

Date | Month

Sales | Sales

In the visual fields pane (not the Fields pane—the visual fields pane is located beneath the Visualizations pane), notice that the fields are assigned to the X-axis and Column y-axis wells/areas.

By dragging fields into a visual, they will be added to default wells/areas. For precision, you can drag fields directly into the wells/areas, as you will do next.

From the Fields pane, drag the Sales | Profit Margin field into the Line y-axis well/area.

Notice that the visual has 11 months only.

The last month of the year, 2020 June, does not have any sales (yet). By default, the visual has eliminated months with BLANK sales. You will now configure the visual to show all months.

In the visual fields pane, in the X-axis well/area, for the Month field, click the down-arrow, and then select Show Items With No Data.

Notice that the month 2020 June now appears.

De-select the chart by clicking an empty area of the report page.

To add a chart to the page, in the Visualizations pane, click the Map visual type.

Resize and position the visual so it sits beneath the column/line chart, and so it fills half the width of the chart above.

Add the following fields to the visual wells/areas:

Location: Region | Country

Legend: Product | Category

Size: Sales | Sales

De-select the chart by clicking an empty area of the report page.

To add a chart to the page, in the Visualizations pane, click the Stacked Bar Chart visual type.

Resize and position the visual so it fills the remaining report page space.

Add the following fields to the visual wells/areas:

Axis: Product | Category

Value: Sales | Quantity

To format the visual, open the Format pane.

Expand the Bars and then the Colors group, and then set the Default Color property to a suitable color (to complement the column/line chart).

Set the Data Labels property to On.

Save the Power BI Desktop file.

The design of the first page is now complete.

Design page 2
In this task you will design the second report page. When you’ve completed the design, the page will look like the following:

Image of page 2, comprising a slicer and matrix.

Important: When detailed instructions have already been provided in the labs, the lab steps will provide more concise instructions. If you need the detailed instructions, you can refer back to other tasks in this lab.

To create a new page, at the bottom-left, click the plus icon.

Rename the page to Profit.

Add a slicer based on the Region | Region field.

Use the Format pane to enable the “Select All” option (in the Selection group).

Resize and position the slicer so it sits at the left side of the report page, and so it is about half the page height.

Add a matrix visual, and resize and position it so it fills the remaining space of the report page


Add the Date | Fiscal hierarchy to the matrix Rows well/area.


Add the following five Sales table fields to the Values well/area:

Orders (from the Counts folder)

Sales

Cost

Profit

Profit Margin


In the Filters pane (located at the left of the Visualizations pane), notice the Filter On This Page well/area (you may need to scroll down).

From the Fields pane, drag the Product | Category field into the Filter On This Page well/area.

Inside the filter card, at the top-right, click the arrow to collapse the card.


Fields added to the Filters pane can achieve the same result as a slicer. One difference is they don’t take up space on the report page. Another difference is that they can be configured to achieve more sophisticated filtering requirements.

Add each of the following Product table fields to the Filter On This Page well/area, collapsing each, directly beneath the Category card:

Subcategory

Product

Color

Save the Power BI Desktop file.

The design of the second page is now complete.

Design page 3
In this task you will design the third—and final—report page. When you’ve completed the design, the page will look like the following:

Image of page 3, comprising a slicer and three visuals.

Create a new page, and then rename it as My Performance.

To simulate the performance of row-level security filters, drag the Salesperson (Performance) | Salesperson field to the page level filters in the filter pane.

Image of Salesperson field in filter pane.

Select Michael Blythe. Data on the My Performance report page will now be filtered to display data for Michael Blythe only.

Add a dropdown slicer based on the Date | Year field, and then resize and position it so it sits at the top-left corner of the page.

In the slicer, set the page to filter by FY2019.

Add a Multi-row Card visual, and then resize and reposition it so it sits to the right of the slicer and fills the remaining width of the page.

Add the following four fields to the visual:

Sales | Sales

Targets | Target

Targets | Variance

Targets | Variance Margin

Format the visual:

In the Callout values group, increase the Text Size property to 28pt

In the Background group, set the Color to a light gray color

Add a Clustered Bar Chart visual, and then resize and position it so it sits beneath the multi-row card visual and fills the remaining height of the page, and half the width of the multi-row card visual.

Add the following fields to the visual wells/areas:

Axis: Date | Month

Value: Sales | Sales and Targets | Target

To create a copy of the visual, press Ctrl+C, and then press Ctrl+V.

Position the new visual to the right of the original visual.

To modify the visualization type, in the Visualizations pane, select Clustered Column Chart.

It’s now possible to see the same data expressed by two different visualization types. This isn’t a good use of the page layout, however, you’ll improve it in the Design a Report in Power BI Desktop, Part 2 lab by superimposing the visuals. By adding buttons to the page, you’ll allow the report user to determine which of the two visuals is visible.

The design of the third—and final—page is now complete.

Task 7: Publish the report
In this task you will publish the report.

Select the Overview page.

Save the Power BI Desktop file.

On the Home ribbon tab, from inside the Share group, click Publish.

In the Publish to Power BI window, notice that My Workspace is selected.

To publish the report, click Select.

When the publication has succeeded, click Got It.

Leave Power BI Desktop open.

You’ll explore the report in the Power BI service in the next exercise.

Exercise 2: Explore the Report
In this exercise you will explore the report that was published to Power BI.

Task 1: Explore the report
In this task you will explore the report that was published to Power BI.

In the Microsoft Edge browser window, in the Power BI service, in the Navigation pane (located at the left, and it could be collapsed), expand My Workspace.

Review the contents of the workspace, noticing the Sales Analysis report and dataset.

When you published the Power BI Desktop file, the data model was published as a dataset.

If you don’t see it, press F5 to reload the browser, and then expand the workspace again.

To open the report, click the Sales Analysis report.

At the left, in the Pages pane, select the Overview page.

In the Regions slicer, while pressing the Ctrl key, select multiple regions.

In the column/line chart, select any month column to cross filter the page.

While pressing the Ctrl key, select an additional month.

By default, cross filtering filters all other visuals on the page.

Notice that the bar chart is filtered and highlighted, with the bold portion of the bars representing the filtered months.

Hover the cursor over the bar chart visual, and then at the top-right, hover the cursor over the filter icon.

The filter icon allows you to understand all filters that are applied to the visual, including slicers and cross filters from other visual.

Hover the cursor over a bar, and then notice the tooltip information.

To undo the cross filter, in the column/line chart, click an empty area of the visual.

Hover the cursor over the map visual, and then at the top-right, click the Focus mode icon.
Focus mode zooms the visual to full page size.

Hover the cursor over different segments of the bar charts to reveal tooltips.

To return to the report page, at the top-left, click Back to Report.

Hover the cursor over the map visual again, and then at the top-right, click the ellipsis (…), and then notice the menu options.

Try out each of the options, except Chat in Teams.

At the left, in the Pages pane, select the Profit page.

Notice that the Region slicer has a different selection to the Region slicer on the Overview page.

The slicers are not synchronized. You’ll modify the report design to ensure they sync between pages in the Design a Report in Power BI Desktop, Part 2 lab.

In the Filters pane (located at the right), expand a filter card, and apply some filters.

The Filters pane allows you to define more filters than could possibly fit on a page as slicers.

In the matrix visual, use the plus (+) button to drill into the Fiscal hierarchy.

Select the My Performance page.

At the top-right on the menu bar, click View, and then select Full Screen.

Interact with the page by modifying the slicer, and cross filtering the page.

At the bottom of the window, notice the commands to change page, navigate backwards or forwards between pages, or to exit full screen mode.

Click the left icon to exit full screen mode.

Task 2: Finish up
In this task you will complete the lab.

To return to your workspace, in the banner across the window web page, click My Workspace.


Leave the Microsoft Edge browser window open.

You will enhance the report design with advanced features in the Design a Report in Power BI Desktop, Part 2 lab.
