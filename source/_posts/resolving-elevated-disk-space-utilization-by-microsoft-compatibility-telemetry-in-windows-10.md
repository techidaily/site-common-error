---
title: Resolving Elevated Disk Space Utilization by Microsoft Compatibility Telemetry in Windows 10
date: 2024-08-15T11:09:51.218Z
updated: 2024-08-16T11:09:51.218Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Elevated Disk Space Utilization by Microsoft Compatibility Telemetry in Windows 10
excerpt: This Article Describes Resolving Elevated Disk Space Utilization by Microsoft Compatibility Telemetry in Windows 10
thumbnail: https://thmb.techidaily.com/4aac991e64509d68ac8489b0b42db25368d487df0c50d4cd60fbe09c3938eb3d.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

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

<!-- affiliate ads begin -->
<a href="https://boody-eco-wear.pxf.io/c/5597632/1567905/13846" target="_top" id="1567905"><img src="//a.impactradius-go.com/display-ad/13846-1567905" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1567905/13846" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)
<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)
<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
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

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-sony-bdp-s3700-overhaul-a-new-perspective-review/"><u>[New] In 2024, Sony BDP-S3700 Overhaul  A New Perspective Review</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-the-art-of-sharing-online-videos-from-youtube-to-facebook/"><u>[Updated] The Art of Sharing Online Videos From YouTube to Facebook</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-making-your-twitter-media-a-gif-masterpiece/"><u>2024 Approved  Making Your Twitter Media A GIF Masterpiece</u></a></li>
<li><a href="https://common-error.techidaily.com/adjusting-input-timings-for-compatibility-with-modern-displays/"><u>Adjusting Input Timings for Compatibility with Modern Displays</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-your-pc-gameplay-mastering-windows-11-performance-enhancements/"><u>Boost Your PC Gameplay: Mastering Windows 11 Performance Enhancements</u></a></li>
<li><a href="https://vp-tips.techidaily.com/computer-connection-5-strategies-to-move-files/"><u>Computer Connection  5 Strategies to Move Files</u></a></li>
<li><a href="https://extra-hints.techidaily.com/conquering-video-design-challenges-with-filmora-tips-for-2024/"><u>Conquering Video Design Challenges with Filmora Tips for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-rpc-communication-failures-in-windows-environments/"><u>Diagnosing and Repairing RPC Communication Failures in Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-solving-the-missing-sound-hardware-problem-in-windows-11/"><u>Diagnosing and Solving the Missing Sound Hardware Problem in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-your-computer-struggles-with-memory-in-windows-11/"><u>Effective Solutions for When Your Computer Struggles with Memory in Windows 11</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/efficient-snap-catch-strategies/"><u>Efficient Snap Catch Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-repairing-a-non-functional-shift-key-successful-strategies-inside/"><u>Expert Advice on Repairing a Non-Functional Shift Key: Successful Strategies Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-how-to-resolve-the-silent-gameplay-issue-in-forza-horizon-4/"><u>Fixed: How to Resolve the Silent Gameplay Issue in Forza Horizon 4</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-resolved-0xa00f4292-comprehensive-guide-to-solve-your-windows-camera-issue/"><u>Fixing the [Resolved] 0xA00F4292: Comprehensive Guide to Solve Your Windows Camera Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-resolve-microsoft-windows-camera-error-0xa00f4292/"><u>Fixing the Issue: Resolve Microsoft Windows Camera Error 0xA00F4292</u></a></li>
<li><a href="https://common-error.techidaily.com/how-a-graphics-driver-upgrade-restored-your-devices-miracast-capabilities-successfully/"><u>How a Graphics Driver Upgrade Restored Your Device's Miracast Capabilities Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-frequent-usb-connection-drops-and-keep-your-device-hooked-up/"><u>How to Address Frequent USB Connection Drops and Keep Your Device Hooked Up</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-the-problem-when-modules-are-not-detected/"><u>How To Correctly Address The Problem When Modules Are Not Detected</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-teredo-cannot-establish-connection-error/"><u>How to Fix 'Teredo Cannot Establish Connection' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-disappearing-mouse-cursor-back-on-windowshttps-10/"><u>How to Get Your Disappearing Mouse Cursor Back on [Windows](https://) 10</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-pause-life360-location-sharing-for-lava-yuva-2-drfone-by-drfone-virtual-android/"><u>How To Pause Life360 Location Sharing For Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-honor-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on Honor</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722981848864-hyperscape-pc-stability-issues-solutions-found/"><u>HyperScape PC Stability Issues - Solutions Found</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-review-of-minecraft-unparalleled-fun-for-players-everywhere/"><u>In-Depth Review of Minecraft: Unparalleled Fun for Players Everywhere</u></a></li>
<li><a href="https://common-error.techidaily.com/matching-cameras-to-work-with-windows-hello/"><u>Matching Cameras to Work with Windows Hello</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-free-to-edit-top-video-editing-software-without-watermarks-or-fees-for-2024/"><u>New Free to Edit Top Video Editing Software without Watermarks or Fees for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/one-click-solution-convert-facebook-vids-into-mp3s/"><u>One-Click Solution  Convert Facebook Vids Into MP3s</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/prime-titles-pro-elevate-your-youtube-game-for-2024/"><u>Prime Titles Pro  Elevate Your YouTube Game for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/quick-guide-lecture-capture-with-your-computer-mac/"><u>Quick Guide  Lecture Capture with Your Computer (Mac)</u></a></li>
<li><a href="https://common-error.techidaily.com/reboot-surprise-from-pcs-on-win11/"><u>Reboot Surprise From PCs on Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-league-of-legends-lagging-download-woes-quick-fix/"><u>Resolve Your League of Legends Lagging Download Woes - Quick Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208649952-resolving-the-mystery-of-gone-desktop-icons-on-windows-10-effective-methods-to-get-them-back/"><u>Resolving the Mystery of Gone Desktop Icons on Windows 10 - Effective Methods to Get Them Back</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-connection-issues-when-cant-reach-steam-game-servers-or-content/"><u>Solving Connection Issues: When Can't Reach Steam Game Servers or Content</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-overcoming-error-0x800f081f-during-net-framework-35-setup/"><u>Solving the Dilemma: Overcoming Error 0X800F081F During .NET Framework 3.5 Setup</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-download-sites-showcasing-exquisite-text-effects-for-2024/"><u>Top Download Sites Showcasing Exquisite Text Effects for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-scroll-problems-on-your-synaptics-trackpad-after-upgrading-to-windows-11/"><u>Troubleshooting Scroll Problems on Your Synaptics Trackpad After Upgrading to Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-solving-high-pitched-noises-in-your-pcs-integrated-speakers-windows-107/"><u>Ultimate Guide to Solving High-Pitched Noises in Your PC's Integrated Speakers (Windows 10/7)</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-your-computer-is-low-on-memory-solved/"><u>Windows 10 Your Computer Is Low on Memory [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-updates-successfully-restored-solutions-and-fixes/"><u>Windows Updates Successfully Restored: Solutions and Fixes</u></a></li>
</ul></div>
