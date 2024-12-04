---
title: "Fix Guide: Overcome 'Windows 11 Installer Error Code 80240020'"
date: 2024-11-28T17:43:50.290Z
updated: 2024-12-04T05:57:34.075Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fix Guide: Overcome 'Windows 11 Installer Error Code 80240020'"
excerpt: "This Article Describes Fix Guide: Overcome 'Windows 11 Installer Error Code 80240020'"
thumbnail: https://thmb.techidaily.com/7231e7cfa11b8c48bc0e8ca6efb14ca7e0a26276b7faf838f32af6539b7e71cf.jpg
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
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-sonys-shutterbug-fixing-the-no-video-fiasco/"><u>[Updated] 2024 Approved Sony's Shutterbug Fixing the No-Video Fiasco</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-mastering-skype-calls-on-pc-and-mac-free-vs-paid-recording-tips-for-2024/"><u>[Updated] Mastering Skype Calls on PC & Mac Free vs Paid Recording Tips for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-twitter-image-resolution-standards/"><u>[Updated] Twitter Image Resolution Standards</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-unleash-the-potential-of-your-video-with-best-thumbnail-fonts/"><u>2024 Approved Unleash the Potential of Your Video with Best Thumbnail Fonts</u></a></li>
<li><a href="https://common-error.techidaily.com/bring-back-the-keys-tablet-saved/"><u>Bring Back The Keys! Tablet Saved</u></a></li>
<li><a href="https://solve-helper.techidaily.com/fast-mp4-to-mp3-transformation-techniques-for-windows-users/"><u>Fast MP4 to MP3 Transformation Techniques for Windows Users</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-honor-play-8t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Honor Play 8T | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-snapsnatcher-fb-media-extraction/"><u>In 2024, SnapSnatcher FB Media Extraction</u></a></li>
<li><a href="https://some-approaches.techidaily.com/1726227793221-movavi/"><u>Movavi 라이브 스트리밭으로 만드는 정품 캡쳐: 영상 녹음 지형학</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-windows-10s-delayed-shutdown-bug-get-started/"><u>Quick Fixes for Windows 10'S Delayed Shutdown Bug - Get Started</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-when-your-bluetooth-mouse-stops-working-on-windows-computers/"><u>Quick Solutions for When Your Bluetooth Mouse Stops Working on Windows Computers</u></a></li>
<li><a href="https://windows11.techidaily.com/reinstating-lost-gesture-control-on-pcs-running-windows/"><u>Reinstating Lost Gesture Control on PCs Running Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212456673-resolve-your-overwatch-audio-glitches-instantly/"><u>Resolve Your Overwatch Audio Glitches Instantly</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-fatal-error-code-1603-in-installations-a-comprehensive-guide-to-recovery/"><u>Solving Fatal Error Code 1603 in Installations - A Comprehensive Guide to Recovery</u></a></li>
<li><a href="https://techtrends.techidaily.com/spotlight-on-sonys-afela-decoding-expected-price-points-release-dates-and-rumored-vehicle-capabilities/"><u>Spotlight on Sony's AFELA: Decoding Expected Price Points, Release Dates & Rumored Vehicle Capabilities</u></a></li>
<li><a href="https://common-error.techidaily.com/trim-high-cpu-usage-in-win11-via-wmi-enhancements/"><u>Trim High CPU Usage in Win11 via WMI Enhancements</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204854376-trouble-with-netflix-discover-why-its-not-streaming-and-how-to-fix-it/"><u>Trouble with Netflix? Discover Why It's Not Streaming and How to Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-resolve-d3d-error-not-available/"><u>Troubleshooting Steps to Resolve D3D Error 'Not Available'</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-update-stuck-or-frozen-how-do-i-fix-it/"><u>Windows 11 Update Stuck or Frozen - How Do I Fix It?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tPgf_wSdhS8?si=BHoH1ryaxmwk-8FV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

