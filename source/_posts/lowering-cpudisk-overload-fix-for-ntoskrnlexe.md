---
title: "Lowering CPU/Disk Overload: Fix for Ntoskrnl.exe"
date: 2024-08-22T19:29:58.711Z
updated: 2024-08-23T19:29:58.711Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Lowering CPU/Disk Overload: Fix for Ntoskrnl.exe"
excerpt: "This Article Describes Lowering CPU/Disk Overload: Fix for Ntoskrnl.exe"
thumbnail: https://thmb.techidaily.com/91aa12f63404e244829a566c9da569c7d4c3ec60cf75cf3cc9677e68e8f64011.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082541/7443" target="_top" id="2082541"><img src="//a.impactradius-go.com/display-ad/7443-2082541" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
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

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
 4) Restart your computer after this.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-essential-techniques-for-youtube-end-screen-designs/"><u>[New] In 2024, Essential Techniques for YouTube End Screen Designs</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-insight-into-top-10-youtube-mp3-downloader-apps/"><u>[New] In 2024, Insight Into Top 10 YouTube MP3 Downloader Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-navigating-the-social-maze-tweets-plus-tumble-videos/"><u>[New] In 2024, Navigating the Social Maze  Tweets + Tumble Videos</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-video-upload-insights-aspect-ratio-for-twitters-platform-for-2024/"><u>[New] Video Upload Insights  Aspect Ratio for Twitter's Platform for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-capturing-your-screen-on-pc-free-ways-to-do-it/"><u>2024 Approved  Capturing Your Screen on PC  Free Ways to Do It</u></a></li>
<li><a href="https://tech-haven.techidaily.com/boost-your-efficiency-5-innovative-gpt-tips-for-human-resources/"><u>Boost Your Efficiency: 5 Innovative GPT Tips for Human Resources</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-werfaultexe-hurdle-tips-and-tricks-for-stable-windows/"><u>Bypassing the werFault.exe Hurdle: Tips & Tricks for Stable Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-dead-dns-servers-here-are-4-effortless-fixes/"><u>Dealing with Dead DNS Servers? Here Are 4 Effortless Fixes!</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-dealing-with-disruptions-in-hamachi-virtual-private-network-services/"><u>Effective Fixes: Dealing with Disruptions in Hamachi Virtual Private Network Services</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-vac-was-unable-to-verify-the-game-session/"><u>Fix: VAC Was Unable to Verify the Game Session</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-windows-resource-protection-could-not-start-the-repair-service-sfc-error/"><u>Fixed: Windows Resource Protection Could Not Start the Repair Service - Sfc Error</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-why-your-wireless-mouse-fails-in-windows-11-and-10/"><u>Fixing the Issue: Why Your Wireless Mouse Fails in Windows 11 & 10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-flat-to-fantastic-3d-text-creation-tips/"><u>From Flat to Fantastic  3D Text Creation Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-camera-back-to-work-on-surface-book-pro-4-after-upgrading-to-windows-11-a-solution-guide/"><u>Getting Your Camera Back to Work on Surface Book (Pro 4) After Upgrading to Windows 11 - A Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/google-chrome-crash-course-overcoming-the-not-responding-dilemma/"><u>Google Chrome Crash Course: Overcoming the Not Responding Dilemma</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/handling-mfc42ddll-absence-problems-expert-tips-and-solutions-for-windows-users/"><u>Handling mfc42d.dll Absence Problems - Expert Tips and Solutions for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-bypass-the-configuring-windows-stuck-phase-and-continue-setup/"><u>How to Bypass the 'Configuring Windows' Stuck Phase and Continue Setup</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-apple-iphone-12-to-factory-settings-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Reset Apple iPhone 12 to Factory Settings? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-solutions-for-printer-error-on-your-pdf-documents/"><u>Immediate Solutions for Printer Error on Your PDF Documents</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-4-ways-to-unlock-iphone-6s-to-use-usb-accessories-without-passcode-by-drfone-ios/"><u>In 2024, 4 Ways to Unlock iPhone 6s to Use USB Accessories Without Passcode</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-spotify-promotion-strategies-for-effective-ads/"><u>Mastering Spotify Promotion  Strategies for Effective Ads</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211344252-miracast-troubles-correct-your-graphics-driver-for-seamless-screen-mirroring/"><u>Miracast Troubles? Correct Your Graphics Driver for Seamless Screen Mirroring!</u></a></li>
<li><a href="https://common-error.techidaily.com/operation-denied-execution-stopped/"><u>Operation Denied: Execution Stopped</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-update-error-0x80070002-effective-fixes-for-hassle-free-updating/"><u>Overcome Windows Update Error 0X80070002: Effective Fixes for Hassle-Free Updating</u></a></li>
<li><a href="https://common-error.techidaily.com/shockwave-flash-issues-in-google-chrome-follow-our-updated-solution-guide/"><u>Shockwave Flash Issues in Google Chrome? Follow Our Updated Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-of-a-vanished-bluetooth-icon-on-windows-10-machines-expert-tips-and-tricks/"><u>Solving the Mystery of a Vanished Bluetooth Icon on Windows 10 Machines: Expert Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fixing-lenovos-unresponsive-fingerprint-reader-with-minimal-hassle/"><u>Step-by-Step Guide: Fixing Lenovo's Unresponsive Fingerprint Reader with Minimal Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-lenovo-special-characters-key-with-ease/"><u>Troubleshoot Lenovo Special Characters Key with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solutions-for-svchostexe-high-resource-consumption-on-windows-11/"><u>Troubleshooting and Solutions for svchost.exe High Resource Consumption on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-driverpowerstateerror-on-your-computer/"><u>Troubleshooting DRIVER_POWER_STATE_ERROR on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-overcoming-update-failure-messages-in-warframe/"><u>Troubleshooting Guide: Overcoming 'Update Failure' Messages in Warframe</u></a></li>
<li><a href="https://common-error.techidaily.com/unplugged-and-confused-heres-why-your-laptop-turned-off-randomly-solved/"><u>Unplugged and Confused? Here's Why Your Laptop Turned Off Randomly (Solved)</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-the-ultimate-guide-to-video-editing-splitting-videos-in-windows-live-movie-maker-for-2024/"><u>Updated The Ultimate Guide to Video Editing Splitting Videos in Windows Live Movie Maker for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-troubleshooting-harnessing-the-power-of-sfc-and-dism-utilities/"><u>Windows 10 Troubleshooting: Harnessing the Power of SFC and DISM Utilities</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-solving-problems-with-your-spacebar-not-working-properly/"><u>Windows 11: Solving Problems with Your Spacebar Not Working Properly</u></a></li>
</ul></div>
