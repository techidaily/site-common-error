---
title: "Quick Resolution for Error 1603: Eliminating Fatal Issues During Installation"
date: 2024-10-01T01:50:48.461Z
updated: 2024-10-07T11:00:33.197Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Quick Resolution for Error 1603: Eliminating Fatal Issues During Installation"
excerpt: "This Article Describes Quick Resolution for Error 1603: Eliminating Fatal Issues During Installation"
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-access-the-latest-social-interactions-watch-facebook-live-on-roku/"><u>[New] In 2024, Access the Latest Social Interactions Watch Facebook Live on Roku</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-realme-c51-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Realme C51 PC | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/best-methods-to-unfreeze-your-windows-10-desktop-bar-a-guide/"><u>Best Methods to Unfreeze Your Windows 10 Desktop Bar: A Guide</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/chortle-chamber-ideas-for-7-amusing-online-sessions-for-2024/"><u>Chortle Chamber Ideas for 7 Amusing Online Sessions for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/elite-cameras-perfect-for-professional-podcasting/"><u>Elite Cameras Perfect for Professional Podcasting</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-fixes-for-when-you-cant-reach-destiny-2-servers-a-players-handbook/"><u>Essential Fixes for When You Can't Reach Destiny 2 Servers: A Player's Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-incompatibility-updating-your-devices-driver-for-optimal-wow-performance/"><u>Fixing Incompatibility: Updating Your Device's Driver for Optimal WoW Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/pam-varies-amplitude-but-not-pulse-width-or-frequency/"><u>PAM Varies Amplitude but Not Pulse Width or Frequency.</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-troubleshooting-resolving-system-locks-on-windows-11/"><u>Step-by-Step Troubleshooting: Resolving System Locks on Windows 11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/this-chrome-extension-makes-chatgpt-prompting-easy/"><u>This Chrome Extension Makes ChatGPT Prompting Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-resolve-destiny-n-initializing-problems/"><u>Troubleshooting Steps To Resolve Destiny N Initializing Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-reboot-triggers-in-win10/"><u>Unexpected Reboot Triggers in Win10</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-free-online-movie-making-software-top-picks-for-2024/"><u>Updated Free Online Movie Making Software Top Picks for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

