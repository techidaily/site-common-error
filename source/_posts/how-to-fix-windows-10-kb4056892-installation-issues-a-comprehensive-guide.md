---
title: "How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
date: 2024-12-28T18:32:10.222Z
updated: 2025-01-04T03:07:39.982Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
excerpt: "This Article Describes How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/cbe88b794b4a33f4b9a69a7996ceb63e4276735d9be42e403798167c8028b648.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-optimize-logitech-footage-background-free-method/"><u>[New] In 2024, Optimize Logitech Footage - Background-Free Method</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-incorporating-on-screen-words-a-tiktok-video-transformation/"><u>[Updated] Incorporating On-Screen Words A TikTok Video Transformation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-simplified-guide-to-burning-audio-from-cds-using-wmp/"><u>[Updated] Simplified Guide to Burning Audio From Cds Using WMP</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-to-get-out-of-the-preparing-to-load-windows-phase-on-your-laptop-or-desktop/"><u>Easy Solutions to Get Out of the 'Preparing to Load Windows' Phase on Your Laptop or Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-your-pc-freezes-on-windows-10/"><u>Effective Solutions for When Your PC Freezes on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-wdk-usage-minimizes-high-cpu-consumption-issues/"><u>Enhanced WDK Usage Minimizes High CPU Consumption Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-apex-legends-cheating-flag-today-effortless-tips-to-get-back-in-action/"><u>Fix Your Apex Legends Cheating Flag Today: Effortless Tips to Get Back in Action</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-samsung-galaxy-a24-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-recover-when-geforce-experience-wont-retrieve-your-settings-anymore/"><u>How to Recover When GeForce Experience Won't Retrieve Your Settings Anymore</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-easy-fixes-how-to-recover-forgotten-icloud-password-on-your-iphone-xr-by-drfone-ios/"><u>In 2024, Easy Fixes How To Recover Forgotten iCloud Password On your iPhone XR</u></a></li>
<li><a href="https://fox-that.techidaily.com/iphone-call-reception-problems-what-should-you-try-first/"><u>IPhone Call Reception Problems – What Should You Try First?</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-windows-11-a-step-by-step-guide-to-running-any-app-with-admin-rights/"><u>Mastering Windows 11: A Step-by-Step Guide to Running Any App with Admin Rights</u></a></li>
<li><a href="https://solve-popular.techidaily.com/the-finest-selection-of-6-proven-gmail-backup-software-options-on-windows-platforms/"><u>The Finest Selection of 6 Proven Gmail Backup Software Options on Windows Platforms</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-video-editing-software-proven-tools-for-stunning-visual-effects/"><u>Top Video Editing Software: Proven Tools for Stunning Visual Effects</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-destiny-2-servers-wont-start/"><u>Troubleshooting Tips for When Destiny 2 Servers Won't Start</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-troubleshooting-microsoft-cant-print-to-pdf-anymore/"><u>Windows 11 Troubleshooting: Microsoft Can't Print to PDF Anymore?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cBCyRXC1-Tw?si=lN9P2xo0hsfyD8K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

