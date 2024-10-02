---
title: "Overcoming the Windows 11 Update Failure: Error Code 0X80240034 Explained"
date: 2024-09-24T21:05:53.321Z
updated: 2024-10-01T22:37:08.041Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming the Windows 11 Update Failure: Error Code 0X80240034 Explained"
excerpt: "This Article Describes Overcoming the Windows 11 Update Failure: Error Code 0X80240034 Explained"
thumbnail: https://thmb.techidaily.com/3da10c18ed5eb1d81fc33e9b77c3f37bbadf618042f3295c06f9d5e5b10aa5c0.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-rehabilitating-faulty-obs-camera-connection/"><u>[Updated] In 2024, Rehabilitating Faulty OBS Camera Connection</u></a></li>
<li><a href="https://facebook.techidaily.com/deconstructing-digital-disguises-on-social-media/"><u>Deconstructing Digital Disguises on Social Media</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-resolve-error-code-0x80n0f0922-in-windows-10-updates/"><u>Effective Strategies to Resolve Error Code 0X80n0f0922 in Windows 10 Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-login-problems-the-user-profile-service-failure-on-windows-11-explained/"><u>Fixing Login Problems: The User Profile Service Failure on Windows 11 Explained</u></a></li>
<li><a href="https://techidaily.com/how-to-upgrade-apple-iphone-12-pro-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Upgrade Apple iPhone 12 Pro without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-pioneering-virtual-voyages-with-jaunt-vr/"><u>In 2024, Pioneering Virtual Voyages with Jaunt VR</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/in-2024-top-5-free-video-compression-apps-for-iphone-and-ipad/"><u>In 2024, Top 5 Free Video Compression Apps for iPhone and iPad</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-stability-advanced-fixes-for-persistent-lag-in-fallout-4-yearbook/"><u>Mastering Stability: Advanced Fixes for Persistent Lag in Fallout 4 [Yearbook]</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/nebula-network-nexus-space-data-lifesaver/"><u>Nebula Network Nexus - Space Data Lifesaver</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolved-how-to-fix-the-fifa-2020-game-crash-issue/"><u>Resolved: How to Fix the FIFA 2020 Game Crash Issue</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/reviving-cut-off-livestreams-solving-facebook-streaming-hiccups/"><u>Reviving Cut-Off Livestreams Solving Facebook Streaming Hiccups</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-non-responsive-touchpad-solutions-and-tips/"><u>Troubleshooting a Non-Responsive Touchpad: Solutions & Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

