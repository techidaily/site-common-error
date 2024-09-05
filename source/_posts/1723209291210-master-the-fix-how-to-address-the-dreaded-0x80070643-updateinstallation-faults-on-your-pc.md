---
title: "Master the Fix: How To Address The Dreaded 0X80070643 Update/Installation Faults on Your PC"
date: 2024-09-04T20:19:50.278Z
updated: 2024-09-05T20:19:50.278Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Master the Fix: How To Address The Dreaded 0X80070643 Update/Installation Faults on Your PC"
excerpt: "This Article Describes Master the Fix: How To Address The Dreaded 0X80070643 Update/Installation Faults on Your PC"
thumbnail: https://thmb.techidaily.com/07fa8cadb13240ad4114bdffce36c4f17cee86cd9ffa9ec58a8ecda669ea9207.jpg
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

## Method 3: Running System File Checker

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

**1)**  On your keyboard, press**the Windows Logo Key** and then type**cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **Ok** to run the **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap37.png)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1167086/14483" target="_top" id="1167086">
  <img src="//a.impactradius-go.com/display-ad/14483-1167086" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1167086/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**2)** On your keyboard, type the command below and press **Enter** . **If your current operating system is Windows 7, please skip this step.**

DISM.exe /Online /Cleanup-image /Restorehealth

 It may take several minutes for this command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap11.png)

**3)** When this command operation is completed, on your keyboard, type the following command and press **Enter** .

sfc /scannow

It may take some time for the command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap12-1.png)

**4)** When this command operation is completed, close the **Command Prompt** and run **Windows Update**  again to check whether this method works or not. If you still fail to install updates for your Windows system, please try the next method.

<!-- affiliate ads begin -->
<span id="1531882">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531882.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531882">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531882.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531882%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531882/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997662/19272" target="_top" id="1997662">
  <img src="//a.impactradius-go.com/display-ad/19272-1997662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997662/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 “**X64-based PC** ” indicates that your Windows OS is 64-bit; “**X86-based PC** ” means that your Windows OS is 32-bit.

**4)** Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

