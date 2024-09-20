---
title: "Origin Gaming Error Solutions: Correcting Setup Problems Smoothly"
date: 2024-09-16T18:00:30.795Z
updated: 2024-09-20T18:56:04.060Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Origin Gaming Error Solutions: Correcting Setup Problems Smoothly"
excerpt: "This Article Describes Origin Gaming Error Solutions: Correcting Setup Problems Smoothly"
thumbnail: https://thmb.techidaily.com/5a47a6a0d1daec39c5712eb645e3012dacc86a9be39fe69eb45844425e13837c.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://desktop-recording.techidaily.com/new-harnessing-the-power-of-ps4-capture-for-gamers-everywhere/"><u>[New] Harnessing the Power of PS4 Capture for Gamers Everywhere</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-calm-cursor-3-pathways-to-mellow-watching-videos-on-youtube-57-chars/"><u>[Updated] 2024 Approved Calm Cursor 3 Pathways to Mellow Watching Videos on YouTube (57 Chars)</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-mastering-screen-shots-on-windows-machines/"><u>[Updated] Mastering Screen Shots on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-224003-solved-enjoy-uninterrupted-video-viewing/"><u>Error Code 224003 Solved: Enjoy Uninterrupted Video Viewing</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-microsoft-print-to-pdf-issue-on-windows-11-a-comprehensive-guide/"><u>Fixing the 'Microsoft Print to PDF' Issue on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-master-your-youtube-identity-with-cool-titles/"><u>In 2024, Master Your YouTube Identity with Cool Titles</u></a></li>
<li><a href="https://common-error.techidaily.com/resizing-and-moving-windows-beyond-the-display-edge-tips-and-tricks/"><u>Resizing and Moving Windows Beyond the Display Edge: Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-when-your-pc-wont-boot-overcoming-the-getting-windows-ready-hurdle/"><u>Solutions for When Your PC Won't Boot: Overcoming the 'Getting Windows Ready' Hurdle</u></a></li>
<li><a href="https://program-issues.techidaily.com/tackling-lag-issues-in-call-of-duty-modern-warfare-ii-warzone-20-ultimate-troubleshooting-guide/"><u>Tackling Lag Issues in Call of Duty: Modern Warfare II (Warzone 2.0) – Ultimate Troubleshooting Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204983360-troubleshooting-video-files-resolve-playback-error-22403-now/"><u>Troubleshooting Video Files - Resolve Playback Error 22403 Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-sign-in-errors-with-user-profile-services/"><u>Troubleshooting Windows 11 Sign-In Errors with User Profile Services</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlock-iphone-6s-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>Unlock iPhone 6s With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-your-itel-p40-auto-does-not-work-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What To Do if Your Itel P40 Auto Does Not Work | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798161/11305" target="_top" id="798161">
  <img src="//a.impactradius-go.com/display-ad/11305-798161" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798161/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

