---
title: Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]
date: 2024-12-03T20:14:40.349Z
updated: 2024-12-10T18:20:07.745Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]
excerpt: This Article Describes Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]
thumbnail: https://thmb.techidaily.com/aa9290eddc8ec2cc97b63ee765b598d95b8b81e9c2cca36d2d92b110af8ad1f5.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://youtube-lab.techidaily.com/onquer-youtubes-copy-paste-loop-mastery-essentials/"><u>[New] Conquer YouTube's Copy-Paste Loop Mastery Essentials</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-tiktoks-viral-rhymes-a-guide-to-popular-rap-songs/"><u>[New] In 2024, TikTok's Viral Rhymes A Guide to Popular Rap Songs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-mac-enthusiasts-take-on-screenflow-software-review/"><u>[Updated] 2024 Approved Mac Enthusiast's Take on ScreenFlow Software Review</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-explore-template-treasures-to-craft-unique-corporate-emblems/"><u>[Updated] Explore Template Treasures to Craft Unique Corporate Emblems</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-how-to-use-story-remix-to-edit-a-video-in-windows-10-photos-for-2024/"><u>[Updated] How to Use Story Remix to Edit a Video in Windows 10 Photos for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-best-practices-for-compliant-twitter-videos/"><u>[Updated] In 2024, Best Practices for Compliant Twitter Videos</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/exploring-the-enhanced-viewing-experience-of-apple-tv-with-ultra-hd-quality-and-innovative-voice-controls/"><u>Exploring the Enhanced Viewing Experience of Apple TV with Ultra HD Quality and Innovative Voice Controls</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-your-pc-refresh-a-step-by-step-walkthrough-for-windows-11-reboot/"><u>Fast-Track Your PC Refresh: A Step-by-Step Walkthrough for Windows 11 Reboot</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-lenovo-wifi-error-no-appropriate-driver-to-be-installed/"><u>Fix Lenovo WiFi Error: No Appropriate Driver to Be Installed</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-stuck-boot-loops-overcome-being-trapped-at-setting-up-windows-prepare-effortlessly/"><u>Fixing Stuck Boot Loops: Overcome Being Trapped at 'Setting Up Windows Prepare' Effortlessly</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/top-5-cinematiccamera-tips-of-2024/"><u>Top 5 Cinematic/Camera Tips Of 2024</u></a></li>
<li><a href="https://fox-useful.techidaily.com/troubleshooting-guide-successfully-updating-and-installing-windows-11-via-usb-drives/"><u>Troubleshooting Guide: Successfully Updating & Installing Windows 11 via USB Drives</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-persistent-restart-cycles-in-windows-1110-effective-fixes-revealed/"><u>Winning Against Persistent Restart Cycles in Windows 11/10 - Effective Fixes Revealed</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

