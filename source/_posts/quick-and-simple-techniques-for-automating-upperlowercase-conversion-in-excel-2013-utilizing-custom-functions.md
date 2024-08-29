---
title: Quick & Simple Techniques for Automating Upper/Lowercase Conversion in Excel 2013 Utilizing Custom Functions
date: 2024-08-28T05:00:56.120Z
updated: 2024-08-29T05:00:56.120Z
tags:
  - excel
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/00_lead_image_change_case.png
---

## Quick & Simple Techniques for Automating Upper/Lowercase Conversion in Excel 2013 Utilizing Custom Functions

You may find you need to change multiple cells from one case to another in Excel. Maybe you imported data that came in all upper case, or maybe you convert headings on columns to upper case. Changing case is easy using some special functions.

 There are three functions that allow you to change the case of text in multiple columns easily:

* \= Upper(B1) – converts text to all upper case
* \= Lower(B1) – converts text to all lower case
* \= Proper(B1) – converts text to proper case, or title case (the first letter of each word is capitalized)

 For our example, we will change two columns of first and last names in a sample address list. First, we want to insert a new column after the Last name column. To do this, highlight the column after which you want to insert the blank column by clicking on the lettered header, right-click on the header, and select Insert from the popup menu.

![01_inserting_column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/01_inserting_column.png) 

 The new column is formatted the same way as the original column. In our example, we entered the title of the column in the gray highlighted cell at the top of the column. We will be deleting the original column once we’ve converted the case.

![02_entering_title](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/02_entering_title.png) 

 In the first cell of the new column, enter the desired case function, with the cell reference in the parentheses, for the text you want to convert. In our example, we want to convert each name to title case, so we entered the Proper() function in the first cell in the column (below the heading row) with A2 as the cell reference.

 NOTE: Remember to preface your function with the equals sign.

![03_entering_formula](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/03_entering_formula.png) 

 Now, we need to propagate the function to the rest of the cells in the column. To do this, select the cell containing the case function and click Copy in the Clipboard section of the Home tab or press Ctrl + C.

![04_clicking_copy](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/04_clicking_copy.png) 

 Highlight the remaining cells in the column and click Paste or press Ctrl + V.

![05_clicking_paste](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/05_clicking_paste.png) 

 TIP: You can also quickly copy the contents of a cell into the remaining cells in the column by double-clicking the box on the lower, right corner of the cell.

![05a_double_click_box_to_paste](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/05a_double_click_box_to_paste.png) 

 Each of the cells in the new column look like they contain the names in a different case. However, each cell still contains the Proper() function referring to another cell. Because we are planning to delete the original column, we need to replace the function with the actual name to which it evaluates. To do this, highlight all the cells in the column containing the function and copy them.

