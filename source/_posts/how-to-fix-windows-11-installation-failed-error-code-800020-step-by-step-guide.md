---
title: How to Fix Windows 11 Installation Failed Error Code 80#0020 - Step-by-Step Guide
date: 2024-09-30T10:23:51.553Z
updated: 2024-10-07T07:33:05.135Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows 11 Installation Failed Error Code 80#0020 - Step-by-Step Guide
excerpt: This Article Describes How to Fix Windows 11 Installation Failed Error Code 80#0020 - Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/c48a785cefdb0843c6e76d439ab755593afd7522af39269117f83ccabe84316f.png
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-game-up-your-content-with-these-effective-freefire-video-hashtags/"><u>[Updated] 2024 Approved Game Up Your Content with These Effective FreeFire Video Hashtags</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-chucklecraft-sign-up-now-and-laugh-later/"><u>[Updated] ChuckleCraft Sign Up Now & Laugh Later</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-essential-tips-building-an-instagram-money-machine/"><u>[Updated] Essential Tips Building an Instagram Money Machine</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-zoom-and-google-meet-visual-clarity-your-step-by-step-guide-to-cleaner-participation/"><u>2024 Approved Zoom & Google Meet Visual Clarity Your Step-by-Step Guide to Cleaner Participation</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208009912-endless-cursor-flicker-heres-what-you-can-do-to-fix-it/"><u>Endless Cursor Flicker? Here's What You Can Do To Fix It</u></a></li>
<li><a href="https://tech-revival.techidaily.com/enjoy-endless-playlists-best-free-download-platforms-for-ipod-users/"><u>Enjoy Endless Playlists: Best Free Download Platforms for iPod Users</u></a></li>
<li><a href="https://common-error.techidaily.com/ensuring-ftdi-integrity-the-crucial-role-of-compatible-hardware-components-and-drivers/"><u>Ensuring FTDI Integrity: The Crucial Role of Compatible Hardware Components and Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/fixing-usbasp-on-xp-7-81-and-10-for-uninterrupted-use/"><u>Fixing USBasp on XP, 7, 8.1 & 10 for Uninterrupted Use</u></a></li>
<li><a href="https://tech-haven.techidaily.com/implementing-gpt-4s-cutting-edge-technology-in-your-conversations-with-chatgpt-live-demonstration-and-tutorial/"><u>Implementing GPT-4's Cutting-Edge Technology in Your Conversations with ChatGPT: Live Demonstration and Tutorial</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/in-2024-premier-free-audio-to-image-software-for-iphones-and-tablets/"><u>In 2024, Premier Free Audio-To-Image Software for iPhones and Tablets</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-resolution-for-non-functioning-airdrop-effortless-solutions-explained/"><u>Quick Resolution for Non-Functioning AirDrop: Effortless Solutions Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-restore-your-dell-speaker-functionality/"><u>Step-by-Step Tips to Restore Your Dell Speaker Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-frustrating-twitch-error-code-4000/"><u>Ultimate Guide: Resolving the Frustrating Twitch Error Code 4000</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-adobe-premiere-pros-secret-weapons-top-15-plugins-you-need-free-and-paid/"><u>Updated Adobe Premiere Pros Secret Weapons Top 15 Plugins You Need (Free & Paid)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

