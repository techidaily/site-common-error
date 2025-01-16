---
title: Complete Guide to Lowering High CPU Usage by svchost.exe on Windows 10 Devices – Solved
date: 2025-01-14T16:17:27.856Z
updated: 2025-01-16T16:32:42.384Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fJlICvacgJY?si=jNeijBVj7ia4ammA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jvwX82j3ci0?si=gAWoovjXgs3m1d7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-blueprint-for-creating-viral-trailers-in-the-world-of-youtube/"><u>[New] 2024 Approved Blueprint for Creating Viral Trailers in the World of YouTube</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-direct-from-instagram-masterful-techniques-for-igtv-video-transferring-for-2024/"><u>[New] Direct From Instagram Masterful Techniques for IGTV Video Transferring for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/rom-raw-video-to-engaging-youtube-videos-with-sony-vegas-tools-for-2024/"><u>[New] From Raw Video to Engaging YouTube Videos with Sony Vegas Tools for 2024</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-in-2024-boosting-collaboration-mastery-of-zoom-capabilities-in-win10/"><u>[New] In 2024, Boosting Collaboration Mastery of Zoom Capabilities in Win10</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-cutting-edge-strategies-for-recording-online-classes/"><u>[New] In 2024, Cutting-Edge Strategies for Recording Online Classes</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-gear-360-vs-lgcam-determining-best-in-3d-capture/"><u>[Updated] In 2024, Gear 360 vs LGCam Determining Best in 3D Capture</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-the-comprehensive-guide-to-ultimate-video-editing-vivacut-24-edition/"><u>[Updated] The Comprehensive Guide to Ultimate Video Editing VivaCut '24 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/breaking-free-how-to-fix-the-windows-10-endless-recovery-cycle/"><u>Breaking Free: How to Fix the Windows 10 Endless Recovery Cycle</u></a></li>
<li><a href="https://unlock-android.techidaily.com/delete-gmail-account-withwithout-password-on-honor-x50i-by-drfone-android/"><u>Delete Gmail Account With/Without Password On Honor X50i</u></a></li>
<li><a href="https://common-error.techidaily.com/effectively-managing-elevated-cpu-utilization-in-system-idle-tasks-a-solution-guide/"><u>Effectively Managing Elevated CPU Utilization in System Idle Tasks: A Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-invalid-directory-name-error-step-by-step-troubleshooting-guide/"><u>How to Fix 'Invalid Directory Name' Error: Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-infinix-note-30-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Infinix Note 30 to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-outage-or-glitch-heres-how-you-can-get-it-running-smoothly-again/"><u>Netflix Outage or Glitch? Here's How You Can Get It Running Smoothly Again</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-the-anatomy-of-great-lower-thirds-a-guide-for-fcpx-editors/"><u>New 2024 Approved The Anatomy of Great Lower Thirds A Guide for FCPX Editors</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-issues-with-the-battleye-anti-cheat-installation/"><u>Resolved: Fixing Issues with the BattlEye Anti-Cheat Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210106262-troubleshoot-windows-10-bluetooth-not-detected-with-ease/"><u>Troubleshoot Windows 10 Bluetooth Not Detected with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-with-steam-apps-dll/"><u>Troubleshooting Error with Steam App's Dll</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-rapid-ascension-of-scroll-bars-in-windows-11s-file-explorer-a-complete-guide/"><u>Troubleshooting the Rapid Ascension of Scroll Bars in Windows 11'S File Explorer: A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-the-mystery-understanding-unexpected-auto-boot-in-windows-10-systems/"><u>Unraveling the Mystery: Understanding Unexpected Auto-Boot in Windows 10 Systems</u></a></li>
</ul></div>

