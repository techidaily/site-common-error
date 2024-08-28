---
title: Troubleshooting Tips for Fixing Windows 11 Installation Error 80240020 [Solved]
date: 2024-08-27T13:51:56.075Z
updated: 2024-08-28T13:51:56.075Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Tips for Fixing Windows 11 Installation Error 80240020 [Solved]
excerpt: This Article Describes Troubleshooting Tips for Fixing Windows 11 Installation Error 80240020 [Solved]
thumbnail: https://thmb.techidaily.com/99e083d06891d6b9709e3f748eff8a9d6ada1ef3054d20b60fdb2ab68b2e719b.png
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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-clearing-your-name-after-a-youtube-copyright-strike-notice/"><u>[New] 2024 Approved  Clearing Your Name After a YouTube Copyright Strike Notice</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-outstanding-storytelling-on-screen/"><u>[New] Outstanding Storytelling on Screen</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-streamlining-video-communication-in-laptop-using-whatsapp-desktop/"><u>[Updated] 2024 Approved  Streamlining Video Communication in Laptop Using WhatsApp Desktop</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-quick-subscribe-does-it-really-amplify-watch-time/"><u>[Updated] In 2024, Quick-Subscribe  Does It Really Amplify Watch Time?</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-navigating-youtubes-photo-publishing/"><u>[Updated] Navigating YouTube's Photo Publishing</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-unpacking-sharex-evaluation-and-replacements-for-2024/"><u>[Updated] Unpacking ShareX  Evaluation & Replacements for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-the-character-visualization-tool/"><u>Accessing the Character Visualization Tool</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehve-steps-to-revive-your-acers-audio-no-more-quiet-computers/"><u>Comprehve Steps to Revive Your Acer's Audio – No More Quiet Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-initialization-fixes-unstuck-from-the-boot-sequence-hurdle/"><u>Destiny 2 Initialization Fixes: Unstuck From the Boot Sequence Hurdle</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-the-windows-camera-error-code-0xa00f4292/"><u>Diagnosing and Repairing the Windows Camera Error Code 0xA00F4292</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-repairing-google-chromes-unwanted-black-display-problem/"><u>Expert Advice on Repairing Google Chrome's Unwanted Black Display Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-prevent-your-usb-from-keep-dropping-out/"><u>Expert Advice: Prevent Your USB From Keep Dropping Out</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-10s-troubling-0x80072efd-error-step-by-step-solutions/"><u>Fixing Windows 10'S Troubling '0X80072EFD' Error: Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-laptops-trackpad-issues-on-windows-11-8-and-7-a-comprehensive-guide/"><u>Fixing Your Laptop's Trackpad Issues on Windows 11, 8 & 7: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-failed-windows-update-issues-effectively/"><u>How to Fix Failed Windows Update Issues Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-steelseries-arctis-5-microphone-issue-a-comprehensive-guide/"><u>How to Fix the SteelSeries Arctis 5 Microphone Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-p40plus-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Itel P40+ Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://common-error.techidaily.com/improved-safety-configuration-activate-secure-file-transfer-with-newly-configured-restrictions/"><u>Improved Safety Configuration: Activate Secure File Transfer with Newly Configured Restrictions</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-excellent-typography-trick-sets/"><u>In 2024, Excellent Typography Trick Sets</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/masterful-mp4-transformation-tools-facebook-edition/"><u>Masterful MP4 Transformation Tools (Facebook Edition)</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-installation-obstacles-with-precision/"><u>Overcoming Installation Obstacles with Precision</u></a></li>
<li><a href="https://common-error.techidaily.com/pubg-troubleshooting-tips-overcoming-in-game-building-loading-problems/"><u>PUBG Troubleshooting Tips - Overcoming In-Game Building Loading Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-windows-7-failing-to-recognize-second-display-issue/"><u>Resolved: Windows 7 Failing to Recognize Second Display Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-steps-to-resolve-your-nonfunctional-wi-fi-connection/"><u>Simple Steps to Resolve Your Nonfunctional Wi-Fi Connection</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-fix-steps-when-bluetooth-misses-display-on-device-manager/"><u>Solved: Fix Steps When Bluetooth Misses Display on Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-resolve-windows-10-hosted-network-connection-issues/"><u>Solved: How to Resolve Windows 10 Hosted Network Connection Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-correcting-the-windows-update-failed-with-code-0x8024200d-issue/"><u>Step-by-Step Solution for Correcting the 'Windows Update Failed with Code 0X8024200D' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-frozen-tailored-settings-on-accounts/"><u>Troubleshooting Frozen Tailored Settings on Accounts</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-outlook-cannot-reach-microsoft-exchange-server-errors/"><u>Troubleshooting Steps for 'Outlook Cannot Reach Microsoft Exchange Server' Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-overcoming-windows-11-black-screen-challenges-effortlessly/"><u>Troubleshooting Tips: Overcoming Windows 11 Black Screen Challenges Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-wifi-disconnects-on-windows-710-fixing-ethernet-issues-step-by-step/"><u>Troubleshooting WiFi Disconnects on Windows 7/10: Fixing Ethernet Issues Step-by-Step</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-high-performance-gaming-in-windows-11-strategies-for-gamers/"><u>Unlocking High-Performance Gaming in Windows 11: Strategies for Gamers</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-discover-the-top-10-android-video-editing-apps-free-and-paid-for-2024/"><u>Updated Discover the Top 10 Android Video Editing Apps Free and Paid for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->