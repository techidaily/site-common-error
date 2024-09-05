---
title: Bypass and Repair Critical Error 0xC1900208 in Your Windows 10 System Update Process
date: 2024-09-04T20:17:32.508Z
updated: 2024-09-05T20:17:32.508Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Bypass and Repair Critical Error 0xC1900208 in Your Windows 10 System Update Process
excerpt: This Article Describes Bypass and Repair Critical Error 0xC1900208 in Your Windows 10 System Update Process
thumbnail: https://thmb.techidaily.com/f55f35329f28573e49eb2c54e3ad586424ba4a61048c3f39de5943b637615a77.jpg
---

## Definitive Solutions to Error 0X802^24200D – Successfully Update Your Windows System Now

If you’re seeing an**error code 0x8024200d**  when performing a Windows update,  you’re not alone. Many Windows users are reporting it. This error code usually appears when they try to update to a new build of the Windows system. The reason behind it is that some updated files are missing or corrupted.

 The good news is you can fix it. You should be able to fix the problem quite easily using one of the solutions we’ve listed below. You may not have to try them all. Just work your way down the list until you find the one that works.

1. [**Running the Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. **[Restarting the Windows Update service](https://tools.techidaily.com/drivereasy/download/)**
3. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
4. **[Downloading updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**

## Method 1: Running the Windows Update Troubleshooter

 You can download and run**the Windows Update Troubleshooter** to automatically diagnose and resolve any issues regarding Windows Update.

**1)** Click **[here](http://aka.ms/diag%5Fwu)**  to download the Windows Update Troubleshooter.

**2)** Double-click the downloaded file (**WindowsUpdate.diagcab** ) to run the troubleshooter, and then click**Next** .

**If your current operating system is Windows 7** , you just need to wait until the troubleshooter finishes the process and shows you the process result.**If your current operating system is Windows 8 or Windows 10** , you may need to follow the steps below.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap3-1.png)

**3)** If there is a more recent version of Windows Update troubleshooter available, click to run it.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap4-2.png)

**4)** In the new version of Windows Update troubleshooter, Click **Next** . The troubleshooter will check the available updates for your machine.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap5-1.png)

**5)** Click **Apply this fix**  to start the update process in the background immediately.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap7.png)

 The troubleshooter will try to fix the issue for you. You can restart your computer and try to perform the Windows update again. If it still doesn’t work, please try the next method.

## Method 2: Restarting the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try to restart the Windows Update service to resolve this problem. Here’s how to do it:

**1)** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog, then type**services.msc** and press**Enter** to open the Services window.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap13.png)

**2)** Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap14-2.png)

**3)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open **File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.

`C:\Windows\SoftwareDistribution\DataStore`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap18-2.png)

Please paste it in the address bar.

**4)** Delete all the files in the folder **DataStore** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap20-1.png)

 When all the files are deleted, you shall see “This folder is empty”.

**5)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open**File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to open the**Download** folder.

`` `C:\Windows\SoftwareDistribution\Download`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap21-1.png)

Please paste it in the address bar.

**6)** Delete all the files in the folder**Download** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap22-3.png)

 When all the files are deleted, you shall see “This folder is empty”.

**7)** In the Services window, right-click **Windows Update**  and select**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap24-2.png)

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next method.

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
## Method 3: Running System File Checker

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

**1)**  On your keyboard, press**the Windows Logo Key** and then type**cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **Ok** to run the **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap37.png)

**2)** On your keyboard, type the command below and press **Enter** . **If your current operating system is Windows 7, please skip this step.**

DISM.exe /Online /Cleanup-image /Restorehealth

 It may take several minutes for this command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap11.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)** When this command operation is completed, on your keyboard, type the following command and press **Enter** .

sfc /scannow

It may take some time for the command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap12-1.png)

**4)** When this command operation is completed, close the **Command Prompt** and run **Windows Update**  again to check whether this method works or not. If you still fail to install updates for your Windows system, please try the next method.

<!-- affiliate ads begin -->
<span id="1983474">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983474.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983474">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983474.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983474%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983474/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 4: Downloading updates from Microsoft Update Catalog manually

 If all the methods mentioned above still don’t work for you, you can try to download the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

