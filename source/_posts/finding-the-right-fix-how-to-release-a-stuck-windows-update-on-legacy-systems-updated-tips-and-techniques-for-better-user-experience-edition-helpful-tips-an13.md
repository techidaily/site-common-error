---
title: "Finding The Right Fix: How to Release A Stuck Windows Update on Legacy Systems - Updated Tips & Techniques For Better User Experience Edition! (Helpful Tips and Guides.)"
date: 2024-08-22T19:23:18.694Z
updated: 2024-08-23T19:23:18.694Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Finding The Right Fix: How to Release A Stuck Windows Update on Legacy Systems - Updated Tips & Techniques For Better User Experience Edition! (Helpful Tips and Guides.)"
excerpt: "This Article Describes Finding The Right Fix: How to Release A Stuck Windows Update on Legacy Systems - Updated Tips & Techniques For Better User Experience Edition! (Helpful Tips and Guides.)"
thumbnail: https://thmb.techidaily.com/ade52c66f0e56fc9f46bf8a90a52f0a6d57269829cd3f5e819633e97b2be938d.jpg
---

## Professional Maintenance: Regularly Scheduled Maintenance, as Recommended by the Car Manufacturer, Can Help Identify and Address Any Potential Issues with the Suspension Before They Become Serious Problems

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
<li><a href="https://facebook-video-share.techidaily.com/new-2024-approved-enhancing-youtube-viewing-experience-with-right-video-formats/"><u>[New] 2024 Approved  Enhancing YouTube Viewing Experience with Right Video Formats</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-exclusive-selection-of-elite-race-games/"><u>[New] 2024 Approved  Exclusive Selection of Elite Race Games</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-guidelines-for-compelling-visual-fb-marketing-for-2024/"><u>[New] Guidelines for Compelling Visual FB Marketing for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-7-best-free-online-youtube-tag-extractors/"><u>[New] In 2024, 7 Best Free Online YouTube Tag Extractors</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-in-2024-elevating-your-tiktok-pics-with-simple-edits/"><u>[New] In 2024, Elevating Your TikTok Pics with Simple Edits</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-deletion-methods-for-youtubes-backlogged-video-collection/"><u>[Updated] 2024 Approved  Deletion Methods for YouTube's Backlogged Video Collection</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-clandestine-snapsnapper-concealed-techniques-for-image-capturing/"><u>[Updated] Clandestine SnapSnapper  Concealed Techniques for Image Capturing</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-crafting-a-seamless-cross-share-experience-with-fb-and-igtv-for-2024/"><u>[Updated] Crafting a Seamless Cross-Share Experience with FB & IGTV for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-from-static-to-dynamic-a-comprehensive-look-at-the-new-polaroid-xs-100i-action-camera/"><u>[Updated] From Static to Dynamic  A Comprehensive Look at the New Polaroid XS 100I Action Camera</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-quintessential-ios-emulators-for-playstation-2-for-2024/"><u>[Updated] Quintessential iOS Emulators for PlayStation 2 for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-enhance-vr-experience-advanced-gopro-4k-editing/"><u>2024 Approved  Enhance VR Experience  Advanced GoPro 4K Editing</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-key-concepts-in-image-manipulation/"><u>2024 Approved  Key Concepts in Image Manipulation</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/activating-disabled-freesync-on-amd-gpus/"><u>Activating Disabled FreeSync on AMD GPUs</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-lag-expert-ways-to-fix-high-ping-in-counter-strike-global-offensive/"><u>Beat the Lag - Expert Ways to Fix High Ping in Counter-Strike Global Offensive</u></a></li>
<li><a href="https://fox-info.techidaily.com/chuckle-craft-ranking-the-top-10-memes-by-wow-factor-for-2024/"><u>Chuckle Craft  Ranking the Top 10 Memes by Wow Factor for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehvew-of-fixes-to-bring-back-sound-on-your-ps4s-chat-microphone/"><u>Comprehvew of Fixes to Bring Back Sound on Your PS4's Chat Microphone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discover-bargains-with-oodles-gratis-community-ads/"><u>Discover Bargains with Oodle's Gratis Community Ads</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-fix-the-windows-update-failed-with-code-0x8024002e/"><u>Effective Solutions to Fix the 'Windows Update Failed with Code 0X8024002E'</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-the-new-world-launch-wont-start-anti-cheat-problem/"><u>Effective Solutions to the 'New World Launch Won't Start: Anti-Cheat Problem'</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1603-deciphered-a-step-by-step-guide-to-solving-fatal-setup-issues/"><u>Error 1603 Deciphered: A Step-by-Step Guide to Solving Fatal Setup Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-31-on-your-pc-heres-how-you-can-solve-it/"><u>Error Code 31 on Your PC? Here's How You Can Solve It!</u></a></li>
<li><a href="https://common-error.techidaily.com/from-broken-to-secure-fixing-problematic-windows-update-processes/"><u>From Broken to Secure: Fixing Problematic Windows Update Processes</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-lenovo-mouse-pad-working-again-on-any-version-of-windows-comprehensive-fixes/"><u>Get Your Lenovo Mouse Pad Working Again on Any Version of Windows - Comprehensive Fixes!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210142536-hdmi-through-usb-failure-heres-how-you-can-resolve-it/"><u>HDMI Through USB Failure? Here’s How You Can Resolve It!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-invalid-directory-name-mistake-quickly/"><u>How to Fix 'Invalid Directory Name' Mistake Quickly!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-responsive-mousepad-on-your-laptop-running-windows-10-8-or-e7/"><u>How to Fix a Non-Responsive Mousepad on Your Laptop Running Windows (10, 8 or E7)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-bluetooth-devices-showing-as-connected-but-inaccessible-in-windows-10/"><u>How to Fix Bluetooth Devices Showing as Connected but Inaccessible in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-optimize-your-system-resolving-high-graphics-usage-by-desktop-window-manager-in-windows/"><u>How to Optimize Your System: Resolving High Graphics Usage by Desktop Window Manager in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-disk-check-stuck-situations-in-your-windows-10-device-effortlessly/"><u>How to Overcome Disk Check Stuck Situations in Your Windows 10 Device Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-undetected-bluetooth-gadgets-in-windows-10/"><u>How to Resolve Undetected Bluetooth Gadgets in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-and-repair-audio-playback-errors-on-youtube-for-windows-11-users/"><u>How to Troubleshoot and Repair Audio Playback Errors on YouTube for Windows 11 Users</u></a></li>
<li><a href="https://review-topics.techidaily.com/identify-missing-hardware-drivers-with-windows-device-manager-in-windows-10-by-drivereasy-guide/"><u>Identify missing hardware drivers with Windows Device Manager in Windows 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/ps5xbox-series-x-top-gaming-tvs-unveiled/"><u>PS5/Xbox Series X  Top Gaming TVs Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/quickly-restore-charging-functionality-to-your-laptop-expert-tips-inside/"><u>Quickly Restore Charging Functionality to Your Laptop: Expert Tips Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-windows-could-not-install-in-minutes-with-these-tips/"><u>Resolve 'Windows Could Not Install' In Minutes with These Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/secure-guide-acquiring-permissions-from-trustedinstaller-for-file-modification-tasks/"><u>Secure Guide: Acquiring Permissions From TrustedInstaller for File Modification Tasks</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-overcoming-insufficient-system-resources-issue/"><u>Solution Steps for Overcoming 'Insufficient System Resources' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-of-inaccessible-windows-security-feature-smartscreen-troubleshoot-tips/"><u>Solving the Issue of Inaccessible Windows Security Feature – SmartScreen Troubleshoot Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-windows-entry-point-missing-error-fix/"><u>Step-by-Step Solution for Windows 'Entry Point Missing' Error Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-lenovo-mouse-pad-in-windows-operating-systems/"><u>Troubleshooting Non-Responsive Lenovo Mouse Pad in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-success-quick-solution-for-error-1053-when-service-fails-to-react-timely/"><u>Troubleshooting Success: Quick Solution for Error 1053 When Service Fails to React Timely</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-for-valorant-how-to-stop-screen-tearing-once-and-for-all/"><u>Ultimate Troubleshooting for Valorant: How To Stop Screen Tearing Once and For All</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-do-when-laptopdesktop-wont-turn-on-essential-fixes/"><u>What to Do When Laptop/Desktop Won't Turn On - Essential Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-strategies-to-overcome-continuous-windows-10-startup-issues/"><u>Winning Strategies to Overcome Continuous Windows 10 Startup Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-with-unshuttable-windows-10-systems-fixed/"><u>Winning the Battle with Unshuttable Windows 10 Systems [FIXED]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://proteahair.pxf.io/c/5597632/1983634/23621" target="_top" id="1983634"><img src="//a.impactradius-go.com/display-ad/23621-1983634" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983634/23621" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->