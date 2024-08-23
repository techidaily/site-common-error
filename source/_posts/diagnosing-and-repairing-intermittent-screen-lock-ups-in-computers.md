---
title: Diagnosing and Repairing Intermittent Screen Lock-Ups in Computers
date: 2024-08-22T19:28:20.442Z
updated: 2024-08-23T19:28:20.442Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Repairing Intermittent Screen Lock-Ups in Computers
excerpt: This Article Describes Diagnosing and Repairing Intermittent Screen Lock-Ups in Computers
thumbnail: https://thmb.techidaily.com/afa50b24e25ed08989c229ae73d3b233da6ab60b7cf21c80e9cb56c9f6856e1f.jpg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4600113&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/drm-removal-feature2.png" border="0">Any DRM Removal for Win：Remove DRM from Adobe, Kindle, Sony eReader, Kobo, etc, read your ebooks anywhere.</a>
<!-- affiliate ads end -->
**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  
**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

Restart your computer to see if the error has gone.

---

### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.
<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://extra-tips.techidaily.com/new-15-best-luts-to-enhance-gopro-action-camera-footage/"><u>[New] 15 Best LUTs To Enhance GoPro Action Camera Footage</u></a></li>
<li><a href="https://youtube-web.techidaily.com/024-approved-from-video-conference-to-youtube-broadcast-google-meet-explained/"><u>[New] 2024 Approved  From Video Conference to Youtube Broadcast  Google Meet Explained</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-best-top-xbox-hdds-your-ultimate-list/"><u>[New] In 2024, Best Top Xbox HDDs  Your Ultimate List</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-delve-into-all-shared-visuals-within-a-chat-on-messenger/"><u>[New] In 2024, Delve Into All Shared Visuals Within a Chat on Messenger</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-scrutinizing-vlc-for-video-capturing-for-2024/"><u>[New] Scrutinizing VLC for Video Capturing for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-unlocking-the-potential-of-onestream-live-streaming/"><u>[New] Unlocking the Potential of OneStream Live Streaming</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-windows-11-cpu-spikes-stopped-by-interrupts/"><u>[RESOLVED] Windows 11 CPU Spikes Stopped by Interrupts</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-enhancing-teamimage-blurring-backgrounds-on-microsoft-teams/"><u>[Updated] 2024 Approved  Enhancing TeamImage  Blurring Backgrounds on Microsoft Teams</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-perfecting-highlight-covers-an-in-depth-insta-photography-guide/"><u>[Updated] 2024 Approved  Perfecting Highlight Covers  An In-Depth Insta Photography Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-delving-into-asmrs-potential-upsides/"><u>[Updated] In 2024, Delving Into ASMR's Potential Upsides</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-strategic-campaign-planning-for-health-brands/"><u>[Updated] Strategic Campaign Planning for Health Brands</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-symphony-of-microphones-on-a-mac/"><u>2024 Approved  Symphony of Microphones on a Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/a-developers-handbook-on-fixing-opengl-glexttexturecompression-format-issue-error-1281-a-complete-solution/"><u>A Developer's Handbook on Fixing OpenGL GL_EXT_texture_compression Format Issue (Error 1281): A Complete Solution</u></a></li>
<li><a href="https://extra-information.techidaily.com/advancing-beyond-vp9-a-look-at-av1/"><u>Advancing Beyond VP9  A Look at AV1</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-hp-deskjet-d1nker-printing-software-compatibility-with-windows-7-10/"><u>Comprehensive Fixes for HP Deskjet D1nker Printing Software Compatibility with Windows 7-10</u></a></li>
<li><a href="https://common-error.techidaily.com/decided-no-endorsement-of-opengl-by-drivers/"><u>Decided: No Endorsement of OpenGL by Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/execution-barred/"><u>Execution Barred</u></a></li>
<li><a href="https://facebook.techidaily.com/facebook-unveils-meta-a-revolution-in-social-media-branding/"><u>Facebook Unveils Meta: A Revolution in Social Media Branding</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-a-non-responsive-huion-pen-in-minutes-with-these-5-techniques/"><u>Fix a Non-Responsive Huion Pen in Minutes with These 5 Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-it-expert-tips-for-escaping-stuck-windows-setup-phase/"><u>Fixed It! Expert Tips for Escaping Stuck Windows Setup Phase</u></a></li>
<li><a href="https://common-error.techidaily.com/from-inactive-to-active-logitech-restoration/"><u>From Inactive to Active: Logitech Restoration</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-check-if-your-vivo-v30-lite-5g-is-unlocked-by-drfone-android/"><u>How To Check if Your Vivo V30 Lite 5G Is Unlocked</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-apple-iphone-15-could-not-be-activatedreached-issue-by-drfone-ios/"><u>How To Fix Apple iPhone 15 Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-opengl-error-1281-solved/"><u>How to Fix OpenGL Error 1281 [Solved]</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-mend-synapse-glitches-on-w11-and-w10/"><u>How to Mend Synapse Glitches on W11 and W10</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-samsung-galaxy-z-fold-5-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Samsung Galaxy Z Fold 5 Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-how-to-guide-on-bypassing-the-apple-iphone-15-pro-max-icloud-lock-by-drfone-ios/"><u>In 2024, A How-To Guide on Bypassing the Apple iPhone 15 Pro Max iCloud Lock</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-musical-masterclasses-in-15-short-video-formats-on-youtube/"><u>In 2024, Musical Masterclasses in 15 Short Video Formats on YouTube</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-samsung-galaxy-xcover-7-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Samsung Galaxy XCover 7 Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unravel-costs-liberating-your-vob-experience-pcmac/"><u>In 2024, Unravel Costs  Liberating Your VOB Experience (PC/Mac)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202941627-internet-explorer-errors-heres-how-to-get-it-running-smoothly-again/"><u>Internet Explorer Errors? Here’s How to Get It Running Smoothly Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-techniques-resolving-werfaultexe-windows-hiccups-5plus-tips/"><u>Master the Techniques: Resolving werFault.exe Windows Hiccups (5+ Tips)</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-troubleshooting-seamless-bluetooth-pairings-with-your-windows-10/"><u>Mastering the Art of Troubleshooting: Seamless Bluetooth Pairings with Your Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-effortless-solutions-for-broken-overwatch-audio-calls/"><u>Mastering the Fix: Effortless Solutions for Broken Overwatch Audio Calls</u></a></li>
<li><a href="https://common-error.techidaily.com/optimal-setup-guide-why-you-must-have-a-gpu-with-d3d11-support-to-run-the-engine-without-issues/"><u>Optimal Setup Guide: Why You Must Have a GPU with D3D11 Support to Run the Engine without Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-voice-chat-hurdles-in-overwatch-simple-solutions-inside/"><u>Overcoming Voice Chat Hurdles in Overwatch - Simple Solutions Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/patch-and-enhance-correctly-install-the-overlooked-key-media-controller-driver-on-your-machine/"><u>Patch and Enhance: Correctly Install the Overlooked Key Media Controller Driver on Your Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-the-fixes-for-the-windows-11-critical-error-displayed-on-a-red-screen/"><u>Resolved: The Fixes for the Windows 11 Critical Error Displayed on a Red Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-setbacks-with-the-windows-10-april-2020-update-version-1903-insights/"><u>Resolving Setbacks with the Windows 10 April 2020 Update: Version 1903 Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/silent-blackout-visual-quirk/"><u>Silent Blackout: Visual Quirk</u></a></li>
<li><a href="https://common-error.techidaily.com/smooth-sailing-again-overcoming-google-chromes-not-responding-hurdle/"><u>Smooth Sailing Again! Overcoming Google Chrome's 'Not Responding' Hurdle</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-compatibility-making-your-wacom-pen-functional-again-on-windows-11-and-10/"><u>Solving Compatibility: Making Your Wacom Pen Functional Again on Windows 11 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-symbol-issue-a-step-by-step-guide/"><u>Solving the '@' Symbol Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-enabling-bluetooth-features-in-windows-7/"><u>Step-by-Step Instructions: Enabling Bluetooth Features in Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-the-d3derr-not-available-windows-error/"><u>Step-by-Step Solution to the D3DERR Not Available Windows Error</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-worrying-about-your-huion-device-discover-these-5-quick-pen-repair-tips/"><u>Stop Worrying About Your Huion Device; Discover These 5 Quick Pen Repair Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/the-easy-way-out-expert-advice-on-mending-defective-usb-charging-points/"><u>The Easy Way Out: Expert Advice on Mending Defective USB Charging Points</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-gpu-consumption-by-the-dwm-on-windows-11/"><u>Top 5 Solutions for Reducing GPU Consumption by the DWM on Windows 11</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/transform-your-videos-with-pro-grade-jump-cuts-in-fcpx-for-2024/"><u>Transform Your Videos with Pro-Grade Jump Cuts in FCPX for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-non-supported-display-reaction-times-on-your-device/"><u>Troubleshooting Steps for Non-Supported Display Reaction Times on Your Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-bluetooth-device-shows-connection-status-paired-yet-non-responsive-in-windows-10/"><u>Troubleshooting: Bluetooth Device Shows Connection Status 'Paired' Yet Non-Responsive in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-repair-guide-getting-your-xbox-one-controller-xp-back-online/"><u>Ultimate Repair Guide: Getting Your Xbox One Controller (XP) Back Online</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-the-role-of-svchostexe-in-windows-netsvcs-explained-and-solutions-for-excessive-network-usage/"><u>Understanding the Role of svchost.exe in Windows: Netsvcs Explained & Solutions for Excessive Network Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-pc-restart-issues-comprehensive-solution-to-avoid-reset-problems/"><u>Windows 11 PC Restart Issues – Comprehensive Solution to Avoid Reset Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-over-the-system-restore-failed-error-code-0x80-on-windows-11-with-this-ultimate-fix/"><u>Winning Over the 'System Restore Failed: Error Code 0X80' On Windows 11 with This Ultimate Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/1723200620079-winning-the-battle-against-msmpengexe-reducing-cpu-usage-in-windows-11-effective-strategies-inside/"><u>Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside</u></a></li>
</ul></div>
