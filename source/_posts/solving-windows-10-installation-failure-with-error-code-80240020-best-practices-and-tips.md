---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-12-30T21:44:20.951Z
updated: 2025-01-04T02:11:08.919Z
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-optimal-flv-to-youtube-transformers-in-a-ranking-list/"><u>[New] 2024 Approved Optimal FLV to YouTube Transformers in a Ranking List</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-2024-approved-breaking-through-with-stunning-hdr-portrait-shots/"><u>[Updated] 2024 Approved Breaking Through with Stunning HDR Portrait Shots</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-quick-guide-to-effective-screen-recording-macos/"><u>[Updated] 2024 Approved Quick Guide to Effective Screen Recording macOS</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fix-for-windows-10-microsoft-store-wont-start/"><u>Comprehensive Fix for Windows 10: Microsoft Store Won't Start?</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-fixing-graphic-issues-in-modern-windows-environments-win1110/"><u>Effective Solutions for Fixing Graphic Issues in Modern Windows Environments (Win11/10)</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-for-dealing-with-hamachi-connection-stop-errors/"><u>Effortless Solutions for Dealing with Hamachi Connection Stop Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-resolving-usb-device-not-recognized-errors-with-failed-port-resets-in-windows-11/"><u>Expert Guide: Resolving 'USB Device Not Recognized' Errors with Failed Port Resets in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-connection-errors-between-bluetooth-keyboards-and-computers/"><u>Expert Tips for Fixing Connection Errors Between Bluetooth Keyboards and Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-your-matches-avoid-infinite-loading-in-valorant-with-these-fixes/"><u>Fast Track Your Matches: Avoid Infinite Loading in Valorant with These Fixes</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/harnessing-the-power-of-youtubes-seo-keywords/"><u>Harnessing the Power of YouTube's SEO Keywords</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203208322-lenovo-keyboard-malfunction-heres-how-you-can-resolve-it/"><u>Lenovo Keyboard Malfunction? Here's How You Can Resolve It</u></a></li>
<li><a href="https://review-topics.techidaily.com/realme-narzo-60-5g-messages-recovery-recover-deleted-messages-from-realme-narzo-60-5g-by-fonelab-android-recover-messages/"><u>Realme Narzo 60 5G Messages Recovery - Recover Deleted Messages from Realme Narzo 60 5G</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reveal-the-invisible-storage-on-your-apple-machine/"><u>Reveal the Invisible Storage on Your Apple Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/the-fix-reactivating-lighting-features-on-your-corsair-keyboard/"><u>The Fix: Reactivating Lighting Features on Your Corsair Keyboard</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/2212474-9780007537013-the-monkey-in-2014-your-chinese-horoscope/"><u>The Monkey in 2014: Your Chinese Horoscope | Free Book</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-10-methods-for-seamlessly-moving-images-from-your-iphone-onto-a-mac/"><u>Top 10 Methods for Seamlessly Moving Images From Your iPhone Onto a Mac</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

