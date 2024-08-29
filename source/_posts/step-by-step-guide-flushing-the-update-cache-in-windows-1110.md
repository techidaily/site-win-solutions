---
title: "Step-by-Step Guide: Flushing the Update Cache in Windows 11/10"
date: 2024-08-26 17:52:21
updated: 2024-08-29 11:10:47
tags:
  - windows
categories:
  - tech
thumbnail: https://thmb.techidaily.com/2d3c664ce9be135fd37888c5ff8219b3062ccd69d1f4c4bde112a2f9adac51f0.jpg
---

## Step-by-Step Guide: Flushing the Update Cache in Windows 11/10

### Quick Links

* [Why Should You Clear Your Windows Update Cache?](https://techno-recovery.techidaily.com/the-ultimate-collection-of-ps-vr2-game-announcements-everything-unveiled-to-date/)
* [Clear Windows Update Cache Using File Explorer](https://screen-sharing-recording.techidaily.com/updated-masterclass-of-marksmen-select-7-superior-fps-for-2024/)
* [Clear Windows Update Cache Using Disk Cleanup](https://instagram-video-recordings.techidaily.com/in-2024-cracking-the-code-of-true-instagram-photos/)
* [Clear Windows Update Cache Using Command Prompt](https://android-location.techidaily.com/in-2024-9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-realme-11x-5g-drfone-by-drfone-virtual/)

### Key Takeaways

* To delete the update cache, open Run, type **services.msc**, right-click "Windows Update," and choose "Stop." Keep the window open.
* Open Run again, type **C:\\Windows\\SoftwareDistribution\\**, select all files, right-click a file, and choose the trash can icon (Windows 11) or "Delete" (Windows 10).
* Come back to the "Services" window, right-click "Windows Update," and choose "Start."

 Both Windows 11 and Windows 10 make it super easy to clear your Windows Update cache. You can use a graphical method or a command line option to delete the saved update files. We’ll show you your available options.

##  Why Should You Clear Your Windows Update Cache?

 There are many reasons you might want to clear your Windows Update cache.

 You might be [facing issues finding or installing updates](https://extra-guidance.techidaily.com/2024-approved-smoothing-out-the-rough-edges-in-photo-booth-videos/), and clearing the cache often fixes the problem. Clearing the cache fixes issues with Windows Updates by forcing Windows to re-download all the required files.

 Another reason is to [free up storage space](https://voice-adjusting.techidaily.com/premier-software-solutions-for-clearing-up-rough-audio-texture-for-2024/). Update cache files often use a huge chunk of the storage, and you can reclaim that by deleting those cached files. (Windows does delete some update files after installing those updates, but not all.)

##  Clear Windows Update Cache Using File Explorer

 An easy graphical way to delete the update cache is to use File Explorer. This method deletes all the update cache files.

 To use this method, open the Run dialog box by pressing Windows+R. Type the following in the box and press Enter:

services.msc

 In the Services window, find the Windows Update service. Right-click it and select "Stop." Keep this window open as you’ll come back here later.

!['Stop' highlighted for 'Windows Update' on the 'Services' window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/1-stop-windows-update-service.jpg) 

 Launch Run again using Windows+R, type the path below in the box, and press Enter. The following is the path to the Windows Update cache folder. It assumes that Windows is installed on your C:\\ drive. However, if that’s not the case, just change the drive letter in the path.

C:\Windows\SoftwareDistribution\

 Press Ctrl+A to [select all files in the open folder](https://on-screen-recording.techidaily.com/updated-effective-strategies-to-capture-and-save-google-voice-dialogues-for-2024/). Right-click a selected file and choose the trash can icon (Windows 11) or "Delete" (Windows 10).

![The trash can icon highlighted for the Windows Update cache files.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/2-delete-windows-update-cache-files.jpg) 

 Close File Explorer and [empty the Recycle Bin](https://some-guidance.techidaily.com/new-the-complete-powerdirector-2024-users-handbook/).

 Then, return to the "Services" window, right-click "Windows Update," and choose "Start."

!['Start' highlighted for 'Windows Update' on the 'Services' window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/3-start-windows-update-service.jpg) 

 This ensures your PC can continue to look for the latest updates.

##  Clear Windows Update Cache Using Disk Cleanup

 Windows’s built-in Disk Cleanup utility helps delete some Windows Update cache files.

 To use it, open the Start Menu, search for **Disk Cleanup**, and launch the utility.

![Disk Cleanup highlighted in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/4-run-disk-cleanup.jpg) 

 Select your Windows installation drive and choose "OK."

![The Windows installation drive and 'OK' highlighted in Disk Cleanup prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/5-choose-windows-drive.jpg) 

 Select "Clean Up System Files."

!['Clean Up System Files' highlighted in Disk Cleanup.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/6-clean-up-system-files.jpg) 

 Choose your Windows installation drive again and select "OK."

 In Disk Cleanup, enable the "Windows Update Cleanup" option. Feel free to enable other options if you’d like to delete those files as well. Then, at the bottom, click "OK."

!['Windows Update Cleanup' and 'OK' highlighted in Disk Cleanup.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/7-delete-windows-update-cache-disk-cleanup.jpg) 

 The tool will begin cleaning up the update cache files.

##  Clear Windows Update Cache Using Command Prompt

 If you prefer command line methods over graphical ones, use a few commands in Command Prompt (or PowerShell) to remove the update cache.

 Begin by opening the Start Menu, searching for **Command Prompt**, and selecting "Run as Administrator."

!['Run as Administrator' highlighted for Command Prompt in Windows Search.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/8-run-cmd-as-admin.jpg) 

 In the "User Account Control" (UAC) prompt, select "Yes."

 Type the following lines in Command Prompt, and press Enter after each line. The first command disables the Windows Update service and the second command turns off the Background Intelligent Transfer Service service.

        `net stop wuauserv  
net stop bits`
    
![Commands to stop certain Windows services typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/9-stop-services.jpg) 

 Next up, run the following command to make the Windows Update cache folder the current working directory.

cd %windir%\SoftwareDistribution

 Type the following command and press Enter to delete the update cache.

del /f /s /q *.*

![Commands to clear the Windows Update cache typed in Command Prompt.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/10-clear-update-cache-cmd.jpg) 

 After clearing the cache, restart the services you stopped above. Do that by typing the following commands and pressing Enter after each line.

        `net start wuauserv  
net start bits`
    
 You’re done.

###  Use a Script to Clear Update Cache in a Single-Click

 You can [make a batch file](https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-vivo-t2-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/) out of the commands above to clear your Windows Update cache in just a single click. This is a convenient method if you delete your update cache files often.

 To make that script, open the Start Menu, search for **Notepad**, and launch the app. Copy the code below and paste it in your Notepad document.

        `net stop wuauserv  
net stop bits  
cd %windir%\SoftwareDistribution  
del /f /s /q *.*  
net start wuauserv  
net start bits`
    
 Save the file by choosing File > Save from the menu bar.

 In the "Save As" window, select the folder where you want to save the script. Click the "Save as Type" drop-down menu and choose "All Files." Select the "File Name" field and enter a name of your choice. Then, append **.bat** at the end of the file name. This ensures Notepad saves the file as a batch script.

 Then, click "Save."

![Windows' 'Save As' window.](https://static1.howtogeekimages.com/wordpress/wp-content/uploads/2024/02/11-create-update-cache-removal-batch-file.jpg) 

 In the future, to clear your Windows Update cache using the script, right-click the script file and select "Run as Administrator." In the User Account Control prompt, choose "Yes." The script will stop certain services, deletes the update cache files, and restarts the stopped services.

---

 And that’s how you get rid of the update cache files using various ways on your Windows 11 or Windows 10 computer. We hope you find the methods useful.

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
