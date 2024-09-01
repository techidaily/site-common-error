---
title: Resolving the 'Windows Installer Service Unavailable' Error - A Comprehensive Guide
date: 2024-08-31T17:42:38.793Z
updated: 2024-09-01T17:42:38.793Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving the 'Windows Installer Service Unavailable' Error - A Comprehensive Guide
excerpt: This Article Describes Resolving the 'Windows Installer Service Unavailable' Error - A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/21333b0674dae8e987dce32ef856602446e7d37aac1b972fab53c865a8b5f643.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4940317&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/333ac5d90817d69113471fbb6e531bee/sps-partnership-728x90eng.png" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://common-error.techidaily.com/1723210733201-issue-resolved-how-to-overcome-windows-camera-error-code-0xa0-groovyf4292-and-get-back-to-snapshots/"><u>[Issue Resolved]: How to Overcome Windows Camera Error Code 0xA0 Groovyf4292 and Get Back to Snapshots!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-2024-approved-webcam-mastery-unique-ideas-explored/"><u>[New] 2024 Approved  Webcam Mastery  Unique Ideas Explored</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-frametaker-high-quality-edition/"><u>[New] In 2024, FrameTaker High-Quality Edition</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-the-essentials-of-sims-4-gameplay-recording/"><u>[New] In 2024, The Essentials of Sims 4 Gameplay Recording</u></a></li>
<li><a href="https://youtube-web.techidaily.com/anipulate-sound-rate-in-youtube-playback-for-2024/"><u>[New] Manipulate Sound Rate in YouTube Playback for 2024</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-2024-approved-ultimate-guide-to-7-top-mac-vids/"><u>[Updated] 2024 Approved  Ultimate Guide to 7 Top Mac Vids</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-prime-selection-instagrams-top-8-ae-designs/"><u>[Updated] In 2024, Prime Selection  Instagram's Top 8 AE Designs</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-mastering-selfies-on-instagram-a-guide/"><u>[Updated] Mastering Selfies on Instagram  A Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-windows-8-moviemaker-step-by-step-guide/"><u>[Updated] Mastering Windows 8 Moviemaker  Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-inspirational-themes-for-regular-vlogs/"><u>2024 Approved  Inspirational Themes for Regular Vlogs</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-inadequate-system-power-to-fulfill-task-requests/"><u>Addressing Inadequate System Power to Fulfill Task Requests</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/androids-ultimate-sky-archive-sentries-2-written-by-a-user-not-an-ai-model-for-2024/"><u>Android's Ultimate Sky Archive Sentries (2 Written by a User, Not an AI Model for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-service-initialization-now-successful-resolved-generic-error-issues/"><u>BattlEye Service Initialization Now Successful - Resolved Generic Error Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-error-code-80240020-a-troubleshooters-guide-to-successfully-installing-windows-10/"><u>Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-restoring-corrupted-data-on-your-windows-11-pc/"><u>Comprehensive Solutions for Restoring Corrupted Data on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/cracking-down-on-distorted-sounds-fix-your-windows-107-speaker-problems/"><u>Cracking Down on Distorted Sounds: Fix Your Windows 10/7 Speaker Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-security-measures-activated-for-local-systems/"><u>Enhanced Security Measures Activated for Local Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/eternal-rest-for-my-system-wake-fail/"><u>Eternal Rest for My System: Wake Fail</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-prevent-and-solve-oddworld-soulstorm-freezing-on-desktop-pc/"><u>Expert Tips to Prevent and Solve Oddworld: Soulstorm Freezing on Desktop PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-overcome-windows-11-installer-error-code-80240020/"><u>Fix Guide: Overcome 'Windows 11 Installer Error Code 80240020'</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-cyclic-redundancy-check-errors-in-your-files/"><u>How To Resolve Cyclic Redundancy Check Errors in Your Files</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-unexpected-shutdowns-with-error-code-167-in-windows-systems/"><u>How to Resolve Unexpected Shutdowns with Error Code 1#67 in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206141954-how-to-restore-sounds-in-forza-horizon-4-after-a-silent-ride-solutions-unveiled/"><u>How to Restore Sounds in Forza Horizon 4 After a Silent Ride – Solutions Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-tackle-dota-2s-modify-graphics-api-error-message-2024-in-minutes/"><u>How to Tackle Dota 2'S 'Modify Graphics API' Error Message 2024 in Minutes!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208231568-hp-laptop-usb-dysfunction-heres-how-to-restore-its-functionality/"><u>HP Laptop USB Dysfunction? Here’s How to Restore Its Functionality!</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-perfecting-the-art-of-photo-mosaic-creation/"><u>In 2024, Perfecting the Art of Photo Mosaic Creation</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-mouse-pad-not-working-in-windows-1087-fixed/"><u>Lenovo Mouse Pad Not Working in Windows 10/8/7 [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-dll-error-for-opencl-applications/"><u>Overcoming DLL Error for OpenCL Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-problems-with-windows-11-1607-feature-set-installation-errors/"><u>Overcoming Problems with Windows 11 1607 Feature Set Installation Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolving-skype-video-issues-on-windows-11/"><u>Quick Solutions: Resolving Skype Video Issues on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-guide-to-fast-league-of-legends-downloading-say-goodbye-to-delays/"><u>Quick-Fix Guide to Fast League of Legends Downloading: Say Goodbye to Delays!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-failed-to-initialize-unity-graphics-bug-quickly/"><u>Resolve 'Failed To Initialize' Unity Graphics Bug Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-the-bluetooth-not-detected-on-windows-11-fast-fix-guide/"><u>Resolve the Bluetooth Not Detected on Windows 11 - Fast Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-10-bluetooth-connectivity-issues-instantly-step-by-step-guide/"><u>Resolve Your Windows 10 Bluetooth Connectivity Issues Instantly - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-sign-in-issues-fixing-user-profile-service-failures/"><u>Resolve Your Windows Sign-In Issues: Fixing User Profile Service Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/sd-invisible-no-more-find-the-answer-here/"><u>SD Invisible No More, Find the Answer Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-internal-webcam-woes-with-these-simple-fixes-for-windows-users/"><u>Solve Your Internal Webcam Woes with These Simple Fixes for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-sound-issues-eliminating-crackling-from-speakers-in-windows-117/"><u>Solving Your Sound Issues: Eliminating Crackling From Speakers in Windows 11/7</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-for-troubleshooting-error-0x8024401c-during-windows-updates-on-versions-1011/"><u>Step-by-Step Guide for Troubleshooting Error 0X8024401C During Windows Updates on Versions 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-showing-your-hidden-windows-1amoader-bar-again/"><u>Step-by-Step Solution: Showing Your Hidden Windows 1Amoader Bar Again</u></a></li>
<li><a href="https://common-error.techidaily.com/top-tips-for-fixing-windows-11-stalling-issues/"><u>Top Tips for Fixing Windows 11 Stalling Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-csgo-issues-fast-fixes-for-no-more-game-crashes/"><u>Troubleshoot CSGO Issues - Fast Fixes for No More Game Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-when-file-explorer-wont-respond-in-windows-10/"><u>Troubleshooting Guide: When File Explorer Won't Respond in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-solving-windows-10-freezing-issues/"><u>Troubleshooting Tips: Solving Windows 10 Freezing Issues</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-incorporate-melodies-into-gif-file-on-pc/"><u>Updated Incorporate Melodies Into GIF File on PC</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/visualsnitch-capture-and-save-tweets-images-and-videos/"><u>VisualSnitch  Capture and Save Tweets' Images & Videos</u></a></li>
</ul></div>
