---
title: Easy Average Computation Techniques Using Microsoft Excel Tutorials
date: 2024-08-28T05:00:31.341Z
updated: 2024-08-29T05:00:31.341Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2023/08/microsoft-excel-logo-1.jpg
---

## Easy Average Computation Techniques Using Microsoft Excel Tutorials

### Quick Links

* [How Many Average Functions Are There in Excel?](https://instagram-video-files.techidaily.com/updated-in-2024-rapid-route-learning-the-ins-and-outs-of-insta-talks/)
* [How to Use AVERAGE in Excel](https://data-safeguard.techidaily.com/photoshop-cs8-installation-tutorial-for-windows-users-start-editing/)
* [How to Use AVERAGEA in Excel](https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-huawei-p60-drfone-by-drfone-virtual-android/)
* [How to Use AVERAGEIF in Excel](https://program-issues.techidaily.com/solving-the-mystery-a-step-by-step-guide-to-resolve-dev-error-6034-on-pc-and-xbox/)
* [How to Use AVERAGEIFS in Excel](https://extra-hints.techidaily.com/slowly-quieting-tracks-with-fl-studio/)

 Excel has hundreds of functions that can help you to quickly and accurately perform calculations, among which are the AVERAGE functions. You might want to calculate the average sales figures, get the average of a group of data that contains numbers and text, or work out the average of all student scores over a certain number.

##  How Many Average Functions Are There in Excel?

 There are four AVERAGE functions and each has different uses:

* **AVERAGE**: This produces the arithmetic mean (the sum of all numbers divided by the number of values) of a set of data, ignoring anything that isn't a number.
* **AVERAGEA**: This returns the mean of a set of numbers, text, and logical arguments.
* **AVERAGEIF**: This calculates the arithmetic mean of a set of numerical data that fulfill a single criterion.
* **AVERAGEIFS**: This tells you the arithmetic mean of a set of numerical data that fulfill several criteria.

 Let's explore these in more detail.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Use AVERAGE in Excel

 To calculate the average in Excel, use the following syntax:

=AVERAGE(A,B)

 where A is the first number, cell reference, or range, and B is up to a maximum of 255 additional numbers, cell references, or ranges to include in the average calculation.

 In this example, we have a set of seven students and want to calculate their average exam score.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores will be calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 As you can see, Student C scored 0 and Student F has yet to take the exam. As a result, we want Excel to work out the scores of those who have taken the exam (all students except for Student F).

 To do this, we would type the following formula into cell D2:

=AVERAGE(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is an 'average' cell, where their average scores has been calculated using the AVERAGE function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/average-calculated-1.png) 

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
 The AVERAGE function includes 0 within its calculations, but ignores all empty cells, text, and logical values (TRUE or FALSE). So, we can be confident that this calculation will include Student C's score, but ignore Student F's score.

 If any of the values being used in the AVERAGE calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would not work.

 To save time, you can instead calculate the average through a few simple clicks. First, select your data to average, click the "Home" tab on the ribbon, and in the "Editing" group, click on the drop-down arrow next to the sigma (Σ) symbol. From there, click "Average". The result will appear at the end of your data.

##  How to Use AVERAGEA in Excel

 AVERAGEA works in a very similar way to AVERAGE, but includes more than just numbers within the calculation. Here's the syntax for this function:

=AVERAGE(A,B)

 where A is the first value (including numbers, logical values such as TRUE or FALSE, and text), and B is up to a maximum of 255 additional values to include in the average calculation.

 The AVERAGEA function is useful if you have a mixed set of data containing numbers, logical values, and text, and you want to include them all within your calculation.

 Taking the same set of data that we used in the example above, we now want to work out the average using AVERAGEA.

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and a space where their average scores will be calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-uncalculated.png) 

 In cell D5, we would type the following formula:

=AVERAGEA(B2:B8)

![Excel sheet showing a table with two columns: column A contains student names and column B contains their exam scores. Next to this table is the average of the scores, calculated using AVERAGE, and their average scores, calculated using the AVERAGEA function.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averagea-calculated.png) 

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
 Unlike the AVERAGE function, which ignores logical values, the AVERAGEA calculation includes FALSE within the calculation as 0\. If this were instead TRUE, this would be counted as 1\. As a result, in our example, Student C's score of 0 is included, and Student F is also calculated as having scored 0\. This is why the result is lower for this calculation than the previous one.

 AVERAGEA counts any other text as 0 (for example, if you type FOUR, this is still represented as 0, and not 4), and ignores empty cells.

 As with AVERAGE, if any of the values being used in the AVERAGEA calculation were to contain [one of Excel's formula errors](https://extra-lessons.techidaily.com/step-into-premium-sound-quality-garageband-edition/), the calculation would return an error.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
##  How to Use AVERAGEIF in Excel

 AVERAGEIF effectively performs two calculations in one go, first identifying data that meet a certain criterion before then finding the average of these data. AVERAGEIF uses the following syntax:

=AVERAGEIF(A,B,C)

 where A is the range of values or cells to include in the average, B is the criterion, and C (optional) is the actual set of cells to average. Confusing? Let's look at this example.

 We want to work out two things from this table. First, we want to find the average score of all students who scored more than 10 in the exam, and second, we want to work out the average scores of all students over 12 years of age.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table are cells where the AVERAGEIF functions will be tested.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-uncalculated.png) 

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1494880/17238" target="_top" id="1494880"><img src="//a.impactradius-go.com/display-ad/17238-1494880" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1494880/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 To work out the average score of all students who scored more than 10, we would use the following formula:

=AVERAGEIF(B2:B8,">10")

 Notice two things in this formula. First, the criteria must always be enclosed in double quotes. Second, we've only included two arguments within the parentheses, as there's no need to refer to any other data elsewhere within our calculation.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, the first AVERAGEIF calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-1.png) 

 This has correctly picked up the scores of Students A, B, D, and E, as these are all more than 10.

 To work out the average scores of all students over 12 years of age, we would use the following formula:

=AVERAGEIF(C2:C8,">12",B2:B8)

 Notice the difference between the two formulas. Where the previous calculation contained two arguments, this one contains three, as we are assessing two sets of data.

 The "C2:C8" part of the formula tells Excel to look in that range (the students' ages) for the criteria, the ">12" part tells Excel to identify any values over 12 in the C2:C8 range (the students' ages), and "B2:B8" (the students' scores) is the part being averaged.

![Excel sheet showing a table with three columns: column A contains student names, column B contains their exam scores, and column C contains their ages. Next to this table, both AVERAGEIF calculations have been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageif-calculated-2-1.png) 

 This has correctly picked up the scores of Students A, B, D, and E, as they are all over 12 years of age. The calculation also ignores logical values, which is why it hasn't considered Student F, even though they are over 12 years old.

 The criteria used in AVERAGEIF can use one of Excel's six logical operators—these are > (greater than), < (less than), = (equal to), <= (less than or equal to), >= (greater than or equal to), or <> (not equal to)—and wildcards (\* and ?). If you want to include an actual question mark or asterisk, add a tilde (\~) before the character.

##  How to Use AVERAGEIFS in Excel

 The AVERAGEIFs function allows you to include several criteria to assess before calculating the average. It works using the following syntax:

=AVERAGEIFS(A,B,C)

 where A identifies the cells to average, B is the cells used to identify the criteria, and C is the criteria. There can be up to 127 criteria, so multiple pairs of cells (B) and criteria (C) can be used.

 Take this example, where we want to work out the exam scores of students in Green House over the age of 10.

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where AVERAGEIFS will be performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-uncalculated.png) 

 To do this, we would use the following formula:

=AVERAGEIFS(B2:B8,C2:C8,"Green",D2:D8,">10")

 "B2:B8" contains the data to be averaged (the students' scores), "C2:C8" is the first range to be tested with the criterion of "Green" (the student's house), and "D2:D18" is the second range to be tested with the criterion of ">10" (the student's age).

![Excel sheet showing a table with four columns: column A contains student names, column B contains their exam scores, column C contains their house, and column D contains their age. Next to this table is a cell where an AVERAGEIFS calculation has been performed.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/averageifs-calculated-1.png) 

 This has correctly averaged the scores of Students D and G, as they are both in Green House and are over 10 years old.

 Other things to note about AVERAGEIFS:

* TRUE is counted as 1, and FALSE is counted as 0.
* In the criteria, you can use a question mark (?) as a wildcard to match any single character, or an asterisk (\*) as a wildcard to match any sequence of characters. Use a tilde (\~) before the character if you're looking to identify an actual question mark or asterisk.

---

 As well as using AVERAGEIF and AVERAGEIFS, you can [sort and filter data in Excel](https://facebook-video-share.techidaily.com/free-audio-treasures-to-amplify-youtube-in-2024/) to only show certain figures within your tables.

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
<li><a href="https://extra-support.techidaily.com/new-iphone-lens-mastery-unleashing-creativity/"><u>[New] IPhone Lens Mastery - Unleashing Creativity</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-crafting-yt-masterpieces-for-igtv-showcase/"><u>[Updated] In 2024, Crafting YT Masterpieces for IGTV Showcase</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-personalized-and-accessible-video-conclusions-downloads/"><u>[Updated] Personalized & Accessible Video Conclusions Downloads</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-understanding-and-earning-through-youtubes-cp2024-plan/"><u>[Updated] Understanding and Earning Through YouTube's CP2024 Plan</u></a></li>
<li><a href="https://win-solutions.techidaily.com/baldurs-gate-3-and-cpu-usage-6-key-strategies-to-reduce-high-resource-consumption/"><u>Baldur's Gate 3 and CPU Usage: 6 Key Strategies to Reduce High Resource Consumption</u></a></li>
<li><a href="https://win-solutions.techidaily.com/banish-your-pcs-ghosting-issues-a-step-by-step-fix-for-horizon-forbidden-west/"><u>Banish Your PC's Ghosting Issues – A Step-by-Step Fix for Horizon Forbidden West</u></a></li>
<li><a href="https://win-solutions.techidaily.com/dealing-with-the-dark-beginning-solutions-for-elden-ring-launch-glitches/"><u>Dealing With the Dark Beginning: Solutions for 'Elden Ring' Launch Glitches</u></a></li>
<li><a href="https://facebook.techidaily.com/deleting-all-your-fb-alerts-a-step-by-step-guide/"><u>Deleting All Your FB Alerts: A Step-by-Step Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/dying-light-gaming-troubles-heres-how-to-tackle-the-freezing-and-lag-problems-efficiently/"><u>Dying Light Gaming Troubles? Here's How to Tackle the Freezing & Lag Problems Efficiently</u></a></li>
<li><a href="https://win-solutions.techidaily.com/effective-ways-to-overcome-the-sims-4-error-code-video-card-troubleshooting-steps/"><u>Effective Ways to Overcome The Sims 4 Error Code: Video Card Troubleshooting Steps</u></a></li>
<li><a href="https://win-solutions.techidaily.com/essential-steps-to-resolve-elite-dangerous-pc-malfunctions-for-smooth-gaming/"><u>Essential Steps to Resolve Elite: Dangerous PC Malfunctions for Smooth Gaming</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722996084966-experiencing-league-of-legends-connection-errors-learn-the-quick-fixes/"><u>Experiencing League of Legends Connection Errors? Learn the Quick Fixes</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-solutions-for-when-modern-warfare-2-fails-to-boot-up/"><u>Expert Solutions for When Modern Warfare 2 Fails to Boot Up</u></a></li>
<li><a href="https://win-able.techidaily.com/expert-solutions-to-overcome-crashing-problems-with-lego-star-wars-the-skywalker-saga-on-pc/"><u>Expert Solutions to Overcome Crashing Problems with Lego Star Wars: The Skywalker Saga on PC</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fix-and-play-baldurs-gate-3-ready-for-your-fantasy-adventure-awaits/"><u>Fix and Play: Baldur's Gate 3 Ready for Your Fantasy Adventure Awaits!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-persistent-loading-issues-in-red-dead-redemption-2-solutions-and-tips/"><u>Fixing Persistent Loading Issues in Red Dead Redemption 2 - Solutions & Tips</u></a></li>
<li><a href="https://win-solutions.techidaily.com/grand-theft-auto-v-graphics-d3d-setup-failure-errgfxd3dinit-a-comprehensive-fix-guide/"><u>Grand Theft Auto V Graphics D3D Setup Failure ERR_GFX_D3D_INIT: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-eliminate-stuttering-and-smooth-out-gameplay-for-assassins-creed-valhalla-on-pc/"><u>How to Eliminate Stuttering and Smooth Out Gameplay for Assassin’s Creed Valhalla on PC</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-get-past-the-block-steps-to-launch-saints-row-on-your-desktop-smoothly/"><u>How to Get Past the Block: Steps to Launch Saints Row on Your Desktop Smoothly</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-note-30-vip-racing-edition-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Note 30 VIP Racing Edition Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-vivo-v27-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Vivo V27? | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723002446238-jurassic-world-evolution-master-the-tips-and-tricks-to-stop-your-game-from-crashing/"><u>Jurassic World Evolution: Master the Tips & Tricks to Stop Your Game From Crashing</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-high-frame-rates-in-escape-from-tarkov-a-professionals-insightful-guide/"><u>Mastering High Frame Rates in Escape From Tarkov: A Professional's Insightful Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/no-more-glitches-how-to-ensure-a-smooth-v-rising-experience-on-windows-1011/"><u>No More Glitches: How to Ensure a Smooth V Rising Experience on Windows 10/11</u></a></li>
<li><a href="https://win-solutions.techidaily.com/pc-gaming-optimized-overcoming-the-dual-decline-in-frames-per-second/"><u>PC Gaming Optimized: Overcoming the Dual Decline in Frames Per Second</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolved-top-8-techniques-to-prevent-multiversus-from-crashing/"><u>Resolved: Top 8 Techniques to Prevent MultiVersus From Crashing</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-oxygen-not-included-game-crash-problems-a-comprehensive-guide/"><u>Resolving 'Oxygen Not Included' Game Crash Problems: A Comprehensive Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-frame-drops-and-lags-in-age-of-empires-iv-a-comprehensive-guide/"><u>Resolving Frame Drops and Lags in Age of Empires IV: A Comprehensive Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/say-goodbye-to-sea-of-thieves-game-crashes-for-good-with-these-proven-fixes/"><u>Say Goodbye to Sea of Thieves Game Crashes for Good with These Proven Fixes</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/setting-up-snapchat-on-apple-computers-step-by-step/"><u>Setting Up Snapchat on Apple Computers Step by Step</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solution-guide-for-when-crusader-kings-ii-launches-incorrectly-or-fails-to-open/"><u>Solution Guide for When Crusader Kings II Launches Incorrectly or Fails to Open</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solve-your-pcs-v-rising-hiccups-fixing-continuous-crashes/"><u>Solve Your PC's V-Rising Hiccups: Fixing Continuous Crashes</u></a></li>
<li><a href="https://win-solutions.techidaily.com/step-by-step-solutions-to-fix-slow-response-times-in-naraka-point-aeon-online-gameplay/"><u>Step-by-Step Solutions to Fix Slow Response Times in Naraka Point Aeon Online Gameplay</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshoot-and-fix-persistent-game-crashes-in-frontier-for-pc-players/"><u>Troubleshoot & Fix Persistent Game Crashes in Frontier for PC Players</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/ultimate-guide-to-youtube-thumbnail-creation-on-mac/"><u>Ultimate Guide to YouTube Thumbnail Creation on Mac</u></a></li>
<li><a href="https://win-solutions.techidaily.com/ultimate-guide-resolving-the-infamous-tfla0002-finals-issue/"><u>Ultimate Guide: Resolving the Infamous TFLA0002 Finals Issue</u></a></li>
<li><a href="https://win-solutions.techidaily.com/unstuck-at-last-chance-tavern-overcoming-sea-of-thieves-loading-hurdles/"><u>Unstuck at Last Chance Tavern: Overcoming Sea of Thieves' Loading Hurdles</u></a></li>
<li><a href="https://win-solutions.techidaily.com/valheim-launch-glitch-solutions-optimized-gameplay-starts-users/"><u>Valheim Launch Glitch Solutions: Optimized Gameplay Starts Users</u></a></li>
<li><a href="https://win-solutions.techidaily.com/war-thunder-continues-to-crash-essential-troubleshooting-steps/"><u>War Thunder Continues to Crash : Essential Troubleshooting Steps</u></a></li>
<li><a href="https://win-solutions.techidaily.com/why-is-my-ubisoft-connect-not-working-solutions-to-common-glitches-in-202cu/"><u>Why Is My Ubisoft Connect Not Working? Solutions to Common Glitches in 202Cu</u></a></li>
</ul></div>
