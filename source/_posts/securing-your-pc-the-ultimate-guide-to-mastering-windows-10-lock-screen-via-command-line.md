---
title: "Securing Your PC: The Ultimate Guide to Mastering Windows 10 Lock Screen via Command Line"
date: 2024-11-02T01:22:02.754Z
updated: 2024-11-05T04:03:50.040Z
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/e773ad143d0e6a181e98946175694e64ba11aabb2b269c227b4f6fa4a346892f.jpg
---

## Securing Your PC: The Ultimate Guide to Mastering Windows 10 Lock Screen via Command Line

### Quick Links

* [Lock Your Windows 10 PC Using Command Prompt](https://vp-tips.techidaily.com/new-audiovisual-adaptability-in-free-fire-for-2024/)
* [Set the Lock Screen Timeout Setting Using Command Prompt](https://eaxpv-info.techidaily.com/new-finding-a-different-way-to-naming-your-channel-with-filmora-for-2024/)

### Key Takeaways

* To lock your Windows PC using Command Prompt, run "**Rundll32.exe user32.dll,LockWorkStation"** in the Command Prompt
* To set the lock screen timeout, run "**powercfg.exe /SETACVALUEINDEX SCHEME\_CURRENT SUB\_VIDEO VIDEOCONLOCK <time>"** in Command Prompt as Admin
* Activate the lock screen timeout setting by running "**powercfg.exe /SETACTIVE SCHEME\_CURRENT"** after you set the timeout.

 One of the first rules of cyber security is to always lock your PC before stepping away. While it may not be the quickest way to lock your Windows 10 PC, you can do it using the Command Prompt.

##  Lock Your Windows 10 PC Using Command Prompt

 First, [open the Command Prompt](https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-oppo-a78-frp-by-drfone-android/) on your PC by opening the Start menu, typing “cmd” in the Windows Search bar, and then selecting “Command Prompt” from the search results.

![Click the Start button, search for 'cmd,' then open 'Command Prompt.'](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/1-launch-cmd.png) 

 Command Prompt will now open. Here, run this command to lock your Windows 10 PC.

Rundll32.exe user32.dll,LockWorkStation

![Locking your PC with Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/2-lock-pc-command-prompt.png) 

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918703/19272" target="_top" id="1918703">
  <img src="//a.impactradius-go.com/display-ad/19272-1918703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918703/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Once executed, your PC will be locked. You'll have to sign back in with your PIN, password, or whatever sign-in method you usually use.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Set the Lock Screen Timeout Setting Using Command Prompt

 Once you’ve locked your PC, the lock screen will generally be displayed for a certain amount of time before it time outs. You can set the amount of time that needs to pass before timing out using the Command Prompt.

 To do this, you’ll need to [open Command Prompt as an admin](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/). Do so by typing “cmd” in the Windows Search bar and then right-clicking “Command Prompt” from the results. Next, select “Run As Administrator” from the menu that appears.

![Launching Command Prompt as admin.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/3-launch-cmd.png) 

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141687/17094" target="_top" id="2141687">
  <img src="//a.impactradius-go.com/display-ad/17094-2141687" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141687/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 With Command Prompt open, run this command.

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK <time>

 Replace `<time>` with your desired amount of time in seconds. That means if you want to time out the lock screen after two minutes, you’d enter this command:

powercfg.exe /SETACVALUEINDEX SCHEME_CURRENT SUB_VIDEO VIDEOCONLOCK 120

![Change the timeout to 120.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/4-changing-timeout-to-120.png) 

 This command sets the lock screen timeout setting for your PC if it’s plugged in to a power source. To set the lock screen timeout setting for your PC if it’s running on battery, change`/SETACVALUEINDEX` to`/SETDCVALUEINDEX` and run the command as normal.

 Next, run this command:

powercfg.exe /SETACTIVE SCHEME_CURRENT

![Apply the setting to the currently active scheme.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/01/5-set-active.png) 

<!-- affiliate ads begin -->
<a href="https://malaysia-healthcare-travel-council.pxf.io/c/5597632/1557747/17382" target="_top" id="1557747">
  <img src="//a.impactradius-go.com/display-ad/17382-1557747" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://malaysia-healthcare-travel-council.pxf.io/i/5597632/1557747/17382" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Now your [lock screen](https://driver-download.techidaily.com/1722977751917-synaptics-drivers-download-and-update-for-windows-easily/) will timeout after the set amount of time. Give it a try!

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
<li><a href="https://win-solutions.techidaily.com/avoid-crashes-and-fix-bugs-the-ultimate-guide-to-overcoming-pc-issues-in-fortnite/"><u>Avoid Crashes and Fix Bugs: The Ultimate Guide to Overcoming PC Issues in Fortnite</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/crafting-the-ideal-laptop-for-unmatched-playtime/"><u>Crafting the Ideal Laptop for Unmatched Playtime</u></a></li>
<li><a href="https://win-solutions.techidaily.com/dead-space-reboot-wont-start-here-are-5-expert-fixes-for-gamers/"><u>Dead Space Reboot Won't Start? Here Are 5 Expert Fixes for Gamers !</u></a></li>
<li><a href="https://win-solutions.techidaily.com/expert-tips-to-repair-nonfunctional-dolby-atmos-audio-features-in-windows-devices/"><u>Expert Tips to Repair Nonfunctional Dolby Atmos Audio Features in Windows Devices</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-motorola-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Motorola?</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-fix-hp-scanner-not-working-2022-tips/"><u>How to Fix HP Scanner Not Working – 2022 Tips</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1722993718920-how-to-overcome-graphics-lag-and-stutter-in-call-of-duty-black-ops-cold-war-top-tricks-revealed/"><u>How to Overcome Graphics Lag and Stutter in Call of Duty: Black Ops Cold War - Top Tricks Revealed!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-speed-up-your-sluggish-spotify-web-player-a-step-by-step-fix/"><u>How to Speed Up Your Sluggish Spotify Web Player - A Step-by-Step Fix</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-vivo-y100i-power-5g-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Vivo Y100i Power 5G Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-instagram-music-copyright-rules/"><u>In 2024, Instagram Music Copyright Rules</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-simplifying-vfx-with-magix-video-pro-x/"><u>In 2024, Simplifying VFX with Magix Video Pro X</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-syncopating-songs-implementing-fades-in-logic-pro-x/"><u>In 2024, Syncopating Songs Implementing Fades in Logic Pro X</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-the-ultimate-guide-altering-voices-for-a-competitive-edge-in-free-fire/"><u>In 2024, The Ultimate Guide Altering Voices for a Competitive Edge in Free Fire</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-nba-2k24-expert-advice-on-fixing-the-727e66ac-error-2024-edition/"><u>Mastering NBA 2K24: Expert Advice on Fixing the 727E66AC Error - 2024 Edition</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/premier-ios-devices-to-play-psp-games-in-high-fidelity-2023-edition-for-2024/"><u>Premier iOS Devices to Play PSP Games in High Fidelity, 2023 Edition for 2024</u></a></li>
<li><a href="https://win-solutions.techidaily.com/resolving-startup-problems-in-the-evil-genius-2-strategy-game/"><u>Resolving Startup Problems in the Evil Genius 2 Strategy Game</u></a></li>
<li><a href="https://win-solutions.techidaily.com/step-by-step-tutorial-for-uninstalling-nvidias-geforce-experience-software/"><u>Step-by-Step Tutorial for Uninstalling Nvidia's GeForce Experience Software</u></a></li>
</ul></div>

