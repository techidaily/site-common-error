---
title: "High-Performance Windows Driver Setup: Keeping CPU Usage Low"
date: 2024-08-27T13:46:26.190Z
updated: 2024-08-28T13:46:26.190Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes High-Performance Windows Driver Setup: Keeping CPU Usage Low"
excerpt: "This Article Describes High-Performance Windows Driver Setup: Keeping CPU Usage Low"
thumbnail: https://thmb.techidaily.com/31fd63ab910fdd0bfef9c588934b4c990590f2025d46dff0a5963e90a62a92d8.jpg
---

## Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<span id="1793213">
					<video width="1080" height="1620" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19135-1793213">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1793213.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:1080px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftinyland.pxf.io%2Fc%2F5597632%2F1793213%2F19135'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793213/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BEditor%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/6d3207fd-9f15-4c21-f0ad-59c68e6a7e2a.png" border="0"></a>
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5) Restart your computer and see if your computer runs normally now.

## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-data.techidaily.com/024-approved-maximize-earnings-a-three-pronged-approach-to-monitoring-youtube-revenue/"><u>[New] 2024 Approved  Maximize Earnings  A Three-Pronged Approach to Monitoring YouTube Revenue</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-crafting-compelling-visual-narratives-with-illustrators-motion-blur/"><u>[Updated] 2024 Approved  Crafting Compelling Visual Narratives with Illustrator's Motion Blur</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-the-ultimate-key-to-capturing-and-preserving-your-favorite-streamed-shows/"><u>[Updated] In 2024, The Ultimate Key to Capturing and Preserving Your Favorite Streamed Shows</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-turn-views-into-earnings-monetize-with-more-than-500-subscribers/"><u>2024 Approved  Turn Views Into Earnings  Monetize with More than 500 Subscribers</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/2024-approved-yotube-success-crafting-unforgettable-music-reaction-content/"><u>2024 Approved  YoTube Success  Crafting Unforgettable Music Reaction Content</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/apple-iphone-7-backup-password-never-set-but-still-asking-heres-the-fix-drfone-by-drfone-ios/"><u>Apple iPhone 7 Backup Password Never Set But Still Asking? Heres the Fix | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/decode-and-defeat-the-windows-10-0x80072efd-error-easily/"><u>Decode and Defeat the Windows 10 0X80072EFD Error Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-call-of-duty-wwii-error-code-4220-expert-tips-and-tricks/"><u>Diagnosing and Repairing Call of Duty WWII Error Code 4220: Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1603-decoded-strategies-for-a-successful-software-installation-fix/"><u>Error 1603 Decoded: Strategies for a Successful Software Installation Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-1067-explained-steps-to-prevent-unexpected-windows-process-terminations/"><u>Error Code 1067 Explained: Steps to Prevent Unexpected Windows Process Terminations</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-handling-directory-does-not-exist-errors-successfully/"><u>Expert Tips for Handling 'Directory Does Not Exist' Errors Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-restoring-your-pcs-built-in-camera-functionality-on-windows-systems/"><u>Expert Tips: Restoring Your PC's Built-In Camera Functionality on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-volume-icon-missing-on-windows-10-with-pictures/"><u>Fix Volume Icon Missing on Windows 10 [with Pictures]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-errors-successfully-installing-hp-deskjet-d1360-printer-drivers-on-windows-788110/"><u>Fixing Errors: Successfully Installing HP Deskjet D1360 Printer Drivers on Windows 7/8/8.1/10</u></a></li>
<li><a href="https://common-error.techidaily.com/get-back-in-the-game-solving-common-issues-with-minecrafts-lan-setup/"><u>Get Back in the Game: Solving Common Issues with Minecraft's LAN Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-huion-stylus-up-and-running-again-top-5-fixes/"><u>Get Your Huion Stylus Up and Running Again - Top 5 Fixes!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-audio-problems-in-windows-107-fix-crackling-sounds/"><u>How to Troubleshoot Audio Problems in Windows 10/7 – Fix Crackling Sounds</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-oppo-k11x-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Oppo K11x Phone When You Forget the Password</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-to-samsung-galaxy-s23plus-frp-bypass-with-best-methods-by-drfone-android/"><u>In 2024, Easy Guide to Samsung Galaxy S23+ FRP Bypass With Best Methods</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-latest-guide-on-ipad-23-and-iphone-xs-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Latest Guide on iPad 2/3 and iPhone XS iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://extra-support.techidaily.com/maximize-screen-size-for-youtube-videos-for-2024/"><u>Maximize Screen Size for YouTube Videos for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-your-screens-brightness-blues-fixes-for-windows-10-problems/"><u>Overcome Your Screen’s Brightness Blues: Fixes for Windows 10 Problems</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/pushing-boundaries-with-high-speed-cinematography-for-2024/"><u>Pushing Boundaries with High-Speed Cinematography for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-windows-11-touchscreen-problems-quickly-using-this-5-part-strategy/"><u>Resolve Windows 11 Touchscreen Problems Quickly Using This 5-Part Strategy</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-copy-paste-problems-in-windows-11-a-comprehensive-guide/"><u>Resolving Copy-Paste Problems in Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-overcome-the-preparing-to-configure-windows-hurdle-easily/"><u>Solution Found! Overcome the 'Preparing to Configure Windows' Hurdle Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-windows-11-sound-problems-mastering-the-volume-settings-restoration/"><u>Solve Your Windows 11 Sound Problems - Mastering the Volume Settings Restoration</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-dll-runtime-140-not-found-issue/"><u>Troubleshooting Guide for 'DLL Runtime 140 Not Found' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-night-light-doesnt-work-on-windows-10-and-11-systems/"><u>Troubleshooting: Night Light Doesn't Work on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-crc-cyclical-data-integrity-issues/"><u>Understanding and Resolving CRC Cyclical Data Integrity Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-bluetooth-problems-a-step-by-step-guide-to-detecting-devices-easily/"><u>Windows 10 Bluetooth Problems? A Step-by-Step Guide to Detecting Devices Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-continuous-automatic-repairs-in-windows-11-top-fixes/"><u>Winning the Battle Against Continuous Automatic Repairs in Windows #11: Top Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-windows-10-update-error-0xc1900208-a-comprehensive-fix-guide/"><u>Winning the Battle Against Windows 10 Update Error 0xC1900208: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/xbox-ones-joystick-pc-compatibility-triumph/"><u>Xbox One's Joystick: PC Compatibility Triumph</u></a></li>
</ul></div>
