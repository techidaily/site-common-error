---
title: "Missing DLL: MSVCR120 on Win11/10"
date: 2024-08-27T13:54:07.220Z
updated: 2024-08-28T13:54:07.220Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Missing DLL: MSVCR120 on Win11/10"
excerpt: "This Article Describes Missing DLL: MSVCR120 on Win11/10"
thumbnail: https://thmb.techidaily.com/dc4cacbc8b493fc632f86712912ebd59bbc9ecbefdaf01df729929788c56ed4e.jpeg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

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
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BBusiness%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/business-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
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
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<li><a href="https://vp-tips.techidaily.com/new-in-2024-mastering-gopro-timelapse-a-step-by-step-guide/"><u>[New] In 2024, Mastering GoPro Timelapse  A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-lightened-transition-tactics/"><u>[New] Lightened Transition Tactics</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-advanced-tips-for-organizing-your-youtube-clip-structure/"><u>[Updated] Advanced Tips for Organizing Your YouTube Clip Structure</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-efficiently-capture-and-record-your-idevice-screen/"><u>[Updated] In 2024, Efficiently Capture and Record Your iDevice Screen</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-in-depth-samsung-picture-editor-features-and-proscons/"><u>[Updated] In-Depth Samsung Picture Editor  Features and Pros/Cons</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/2024-approved-a-teachers-guide-to-enhancing-learning-through-youtube-videos/"><u>2024 Approved  A Teacher's Guide to Enhancing Learning Through YouTube Videos</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-the-comprehensive-manual-for-effective-morphvox-voice-changes/"><u>2024 Approved  The Comprehensive Manual for Effective MorphVOX Voice Changes</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-top-360-live-streaming-cameras-for-youtube-and-facebook/"><u>2024 Approved  Top 360 Live Streaming Cameras for YouTube and Facebook</u></a></li>
<li><a href="https://screen-capture.techidaily.com/best-practices-for-high-quality-remote-podcasts-for-2024/"><u>Best Practices for High-Quality Remote Podcasts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/breeze-through-blockages-repair-techniques-for-stalled-0-windows-updates/"><u>Breeze Through Blockages: Repair Techniques for Stalled 0%% Windows Updates</u></a></li>
<li><a href="https://unlock-android.techidaily.com/complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-tecno-camon-20-pro-5g-by-drfone-android/"><u>Complete Review & Guide to Techeligible FRP Bypass and More For Tecno Camon 20 Pro 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/cracking-down-error-1067-the-process-that-stopped-in-windows-explained-and-fixed/"><u>Cracking Down Error 1067: The Process that Stopped in Windows Explained & Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-restarting-your-failed-diagnostics-service-quick-fixes-applied/"><u>Diagnosing and Restarting Your Failed Diagnostics Service - Quick Fixes Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-memory-integrity-failures-in-ftdis-sys-caused-by-driver-inefficiencies/"><u>Diagnosing Memory Integrity Failures in FTDIS Sys Caused by Driver Inefficiencies</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-to-overcome-incomplete-windows-updates/"><u>Easy Solutions to Overcome Incomplete Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-troubleshooting-steps-for-repairing-your-lenovos-malfunctioning-fingerprint-scanner/"><u>Easy Troubleshooting Steps for Repairing Your Lenovo's Malfunctioning Fingerprint Scanner</u></a></li>
<li><a href="https://fox-glue.techidaily.com/freelancers-corner-yearly-best-free-text-files-for-2024/"><u>Freelancers’ Corner  Yearly Best FREE Text Files for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/freeze-the-fun-screenshots-and-recording-in-win10-for-2024/"><u>Freeze the Fun  Screenshots & Recording in Win10 for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208725532-google-chrome-blackout-heres-how-to-restore-your-browsers-display/"><u>Google Chrome Blackout? Here's How to Restore Your Browser's Display!</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/harmonizing-tracks-in-youtube-music/"><u>Harmonizing Tracks in YouTube Music</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-registry-error-while-accessing-images-on-your-windows-10-pc/"><u>How to Fix 'Registry Error' While Accessing Images on Your Windows 10 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204018801-how-to-fix-the-missing-device-warning-in-icu-software-expert-solutions/"><u>How to Fix the Missing Device Warning in ICU Software - Expert Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-windows-10-when-your-space-bar-doesnt-work/"><u>How to Repair Windows 10 When Your Space Bar Doesn't Work</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-your-astro-a40-mic-when-it-stops-working/"><u>How to Repair Your Astro A40 Mic When It Stops Working</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-honor-v-purse-drfone-by-drfone-android/"><u>How to Screen Mirroring Honor V Purse? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-teleport-your-gps-location-on-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>How To Teleport Your GPS Location On Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/identifying-and-rectifying-self-starting-behavior-on-your-windows-10-device/"><u>Identifying & Rectifying Self-Starting Behavior on Your Windows 10 Device</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-oppo-a58-4g-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Oppo A58 4G Phone?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-nubia-red-magic-8s-pro-bootloader-easily-by-drfone-android/"><u>In 2024, How to Unlock Nubia Red Magic 8S Pro Bootloader Easily</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-one-step-shot-simplify-podcast-streaming/"><u>In 2024, One Step Shot  Simplify Podcast Streaming</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-pedagogic-pros-the-finest-lecture-recording-devices-for-instructors/"><u>In 2024, Pedagogic Pros  The Finest Lecture Recording Devices for Instructors</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-step-by-step-tutorial-how-to-bypass-samsung-galaxy-a34-5g-frp-by-drfone-android/"><u>In 2024, Step-by-Step Tutorial How To Bypass Samsung Galaxy A34 5G FRP</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/new-easy-tutorial-how-to-record-and-send-talking-emoji-for-iphone-for-2024/"><u>New Easy Tutorial How to Record and Send Talking Emoji for iPhone for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/no-more-freezing-expert-tips-for-troubleshooting-nier-automata-pc-bugs/"><u>No More Freezing: Expert Tips for Troubleshooting Nier: Automata PC Bugs</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-hp-laptops-camera-wont-work-with-windows-11/"><u>Quick Fixes for When Your HP Laptop's Camera Won't Work with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-common-cheats-in-apex-legends-easy-anti-cheat-system/"><u>Resolved! Troubleshooting Common Cheats in Apex Legends' Easy Anti-Cheat System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-problem-occurred-while-rebooting-error-in-windows-10/"><u>Resolving the 'Problem Occurred While Rebooting' Error in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204570284-smooth-gameplay-on-demand-no-trouble/"><u>Smooth Gameplay on Demand, No Trouble</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-when-numbers-wont-press-on-your-keyboard/"><u>Solution Guide: When Numbers Won't Press on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-usb-ports-failure-issues-for-users-of-windows-11/"><u>Solving 'USB Ports Failure' Issues for Users of Windows 11</u></a></li>
<li><a href="https://driver-download.techidaily.com/speedy-download-of-hp-stream-driver-packages-user-friendly-processes-guaranteed/"><u>Speedy Download of | HP Stream Driver Packages | User-Friendly Processes Guaranteed</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-the-loading-player-error-on-your-windows-pc-now-available/"><u>Step-by-Step Guide to Fix the Loading Player Error on Your Windows PC - Now Available!</u></a></li>
<li><a href="https://common-error.techidaily.com/taming-wudfhostexe-strategies-for-optimizing-your-pcs-performance-on-windows-am/"><u>Taming wudfhost.exe: Strategies for Optimizing Your PC's Performance on Windows Am</u></a></li>
<li><a href="https://common-error.techidaily.com/the-role-of-msda80dll-in-your-system-do-you-need-to-retain-it/"><u>The Role of MSDA80.DLL in Your System - Do You Need to Retain It?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-flash-content-failures-in-google-chrome-a-comprehensive-guide/"><u>Troubleshooting Flash Content Failures in Google Chrome: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-the-semaphore-timed-out-error-code-0x80070079/"><u>Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210105917-troubleshooting-missing-desktop-icons-on-windows-11-solved/"><u>Troubleshooting Missing Desktop Icons on Windows 11 – Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-failed-windows-11-version-1607-update-issues/"><u>Troubleshooting Steps for Failed Windows 11 (Version 1607) Update Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-restoring-access-to-remotely-located-servers/"><u>Troubleshooting Tips for Restoring Access to Remotely Located Servers</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-win32-kernal-termination-error-0xc0000005-on-your-pc/"><u>Ultimate Guide: Resolving the Win32 Kernal Termination Error (0xC0000005) on Your PC</u></a></li>
</ul></div>
