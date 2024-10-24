---
title: "Excelling in Non-Accounting Tasks: How Excel Enhances Daily Productivity for All Professionals"
date: 2024-08-28T05:02:12.642Z
updated: 2024-08-29T05:02:12.642Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/f999915018347bdff47350b20a165acd94706d7edbf7c9a39198b21a53e266f6.jpg
---

## Excelling in Non-Accounting Tasks: How Excel Enhances Daily Productivity for All Professionals

### Quick Links

* [Budgeting](https://instagram-video-files.techidaily.com/new-8-best-popular-instagram-after-effects-templates/)
* [Vacation Destinations With Different Criteria](https://screen-mirroring-recording.techidaily.com/in-2024-securing-every-moment-tips-for-reliable-capture-of-google-meet-sessions/)
* [Tracking My Sports Team’s Stats](https://youtube-webster.techidaily.com/ontent-strategy-boost-top-8-youtube-rank-watcher-revealed-for-2024/)
* [Tracking My Weight (I’m on a Diet!)](https://www.howtogeek.com/excel-isnt-just-for-accountants-ways-i-use-it-in-my-daily-life/#tracking-my-weight-i-rsquo-m-on-a-diet)

 Excel is often seen as a complicated program for highly trained accountants, but this isn't necessarily the case. I use Excel daily to keep track of my budgeting, choose the ideal vacation destination, track my team's sports stats, and keep an eye on my weight-loss progress... and you can too!

##  1\. Budgeting

 With today's never-ending cost-of-living increases, I use Excel to manage my budgeting and keep track of how much disposable income I have left over each month.

 First, create an Excel table by typing **Type**, **Details**, **Cost**, **To Pay**, and **Date** in cells A1 to E1.

* The Type column is the category of the expenditure (useful for filtering later on).
* The Details column contains the specific information about what the cost is.
* The Cost column contains the specific price of the expenditure.
* Leave the To Pay column blank for now.
* The Date column reminds you of when the payment is due to be made.

 Once you have input the data into columns A, B, C, and E, [format your table](https://instagram-videos.techidaily.com/updated-2024-approved-how-to-convert-your-best-videography-into-melodic-mp3s-insta/) and [give your table a name](https://facebook-record-videos.techidaily.com/new-your-essential-guide-to-mobile-asmr-sounds/). In my case, I've called it Budgeting.

 Whenever you type a date in Excel, make sure the [cell data type is set to "Date."](https://video-capture.techidaily.com/new-from-playback-to-printout-top-five-methods-of-documenting-minecraft-on-a-mac-for-2024/) This will mean that Excel can use these dates to help you manage your budget automatically.

![A formatted table in Excel with details of expenditures for budgeting purposes.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/budgeting-1-1.png) 

 Now, in cell G1, type **Today's Date**, in cell G2, type **End of Month**, and in cell G3, type **Days Left**.

 In cell H1, type the following formula to generate today's date:

=today()

 In cell H2, type the last date of the current month manually.

 In cell H3, type the following formula to calculate the number of days remaining in the month:

=SUM(H2-H1)

![An Excel budgeting spreadsheet with today's date, the end of the month, and the days remaining.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/budgeting-2-1.png) 

 We're now ready to populate column D. In cell D2, type

=IF([@Date]<$H$1,"PAID",[@Cost])

 This means that if the date of the payment item in row 2 is earlier than today's date (in cell H1), we want Excel to mark it as Paid. If the date is later than today's date, the total cost of that item will show in this cell. When you press enter after typing the formula, the rest of the column will populate automatically.

![An Excel table with monthly budgeting and the To Pay column populated.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/budgeting-3-1.png) 

 Finally, we can now use all this information to calculate our budget.

 Underneath your formatted table, in column A, type **Bank balance**, **Total expenditure**, **Total left to pay**, **Leftover**, and **Daily budget** on separate rows. Then, you will need to add totals or formulas to the corresponding cells in column B as follows:

![An Excel sheet with budgeting totals underneath the main expenditure table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/budgeting-4-1.png) 

 Type your bank balance manually. You should update this cell each time you return to check your budget.

 Then, in the cell next to Total expenditure, type

=SUM(Budgeting[Cost])

 where _Budgeting_ is the name we assigned to our table, and _\[Cost\]_ is the name of the column we're totalling.

 Now, in the cell next to Total left to pay, type

=SUM(Budgeting[To pay])

 In the cell next to Leftover, type

=SUM(B21-B23)

 where _B21_ is your manually-added bank balance, and _B23_ is the cell containing the total left to pay.

 In the cell next to Daily budget, type

=SUM(B24/H3)

 where _B24_ is the total leftover, and _H3_ is the number of days remaining in the month.

 You now have a complete monthly budgeting spreadsheet. Simply duplicate the sheet each month to set up a new budget. Then, amend that month's payment details, change the last day of the month in cell H2, and keep your bank balance updated.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  2\. Vacation Destinations With Different Criteria

 With so many options for different vacation destinations, Excel can help you keep these in order. Yes, there are websites that can help you with some criteria, but how about those specific elements that matter to you, such as property with a fireplace, or a region with a dark sky for those of you who love stargazing? Whatever it is you're looking for, use Excel to whittle down your options without having to pay that extra percentage for third-party booking commissions.

 I love going on short stays around the UK, and this spreadsheet started off with a few notes about some of the properties that tickled my fancy. But as I stayed at more places, I started to realize what elements mattered to me the most, and my spreadsheet quickly expanded.

![An Excel sheet with a list of holiday properties and several criteria.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/holiday-cottages-list.png) 

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
 Here are some of the tools I benefit from the most when using my spreadsheet:

* [Freeze panes](https://extra-lessons.techidaily.com/prime-traffic-magnet-design/): With my spreadsheet being so vast, I decided to freeze the property link and name columns and the header row. This means that, whenever I scroll across or down, those parts remain visible. In the example above, I selected cell C3, and in the View tab on the ribbon, I clicked "Freeze Panes" to freeze row 1 and columns A and B.
* [Filters](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/): The whole purpose of this spreadsheet is to help me choose which property to go to based on specific criteria. So, I added a filter to my spreadsheet. I selected the whole of row 1, headed to the Data tab on the ribbon, and clicked the "Filter" button. Now, I can use the filter drop-down arrows in each column to nitpick my preferences. For example, I can order the price from lowest to highest in column D, remove all properties that don't allow dogs in column I, and filter by color according to the light pollution in column H.
* [Hidden rows and columns](https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-6-by-drfone-ios/) containing formulas: I have hidden row 2 in my spreadsheet because I've added details in columns F and G that I don't want to display on my sheet or be included in the filters I apply. In cell F2, I typed my car's miles per gallon, and in cell G2, I converted the total gallons to liters, so that I could work out the fuel cost for the trip. To hide a row or column, right-click on the gray header (the column letter or column number), and click "Hide."
* Color code: As an avid stargazer, I use a [light pollution map](https://www.lightpollutionmap.info/) to find out whether there's a good chance of seeing the Milky Way. I then use Excel's color fill to match the cell color with the light pollution indicator. Blues on the map represent little light pollution, while yellows and oranges represent heavy light pollution. I can then filter column H by color to see which properties are likely to offer the best skies.
* [Notes](https://video-screen-grab.techidaily.com/how-to-expertly-archive-your-favorite-streamed-shows-hulu-for-2024/): Notice the red markers on cells B14 and B17\. These show that I've added a note to that cell that I didn't want to add as an extra column to the spreadsheet. For example, in B14, I made a note that the minimum stay at that property is five nights. To do this, simply right-click the relevant cell, and click "New Note."

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
##  3\. Tracking My Sports Team’s Stats

 This is my favorite Excel workbook. Like with most spreadsheets, they started off really simple, and I've gradually added to them over time.

 The best tools for creating these spreadsheets have been conditional formatting and charts.

![An Excel spreadsheet containing players' details for each game.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/player-game-details.png) 

 As you can see in the screenshot above, I've used [conditional formatting](https://ai-live-streaming.techidaily.com/simple-tricks-avoiding-hassle-while-uninstalling-nvidia-geforce-experience/) to automatically apply color to cells based on their values (such as red for L, yellow for D, and green for W). To do this, I selected the whole of column D, opened "Conditional Formatting" in the Home tab, and clicked "New Rule." I then clicked "Format Only Cells That Contain" and completed the details of the rule in the easy-to-follow dialog box.

![An Excel sheet showing player stats, and conditional formatting used to display data bars.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/player-stats.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
 On this sheet, I've used an in-built conditional formatting rule to create data bars. I selected column B, clicked "Conditional Formatting" in the Home tab, and hovered over "Data Bars." I could then choose the data bar type that best aligned with my spreadsheet's formatting. Then, I used the Format Painter tool to apply the same rules to the other columns, alternating between blue and green for clarity.

![An Excel dashboard containing four charts based on data on the other sheets in the workbook.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/dashboard.png) 

 My sports team tracking workbook contains 12 tabs overall, so I created a dashboard sheet that pulls together the key information in chart form in one place. Click the "+" at the bottom of your workbook to add a new sheet, and double-click the new tab to rename it **Dashboard**. Then, use the Charts group in the Insert tab on the ribbon to [choose different graphs](https://technical-tips.techidaily.com/top-techniques-for-enhancing-photo-quality-on-your-ios-device/) that will work well for your data. Finally, you can [format your data labels](https://win11.techidaily.com/new-era-of-connectivity-windows-for-iphones-ipads-and-pcs-just-dropped/) and chart colors to make them look exactly how you want, and [hide the gridlines](https://driver-download.techidaily.com/easy-guide-to-installing-amd-radeon-hd-7700-graphics-card-driver-updates/) to add that extra presentational touch to your dashboard.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453721/17020" target="_top" id="1453721"><img src="//a.impactradius-go.com/display-ad/17020-1453721" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453721/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
##  4\. Tracking My Weight (I’m on a Diet!)

 Who knew that Excel could be a weight-loss motivator?

![An Excel sheet with a table on the left containing date, weight, and target values, and a line chart on the right displaying the data in the table.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/05/weight-tracking.png) 

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
 Using Excel's formatted table function and line chart, I created a spreadsheet to track my weight and show me how close to my target I am getting:

1. Start by creating a table by typing **Date**, **Weight**, and **Target** into cells A1, B1, and C1, respectively. Once you have your first row of data, highlight all the cells in the table (including the headers), and head to the Home tab. From there, in the Styles group, click "Format As Table," and check the "My Table Has Headers" box.
2. Next, you should name your table. Click anywhere on your formatted table, and in the Table Design tab, rename the table as **Weight** in the Table Name field on the left.
3. Now, click anywhere on the table again, and click the "Line Chart" option in the Insert tab.
4. Finally, double click anywhere on your newly created chart to format its design and amend the axis options to suit your needs.

 To add a new row for the next day's data, right-click the bottom row of your table, hover over "Insert," and click "Table Row Below."

---

 Once you start using Excel for your everyday dealings, you'll undoubtedly find even more uses for this dynamic program, and using [these little-known Excel functions](https://win-howtos.techidaily.com/error-0xc1900208-on-windows-11-updates-heres-how-you-can-fix-it/) can help you to make your spreadsheets more adaptable to your needs.

ending

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


