---
title: "Resolved: Fixing the 0X8024401C Troubleshooting Guide for Windows Update on Windows 10 & 11"
date: 2024-09-29T03:30:53.622Z
updated: 2024-10-02T01:56:01.547Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing the 0X8024401C Troubleshooting Guide for Windows Update on Windows 10 & 11"
excerpt: "This Article Describes Resolved: Fixing the 0X8024401C Troubleshooting Guide for Windows Update on Windows 10 & 11"
thumbnail: https://thmb.techidaily.com/de76a8c110eaff7a166a09fee629e954d26d490c5f1eecc48133ce74b4cc31e3.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-unlocking-the-secrets-to-parallel-playback-prowess/"><u>[Updated] Unlocking the Secrets to Parallel Playback Prowess</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-liberate-your-video-files-free-online-tools-for-facebook-videos-in-1080phd/"><u>2024 Approved Liberate Your Video Files - Free Online Tools for Facebook Videos in 1080P/HD</u></a></li>
<li><a href="https://screen-recording.techidaily.com/comprehensive-guide-to-recording-hulu-across-platforms-for-2024/"><u>Comprehensive Guide to Recording Hulu Across Platforms for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/crucial-aspects-for-your-next-dash-cam-decision/"><u>Crucial Aspects for Your Next Dash Cam Decision</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-minecraft-mojang-error-code-5/"><u>How to Resolve Minecraft Mojang Error Code 5</u></a></li>
<li><a href="https://review-topics.techidaily.com/recover-iphone-14-plus-data-from-ios-icloud-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover iPhone 14 Plus Data From iOS iCloud | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-the-problem-of-malfunctioning-navigation-keys-on-your-keyboard/"><u>Solve the Problem of Malfunctioning Navigation Keys on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-repair-for-applicationexe-stop-error-in-windows/"><u>Step-by-Step Repair for Application.exe Stop Error in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/system-update-required-crtdll-missing/"><u>System Update Required: crt.dll Missing</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-m14-5g-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy M14 5G | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896555/19272" target="_top" id="1896555">
  <img src="//a.impactradius-go.com/display-ad/19272-1896555" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896555/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

