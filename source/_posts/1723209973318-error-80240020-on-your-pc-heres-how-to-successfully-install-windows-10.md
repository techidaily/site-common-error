---
title: Error 80240020 on Your PC? Here's How to Successfully Install Windows 10!
date: 2024-10-25T17:02:38.445Z
updated: 2024-10-30T16:13:57.675Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10!
excerpt: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10!
thumbnail: https://thmb.techidaily.com/f946d84f254099655a6b886de29d65e5f587fa0ecc62cec124a4f1eb3cdbb6d6.jpg
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
<li><a href="https://extra-hints.techidaily.com/new-a-step-by-step-approach-how-to-record-and-archive-online-radio/"><u>[New] A Step-by-Step Approach How To Record & Archive Online Radio</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-mastering-multimedia-content-putting-photos-together-on-insta-story/"><u>[Updated] In 2024, Mastering Multimedia Content Putting Photos Together on Insta Story</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209874334-bluetooth-connection-problems-in-windows-10-heres-how-to-fix-them/"><u>Bluetooth Connection Problems in Windows 10? Here's How to Fix Them!</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-winupdate-issue-zero-hour-fixes-for-error-0x80070002/"><u>Bypassing WinUpdate Issue - Zero Hour Fixes for Error 0X80070002</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-messages-from-infinix-smart-8-by-fonelab-android-recover-messages/"><u>Easy steps to recover deleted messages from Infinix Smart 8</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-a-quick-and-responsive-keyboard-experience/"><u>Effortless Fixes for a Quick and Responsive Keyboard Experience</u></a></li>
<li><a href="https://tech-hub.techidaily.com/evaluating-ai-in-the-art-of-mixed-drinks/"><u>Evaluating AI in the Art of Mixed Drinks</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209887897-getting-the-function-fn-buttons-back-on-your-dell-device-lets-resolve-that-today/"><u>Getting the Function (Fn) Buttons Back on Your Dell Device? Let's Resolve That Today!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-oppo-find-x7-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 Oppo Find X7 Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://article-tips.techidaily.com/in-2024-on-the-move-high-performance-free-online-tempo-tracking-tools/"><u>In 2024, On-the-Move High-Performance, Free Online Tempo Tracking Tools</u></a></li>
<li><a href="https://some-tips.techidaily.com/navigating-tomorrow-cosmic-as-your-gateway-to-the-next-gen-linux-experience/"><u>Navigating Tomorrow: COSMIC as Your Gateway to the Next-Gen Linux Experience</u></a></li>
<li><a href="https://techtrends.techidaily.com/onepluss-next-evolution-a-sneak-peek-into-price-range-estimated-release-date-and-feature-set-for-upcoming-device/"><u>OnePlus's Next Evolution: A Sneak Peek Into Price Range, Estimated Release Date & Feature Set for Upcoming Device</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209518388-pubg-structures-failing-to-load-heres-the-fix/"><u>PUBG Structures Failing to Load? Here's the Fix!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722958559035-step-by-step-fix-guide-for-hps-beats-sound-card-drivers-on-windows-1087-now-solved/"><u>Step by Step Fix Guide for HP's Beats Sound Card Drivers on Windows 10/8/7 - Now Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-destiny-twos-server-accessibility-trouble/"><u>Troubleshooting and Solving Destiny ˈTwo's Server Accessibility Trouble</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-svchostexe-reducing-cpu-load-on-your-windows-11-pc-guide/"><u>Troubleshooting Svchost.exe: Reducing CPU Load on Your Windows 11 PC [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-erratic-wireless-mouse-problem-in-windows-11-and-10-a-comprehensive-guide/"><u>Troubleshooting Your Erratic Wireless Mouse Problem in Windows 11 and 10: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-volume-control-not-working-solved/"><u>Windows 11 Volume Control Not Working [SOLVED]</u></a></li>
<li><a href="https://some-guidance.techidaily.com/1724313544300-abbyy/"><u>グローバルスケールでのABBYYによるデジタル・トランスフォーメーション調査研究</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1444782">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1444782.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1444782">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1444782.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1444782%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1444782/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

