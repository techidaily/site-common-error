---
title: "Fix Guide: Overcome 'Windows 11 Installer Error Code 80240020'"
date: 2024-08-27T13:40:02.534Z
updated: 2024-08-28T13:40:02.534Z
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
<li><a href="https://common-error.techidaily.com/1723209408483-solved-laptop-battery-not-charging-quickly-and-easily/"><u>[SOLVED] | Laptop Battery Not Charging | Quickly & Easily</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-2024-approved-identify-10-shadowy-instagram-story-observers/"><u>[Updated] 2024 Approved  Identify 10 Shadowy Instagram Story Observers</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-winning-9-gif-recorder-apps-master-your-animated-archive/"><u>[Updated] 2024 Approved  Winning 9 GIF Recorder Apps  Master Your Animated Archive</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-revolutionizing-reach-the-next-wave-of-fb-ad-techniques-2024/"><u>[Updated] Revolutionizing Reach  The Next Wave of FB Ad Techniques, 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-crafting-engaging-unboxings-to-skyrocket-like-counts/"><u>2024 Approved  Crafting Engaging Unboxings to Skyrocket Like Counts</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-the-ultimate-collection-best-zero-price-photo-editing-software/"><u>2024 Approved  The Ultimate Collection  Best Zero-Price Photo Editing Software</u></a></li>
<li><a href="https://common-error.techidaily.com/banish-pdf-printing-issues-quick-and-effective-remedies-await-you/"><u>Banish PDF Printing Issues: Quick and Effective Remedies Await You</u></a></li>
<li><a href="https://win-blog.techidaily.com/batman-arkham-knight-crashes-fast-track-repair-guide-for-game-malfunctions/"><u>Batman Arkham Knight Crashes - Fast Track Repair Guide for Game Malfunctions</u></a></li>
<li><a href="https://common-error.techidaily.com/dell-laptop-keyboard-malfunction-heres-how-you-can-fix-it-quickly/"><u>Dell Laptop Keyboard Malfunction? Here's How You Can Fix It Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/disregarded-sd-card-dont-despair-solutions-await/"><u>Disregarded SD Card, Don't Despair! Solutions Await</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206686906-easily-restore-charging-on-your-laptop-solutions-at-hand/"><u>Easily Restore Charging on Your Laptop - Solutions at Hand!</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/easy-guide-to-using-your-phone-as-an-alternative-camera/"><u>Easy Guide to Using Your Phone as an Alternative Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-crc-cyclic-redundancy-check-problems-in-your-data/"><u>Effective Remedies for CRC (Cyclic Redundancy Check) Problems in Your Data</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-overcome-and-fix-code-28-device-manager-issues-on-your-pc/"><u>Effective Techniques to Overcome and Fix Code 28 Device Manager Issues on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-the-hurdle-of-error-0x800f0831-quickly-with-built-in-windows-update-features/"><u>Eliminate the Hurdle of 'Error 0X800F0831' Quickly with Built-In Windows Update Features</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unresponsive-number-keys-on-your-keyboard/"><u>Fixing Unresponsive Number Keys on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206482260-geforce-experience-setup-glitch-solved-retrieve-your-custom-configurations-now/"><u>GeForce Experience Setup Glitch Solved - Retrieve Your Custom Configurations Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-the-recently-resolved-database-glitch-in-windows-10-updates/"><u>How to Address the Recently Resolved Database Glitch in Windows 10 Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-key-not-working/"><u>How to Fix @ Key Not Working</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-intercept-text-messages-on-samsung-galaxy-s23plus-drfone-by-drfone-virtual-android/"><u>How to Intercept Text Messages on Samsung Galaxy S23+ | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-android/"><u>How to Screen Mirroring Xiaomi Redmi Note 13 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-12-mini-to-ipad-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 12 mini to iPad? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-the-quest-for-content-videos-in-social-media-network/"><u>In 2024, The Quest for Content  Videos in Social Media Network</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-unlock-oppo-reno-10-pro-5g-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Oppo Reno 10 Pro 5G Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://common-error.techidaily.com/minecraft-opengl-problem-solving-a-comprehensive-fix-it-manual/"><u>Minecraft OpenGL Problem Solving: A Comprehensive Fix-It Manual</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-unlocking-audio-fidelity-top-advice-for-playing-m4a-on-android-devices/"><u>New Unlocking Audio Fidelity Top Advice for Playing M4A on Android Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-latency-effective-ways-to-eliminate-lag-in-your-windows-10-keyboard/"><u>Overcome Latency: Effective Ways to Eliminate Lag in Your Windows 10 Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-slow-booting-in-windows-7-users/"><u>Quick Fixes for Slow Booting in Windows 7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-desktop-mouse-stops-working/"><u>Quick Fixes for When Your Desktop Mouse Stops Working</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-extended-semaphore-error-timeout-limit-exceeded-issue-error-code-0x80070079/"><u>Resolved: Extended Semaphore Error - Timeout Limit Exceeded Issue (Error Code 0X80070079)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-the-windows-update-error-code-0x802n4002e/"><u>Resolved: Fixing the Windows Update Error Code 0X802n4002E</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206650968-sd-invisible-no-more-find-the-answer-here/"><u>SD Invisible No More, Find the Answer Here</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207936743-solution-found-compatibility-issues-with-display-input-timing-fixed/"><u>Solution Found: Compatibility Issues with Display Input Timing Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-to-pubg-structures-failure-now-fixed/"><u>Solution to PUBG Structures Failure - Now Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-resolving-the-win32-app-crash-code-0x00000005/"><u>Step-by-Step Guide: Resolving the Win32 App Crash - Code 0X00000005</u></a></li>
<li><a href="https://common-error.techidaily.com/success-story-restoring-communication-with-a-non-responsive-dhcp-server/"><u>Success Story: Restoring Communication With a Non-Responsive DHCP Server</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fixes-for-kodis-glitches-say-goodbye-to-playback-issues/"><u>The Ultimate Fixes for Kodi's Glitches: Say Goodbye to Playback Issues!</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/top-10-fingerprint-lock-apps-to-lock-your-oppo-a56s-5g-phone-by-drfone-android/"><u>Top 10 Fingerprint Lock Apps to Lock Your Oppo A56s 5G Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-high-wudfhostexe-process-load-in-windows-10-systems/"><u>Troubleshooting High WUDFHost.exe Process Load in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-fixing-logon-issues-with-user-profile-services/"><u>Troubleshooting Steps for Fixing Logon Issues with User Profile Services</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-successful-steps-to-get-internet-explorer-up-and-running-again/"><u>Troubleshooting: Successful Steps to Get Internet Explorer Up and Running Again</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-boosting-game-performance-in-windows-11/"><u>Ultimate Guide to Boosting Game Performance in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-correcting-entry-point-misses-in-microsoft-windows/"><u>Understanding and Correcting Entry Point Misses in Microsoft Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-common-dll-errors-fix-and-prevention-tips/"><u>Winning Against Windows Common Dll Errors: Fix and Prevention Tips</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->