---
title: Guide on Consolidating, Refining Shape, and Modifying Size of Worksheets Within Excel Spreadsheets
date: 2024-08-28T05:00:46.788Z
updated: 2024-08-29T05:00:46.788Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2021/09/microsoft_excel_hero_1200x675.jpg
---

## Guide on Consolidating, Refining Shape, and Modifying Size of Worksheets Within Excel Spreadsheets

### Quick Links

* [Combine Arrays](https://youtube-tips.techidaily.com/ed-premier-directory-of-economical-visual-content-providers-for-2024/)
* [Reshape Arrays](https://youtube-videos.techidaily.com/a-global-perspective-your-favorite-travel-youtubers-for-2024/)
* [Resize Arrays](https://instagram-videos.techidaily.com/new-2024-approved-step-by-step-designing-aplus-cover-photos-for-your-insta-highlights/)

 Working with arrays, or adjacent cell ranges, in Microsoft Excel can be challenging at times. If you'd like to combine, reshape, or resize an array, you can choose from a [collection of functions](https://win11.techidaily.com/renaissance-pc-refresh-with-atlasos/) that can cover many situations.

 These 11 functions are new to Excel as of August 2022\. They're rolling out to Excel users over time beginning with [Office Insiders](https://tech-haven.techidaily.com/rethinking-ai-why-claude-3-surpasses-chatgpt-in-4-ways/).

##  Combine Arrays

[Combining data](https://extra-approaches.techidaily.com/new-meme-creation-at-its-peak-10-templates-unveiled/) in a spreadsheet can be difficult. With the VSTACK and HSTACK functions, you can stack arrays vertically and horizontally.

Related: [How to Combine Data From Spreadsheets in Microsoft Excel](https://extra-approaches.techidaily.com/new-meme-creation-at-its-peak-10-templates-unveiled/) 

 The syntax for each function is the same as 

        `VSTACK(array1, array2,...)`
    
 and 

        `HSTACK(array1, array2,...)`
    
 with only one required array and others optional.

 To combine the arrays in cells B2 through F3 and H2 through L3 vertically, use this formula for the VSTACK function:

=VSTACK(B2:F3,H2:L3)

![VSTACK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/VSTACK-ExcelArrayFunctions.png) 

 To combine those same arrays horizontally instead, use this formula for the HSTACK function:

=HSTACK(B2:F3,H2:L3)

![HSTACK function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/HSTACK-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
##  Reshape Arrays

 If it's not combining arrays that you want to do but reshaping them instead, there are four [functions you can use](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/).

Related: [12 Basic Excel Functions Everybody Should Know](https://visual-screen-recording.techidaily.com/in-2024-a-step-by-step-recorder-for-discord-enthusiasts/) 

###  Convert an Array to a Row or Column

 First, the TOROW and TOCOL functions let you shape the array as a row or a column. The syntax for each is `TOROW(array, ignore, by_column)` and `TOCOL(array, ignore, by_column)`.

* **Ignore**: To ignore certain types of data, enter 1 for blanks, 2 for errors, or 3 for blanks and errors. The default is 0 to ignore no values.
* **By\_column**: Use this argument to scan the array by column using TRUE. If no argument is included, FALSE is the default, which scans the array by row. This determines how the values are ordered.

 To convert the array B2 through F3 to a row, use this formula with the TOROW function:

=TOROW(B2:F3)

![TOROW function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TOROW-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
 To convert that same array to a column instead, use the TOCOL function with this formula:

=TOCOL(B2:F3)

![TOCOL function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TOCOL-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600114&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Mac： Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
###  Convert a Row or Column to an Array

 To do the opposite of the above and convert a row or column to an array, you can use WRAPROWS and WRAPCOLS. The syntax for each is `WRAPROWS(reference, wrap_count, pad)` and `WRAPCOLS(reference, wrap_count, pad)` with the `reference` being a group of cells.

* **Wrap\_count**: The number of values for each row or column.
* **Pad**: The value to display for the pad (empty cell).

 To convert the cells B2 through K2 to a two-dimensional array by wrapping rows, use the WRAPROWS function. With this formula, the cells are wrapped using three values per row with "empty" as the `pad`.

=WRAPROWS(B2:K2,3,"empty")

![WRAPROWS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/WRAPROWS-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To convert the same cells into a two-dimensional array by wrapping columns, use the WRAPCOLS function. With this formula, the cells are wrapped using three values per column with "empty" as the `pad`.

=WRAPCOLS(B2:K2,3,"empty")

![WRAPCOLS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/WRAPCOLS-ExcelArrayFunctions.png) 

##  Resize Arrays

 Maybe you want to adjust the size of an array by adding some data or dropping unnecessary cells. There are five [functions to help](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) you do this depending on the result you want.

Related: [13 Essential Excel Functions for Data Entry](https://vimeo-videos.techidaily.com/in-2024-high-end-downloads-best-10-apps-for-extracting-vimeo-videos/) 

###  Take or Drop Rows or Columns

 With the TAKE function, you keep the number of rows or columns you specify. With the DROP function, you do the opposite and remove the number of rows or columns you specify. You'll use positive numbers to take or drop from the start of the array and negative numbers to take or drop from the end.

 The syntax for each is `TAKE(array, rows, columns)` and `DROP(array, rows, columns)` where you need at least one of the second two arguments; `rows` or `columns`.

 To keep the first two rows in the array B2 through F5, use TAKE with the `rows` argument. Here's the formula:

=TAKE(B2:F5,2)

![TAKE function for rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TAKErows-ExcelArrayFunctions.png) 

 To keep the first two columns in that same array, use the `columns` argument instead:

=TAKE(B2:F5,,2)

![TAKE function for columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/TAKEcolumns-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To remove the first two rows in the array B2 through F5, use DROP with the `rows` argument and this formula:

=DROP(B2:F5,2)

![DROP function for rows](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/DROProws-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
 To remove the first two columns in that same array, use the `columns` argument instead and this formula:

=DROP(B2:F5,,2)

![DROP function for columns](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/DROPcolumns-ExcelArrayFunctions.png) 

###  Keep a Certain Number of Rows or Columns

 To select the exact row and column numbers you want to keep from an array, you'd use the CHOOSEROWS and CHOOSECOLS functions.

 The syntax for each is `CHOOSEROWS(array, row_num1, row_num2,...)` and `CHOOSECOLS(array, column_num1, column_num2,...)` where the first two arguments are required. You can add more row and column numbers if you like.

 To return rows 2 and 4 from the array B2 through F5, you'd use the CHOOSEROWS function and this formula:

=CHOOSEROWS(B2:F5,2,4)

![CHOOSEROWS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/CHOOSEROWS-ExcelArrayFunctions.png) 

 To return columns 3 and 5 from the same array, you'd use the CHOOSECOLS function with this formula:

=CHOOSECOLS(B2:F5,3,5)

![CHOOSECOLS function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/CHOOSECOLS-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Remember to use the row or column numbers for the array, _not_ for the sheet.

###  Expand an Array to Specific Dimensions

 Maybe you plan to add more data to your array, so you want to make it a specific size to [add a border](https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-on-apple-iphone-14-by-drfone-ios/) or use [conditional formatting](https://fox-blue.techidaily.com/updated-2024-approved-ultimate-list-selecting-excellent-webcams-for-podcasts/). With the EXPAND function, you enter the number of rows and columns your array should cover.

Related: [How To Add and Change Cell Borders In Excel](https://activate-lock.techidaily.com/in-2024-3-effective-ways-to-unlock-icloud-account-without-password-on-apple-iphone-14-by-drfone-ios/) 

 The syntax for the function is `EXPAND(array, rows, columns, pad)` where a missing `rows` or `columns` argument means those will not expand. Optionally, you can include the `pad` value for the empty cells.

 To expand the array B2 through F5 to cover 10 rows and 10 columns, you'd use this formula:

=EXPAND(B2:F5,10,10)

![EXPAND function in Excel](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/EXPAND-ExcelArrayFunctions.png) 

 To expand that same array to the same dimensions and include the `pad` "empty," use this formula:

=EXPAND(B2:F5,10,10,"empty")

![EXPAND function with a pad value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2022/08/EXPANDpad-ExcelArrayFunctions.png) 

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
 Although the `pad` argument is optional, you may prefer it over [seeing an error](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/) as shown above.

 These 11 functions give you more control than ever over your arrays in Microsoft Excel. Give them a try and see if they accomplish what you need.

Related: [How to Fix Common Formula Errors in Microsoft Excel](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/)

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


