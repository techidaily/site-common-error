---
title: Troubleshooting the Increased Disk Space Consumption of Telemetry Feature in Windows Press>Windows 11
date: 2024-09-04T20:19:43.978Z
updated: 2024-09-05T20:19:43.978Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting the Increased Disk Space Consumption of Telemetry Feature in Windows Press>Windows 11
excerpt: This Article Describes Troubleshooting the Increased Disk Space Consumption of Telemetry Feature in Windows Press>Windows 11
thumbnail: https://thmb.techidaily.com/5b6554e76aaa2a052eebb5ed360ccf43529d16f47d56cedf742a90d738a59cc9.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

### Method 1: Using Group Policy Editor

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) Type **gpedit.msc**  and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279bde5ee8d.png)

**Note:**  If you cannot find gpedit.msc on your Windows 10,[here is the method to got it.](https://tools.techidaily.com/drivereasy/download/)
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``
 3) Go to **Computer Configuration** \> **Administrative** **Templates** \>**Windows Components** \> **Data Collection and Preview Builds** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``

 5) Select **Disabled** , then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279d1cdc304.jpg)

 6) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.  
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` `` `
` `
` `
` `
` `
` `
` `
` `
` `
`

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

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
2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024338/7443" target="_top" id="2024338">
  <img src="//a.impactradius-go.com/display-ad/7443-2024338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024338/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106658/12108" target="_top" id="2106658">
  <img src="//a.impactradius-go.com/display-ad/12108-2106658" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106658/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

<!-- affiliate ads begin -->
<span id="1498635">
					<video width="320" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1498635.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/17326-1498635">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1498635.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:200px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fancheer.sjv.io%2Fc%2F5597632%2F1498635%2F17326'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1498635/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Reboot your Windows 10 PC.

5) On your keyboard, press the **Ctrl**  +**Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

 **Note:** If you can’t find gpedit.msc on your Windows 10 computer, here’s how you can get it: 1\. Download gpedit.msc(Group Policy Editor) from Internet  
 2\. When it’s done, Go to C:\\Windows\\SysWOW64, and copy the followings:  
 folders: GroupPolicy  
 GroupPolicyUsers  
 gpedit.msc(console document)  
 3\. Paste them in the following locations:  
 C:\\Windows\\System  
 C:\\Windows\\System32

 Hopefully this article could help you fix the problem. Feel free to comment below with your own experiences.

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
<li><a href="https://fox-helps.techidaily.com/new-augmenting-our-perception-an-introduction/"><u>[New] Augmenting Our Perception  An Introduction</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-snapsavvy-ai-revolutionizing-edit-processes-for-2024/"><u>[New] SnapSavvy AI  Revolutionizing Edit Processes for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-superior-online-emporiums-where-boxes-reflect-your-style/"><u>[New] Superior Online Emporiums  Where Boxes Reflect Your Style</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unveiling-ms-edges-picture-in-picture-magic/"><u>[New] Unveiling MS Edge's Picture-in-Picture Magic</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-virtual-screens-the-ultimate-guide/"><u>[Updated] 2024 Approved  Virtual Screens  The Ultimate Guide</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-innovative-solutions-advanced-mobile-recording-on-android/"><u>[Updated] In 2024, Innovative Solutions  Advanced Mobile Recording on Android</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-precision-in-photos-mastering-insta-story-zoom-levels/"><u>[Updated] In 2024, Precision in Photos  Mastering Insta Story Zoom Levels</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-halo-4-ue4-game-stopping-bugs-essential-fixes-and-workarounds/"><u>Beat Halo 4 UE4 Game-Stopping Bugs: Essential Fixes and Workarounds</u></a></li>
<li><a href="https://common-error.techidaily.com/decode-the-netflix-proxy-hurdle-steps-to-remove-your-vpn-and-watch-without-interruption/"><u>Decode the Netflix Proxy Hurdle: Steps to Remove Your VPN and Watch Without Interruption</u></a></li>
<li><a href="https://discover-dash.techidaily.com/effizientes-umwandeln-von-mkv-in-mp4-ohne-qualitatseinbussen-eine-anleitung/"><u>Effizientes Umwandeln Von MKV in MP4 Ohne Qualitätseinbußen - Eine Anleitung</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-remedies-for-microsofts-error-code-0x800f0831-via-windows-update-options/"><u>Effortless Remedies for Microsoft's Error Code 0X800f0831 via Windows Update Options</u></a></li>
<li><a href="https://fox-access.techidaily.com/elevate-your-flying-game-with-tailored-drone-propellers/"><u>Elevate Your Flying Game with Tailored Drone Propellers</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-resolving-user-configuration-errors-fixing-set-user-settings-to-driver-failed/"><u>Expert Advice: Resolving User Configuration Errors - Fixing 'Set User Settings To Driver Failed'</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-desktop-is-not-available-on-your-windows-system-profile-folder/"><u>Expert Tips for Fixing 'Desktop Is Not Available' On Your Windows System Profile Folder</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-your-windows-10-screensaver-functionality/"><u>Expert Tips for Restoring Your Windows 10 Screensaver Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-how-to-restore-your-computers-keyboard-lighting/"><u>Fixes: How to Restore Your Computer's Keyboard Lighting</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-chromecasts-connectivity-woes-a-step-by-step-guide/"><u>Fixing Chromecast's Connectivity Woes: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unregistered-windows-10-programs-effective-solutions-and-tips/"><u>Fixing Unregistered Windows 10 Programs: Effective Solutions and Tips</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-the-latest-amd-rx-6800-graphics-card-drivers-for-all-windows-versions-111087/"><u>Get the Latest AMD RX 6800 Graphics Card Drivers for All Windows Versions (11/10/8/7)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-ensure-stable-connections-fixing-recurring-usb-disconnect-dilemma/"><u>How to Ensure Stable Connections - Fixing Recurring USB Disconnect Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-breaking-ssltls-handshake-in-firefox-browser/"><u>How to Fix a Breaking SSL/TLS Handshake in Firefox Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quickly-solve-the-lagging-shutdown-of-your-windows-10-pc/"><u>How to Quickly Solve the Lagging Shutdown of Your Windows 10 PC</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-repair-unresponsive-camera-issues-during-a-zoom-call/"><u>How to Repair Unresponsive Camera Issues During a Zoom Call</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-the-disappeared-volume-icon-in-windows-10-with-step-by-step-images/"><u>How to Restore the Disappeared Volume Icon in Windows 10 with Step-by-Step Images</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211673739-how-to-successfully-launch-your-hosted-network-on-windows-10-solved/"><u>How to Successfully Launch Your Hosted Network on Windows 10 - Solved</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-6-plus-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 6 Plus Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-apple-iphone-15-drfone-by-drfone-virtual-ios/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Apple iPhone 15? | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-everything-to-know-about-apple-id-password-requirements-for-iphone-xs-max-by-drfone-ios/"><u>In 2024, Everything To Know About Apple ID Password Requirements For iPhone XS Max</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-get-the-apple-id-verification-code-on-apple-iphone-14-pro-in-the-best-ways-by-drfone-ios/"><u>In 2024, How To Get the Apple ID Verification Code On Apple iPhone 14 Pro in the Best Ways</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/1721267361759-iphone-resurrection-for-techies-recovering-data-without-a-single-backup-record/"><u>IPhone Resurrection for Techies - Recovering Data without a Single Backup Record!</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-repair-success-restoring-type-functionality-step-by-step/"><u>Keyboard Repair Success: Restoring Type Functionality Step by Step</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-the-approval-process-with-trustedinstaller-for-file-alterations/"><u>Navigating the Approval Process with TrustedInstaller for File Alterations</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-windows-10-health-understanding-the-power-of-sfc-and-dism-repair-methods/"><u>Optimizing Windows 10 Health: Understanding the Power of SFC and DISM Repair Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-windows-preparing-hang-essential-tips-and-tricks/"><u>Overcoming the 'Windows Preparing' Hang: Essential Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-and-simple-methods-to-overcome-the-disk-write-error-on-steam/"><u>Quick & Simple Methods to Overcome the 'Disk Write Error' On Steam</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-sluggish-startups-in-windows-7/"><u>Quick Fixes for Sluggish Startups in Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-fixing-the-graphic-cards-unavailability-in-starcraft-ii/"><u>Solution Found: Fixing the Graphic Card's Unavailability in StarCraft II</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-enable-bluetooth-detection-on-windows-device-manager/"><u>Solved: How to Enable Bluetooth Detection on Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-aoc-monitor-connection-issues-troubleshooting-steps-for-windows-11-users/"><u>Solving AOC Monitor Connection Issues: Troubleshooting Steps for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-civilization-vis-incompatible-graphics-card-issue/"><u>Solving Civilization VI's Incompatible Graphics Card Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-correct-the-configuration-fault-on-your-new-windows-11-pc/"><u>Step-by-Step Guide to Correct the Configuration Fault on Your New Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-when-your-laptops-touchpad-fails/"><u>Step-by-Step Solutions for When Your Laptop's Touchpad Fails</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/tactics-for-textural-image-modification/"><u>Tactics for Textural Image Modification</u></a></li>
<li><a href="https://common-error.techidaily.com/tech-trouble-gaming-interruptions-in-windows-os/"><u>Tech Trouble: Gaming Interruptions in Windows OS</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-trending-and-most-popular-movies-to-binge-on-disneyplus-this-week/"><u>Top Trending & Most Popular Movies to Binge on Disney+ This Week</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-resolve-unresponsive-mousepad-issues-in-windows-1187-systems/"><u>Troubleshoot and Resolve Unresponsive Mousepad Issues in Windows 11/8/7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-servers-not-available-error-on-destiny-2-expert-tips-and-fixes/"><u>Troubleshooting 'Servers Not Available' Error on Destiny 2 - Expert Tips and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-your-laptops-stuck-on-screen-issue/"><u>Ultimate Guide: Resolving Your Laptop's Stuck-On Screen Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/win10-reboots-without-user-input/"><u>Win10 Reboots Without User Input</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-cast-troubles-heres-how-you-can-get-it-working-smoothly-again/"><u>Windows 10 Cast Troubles? Here's How You Can Get It Working Smoothly Again</u></a></li>
</ul></div>
