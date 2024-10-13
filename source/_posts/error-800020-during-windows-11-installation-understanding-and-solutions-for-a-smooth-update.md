---
title: "Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update"
date: 2024-10-11T01:10:44.065Z
updated: 2024-10-13T04:26:16.661Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update"
excerpt: "This Article Describes Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update"
thumbnail: https://thmb.techidaily.com/dce6bc9a112b3f049356452f785b8eb72027385ba75d849bd9c5cf60929a80d0.png
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

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
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407">
  <img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/977686/11832" target="_top" id="977686">
  <img src="//a.impactradius-go.com/display-ad/11832-977686" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/977686/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-the-ultimate-guide-canvas-hidden-tips-and-tricks/"><u>[New] 2024 Approved The Ultimate Guide Canva's Hidden Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-connectivity-issues-in-wacom-drawing-tablets/"><u>Diagnosing and Fixing Connectivity Issues in Wacom Drawing Tablets</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/direct-pathways-moving-iphone-content-to-pc-efficiently/"><u>Direct Pathways Moving iPhone Content to PC Efficiently</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-asus-vg248qe-graphics-card-driver-simple-steps/"><u>Download & Update Asus VG248QE Graphics Card Driver - Simple Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-repairing-blue-screen-error-0xc00000e9-on-windows-computers/"><u>Expert Tips for Repairing Blue Screen Error 0Xc00000e9 on Windows Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-x3daudio17dll-error-play-games-smoothly/"><u>Fix X3DAudio1_7.dll Error, Play Games Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-asus-laptops-malfunctioning-fn-control-keys-a-step-by-step-guide/"><u>Fixing ASUS Laptop's Malfunctioning FN Control Keys – A Step by Step Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Honor Magic 5 Lite? | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-updated-method-to-bypass-samsung-galaxy-m34-frp-by-drfone-android/"><u>In 2024, The Updated Method to Bypass Samsung Galaxy M34 FRP</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unidentified-usb-complications-with-port-resets-failures-on-windows-10/"><u>Overcoming Unidentified USB Complications with Port Resets Failures on Windows 10</u></a></li>
<li><a href="https://win-howtos.techidaily.com/resolving-microsoft-compatibility-telemetry-excessive-storage-use-in-windows-10/"><u>Resolving Microsoft Compatibility Telemetry Excessive Storage Use in Windows 10</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/selecting-superior-capture-cards-switch-style/"><u>Selecting Superior Capture Cards, Switch Style</u></a></li>
</ul></div>

