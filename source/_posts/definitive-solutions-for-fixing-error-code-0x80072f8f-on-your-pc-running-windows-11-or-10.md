---
title: Definitive Solutions for Fixing Error Code 0X80072f8f on Your PC Running Windows 11 or 10
date: 2024-10-03T10:13:48.957Z
updated: 2024-10-06T20:02:52.556Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Definitive Solutions for Fixing Error Code 0X80072f8f on Your PC Running Windows 11 or 10
excerpt: This Article Describes Definitive Solutions for Fixing Error Code 0X80072f8f on Your PC Running Windows 11 or 10
thumbnail: https://thmb.techidaily.com/8f0b4518ce0df25393954ab31a3f7f9f5a628c2c9b34d40260095f1057a6321d.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://video-capture.techidaily.com/new-in-2024-unveiling-google-meets-screen-alteration-techniques/"><u>[New] In 2024, Unveiling Google Meet's Screen Alteration Techniques</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-overwatch-gamers-record-like-a-pro/"><u>[Updated] In 2024, Overwatch Gamers, Record Like a Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-resolving-windows-1110-endless-reboot-loop/"><u>Fix: Resolving Windows 11/10 Endless Reboot Loop</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-0x80071ac3-faulty-disk-mistake-in-your-system/"><u>How to Resolve the 0X80071AC3 Faulty Disk Mistake in Your System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-to-windows-11-brightness-controls/"><u>How To Restore Functionality to Windows 11 Brightness Controls</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-samsung-galaxy-a24-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Samsung Galaxy A24 | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-effortless-link-upload-on-instagrams-social-sphere/"><u>In 2024, Effortless Link Upload on Instagram's Social Sphere</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-your-visuals-with-optimal-dimensions/"><u>In 2024, Master Your Visuals with Optimal Dimensions</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721451452625-resolve-airpods-connection-issues-no-more-unwanted-switching-between-apple-products/"><u>Resolve AirPods Connection Issues: No More Unwanted Switching Between Apple Products!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-guide-for-fixing-windows-10-system-crashes-during-launch/"><u>Resolved: Troubleshooting Guide for Fixing Windows 10 System Crashes During Launch</u></a></li>
<li><a href="https://games-able.techidaily.com/sync-your-drawings-and-beats-with-tablets/"><u>Sync Your Drawings and Beats with Tablets</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-common-problems-with-cyclic-redundancy-check-data-integrity/"><u>Troubleshooting Common Problems with Cyclic Redundancy Check (Data Integrity)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-functional-usb-ports-on-windows-11-solutions-and-fixes/"><u>Troubleshooting Non-Functional USB Ports on Windows 11: Solutions and Fixes</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/uncovering-best-in-class-steadicams-for-high-end-dslr-projects/"><u>Uncovering Best-in-Class Steadicams for High-End DSLR Projects</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-users-rejoice-comprehensive-guide-to-fixing-your-keyboard-responsiveness-issues/"><u>Windows 10 Users Rejoice: Comprehensive Guide to Fixing Your Keyboard Responsiveness Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136616/26400" target="_top" id="2136616">
  <img src="//a.impactradius-go.com/display-ad/26400-2136616" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136616/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

