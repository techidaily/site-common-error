---
title: "Comprehensive Techniques for Resolving Windows 11 Error Code 0X80072EFD: A Step-by-Step Tutorial"
date: 2024-10-31T01:39:12.779Z
updated: 2024-11-04T17:43:57.807Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Comprehensive Techniques for Resolving Windows 11 Error Code 0X80072EFD: A Step-by-Step Tutorial"
excerpt: "This Article Describes Comprehensive Techniques for Resolving Windows 11 Error Code 0X80072EFD: A Step-by-Step Tutorial"
thumbnail: https://thmb.techidaily.com/5b41f1296863a8cc22d3a2c3dbb979d19c4362b2b1c96fbfb8d71b7193c17bd8.jpg
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
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135348/19272" target="_top" id="2135348">
  <img src="//a.impactradius-go.com/display-ad/19272-2135348" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135348/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657396/16446" target="_top" id="1657396">
  <img src="//a.impactradius-go.com/display-ad/16446-1657396" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657396/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139107/17108" target="_top" id="2139107">
  <img src="//a.impactradius-go.com/display-ad/17108-2139107" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139107/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-comprehensive-guide-to-crafting-professional-haul-videos/"><u>[New] 2024 Approved Comprehensive Guide to Crafting Professional Haul Videos</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-essential-tactics-for-youtube-success-in-25-ways/"><u>[New] In 2024, Essential Tactics for YouTube Success in 25 Ways</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-cloud-savvy-pinpointing-optimal-data-purchases/"><u>[Updated] Cloud Savvy Pinpointing Optimal Data Purchases</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-fast-snap-restoration-guide/"><u>[Updated] Fast Snap Restoration Guide</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-leveraging-synergies-how-to-choose-ideal-youtube-duosgroups/"><u>[Updated] Leveraging Synergies How to Choose Ideal YouTube Duos/Groups</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-for-addressing-the-hamachi-service-stopped-trouble-on-your-system/"><u>Effective Techniques for Addressing the 'Hamachi Service Stopped' Trouble on Your System</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-samsung-galaxy-z-flip-5-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Samsung Galaxy Z Flip 5 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-functional-microphone-on-skype/"><u>How to Fix a Non-Functional Microphone on Skype</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-top-free-4k-movies-player-picks-for-your-pc-with-windows-11-or-macos-system/"><u>The Top Free 4K Movies Player Picks for Your PC with Windows 11 or MacOS System</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-overcoming-monster-hunter-worlds-pc-disconnect-glitches/"><u>The Ultimate Guide to Overcoming Monster Hunter World's PC Disconnect Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fix-unsupported-operating-system-warning-and-prevent-exit-during-installation/"><u>Troubleshooting Guide: Fix Unsupported Operating System Warning & Prevent Exit During Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-repairing-a-non-functional-logitech-mouse-scroll-wheel/"><u>Troubleshooting Guide: Repairing a Non-Functional Logitech Mouse Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-non-functional-integrated-webcam-issues-in-windows/"><u>Troubleshooting Steps: Resolving Non-Functional Integrated Webcam Issues in Windows</u></a></li>
</ul></div>

