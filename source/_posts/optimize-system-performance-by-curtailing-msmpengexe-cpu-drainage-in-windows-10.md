---
title: Optimize System Performance by Curtailing MsMpEng.exe CPU Drainage in Windows 10
date: 2025-02-27T06:29:46.581Z
updated: 2025-03-02T10:49:38.416Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Optimize System Performance by Curtailing MsMpEng.exe CPU Drainage in Windows 10
excerpt: This Article Describes Optimize System Performance by Curtailing MsMpEng.exe CPU Drainage in Windows 10
thumbnail: https://thmb.techidaily.com/faf305db1bff9ec7cfb8fafeb68d0a5e6478101d40a48c00d6fe1d681c9c048c.jpg
---

## Win 10 High CPU Drain by svchost.exe? Here’s How to Optimize It

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

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

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

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

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

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
<li><a href="https://youtube-data.techidaily.com/n-2024-surveying-youtube-interactions/"><u>[New] In 2024, Surveying YouTube Interactions</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-step-up-your-game-expert-tips-for-tiktok-editing/"><u>[New] Step Up Your Game Expert Tips for TikTok Editing</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-art-of-memetic-mastery/"><u>[New] The Art of Memetic Mastery</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-unleash-the-full-potential-of-your-hdr-images-with-lightroom/"><u>[New] Unleash the Full Potential of Your HDR Images with Lightroom</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-11-best-free-youtube-name-generators-you-should-try/"><u>[Updated] 2024 Approved 11 Best Free YouTube Name Generators You Should Try</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-the-challenge-of-svchostexe-netsvcs-strategies-to-curtail-its-significant-impact-on-internet-usage/"><u>Addressing the Challenge of svchost.exe (NETsvcs): Strategies to Curtail Its Significant Impact on Internet Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-file-explorer-hangs-tips-and-solutions-for-smoother-windows-experience/"><u>Bypassing File Explorer Hangs: Tips and Solutions for Smoother Windows Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-tips-and-tricks-ensuring-seamless-bluetooth-pairing-with-windows-11/"><u>Essential Tips and Tricks: Ensuring Seamless Bluetooth Pairing with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-on-enabling-windows-update-service-to-keep-your-pc-secure/"><u>Expert Tips on Enabling Windows Update Service to Keep Your PC Secure</u></a></li>
<li><a href="https://common-error.techidaily.com/from-freeze-to-flow-handling-and-correcting-twitch-error-code-4000-for-uninterrupted-streaming/"><u>From Freeze to Flow: Handling and Correcting Twitch Error Code 4000 for Uninterrupted Streaming</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restore-corrupt-system-files-on-your-windows-machine/"><u>Guide to Restore Corrupt System Files on Your Windows Machine</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-pc-screen-to-motorola-moto-g34-5g-phones-drfone-by-drfone-android/"><u>How to Mirror PC Screen to Motorola Moto G34 5G Phones? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-essential-knowledge-unmarked-photo-accumulation/"><u>In 2024, Essential Knowledge Unmarked Photo Accumulation</u></a></li>
<li><a href="https://common-error.techidaily.com/msvcr71dll-found-problem-solution-confirmed/"><u>MSVCR71.dll Found: Problem Solution Confirmed</u></a></li>
<li><a href="https://win-guides.techidaily.com/protect-your-data-secure-against-duplication-of-files-on-macs-external-hdd-with-6-proven-strategies/"><u>Protect Your Data: Secure Against Duplication of Files on Mac's External HDD with 6 Proven Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202809805-reviving-broken-arrow-buttons-expert-fixes-for-a-smooth-typing-experience/"><u>Reviving Broken Arrow Buttons - Expert Fixes for a Smooth Typing Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-functionality-of-your-embedded-webcam-on-pcs-running-windows/"><u>Step-by-Step Guide: Restoring Functionality of Your Embedded Webcam on PCs Running Windows</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/the-definitive-guide-to-capturing-your-streams-netflix-mac-edition-for-2024/"><u>The Definitive Guide to Capturing Your Streams Netflix Mac Edition for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/tiny-yet-spacious-the-innovative-apple-vision-pro-case-holds-its-own-with-minimal-dimensions/"><u>Tiny Yet Spacious: The Innovative Apple Vision Pro Case Holds Its Own with Minimal Dimensions</u></a></li>
</ul></div>

