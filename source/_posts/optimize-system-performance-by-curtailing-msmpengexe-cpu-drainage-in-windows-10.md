---
title: Optimize System Performance by Curtailing MsMpEng.exe CPU Drainage in Windows 10
date: 2025-01-12T16:09:45.210Z
updated: 2025-01-16T16:11:04.374Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oP8grXxuy2o?si=uIRNhTYbecTcaC7J" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jpdGEJJwMLY?si=eKgXOPpNeYvYKcel" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-unlimited-chuckles-craftsmanship-no-monetary-requirement/"><u>[New] 2024 Approved Unlimited Chuckles Craftsmanship No Monetary Requirement</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-premier-vr-screens-producers/"><u>[New] In 2024, Premier VR Screens Producers</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201931076-solved-how-to-boost-your-windowslinux-performance-and-reduce-shell-induced-high-cpu-use/"><u>[Solved] How to Boost Your Windows/Linux Performance and Reduce Shell-Induced High CPU Use</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-fresh-topics-to-cover-in-your-vlogs/"><u>[Updated] 2024 Approved Fresh Topics to Cover in Your Vlogs</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-viral-videos-not-pricey-twitter-video-to-gif-conversion/"><u>[Updated] In 2024, Viral Videos, Not Pricey Twitter Video to GIF Conversion</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-melodic-mastery-for-game-dominance-in-free-fire/"><u>[Updated] Melodic Mastery for Game Dominance in Free Fire</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-cultivate-creativity-best-video-concepts-for-viewers/"><u>2024 Approved Cultivate Creativity Best Video Concepts for Viewers</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-smooth-sailing-with-kinemaster-in-film-edits/"><u>2024 Approved Smooth Sailing with Kinemaster in Film Edits</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-lower-network-traffic-tackling-the-svchostexe-netsvcs-challenge/"><u>Effective Strategies to Lower Network Traffic: Tackling the svchost.exe (NETsvcs) Challenge</u></a></li>
<li><a href="https://win11.techidaily.com/fix-malfunctioning-windows-keyboard-buttons/"><u>Fix Malfunctioning Windows Keyboard Buttons</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-broken-usb-ports-on-windows-11-devices-quick-solutions/"><u>Fixing Broken USB Ports on Windows 11 Devices – Quick Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-i-fixed-the-windows-1n-update-not-installing-issue-tips-and-tricks-inside/"><u>How I Fixed the Windows 1N Update Not Installing Issue – Tips & Tricks Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/inconsistent-text-replication-windows-11/"><u>Inconsistent Text Replication, Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/mastering-mixed-media-with-color-for-2024/"><u>Mastering Mixed Media with Color for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-how-to-stop-your-pc-from-falling-asleep-unintentionally/"><u>Quick Fixes: How to Stop Your PC From Falling Asleep Unintentionally</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-bluetooth-woes-windows-11-wireless-fixes-and-tips-for-pairing-success/"><u>Solve Your Bluetooth Woes: Windows ˈ11 Wireless Fixes and Tips for Pairing Success</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transform-gaming-nights-innovative-techniques-to-design-dandd-characters-with-chatgpt-and-dall-e/"><u>Transform Gaming Nights: Innovative Techniques to Design D&D Characters with ChatGPT & DALL-E</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-windows-11-startup-crashes/"><u>Troubleshooting Guide: Resolving Windows 11 Startup Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/xbox-one-wireless-controller-connection-problem-heres-how-to-fix-it/"><u>Xbox One Wireless Controller Connection Problem? Here's How to Fix It</u></a></li>
</ul></div>

