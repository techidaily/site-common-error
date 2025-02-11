---
title: "Resolved: Fixing Issues with the BattlEye Anti-Cheat Installation"
date: 2025-02-10T07:40:47.566Z
updated: 2025-02-11T01:35:53.931Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing Issues with the BattlEye Anti-Cheat Installation"
excerpt: "This Article Describes Resolved: Fixing Issues with the BattlEye Anti-Cheat Installation"
thumbnail: https://thmb.techidaily.com/44b00e7ceffa68921ecf622a184f48a9d902f80a57b12969c744bb786188a75e.png
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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-how-to-secure-youtube-channels-audible-content/"><u>[Updated] 2024 Approved How to Secure YouTube Channels' Audible Content</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-the-playlist-wizard-youtube-music-edition/"><u>[Updated] The Playlist Wizard YouTube Music Edition</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-advanced-approach-harnessing-watch-for-mac-unlock/"><u>2024 Approved Advanced Approach Harnessing Watch for Mac Unlock</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-resolving-high-cpu-demands-of-svchostexe-in-windows-11-systems/"><u>Diagnosing & Resolving High CPU Demands of svchost.exe in Windows 11 Systems</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/excels-scalability-triumphs-over-ai-dialogue-systems/"><u>Excel's Scalability Triumphs Over AI Dialogue Systems</u></a></li>
<li><a href="https://fox-direct.techidaily.com/exclusive-selection-of-vr-for-drone-pilots/"><u>Exclusive Selection of VR for Drone Pilots</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/how-to-access-and-view-stored-wireless-network-passwords-in-windows-11/"><u>How to Access and View Stored Wireless Network Passwords in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-11s-svchostexe-eating-up-your-processor-speedily/"><u>How to Fix Windows 11’S svchost.exe Eating Up Your Processor Speedily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-excessive-cpu-use-by-realtek-ravbg64exe-in-your-system/"><u>How to Stop Excessive CPU Use by Realtek 'ravbg64.exe' In Your System</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-elite-digital-tunes-transmission-service/"><u>In 2024, Elite Digital Tunes Transmission Service</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-common-issues-with-a-nonfunctioning-dell-keyboard-a-comprehhemic-guide/"><u>Overcoming Common Issues with a Nonfunctioning Dell Keyboard: A Comprehhemic Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/rescue-offscreen-windows-with-simple-tricks-and-tips/"><u>Rescue Offscreen Windows with Simple Tricks and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-the-hosted-network-cannot-start-error-in-windows-10/"><u>Resolved: How to Fix the 'Hosted Network Cannot Start' Error in Windows 10</u></a></li>
<li><a href="https://win11-tips.techidaily.com/techniques-to-maintain-calc-leading-placement/"><u>Techniques to Maintain Calc Leading Placement</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-guide-for-when-your-touchpads-pointer-goes-mia-in-windows-11/"><u>The Ultimate Fix Guide for When Your Touchpad's Pointer Goes MIA in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-rated-wireless-router-and-cable-modem-bundles/"><u>Top-Rated Wireless Router & Cable Modem Bundles</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/td3ojuzhloY?si=N_maQNiJWrJp7XZl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

