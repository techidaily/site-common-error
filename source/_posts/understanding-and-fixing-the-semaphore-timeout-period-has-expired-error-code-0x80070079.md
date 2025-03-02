---
title: Understanding and Fixing 'The Semaphore Timeout Period Has Expired' Error Code 0X80070079
date: 2025-02-23T17:19:49.573Z
updated: 2025-03-02T14:13:20.473Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding and Fixing 'The Semaphore Timeout Period Has Expired' Error Code 0X80070079
excerpt: This Article Describes Understanding and Fixing 'The Semaphore Timeout Period Has Expired' Error Code 0X80070079
thumbnail: https://thmb.techidaily.com/80d3fa767f44fdaa6b3c03730260a31e590107858e011b7c1ceac58f39d7b6f4.jpg
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
<li><a href="https://youtube-web.techidaily.com/024-approved-strategic-playlist-formation-your-guide-to-youtube-mastery/"><u>[New] 2024 Approved Strategic Playlist Formation Your Guide to YouTube Mastery</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-shine-and-sharpness-streamlined-brightening-of-iphone-movies/"><u>[Updated] Shine and Sharpness Streamlined Brightening of iPhone Movies</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-exploring-the-best-converters-for-tiktok-graphics/"><u>2024 Approved Exploring the Best Converters for TikTok Graphics</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-restoring-corrupted-data-on-your-windows-11-pc/"><u>Comprehensive Solutions for Restoring Corrupted Data on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/cracking-down-on-distorted-sounds-fix-your-windows-107-speaker-problems/"><u>Cracking Down on Distorted Sounds: Fix Your Windows 10/7 Speaker Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-unexpected-shutdowns-with-error-code-167-in-windows-systems/"><u>How to Resolve Unexpected Shutdowns with Error Code 1#67 in Windows Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-essential-guide-three-approaches-for-documenting-discords-live-streams/"><u>In 2024, Essential Guide Three Approaches for Documenting Discord's Live Streams</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-any-motorola-phone-password-using-emergency-call-by-drfone-android/"><u>In 2024, How To Unlock Any Motorola Phone Password Using Emergency Call</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/mastering-free-and-paid-tools-for-vimeo-video-downloads-for-2024/"><u>Mastering Free & Paid Tools for Vimeo Video Downloads for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/techniques-to-frame-photos-with-leading-lines-iphone/"><u>Techniques to Frame Photos with Leading Lines (iPhone)</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/top-3-herramientas-esenciales-para-la-copia-bit-a-bit-de-archivos-criticos-en-linux-y-windows/"><u>Top 3 Herramientas Esenciales Para La Copia Bit a Bit De Archivos Críticos en Linux Y Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-csgo-issues-fast-fixes-for-no-more-game-crashes/"><u>Troubleshoot CSGO Issues - Fast Fixes for No More Game Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-when-file-explorer-wont-respond-in-windows-10/"><u>Troubleshooting Guide: When File Explorer Won't Respond in Windows 10</u></a></li>
<li><a href="https://hardware-help.techidaily.com/update-to-the-newest-windows-compatible-geforce-gtx-ebx-770-graphics-driver-software/"><u>Update to the Newest Windows-Compatible GeForce GTX Ebx 770 Graphics Driver Software</u></a></li>
</ul></div>

