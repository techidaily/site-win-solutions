---
title: "Step-by-Step Guide: Counting Actively Used Sheets in Microsoft Excel"
date: 2024-08-28T05:02:03.883Z
updated: 2024-08-29T05:02:03.883Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/4a2496ce821a6c52eaf0cfecea597eea88a88766153a92e1f9e8401a4428c9fb.jpg
---

## Step-by-Step Guide: Counting Actively Used Sheets in Microsoft Excel

If you have large workbooks with a lot of formulas on the worksheets, recalculating the workbooks can take a long time. By default, Excel automatically recalculates all open workbooks as you change values in the worksheets. However, you can choose to recalculate only the current worksheet manually.

 Notice I said worksheet, not workbook. There is no direct way in Excel to manually recalculate only the current workbook, but you can manually recalculate the current worksheet within a workbook.

 To begin, click the “File” tab.

![01_clicking_the_file_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/01_clicking_the_file_tab.png) 

 On the backstage screen, click “Options” in the list of items on the left.

![02_clicking_options](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/02_clicking_options-1.png) 

 The Excel Options dialog box displays. Click “Formulas” in the list of items on the left.

![03_clicking_formulas](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/03_clicking_formulas.png) 

 In the Calculation options section, click the “Manual” radio button to turn on the ability to manually calculate each worksheet. When you select “Manual”, the “Recalculate workbook before saving” check box is automatically checked. If you save your worksheet often and would rather not wait for it to recalculate every time you do, select the “Recalculate workbook before saving” check box so there is NO check mark in the box to disable the option.

 You’ll also notice the “Automatic except for data tables” option. Data tables are [defined by Microsoft](https://support.office.com/en-us/article/Calculate-multiple-results-by-using-a-data-table-e95e2487-6ca6-4413-ad12-77542a5ea50b) as:

> “. . . a range of cells that shows how changing one or two variables in your formulas will affect the results of those formulas. Data tables provide a shortcut for calculating multiple results in one operation and a way to view and compare the results of all the different variations together on your worksheet.”

 Data tables are recalculated every time a worksheet is recalculated, even if they have not changed. If you’re using a lot of data tables, and you still want to automatically recalculate your workbooks, you can select the “Automatic except for data tables” option, and everything except for your data tables will be recalculated, saving you some time during recalculation.

![04_selecting_manual](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/04_selecting_manual.png) 

 If you don’t mind the “Recalculate workbook before saving” option being enabled when you turn on Manual calculation, there is a quicker way of choosing to manually recalculate your worksheets. First, click the “Formulas” tab.

![05_clicking_formulas_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/05_clicking_formulas_tab.png) 

 Then, in the Calculation section of the Formulas tab, click the “Calculation Options” button and select “Manual” from the drop-down menu.

![06_selecting_manual_on_formulas_tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2016/04/06_selecting_manual_on_formulas_tab.png) 

 Once you’ve turned on manual calculation, you can click “Calculate Sheet” in the Calculation section of the Formulas tab, or press Shift+F9, to manually recalculate the active worksheet. If you want to recalculate everything on all worksheets in all open workbooks that has changed since the last calculation, press F9 (only if you have turned off Automatic calculation). To recalculate all formulas in all open workbooks, regardless of whether they have changed since the last recalculation, press Ctrl+Alt+F9\. To check formulas that depend on other cells first and then recalculate all formulas in all open workbooks, regardless of whether they have changed since the last recalculation, press Ctrl+Shift+Alt+F9.

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1572622/13846" target="_top" id="1572622"><img src="//a.impactradius-go.com/display-ad/13846-1572622" border="0" alt="" width="1000" height="1298"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1572622/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->