---
title: Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved
date: 2024-12-27T23:21:10.537Z
updated: 2025-01-03T23:23:17.291Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved
excerpt: This Article Describes Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved
thumbnail: https://thmb.techidaily.com/d594c9f97f5c7acf04e5131f6f5a4cdb7d19c04f53e109e380d118d9fb18d3fe.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/f3PFn06LijE?si=zHrmlTOzrKxXe-k4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wVVp-GggK3U?si=RJb1ClNQV7GjTu_3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://common-error.techidaily.com/solved-failed-to-load-hardware-monitor-driver/"><u>[SOLVED] Failed to Load Hardware Monitor Driver</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-mastering-lightroom-crafting-breathtaking-hdr-photos/"><u>[Updated] 2024 Approved Mastering Lightroom Crafting Breathtaking HDR Photos</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-resolve-androidios-issues-with-fb-video-playback/"><u>[Updated] Resolve Android/iOS Issues with FB Video Playback</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-the-ultimate-composition-crafting-memorable-podcast-covers/"><u>[Updated] The Ultimate Composition Crafting Memorable Podcast Covers</u></a></li>
<li><a href="https://win-web3.techidaily.com/1-quick-tips-how-to-restore-lost-data-on-your-flash-drive-without-spending-a-penny/"><u>1. Quick Tips: How To Restore Lost Data On Your Flash Drive Without Spending A Penny</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-discovering-the-best-in-class-9-microphone-recorders-reviewed/"><u>2024 Approved Discovering the Best in Class 9 Microphone Recorders Reviewed</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-correcting-your-screens-no-signal-problem-from-diagnosis-to-fix/"><u>Comprehensive Guide to Correcting Your Screen's 'No Signal' Problem: From Diagnosis to Fix</u></a></li>
<li><a href="https://some-tips.techidaily.com/discover-the-premier-offers-for-household-energy-backup-systems-in-december-2022-insider-picks-by-zdnet/"><u>Discover the Premier Offers for Household Energy Backup Systems in December 2022 - Insider Picks by ZDNet</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-organization-with-windows-11-file-explorer-a-step-by-step-guide/"><u>Effortless Organization with Windows 11 File Explorer - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-0x887a0006-fast-and-simple-troubleshooting-steps/"><u>Error Code 0X887A0006: Fast and Simple Troubleshooting Steps!</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-dealing-with-the-binkw32dll-not-present-problem/"><u>Expert Advice for Dealing with the Binkw32.dll Not Present Problem</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/google-pixel-watch-3-exclusive-breaking-down-rumors-on-pricing-structure-release-windows-and-tech-specs/"><u>Google Pixel Watch 3 Exclusive – Breaking Down Rumors on Pricing Structure, Release Windows, and Tech Specs</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-honor-90-lite-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Honor 90 Lite Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-tackle-unavailable-previews-on-windows-outlook-email/"><u>How to Tackle Unavailable Previews on Windows Outlook Email</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-usb-recognition-issues-in-windows-11-no-more-port-reset-failures/"><u>Mastering USB Recognition Issues in Windows 11: No More Port Reset Failures</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/streamlining-cross-platform-communication-via-skype-chat-rooms/"><u>Streamlining Cross-Platform Communication via Skype Chat Rooms</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-installing-latest-windows-10-build-1607-common-issues-and-fixes/"><u>Trouble Installing Latest Windows 10 Build 1607: Common Issues and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-successfully-turning-on-bluetooth-in-windows-11-and-10/"><u>Troubleshooting Tips: Successfully Turning On Bluetooth in Windows 11 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-do-when-you-encounter-a-monitor-lacking-hdcp-capability/"><u>What to Do When You Encounter a Monitor Lacking HDCP Capability</u></a></li>
</ul></div>

