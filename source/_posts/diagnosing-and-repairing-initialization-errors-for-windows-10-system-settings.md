---
title: Diagnosing and Repairing Initialization Errors for Windows 10 System Settings
date: 2024-09-04T20:22:02.626Z
updated: 2024-09-05T20:22:02.626Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Repairing Initialization Errors for Windows 10 System Settings
excerpt: This Article Describes Diagnosing and Repairing Initialization Errors for Windows 10 System Settings
thumbnail: https://thmb.techidaily.com/8581bfa31a5d038a1f8f5ee676586f0437981f1b9f6527b07717a27989fe2446.jpg
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
<li><a href="https://youtube-lab.techidaily.com/n-2024-instantly-boost-youtube-performance-master-render-and-upload/"><u>[New] In 2024, Instantly Boost YouTube Performance - Master Render and Upload</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-ultimate-5-social-media-films-for-2024/"><u>[New] Ultimate 5 Social Media Films for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-from-gym-goer-to-broadcayer-set-up-a-sports-vlog-on-macos-for-2024/"><u>[Updated] From Gym Goer to Broadcayer  Set Up a Sports Vlog on macOS for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-to-amend-blurry-mobile-streaming-on-social-platforms/"><u>[Updated] How to Amend Blurry Mobile Streaming on Social Platforms</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-the-ultimate-tutorial-for-turning-twitter-videos-into-gifs/"><u>[Updated] In 2024, The Ultimate Tutorial for Turning Twitter Videos Into GIFs</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-examining-realities-intertwined-what-is-mixed-reality/"><u>2024 Approved  Examining Realities Intertwined  What Is Mixed Reality?</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-secrets-of-facebook-cover-vids-for-aspiring-social-media-stars/"><u>2024 Approved  Secrets of Facebook Cover Vids for Aspiring Social Media Stars</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-the-solved-camera-hurdle-detailed-fixes-for-error-code-0xa00f4292-on-your-pc/"><u>Bypass the [Solved] Camera Hurdle: Detailed Fixes for Error Code 0Xa00f4292 on Your PC</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/catch-or-beat-sleeping-snorlax-on-pokemon-go-for-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>Catch or Beat Sleeping Snorlax on Pokemon Go For Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-repair-steps-solving-the-failed-user-profile-logon-issue/"><u>Complete Repair Steps: Solving the Failed User Profile Logon Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-cure-google-chromes-persistent-black-display-problem/"><u>Comprehensive Solutions to Cure Google Chrome's Persistent Black Display Problem</u></a></li>
<li><a href="https://windows11.techidaily.com/enhancing-power-feedback-setting-up-fully-charged-notifications-in-win11/"><u>Enhancing Power Feedback: Setting Up Fully Charged Notifications in Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-windows-1011-night-light-feature-wont-start/"><u>Fixing the Issue: Windows 10/11 Night Light Feature Won't Start</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-device-driver-power-failures-a-comprehensive-walkthrough/"><u>Fixing Windows Device Driver Power Failures - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://tech-hub.techidaily.com/from-mundane-to-magical-weaving-wonders-with-chatgpt/"><u>From Mundane to Magical: Weaving Wonders with ChatGPT</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-diagnosing-and-repairing-problematic-video-card-drivers-that-cause-minecraft-crashes-in-windows-environments/"><u>Guide to Diagnosing and Repairing Problematic Video Card Drivers that Cause Minecraft Crashes in Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-and-detect-bluetooth-devices-on-windows-10-easily/"><u>How to Enable and Detect Bluetooth Devices on Windows 10 Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-lenovo-mouse-pad-when-it-stops-working-on-any-windows-platform/"><u>How to Fix Your Lenovo Mouse Pad when It Stops Working on Any Windows Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-fix-a-laptop-trackpad-that-wont-work-anymore/"><u>How To Restore Functionality: Fix A Laptop Trackpad That Won't Work Anymore</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-essential-techniques-in-creating-youtube-thumbnails-that-stand-out/"><u>In 2024, Essential Techniques in Creating YouTube Thumbnails That Stand Out</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-tecno-camon-20-premier-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/lenovo-webcam-driver-update-guide-for-optimal-performance-on-windows-7-computers/"><u>Lenovo Webcam Driver Update Guide for Optimal Performance on Windows 7 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210527473-master-the-art-of-a-smooth-csgo-experience-no-more-abrupt-game-shutdowns/"><u>Master the Art of a Smooth CSGO Experience: No More Abrupt Game Shutdowns!</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-streaming-made-better-no-more-pauses-or-lag-fix-your-device-today/"><u>Netflix Streaming Made Better: No More Pauses or Lag – Fix Your Device Today!</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-constant-errors-in-microsoft-outlook-a-comprehensive-guide/"><u>Overcoming Constant Errors in Microsoft Outlook: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/power-overload-solution-for-interface-gateway/"><u>Power Overload Solution for Interface Gateway</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-file-explorer-freezing-issue-on-windows-10-a-complete-guide/"><u>Resolve File Explorer Freezing Issue on Windows 10: A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-steps-to-overcome-preparing-to-install-windows-issue/"><u>Resolved: Steps to Overcome 'Preparing to Install Windows' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-non-working-usb-slots-in-dell-computers-expert-advice/"><u>Resolving Issues with Non-Working USB Slots in Dell Computers - Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-the-power-of-the-start-menu-repairing-windows-key-glitches-in-windows-11/"><u>Restoring the Power of the Start Menu: Repairing Windows Key Glitches in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-the-dilemma-killing-livekernelevent-error-144/"><u>Solve the Dilemma: Killing 'LiveKernelEvent Error #144'</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-troubleshooting-and-repairing-stuck-file-explorer-on-windows-10/"><u>Solved! Troubleshooting and Repairing Stuck File Explorer on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-lenovo-mouse-pad-issues-on-windows-10-8-and-7-a-complete-fix-guide/"><u>Solving Lenovo Mouse Pad Issues on Windows 10, 8 & 7: A Complete Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-ce-34878-0-hacking-glitch-on-your-sony-ps4-console-complete-walkthrough/"><u>Solving the CE-34878-0 Hacking Glitch on Your Sony PS4 Console - Complete Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-steam-disk-readwrite-errors-with-these-easy-tips/"><u>Troubleshoot Steam Disk Read/Write Errors with These Easy Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-wrap-error-fixing-windows-resource-protection-failed-issues/"><u>Troubleshooting WRAP Error: Fixing 'Windows Resource Protection Failed' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-update-service-wont-start-follow-these-solutions-to-fix-the-problem-instantly/"><u>Windows Update Service Won't Start? Follow These Solutions to Fix the Problem Instantly</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->