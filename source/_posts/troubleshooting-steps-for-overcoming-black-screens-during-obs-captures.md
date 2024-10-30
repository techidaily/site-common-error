---
title: Troubleshooting Steps for Overcoming Black Screens During OBS Captures
date: 2024-10-23T17:48:44.265Z
updated: 2024-10-30T16:09:25.783Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Overcoming Black Screens During OBS Captures
excerpt: This Article Describes Troubleshooting Steps for Overcoming Black Screens During OBS Captures
thumbnail: https://thmb.techidaily.com/443fa3d21137649dff0319f1c3c3070702e32a7b2f673e094959a8fdb4cdbd5b.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1938745/19272" target="_top" id="1938745">
  <img src="//a.impactradius-go.com/display-ad/19272-1938745" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938745/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1424527">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424527.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424527">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424527.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424527%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424527/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136614/26400" target="_top" id="2136614">
  <img src="//a.impactradius-go.com/display-ad/26400-2136614" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136614/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484940/16446" target="_top" id="1484940">
  <img src="//a.impactradius-go.com/display-ad/16446-1484940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484940/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-techniques.techidaily.com/new-expert-advice-on-acquiring-royalty-free-high-quality-graphics/"><u>[New] Expert Advice on Acquiring Royalty-Free, High-Quality Graphics</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ootball-inscriptions-premier-fifa-youtube-insights/"><u>[New] Football Inscriptions Premier FIFA YouTube Insights</u></a></li>
<li><a href="https://some-tips.techidaily.com/new-ultimate-animation-styles-pack/"><u>[New] Ultimate Animation Styles Pack</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-create-an-nft-easily-an-ultimate-guide-for-beginners/"><u>2024 Approved How to Create an NFT Easily An Ultimate Guide for Beginners</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/2024-approved-the-sizzling-social-feast-10-viral-food-trends/"><u>2024 Approved The Sizzling Social Feast 10 Viral Food Trends</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-enabled-successfully-steps-for-displaying-in-windows-device-manager/"><u>Bluetooth Enabled Successfully! Steps for Displaying in Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-fixes-for-resolving-constant-restarts-in-your-windows-10-device/"><u>Easy Fixes for Resolving Constant Restarts in Your Windows 10 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-dealing-with-repeated-not-recognized-kb310218-get-back-to-using-your-usb-devices-now/"><u>Expert Advice for Dealing with Repeated 'Not Recognized KB310218' - Get Back to Using Your USB Devices Now</u></a></li>
<li><a href="https://discover-docs.techidaily.com/guide-complet-pour-effacer-les-vieux-fichiers-dimage-de-sauvegarde-sur-windows-7-8-10-et-11/"><u>Guide Complet Pour Effacer Les Vieux Fichiers D'Image De Sauvegarde Sur Windows 7, 8, 10 Et 11</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-crafting-a-powerful-earnings-strategy-on-the-vimeo-platform/"><u>In 2024, Crafting a Powerful Earnings Strategy on the Vimeo Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209359338-laptop-microphone-problems-discover-effective-fixes-and-solutions-here/"><u>Laptop Microphone Problems? Discover Effective Fixes and Solutions Here</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-best-4k-video-editing-software/"><u>New In 2024, Best 4K Video Editing Software</u></a></li>
<li><a href="https://common-error.techidaily.com/repair-guide-dealing-with-dell-speaker-issues/"><u>Repair Guide: Dealing with Dell Speaker Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-halo-4-ue4-deadly-glitch-overcome-game-crashes/"><u>Solved Halo 4 UE4 Deadly Glitch: Overcome Game Crashes</u></a></li>
<li><a href="https://activate-lock.techidaily.com/the-most-effective-ways-to-bypass-apple-iphone-7-plus-activation-lock-by-drfone-ios/"><u>The Most Effective Ways to Bypass Apple iPhone 7 Plus Activation Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-overcoming-the-stopped-working-hamachi-problem-today/"><u>Troubleshooting Tips: Overcoming the 'Stopped Working' Hamachi Problem Today</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-container-issue-resolution-understanding-and-fixing-the-failed-to-enumerate-objects-error/"><u>Windows 10 Container Issue Resolution: Understanding and Fixing the 'Failed to Enumerate Objects' Error</u></a></li>
</ul></div>

