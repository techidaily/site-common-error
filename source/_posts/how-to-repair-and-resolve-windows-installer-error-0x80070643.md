---
title: How to Repair and Resolve Windows Installer Error 0X80070643
date: 2024-10-16T01:55:50.210Z
updated: 2024-10-18T20:03:09.217Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Repair and Resolve Windows Installer Error 0X80070643
excerpt: This Article Describes How to Repair and Resolve Windows Installer Error 0X80070643
thumbnail: https://thmb.techidaily.com/e6d099750c73059d854ce64a05b1f14144b4ddd8add62154acc4588369eca37b.jpg
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
<a href="https://wigfever.sjv.io/c/5597632/1995803/22899" target="_top" id="1995803">
  <img src="//a.impactradius-go.com/display-ad/22899-1995803" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/1995803/22899" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1880956/19272" target="_top" id="1880956">
  <img src="//a.impactradius-go.com/display-ad/19272-1880956" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880956/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-video-capture.techidaily.com/updated-choosing-the-best-screen-capture-app-obs-vs-fraps-for-2024/"><u>[Updated] Choosing the Best Screen Capture App – OBS vs Fraps for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-exploring-adsense-revenue-streams-on-youtube-for-every-1k-watcher/"><u>[Updated] In 2024, Exploring AdSense Revenue Streams on YouTube for Every 1K Watcher</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/best-12-ai-voice-cloning-tools-online-and-offline/"><u>Best 12 AI Voice Cloning Tools Online & Offline</u></a></li>
<li><a href="https://youtube-data.techidaily.com/dive-into-rank-tracker-solutions-for-peak-success-on-youtube-for-2024/"><u>Deep Dive Into Rank Tracker Solutions for Peak Success on YouTube for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fix-for-error-0x8007002-during-windows-updates-easy-steps-inside/"><u>Effortless Fix for Error 0X80070#02 During Windows Updates | Easy Steps Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-correct-error-code-0x80072f8f-on-your-windows-operating-system/"><u>Expert Tips to Correct Error Code 0X80072F8F on Your Windows Operating System</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-vivo-x90s-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Vivo X90S to iPod | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-pcs-camera-malfunction-fixing-error-code-0xa00f4292-on-windows/"><u>Resolve Your PC's Camera Malfunction: Fixing Error Code 0XA00F4292 on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-common-fixes-for-my-blocky-friends-lan-not-working-situation/"><u>Solved: Common Fixes for My Blocky Friends' LAN Not Working Situation</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/unlock-your-boost-mobile-iphone-8-plus-before-the-plan-expires-by-drfone-ios/"><u>Unlock Your Boost Mobile iPhone 8 Plus Before the Plan Expires</u></a></li>
</ul></div>

