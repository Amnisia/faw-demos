# Oracle ERP Fusion Analytics Warehouse (FAW) Demo

## Introduction

In this demo, you will learn about how a finance team can adress analytics questions through Oracle Fusion ERP Analytics.

Finance teams are under enormous pressure to generate more insights, faster, from their financial systems and other critical data sources. But for most organizations, far too much time is spent manually sourcing, managing, preparing, and securing data – leaving far too little time for true analysis and insight.

Oracle Fusion ERP Analytics provides the fastest path to insight with your ERP data, based on its pre-built integration to your ERP Cloud, pre-built data model, and pre-built interfaces – including KPIs, dashboards, and self- service project areas that you can use to easily customize and extend your analysis. And, it’s all built on the foundation of Oracle Analytics Cloud and the self-tuning, self-scaling, self-securing Oracle Autonomous Data Warehouse.

This demo is designed to give you a showcase of both the pre-built elements of Oracle Fusion ERP Analytics – with a focus on KPIs and dashboards – as well as the intuitive self-service capabilities delivered by the underlying Oracle Analytics Cloud platform.


### Objectives

-   Show how to use the Oracle Fusion ERP Analytics interface through KPI Cards, Decks, Alerts, and Analysis
-   Show how to create a KPI with an ERP Data Model and External Data
-   Showhow to create an Analysis with an ERP Data Model 
-   Show how to blend ERP data with External Data

### Required Artifacts

-   You will need a tenancy environment with FAW access as well as internet access and a modern web browser. 
-   The estimated time to complete this demo is 40 minutes.

