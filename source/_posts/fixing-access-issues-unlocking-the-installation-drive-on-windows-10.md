---
title: "Fixing Access Issues: Unlocking the Installation Drive on Windows 10"
date: 2024-09-09T16:07:23.823Z
updated: 2024-09-15T16:06:06.990Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Access Issues: Unlocking the Installation Drive on Windows 10"
excerpt: "This Article Describes Fixing Access Issues: Unlocking the Installation Drive on Windows 10"
thumbnail: https://thmb.techidaily.com/4e54d2ee69e2d3cc5b62664f281e174d4bc506ec5c304888c5062a8c04d6107f.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://driver-error.techidaily.com/corrected-previous-software-installation-issue-resolved/"><u>[CORRECTED] Previous Software Installation Issue Resolved</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-rediscover-film-noir-creating-vintage-scenes/"><u>[New] 2024 Approved Rediscover Film Noir Creating Vintage Scenes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-critically-acclaimed-phone-and-desktop-video-calls-list/"><u>[Updated] Critically Acclaimed Phone and Desktop Video Calls List</u></a></li>
<li><a href="https://printer-issues.techidaily.com/clearing-up-laser-print-glitches/"><u>Clearing Up Laser Print Glitches</u></a></li>
<li><a href="https://facebook.techidaily.com/fix-for-inaccessible-verification-codes-on-social-media-platforms-fb/"><u>Fix for Inaccessible Verification Codes on Social Media Platforms (FB)</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-high-disk-usage-caused-by-microsofts-telemetry-service-in-windows-11-systems/"><u>Fixing High Disk Usage Caused by Microsoft's Telemetry Service in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-critical-dxgkrnl-problem-and-restore-videos-on-windows/"><u>How to Fix the Critical Dxgkrnl Problem and Restore Videos on Windows</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-huawei-p60-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Huawei P60 Phones with/without a PC</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-the-editors-insight-to-seamless-lut-integration-in-premiere/"><u>In 2024, The Editor's Insight to Seamless LUT Integration in Premiere</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-high-performance-gear-with-tom-a-comprehensive-look-at-hardware/"><u>Navigating High-Performance Gear with Tom: A Comprehensive Look at Hardware</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-to-overcome-the-preparing-to-configure-windows-issue/"><u>Resolved: Step-by-Step Guide to Overcome the 'Preparing to Configure Windows' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-invisible-mouse-icons-in-windows-10-a-complete-solution/"><u>Troubleshooting Invisible Mouse Icons in Windows 10 – A Complete Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-failed-system-restores-in-windows-11/"><u>Understanding and Resolving Failed System Restores in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-error-0x80004005-a-step-by-step-troubleshooting-guide/"><u>Unraveling Error 0X80004005 - A Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725289226601-dvd/"><u>すぐにできる市販DVDバッキングマスター法！フリーチュートリアル</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

