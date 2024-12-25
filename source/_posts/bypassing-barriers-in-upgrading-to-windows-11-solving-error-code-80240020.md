---
title: Bypassing Barriers in Upgrading to Windows 11 - Solving Error Code 80240020
date: 2024-12-24T16:29:12.523Z
updated: 2024-12-25T19:28:24.942Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Bypassing Barriers in Upgrading to Windows 11 - Solving Error Code 80240020
excerpt: This Article Describes Bypassing Barriers in Upgrading to Windows 11 - Solving Error Code 80240020
thumbnail: https://thmb.techidaily.com/ddf4423afddb9cc05befc8c29dab68251d90672059623bcb13035bb3744866c7.png
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-muting-mastery-keeping-your-meeting-focus-on-google-go/"><u>[New] 2024 Approved Muting Mastery Keeping Your Meeting Focus on Google Go</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-leveraging-vocal-charisma-to-enrich-ppt-storytelling-for-2024/"><u>[New] Leveraging Vocal Charisma to Enrich PPT Storytelling for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-musical-spectacles-the-best-top-10-videos-on-facebook/"><u>2024 Approved Musical Spectacles The Best Top 10 Videos on Facebook</u></a></li>
<li><a href="https://common-error.techidaily.com/handling-windows-11-freezes-effective-solutions-and-troubleshooting-steps/"><u>Handling Windows 11 Freezes: Effective Solutions and Troubleshooting Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-solutions-for-audio-files-missing-dlls/"><u>Immediate Solutions for Audio Files' Missing DLLs</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-starting-with-av1-an-essential-overview/"><u>In 2024, Starting with AV1 An Essential Overview</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-the-ultimate-list-of-animation-tools-for-schools/"><u>New In 2024, The Ultimate List of Animation Tools for Schools</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719581601937-rapid-norwegian-understanding-10-daily-moments/"><u>Rapid Norwegian Understanding, 10 Daily Moments!</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-dimmed-keyboard-expert-tips-for-reactivating-backlight-on-macs-and-pcs/"><u>Reviving Your Dimmed Keyboard - Expert Tips for Reactivating Backlight on Macs and PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-to-cut-out-problems-with-logitech-g930-bluetooth-headset/"><u>Solutions to Cut-Out Problems with Logitech G930 Bluetooth Headset</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-most-upvoted-reddit-post-of-all-time-a-list-of-10/"><u>The Most Upvoted Reddit Post of All Time - (A List of 10)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/lCpzYpVPIZA?si=hNte-mPRIzjvqpRy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

