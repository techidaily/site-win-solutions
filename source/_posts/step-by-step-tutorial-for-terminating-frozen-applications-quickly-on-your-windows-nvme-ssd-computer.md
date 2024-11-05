---
title: Step-by-Step Tutorial for Terminating Frozen Applications Quickly on Your Windows Nvme SSD Computer
date: 2024-10-31T04:04:27.533Z
updated: 2024-11-05T01:36:24.243Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/52781818963_ddd89fcf7e_o-4.jpg
---

## Step-by-Step Tutorial for Terminating Frozen Applications Quickly on Your Windows Nvme SSD Computer

### Quick Links

* [Try a Keyboard Shortcut](https://instagram-clips.techidaily.com/the-key-to-viral-instagram-posts/)
* [Force Quit Using Task Manager](https://android-unlock.techidaily.com/in-2024-forgot-pattern-lock-heres-how-you-can-unlock-samsung-galaxy-s24-pattern-lock-screen-by-drfone-android/)
* [Force Quit an App Using Command Prompt](https://fox-links.techidaily.com/expertly-crafted-images-with-lut-techniques-in-photoshop-cs6-for-2024/)

### Key Takeaways

* Try pressing Alt+F4 to force-close an app.
* Open Task Manager, select the frozen app, and click "End Task" to force quit it.
* Run "tasklist" in Command Prompt find tasks, and then use "taskkill /im <program>.exe" to force quit the app.

 It’s not uncommon for an application to stop responding on Windows 10\. When it happens, you can force the app to shut down, effectively unfreezing said application. Here’s how to force quit an app on Windows 10.

##  Try a Keyboard Shortcut

 It's frustrating when an app you're using suddenly freezes. We’ve all done it—exasperatingly clicking the “X” button at least 20 times to close the frozen program. There’s a better way.

 With the frozen application in focus, press Alt+F4 on your keyboard to close it. If the Windows desktop is in focus instead, you'll see a "Shut Down Windows" prompt instead.

 This won't always work—some frozen applications just won't respond.

![Press Alt+F4 to force close an app. If you press Alt+F4 while the desktop is selected, you'll see a 'Shut Down Windows' window appear.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/0-altf4-restart-okay-1.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130870/7443" target="_top" id="2130870">
  <img src="//a.impactradius-go.com/display-ad/7443-2130870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Force Quit Using Task Manager

 As the name implies, [Task Manager](https://some-skills.techidaily.com/new-unveiling-the-secret-sauce-for-massive-tiktok-content-grabs/) is a tool that shows which apps are currently running (as well as other information like resource usage and process stats) and allows you to manage them appropriately.

 To [open Task Manager](https://youtube-blog.techidaily.com/24-top-15-gaming-capture-utilities/), you can press Ctrl+Shift+Esc on your keyboard or right-click the Windows task bar and select “Task Manager” from the menu.

![Right-click the taskbar and select 'Task Manager.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-open-task-manager.png) 

 With Task Manager open, select the task you want to force quit and then select “End Task.”

 If you don't see the name of the app in the list here, click "More Details" and find it in the list on the Processes tab.

![Select the app you want to force quit, then click 'End Task.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/2-select-the-app-and-hit-end-task.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049369/7443" target="_top" id="2049369">
  <img src="//a.impactradius-go.com/display-ad/7443-2049369" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049369/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The frozen program will now close.

##  Force Quit an App Using Command Prompt

 You can find and force quit tasks from the Command Prompt. [Open Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) by typing **cmd** in the Windows search bar, and then selecting the “Command Prompt” app from the search results.

![Search 'cmd' in the Start Menu search, then launch Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/3-launch-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 In Command Prompt, type **tasklist** and press "Enter." Once executed, Command Prompt will display a list of currently running programs, services, and tasks.

![The tasklist command running in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/4-tasklist.png) 

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 The list can admittedly be a bit overwhelming, so just remember to append .exe to the end of the program name. Once you’re ready to force quit the program, execute this command:

taskkill /im <program>.exe

 So, if I wanted to force quit Notepad, I’d run this command:

taskkill /im notepad.exe

![Ending the Notepad process with the taskkill command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/5-kill-notepad.png) 

 A success message will be returned, letting you know you’ve successfully force quit the problematic application.

---

 Of course, you can always reboot or shut down your PC to close an app that's really stuck.

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
<li><a href="https://youtube-tips.techidaily.com/ed-pocket-playlist-portraits-actors-and-audio-art-for-2024/"><u>[Updated] Pocket Playlist Portraits Actors & Audio Art for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-unveiling-the-secret-behind-successful-youtube-thumbnails-for-2024/"><u>[Updated] Unveiling The Secret Behind Successful YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-deep-dive-into-acid-pro-functionality-and-alternatives/"><u>2024 Approved Deep Dive Into ACID Pro Functionality & Alternatives</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/6-unparalleled-mac-apps-for-video-grabbing-for-2024/"><u>6 Unparalleled Mac Apps for Video Grabbing for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/days-gone-not-working-a-complete-guide-to-fixing-pc-installation-woes/"><u>Days Gone Not Working: A Complete Guide to Fixing PC Installation Woes</u></a></li>
<li><a href="https://win-solutions.techidaily.com/error-no-more-mastering-the-art-of-solving-tfla0002-final-exam-glitches/"><u>Error No More: Mastering the Art of Solving 'TFLA0002' Final Exam Glitches</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-fix-and-improve-the-hazy-visual-effects-in-outriders-game/"><u>How to Fix and Improve the Hazy Visual Effects in Outriders Game</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-get-cod-black-ops-cold-war-running-smoothly-on-your-computer/"><u>How to Get Cod: Black Ops Cold War Running Smoothly on Your Computer</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-vivo-y27-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Vivo Y27 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://win-solutions.techidaily.com/pc-gamers-conquer-stray-crashes-with-these-6-effective-remedies/"><u>PC Gamers, Conquer Stray Crashes with These 6 Effective Remedies</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-constant-terraria-crashes-proven-techniques-and-tips/"><u>Resolving Constant Terraria Crashes : Proven Techniques & Tips</u></a></li>
<li><a href="https://screen-capture.techidaily.com/screen-free-serenity-top-10-indoor-games-for-non-networked-play-android/"><u>Screen-Free Serenity Top 10 Indoor Games for Non-Networked Play (Android)</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/2593902-9781785259883-su-horoscopo-chino-liebre/"><u>Su horóscopo chino. Liebre | Free Book</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/top-face-swap-apps-iphone-and-android-edition/"><u>Top Face Swap Apps IPhone and Android Edition</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-and-solving-discord-js-errors-quickly/"><u>Troubleshooting and Solving Discord JS Errors Quickly</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-steps-for-resolving-new-world-connection-issues/"><u>Troubleshooting Steps for Resolving New World Connection Issues</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/updated-the-art-of-harmonizing-moving-images-and-sounds-a-2023-approach/"><u>Updated The Art of Harmonizing Moving Images and Sounds (A 2023 Approach)</u></a></li>
</ul></div>

