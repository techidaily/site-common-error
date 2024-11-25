---
title: "[Solved] Wacom Pen Not Working on Windows 11/10"
date: 2024-11-17T19:07:11.174Z
updated: 2024-11-24T19:05:16.047Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [Solved] Wacom Pen Not Working on Windows 11/10
excerpt: This Article Describes [Solved] Wacom Pen Not Working on Windows 11/10
thumbnail: https://thmb.techidaily.com/4aac991e64509d68ac8489b0b42db25368d487df0c50d4cd60fbe09c3938eb3d.jpg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

9) See if the problem is resolved.

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

 4) Restart your computer after this.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pRR3Oq03EuE?si=ZTy8-WH0AesA9zRh&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-video-files.techidaily.com/new-navigating-music-licens-written-by-john-doe/"><u>[New] Navigating Music Licens Written by John Doe</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-step-by-step-guide-for-easy-macbook-air-recordings-for-2024/"><u>[New] Step-by-Step Guide for Easy Macbook Air Recordings for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-pixel-perfection-top-tools-for-preserving-tweets-videos/"><u>[Updated] Pixel Perfection Top Tools for Preserving Tweets' Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-the-print-screen-not-working-issue-on-windows-1110-pcs/"><u>Effective Solutions to the Print Screen Not Working Issue on Windows 11/10 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/execution-denied-compliance-not-met/"><u>Execution Denied: Compliance Not Met</u></a></li>
<li><a href="https://common-error.techidaily.com/finding-and-restoring-lost-windows-on-your-computer-with-ease/"><u>Finding and Restoring Lost Windows on Your Computer with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/fortnite-graphics-card-compatibility-fix-for-windows-users-unsupported-to-supported/"><u>Fortnite Graphics Card Compatibility Fix for Windows Users (Unsupported to Supported)</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-change-credit-card-on-your-iphone-8-plus-apple-id-and-apple-pay-by-drfone-ios/"><u>How to Change Credit Card on Your iPhone 8 Plus Apple ID and Apple Pay</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-copy-and-paste-failures-in-windows-11-expert-advice/"><u>How to Overcome Copy and Paste Failures in Windows 11 - Expert Advice</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-screen-lock-pin-on-realme-gt-3-like-a-pro-5-easy-ways-by-drfone-android/"><u>How To Remove Screen Lock PIN On Realme GT 3 Like A Pro 5 Easy Ways</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-cut-down-on-hassle-with-easy-ipad-recording-methods/"><u>In 2024, Cut Down On Hassle With Easy iPad Recording Methods</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-secrets-behind-top-performers-in-online-forums-like-reddit/"><u>In 2024, The Secrets Behind Top Performers in Online Forums Like Reddit</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-depth-look-at-iphones-top-watermarking-software-choices-for-2024/"><u>In-Depth Look at iPhone's Top Watermarking Software Choices for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/playing-fortnite-with-any-gpu-tips-for-fixing-compatibility-issues-on-windows/"><u>Playing Fortnite with Any GPU? Tips for Fixing Compatibility Issues on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-how-to-get-non-responsive-chrome-working-again/"><u>Solution Steps: How To Get Non-Responsive Chrome Working Again</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-resolving-issues-with-non-responsive-computer-systems/"><u>Step-by-Step Instructions: Resolving Issues with Non-Responsive Computer Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/the-ultimate-walkthrough-installing-latest-drivers-for-epson-wf-n20-printers-on-microsoft-windows-systems/"><u>The Ultimate Walkthrough: Installing Latest Drivers for Epson WF-N20 Printers on Microsoft Windows Systems</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-illuminating-soundscapes-with-imagery-techniques-for-photographic-audio-amalgamation-2023-art-and-technology-insights/"><u>Updated In 2024, Illuminating Soundscapes with Imagery Techniques for Photographic Audio Amalgamation 2023 Art & Technology Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205015240-usb-mouse-malfunction-on-computers-discover-quick-and-effective-repair-techniques/"><u>USB Mouse Malfunction on Computers? Discover Quick and Effective Repair Techniques</u></a></li>
</ul></div>

