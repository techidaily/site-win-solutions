---
title: Mastering the Art of Changing String Data to Date Formats in Excel Efficiently
date: 2024-08-27 16:57:35
updated: 2024-08-29 12:37:34
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/office_excel_lede-1.png
---

## Mastering the Art of Changing String Data to Date Formats in Excel Efficiently

### Quick Links

* [Dates that Contain a Full Stop/Period](https://instagram-video-recordings.techidaily.com/updated-in-2024-the-ultimate-guide-to-instagram-desktop-video-upload/)
* [Converting the yyyymmdd Format](https://extra-approaches.techidaily.com/in-2024-step-by-step-tailoring-your-way-to-youtube-subtitles-srt/)
* [DATEVALUE and VALUE Functions](https://hardware-tips.techidaily.com/experience-unmatched-speed-save-75-on-editors-pick-the-elegoo-neptune-4-pro-printer/)

 Analysis of business data often requires working with date values in Excel to answer questions such as "how much money did we make today" or "how does this compare to the same day last week?" And that can be hard when Excel doesn't recognize the values as dates.

 Unfortunately, this is not unusual, especially when multiple users are typing this information, copying and pasting from other systems and importing from databases.

 In this article, we will describe four different scenarios and the solutions to convert the text to date values.

##  Dates that Contain a Full Stop/Period

 Probably one of the most common mistakes beginners make when typing dates into Excel is doing so with the full stop character to separate the day, month, and year.

 Excel will not recognize this as a date value and will go ahead and store it as text. However, you can solve this problem with the Find and Replace tool. By replacing the full stops with slashes (/), Excel will automatically identify the values as dates.

 Select the columns on which you want to perform the find and replace.

![Dates with a full stop separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/full-stop-dates.png) 

 Click Home > Find & Select > Replace---or press Ctrl+H.

![Find and select values in a column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/find-and-select-1.png) 

 In the Find and Replace window, type a full stop (.) in the "Find what" field and a slash (/) in the "Replace with" field. Then, click "Replace All."

![filling out the find and replace values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/find-and-replace-window-1.png) 

 All full stops are converted to slashes and Excel recognizes the new format as a date.

![Dates with a full stop separator](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/full-stop-dates.png) 

 If your spreadsheet data is regularly changing, and you want an automated solution for this scenario, you could use [the SUBSTITUTE function](https://support.office.com/en-us/article/substitute-function-6434944e-a904-4336-a9b0-1e58df3bc332).

=VALUE(SUBSTITUTE(A2,".","/"))

 The SUBSTITUTE function is a text function, so cannot convert it to a date on its own. The VALUE function will convert the text value to a numeric value.

 The results are shown below. The value needs to be formatted as a date.

![SUBSTITUTE formula to convert text to dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/substitute-resized-1.png) 

 You can do this using the "Number Format" list on the "Home" tab.

![Formatting number as a date](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/number-format-2.png) 

 The example here of a full stop delimiter is typical. But you can use the same technique to replace or substitute any delimiter character.

##  Converting the yyyymmdd Format

 If you receive dates in the format shown below, it will require a different approach.

![Dates in the yyyymmdd format](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/yyyymmdd-format.png) 

 This format is quite standard in technology as it removes any ambiguity about how different countries store their date values. However, Excel will not initially understand it.

 For a quick manual solution, you could [use Text to Columns](https://ios-location-track.techidaily.com/in-2024-top-10-telegram-spy-tools-on-apple-iphone-14-pro-for-parents-drfone-by-drfone-virtual-ios/).

 Select the range of values you need to convert and then click Data > Text to Columns.

![Text to Columns button from the Data tab](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-to-columns-resized.png) 

 The Text to Columns wizard appears. Click "Next" on the first two steps so that you are at step three, as shown in the image below. Choose Date and then select the date format being used in the cells from the list. In this example, we are dealing with a YMD format.

![Text to Columns to convert 8 digit numbers to dates](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-to-columns-date-format-3.png) 

 If you would like a formula solution, then you could use the Date function to construct the date.

 This would be used alongside the text functions Left, Mid and Right to extract the three parts of a date (day, month, year) from the cell contents.

 The formula below shows this formula using our sample data.

=DATE(LEFT(A2,4),MID(A2,5,2),RIGHT(A2,2))

![Using the DATE formula with 8 digit numbers](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/date-formula-resized.png) 

 Using either of these techniques, you can convert any eight-digit number value. For example, you might receive the date in a ddmmyyyy format or a mmddyyyy format.

##  DATEVALUE and VALUE Functions

 Sometimes the problem is not caused by a delimiter character but has an awkward date structure simply because it is stored as text.

 Below is a list of dates in a variety of structures, but they are all recognizable to us as a date. Unfortunately, they have been stored as text and need converting.

![Dates stored as text](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/text-dates.png) 

 For these scenarios, it is easy to convert using a variety of techniques.

 For this article, I wanted to mention two functions to handle these scenarios. They are DATEVALUE and VALUE.

 The DATEVALUE function will convert text into a date value (probably saw that coming), while the VALUE function will convert text into a generic number value. The differences between them are minimal.

 In the image above, one of the values contains time information as well. And that will be a demonstration of the functions' minor differences.

 The DATEVALUE formula below would convert each one to a date value.

=DATEVALUE(A2)

![DATEVALUE function to convert to date values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/datevalue-resized.png) 

 Notice how the time was removed from the result in row 4\. This formula strictly returns just the date value. The result will still need to be formatted as a date.

 The following formula uses the VALUE function.

=VALUE(A2)

![VALUE function to convert text to numeric values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2019/05/value-resized.png) 

 This formula will produce the same results except for in row 4, where the time value is also maintained.

 The results can then be formatted as date and time, or as a date to hide the time value (but not remove).

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