**5)**  Type the update number that you want to download. In this example, type KB 3006137 and then click **Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap42.png)

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**6)** In the list of search results, select the right update for your operating system and click **Download** .

 If your Windows OS is 64-bit, you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap26-1.png)

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**7)** In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap27.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-leveraging-video-shorts-to-generate-income-online/"><u>[New] 2024 Approved  Leveraging Video Shorts to Generate Income Online</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-mastering-freefire-the-30-best-tag-strategies-to-increase-views/"><u>[New] Mastering FreeFire  The 30 Best Tag Strategies to Increase Views</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capturing-audio-masterpieces-using-audacity/"><u>[Updated] Capturing Audio Masterpieces Using Audacity</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-financial-gains-the-youtube-money-flow-from-1m-views-for-2024/"><u>[Updated] Financial Gains  The Youtube Money Flow From 1M Views for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-melodic-content-and-legalities-on-insta/"><u>[Updated] Melodic Content and Legalities on Insta</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transformative-techniques-mastering-lut-application-in-post-production/"><u>[Updated] Transformative Techniques  Mastering LUT Application in Post-Production</u></a></li>
<li><a href="https://activate-lock.techidaily.com/3-easy-methods-to-unlock-icloud-locked-apple-iphone-11ipadipod-by-drfone-ios/"><u>3 Easy Methods to Unlock iCloud Locked Apple iPhone 11/iPad/iPod</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-realme-12plus-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Realme 12+ 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/bid-farewell-to-overwatch-crashes-a-complete-guide-to-update-graphics-drivers/"><u>Bid Farewell to Overwatch Crashes - A Complete Guide to Update Graphics Drivers</u></a></li>
<li><a href="https://games-able.techidaily.com/budget-gaming-winner-innocn-39g1-r/"><u>Budget Gaming Winner: InnoCN 39G1 R</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/cutting-edge-techniques-for-clear-zoom-captures-for-2024/"><u>Cutting Edge Techniques for Clear Zoom Captures for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/digiarty-software-winx-dvd-faq/"><u>Digiarty Software WinX DVD: よくある質問への解決策 - FAQガイド</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x802n-2400d-winning-the-battle-against-windows-update-failures-strategies-discussed/"><u>Error 0X802n-2400D: Winning the Battle Against Windows Update Failures [STRATEGIES DISCUSSED]</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-overcoming-bluetooth-offline-problems/"><u>Expert Advice on Overcoming 'Bluetooth Offline' Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-fixes-for-quick-recovery-from-windows-setup-errors/"><u>Fast Fixes for Quick Recovery From Windows Setup Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-the-missing-power-alert-a-simple-guide-for-immediate-relief/"><u>Fix the Missing Power Alert: A Simple Guide for Immediate Relief</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-cannot-reach-system-event-notification-service-error-message/"><u>Fixing 'Windows Cannot Reach System Event Notification Service' Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-delayed-typing-fast-and-easy-methods-for-a-responsive-keyboard/"><u>Fixing Delayed Typing - Fast & Easy Methods for a Responsive Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-skype-video-glitches-in-no-time-on-windows-11/"><u>Fixing Skype Video Glitches in No Time on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quiet-your-playstation-4-diagnosing-and-repairing-louder-than-usual-fan-sounds/"><u>How to Quiet Your PlayStation 4: Diagnosing and Repairing Louder-Than-Usual Fan Sounds</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-nokia-c22-drfone-by-drfone-virtual-android/"><u>In 2024, Can I use iTools gpx file to catch the rare Pokemon On Nokia C22 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-tecno-pop-7-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Tecno Pop 7 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-forgotten-pin-of-your-motorola-by-drfone-android/"><u>In 2024, How to Remove Forgotten PIN Of Your Motorola</u></a></li>
<li><a href="https://common-error.techidaily.com/instant-remedies-mend-your-google-hangouts-microphone-without-hassle/"><u>Instant Remedies: Mend Your Google Hangouts Microphone Without Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/navigated-through-stalled-nvidia-installation/"><u>Navigated Through Stalled NVIDIA Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-issues-is-the-service-down-and-what-can-you-do-about-it/"><u>Netflix Issues: Is the Service Down, and What Can You Do About It?</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-problems-with-starting-a-hosted-network-in-windows-11-solutions-and-guidance/"><u>Overcoming Problems with Starting a Hosted Network in Windows 11: Solutions and Guidance</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/pitch-perfect-productions-integrating-songs-in-tiktok-vids/"><u>Pitch-Perfect Productions  Integrating Songs in TikTok Vids</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-fixing-driver-failure-due-to-incorrect-user-preferences/"><u>Resolved Issue: Fixing 'Driver Failure' Due to Incorrect User Preferences</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-for-fixing-0x800705b4-error-in-your-windows-11-system/"><u>Resolved: Step-by-Step Guide for Fixing 0X800705b4 Error in Your Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-device-unavailable-error-code-24-on-windows-1187/"><u>Resolving 'Device Unavailable' Error Code 24 on Windows 11/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-connection-errors-in-geforce-experience-settings-retrieval/"><u>Resolving Connection Errors in GeForce Experience Settings Retrieval</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-elevated-cpu-consumption-in-system-idle-process-a-comprehensive-guide/"><u>Resolving Elevated CPU Consumption in System Idle Process: A Comprehensive Guide</u></a></li>
<li><a href="https://fix-guide.techidaily.com/samsung-galaxy-a14-4g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Samsung Galaxy A14 4G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guided-troubleshooting-windows-cannot-access-system-event-notifier-service/"><u>Solution Guided: Troubleshooting Windows Cannot Access System Event Notifier Service</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-to-reactivate-dimmed-or-dead-keylights-in-your-laptop/"><u>Solution Steps to Reactivate Dimmed or Dead Keylights in Your Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-struggling-with-an-inverted-laptop-screen-easy-fixes-inside/"><u>Stop Struggling with an Inverted Laptop Screen: Easy Fixes Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/system-compliant-with-all-configurations-yet-lacking-response/"><u>System Compliant with All Configurations Yet Lacking Response</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/transforming-cityscapes-into-sustainable-havens-of-life-for-2024/"><u>Transforming Cityscapes Into Sustainable Havens of Life for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-printing-your-pdf-discover-fast-solutions/"><u>Trouble Printing Your PDF? Discover Fast Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206026261-troubleshoot-the-windows-11-bluetooth-not-detected-problem-fast-solutions/"><u>Troubleshoot the Windows 11 Bluetooth Not Detected Problem - Fast Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-0x80072efd-error-in-windows-10-effortlessly/"><u>Troubleshooting and Fixing the 0X80072EFD Error in Windows 10 Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-audio-glitches-solving-crackling-sounds-in-windows-os/"><u>Troubleshooting Audio Glitches: Solving Crackling Sounds in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-missing-device-drivers-on-windows-7-installation/"><u>Troubleshooting Guide: Missing Device Drivers on Windows 7 Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-overcoming-no-pentouch-issues-on-your-monitor/"><u>Troubleshooting Guide: Overcoming 'No Pen/Touch' Issues on Your Monitor</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-windows-error-0x80n04cf/"><u>Troubleshooting Tips for Fixing Windows Error 0X80n04CF</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-apple-iphone-13-pro-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>Unlocking Apple iPhone 13 Pro Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-honor-magic-5-pro-drfone-by-drfone-virtual-android/"><u>Will iSpoofer update On Honor Magic 5 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-hello-isnt-available-on-this-device-on-windows-10-solved/"><u>Windows Hello Isn’t Available on This Device on Windows 10 [Solved]</u></a></li>
</ul></div>