**1)** On your keyboard, press**the Windows Logo Key** and type**Windows Update** , and then press**Enter** to open Windows Update.

**2)** Click **View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.

**3)** Follow the instructions below to view your system type:

**i.** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Enter** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap40.png)

**ii.**  Type the command line**systeminfo** and press**Enter** to view your system type.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap31-2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 “**X64-based PC** ” indicates that your Windows OS is 64-bit; “**X86-based PC** ” means that your Windows OS is 32-bit.

**4)** Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

**5)**  Type the update number that you want to download. In this example, type KB 3006137 and then click **Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap42.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082521/7443" target="_top" id="2082521">
  <img src="//a.impactradius-go.com/display-ad/7443-2082521" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082521/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**6)** In the list of search results, select the right update for your operating system and click **Download** .

 If your Windows OS is 64-bit, you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap26-1.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030395/7443" target="_top" id="2030395">
  <img src="//a.impactradius-go.com/display-ad/7443-2030395" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030395/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**7)** In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap27.png)

**8)** Double-click the downloaded file and follow the on-screen instructions to install the update.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-data.techidaily.com/omparing-digital-platform-profits-dailymovement-to-youtube-revenue/"><u>[New] Comparing Digital Platform Profits  DailyMovement to YouTube Revenue</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-traveling-back-in-social-media-years-a-practical-fb-guide-for-2024/"><u>[New] Traveling Back in Social Media Years  A Practical FB Guide for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-step-by-step-guide-to-download-and-store-twitter-videos-on-phone/"><u>[Updated] 2024 Approved  Step-by-Step Guide to Download and Store Twitter Videos on Phone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-engineering-engaging-media-excerpts-for-2024/"><u>[Updated] Engineering Engaging Media Excerpts for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-acquiring-high-clarity-imagery-without-limitations/"><u>2024 Approved  Acquiring High-Clarity Imagery without Limitations</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-perfect-pixels-in-a-minute-quick-fixes-with-studio-editor/"><u>2024 Approved  Perfect Pixels in a Minute  Quick Fixes with Studio Editor</u></a></li>
<li><a href="https://win-answers.techidaily.com/achieving-optimal-ark-isle-of-carnage-speed-a-players-guide-to-fps-boosting-on-desktops/"><u>Achieving Optimal ARK: Isle of Carnage Speed: A Player's Guide to FPS Boosting on Desktops</u></a></li>
<li><a href="https://common-error.techidaily.com/blackout-phenomenon-screen-quest/"><u>Blackout Phenomenon: Screen Quest</u></a></li>
<li><a href="https://tech-hub.techidaily.com/chatxt-innovation-for-enriched-storytelling/"><u>ChaTxt Innovation for Enriched Storytelling</u></a></li>
<li><a href="https://driver-install.techidaily.com/direct-easy-way-to-get-new-wacom-bamboo-drivers/"><u>Direct, Easy Way to Get New Wacom Bamboo Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-tips-resolving-issues-when-usb-drives-go-missing-on-your-computer/"><u>DIY Repair Tips: Resolving Issues When USB Drives Go Missing on Your Computer</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/easy-transition-upgrading-your-system-from-windows-amo-to-windows-11/"><u>Easy Transition: Upgrading Your System From Windows Amo to Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-dealing-with-an-unresponsive-internet-explorer-browser/"><u>Effective Solutions for Dealing with an Unresponsive Internet Explorer Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/elaborate-on-how-solving-problems-aids-personal-growth-and-self-reliance/"><u>Elaborate on How Solving Problems Aids Personal Growth and Self-Reliance.</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-addressing-the-your-computer-cannot-start-error-message/"><u>Expert Tips for Addressing the 'Your Computer Cannot Start' Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-repairing-malfunctioning-shift-key-on-your-computer/"><u>Expert Tips: Repairing Malfunctioning Shift Key on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/failed-to-initialize-battleye-service-generic-error-fixed/"><u>Failed to Initialize BattlEye Service: Generic Error [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-troubleshooting-and-repairing-unsuccessful-writes-to-referenced-0x-memory-locations/"><u>Fixed: Troubleshooting and Repairing Unsuccessful Writes to Referenced 0X Memory Locations</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-mystery-how-to-stop-your-pc-from-shutting-down-unexpectedly/"><u>Fixing the Mystery: How to Stop Your PC From Shutting Down Unexpectedly</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-update-error-code-8007000e-fast-and-effective-solutions/"><u>Fixing Windows Update Error Code 8007000E: Fast and Effective Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcoming-errors-when-initializing-bluetooth-stack-services/"><u>Guide to Overcoming Errors When Initializing Bluetooth Stack Services</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-videos-from-tecno-pova-5-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Videos from Tecno Pova 5 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/hp-840-g3-drivers-download-and-install/"><u>HP 840 G3 Drivers Download and Install</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-3-solutions-to-find-your-apple-iphone-14-current-location-of-a-mobile-number-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Solutions to Find Your Apple iPhone 14 Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Samsung Galaxy M14 5G? | Dr.fone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-win10-video-capture-pro-professional-edition/"><u>In 2024, Win10 Video Capture Pro - Professional Edition</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/journey-to-jewels-5-optimal-terrafirma-mapping-for-2024/"><u>Journey to Jewels  5 Optimal Terrafirma Mapping for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-issues-is-the-service-down-and-what-can-you-do-about-it/"><u>Netflix Issues: Is the Service Down, and What Can You Do About It?</u></a></li>
<li><a href="https://fox-helps.techidaily.com/next-level-android-for-3d-video-enthusiasts-for-2024/"><u>Next-Level Android for 3D Video Enthusiasts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/nier-automata-crashes-on-desktop-resolved-effective-fixes-and-tweaks-for-gamers/"><u>Nier: Automata Crashes on Desktop Resolved: Effective Fixes and Tweaks for Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-memory-management-executables-impact-on-your-pc-windows-10/"><u>Optimizing Memory Management Executable's Impact on Your PC [WINDOWS 10]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-volume-control-glitches-in-windows-10-effective-solutions-for-crystal-clear-audio/"><u>Overcoming Volume Control Glitches in Windows 10: Effective Solutions for Crystal Clear Audio</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-remedies-to-prevent-your-csgo-from-suddenly-shutting-down/"><u>Quick Remedies to Prevent Your CSGO From Suddenly Shutting Down</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-set-up-problems-for-smooth-gaming-experience-with-eas-origin-platform/"><u>Resolve Set-Up Problems for Smooth Gaming Experience with EA's Origin Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solution-resolving-the-steam-disk-writes-failed-issue-without-hassle/"><u>Simple Solution: Resolving the 'Steam Disk Writes Failed' Issue Without Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-when-google-chrome-freezes-up-and-wont-respond/"><u>Solution for When Google Chrome Freezes Up and Won’t Respond</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solving-pubg-startup-failures-a-detailed-tutorial-for-gamers-and-techies/"><u>Solving PUBG Startup Failures : A Detailed Tutorial for Gamers and Techies</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/step-by-step-method-for-uploading-pictures-from-an-aged-iphone-to-the-latest-iphone-x-using-a-mac-computer/"><u>Step-by-Step Method for Uploading Pictures From an Aged iPhone to the Latest iPhone X Using a Mac Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-fixing-a-vanishing-taskbar-on-windows-10-discover-4-key-methods/"><u>The Ultimate Guide to Fixing a Vanishing Taskbar on Windows 10 - Discover 4 Key Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206874291-trouble-with-updownleftright-keys-discover-easy-fixes-now/"><u>Trouble with Up/Down/Left/Right Keys? Discover Easy Fixes Now</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-ethernet-connectivity-for-windows-117-users/"><u>Troubleshooting Your Ethernet Connectivity for Windows 11/7 Users</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-2024-approved-unlocking-fcpx-advanced-image-cropping-techniques/"><u>Updated 2024 Approved Unlocking FCPX Advanced Image Cropping Techniques</u></a></li>
<li><a href="https://win-howtos.techidaily.com/win10-alleviating-high-cpu-performance-issues/"><u>Win10: Alleviating High-CPU Performance Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-solution-how-to-unstuck-and-repair-your-keyboards-locked-keys/"><u>Windows Solution: How to Unstuck and Repair Your Keyboard's Locked Keys</u></a></li>
</ul></div>
