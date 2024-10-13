---
title: Understanding and Solving the Windows 10 0X80240034 Update Failure
date: 2024-10-07T04:05:58.912Z
updated: 2024-10-12T16:12:02.890Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding and Solving the Windows 10 0X80240034 Update Failure
excerpt: This Article Describes Understanding and Solving the Windows 10 0X80240034 Update Failure
thumbnail: https://thmb.techidaily.com/0902934f7edf585e53199bb405b79c684665bcaad3a1bcb366b5dba56b094eb6.jpg
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
<li><a href="https://extra-hints.techidaily.com/new-breaking-down-advanced-photographic-modes-for-enhanced-results/"><u>[New] Breaking Down Advanced Photographic Modes for Enhanced Results</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/he-chefs-roadmap-creating-culinary-content/"><u>[New] The Chef's Roadmap Creating Culinary Content</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-inside-look-making-most-of-firefox-picture-in-picture/"><u>[Updated] Inside Look Making Most of Firefox Picture-in-Picture</u></a></li>
<li><a href="https://extra-hints.techidaily.com/10-exemplary-websites-for-vector-quality-graphics/"><u>10 Exemplary Websites for Vector-Quality Graphics</u></a></li>
<li><a href="https://article-posts.techidaily.com/beak-beat-boatwrights/"><u>Beak Beat Boatwrights</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-to-launch-the-hosted-network-feature-on-windows-10-systems/"><u>Effective Fixes to Launch the Hosted Network Feature on Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/from-frustration-to-fulfillment-in-nvidia-fixed/"><u>From Frustration to Fulfillment in NVIDIA Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/handling-delayed-service-starts-mastering-the-resolution-of-error-1053/"><u>Handling Delayed Service Starts: Mastering the Resolution of Error 1053</u></a></li>
<li><a href="https://common-error.techidaily.com/huion-pen-problems-discover-five-fast-fixes-to-restore-its-functionality/"><u>Huion Pen Problems? Discover Five Fast Fixes to Restore Its Functionality</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Xiaomi Redmi Note 12T Pro?</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-ultimate-guide-on-iphone-7-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>In 2024, Ultimate Guide on iPhone 7 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-apple-iphone-12-pro-with-forgotten-passcode-different-methods-you-can-try-by-drfone-ios/"><u>In 2024, Unlock Apple iPhone 12 Pro With Forgotten Passcode Different Methods You Can Try</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-video-editing-for-mac-users-avs-editor-software/"><u>In 2024, Video Editing for Mac Users AVS Editor Software</u></a></li>
<li><a href="https://common-error.techidaily.com/prompt-protocols-for-power-puzzles-eliminating-missing-battery-alerts-quickly/"><u>Prompt Protocols for Power Puzzles: Eliminating 'Missing Battery' Alerts Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-troubleshooting-unwritable-segment-at-memory-reference-point-x/"><u>Resolved Issue: Troubleshooting Unwritable Segment at Memory Reference Point X</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-sticky-keys-on-windows-11/"><u>Resolved: Fixing Sticky Keys on Windows 11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/the-insiders-manual-to-upload-content-to-igtv-for-2024/"><u>The Insider's Manual to Upload Content to IGTV for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-troubleshooting-tips-to-overcome-red-screen-issues-in-windows-11/"><u>The Ultimate Troubleshooting Tips to Overcome Red Screen Issues in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-a-non-responsive-huion-pen-with-these-5-effective-techniques/"><u>Troubleshoot a Non-Responsive Huion Pen with These 5 Effective Techniques</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

