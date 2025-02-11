---
title: Snoozing Systems, No Wake Triggered by Windows 10/11
date: 2025-02-06T07:16:58.815Z
updated: 2025-02-11T01:34:04.477Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Snoozing Systems, No Wake Triggered by Windows 10/11
excerpt: This Article Describes Snoozing Systems, No Wake Triggered by Windows 10/11
thumbnail: https://thmb.techidaily.com/6d6cac7e56858e74f7b2bccf55f62023ebda6695ca7ede5596cad05ed3aac833.jpg
---

## Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eu4vwlZcMvM?si=4vEczfVU4BUUFP-t" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nl0Z0eth1u4?si=0eecOBNfc--51AJO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yDuvbv0QOYI?si=byottcEM_Rrvi4EL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-posts.techidaily.com/updated-master-the-art-of-moving-shots-a-handbook-for-hero5-time-lapse-photography/"><u>[Updated] Master the Art of Moving Shots A Handbook for Hero5 Time-Lapse Photography</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unleashing-brand-potential-with-essential-phrases/"><u>2024 Approved Unleashing Brand Potential with Essential Phrases</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-unraveling-vrs-impact-on-digital-cinema/"><u>2024 Approved Unraveling VR's Impact on Digital Cinema</u></a></li>
<li><a href="https://win11.techidaily.com/decoding-and-defeating-win11-webcam-malfunction-error-a00f4289/"><u>Decoding and Defeating Win11 Webcam Malfunction - Error A00F4289</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-to-address-windows-11-microphone-malfunctions-expert-advice/"><u>Effective Fixes to Address Windows 11 Microphone Malfunctions: Expert Advice</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/googles-platform-unveiled-for-professional-podcasters-for-2024/"><u>Google's Platform Unveiled for Professional Podcasters for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-resolve-the-there-was-an-issue-error-when-restoring-windows-10/"><u>How to Successfully Resolve the 'There Was an Issue' Error When Restoring Windows 10</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-efficiently-using-background-footage-in-projects/"><u>In 2024, Efficiently Using Background Footage in Projects</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-ultimate-guide-to-get-the-meltan-box-pokemon-go-for-honor-play-8t-drfone-by-drfone-virtual-android/"><u>In 2024, Ultimate guide to get the meltan box pokemon go For Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/issue-resolved-how-to-repair-broken-numeric-keys-on-a-computer-keyboard/"><u>Issue Resolved: How to Repair Broken Numeric Keys on a Computer Keyboard</u></a></li>
<li><a href="https://vp-tips.techidaily.com/les-meilleures-outils-dextraction-de-dvd-pour-windows-10-et-11-guide-complet-gratuit-2023-decouvrez-vos-options/"><u>Les Meilleures Outils D'Extraction De DVD Pour Windows 10 Et 11 : Guide Complet Gratuit 2023 - Découvrez Vos Options</u></a></li>
<li><a href="https://common-error.techidaily.com/masterful-scrolling-techniques/"><u>Masterful Scrolling Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-device-hung-error-dxgi-with-simple-techniques/"><u>Overcoming the Device Hung Error (DXGI) with Simple Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-revive-your-huion-pen-top-5-faulty-pen-fixes/"><u>Quick Solutions: Revive Your Huion Pen - Top 5 Faulty Pen Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/simplifying-your-connection-ultimate-usb-tethering-tips-for-windows-10/"><u>Simplifying Your Connection: Ultimate USB Tethering Tips for Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-for-inaccessible-0x-memory-write-error-at-specific-reference-point-0x/"><u>Solution Found for Inaccessible 0X Memory Write Error at Specific Reference Point (0X)</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-atandt-mobile-offers-in-may-2024-exclusive-selection-curated-by-zdnet/"><u>Top AT&T Mobile Offers in May 2024: Exclusive Selection Curated by ZDNet</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-10-fix-the-non-functional-touchpad-scroll-problem/"><u>Troubleshooting Windows 10: Fix the Non-Functional Touchpad Scroll Problem</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/unleashing-creativity-in-drone-video-post-production/"><u>Unleashing Creativity in Drone Video Post-Production</u></a></li>
</ul></div>

