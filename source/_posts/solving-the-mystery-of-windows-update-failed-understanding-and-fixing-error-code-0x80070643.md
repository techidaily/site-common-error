---
title: Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643
date: 2024-11-10T17:27:50.856Z
updated: 2024-11-15T18:15:48.694Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643
excerpt: This Article Describes Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
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
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151890/7443" target="_top" id="2151890">
  <img src="//a.impactradius-go.com/display-ad/7443-2151890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-in-2024-fundamentals-of-writing-captivating-videography-scripts/"><u>[New] In 2024, Fundamentals of Writing Captivating Videography Scripts</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-live-streaming-showdown-obs-vs-wirecast-faceoff-for-2024/"><u>[Updated] Live Streaming Showdown OBS vs Wirecast Faceoff for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-obs-and-zoom-integration-your-quick-pathway-for-2024/"><u>[Updated] OBS and Zoom Integration Your Quick Pathway for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-the-ultimate-guide-to-the-best-ps3-gaming-on-pc/"><u>2024 Approved The Ultimate Guide to the Best PS3 Gaming on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-80072ee2-windows-update-error/"><u>Easy to Fix 80072EE2 Windows Update Error</u></a></li>
<li><a href="https://win-howtos.techidaily.com/essential-requirement-compatible-with-directx-11-gpus-only-to-enable-engine-usage/"><u>Essential Requirement: Compatible with DirectX 11 GPUs Only to Enable Engine Usage</u></a></li>
<li><a href="https://unlock-android.techidaily.com/everything-you-need-to-know-about-lock-screen-settings-on-your-infinix-by-drfone-android/"><u>Everything You Need to Know about Lock Screen Settings on your Infinix</u></a></li>
<li><a href="https://change-location.techidaily.com/how-does-the-stardust-trade-cost-in-pokemon-go-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>How does the stardust trade cost In pokemon go On Samsung Galaxy S23+? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/methods-to-change-gps-location-on-vivo-y78-5g-drfone-by-drfone-virtual-android/"><u>Methods to Change GPS Location On Vivo Y78 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-11s-persistent-troubleshooting-loop-with-easy-fixes/"><u>Overcome Windows 11'S Persistent Troubleshooting Loop with Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-solve-the-common-anti-cheat-bug-in-apex-legends/"><u>Quick Guide: Solve the Common Anti-Cheat Bug in Apex Legends</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-why-teredo-pe-is-not-connecting-solutions-and-fixes/"><u>Resolved: Why Teredo PE Is Not Connecting - Solutions and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-fixing-nonfunctional-ethernet-on-windows-107-devices/"><u>Step-by-Step Solutions for Fixing Nonfunctional Ethernet on Windows 10/7 Devices</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-honor-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Honor Android SIM Unlock APK</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-repair-the-nonfunctioning-windows-11-start-menu/"><u>Troubleshooting Guide: How to Repair the Nonfunctioning Windows 11 Start Menu</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-epson-scan-non-responsiveness/"><u>Troubleshooting: Epson Scan Non-Responsiveness</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-solution-for-critical-process-died-blue-screen-bsod-error-code-c00000e9-in-windows/"><u>Ultimate Solution for Critical Process Died Blue Screen (BSoD) Error Code C00000e9 in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/usb-mouse-malfunction-on-computers-discover-quick-and-effective-repair-techniques/"><u>USB Mouse Malfunction on Computers? Discover Quick and Effective Repair Techniques!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-meizu-21-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Meizu 21? | Dr.fone</u></a></li>
</ul></div>

