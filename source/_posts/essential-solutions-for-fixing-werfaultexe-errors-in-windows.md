---
title: Essential Solutions for Fixing werfault.exe Errors in Windows
date: 2024-08-27T13:43:07.211Z
updated: 2024-08-28T13:43:07.211Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Essential Solutions for Fixing werfault.exe Errors in Windows
excerpt: This Article Describes Essential Solutions for Fixing werfault.exe Errors in Windows
thumbnail: https://thmb.techidaily.com/3e80e86fdb89e0d01e5a25ed6bf14d403b0478903fdc0c6822654e31324aff29.jpg
---

## Svchost.exe CPU Hogs in Windows 10? Discover Efficient Solutions for Immediate Relief

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->
2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
<!-- affiliate ads begin -->
<a href="https://ship7com.pxf.io/c/5597632/1509856/17634" target="_top" id="1509856"><img src="//a.impactradius-go.com/display-ad/17634-1509856" border="0" alt="" width="730" height="383"/></a>
<!-- affiliate ads end -->
## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-files.techidaily.com/new-backtracking-visual-vectors-techniques-for-tracking-originals-in-instagram-posts-for-2024/"><u>[New] Backtracking Visual Vectors  Techniques for Tracking Originals in Instagram Posts for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/erfecting-your-youtube-videos-for-igtv-integration/"><u>[New] Perfecting Your Youtube Videos for IGTV Integration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-selective-list-of-pro-gopro-add-ons/"><u>[New] Selective List of Pro-Gopro Add-Ons</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-when-your-mouse-cursor-goes-missing-in-windows-win-10-a-step-by-step-solution/"><u>[Troubleshooting] When Your Mouse Cursor Goes Missing in Windows (Win) [10]: A Step-by-Step Solution.</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-assembling-channel-summaries-that-attract-for-2024/"><u>[Updated] Assembling Channel Summaries That Attract for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-thaw-out-with-five-inviting-winterscapes-for-video-filming/"><u>[Updated] Thaw Out with Five Inviting Winterscapes for Video Filming</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-compilation-techniques-for-posting-youtube-videos-on-facebook/"><u>[Updated] The Ultimate Compilation  Techniques for Posting YouTube Videos on Facebook</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-leading-voice-modifying-apps-magical-calls-and-more/"><u>2024 Approved  Leading Voice-Modifying Apps  Magical Calls & More</u></a></li>
<li><a href="https://screen-capture.techidaily.com/50-greatest-virtual-scenes-for-online-meetings/"><u>50 Greatest Virtual Scenes for Online Meetings</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-0x80072efd-blues-easy-repairs-for-windows-10-users/"><u>Beat the 0X80072EFD Blues: Easy Repairs for Windows 10 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-aoc-computer-screens-not-working-properly-with-the-latest-windows-operating-system/"><u>Diagnosing and Repairing AOC Computer Screens Not Working Properly with the Latest Windows Operating System</u></a></li>
<li><a href="https://fox-access.techidaily.com/discover-the-craft-of-iphone-reflection-photography-for-2024/"><u>Discover the Craft of iPhone Reflection Photography for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-navigation-and-troubleshooting-for-windows-10s-file-explorer/"><u>Effortless Navigation and Troubleshooting for Windows 10'S File Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209210125-error-code-0x800f081f-on-your-mind-solving-the-dotnet-35-install-problems/"><u>Error Code 0X800F081F on Your Mind? Solving the DotNet 3.5 Install Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fec-codes-like-reed-solomon-can-correct-detected-errors-without-retransmission/"><u>FEC Codes Like Reed-Solomon Can Correct Detected Errors without Retransmission.</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-when-your-dell-camcorder-wont-function-with-windows-pc/"><u>Fixes for When Your Dell Camcorder Won't Function with Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-resolved-problem-windows-error-code-1067-premature-process-end/"><u>Fixing the Issue: Resolved Problem - Windows Error Code 1#067: Premature Process End</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-persistent-device-error-code-28-on-your-windows-machine-step-by-step-tutorial/"><u>Fixing the Persistent Device Error Code 28 on Your Windows Machine – Step-by-Step Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-past-errors-a-step-by-step-fix-for-a-non-responsive-microsoft-store/"><u>Getting Past Errors: A Step-by-Step Fix for a Non-Responsive Microsoft Store</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-and-regaining-your-steam-files-that-went-missing/"><u>Guide to Fixing and Regaining Your Steam Files That Went MISSING</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-fix-a-malfunctioning-mic-on-your-computer-system/"><u>How To Diagnose and Fix a Malfunctioning Mic on Your Computer System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-hub-port-power-spike-problem-successfully/"><u>How to Fix a Hub Port Power Spike Problem Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-rid-of-game-lags-in-pubg-expert-tips-and-tricks-uncovered/"><u>How to Get Rid of Game Lags in PUBG? Expert Tips & Tricks Uncovered!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-vivo-v27-phone-without-google-account-by-drfone-android/"><u>How to Unlock Vivo V27 Phone without Google Account?</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-audio-settings-restoring-volume-in-windows-11-made-easy/"><u>Mastering Audio Settings: Restoring Volume in Windows 11 Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-dysfunctional-function-keys-a-step-by-step-guide/"><u>Overcoming the Challenge of Dysfunctional Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-call-logs-from-oneplus-nord-3-5g-by-fonelab-android-recover-call-logs/"><u>Possible solutions to restore deleted call logs from OnePlus Nord 3 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-tips-for-speeding-up-your-pcs-initial-launch-sequence/"><u>Quick Tips for Speeding Up Your PC's Initial Launch Sequence</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-guide-to-resolving-the-persistent-update-service-failed-issue-error-0x80070652/"><u>Simple Guide to Resolving the Persistent 'Update Service Failed' Issue – Error 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-an-unsecured-network-wire-in-windows/"><u>Step-by-Step Guide: Repairing an Unsecured Network Wire in Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/tp-link-archer-c50-an-in-depth-look-at-performance-and-price/"><u>TP-Link Archer C50: An In-Depth Look at Performance and Price</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-airpods-pairing-problems-on-microsofts-latest-os-comprehensive-tips/"><u>Troubleshooting AirPods Pairing Problems on Microsoft's Latest OS - Comprehensive Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-screen-stuttering-and-flickering-problems-on-windows-11-devices/"><u>Troubleshooting Screen Stuttering and Flickering Problems on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-ethernet-connection-problems-in-windows-10-and-7/"><u>Troubleshooting Steps: Resolving Ethernet Connection Problems in Windows 10 and 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-10-combatting-high-disk-usage-from-microsoft-compatibility-telemetry/"><u>Troubleshooting Windows 10: Combatting High Disk Usage From Microsoft Compatibility Telemetry</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-xinput13dll-and-troubleshooting-its-absence/"><u>Understanding XINPUT1_3.dll & Troubleshooting Its Absence</u></a></li>
<li><a href="https://common-error.techidaily.com/unlit-display-random-outage/"><u>Unlit Display: Random Outage</u></a></li>
</ul></div>
