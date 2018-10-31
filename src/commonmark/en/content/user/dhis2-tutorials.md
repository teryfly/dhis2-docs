# DHIS2 Tutorials

<!--DHIS2-SECTION-ID:dhis2_tutorials-->

## Create Scorecards using the Pivot Table app

<!--DHIS2-SECTION-ID:create-scorecards-pivot-table-->

***Scorecards definition:** In public health settings such as Ministries
of Health, scorecards offer a useful and standardized method for
combining related indicators into one table. A scorecard gives an
overall view of the performance of a health program such as a
vaccination program, highlighting successes, weaknesses, and areas for
improvement Here's what a typical scorecard looks like:*

![](resources/images/tutorials/scorecards_pivot_result.png)

This tutorial explains how to create a scorecard in the DHIS2 Pivot
Table app. There are several advantages to using the Pivot Table to
create a scorecard, such as:

  - You can save the scorecard on the dashboard and use it offline.

  - You can share the scorecard with other DHIS2 users.

Let's get started\!

### Create a legend for your scorecard

First, we’ll create a 3-color “traffic light” legend for the scorecard.
With three basic colors, the scorecard is easy to scan and easy to
understand.

1.  Open the **Maintenance** app. Click the menu in the top right corner
    and select Maintenance from the list of apps. You can also type the
    first letters of the word maintenance in the search field to find
    the app.
    
    ![](resources/images/tutorials/scorecards_maintenance_app.png)

2.  In the Maintenance app, scroll to the bottom of the page right down
    to the **Other** section.

3.  Go to **Legend** and click the **+**.
    
    ![](resources/images/tutorials/scorecards_maintenance_legend.png)

4.  In the **Legend Management** page, scroll to the bottom of the page
    and create a new legend by clicking the blue + button.
    
    ![](resources/images/tutorials/scorecards_maintenance_addbtn.png)

5.  Enter a name for the legend such as “Traffic light”, a start value
    and an end value in the fields. The values you enter here depend on
    the performance ratings you wish to set for the scorecard.

6.  Change **Number of legend items** to 3 to display three colors in
    the scorecard. To change the legend item colors, click the blue +
    button and then edit the
    colors.
    
    ![](resources/images/tutorials/scorecards_maintenance_legend_color.png)

### Create a scorecard in the Pivot Table app

1.  Open the **Pivot Table** app from the top right menu of the
    dashboard. You can also enter the first letters of Pivot Table in
    the search field.

2.  Go to **Data** in the pane on the left side and select
    **Indicators** in the list.

3.  Select an **Indicator group** such as “ANC” in the second list.

4.  Using the arrows, select the type of indicators you want to see in
    your scorecard.
    
    ![](resources/images/tutorials/scorecards_pivot_indicators.png)

5.  Click **Update**. This button is in the menu at the top of the
    workspace

6.  Go to **Periods** and select a period for which you want to display
    data. In this “traffic light” example, we’ll use the relative period
    section. In **Quarters**, select **This quarter**and **Last
    quarter**. Clear any other checkboxes and click **Update**.
    
    ![](resources/images/tutorials/scorecards_pivot_period.png)

7.  Go to **Organisation Units** in the same left side pane, and click
    the arrow next to the gear button.

8.  Select **Select levels**.
    
    ![](resources/images/tutorials/scorecards_pivot_orgunit_level.png)

9.  Select **District** from the list (next to the gear button). Click
    **Update**.
    
    ![](resources/images/tutorials/scorecards_pivot_orgunit_level2.png)

As you can see, the scorecard is starting to take shape in the
workspace. Now it’s time to fine-tune the look and feel.

### Organise the layout and display of your scorecard

1.  In the workspace, click **Layout**.
    
    ![](resources/images/tutorials/scorecards_pivot_layout.png)

2.  In **Table layout**, drag **Organisation units** down to the **Row
    dimensions** section.

3.  Drag **Data** to the **Column dimensions** section.

4.  In the **Column dimensions** pane, drag **Periods** below **Data**,
    and click **Update**.

5.  In the workspace, click **Options**.
    
    ![](resources/images/tutorials/scorecards_pivot_options.png)

6.  Go to **Data** and clear all the checkboxes.

7.  Go to **Style** \> **Legend set** and from the list, select the
    legend you created in the Maintenance app. In this example, we
    called it Traffic light.

8.  Go to **Style** \> **Legend display style** and select **Background
    color**.

9.  Click **Update**.

The Scorecard is ready\!


![](resources/images/tutorials/scorecards_pivot_result.png)

### Save and share your scorecard

1.  In the workspace, go to the **Favorites** menu.

2.  Click **Save as**. Enter a name for your Scorecard.

3.  To share your Scorecard, select **Favorites**.

4.  Enter the name of a user group name, and click **Save**. Your
    scorecard can be viewed by people that you share a dashboard with.