![06_formula_still_in_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/06_formula_still_in_cells.png) 

 To paste the values back into the same cells, click the down arrow on the Paste button in the Clipboard section of the Home tab. Then, click Values in the Paste Values section.

 NOTE: This is the same procedure we discussed in a previous article about [converting a numerical formula to a static value](https://article-posts.techidaily.com/decoding-the-art-of-enhanced-perception-for-2024/).

![07_pasting_values](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/07_pasting_values.png) 

 Now, all the cells in the column should contain text, not functions.

![08_names_in_cells](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/08_names_in_cells.png) 

 To delete the original column, select the entire column by clicking the lettered header, right-click on the header, and select Delete from the popup menu.

![09_deleting_original_column](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/09_deleting_original_column.png) 

 To convert the first names to title case, we followed the same procedure.

![10_both_columns_fixed](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2013/05/10_both_columns_fixed.png) 

 It’s that easy to tidy up your text. These case functions will also work if the case of the text is jumbled (e.g., bUFfEt).

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://youtube-tips.techidaily.com/024-approved-expert-strategies-on-calculating-your-youtube-audience-impact-and-revenue/"><u>[New] 2024 Approved  Expert Strategies on Calculating Your YouTube Audience Impact and Revenue</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-eliminating-oculus-sickness-key-tactics/"><u>[New] In 2024, Eliminating Oculus Sickness  Key Tactics</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-trendsetters-guide-selecting-best-tools-to-craft-instagram-videos/"><u>[Updated] 2024 Approved  Trendsetters’ Guide  Selecting Best Tools to Craft Instagram Videos</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-youtube-and-instagram-syncing-up-your-media/"><u>[Updated] YouTube and Instagram  Syncing Up Your Media</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-evaluating-macs-leading-snipping-tools-compilation/"><u>2024 Approved  Evaluating Mac's Leading Snipping Tools Compilation</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-make-a-mark-with-your-first-cool-mac-video-post-on-youtube/"><u>2024 Approved  Make a Mark with Your First Cool Mac Video Post on YouTube</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-the-ultimate-10-step-plan-thriving-in-social-media-management/"><u>2024 Approved  The Ultimate 10-Step Plan  Thriving in Social Media Management</u></a></li>
<li><a href="https://screen-recording.techidaily.com/choosing-between-obs-studio-and-bandicam-for-screen-capture/"><u>Choosing Between OBS Studio and Bandicam for Screen Capture</u></a></li>
<li><a href="https://win-solutions.techidaily.com/complete-guide-solving-warzones-dev-error-5573-across-pc-gaming-platforms-and-consoles/"><u>Complete Guide: Solving Warzone's Dev Error 5573 Across PC Gaming Platforms and Consoles</u></a></li>
<li><a href="https://win-solutions.techidaily.com/conquer-the-game-board-essential-tips-for-roller-champions-crossplay-2024-edition/"><u>Conquer the Game Board: Essential Tips for Roller Champions Crossplay - 2024 Edition</u></a></li>
<li><a href="https://extra-resources.techidaily.com/craft-stunning-iphone-snaps-heed-these-10-guidelines/"><u>Craft Stunning iPhone Snaps - Heed These 10 Guidelines</u></a></li>
<li><a href="https://win-solutions.techidaily.com/crash-free-gaming-experience-overcoming-loops-errors-in-games-on-modern-pc-operating-systems/"><u>Crash-Free Gaming Experience: Overcoming Loops Errors in Games on Modern PC Operating Systems</u></a></li>
<li><a href="https://win-solutions.techidaily.com/dayzoned-crash-woes-heres-how-to-fix-them/"><u>DayZoned Crash Woes? Here's How to Fix Them</u></a></li>
<li><a href="https://win-solutions.techidaily.com/easy-steps-to-eliminate-directx-glitches-for-an-uninterrupted-fifa-19-gaming-experience/"><u>Easy Steps to Eliminate DirectX Glitches for an Uninterrupted FIFA 19 Gaming Experience</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-solutions-to-fix-crashing-episodes-while-playing-fallout-4-on-personal-computers/"><u>Effective Solutions to Fix Crashing Episodes While Playing Fallout 4 on Personal Computers</u></a></li>
<li><a href="https://win-solutions.techidaily.com/enhancing-pc-experience-handling-and-fixing-ghostwire-tokyos-recurring-game-instability-issues/"><u>Enhancing PC Experience - Handling and Fixing Ghostwire: Tokyo's Recurring Game Instability Issues</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-advice-on-reducing-latency-issues-for-a-smoother-cyberpunk-2077-gameplay/"><u>Expert Advice on Reducing Latency Issues for a Smoother Cyberpunk 2077 Gameplay</u></a></li>
<li><a href="https://win-solutions.techidaily.com/exploring-bugs-and-glitches-preventing-wolcen-game-from-releasing-successfully/"><u>Exploring Bugs and Glitches Preventing Wolcen Game From Releasing Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/game-setup-troubles-heres-how-origin-fixes-common-playing-hurdles/"><u>Game Setup Troubles? Here's How Origin Fixes Common Playing Hurdles</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-successfully-run-destiny-2-after-fixes-for-initial-pc-launch-glitches/"><u>How to Successfully Run Destiny 2 After Fixes for Initial PC Launch Glitches</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-samsung-galaxy-m14-5g-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Samsung Galaxy M14 5G to Roku | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-free-mov-video-combiner-software/"><u>In 2024, Best Free MOV Video Combiner Software</u></a></li>
<li><a href="https://games-able.techidaily.com/integrating-safety-into-everyday-child-steam-games/"><u>Integrating Safety Into Everyday Child Steam Games</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-your-ps4s-video-capture-expert-advice-on-camera-placement/"><u>Mastering Your PS4's Video Capture: Expert Advice on Camera Placement</u></a></li>
<li><a href="https://win-solutions.techidaily.com/minecraft-troubles-top-tactics-for-fixing-launch-difficulties-successfully/"><u>Minecraft Troubles? Top Tactics for Fixing Launch Difficulties Successfully</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-in-2024-avs-video-editor-a-comprehensive-analysis/"><u>New In 2024, AVS Video Editor A Comprehensive Analysis</u></a></li>
<li><a href="https://win-solutions.techidaily.com/no-more-fortnite-loading-errors-easy-methods-for-a-smooth-startup/"><u>No More Fortnite Loading Errors: Easy Methods for a Smooth Startup</u></a></li>
<li><a href="https://win-solutions.techidaily.com/optimize-your-gameplay-troubleshooting-lag-in-dragons-dogma/"><u>Optimize Your Gameplay: Troubleshooting Lag in Dragon's Dogma</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcome-discord-delays-comprehensive-fixes-and-tips/"><u>Overcome Discord Delays : Comprehensive Fixes and Tips</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcome-the-steam-damaged-disc-problem-with-easy-fixes-you-can-do-yourself/"><u>Overcome the Steam Damaged Disc Problem with Easy Fixes You Can Do Yourself</u></a></li>
<li><a href="https://win-solutions.techidaily.com/overcoming-common-issues-fixing-the-persistent-loading-screen-in-dota-2/"><u>Overcoming Common Issues: Fixing the Persistent Loading Screen in Dota 2</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723006832677-overwatch-crashes-with-black-screen-here-are-proven-solutions/"><u>Overwatch Crashes with Black Screen? Here Are Proven Solutions!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resident-evil-village-pc-troubleshooting-steps-for-your-black-screen-dilemma/"><u>Resident Evil Village PC - Troubleshooting Steps for Your Black Screen Dilemma</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722999463495-smooth-gaming-experience-achieved-cyberpunk-2077s-lag-and-stuttering-solved/"><u>Smooth Gaming Experience Achieved: Cyberpunk 2077'S Lag and Stuttering Solved</u></a></li>
<li><a href="https://windows11.techidaily.com/step-by-step-guide-to-manipulating-fax-cover-pages-on-win11/"><u>Step-by-Step Guide to Manipulating Fax Cover Pages on Win11</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-selection-premier-web-development-course-picks/"><u>The Ultimate Selection: Premier Web Development Course Picks</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steam-cloud-inconsistency-and-error-messages/"><u>Troubleshooting Steam Cloud Inconsistency and Error Messages</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-the-black-screen-error-in-rainbow-six-siege-for-your-pc-expert-tips/"><u>Troubleshooting the Black Screen Error in Rainbow Six Siege for Your PC – Expert Tips</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-tips-for-resolving-minecrafts-loading-hang-ups/"><u>Troubleshooting Tips for Resolving Minecraft's Loading Hang-Ups</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-your-pc-solutions-for-fifa-22-stability-issues/"><u>Troubleshooting Your PC - Solutions for FIFA 22 Stability Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033095&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced-3YR.png" border="0"></a>
<!-- affiliate ads end -->