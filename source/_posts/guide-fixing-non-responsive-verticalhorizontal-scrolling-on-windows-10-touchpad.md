---
title: "Guide: Fixing Non-Responsive Vertical/Horizontal Scrolling on Windows 10 Touchpad"
date: 2024-10-08T20:04:07.096Z
updated: 2024-10-12T22:50:15.016Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Guide: Fixing Non-Responsive Vertical/Horizontal Scrolling on Windows 10 Touchpad"
excerpt: "This Article Describes Guide: Fixing Non-Responsive Vertical/Horizontal Scrolling on Windows 10 Touchpad"
thumbnail: https://thmb.techidaily.com/5e0a2202e9f4da31ba85b59400bc244193601b11b41dcc123e47e5f9015f53a2.jpg
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
<li><a href="https://some-approaches.techidaily.com/new-integrating-images-into-your-insta-world/"><u>[New] Integrating Images Into Your Insta World</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-the-significance-of-reducing-camera-shake-with-software-tools/"><u>[New] The Significance of Reducing Camera Shake with Software Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-infinite-loading-screen-on-valorant-a-guide-to-getting-you-back-into-action/"><u>[Solved] Infinite Loading Screen on Valorant: A Guide to Getting You Back Into Action</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-ps4-controller-wont-charge/"><u>[SOLVED] PS4 Controller Won’t Charge</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-2024-approved-essential-guide-fetching-twitter-videos-directly-from-mobile/"><u>[Updated] 2024 Approved Essential Guide Fetching Twitter Videos Directly From Mobile</u></a></li>
<li><a href="https://common-error.techidaily.com/activating-bluetooth-on-a-windows-7-machine-a-comprehensive-tutorial/"><u>Activating Bluetooth on a Windows 7 Machine - A Comprehensive Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/all-systems-checked-yet-one-component-idles/"><u>All Systems Checked, Yet One Component Idles</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-overcoming-driverpowerstatefailure-errors/"><u>Effective Solutions for Overcoming DRIVER_POWER_STATE_FAILURE Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-faulty-driver-issues-fast-a-comprehensive-tutorial/"><u>Fixing Faulty Driver Issues Fast: A Comprehensive Tutorial</u></a></li>
<li><a href="https://unlock-android.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-itel-p40-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Itel P40</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/nvidia-geforce-rtx-2amo-driver-pack-best-version-for-windows-10-11-users/"><u>NVIDIA GeForce RTX 2Amo Driver Pack – Best Version for Windows 10, 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-common-causes-and-fixes-for-unresponsive-lenovo-keyboards/"><u>Resolved! Common Causes and Fixes for Unresponsive Lenovo Keyboards</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/solving-hevc-playback-errors-expert-tips-to-enhance-your-experience-with-windows-media-player/"><u>Solving HEVC Playback Errors: Expert Tips to Enhance Your Experience with Windows Media Player</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-functionality-for-the-windows-key-combo-shiftpluss-in-windows-operating-systems/"><u>Step-by-Step Guide to Restoring Functionality for the Windows Key Combo (Shift+S) in WIndows Operating Systems</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-instructions-how-to-get-the-latest-huion-graphics-tablet-driver-for-windows-resolved/"><u>Step-by-Step Instructions: How to Get the Latest Huion Graphics Tablet Driver for Windows [RESOLVED]</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/step-by-step-iphone-360-degrees-and-fb-sharing/"><u>Step-by-Step IPhone, 360 Degrees, & FB Sharing</u></a></li>
<li><a href="https://hardware-help.techidaily.com/why-the-end-of-samsung-messages-could-spell-trouble-for-android-users/"><u>Why the End of Samsung Messages Could Spell Trouble for Android Users</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

