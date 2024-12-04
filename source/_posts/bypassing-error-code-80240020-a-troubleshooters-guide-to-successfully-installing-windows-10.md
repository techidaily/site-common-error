---
title: "Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10"
date: 2024-11-27T06:43:20.888Z
updated: 2024-12-04T02:34:16.691Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10"
excerpt: "This Article Describes Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10"
thumbnail: https://thmb.techidaily.com/d009fff2d2f1ae33a60244be6a10e60fe9a4c6152d14b10a6c314e65ab841263.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://fox-access.techidaily.com/new-in-2024-cutting-edge-tools-for-optimal-yt-titles/"><u>[New] In 2024, Cutting-Edge Tools for Optimal YT Titles</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-innovative-design-and-graphics-free-and-affordable-sources/"><u>[New] In 2024, Innovative Design and Graphics Free & Affordable Sources</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-tune-into-trends-how-to-mix-music-in-storytelling-for-2024/"><u>[New] Tune Into Trends How to Mix Music in Storytelling for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-simple-screen-recorder-for-windows-10-for-2024/"><u>[Updated] Simple Screen Recorder for Windows 10 for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/13-napja-legjobb-a-youtube-videokra-mp3-val-konvertalas-orakig/"><u>13 Napja Legjobb - A YouTube Videókra MP3-Val Konvertálás Órákig</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/boost-your-photo-skills-with-these-top-pixlr-tricks-for-2024/"><u>Boost Your Photo Skills with These Top Pixlr Tricks for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/busting-wi-fi-dead-zones-a-look-at-the-amplifi-hd-smart-mesh-solution/"><u>Busting Wi-Fi Dead Zones: A Look at the Amplifi HD Smart Mesh Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-for-debugging-and-repairing-opengl-errors-within-minecraft/"><u>Effective Techniques for Debugging and Repairing OpenGL Errors Within Minecraft</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-of-brightness-adjustment-in-windows-11-pcs/"><u>How to Restore Functionality of Brightness Adjustment in Windows 11 PCs</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-channel-marketing-making-a-trailer-that-sells-more/"><u>In 2024, Channel Marketing Making a Trailer that Sells More</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-videos-from-gionee-f3-pro-to-ipad-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Videos from Gionee F3 Pro to iPad | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-a-network-locked-nokia-c300-phone-by-drfone-android/"><u>In 2024, How to Unlock a Network Locked Nokia C300 Phone?</u></a></li>
<li><a href="https://common-error.techidaily.com/issue-fixed-cannot-write-data-to-specific-0xreferenced-memory-location/"><u>Issue Fixed: Cannot Write Data to Specific 0xReferenced Memory Location</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-game-freezing-in-valorant-restart-advise/"><u>Overcome Game Freezing in Valorant: Restart Advise</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-of-a-non-charging-dualshock-4-for-playstation-4-gamers/"><u>Solving the Issue of a Non-Charging Dualshock 4 for PlayStation 4 Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-managing-high-wudfhostexe-cpu-drain-on-windows-10-machines/"><u>Step-by-Step Guide to Managing High WUDFHost.exe CPU Drain on Windows 10 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-your-devices-unwanted-power-naps-with-easy-tips/"><u>Troubleshoot Your Device's Unwanted Power Naps with Easy Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-pc-reset-problem-on-windows-10-complete-solution/"><u>Troubleshooting and Fixing the PC Reset Problem on Windows 10 [Complete Solution]</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-msda80dll-importance-and-maintenance-tips/"><u>Understanding MSDA80.DLL: Importance and Maintenance Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AcAYRX0cwwA?si=DxqWU39vqksZbe1s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

