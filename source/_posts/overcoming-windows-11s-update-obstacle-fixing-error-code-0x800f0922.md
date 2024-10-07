---
title: Overcoming Windows 11'S Update Obstacle - Fixing Error Code 0X800F0922
date: 2024-10-02T02:16:52.577Z
updated: 2024-10-07T06:43:31.157Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming Windows 11'S Update Obstacle - Fixing Error Code 0X800F0922
excerpt: This Article Describes Overcoming Windows 11'S Update Obstacle - Fixing Error Code 0X800F0922
thumbnail: https://thmb.techidaily.com/b3073e71d549e5dda027e19f13416a5fe4cf0a11fd5d20364906665ccf8e2b9a.jpg
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
<li><a href="https://some-approaches.techidaily.com/new-top-tier-mkv-players-macos-edition/"><u>[New] Top-Tier MKV Players MacOS Edition</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-deciphering-the-disappearance-of-recommended-video-content-in-your-newsfeed/"><u>[Updated] 2024 Approved Deciphering the Disappearance of Recommended Video Content in Your Newsfeed</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-effortless-exchange-idevice-images-and-videos-for-2024/"><u>[Updated] Effortless Exchange IDevice Images & Videos for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-post-update-boot-loops-on-windows-10-devices/"><u>Diagnosing and Repairing Post-Update Boot Loops on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-black-ops-4-fatal-errors/"><u>How to Fix Black Ops 4 Fatal Errors</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-motorola-razr-40-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Motorola Razr 40 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-art-of-resolving-endless-reboots-in-windows-11-effortlessly/"><u>Master the Art of Resolving Endless Reboots in Windows 11 Effortlessly</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/maximizing-ipad-audio-record-best-tips/"><u>Maximizing iPad Audio Record Best Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-windows-11-taskbar-top-techniques-for-unsticking-it-quickly-and-effectively/"><u>Reviving Your Windows 11 Taskbar: Top Techniques for Unsticking It Quickly and Effectively</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915810/19272" target="_top" id="1915810">
  <img src="//a.impactradius-go.com/display-ad/19272-1915810" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915810/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

