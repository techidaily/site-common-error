---
title: "Critical System Failure: Devices at End"
date: 2024-10-20T20:25:02.864Z
updated: 2024-10-24T17:16:37.209Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Critical System Failure: Devices at End"
excerpt: "This Article Describes Critical System Failure: Devices at End"
thumbnail: https://thmb.techidaily.com/07877b725aebcc26ce626860ff1aa31b598ca62f4a725eae923eeb25fe929021.jpg
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-a-comprehensible-guide-to-integrating-zoom-with-win10/"><u>[New] 2024 Approved A Comprehensible Guide to Integrating Zoom with Win10</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-expert-guide-to-instantaneous-deletion-of-youtube-posts/"><u>[New] 2024 Approved Expert Guide to Instantaneous Deletion of Youtube Posts</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-streamlining-screens-for-large-scale-youtubers/"><u>[Updated] In 2024, Streamlining Screens for Large-Scale YouTubers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-downloading-fb-audio-nuggets/"><u>2024 Approved Downloading FB Audio Nuggets</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-gaggraphs-craft-your-own-jest/"><u>2024 Approved GagGraphs Craft Your Own Jest</u></a></li>
<li><a href="https://blog-min.techidaily.com/8-ways-to-transfer-photos-from-poco-c50-to-iphone-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>8 Ways to Transfer Photos from Poco C50 to iPhone Easily | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-overcoming-windows-10-error-0x80070541-during-updates/"><u>Effective Solutions for Overcoming Windows 10 Error 0X80070541 During Updates</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-honor-90-gt-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-11-updates-avoid-error-code-0x800f0922-pitfalls/"><u>Mastering Windows 11 Updates: Avoid Error Code 0X800F0922 Pitfalls</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-minecraft-slow-performance-a-comprehensive-guide/"><u>Resolve Your Minecraft Slow Performance: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/streamline-your-tasks-essential-tips-for-using-file-explorer-in-windows-1ntegrated-applications-sync-with-google-photos-or-icloud-you-can-access-your-photos78/"><u>Streamline Your Tasks: Essential Tips for Using File Explorer in Windows 1Ntegrated Applications | Sync with Google Photos or iCloud, You Can Access Your Photos From Anywhere and on Any Device</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/the-rise-of-3d-technology-an-insightful-look-at-the-creality-k1-max-review/"><u>The Rise of 3D Technology: An Insightful Look at the Creality K1 Max Review</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolving-issues-with-the-at-sign-on-your-device/"><u>Troubleshooting Tips: Resolving Issues with the At Sign (@) on Your Device</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207794567-win-update-woes-eliminate-error-8007000e-with-these-easy-tips/"><u>Win Update Woes? Eliminate Error 8007000E with These Easy Tips!</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/1720600594541-windows/"><u>ステラ・データリカバリー: Windows上で失われた重要ファイルを効率的に復元する手段</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

