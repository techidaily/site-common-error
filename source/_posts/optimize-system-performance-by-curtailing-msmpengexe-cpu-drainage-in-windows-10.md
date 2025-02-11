---
title: Optimize System Performance by Curtailing MsMpEng.exe CPU Drainage in Windows 10
date: 2025-02-04T05:00:52.722Z
updated: 2025-02-11T04:46:50.726Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fZTlPdOFNmo?si=Ym8p7ayV1gtNzzXj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-essential-11-zero-cost-youtube-moniker-makers/"><u>[New] 2024 Approved Essential 11 Zero-Cost YouTube Moniker Makers</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-efficient-video-editing-with-timestamps-and-on-screen-text-for-2024/"><u>[New] Efficient Video Editing with Timestamps & On-Screen Text for 2024</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-icy-images-cozier-cinematics-best-bgs-selection/"><u>[Updated] Icy Images, Cozier Cinematics Best Bgs Selection</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-xbox-elite-controller-padlock-problems-unlock-the-secrets-to-reviving-your-pen-in-depth-guide/"><u>DIY Xbox Elite Controller Padlock Problems: Unlock the Secrets to Reviving Your Pen (In-Depth Guide)</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-successfully-launching-a-hosted-network-on-your-windows-11-pc/"><u>Expert Tips: Successfully Launching a Hosted Network on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fix-not-present-device-alert-on-pcs-running-windows-1187-error-code-t24/"><u>Guide to Fix 'Not Present' Device Alert on PCs Running Windows 11/8/7 (Error Code: T24)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-error-code-0x8024401c-during-windows-1011-operating-system-updates-successfully/"><u>How to Fix 'Error Code: 0X8024401c' During Windows 10/11 Operating System Updates Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-functioning-lenovo-keyboard-step-by-step-guide/"><u>How to Fix a Non-Functioning Lenovo Keyboard – Step by Step Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-itel-s23plus-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Itel S23+ Device</u></a></li>
<li><a href="https://youtube-data.techidaily.com/droid-comparison-youtube-app-explored-for-2024/"><u>IOS/Android Comparison YouTube App Explored for 2024</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/la-scelta-migliore-per-la-conversione-gratuitamente-dvd-in-formati-multimediali-su-windows-i-vostri-3-top-picks/"><u>La Scelta Migliore per La Conversione Gratuitamente DVD in Formati Multimediali Su Windows: I Vostri 3 Top Picks</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/newest-windows-operating-system-patches-released-in-july-2024/"><u>Newest Windows Operating System Patches Released in July 2024</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/overcoming-windows-10-screen-blankness/"><u>Overcoming Windows 10 Screen Blankness</u></a></li>
<li><a href="https://win11.techidaily.com/remedy-for-unknown-value-issue-in-windows-tech-environment/"><u>Remedy for Unknown Value Issue in Windows Tech Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-wireless-connectivity-overcoming-off-status-alerts-on-devices/"><u>Restoring Wireless Connectivity: Overcoming Off Status Alerts on Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-geforce-experience-setting-capabilities/"><u>Step-by-Step Guide to Restoring GeForce Experience Setting Capabilities</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1722185064415-top-9-benefits-of-switching-to-chatgpt-plus-unlock-your-potential/"><u>Top 9 Benefits of Switching to ChatGPT Plus - Unlock Your Potential!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-night-light-not-responding-errors/"><u>Troubleshooting Windows 11 Night Light Not Responding Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-troubleshooting-your-lenovo-laptops-malfunctioning-webcam/"><u>Ultimate Guide: Troubleshooting Your Lenovo Laptop's Malfunctioning Webcam</u></a></li>
</ul></div>

