---
title: Step-by-Step Solutions for Correcting Error 0X80240017 During Windows Updates
date: 2024-09-10T16:00:44.803Z
updated: 2024-09-15T16:01:34.919Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Correcting Error 0X80240017 During Windows Updates
excerpt: This Article Describes Step-by-Step Solutions for Correcting Error 0X80240017 During Windows Updates
thumbnail: https://thmb.techidaily.com/80c97e26a42ec85426e926d8a619570205ae66ef3c841d342bad4a1013bf8d86.jpg
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
<li><a href="https://fox-blue.techidaily.com/new-efficient-media-transformation-with-actionable-steps-from-xml/"><u>[New] Efficient Media Transformation with Actionable Steps From XML</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-a-year-in-the-market-top-15-finance-videos/"><u>[Updated] In 2024, A Year in the Market Top 15 Finance Videos</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-canon-pixma-mx490-printer-drivers-on-windows/"><u>Download & Update Canon PIXMA MX490 Printer Drivers on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-and-prevent-frequent-mouse-disconnects-a-comprehensive-walkthrough/"><u>Fix and Prevent Frequent Mouse Disconnects: A Comprehensive Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-with-mouses-right-click-feature-on-windows-11-pcs/"><u>Fixing Issues with Mouse's Right-Click Feature on Windows 11 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-expired-semaphore-timeout-period-issue-with-error-0x80070079/"><u>How to Fix the 'Expired Semaphore Timeout Period' Issue with Error 0X80070079</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-detailed-pokemon-go-pvp-tier-list-to-make-you-a-pro-trainer-for-apple-iphone-8-drfone-by-drfone-virtual-ios/"><u>In 2024, A Detailed Pokemon Go PvP Tier List to Make you a Pro Trainer For Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/invisible-exit-command-secreting-windows-11-power-off/"><u>Invisible Exit Command: Secreting Windows 11 Power Off</u></a></li>
<li><a href="https://screen-capture.techidaily.com/poll-power-play-best-election-strategy-games-for-2024/"><u>Poll Power Play Best Election Strategy Games for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/top-picks-8-must-have-wallpapers-for-macos-users/"><u>Top Picks 8 Must-Have Wallpapers for MacOS Users</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-dns-server-not-responding-in-five-steps/"><u>Troubleshooting Guide: Resolving 'DNS Server Not Responding' In Five Steps</u></a></li>
<li><a href="https://techidaily.com/xiaomi-redmi-12-5g-can-t-play-mp4-video-files-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Xiaomi Redmi 12 5G can't play MP4 video files</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137215/26400" target="_top" id="2137215">
  <img src="//a.impactradius-go.com/display-ad/26400-2137215" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137215/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

