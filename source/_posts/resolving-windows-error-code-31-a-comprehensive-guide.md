---
title: "Resolving Windows Error Code 31: A Comprehensive Guide"
date: 2024-10-21T17:29:31.907Z
updated: 2024-10-24T20:09:44.724Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows Error Code 31: A Comprehensive Guide"
excerpt: "This Article Describes Resolving Windows Error Code 31: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/6095600b720da220ffffead1a4fc142237909794e0b00b8441f133e8ae3bdb81.jpg
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
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-interplatform-video-uploading-twitter-and-tumblr-synced/"><u>[Updated] In 2024, Interplatform Video Uploading Twitter & Tumblr Synced</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-navigating-iphones-voice-memos-with-precision-for-2024/"><u>[Updated] Navigating iPhone's Voice Memos with Precision for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/digital-artistry-in-depth-on-ps-distortion-techniques/"><u>Digital Artistry In-Depth on PS Distortion Techniques</u></a></li>
<li><a href="https://buynow-info.techidaily.com/dive-into-excitement-discover-the-10-best-gaming-options-when-youre-feeling-bored/"><u>Dive Into Excitement: Discover the 10 Best Gaming Options When You're Feeling Bored</u></a></li>
<li><a href="https://network-issues.techidaily.com/easy-to-remember-guide-straighten-monitors-quickly/"><u>Easy-to-Remember Guide: Straighten Monitors Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-on-rejuvenating-your-keyboard-settings-with-a-full-reboot/"><u>Expert Tips on Rejuvenating Your Keyboard Settings with a Full Reboot</u></a></li>
<li><a href="https://extra-hints.techidaily.com/film-timeframe-determining-gb-storage-requirement/"><u>Film Timeframe Determining GB Storage Requirement</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-methods-to-mirror-vivo-y100-to-roku-drfone-by-drfone-android/"><u>In 2024, 3 Methods to Mirror Vivo Y100 to Roku | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-honor-90-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Honor 90 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-honor-x50-gt-device-by-drfone-android/"><u>In 2024, What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Honor X50 GT Device</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-keypad-not-working-in-windows-1087-solved/"><u>Laptop Keypad Not Working in Windows 10/8/7 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210515115-lenovo-fingerprint-recognition-problems-heres-how-you-can-repair-it-easily/"><u>Lenovo Fingerprint Recognition Problems? Here's How You Can Repair It Easily</u></a></li>
<li><a href="https://win-fantastic.techidaily.com/overcome-windows-7-backup-stalling-at-9757-with-these-6-strategies-plus-a-crucial-insiders-secret/"><u>Overcome Windows 7 Backup Stalling at 97%/57% with These 6 Strategies + A Crucial Insider's Secret!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-overcoming-error-0x8024c01c-during-windows-system-updates/"><u>Step-by-Step Solution for Overcoming Error 0X802^4C01C During Windows System Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-tips-for-common-oculus-tech-issues/"><u>Step-by-Step Troubleshooting Tips for Common Oculus Tech Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-non-registered-classes-in-windows-10-systems/"><u>Troubleshooting and Solving Non-Registered Classes in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-audio-issues-resolving-crackling-sound-on-pcs-with-windows-11-or-7/"><u>Troubleshooting Audio Issues: Resolving Crackling Sound on PCs with Windows 11 or 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-lenovo-mouse-pad-solutions-for-windows-10-8-and-7/"><u>Troubleshooting Your Lenovo Mouse Pad: Solutions for Windows 10, 8, and 7</u></a></li>
<li><a href="https://common-error.techidaily.com/unstuck-your-windows-update-overcoming-the-stubborn-100-issue-resolved/"><u>Unstuck Your Windows Update! Overcoming the Stubborn 100% Issue (Resolved)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/798165/11305" target="_top" id="798165">
  <img src="//a.impactradius-go.com/display-ad/11305-798165" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i110150.net/i/5597632/798165/11305" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

