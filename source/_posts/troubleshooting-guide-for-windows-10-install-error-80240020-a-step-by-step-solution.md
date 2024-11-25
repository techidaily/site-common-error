---
title: "Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution"
date: 2024-11-20T18:06:47.358Z
updated: 2024-11-24T19:05:43.718Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution"
excerpt: "This Article Describes Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution"
thumbnail: https://thmb.techidaily.com/0039be476e652be6e9e02b60752db5e1733ea22d9d841af5f5ee6bd2b62676ef.jpg
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-unique-stories-crafting-powerful-yt-narratives/"><u>[New] 2024 Approved Unique Stories Crafting Powerful YT Narratives</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-in-2024-how-to-make-outstanding-youtube-outro/"><u>[Updated] In 2024, How to Make Outstanding YouTube Outro?</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-in-2024-ultimate-mc-village-dwellings-guide/"><u>[Updated] In 2024, Ultimate MC Village Dwellings Guide</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-the-ultimate-guide-to-choosing-5-chrome-extensions-for-facebook-videos-for-2024/"><u>[Updated] The Ultimate Guide to Choosing 5 Chrome Extensions for Facebook Videos for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fix-for-dolby-home-theater-malfunction-when-using-windows-11-a-comprehensive-guide/"><u>DIY Fix for Dolby Home Theater Malfunction When Using Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://win-awesome.techidaily.com/downloadable-free-pdf-converter-effortlessly-convert-images-into-pdfs/"><u>Downloadable Free PDF Converter: Effortlessly Convert Images Into PDFs</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-the-user-profile-sign-in-error-messages-in-windows-operating-systems/"><u>Effective Solutions to the User Profile Sign-In Error Messages in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-volume-icon-missing-on-windows-11-with-pictures/"><u>Fix Volume Icon Missing on Windows 11 [with Pictures]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-how-to-get-the-microsoft-store-running-again/"><u>Fixing Issues - How To Get The Microsoft Store Running Again</u></a></li>
<li><a href="https://android-location.techidaily.com/getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-x90s-drfone-by-drfone-virtual/"><u>Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo X90S | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-the-initialization-failed-problem-in-smartaudio/"><u>How to Correct the 'Initialization Failed' Problem in SmartAudio</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-absent-media-device-driver-issue/"><u>How to Resolve the Absent Media Device Driver Issue</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/in-2024-breaking-boundaries-coordinated-video-watch-across-channels/"><u>In 2024, Breaking Boundaries Coordinated Video Watch Across Channels</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-motorola-edge-40-neo-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Motorola Edge 40 Neo FRP Android 10/11/12/13</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-realme-10t-5g-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Realme 10T 5G FRP</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-system-files-is-msda80dll-essential-to-preserve/"><u>Navigating System Files: Is MSDA80.DLL Essential to Preserve?</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-no-audio-output-device-found-issue-on-windows-10-and-11/"><u>Resolving the 'No Audio Output Device Found' Issue on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/valorant-lag-issue-solved-escape-from-the-infinite-wait-screen/"><u>Valorant Lag Issue Solved: Escape From the Infinite Wait Screen</u></a></li>
<li><a href="https://discover-blog.techidaily.com/mp3-asf/"><u>오피스에서 제공하는 MP3 ASF 무료 변환 도구 - 모바이비</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

