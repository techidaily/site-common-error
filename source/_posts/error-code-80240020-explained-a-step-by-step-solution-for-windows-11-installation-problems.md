---
title: Error Code 80240020 Explained - A Step-by-Step Solution for Windows 11 Installation Problems
date: 2024-09-19T17:02:45.249Z
updated: 2024-09-20T19:03:03.827Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error Code 80240020 Explained - A Step-by-Step Solution for Windows 11 Installation Problems
excerpt: This Article Describes Error Code 80240020 Explained - A Step-by-Step Solution for Windows 11 Installation Problems
thumbnail: https://thmb.techidaily.com/c3881c9b3280f6181e5e31cdf97813641b81345019e7ba1cde62d3c30be7801d.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-how-many-seconds-is-a-20mb-video/"><u>[Updated] 2024 Approved How Many Seconds Is a 20Mb Video</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-ultimate-guide-top-10-high-quality-no-cost-recording-tools/"><u>2024 Approved Ultimate Guide Top 10 High-Quality, No-Cost Recording Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-addressing-video-drivers-restart-issues-successfully/"><u>Comprehensive Guide to Addressing Video Drivers Restart Issues Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-non-functional-volume-buttons-in-windows-10-fixed/"><u>How to Fix Non-Functional Volume Buttons in Windows 10 [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-non-responsive-right-click-in-windows-10-a-step-by-step-guide/"><u>Resolving Non-Responsive Right Click in Windows 10 – A Step-by-Step Guide</u></a></li>
<li><a href="https://program-issues.techidaily.com/roblox-stability-fix-6-rapid-repairs-to-enhance-your-gaming-pc/"><u>Roblox Stability Fix: 6 Rapid Repairs to Enhance Your Gaming PC</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/streamline-your-workflow-easy-gopro-video-editing-on-macbook-with-quik/"><u>Streamline Your Workflow Easy GoPro Video Editing on MacBook with Quik</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-solution-to-starting-problems-reviving-your-unresponsive-pc/"><u>The Solution to Starting Problems: Reviving Your Unresponsive PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/top-5-solutions-for-resolving-the-no-user-logon-issue-in-cs-go/"><u>Top 5 Solutions for Resolving the 'No User Logon' Issue in CS: GO</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208426611-troubleshoot-and-solve-the-0x887a0006-glitch-in-no-time/"><u>Troubleshoot and Solve the 0X887A0006 Glitch in No Time</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/m4a-3gpp/"><u>オンラインで簡単にM4Aファイルを無料変換: 3GPP コーデック手転</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2141680/17091" target="_top" id="2141680">
  <img src="//a.impactradius-go.com/display-ad/17091-2141680" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettieu.pxf.io/i/5597632/2141680/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
