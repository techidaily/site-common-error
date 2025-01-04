---
title: Optimize System Performance by Curtailing MsMpEng.exe CPU Drainage in Windows 10
date: 2024-12-30T02:09:30.024Z
updated: 2025-01-04T03:40:39.747Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/h5uImbOWmTg?si=z4kP-R0QbXbBAJTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://common-error.techidaily.com/tech-tips-fixed-kernel32-errors/"><u>[Tech Tips] Fixed Kernel32 Errors</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-10-fastest-growing-youtube-channels-to-light-up-your-mind/"><u>2024 Approved 10 Fastest Growing YouTube Channels to Light Up Your Mind</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-discover-the-best-voice-interpretation-tech-for-mac-users/"><u>2024 Approved Discover the Best Voice Interpretation Tech for Mac Users</u></a></li>
<li><a href="https://common-error.techidaily.com/breaking-the-loop-how-to-prevent-unwanted-reboots-on-your-pc-running-windows-10/"><u>Breaking the Loop: How to Prevent Unwanted Reboots on Your PC Running Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-skype-video-not-working-on-windows-10/"><u>Easy to Fix Skype Video Not Working on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-broken-spacebar-functionality-on-windows-10-pcs/"><u>How to Repair a Broken Spacebar Functionality on Windows 10 PCs</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-disabled-apple-iphone-15-pro-max-how-to-unlock-a-disabled-apple-iphone-15-pro-max-drfone-by-drfone-ios/"><u>In 2024, Disabled Apple iPhone 15 Pro Max How to Unlock a Disabled Apple iPhone 15 Pro Max? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-touchpad-problems-heres-how-to-fix-them-on-windows-1187/"><u>Laptop Touchpad Problems? Here's How to Fix Them on Windows 11/8/7!</u></a></li>
<li><a href="https://games-able.techidaily.com/secrets-to-finding-missing-games-in-egc/"><u>Secrets to Finding Missing Games in EGC</u></a></li>
<li><a href="https://fox-shield.techidaily.com/simple-steps-adding-srt-captions-to-your-avi-videos-with-ease/"><u>Simple Steps: Adding SRT Captions to Your AVI Videos with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-eliminating-lag-issues-in-world-of-warcraft-play/"><u>Step-by-Step Solution: Eliminating Lag Issues in World of Warcraft Play</u></a></li>
<li><a href="https://extra-information.techidaily.com/why-are-videos-invisible-on-sony-a6400/"><u>Why Are Videos Invisible on Sony A6400?</u></a></li>
</ul></div>

