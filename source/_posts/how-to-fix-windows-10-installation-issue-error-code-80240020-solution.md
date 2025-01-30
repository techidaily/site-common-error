---
title: "How to Fix Windows 10 Installation Issue: Error Code 80240020 Solution"
date: 2025-01-28T19:52:27.578Z
updated: 2025-01-29T22:48:03.210Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix Windows 10 Installation Issue: Error Code 80240020 Solution"
excerpt: "This Article Describes How to Fix Windows 10 Installation Issue: Error Code 80240020 Solution"
thumbnail: https://thmb.techidaily.com/da588ad139882f359e01e1480116ed64f1f64c7e5500ad5bb32d29ff957df078.jpg
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
<li><a href="https://youtube-blog.techidaily.com/08858445-new-2024-approved-top-free-audio-samples-for-youtube-creators/"><u>[New] 2024 Approved Top Free Audio Samples for YouTube Creators</u></a></li>
<li><a href="https://common-error.techidaily.com/astro-a40-audio-problem-solved-reviving-the-built-in-microphone/"><u>Astro A40 Audio Problem Solved: Reviving the Built-In Microphone</u></a></li>
<li><a href="https://solve-latest.techidaily.com/automated-user-tracking-with-advanced-analytics-enhanced-via-cookiebot-technology/"><u>Automated User Tracking with Advanced Analytics - Enhanced via Cookiebot Technology</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-steps-to-repair-video-connection-issues-and-eliminate-error-messages/"><u>Comprehensive Steps to Repair Video Connection Issues and Eliminate Error Messages</u></a></li>
<li><a href="https://techtrends.techidaily.com/decoding-immersive-tech-distinguishing-ar-vr-mr-and-xr/"><u>Decoding Immersive Tech: Distinguishing AR, VR, MR & XR</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-crackling-sound-issues-on-speakers-for-windows-10-and-7-a-comprehensive-guide/"><u>Fixing Crackling Sound Issues on Speakers for Windows 10 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-huawei-nova-y71-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Huawei Nova Y71 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-your-vivo-x90ss-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>In 2024, Unlock Your Vivo X90Ss Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
<li><a href="https://solve-lab.techidaily.com/mpegflacmovavi/"><u>MPEG及FLAC間的無成本媒體轉換：使用Movavi 影片轉換器在線完成</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-character-errors-in-keyboard-input-effective-techniques-and-tips/"><u>Overcoming Character Errors in Keyboard Input: Effective Techniques and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-vcruntime140dll-missing-file-alert-step-by-step-fix-guide/"><u>Resolve VCRUNTIME140.dll Missing File Alert - Step-by-Step Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-abrupt-system-turnoffs-during-gaming-across-various-windows-systems-win11-win10-win7-win81-and-win8/"><u>Resolving Abrupt System Turnoffs During Gaming Across Various Windows Systems (Win11, Win10, Win7, Win8.1 & Win8)</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-windows-11-touch-display-top-5-methods/"><u>Revive Your Windows 11 Touch Display: Top 5 Methods</u></a></li>
<li><a href="https://windows11.techidaily.com/seamless-searching-on-windows-techniques-beyond-ls-command/"><u>Seamless Searching on Windows: Techniques Beyond LS Command</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/troubleshooting-your-google-drive-download-issues-expert-tips-and-solutions/"><u>Troubleshooting Your Google Drive Download Issues – Expert Tips and Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PNw3Lb26wFA?si=5NR1XRVSp41EQYMy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

