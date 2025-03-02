---
title: How to Fix Excessive MsMpEngine.exe CPU Drain on Windows 11 [GUIDE]
date: 2025-03-01T07:43:28.251Z
updated: 2025-03-02T03:55:50.592Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Excessive MsMpEngine.exe CPU Drain on Windows 11 [GUIDE]
excerpt: This Article Describes How to Fix Excessive MsMpEngine.exe CPU Drain on Windows 11 [GUIDE]
thumbnail: https://thmb.techidaily.com/e6d973791325054ad0d7f0fcd99fd3ff0a56a44316e750df20403e0686bc2309.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

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
<li><a href="https://fox-blue.techidaily.com/new-maximize-your-snapshots-on-android-for-2024/"><u>[New] Maximize Your Snapshots on Android for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-visual-vault-unrivaled-in-capturing-and-saving-tweets-as-animations/"><u>[New] Visual Vault Unrivaled in Capturing & Saving Tweets as Animations</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-securing-your-social-media-visuals-instagram-edition/"><u>[Updated] 2024 Approved Securing Your Social Media Visuals Instagram Edition</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-ninja-legacy-continuation-game-roundup-like-the-japanese-samurai-epic-for-2024/"><u>[Updated] Ninja Legacy Continuation Game Roundup Like the Japanese Samurai Epic for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-ultimate-mic-selection-for-online-talent-for-2024/"><u>[Updated] Ultimate Mic Selection for Online Talent for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-svchostexe-a-guide-to-lowering-cpu-usage-on-windows-11/"><u>Dealing with svchost.exe: A Guide to Lowering CPU Usage on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/efficiently-handling-error-1er-1053-guaranteeing-timely-service-reaction-to-commands/"><u>Efficiently Handling Error 1Er 1053 - Guaranteeing Timely Service Reaction to Commands</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/essential-visionos-development-tips-apples-expert-recommendations-unveiled/"><u>Essential VisionOS Development Tips: Apple's Expert Recommendations Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-steelseries-arctis-5-microphone-issues-a-step-by-step-guide/"><u>How to Fix SteelSeries Arctis 5 Microphone Issues - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-recover-and-install-necessary-media-hardware-drivers-that-are-currently-missing-on-your-pc/"><u>How to Recover and Install Necessary Media Hardware Drivers that Are Currently Missing on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-mouse-malfunctions-heres-how-to-restore-functionality-and-beat-the-lag/"><u>Laptop Mouse Malfunctions? Here's How to Restore Functionality and Beat the Lag</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-art-of-resolving-endless-reboots-in-windows-11-effortlessly/"><u>Master the Art of Resolving Endless Reboots in Windows 11 Effortlessly</u></a></li>
<li><a href="https://extra-skills.techidaily.com/navigating-the-world-of-filmmaking-best-cameras-for-novices-for-2024/"><u>Navigating the World of Filmmaking Best Cameras for Novices for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/nba-2k21s-viridian-flaw-unveiled-solutions-inside/"><u>NBA 2K21's Viridian Flaw Unveiled - Solutions Inside!</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/new-in-2024-distracted-boyfriend-meme-generator/"><u>New In 2024, Distracted Boyfriend Meme Generator</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-overcoming-problems-with-microsoft-store-not-starting-up/"><u>Troubleshooting Steps for Overcoming Problems with Microsoft Store Not Starting Up</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-video-visionaries-finding-your-cms/"><u>Unison Video Visionaries Finding Your CMS</u></a></li>
<li><a href="https://common-error.techidaily.com/why-isnt-my-razer-keyboard-lit-steps-to-fix-the-led-issue-successfully/"><u>Why Isn't My Razer Keyboard Lit? Steps to Fix the LED Issue Successfully</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/dvdmov/"><u>ご利用いただきありがとう！無料DVDからMOVにする手順</u></a></li>
</ul></div>

