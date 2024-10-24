---
title: "Step-by-Step Guide: Adding Textual Descriptions to Your Excel Charts"
date: 2024-08-28T05:02:02.658Z
updated: 2024-08-29T05:02:02.658Z
tags:
  - excel
categories:
  - tech
thumbnail: https://thmb.techidaily.com/05a2bebe19d9c7fab4bc3ec91fa821946b0580297afafdcde864123fe0ad252d.jpg
---

## Step-by-Step Guide: Adding Textual Descriptions to Your Excel Charts

### Quick Links

* [Why Include Captions in Excel Graphs?](https://extra-information.techidaily.com/start-screen-special-free-editing-tools/)
* [Create the Caption Text](https://techidaily.com/video-fixer-software-for-all-corrupt-videos-of-vivo-v29e-by-stellar-video-repair-mobile-video-repair/)
* [Add Captions to an Excel Graph](https://screen-video-capture.techidaily.com/new-2024-approved-harvest-hits-roundup-next-gen-farming-game-picks/)

 Include captions in your Microsoft Excel graphs to provide rich and meaningful labels. The labels can be used to display extra information that is not plotted on the graph. By linking them to cell values, you can make these captions dynamic.

##  Why Include Captions in Excel Graphs?

 When you create a chart in Excel, you are provided with label elements. These include the chart title, data labels, and axis titles. These labels can be very useful for displaying extra information in the chart, especially when you [use cell values for Excel chart labels](https://tech-recovery.techidaily.com/top-gaming-console-picks-for-the-year-2024/).

 The following chart uses a link to a cell value to show the total cells in the chart title.

![Dynamic chart title using cell values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/dynamic-chart-title.png) 

 However, you are not limited to these built-in labels. You can include captions in Excel graphs by adding text boxes.

 This chart was created using the following set of data.

![Sample data for the chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/chart-data-1.png) 

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
##  Create the Caption Text

 Let's add a caption to tell more of the story of this data. We will add a caption to convey the top product and its sales total.

 First, we need to calculate the data we want to display. In cell D2, the following formula is used to return the maximum sales value.

=MAX(B2:B7)

![Calculate the maximum value](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/max-value-1.png) 

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653808&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
 We can then use a formula in cell D3 with the [INDEX and MATCH combination](https://support.office.com/en-gb/article/look-up-values-with-vlookup-index-or-match-68297403-7c3c-4150-9e3c-4d348188976b) to return the name of that product.

=INDEX(A2:A7,MATCH(D2,B2:B7,0))

![INDEX and MATCH to return product name](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/index-match.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
 In cell D4, we can make a creative caption from these calculated values.

=D3&" is the top product with "&D2&" sales."

![Creative text for a caption](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/creative-text.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
<!-- affiliate ads end -->
##  Add Captions to an Excel Graph

 Before we add the caption, we need to resize the plot area of this chart to make some space for it.

 Click on the plot area to select it, then drag the resize handle to make room between the chart title and the chart values.

![Resize the plot area](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/resize-plot-area.png) 

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 We will include the caption by inserting a text box. Click Insert > Text Box and then select the chart to insert it.

![Insert a text box](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/text-box.png) 

 Next, click in the Formula Bar, type "=" and then select cell D4 (the cell containing the caption text).

![Refer to the caption text cell](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/cell-link.png) 

 Press the Enter key.

 The caption text is shown in the text box and can be moved and resized into an appropriate position on the chart.

![Caption on an Excel chart](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/inserted-caption.png) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
 To finish the caption, format it to a light grey so that it is not as impactful as the chart title. Click Home, the list arrow for "Font Color," then select a light grey.

![Formatting with a light grey font colour](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/light-grey.png) 

 This is one example of including captions, but it is up to you to be creative. You can show whatever information you want your chart to convey to go beyond the standard charts.

![Completed Excel chart with caption](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2020/05/finished-chart.png)

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


