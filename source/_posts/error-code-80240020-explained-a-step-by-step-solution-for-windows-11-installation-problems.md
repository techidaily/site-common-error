---
title: Error Code 80240020 Explained - A Step-by-Step Solution for Windows 11 Installation Problems
date: 2024-09-28T04:10:44.464Z
updated: 2024-10-01T18:56:55.126Z
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-enrich-facebook-tales-unlimited-no-cost-online-and-mobile-upgrades/"><u>[New] 2024 Approved Enrich Facebook Tales Unlimited, No-Cost Online & Mobile Upgrades</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-ride-the-waves-with-top-picks-for-surfing-cams/"><u>[New] Ride the Waves with Top Picks for Surfing Cams</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-a-deep-dive-into-zdsoft-recorder-features-for-2024/"><u>[Updated] A Deep Dive Into ZDSoft Recorder Features for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-eliminating-crackling-sounds-from-native-windows-media-center-sound-system/"><u>Diagnosing and Eliminating Crackling Sounds From Native Windows Media Center Sound System</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212143161-experience-uninterrupted-updates-on-windows-11-solve-error-code-0x800f0922-using-our-top-fixes/"><u>Experience Uninterrupted Updates on Windows 11: Solve ERROR CODE 0X800F0922 Using Our Top Fixes</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-enable-gpu-usage-for-optimal-performance-in-cyberpunk-2077-on-windows/"><u>How to Enable GPU Usage for Optimal Performance in Cyberpunk 2077 on Windows</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-watch-avchd-mts-video-on-redmi-note-13-proplus-5g-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to watch AVCHD MTS video on Redmi Note 13 Pro+ 5G?</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-ae-text-and-title-styles-guide/"><u>In 2024, AE Text & Title Styles Guide</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-easy-guide-how-to-bypass-realme-narzo-60-pro-5g-frp-android-10111213-by-drfone-android/"><u>In 2024, Easy Guide How To Bypass Realme Narzo 60 Pro 5G FRP Android 10/11/12/13</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ity-of-capturing-and-reproducing-youtube-video-playbacks/"><u>Legality of Capturing and Reproducing YouTube Video Playbacks</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-fixes-for-the-elusive-error-in-windows-installer-services/"><u>Mastering Fixes for the Elusive Error in Windows Installer Services</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-quick-fixes-for-windows-11-and-errorcode-0x80072f8f/"><u>Mastering Quick Fixes for Windows 11 and #ErrorCode 0X80072F8f</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-safe-shutdowns-on-a-windows-n-based-system-troubleshooting-tips-and-solutions/"><u>Mastering Safe Shutdowns on a Windows N-Based System – Troubleshooting Tips & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-common-huion-pen-issues-quickly-5-proven-fixes-for-smoother-drawing/"><u>Solve Common Huion Pen Issues Quickly – 5 Proven Fixes for Smoother Drawing</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/step-by-step-guide-to-effective-screen-recording-with-mobizen/"><u>Step-by-Step Guide to Effective Screen Recording with Mobizen</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-to-combat-high-resource-drain-caused-by-wudfhostexe-on-windows-10-systems/"><u>Tips to Combat High Resource Drain Caused by WUDFHost.exe on Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-minecrafts-opengl-issues-step-by-step-solutions/"><u>Ultimate Guide: Resolving Minecraft's OpenGL Issues - Step by Step Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

