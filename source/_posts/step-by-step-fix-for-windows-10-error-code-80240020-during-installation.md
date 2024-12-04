---
title: Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation
date: 2024-11-26T16:24:14.320Z
updated: 2024-12-03T18:56:04.397Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation
excerpt: This Article Describes Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
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
<li><a href="https://youtube-zero.techidaily.com/024-approved-android-and-ios-the-best-sound-distortion-tools/"><u>[New] 2024 Approved Android & iOS The Best Sound Distortion Tools</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-cutting-edge-tricks-in-streamlabs-obs-broadcasts-for-2024/"><u>[Updated] Cutting-Edge Tricks in Streamlabs OBS Broadcasts for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-ultimate-guide-finalcut-pro-for-youtube-editing/"><u>2024 Approved Ultimate Guide FinalCut Pro for YouTube Editing</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210035802-bid-farewell-to-your-blinking-cursor-quick-fixes-inside/"><u>Bid Farewell to Your Blinking Cursor: Quick Fixes Inside!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/break-new-ground-in-cpu-performance-with-an-amd-ryzen-9700x-overclocked-to-an-impressive-58ghz-and-chilled-by-premium-aio-liquid-cooling-plus-a-surprising-i69/"><u>Break New Ground in CPU Performance with an AMD Ryzen #9700X: Overclocked to an Impressive 5.8GHz and Chilled by Premium AIO Liquid Cooling – Plus, a Surprising Idle Speed of 6 GHz Achieved!</u></a></li>
<li><a href="https://common-error.techidaily.com/defeating-ds-stylus-issues-a-thorough-strategy-guide-to-restoring-precision-and-control-in-your-handheld-gaming-adventures/"><u>Defeating DS Stylus Issues - A Thorough Strategy Guide to Restoring Precision and Control in Your Handheld Gaming Adventures</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/experience-a-masterpiece-of-gaming-like-a-dragon-yakuza-review/"><u>Experience a Masterpiece of Gaming - 'Like A Dragon' Yakuza Review</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-missing-d3dx9tld-error-expert-tips-for-quick-recovery/"><u>Fixing Missing D3dx9_tld Error: Expert Tips for Quick Recovery</u></a></li>
<li><a href="https://games-able.techidaily.com/how-to-repair-minecraft-launcher-issue-code-0x803f8001/"><u>How to Repair Minecraft Launcher Issue Code 0X803F8001</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-the-best-methods-to-unlock-the-iphone-locked-to-owner-for-iphone-15-pro-drfone-by-drfone-ios/"><u>In 2024, The Best Methods to Unlock the iPhone Locked to Owner for iPhone 15 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-driverpowerstatefailure-error-step-by-step-guide/"><u>Resolving the DRIVER_POWER_STATE_FAILURE Error: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-print-screens-effective-fixes-for-common-problems-on-microsofts-latest-operating-systems/"><u>Restoring Print Screens: Effective Fixes for Common Problems on Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://games-able.techidaily.com/steams-historical-pricing-for-games-decoded/"><u>Steam's Historical Pricing for Games Decoded</u></a></li>
<li><a href="https://common-error.techidaily.com/the-role-of-msdia80dll-in-windows-operations-to-retain-or-remove/"><u>The Role of MSDIA80.DLL in Windows Operations – To Retain or Remove?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-your-dell-camera-steps-to-get-it-working-on-windows-again/"><u>Troubleshoot Your Dell Camera: Steps to Get It Working on Windows Again</u></a></li>
<li><a href="https://common-error.techidaily.com/undetected-hard-drives-find-out-why-and-how-you-can-fix-it/"><u>Undetected Hard Drives? Find Out Why and How You Can Fix It</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unleash-maximum-downloads-with-utorrent-on-windows-pcs/"><u>Unleash Maximum Downloads with uTorrent on Windows PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nmj7aVvEeAs?si=OcR7USXKGyLcn09q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

