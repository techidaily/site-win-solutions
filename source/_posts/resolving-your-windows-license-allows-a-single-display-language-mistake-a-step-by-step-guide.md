---
title: "Resolving 'Your Windows License Allows a Single Display Language' Mistake: A Step-by-Step Guide"
date: 2024-08-28T04:59:16.068Z
updated: 2024-08-29T04:59:16.068Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/85dce2e7a62329814e9e3c20d7b6e75c4ef84f34c3e72508a64214321a25f133.jpg
---

## Resolving 'Your Windows License Allows a Single Display Language' Mistake: A Step-by-Step Guide

### Key Takeaways

* Go to Settings > Time and Language > Language and Region. Then, click "Add a Language," select your desired language, and install it.
* After that, copy the Language ID from the Microsoft website and input it into the Registry Editor to switch to your desired language.

 Have you encountered an error stating "Your Windows License Only Supports One Display Language" while attempting to switch your display language on Windows? If so, you're using a single language license, which doesn't allow language changes. Don't worry; we have a workaround. 

##  Install the Language Pack of Your Preferred Language

 To begin, download and install the language pack for your desired language if it's not already downloaded. Right-click on the Start button and open "Settings." Navigate to the "Time and Language" tab, then go to "Language and Region."

![Opening the language and region settings in the Windows Settings app.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-opening-the-language-and-region-settings-in-the-windows-settings-app.jpg) 

 Click on the "Add a Language" button, choose your preferred language from the list, and click "Next." Check the boxes for all optional language features, and click "Install" to allow Windows to install the chosen language.

![Installing a language in Windows 11.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/installing-a-language-in-windows-11.jpg) 

 If you're on Windows 10, [installing a language pack follows a slightly different procedure](https://article-posts.techidaily.com/transform-your-in-game-identity-with-these-free-free-fire-vocal-hacks-for-2024/).

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
##  Switch the Language Using Registry Editor

 After installing the language pack, you can switch to that language [using the Registry Editor](https://facebook-record-videos.techidaily.com/new-economical-mic-options-for-youtube-vloggers-for-2024/). Before you do that, go to the [Microsoft website](https://learn.microsoft.com/en-us/openspecs/windows%5Fprotocols/ms-lcid/a9eac961-e77d-41a6-90a5-ce1a8b0cdb9c), press CTRL+F, and type the name of your desired language to locate it. Once found, copy the last four digits of its Language ID.

![Copying last four digits of a language id from the Microsoft website.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/copying-last-four-digits-of-a-language-id-from-the-microsoft-website.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
 After that, type "Registry Editor" in Windows Search and open the Registry Editor app. If prompted, click "Yes" in the UAC window. Navigate to HKEY\_LOCAL\_MACHINE > SYSTEM > CurrentControlSet > Control > Nls > Language in the Registry Editor. Then, double-click on the "Default" string, and paste the last four digits of the Language ID into the "Value Data" field. Click "OK."

![Pasting the language ID in the Value Data field of a string in Registry Editor.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/pasting-the-language-id-in-the-value-data-field-of-a-string-in-registry-editor.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
 After that, double-click on the "InstallLanguage" string, input the copied digits in the "Value Data" field, and click "OK." Close the Registry Editor and restart your device once.

---

 While this method lets you change the language, it's important to note that you'll need to modify the values again if you wish to switch back. So, we suggest [upgrading your Windows license](https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-apple-iphone-7-plus-online-without-jailbreak-by-drfone-ios/). This way, you'll be able to effortlessly use and switch between languages without the need to tweak the Registry Editor.

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


