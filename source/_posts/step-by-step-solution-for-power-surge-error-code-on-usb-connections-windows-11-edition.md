---
title: Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
date: 2024-10-12T23:25:53.913Z
updated: 2024-10-18T21:29:30.273Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
excerpt: This Article Describes Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
thumbnail: https://thmb.techidaily.com/7f38f48d6c1e2e7dd4ffc2cf3530de002749e2e66d038be493fc55f20cd91a70.jpg
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
<li><a href="https://extra-support.techidaily.com/new-masterclass-in-virtual-reality-finger-hacks/"><u>[New] Masterclass in Virtual Reality Finger Hacks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-unlocking-higher-views-on-instagram-videos/"><u>[New] Unlocking Higher Views on Instagram Videos</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-how-to-unlock-full-potential-with-iphone-hdr/"><u>2024 Approved How to Unlock Full Potential with iPhone HDR</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-24-a-step-by-step-solution-for-missing-devices-in-windows-10-8-and-7/"><u>Error Code 24 - A Step-by-Step Solution for Missing Devices in Windows 10, 8 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-sims-4-opening-errors-quick-and-effective-solutions/"><u>Fixes for Sims 4 Opening Errors - Quick and Effective Solutions</u></a></li>
<li><a href="https://windows11.techidaily.com/how-to-create-a-linux-virtual-machine-inside-a-windows-virtual-machine-using-hyper-v/"><u>How to Create a Linux Virtual Machine Inside a Windows Virtual Machine Using Hyper-V</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-exclusive-fb-download-tools-optimized-for-firefox-users/"><u>In 2024, Exclusive FB Download Tools - Optimized For FireFox Users</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-itel-p55-5g-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Itel P55 5G</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/live-streaming-console-gaming-secrets-on-a-computer-for-2024/"><u>Live-Streaming Console Gaming Secrets on a Computer for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-disabled-wi-fi-functionality-a-comprehensive-guide/"><u>Resolving Issues with Disabled Wi-Fi Functionality: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-print-screen-failure-in-windows-10-and-windows-11-operating-systems/"><u>Resolving Print Screen Failure in Windows 10 and Windows 11 Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/technical-guide-to-optimal-playability-why-your-pc-must-have-a-d3d11-graphics-card-compatibility-to-run-the-engine-flawlessly/"><u>Technical Guide to Optimal Playability: Why Your PC Must Have a D3D11 Graphics Card Compatibility to Run the Engine Flawlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-at-windows-11-essential-tweaks-to-elevate-your-gaming-capabilities/"><u>Winning at Windows 11: Essential Tweaks to Elevate Your Gaming Capabilities</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