### Extra Resources
-   To learn more about Oracle Fusion ERP Analytics, feel free to explore the capabilities by clicking on this link: [Oracle Fusion ERP Analytics Getting Started Documentation](https://docs.oracle.com/en/cloud/saas/analytics/fawag/get-started-oracle-analytics-applications.html#GUID-66FF30CB-C4C4-4184-9223-DE5AE3E83C80)

## Part 1. Explore the Interface and Pre-Built Content: KPI Cards, Decks, Alerts, and Analysis

1. We’ll start our experience with Oracle Fusion ERP Analytics by getting a good understanding of the out-of-the-box KPIs that finance executives and management can use to stay on top of the business. 

2. The product contains a library of 50+ pre-built Key Performance Indicators (KPIs) around profit and loss, balance sheets, financial ratios, receivables, and payables. You will learn to read the KPIs, leverage pre-built Decks or create simple customized decks, set alerts, and perform some additional analysis. 


### **Step 1:** 

1. **Note**: when going through this demo, your visualizations may looks slightly different from what is seen in the demo guide. This is okay- the data on the backend instance is updated regularly so the visualizations may look differently for you.

2. Enter the credentials you were given and click the **Sign In** button.

![](./images/1.png " ")

### **Step 2:** 

1. We start at the homepage, where contains KPIs and Decks that you have marked as favorites. Since this is the first time you have logged in, the screen will be blank. Let’s explore how to navigate within the application.

![](./images/2a.png " ")

2. Click on the upper left **hamburger menu** icon to see the following:
    1. **Decks** are how KPIs are presented and organized. 
    2. **KPIs** is where you can create and edit the Key Performance Indicators library.
    3. **Projects** is where you can create and edit analysis and reports.
    4. **Data** is where you manage data access and workflows. 

3. Click on **Decks**.

![](./images/2b.png " ")

### **Step 3:** 

1. Now, take a moment to review a few of the pre-built decks. From left to right, click on the following:
    1. **Profit and Loss**
    2. **Payables**
    3. **Balance Sheet**
    4. **Financial Ratios**

2. Take a moment to look at the pre- built KPIs on each deck.

![](./images/3.png " ")

### **Step 4:** 

1. From the **Financial Ratios** deck, click the **filter icon** on the top right.

2. **Note** that the current deck is filtered by Current Quarter by default. You can easily change the filter here to focus on a different context, such as business unit, cost center, time, etc. For instance, feel free to click on the **Time** field to change it to **Previous** and **Year** and then click on **Apply**. Feel free to try this on the other pre-built decks to see how the data and according visualizations change.

3. Click the **filter icon** again to make it disappear.

![](./images/4.png " ")

### **Step 5:** 

1. Click on **My P&L** – a custom deck that we have created and shared with you. Every user can easily create their own custom decks with the top KPIs they want to monitor.

2. **Note** that a deck contains one or more KPI “cards.”

3. Each KPI card can be customized in numerous ways. In addition to the visualization, observe that the Revenue KPI Card contains the following:
    1. An **Alert** (the top line is green – as Revenue is above target)
    2. A Comparison to **Target**
    3. A Comparison to **Previous Time Period**

![](./images/5.png " ")

### **Step 6:** 

1. On this deck, we notice that although Revenue is above target, Operating Expenses are trending up.

2. From each KPI, it’s very easy to drill into deeper insights about your finance data. Let’s drill in to OPEX to explore further.

3. Click on the **OPEX** KPI card **hamburger menu icon**.

4. Select **Operating Expense Analysis PL**.

![](./images/6.png " ")

### **Step 7:** 

1. This pre-built analysis provides additional visualizations to highlight and accelerate further analysis.

2. Observe the following:
    1. Trailing 12 months and quarterly operating expenses are increasing.
    2. The tree map visualization shows that the Call Center is the top area for expense.
    3. In the bottom bar chart, we see a spike in payroll cost.

3. Finally, click on the **back arrow** at the upper left of the screen to return to the deck.

![](./images/7.png " ")

### **Step 8:** 

1. We’re now back on the My P&L deck, which was shared with you with “view only” access. We want to dig deeper into payroll cost, so we’ll create a new custom deck that we can customize to meet our needs:

2. Click the **hamburger menu icon** on the top right.

3. Select **Add Deck**.

![](./images/8.png " ")

### **Step 9:** 

1. Name your deck **Payroll Deck ~InsertYourInitialsHere~** 

2. Click the **Save** button.

![](./images/9.png " ")

### **Step 10:** 

1. First, let’s add the **Payroll Cost KPI** to this new deck.

2. Click the **+ icon**.

![](./images/10.png " ")

### **Step 11:** 

1. **Scroll** through the KPI library so you can see all of the out of the box KPIs.

2. Select **Payroll Cost PL** KPI

3. **Note**: You see two Payroll Cost KPIs with very similar names, because one of them is a custom KPI. Be sure to select **Payroll Cost PL**.

4. You will see a Preview of the card, but we want to customize it before we add it to the deck.

![](./images/11a.png " ")

5. Click the **Customize Card** button.

![](./images/11b.png " ")

### **Step 12:** 

1. Note that by default, this KPI is configured as follows:
    1. Target: compares against the payroll cost budget.
    2. Target Value: set to % Variance from Target.

2. Now we’ll customize the KPI. Click **Show Change** checkbox.

![](./images/12a.png " ")

3. By default, Last Period is set to display a Qtr over Qtr comparison.

4. Click the **Last Period** value. 

![](./images/12b.png " ")

5. Select **Same Period Last year**.

6. The Preview updates, and we now see a new +% YoY.

![](./images/12c.png " ")

### **Step 13:** 

1. We can also customize the visualization itself in this KPI Card.

2. We’ll now do so by adding budget to the visualization.

3. In the **Detail Visualization** section, click **More Options** to expand it.

![](./images/13a.png " ")
 
4. **Scroll down** and under **Additional Data**, look for **Values**.

5. In the Values drop-down, select **Payroll Cost Budget**. We now see the budget in the visualization.

![](./images/13b.png " ")

6. To make the visualization easier to read,  go to the **Visualization** box and select **Line Bar Combo**.

![](./images/13c.png " ")

### **Step 14:** 

1. Observe how we now see actuals (blue bar) trending over budget (green line).

![](./images/14.png " ")

### **Step 15:** 

1. Now, click the **Status and Notifications** tab. The colored line (in this case, red) at the top of the KPI Card is an alert. The default rule is that Payroll Cost >110% is set to red (“Critical”).

2. Let’s customize the alert status. Change the 110% value to 130% by typing in **130**%.

3. Click the **Add Card** button.

![](./images/15new.png " ")

### **Step 16:** 

1. The KPI is now added to the deck. Payroll Cost is trending up plus over budgets. And the alert bar is showing up as yellow (“Warning”).

2. Click the **star icon** to mark as a favorite to put it on our home page.

3. Click the **maximize icon** so we can navigate to a larger card to see more information.

![](./images/16.png " ")

### **Step 17:** 

1. KPI Cards are designed to enable fast, immediate collaboration.

2. Click **Enter message** to create a note to the finance analyst to investigate payroll cost.

![](./images/17a.png " ")

3. Type the following: **Lizzy – please investigate why Payroll Cost is trending up and over budget.**

4. Click **Add Note**.

5. Notice that at the bottom of the popup window that the system recommends related metrics. In this case, the system recommends Payroll Cost Budget, Sales and Marketing, and Other Operating Expenses.

![](./images/17b.png " ")

### **Step 18:** 

1. Let's continue with our collaboration example. 

2. Click the **camera icon** to attach a snapshot image of the KPI card to the note you sent to Lizzy

3. Click the **back arrow** next to the Notes title.

![](./images/18.png " ")

### **Step 19:** 

1. Now let’s fast forward. Our business analyst, Lizzy, has completed additional analysis on this issue. She can easily share it back with us by attaching it right to the KPI. Let’s take a look at her analysis.

2. Click on the **HR Payroll and Attrition Analysis** link.

![](./images/19.png " ")

### **Step 20:** 

1. Our financial analyst created a detailed analysis based on both financial as well as HR workforce attrition data.

2. Review the analyst’s note: Lizzy observes that overtime pay started to increase in July, which was the same time the Call Center had a spike in attrition. You can see the spike in the lower left visualization.

3. Two additional items stand out:
    1. Statistical trending and forecasting capabilities enhance several visualizations, including the projected attrition trend as well as the future impact of overtime.
    2. Observe the Turnover narrative on the right was created using point and click natural language generation capabilities applied to the “Turnover by Department” visualization.

![](./images/20.png " ")

### **Step 21:** 

1. Let's return to the home page. 

2. Click the **Back arrow** in the upper left.

![](./images/21a.png " ")

3. Click **My P&L** deck.

![](./images/21b.png " ")

### **Step 22:**

1. Congratulations on completing this section! Please delete the deck with the cards you have made, which you named **Payroll Deck ~InsertYourInitialsHere~**, during this workshop by clicking on the decks' **menu bar** and selecting **Delete** for the Deck

2. Additionally, please go back to the console section where you left a **note** in Step 17 for a financial analyst to check out, and **delete** the note similarly.

![](./images/22new.png " ")

3. To recap, in this part, you:
    1. Monitored business performance with pre-built KPIs and pre-built Decks
    2. Drilled into deeper analysis, which is available through pre-built reports
    3. Collaborated with the team – within the platform – to answer questions
    4. Observed how an analyst can easily bring additional data sets – like HR data – into the platform to perform cross- functional analysis.


## Part 2. Create a KPI with the Prebuilt ERP Data Model and External Data

1. Next, let's use the Financials-AP Invoice prebuilt subject area to create a KPI for Outstanding Invoice Amounts.  We will be also using an excel file that holds the target value the company set for Outstanding Invoices

### **Step 1:** 

1. From the browser console, click on the upper left **hamburger menu icon** and then click on **KPIs**.

![](./images/2-1.png " ")

### **Step 2:** 

1. Click the **Create** button.

 ![](./images/2-2.png " ")
 
 ### **Step 3:** 

1. A "Add Data Set" window will pop-up. Select the **Financials-AP Invoice** Subject Area and then click on the **Add to KPI** button.

![](./images/2-3.png " ")

### **Step 4:** 

1. A data pane window will appear in the left area of your screen. Click on the **+ icon** next to "Data Elements".

 ![](./images/2-4-1.png " ")
 
 2.  Then, click on the **Data Sets** tab.
 
![](./images/2-4-2.png " ")
  
3. Select the **Invoice Targets** Data Set and then click on the **Add to KPI** button.
  
![](./images/2-4-3.png " ")

### **Step 5:** 

1. You should now see the Overview page of your KPI. Enter the Name of the KPI as **AP Invoices XX** where XX are your initials. 

2. Then, in the Tags field, type **invoice**.

3. Proceed to the next step by clicking the **AP Invoices XX** name in the Data Elements pane on the left.

![](./images/2-5.png " ")

### **Step 6:** 

1. In the bottom left settings pane, click the **gear icon**. Then, select **Stay Below Target** for the Target Goal

![](./images/2-6-1.png " ")

2. Select **Decrease over time** for Trends Goal

![](./images/2-6-2.png " ")

### **Step 7:** 
 
1. Expand the **Financials – AP Invoices** folder by clicking on it. Then, expand the **Facts – Ledger Currency** folder (You will need to scroll to see this folder at the bottom of the data pane) and then drag **Invoices Amount** to the Measurement box in the Data section.

![](./images/2-7.png " ")

### **Step 8:** 
 
1. Expand the **Invoice Targets** folder in the data pane window on the left. Then, drag **Invoice Target** to the Target box.

![](./images/2-8.png " ")

### **Step 9:** 

1. Scroll back to the **Facts – Ledger Currency** folder and drag **Invoice Count** to the Related Measurement box.

![](./images/2-9.png " ")
 
### **Step 10:** 
 
1. Proceed to do the same for a few elements from the **Time** folder by clicking to expanding the folder. 
 
2. Then, drag **Fiscal Year** to the Year box.
 
3. Drag **Fiscal Quarter** to the Quarter box.
 
4. Drag **Fiscal Period** to the Month box.
 
![](./images/2-10.png " ")
  
### **Step 11:** 
   
1. Click to open the the **Ledger** folder

2. Drag **Ledger** to the Related Grouping Categories box

![](./images/2-11-1.png " ")

3. Click to open the **Payables Invoicing Business Unit** folder

4. Drag Payables Invoicing Business Unit Name to Related Grouping Categories
   
![](./images/2-11-2.png " ")

### **Step 12:** 
   
1. Let's observe some conditions. Scroll down to the bottom of the screen. Notice the **Conditions** and **Links** options. This is where you can specify the target ranges as well as link to other analysis such as a Project, Dashboard or Analyses. We will leave these as the are today.
   
![](./images/2-12.png " ")

### **Step 13:** 
   
1.  Click the **Save** button at the top.
   
![](./images/2-13.png " ")

### **Step 14:** 
   
1. Let's go back to view the decks. Click on the upper left **hamburger menu icon** and then click on **Decks**.
   
![](./images/2-14.png " ")

### **Step 15:** 
   
1. Select the **Payroll Deck**.
   
![](./images/2-15.png " ")

### **Step 16:** 
   
1. First, let’s add the **AP Invoices XX** KPI to this new deck by clicking the **+ icon**.
   
![](./images/2-16.png " ")

### **Step 17:** 
   
1. Select your **AP Invoices XX** KPI. 

![](./images/2-17-1.png " ")

2. Then, click the **Add Card** button.

![](./images/2-17-2.png " ")

### **Step 18:** 
   
1. Congratulations, your new KPI for AP Invoices is now added to your Payroll Deck and is available for viewing and use!
   
![](./images/2-18.png " ")


## Part 3. Create an Analysis with the Pre-Built ERP Data Model 

1. Now, let's take a look at the out of the box GL profitability analysis and subject area and see how to customize and extend them to create new analysis and reports.

### **Step 1:** 

1. Starting from the **My P&L** deck, we’re going to drill into the out of the box Net Income Analysis.

2. Click the **Net Income PL** card **hamburger menu icon**.

![](./images/3-1a.png " ")

3. Select **Income Analysis**.

![](./images/3-1b.png " ")

### **Step 2:** 

1. Observe the following: 
    1. Net Income for the current quarter in a waterfall viz
    2. A quarterly trend for net Income, Revenue and Net Income Margin %
    3. Net income details.

2. Click the **Edit button** so we can customize this analysis. 
3. **Note**: this may take some time. If the linked page does not load in a minute, please try using a different browser.

![](./images/3-2.png " ")

### **Step 3:** 
1. First, begin by clicking on the **small down arrow icon** of the canvas and then **Duplicate Canvas**

![](./images/part2-1.png " ")

2. Rename the canvas by clicking on the **small down arrow icon** of the canvas and then **Rename**
3. Input as the name the following, making sure to input your initials **Overview ~InsertYourInitialsHere~**

![](./images/part2-2.png " ")

4. Let’s take a moment to tour the self-service project.
5. On the canvas are our four familiar visualizations. Click to highlight one.

6. Observe the grammar pane on the immediate left – it is the control panel for each visualization, allowing you to modify the visualization as needed.
7. Observe the data pane on the far left. Oracle Analytics for Fusion ERP contains a pre-built data pipeline that directly imports your ERP Cloud data, as well as a pre-built data model.
8. From this data pane, you can see views of your finance data organized into constructs called subject areas. Here, we see the Financial – GL Profitability subject area. It is organized into folders containing attributes and metrics.
9. Observe at the bottom left, you see the setting pane for whatever object we select.

![](./images/3-3.png " ")

### **Step 4:** 

1. Now we’ll build a few visualizations with the pre-built data in this subject area.

2. Click the **+ icon** at the bottom of the screen to create a new canvas.

3. Rename the canvas by clicking on the **small down arrow icon** of the canvas and then **Rename**
4. Input as the name **Fiscal ~InsertYourInitialsHere~**

![](./images/part2-2.png " ")

5. To build our first visualization, let's make a simple pivot table. In the **Data pane**, do the following:
    1. Click to open the **Time** folder in the **Financials - GL Profitability** folder
    2. Right Click **Fiscal Quarter**
    3. Select **Pick Visualization** from the popup window
    4. Select the **Pivot icon**

![](./images/3-4a.png " ")

6. **Drag** the **Data pane** wider so you can see better.

7. Click the **Balancing Segment Hierarchy** folder to open.

8. Double Click **Balancing Segment Level 30 Description**.

9. Scroll down the **data pane**.

![](./images/3-4b.png " ")

10. Click **Facts – Ledger Currency folder** to open.

11. Click **Profit and Loss (LC)** subfolder to open.

12. Double Click **Net Income**.

13. And it’s as simple as that to create your first visualization – slicing and dicing net income by different dimensions.

14. Let's finish by enabling a filter for two fiscal years by clicking on the **Fiscal Year (2)** filter's **hamburger menu icon** and then on **Enable Filter**

![](./images/3-4d.png " ")

15. Your visualizations should now look similar to the following: 

![](./images/3-4c.png " ")

### **Step 5:** 

1. We’ll create a second visualization by duplicating this pivot table.

2. On the upper right of the pivot table visualization, click the hamburger menu icon

3. Hover over **Edit**

4. Click on Duplicate Visualization to add a duplicate to the canvas.

![](./images/3-5.png " ")

### **Step 6:** 

1. Select the right pivot table visualization if not selected already

2. Click the **Visualization Type icon**.

3. Select **Area icon** from the dropdown list.

![](./images/3-6.png " ")

### **Step 7:** 

1. Your new “Area” visualization will now look like this. You can see that the combination of the table and the visualization helps tell the story more clearly.
2. **Note**: If your new visualization looks different from what is shown, double-check the fields on the grammar pane and adjust it as necessary.

![](./images/3-7.png " ")

### **Step 8:** 

1. We’ll now further customize this visualization by adding data labels.

2. With **# Net Income** selected, scroll down to the bottom left settings panel.

3. Click on the **#** menu, and make the following modifications:
    1. Data Label: Select **Auto**
    2. Font: Select **Auto** and click the **bold icon**
    3. Number Format: Select **Number**
    4. Decimal: Select **None**
    5. Abbreviate: Select **On**

![](./images/3-8.png " ")

### **Step 9:** 

1. Now your visualization is much more readable with the data values. Let’s create another visualization.

2. On the upper right of the area visualization, click the **hamburger menu icon**

3. Hover over **Edit**

4. Click on **Duplicate Visualization**

![](./images/3-9.png " ")

### **Step 10:** 

1. Let's reorganize the visualizations on the canvas.

2. Click on one of the area visualizations and drag it above the pivot table. Watch for the blue bar to show before releasing your mouse.

![](./images/3-10.png " ")

### **Step 11:** 

1. Select the visualization you just dragged to the top (the visualization will be outlined in blue when it is selected).

2. In the grammar pane on the left, remove **Fiscal Quarter** by clicking the **x**.

![](./images/3-11.png " ")

### **Step 12:** 

1. Let's change the visualization type.

2. In the grammar pane on the left, click **Area**.

3. Select **Donut** from the dropdown list.

![](./images/3-12.png " ")

### **Step 13:** 

1. Scroll up the Data pane. 

2. Open the **Time** folder.

3. Click and drag **Fiscal Year** to the **Trellis Columns** area in the grammar pane.

![](./images/3-13.png " ")

### **Step 14:** 

1. The visualization now compares net income by regional segments across fiscal years.

![](./images/3-14.png " ")

### **Step 15:** 

1. We’ll next create a text narrative description of the area visualization. First let’s duplicate the area visualization. 

2. On the Upper right of the Area visualization, click the **hamburger menu icon**

3. Hover over **Edit**

4. Click **Duplicate Visualization** to add a duplicate to the canvas.

![](./images/3-15.png " ")

### **Step 16:** 

1. Select the new duplicate Area visualization if not selected already

2. Click the **Visualization Type** icon.

3. Select **Language Narrative icon** from the dropdown list.

![](./images/3-16.png " ")

### **Step 17:** 

1. A generated narrative describing the Area visualization will appear on the left.

![](./images/3-17.png " ")

## Part 4. Blend ERP data with External Data

1. Let's now go through how to extend your analysis by blending in an external data source that provides additional insight to your ERP data. 

2. **Note**: when going through this part, your visualizations may looks slightly different from what is seen in the demo guide. This is okay- the data on the backend instance is updated regularly so the visualizations may look differently for you.

### **Step 1:** 

1. Let’s navigate to the Home page.

2. Select the **hamburger menu icon** on the top left.

3. Click **Home**.

![](./images/4-1.png " ")

### **Step 2:** 

1. Below the Get Started banner, you will see shortcuts to pre-built analyses. 

2. Click **Projects and Reports**

![](./images/4-2.png " ")

### **Step 3:** 

1. In the search bar, input **AP Analysis Lab Demo** and click on the **AP Analysis Lab Demo** project

![](./images/step4-project.png " ")

### **Step 4:** 

1. This project contains analyses across two subject areas, AP Invoices and AP Balances. Visualizations include:
    1. AP Balances with a quarterly trend.
    2. Top 10 suppliers with AP Balances.
    3. Top Invoice Amounts by Payment Terms and Supplier Names.

2. Click the **+ icon** at the bottom of the screen to create a new canvas.

![](./images/part4-1new2.png " ")

3. Please rename this new canvas to **Analysis ~InsertYourInitialsHere~** by clicking on the **small down arrow icon** of the canvas and then **Rename**

![](./images/part4-1new3.png " ")

### **Step 5:** 

1. Let's download an excel dataset file from this workshop to load into your instance. You can download it by clicking on the following text link: [Download supplier\_risk\_ratings.xlsx here](https://objectstorage.us-ashburn-1.oraclecloud.com/p/vq-e_pds9JCsEbPmtqIxazJWvGepb0qV6vYyCCa2qis/n/orasenatdpltoci01/b/cloud-data-platform-workshop-files/o/supplier_risk_ratings.xlsx). Then, return back to Fusion ERP Analytics in your browser window.

2. In the data pane, click on the **+ icon** at the top and then select **Add Data Set** in the popup window.

![](./images/4-5-2.png " ")

3. Click **Create Data Set** button.

![](./images/4-5-3.png " ")

4. Click **Drop data file here or click to browse**.

![](./images/4-5-4.png " ")

5. Select the **supplier\_risk\_ratings.xlsx** excel file you downloaded previously and then click on the **Open** button.

### **Step 6:** 

1. Observe the following column definitions in the supplier credit ratings file:
    1. The Credit Risk score measures a business’s past payment performance.  
    2. The Ability to Pay rating helps predict the chance a supplier will become inactive or shut down in the next 12 months.

2. Continue by clicking the **Add** button.

![](./images/4-6.png " ")

### **Step 7:** 

1. Click the **Data Diagram** tab at the bottom of the window.

![](./images/4-7.png " ")

### **Step 8:** 

1. The system automatically joins fields with the same name. Click the **blue bubble 1** on the join line to examine how the new spreadsheet is joined to the pre-built subject area data. Observe that it matched on supplier name. If there was no automatic match then you could add the match manually. Proceed by clicking the **OK** button.

![](./images/4-8-1.png " ")

2. Then, in the upper right of the screen, click the **Visualize** link.

![](./images/4-8-2.png " ")

### **Step 9:** 

1. Let’s create a visualization that uses data from both the subject area and the excel file. In the data pane, confirm you are in the **Financials - AP Invoices Subject Area** and click the **Supplier** folder to expand it and then double click on **Supplier Name**. 

![](./images/4-9-1.png " ")

2. Now, click on the **Facts – Ledger Currency** folder to expand it and then double click on **Invoice Amount**.

![](./images/4-9-2.png " ")

3. Then, click on the **supplier\_credit\_ratings** folder to expand it and double click on **Credit Risk**.

![](./images/4-9-3.png " ")

### **Step 10:** 

1. The system automatically creates a scatter chart in which each bubble represents a supplier. A Credit Rating of closer to 10 indicates high risk. Let’s add Ability to Pay into the scatter. In the data pane, double click on **Ability to Pay** from the **supplier\_credit\_ratings** folder. Ability to Pay will then be added to the visualization as the bubble color.

![](./images/4-10.png " ")

### **Step 11:** 

1. Let’s add Invoice count into the scatter. In the data pane, double click on **Invoices Count** from the **Facts – Ledger Currency** folder. Invoices Count is then added to the visualization as the bubble size.

![](./images/4-11.png " ")

### **Step 12:** 

1. Let’s filter for just the top 10 suppliers. In the grammar pane, click on **# Invoices Amount** and drag it to the **Filters** section. Disregard the popup window.

![](./images/4-12-1.png " ")

2. In the **Filters** section of the grammar pane, do the following:
    1. Click on **Invoice Amount** in the filter. 
    2. Hover over or click on **Filter Type**. 
    3. Select **Top Bottom N**.

![](./images/4-12-2.png " ")

### **Step 13:** 

1. A popup window will appear. The default is 10, which we will accept. Click anywhere on the visualization to close the popup window. Your visualization should look similar to this:

![](./images/4-13.png " ")

### **Step 14:** 

1. Let’s add data labels to the visualization. At the bottom left settings panel, click on the **#** icon to access its menu. Then, click on the **Data Label** option and click on  **Auto**.

![](./images/4-14.png " ")

### **Step 15:** 

1. The visualization helps to identify a supplier that we may introduce some risk, and may require deeper analysis. For now, let's go ahead and save your work. 

![](./images/4-15.png " ")

2. First, click **Save As** at the top. Then, name your project **Net Income Analysis XX** where XX are your initials. Proceed by clicking on the **Save** button. Note: you may see a generating thumbnail message. If you do, click on **Skip** to ignore it.

### **Step 16:**

1. Nice work on making these canvases and visualizations! Please go ahead and delete the canvases with your initials at this time by clicking on the canvas **down arrow icon** and selecting **Delete Canvas**. There should be one canvas you need to delete in this project, **Analysis ~InsertYourInitialsHere~**. Please do the same for your **Net Income Analysis XX** project.

![](./images/part2-3.png " ")

2. When exiting the instance, make sure you don't save any changes made during the demo by clicking on **Don't Save** when any **Save Changes?** text boxes pop up.

## Summary

-   In this demo, you explored Oracle Fusion ERP Analytics. You navigated the Interface and pre-built content through KPI Cards, Decks, Alerts, and Analysis. You also created a KPI with an ERP Data Model and External Data, constructed an Analysis with an ERP Data Model, and blended ERP data with External Data


## Acknowledgements

- **Author** - NA Cloud Engineering - Philip Pavlov
- **Last Updated By/Date** - Philip Pavlov, Analytics Specialist, March 2021

See an issue?  Please open up a request [here](https://github.com/oracle/learning-library/issues).   Please include the demo name and section in your request. 
