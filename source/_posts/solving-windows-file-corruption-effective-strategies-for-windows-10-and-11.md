---
title: "Solving Windows File Corruption: Effective Strategies for Windows 10 & 11"
date: 2024-09-30T23:16:33.724Z
updated: 2024-10-06T20:50:20.822Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Windows File Corruption: Effective Strategies for Windows 10 & 11"
excerpt: "This Article Describes Solving Windows File Corruption: Effective Strategies for Windows 10 & 11"
thumbnail: https://thmb.techidaily.com/82a28386a9112ee73bc2dbed1a00fc83e61f6f26163c69b1bc0d92f7095e097d.JPG
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
<li><a href="https://extra-skills.techidaily.com/new-novices-selection-guide-to-ideal-filming-cameras/"><u>[New] Novice's Selection Guide to Ideal Filming Cameras</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solved-counter-strike-2-mic-not-working/"><u>[SOLVED] Counter-Strike 2 Mic Not Working</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-best-8-filter-packs-for-dynamic-video-streaming/"><u>[Updated] Best 8 Filter Packs for Dynamic Video Streaming</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-channel-charm-with-cost-free-visual-aids/"><u>[Updated] In 2024, Channel Charm with Cost-Free Visual Aids</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-pitch-perfect-techniques-for-integrating-tunes-into-vimeo-videos/"><u>[Updated] Pitch Perfect Techniques for Integrating Tunes Into Vimeo Videos</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-top-6-virtual-reality-vr-gloves-to-check-out/"><u>[Updated] Top 6 Virtual Reality (VR) Gloves to Check Out</u></a></li>
<li><a href="https://common-error.techidaily.com/beating-the-glitch-fixes-for-opening-issues-with-nvidias-geforce-experience-software/"><u>Beating the Glitch: Fixes for Opening Issues with Nvidia's GeForce Experience Software</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehvew-why-isnt-my-lenovo-keyboard-working-fixes-inside/"><u>Comprehvew: Why Isn't My Lenovo Keyboard Working? - Fixes Inside</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-elevate-your-gaming-experience-with-these-5-techniques-on-windows-11/"><u>In 2024, Elevate Your Gaming Experience with These 5 Techniques on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206484481-lenovo-pad-not-responding-get-it-up-and-running-on-your-pc-again/"><u>Lenovo Pad Not Responding? Get It Up & Running on Your PC Again</u></a></li>
<li><a href="https://win-blog.techidaily.com/resolving-common-problems-get-your-logitech-c920-camera-working-again/"><u>Resolving Common Problems: Get Your Logitech C920 Camera Working Again</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-windows-11-microphone-challenges-a-comprehensive-fix-guide/"><u>Solve Your Windows 11 Microphone Challenges: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-eliminating-the-troublesome-0x8007001f-update-issue-on-windows/"><u>Step-by-Step Solution: Eliminating the Troublesome 0X8007001F Update Issue on Windows</u></a></li>
<li><a href="https://media-tips.techidaily.com/top-5-ultimate-gif-compression-tools-for-faster-discord-uploads/"><u>Top 5 Ultimate GIF Compression Tools for Faster Discord Uploads</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-ethernet-connection-problems-in-windows-11-and-7/"><u>Troubleshooting Ethernet Connection Problems in Windows 11 and 7</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-shutdowns-on-windows-11/"><u>Unexpected Shutdowns on Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
