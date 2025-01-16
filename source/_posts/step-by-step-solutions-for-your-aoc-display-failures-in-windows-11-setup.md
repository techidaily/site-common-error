---
title: Step-by-Step Solutions for Your AOC Display Failures in Windows 11 Setup
date: 2025-01-09T16:03:45.710Z
updated: 2025-01-16T16:01:58.060Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Your AOC Display Failures in Windows 11 Setup
excerpt: This Article Describes Step-by-Step Solutions for Your AOC Display Failures in Windows 11 Setup
thumbnail: https://thmb.techidaily.com/7b61f24c759b4bb707c98e4d5ba6ea429d7484a4ebc98b905ced6f7c4d8a2b63.jpg
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
<li><a href="https://snapchat-videos.techidaily.com/new-innovative-pathways-ensuring-correct-iphone-snapchat-data-flow-for-2024/"><u>[New] Innovative Pathways Ensuring Correct iPhone-Snapchat Data Flow for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-leveraging-zooms-full-spectrum-of-live-video-capabilities/"><u>[New] Leveraging Zoom's Full Spectrum of Live Video Capabilities</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-unleash-your-creative-genius-with-iphone-x-camera/"><u>2024 Approved Unleash Your Creative Genius with iPhone X Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211010595-dragon-ball-fighterz-connectivity-issue-successfully-resolved/"><u>Dragon Ball FighterZ Connectivity Issue - Successfully Resolved!</u></a></li>
<li><a href="https://fox-glue.techidaily.com/enhance-virtual-engagement-streaming-with-finesse-using-zoom-and-youtube-live-for-2024/"><u>Enhance Virtual Engagement Streaming with Finesse Using Zoom and YouTube Live for 2024</u></a></li>
<li><a href="https://discover-bits.techidaily.com/expert-tips-from-yl-computing-secreting-data-invisible-to-others-in-windows-11/"><u>Expert Tips From YL Computing: Secreting Data Invisible to Others in Windows 11</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/1722974437910-fire-extinguishing-agents-work-by-interrupting-the-chemical-reactions-involved-in-combustion/"><u>Fire Extinguishing Agents Work by Interrupting the Chemical Reactions Involved in Combustion</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-crackling-sound-on-speakers-for-windows-11-and-7-users-resolved/"><u>How to Fix Crackling Sound on Speakers for Windows 11 & 7 Users – Resolved!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-the-challenge-of-an-unresponsive-dns-top-five-strategies/"><u>Overcoming the Challenge of an Unresponsive DNS: Top Five Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-steps-to-stop-excessive-cpu-consumption-by-wudfhostexe-on-windows-10/"><u>Resolved: Troubleshooting Steps to Stop Excessive CPU Consumption by wudfhost.exe on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-unpairing-problems-in-windows-10-bluetooth-devices/"><u>Step-by-Step Solutions for Unpairing Problems in Windows 10 Bluetooth Devices</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/the-updated-method-to-bypass-vivo-v30-lite-5g-frp-by-drfone-android/"><u>The Updated Method to Bypass Vivo V30 Lite 5G FRP</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-laptop-trackpad-issues-on-windows-11-8-and-7/"><u>Troubleshooting Guide: Fixing Laptop Trackpad Issues on Windows 11, 8 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-your-logitech-scroll-wheel-stops-working-correctly/"><u>Troubleshooting Tips for When Your Logitech Scroll Wheel Stops Working Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-how-to-get-your-usb-mouse-back-in-action-on-a-laptop/"><u>Troubleshooting: How to Get Your USB Mouse Back in Action on a Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-the-mystery-of-persistent-usb-disconnections/"><u>Ultimate Guide: Solving the Mystery of Persistent USB Disconnections</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/unlocking-network-diagnostics-how-to-execute-the-tracert-tool-in-windows/"><u>Unlocking Network Diagnostics: How to Execute the Tracert Tool in Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

