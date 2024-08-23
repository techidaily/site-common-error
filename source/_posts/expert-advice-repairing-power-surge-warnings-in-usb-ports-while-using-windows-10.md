---
title: "Expert Advice: Repairing 'Power Surge' Warnings in USB Ports While Using Windows 10"
date: 2024-08-22T19:30:34.283Z
updated: 2024-08-23T19:30:34.283Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Advice: Repairing 'Power Surge' Warnings in USB Ports While Using Windows 10"
excerpt: "This Article Describes Expert Advice: Repairing 'Power Surge' Warnings in USB Ports While Using Windows 10"
thumbnail: https://thmb.techidaily.com/e6889a658e4bba9c2827feba4ea063c236adc8db7e5b5caf8c7f574f84c4eaab.jpg
---

## Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10

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

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->
 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
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
<li><a href="https://common-error.techidaily.com/fixed-league-of-legends-slow-download-issue/"><u>[FIXED] League of Legends Slow Download Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-unusual-windows-stop-affects-cpu-usage/"><u>[FIXED] Unusual Windows Stop Affects CPU Usage</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-breaking-barriers-masterful-techniques-for-photosvideos-in-win11/"><u>[New] 2024 Approved  Breaking Barriers  Masterful Techniques for Photos/Videos in Win11</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-mastering-video-file-processing-movs-in-windows-11-edition/"><u>[New] 2024 Approved  Mastering Video File Processing  MOVs in Windows 11 Edition</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-maximize-monetization-the-step-by-step-for-youtube-profiles/"><u>[New] In 2024, Maximize Monetization  The Step-by-Step for YouTube Profiles</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-transforming-gifs-to-stickers-comprehensive-instruction-for-messaging-apps-for-2024/"><u>[New] Transforming GIFs to Stickers  Comprehensive Instruction for Messaging Apps for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unlocking-potential-angular-video-editing-on-your-android-device/"><u>[New] Unlocking Potential  Angular Video Editing on Your Android Device</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-the-directory-name-is-invalid-error/"><u>[SOLVED] The Directory Name Is Invalid Error</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-swiftly-flip-and-swivel-movies-for-a-better-viewing-experience-using-vlc/"><u>[Updated] Swiftly Flip and Swivel Movies for a Better Viewing Experience Using VLC</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-ultimate-guide-to-saving-your-iphone-7-display-for-2024/"><u>[Updated] The Ultimate Guide to Saving Your iPhone 7 Display for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-dive-deep-into-color-correction-top-11-resources/"><u>2024 Approved  Dive Deep Into Color Correction  Top 11 Resources</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-navigate-the-digital-realm-uploading-to-instagram-tv/"><u>2024 Approved  Navigate the Digital Realm  Uploading to Instagram TV</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-simplify-video-creation-making-engaging-youtube-trailers-in-filmora/"><u>2024 Approved  Simplify Video Creation  Making Engaging YouTube Trailers in Filmora</u></a></li>
<li><a href="https://common-error.techidaily.com/5-proven-fixes-for-restoring-touchscreen-responsiveness-in-windows-10/"><u>5 Proven Fixes for Restoring Touchscreen Responsiveness in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/et3rminate-all-unnecessary-applications-running-in-the-background-that-might-be-hogging-system-resources-which-could-potentially-help-with-driver-installati143/"><u>e.t3rminate All Unnecessary Applications Running in the Background that Might Be Hogging System Resources, Which Could Potentially Help with Driver Installation Issues.</u></a></li>
<li><a href="https://common-error.techidaily.com/effortlessly-resolving-the-windows-11-reboot-cycle-dilemma/"><u>Effortlessly Resolving the Windows 11 Reboot Cycle Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-repairing-error-0x802n4401c-that-hampers-update-process-on-windows-10-and-11-machines/"><u>Expert Advice for Repairing Error 0X802n4401C That Hampers Update Process on Windows 10 & 11 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-to-repairing-your-astro-a40-laptops-non-working-built-in-mic/"><u>Expert Guide to Repairing Your Astro A40 Laptop's Non-Working Built-In Mic</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-eradicating-google-chromes-unwanted-black-screens/"><u>Expert Guide: Eradicating Google Chrome's Unwanted Black Screens</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-resolving-the-dilemma-of-a-unresponsive-charging-ps4-gamepad/"><u>Expert Guide: Resolving the Dilemma of a Unresponsive Charging PS4 Gamepad</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-pairing-your-xbox-one-gamepad-when-sync-problems-arise/"><u>Expert Tips for Pairing Your Xbox One Gamepad When Sync Problems Arise</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-repairing-a-broken-internet-explorer-connection/"><u>Expert Tips for Repairing a Broken Internet Explorer Connection</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-and-enhance-your-laptops-touchpad-performance-with-these-simple-steps/"><u>Fix and Enhance Your Laptop's Touchpad Performance with These Simple Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-solutions-for-the-widevine-cdm-not-found-error-in-windows/"><u>Fixes and Solutions for the 'Widevine CDM Not Found' Error in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-persistent-reboot-loop-in-windows-11-and-10-systems/"><u>Fixes for Persistent Reboot Loop in Windows 11 & 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unseen-troubles-making-western-digitals-my-passport-ultra-visible-again-on-a-windows-pc/"><u>Fixing Unseen Troubles: Making Western Digital's My Passport Ultra Visible Again on a Windows PC</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-netflix-location-to-get-more-country-version-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>How to Change Netflix Location to Get More Country Version On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-no-audio-output-device-is-installed-error-in-windows-1011/"><u>How to Fix “No Audio Output Device Is Installed” Error in Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-0x80070490-windows-update-error-successfully/"><u>How to Fix the 0X80070490 Windows Update Error Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-there-was-an-error-setting-up-your-pc-bug-in-windows-11-fixed-now/"><u>How to Resolve 'There Was an Error Setting up Your PC' Bug in Windows 11 - Fixed Now</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-unrecognized-external-storage-a-guide-for-wd-my-passport-ultra-in-windows-1011/"><u>How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-accessing-premium-facebook-videos-offline/"><u>In 2024, Accessing Premium Facebook Videos Offline</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-what-are-location-permissions-life360-on-poco-c65-drfone-by-drfone-virtual-android/"><u>In 2024, What are Location Permissions Life360 On Poco C65? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205736440-internet-explorer-wont-open-solved/"><u>Internet Explorer Won't Open [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-stuck-on-white-screen-troubleshooting-steps-that-work/"><u>Laptop Stuck on White Screen? Troubleshooting Steps That Work!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-common-problems-for-seamless-minecraft-multiplayer-lan-play/"><u>Overcoming Common Problems for Seamless Minecraft Multiplayer LAN Play</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-startup-hurdles-a-comprehaster-guide-for-origin-game-launches/"><u>Overcoming Startup Hurdles - A Comprehaster Guide for Origin Game Launches</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-geforce-experience-launch-issues-a-step-by-step-guide/"><u>Resolving GeForce Experience Launch Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-printer-driver-issues-how-to-fix-cannot-find-appropriate-driver/"><u>Resolving Windows Printer Driver Issues: How to Fix 'Cannot Find Appropriate Driver'</u></a></li>
<li><a href="https://common-error.techidaily.com/speed-and-precision-master-windows-scrolls/"><u>Speed and Precision: Master Windows Scrolls</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-correcting-windows-update-failure-error-0x80070002/"><u>Step-by-Step Guide to Correcting Windows Update Failure (Error 0X80070002)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-your-mouses-right-click-in-windows-10/"><u>Step-by-Step Guide to Restoring Your Mouse's Right Click in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/taking-all-three-drugs-at-bedtime-would-not-minimize-interactions-but-could-lead-to-unnecessary-intake-of-diuril-and-potentially-exacerbate-its-side-effects86/"><u>Taking All Three Drugs at Bedtime Would Not Minimize Interactions but Could Lead to Unnecessary Intake of Diuril and Potentially Exacerbate Its Side Effects During Sleep</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205852310-troubleshoot-and-resolve-your-windows-0x80cuase-070643-updating-or-installing-problems-easily/"><u>Troubleshoot & Resolve Your Windows 0X80cuase 070643 Updating or Installing Problems Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-making-your-usb-flash-drive-detectable-again/"><u>Troubleshooting Guide: Making Your USB Flash Drive Detectable Again</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-issues-with-the-at-sign-on-your-device/"><u>Troubleshooting Steps: Resolving Issues with the At Sign on Your Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-overcome-the-windows-1-cuffed-at-99-error-easily/"><u>Troubleshooting: Overcome the 'Windows 1 Cuffed at 99%%' Error Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-correcting-the-sxs-configuration-flaw-in-windows-11-a-detailed-fix-guide/"><u>Understanding and Correcting the SxS Configuration Flaw in Windows 11: A Detailed Fix Guide</u></a></li>
</ul></div>
