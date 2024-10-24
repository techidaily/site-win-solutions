---
title: Step-by-Step Guide to Fixing Microsoft's Notorious 0X80070643 Update Error on Windows
date: 2024-08-28T05:00:13.046Z
updated: 2024-08-29T05:00:13.046Z
tags:
  - windows
categories:
  - tech
thumbnail: https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/windows-10-kb5034441-update-error.jpg
---

## Step-by-Step Guide to Fixing Microsoft's Notorious 0X80070643 Update Error on Windows

### Quick Links

* [Is Downloading the Windows 10 KB5034441 Update Important?](https://unlock-android.techidaily.com/5-solutions-for-tecno-spark-10c-unlock-without-password-by-drfone-android/)
* [What is the WinRE Recovery Partition?](https://vp-tips.techidaily.com/mastering-subtitle-craft-with-the-best-online-resources-today/)
* [How to Fix the Windows Update Error 0x80070643](https://win11.techidaily.com/unlocking-dangers-hacked-fingerprints-on-windows-pcs/)

### Key Takeaways

* The Windows Recovery Environment (WinRE) is a tool that helps you restore your system to its factory settings in case of severe system corruption.
* If your Windows Recovery partition doesn't have at least 250 MB of free space, you'll encounter the error 0x80070643 when downloading the Windows 10 KB503441 update.
* To fix this issue, you'll need to resize the Recovery partition using the Command Prompt.

 Microsoft releases updates for Windows to add new features and fix bugs in the current version. Most updates download without problems, but some can cause errors during the download. One such error is Windows update error 0x80070643, which occurs while downloading the Windows 10 KB5034441 update.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B300x600%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-300x600.gif" border="0"></a>
<!-- affiliate ads end -->
##  Is Downloading the Windows 10 KB5034441 Update Important?

 Microsoft released the [KB5034441 update](https://support.microsoft.com/en-au/topic/kb5034441-windows-recovery-environment-update-for-windows-10-version-21h2-and-22h2-january-9-2024-62c04204-aaa5-4fee-a02a-2fdea17075a8) in January 2024\. If your computer uses Windows Recovery Environment (WinRE), this update automatically applies the Safe OS Dynamic Update to address a security vulnerability. If left unpatched, attackers could exploit this vulnerability to bypass [BitLocker encryption](https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/) through WinRE.

 That means there's no question about downloading the KB5034441 update for Windows 10—it's a crucial security fix, and it's important to install it. However, there is a catch.

 It turns out the error 0x80070643 occurs even on systems that lack a Recovery partition. The exact error is:

 There were some problems installing updates, but we’ll try again later. If you keep seeing this and want to search the web or contact support for information, this may help: (0x80070643).

![Windows Update Error 0x80070643](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/windows-update-error-0x80070643.jpg) 

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Microsoft clearly states that if your system doesn't have a Recovery partition, you don't need to download the KB5034441 update and you can ignore this error. However, if your system does feature a Recovery partition, it's important for you to download the update and, unfortunately, Microsoft isn't going to release an automatic fix that will solve the 0x80070643 error.

 Earlier, when the report broke about users facing this issue, Microsoft acknowledged it and said they were working on a fix. However, that hasn't panned out (yet). 

 They have [updated their blog](https://learn.microsoft.com/en-us/windows/release-health/resolved-issues-windows-10-22h2#3231msgdesc) that discusses the error to mention that "Automatic resolution of this issue won't be available in a future Windows update. Manual steps are necessary to complete the installation of this update on devices which are experiencing this error." This means the only way for you to get rid of the problem is to perform the manual fix released by Microsoft, which is resizing the partition.

##  What is the WinRE Recovery Partition?

 When you [open the Disk Management tool](https://extra-resources.techidaily.com/picture-posters-best-frame-enhancing-software-recommendations/) on your computer, you will see a Recovery partition section in the area where the drive with the operating system is listed. But what exactly is this Recovery partition?

![Recovery partition in Disk Management](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/recovery-partition-in-disk-management.jpg) 

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Windows Recovery Environment (WinRE) is a built-in feature provided by Windows that helps you recover your computer when it has been corrupted for various reasons, and you cannot boot it. Additionally, it will help recover your system when it has become unusable due to incorrect updates or accidental removal of system files.

 To check if the Recovery partition is configured properly on your computer, [open Command Prompt as an administrator](https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-14-ultra-drfone-by-drfone-android/), type **reagentc /info**, and hit Enter. If you see "Enabled" next to Windows RE status, it means your computer has a Recovery partition, and it is working properly.

![Windows RE status in Command Prompt](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/windows-re-status-in-command-prompt.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
 For you to install the KB5034441 update, there must be 250 MB of free space in the Recovery partition. If the partition has less than that, you will encounter the 0x80070643 error when downloading the update.

##  How to Fix the Windows Update Error 0x80070643

 As mentioned earlier, the 0x80070643 error occurs when the Recovery partition doesn't have 250 MB of free space. This means that to fix the problem, you will need to provide more space to the Recovery partition. To do that, open Command Prompt as an administrator, type **reagentc /disable** to disable the Recovery partition, and hit Enter.

![Disable Recovery Partition command.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/disable-recovery-partition-command.jpg) 

 Type **diskpart** and hit Enter.

![Diskpart command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/diskpart-command-in-cmd.jpg) 

 Execute the **list disk** command to list all the disks.

![List disk command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/list-disk-command-in-cmd.jpg) 

 Select the disk where your operating system is installed. For example, if it is Disk 1, type **select disk 1** and hit Enter.

![Select disk command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/select-disk-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Type **list partition** to list the partitions on the disk.

![List partition command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/list-partition-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Select the primary disk partition. For example, if it is Partition 3, type **select partition 3** and hit Enter.

![Select partition 3 command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/select-partition-3-command-in-cmd.jpg) 

 You'll now have to shrink the partition. For that, type **shrink desired=250 minimum=250** and hit Enter.

![Shrink command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/shrink-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
 Now, select the Recovery partition. It will be labeled as "Recovery." For example, if it is Partition 4, type **select partition 4** and hit Enter.

![select partition 4 command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/select-partition-4-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
 Type **delete partition override** and hit Enter to delete the recovery partition.

![delete partition override command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/delete-partition-override-command-in-cmd.jpg) 

 Here's the most important step. Scroll up in your Command Prompt window and check the [disk partition style](https://facebook-video-footage.techidaily.com/updated-pro-level-gif-generation-a-critical-review/). If there's an asterisk (\*) in the GPT column of your operating system disk, it means you have GUID Partition Table (GPT) partition style. If there's no asterisk in the GPT column, then it's [MBR partition style](https://instagram-videos.techidaily.com/2024-approved-exclusive-guide-ranking-most-effective-ig-money-makers/).

![Asterick mark in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/asterick-mark-in-cmd.jpg) 

 If your disk is GPT, type **create partition primary id=de94bba4-06d1-4d40-a16a-bfd50179d6ac** and hit Enter. Then, type **gpt attributes =0x8000000000000001** and hit Enter. If your disk is MBR, type **create partition primary id=27** and hit Enter.

Close 

 Type **format** **quick fs=ntfs label="Windows RE tools"** and hit Enter. This will format the partition.

![Format command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/format-command-in-cmd.jpg) 

 Execute **list vol** to confirm that the recovery partition has been created.

![List vol command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/list-vol-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Type **exit** and hit Enter to exit Diskpart.

![Exit command in CMD.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/exit-command-in-cmd.jpg) 

 Re-enable the Recovery partition by typing **reagentc /enable** and hitting Enter.

![Recovery parition enable command in CMD](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/06/recovery-parition-enable-command-in-cmd.jpg) 

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
 Finally, to confirm the Recovery partition is configured properly on your computer, type **reagentc /info** and hit Enter. If you see "Enabled" next to Windows RE status, it means the Recovery partition is working properly. After that, [restart your computer](https://article-posts.techidaily.com/comparing-the-creme-de-la-creme-gopro-hero5-black-to-hero4-silver-for-2024/) and try downloading the Windows update again. This time, the error code 0x80070643 shouldn't interrupt the download process.

---

 Windows updates and error codes are a never-ending story, and this definitely won't be the last time you encounter an error code interfering with the Windows update process. But, like any other problem in the world, Windows update errors have their own solutions. Hopefully, the above fix has helped you get rid of the Windows update error 0x80070643, and you're able to successfully download the KB5034441 security update from Microsoft.

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


