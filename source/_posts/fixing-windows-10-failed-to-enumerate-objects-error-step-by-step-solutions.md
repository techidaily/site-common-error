---
title: "Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions"
date: 2024-08-15T11:03:49.060Z
updated: 2024-08-16T11:03:49.060Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions"
excerpt: "This Article Describes Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions"
thumbnail: https://thmb.techidaily.com/a9441716968b4b370228db8f919eac0889d914a97cb067222fedd44de8e1315f.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://common-error.techidaily.com/alert-paste-problematic-windows-11-feature/"><u>[ALERT] Paste Problematic Windows 11 Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-device-not-migrated-on-windows-11/"><u>[Solved] Device Not Migrated on Windows 11</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-perfecting-your-screen-recording-during-games/"><u>[Updated] 2024 Approved  Perfecting Your Screen Recording During Games</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-decoding-the-divergence-360-film-vs-virtual-reality-for-2024/"><u>[Updated] Decoding the Divergence  360° Film Vs. Virtual Reality for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-top-10-gamer-vloggers-on-tiktok-today/"><u>[Updated] In 2024, Top 10 Gamer Vloggers on TikTok Today</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-fifteen-methods-to-reset-a-twitch-stream-in-real-time/"><u>2024 Approved  Fifteen Methods to Reset a Twitch Stream in Real-Time</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-ranking-macs-best-rated-sniping-programs/"><u>2024 Approved  Ranking Mac's Best-Rated Sniping Programs</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-blueprint-of-dynamic-dialogue-in-scripts/"><u>2024 Approved  The Blueprint of Dynamic Dialogue in Scripts</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-trendsetting-images-their-histories/"><u>2024 Approved  Trendsetting Images  Their Histories</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-buffs-expert-hacks-for-fast-tracking-league-of-legends-game-setup/"><u>Bypass Buffs: Expert Hacks for Fast-Tracking League of Legends Game Setup</u></a></li>
<li><a href="https://windows11.techidaily.com/camouflage-computing-integrating-archives-into-digital-image-win/"><u>Camouflage Computing: Integrating Archives Into Digital Image WIN</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolve-windows-update-error-0x8024002e-once-and-for-all/"><u>Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All!</u></a></li>
<li><a href="https://common-error.techidaily.com/decrease-your-computers-workload-combating-high-resource-demand-by-wudfhostexe-on-windows-fixed/"><u>Decrease Your Computer's Workload: Combating High Resource Demand by WUDFHost.exe on Windows ([Fixed])</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-to-combat-excessive-cpu-usage-by-microsofts-msmpengexe-in-win-11-environments/"><u>Effective Fixes to Combat Excessive CPU Usage by Microsoft's MsMpEng.exe in Win 11 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-for-overcoming-the-windows-update-error-0x80070002/"><u>Effortless Solutions for Overcoming the Windows Update Error 0X80070002</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205009552-effortlessly-fix-windows-10-bluetooth-disappearance-issues-in-minutes/"><u>Effortlessly Fix Windows 10 Bluetooth Disappearance Issues in Minutes</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-speaker-noise-on-your-pc-top-fixes-for-windows-11-and-7-systems/"><u>Eliminate Speaker Noise on Your PC: Top Fixes for Windows 11 and 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-computer-freezes-when-playing-games-easily/"><u>Fix Computer Freezes when Playing Games [Easily]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-tips-troubleshooting-a-non-functional-mic-on-windows-10/"><u>Fixes & Tips: Troubleshooting a Non-Functional Mic on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-non-functional-dell-webcam-on-windows-step-by-step-guide/"><u>Fixing a Non-Functional Dell Webcam on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-missing-d3dxt939dll-errors-in-windows-expert-solutions-and-tips/"><u>Fixing Missing d3dxt9_39.dll Errors in Windows - Expert Solutions and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-non-compatible-hardware-drivers-for-a-smoother-world-of-warcraft-experience/"><u>Fixing Non-Compatible Hardware Drivers for a Smoother World of Warcraft Experience</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-display-apple-iphone-14-screen-on-pc-easily-drfone-by-drfone-ios/"><u>How to Display Apple iPhone 14 Screen on PC Easily? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-d3derr-notavailable/"><u>How To Fix D3DERR NOTAVAILABLE</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-illumination-on-a-non-responsive-corsair-keyboard/"><u>How to Restore Illumination on a Non-Responsive Corsair Keyboard</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/navigate-and-organize-files-flawlessly-in-windows-10/"><u>Navigate and Organize Files Flawlessly in Windows 지정기 10</u></a></li>
<li><a href="https://common-error.techidaily.com/oddworld-soulstorm-crashing-on-pc-solved/"><u>Oddworld: Soulstorm Crashing On PC [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-how-to-resolve-undetected-battery-problems/"><u>Quick Troubleshooting: How to Resolve Undetected Battery Problems</u></a></li>
<li><a href="https://windows11.techidaily.com/real-time-resource-management-tracking-cpu-memory-and-graphics/"><u>Real-Time Resource Management: Tracking CPU, Memory & Graphics</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/reviving-rare-memories-turning-photos-into-engaging-videos-for-2024/"><u>Reviving Rare Memories  Turning Photos Into Engaging Videos for 2024</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-recent-calls-back-from-xiaomi-13t-by-fonelab-android-recover-call-logs/"><u>Simple ways to get recent calls back from Xiaomi 13T</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-connecting-your-microsoft-dock-with-windows-10-resolved/"><u>Step-by-Step Solution for Connecting Your Microsoft Dock with Windows 10 [Resolved]</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-launching-the-hosted-network-feature-in-windows-11-after-common-hurdles/"><u>Successfully Launching the Hosted Network Feature in Windows 11 After Common Hurdles</u></a></li>
<li><a href="https://windows11.techidaily.com/tackling-the-not-found-gpeditmsc-in-windows-errors/"><u>Tackling the Not Found: Gpedit.msc in Windows Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207450866-troubled-by-the-0x80072efd-mistake-on-your-pc-heres-how-to-resolve-it/"><u>Troubled by the 0X80072EFD Mistake on Your PC? Here’s How to Resolve It</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solutions-for-windows-resource-protection-failures/"><u>Troubleshooting and Solutions for Windows Resource Protection Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-get-dell-webcam-operational-on-windows-systems/"><u>Troubleshooting Guide: How to Get Dell Webcam Operational on Windows Systems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->