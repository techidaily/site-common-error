---
title: How to Fix the 'Windows 10 Installation Error (Code 80240020)' - A Step-by-Step Guide
date: 2024-10-12T16:38:51.324Z
updated: 2024-10-19T03:36:36.506Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix the 'Windows 10 Installation Error (Code 80240020)' - A Step-by-Step Guide
excerpt: This Article Describes How to Fix the 'Windows 10 Installation Error (Code 80240020)' - A Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/f35b950c7a8f4cdd1989c1e04c70b04dbfa6ce641c77398dacbaad68cbaf2be6.jpg
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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-efficient-chromebook-screen-logger/"><u>[Updated] In 2024, Efficient Chromebook Screen Logger</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-ranking-top-10-budget-friendly-video-editing-apps/"><u>[Updated] Ranking Top 10 Budget-Friendly Video Editing Apps</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-stellar-visuals-enhancing-google-meet-collaboration/"><u>[Updated] Stellar Visuals Enhancing Google Meet Collaboration</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-on-your-phone-discover-why-it-may-not-be-necessary-to-install/"><u>ChatGPT on Your Phone: Discover Why It May Not Be Necessary to Install</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-resolving-the-dreaded-error-code-0xa00f4292-on-windows-based-cameras/"><u>Expert Advice for Resolving the Dreaded Error Code 0xA00F4292 on Windows-Based Cameras</u></a></li>
<li><a href="https://sound-issues.techidaily.com/expert-tips-to-restore-sound-on-a-non-working-laptop/"><u>Expert Tips to Restore Sound on a Non-Working Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-eliminate-the-error-of-missing-d3dx939dll-file-on-your-computer/"><u>Fix Guide: Eliminate the Error of Missing D3DX9_39.dll File on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-vcruntime140dll-missing-file-issue-complete-solution/"><u>Fixing the VCRUNTIME140.dll Missing File Issue - Complete Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-erratic-screen-behavior-in-windows-11-a-comprehensive-guide/"><u>How to Stop Erratic Screen Behavior in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-tecno-spark-20c-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Tecno Spark 20C | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/insights-into-instagram-an-in-depth-analysis-guide-for-professionals/"><u>Insights Into Instagram An In-Depth Analysis Guide for Professionals</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-woes-repairing-damaged-up-down-left-and-right-arrow-keys/"><u>Keyboard Woes: Repairing Damaged Up, Down, Left and Right Arrow Keys</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-art-of-fixing-windows-11s-troublesome-bluetooth-a-2024-guide/"><u>Master the Art of Fixing Windows 11'S Troublesome Bluetooth: A 2024 Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/overcome-distorted-voice-in-virtual-meetings/"><u>Overcome Distorted Voice in Virtual Meetings</u></a></li>
<li><a href="https://hardware-help.techidaily.com/pcie-evolution-continues-explore-how-pcie-60s-new-thermal-technology-outperforms-its-predecessor/"><u>PCIe Evolution Continues: Explore How PCIe 6.0'S New Thermal Technology Outperforms Its Predecessor</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-0x800705b4-fault-during-windows-10-updates-a-complete-fix-guide/"><u>Resolving the 0X800705b4 Fault During Windows 10 Updates - A Complete Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-resolve-unknown-usb-device-errors-on-windows-11/"><u>Solving the Mystery: Resolve 'Unknown USB Device' Errors on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-lowering-wudfhost-cpu-usage-in-windows-ebuilds/"><u>Step-by-Step Guide to Lowering WUDFHost CPU Usage in Windows Ebuilds</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-honor-100-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Honor 100</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918661/19272" target="_top" id="1918661">
  <img src="//a.impactradius-go.com/display-ad/19272-1918661" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918661/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

