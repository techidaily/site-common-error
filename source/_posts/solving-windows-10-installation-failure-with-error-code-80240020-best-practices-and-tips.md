---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2025-02-23T20:45:58.696Z
updated: 2025-03-01T18:52:03.814Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
excerpt: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
thumbnail: https://thmb.techidaily.com/c616a530c3b86047af7fee8d712f3caf3cb46a3e47132cccfb907573c9519566.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-best-zoom-audio-settings-for-getting-audio-quality-2-ways/"><u>[New] In 2024, Best Zoom Audio Settings for Getting Audio Quality [2 Ways]</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-through-eyes-unseen-an-essential-vr-chronology-for-2024/"><u>[New] Through Eyes Unseen An Essential VR Chronology for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-seamlessly-embedding-youtube-subtitles-an-easy-to-follow-guide/"><u>[Updated] Seamlessly Embedding YouTube Subtitles An Easy-to-Follow Guide</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-apple-books-application-assessment/"><u>Comprehensive Apple Books Application Assessment</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-ways-to-restore-mic-functionality-on-your-steelseries-arctis-5-headset/"><u>Effective Ways to Restore Mic Functionality on Your SteelSeries Arctis 5 Headset</u></a></li>
<li><a href="https://article-files.techidaily.com/enhancing-media-interaction-with-smart-control-options/"><u>Enhancing Media Interaction with Smart Control Options</u></a></li>
<li><a href="https://article-files.techidaily.com/how-to-create-effective-intro-videos-for-your-podcasts/"><u>How to Create Effective Intro Videos for Your Podcasts</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-bluetooth-device-recognition-in-windows-11-fixes-and-tips-for-seamless-connectivity/"><u>Mastering Bluetooth Device Recognition in Windows 11 – Fixes and Tips for Seamless Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-easy-ways-to-overcome-steams-write-disc-error/"><u>Quick Guide: Easy Ways to Overcome Steam's Write Disc Error</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/the-ultimate-guide-to-recording-hulu-episodes-on-multiple-devices/"><u>The Ultimate Guide to Recording Hulu Episodes on Multiple Devices</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-nokia-c110-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Nokia C110 Reset Code | Dr.fone</u></a></li>
<li><a href="https://hardware-help.techidaily.com/top-framework-chromebook-assessment-an-unparalleled-mix-of-durability-and-longevity-a-comprehensive-guide/"><u>Top Framework Chromebook Assessment: An Unparalleled Mix of Durability and Longevity - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-speeding-up-your-computers-startup-process/"><u>Troubleshooting Tips for Speeding Up Your Computer's Startup Process</u></a></li>
<li><a href="https://common-error.techidaily.com/urgent-fix-required-enable-local-authorization-defenses-now/"><u>Urgent Fix Required: Enable Local Authorization Defenses Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-troubleshooting-steps-for-restoring-functionality-to-a-defective-bluetooth-mouse/"><u>Windows Troubleshooting: Steps for Restoring Functionality to a Defective Bluetooth Mouse</u></a></li>
</ul></div>

