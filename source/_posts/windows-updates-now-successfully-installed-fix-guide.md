---
title: "Windows Updates Now Successfully Installed: Fix Guide"
date: 2024-10-01T21:50:37.534Z
updated: 2024-10-07T07:55:38.934Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows Updates Now Successfully Installed: Fix Guide"
excerpt: "This Article Describes Windows Updates Now Successfully Installed: Fix Guide"
thumbnail: https://thmb.techidaily.com/86e7c4ea92c80232a2f22ec398fe1175bda0bfa79b5ffdb49f75954366a9ab9c.jpg
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-efficient-shortening-of-instagram-video-content-mac/"><u>[New] In 2024, Efficient Shortening of Instagram Video Content (Mac)</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/n-2024-pathway-to-youtube-partnerships-simplifying-the-process-for-small-creators/"><u>[New] In 2024, Pathway to YouTube Partnerships Simplifying the Process for Small Creators</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-top-ff-video-grab-extensions-and-tools-for-2024/"><u>[New] Top FF Video Grab - Extensions & Tools for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-mastery-guide-for-instagrams-favorite-interrogation-icon/"><u>2024 Approved Mastery Guide for Instagram's Favorite Interrogation Icon</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-vivo-y55s-5g-2023-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Vivo Y55s 5G (2023)</u></a></li>
<li><a href="https://fox-http.techidaily.com/balancing-intense-beats-with-fl-studios-easeful-dimming-for-2024/"><u>Balancing Intense Beats with FL Studio's Easeful Dimming for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-activating-bluetooth-on-your-pc-running-windows-10-or-11/"><u>Comprehensive Guide: Activating Bluetooth on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-malfunctioning-alphabet-keys-tips-for-windows-1011-users/"><u>Diagnosing & Fixing Malfunctioning Alphabet Keys: Tips for Windows 10/11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-print-to-pdf-feature-issues-on-windows-10-and-11/"><u>Fixing 'Print to PDF' Feature Issues on Windows 10 & 11</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-av1-decoded-a-novices-introduction/"><u>In 2024, AV1 Decoded A Novice's Introduction</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-vivo-v27-pro-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Vivo V27 Pro to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211794587-keyboard-arrow-keys-not-working-try-these-fixes/"><u>Keyboard Arrow Keys Not Working? Try These Fixes!</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-bluetooth-setup-a-comprehensive-guide-for-windows-1110-users/"><u>Mastering Bluetooth Setup: A Comprehensive Guide for Windows 11/10 Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/navigating-away-from-giant-tech-companies-like-microsoft-understanding-the-need-for-alternatives-in-government-systems/"><u>Navigating Away From Giant Tech Companies Like Microsoft: Understanding the Need for Alternatives in Government Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-persistent-windows-update-problem-clear-instructions-for-handling-error-0x8024402c/"><u>Overcoming the Persistent Windows Update Problem: Clear Instructions for Handling Error 0X8024402c</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-whirring-woes-diagnosing-and-fixing-the-root-of-loudness-problems/"><u>PS4 Whirring Woes - Diagnosing & Fixing the Root of Loudness Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-bluetooth-functionality-on-windows-10-fast-and-straightforward-fixes-inside/"><u>Revive Your Bluetooth Functionality on Windows 10: Fast and Straightforward Fixes Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-nonfunctioning-function-keys-on-dell-laptops/"><u>Step-by-Step Solutions for Nonfunctioning Function Keys on Dell Laptops</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-in-2024-zero-cost-4k-video-conversion-top-10-solutions/"><u>Updated In 2024, Zero-Cost 4K Video Conversion Top 10 Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1770544">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770544.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770544">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770544.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770544%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770544/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

