---
title: Effortless Solutions for Instant Windows Installation Errors
date: 2024-10-29T02:43:09.493Z
updated: 2024-11-04T22:24:08.788Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effortless Solutions for Instant Windows Installation Errors
excerpt: This Article Describes Effortless Solutions for Instant Windows Installation Errors
thumbnail: https://thmb.techidaily.com/4f442cf2fb2227aedd89e7821028b21747d22144c354cf210b05071a53d43806.jpg
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
<li><a href="https://facebook-video-recording.techidaily.com/new-your-roadmap-to-sourcing-videos-on-social-media-fb-edition-for-2024/"><u>[New] Your Roadmap to Sourcing Videos on Social Media (FB Edition) for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-complete-instagram-analytics-companion-transforming-metrics-into-strategy/"><u>[Updated] 2024 Approved The Complete Instagram Analytics Companion Transforming Metrics Into Strategy</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-how-to-preserve-your-roblox-experience-with-flawless-recording-mac/"><u>2024 Approved How to Preserve Your Roblox Experience with Flawless Recording (Mac)</u></a></li>
<li><a href="https://common-error.techidaily.com/5-proven-techniques-for-resolving-touchscreen-problems-in-windows-10/"><u>5 Proven Techniques for Resolving Touchscreen Problems in Windows 10</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Apple iPhone 13 | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-premium-mkv-player-for-windows-devices/"><u>In 2024, Premium MKV Player for Windows Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-chromes-mystery-a-guide-to-overcoming-complete-screen-darkness/"><u>Resolve Chrome's Mystery: A Guide to Overcoming Complete Screen Darkness</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-windows-10-crashing-at-boot/"><u>Resolved: How to Fix Windows 10 Crashing at Boot</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-the-0x80070490-error-on-your-windows-system/"><u>Troubleshooting and Solving the 0X80070490 Error on Your Windows System</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-vivo-y02t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Vivo Y02T | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938716/19272" target="_top" id="1938716">
  <img src="//a.impactradius-go.com/display-ad/19272-1938716" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938716/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

