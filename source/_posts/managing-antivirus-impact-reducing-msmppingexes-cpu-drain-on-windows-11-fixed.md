---
title: "Managing Antivirus Impact: Reducing msmpping.exe's CPU Drain on Windows 11 [FIXED]"
date: 2024-08-15T10:58:33.403Z
updated: 2024-08-16T10:58:33.403Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Managing Antivirus Impact: Reducing msmpping.exe's CPU Drain on Windows 11 [FIXED]"
excerpt: "This Article Describes Managing Antivirus Impact: Reducing msmpping.exe's CPU Drain on Windows 11 [FIXED]"
thumbnail: https://thmb.techidaily.com/5f5f5b93e7d5296621d28cc46446de06ad76f2671bd83441f8c16419df01fcdb.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-leading-with-innovation-configuring-and-measuring-success-in-fb-instream-ads/"><u>[New] 2024 Approved  Leading with Innovation  Configuring & Measuring Success in FB Instream Ads</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-switching-names-on-google-meet-for-laptops-phones/"><u>[New] Switching Names on Google Meet for Laptops, Phones</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-audio-integration-into-visual-screens-via-apple/"><u>[Updated] 2024 Approved  Audio Integration Into Visual Screens via Apple</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-thorough-examination-of-hero5-video-content/"><u>2024 Approved  A Thorough Examination of Hero5 Video Content</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-flattening-lines-easy-curve-transformation/"><u>2024 Approved  Flattening Lines  Easy Curve Transformation</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-precision-speed-control-for-elite-pc-users/"><u>2024 Approved  Precision Speed Control for Elite PC Users</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-step-by-step-methods-for-iphone-screen-capture/"><u>2024 Approved  Step-by-Step Methods for iPhone Screen Capture</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/3-easy-ways-to-factory-reset-a-locked-iphone-12-without-itunes-drfone-by-drfone-ios/"><u>3 Easy Ways to Factory Reset a Locked iPhone 12 Without iTunes | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-not-working-on-windows-11-try-these-effortless-repairs/"><u>Bluetooth Not Working on Windows 11? Try These Effortless Repairs</u></a></li>
<li><a href="https://common-error.techidaily.com/clear-directions-to-repair-the-sudden-unexpected-error-in-windows-error-code-0xc00ebc9/"><u>Clear Directions to Repair the Sudden Unexpected Error in Windows (Error Code 0XC00ebc9)</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-hunt-for-windows-hello-camera/"><u>Compatibility Hunt for Windows Hello Camera</u></a></li>
<li><a href="https://hardware-help.techidaily.com/easy-tutorial-refresh-samsung-monitor-drivers-in-windows-pcs/"><u>Easy Tutorial: Refresh Samsung Monitor Drivers in Windows PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-repairing-unresponsive-keys-when-logging-into-windows/"><u>Effective Remedies: Repairing Unresponsive Keys When Logging Into Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206837616-fix-huion-graphics-tablet-issues-in-minutes-top-5-methods/"><u>Fix Huion Graphics Tablet Issues in Minutes - Top 5 Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211406665-fixing-the-crimson-display-issue-overcoming-the-notorious-red-screen-glitch/"><u>Fixing The Crimson Display Issue - Overcoming the Notorious Red Screen Glitch</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-update-errors-version-1607-what-you-need-to-know/"><u>Fixing Windows 11 Update Errors (Version 1607) – What You Need to Know</u></a></li>
<li><a href="https://common-error.techidaily.com/follicular-carcinoma-while-less-common-than-papillary-still-accounts-for-a-significant-percentage-of-all-thyroid-cancers/"><u>Follicular Carcinoma, While Less Common than Papillary, Still Accounts for a Significant Percentage of All Thyroid Cancers.</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-repairing-inoperative-scrolling-features-of-a-touchpad-in-windows-11/"><u>Guide to Repairing Inoperative Scrolling Features of a Touchpad in Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-sony-xperia-10-v-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Sony Xperia 10 V? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-call-of-duty-world-at-war-error-code-4220-instantly-step-by-step-guide/"><u>How to Correct Call of Duty: World at War Error Code 4220 Instantly - Step by Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-not-present-device-issue-on-windows-pc-error-code-e-24/"><u>How to Fix the ‘Not Present’ Device Issue on Windows PC (Error Code E-24)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206258902-how-to-securely-eliminate-critical-error-scams-in-google-chrome-expert-tips-inside/"><u>How to Securely Eliminate Critical Error SCAMs in Google Chrome – Expert Tips Inside!</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-most-known-ways-to-find-someone-on-tinder-for-samsung-galaxy-a15-4g-by-name-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Most-Known Ways to Find Someone on Tinder For Samsung Galaxy A15 4G by Name | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-how-to-bypass-icloud-lock-on-iphone-11-by-drfone-ios/"><u>In 2024, How to Bypass iCloud Lock on iPhone 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205003990-microsoft-wireless-display-adapter-wont-connect-on-windows-10-solved/"><u>Microsoft Wireless Display Adapter Won’t Connect on Windows 10 [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-epson-scanner-connectivity-problems/"><u>Overcoming Epson Scanner Connectivity Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-smartscreen-disconnect-errors-comprehensive-steps-to-restore-access/"><u>Overcoming Windows SmartScreen Disconnect Errors: Comprehensive Steps to Restore Access</u></a></li>
<li><a href="https://common-error.techidaily.com/recover-missing-taskbar-icon-shortcuts-in-windows-10-with-these-proven-tips/"><u>Recover Missing Taskbar Icon Shortcuts in Windows 10 With These Proven Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-pcs-silent-mode-addressing-lack-of-sound-in-windows-os/"><u>Resolve Your PC's Silent Mode: Addressing Lack of Sound in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-steams-missing-files-and-restore-full-access/"><u>Resolved: How to Fix Steam's Missing Files and Restore Full Access</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-usb-devices-not-working-on-latest-windows-operating-systems/"><u>Resolving Issues with USB Devices Not Working on Latest Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-wwe-2k-battlegrounds-directx-11-version-100-compatibility-issue/"><u>Resolving the WWE 2K Battlegrounds DirectX 11 Version 10.0 Compatibility Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/search-for-light-control-tool-in-windows/"><u>Search for Light Control Tool in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-of-malfunctioning-usb-input-devices-in-windows-7-systems/"><u>Solving the Dilemma of Malfunctioning USB Input Devices in Windows 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-of-forced-reboots-instead-of-properly-closing-on-windows-11-systems/"><u>Solving the Problem of Forced Reboots Instead of Properly Closing on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fixing-0x800f0831-with-windows-update-features/"><u>Step-by-Step Guide: Fixing 0X800F0831 with Windows Update Features</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reducing-high-cpu-consumption-from-windows-audio-device-isolation-discrepancy/"><u>Step-by-Step Guide: Reducing High CPU Consumption From Windows Audio Device Isolation Discrepancy</u></a></li>
<li><a href="https://common-error.techidaily.com/the-complete-guide-to-overcome-the-frustrating-windows-network-error-0x800704cf/"><u>The Complete Guide To Overcome The Frustrating Windows Network Error 0X800704CF</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202390863-third-monitor-not-detected-heres-the-real-fix/"><u>Third Monitor Not Detected? Here’s the Real Fix</u></a></li>
<li><a href="https://buynow-info.techidaily.com/top-5-factors-to-evaluate-when-selecting-your-perfect-fitness-tracker/"><u>Top 5 Factors to Evaluate When Selecting Your Perfect Fitness Tracker</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-apps-and-online-tools-to-track-itel-p40-phone-withwithout-imei-number-by-drfone-android/"><u>Top Apps and Online Tools To Track Itel P40 Phone With/Without IMEI Number</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-broken-key-on-your-keyboard-a-step-by-step-guide/"><u>Troubleshooting a Broken '@' Key on Your Keyboard - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-error-0x800f081f-in-microsoft-net-framework-35-installation-process/"><u>Troubleshooting Guide for Error 0X800F081F in Microsoft .NET Framework 3.5 Installation Process</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-shutdown-problems-in-windows-11-a-comprehensive-guide/"><u>Troubleshooting Shutdown Problems in Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211249748-troubleshooting-the-wi-fi-has-been-turned-off-error-solutions-proven-effective/"><u>Troubleshooting the 'Wi-Fi Has Been Turned Off' Error: Solutions Proven Effective!</u></a></li>
<li><a href="https://howto.techidaily.com/vivo-y100i-power-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Vivo Y100i Power 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
</ul></div>
