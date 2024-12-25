---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-12-24T19:57:19.863Z
updated: 2024-12-25T19:47:10.347Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
excerpt: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
thumbnail: https://thmb.techidaily.com/c616a530c3b86047af7fee8d712f3caf3cb46a3e47132cccfb907573c9519566.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://fox-glue.techidaily.com/new-lgs-monitor-marvel-an-exhaustive-look-at-ultra-clear-technology/"><u>[New] LG's Monitor Marvel An Exhaustive Look at Ultra-Clear Technology</u></a></li>
<li><a href="https://article-files.techidaily.com/new-navigating-beyond-wirecast-for-broadcast-solutions-for-2024/"><u>[New] Navigating Beyond WireCast for Broadcast Solutions for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-comprehensive-fs-view-strategies-for-premiere-pro/"><u>[Updated] In 2024, Comprehensive FS View Strategies for Premiere Pro</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-ultimate-top-notch-photo-cloud-storages-both-gratis-and-premium-options-for-2024/"><u>[Updated] Ultimate Top-Notch Photo Cloud Storages Both Gratis & Premium Options for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-transform-your-images-into-nfts-the-best-generators-listed/"><u>2024 Approved Transform Your Images Into NFTs - The Best Generators Listed</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-restarting-your-failed-diagnostics-service-quick-fixes-applied/"><u>Diagnosing and Restarting Your Failed Diagnostics Service - Quick Fixes Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-memory-integrity-failures-in-ftdis-sys-caused-by-driver-inefficiencies/"><u>Diagnosing Memory Integrity Failures in FTDIS Sys Caused by Driver Inefficiencies</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-registry-error-while-accessing-images-on-your-windows-10-pc/"><u>How to Fix 'Registry Error' While Accessing Images on Your Windows 10 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-windows-10-when-your-space-bar-doesnt-work/"><u>How to Repair Windows 10 When Your Space Bar Doesn't Work</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-screen-mirroring-samsung-galaxy-s23-to-pc-drfone-by-drfone-android/"><u>In 2024, How to Screen Mirroring Samsung Galaxy S23 to PC? | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/inside-information-on-truthgpt-what-you-need-to-know-about-elon-musks-latest-endeavor/"><u>Inside Information on TruthGPT – What You Need to Know About Elon Musk's Latest Endeavor</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-the-loading-player-error-on-your-windows-pc-now-available/"><u>Step-by-Step Guide to Fix the Loading Player Error on Your Windows PC - Now Available!</u></a></li>
<li><a href="https://android-frp.techidaily.com/step-by-step-tutorial-how-to-bypass-lava-yuva-2-pro-frp-by-drfone-android/"><u>Step-by-Step Tutorial How To Bypass Lava Yuva 2 Pro FRP</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-the-semaphore-timed-out-error-code-0x80070079/"><u>Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-failed-windows-11-version-1607-update-issues/"><u>Troubleshooting Steps for Failed Windows 11 (Version 1607) Update Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

