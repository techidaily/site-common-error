---
title: Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved
date: 2024-09-04T20:21:58.922Z
updated: 2024-09-05T20:21:58.922Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved
excerpt: This Article Describes Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved
thumbnail: https://thmb.techidaily.com/20681dc3787d86713afd2395e0942d0819f5bca12434956d1fe5521df7d6718e.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

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
<li><a href="https://youtube-webster.techidaily.com/024-approved-11-fitness-youtube-video-ideas-to-keep-you-and-your-viewers-moving/"><u>[New] 2024 Approved  11 Fitness YouTube Video Ideas to Keep You and Your Viewers Moving</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-how-do-beginners-make-a-cool-video-for-youtube-on-mac/"><u>[New] 2024 Approved  How Do Beginners Make a Cool Video for YouTube on Mac</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-steps-to-ensure-obs-captures-sound-effectively/"><u>[New] 2024 Approved  Steps to Ensure OBS Captures Sound Effectively</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-transforming-youtubers-into-titans-with-key-insights-from-the-hub/"><u>[New] 2024 Approved  Transforming YouTubers Into Titans with Key Insights From the Hub</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-stream-to-instagram-effortless-broadcast-via-obs-software/"><u>[Updated] In 2024, Stream to Instagram  Effortless Broadcast via OBS Software</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-transform-meetings-with-easy-to-follow-zoom-sharing-tips-for-2024/"><u>[Updated] Transform Meetings with Easy-to-Follow Zoom Sharing Tips for 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-youtube-riches-with-best-hash-tags-tips-for-2024/"><u>[Updated] YouTube Riches with Best Hash Tags Tips for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/2024-approved-maximizing-facebook-favorites-perfecting-square-video-crafting/"><u>2024 Approved  Maximizing Facebook Favorites  Perfecting Square Video Crafting</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/8-best-apps-for-screen-mirroring-lava-agni-2-5g-pc-drfone-by-drfone-android/"><u>8 Best Apps for Screen Mirroring Lava Agni 2 5G PC | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/class-not-registered-on-windows-10-solved/"><u>Class Not Registered on Windows 10 [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-failed-installs-of-windows-11-build-1607-features/"><u>Diagnosing Failed Installs of Windows 11, Build 1607 Features</u></a></li>
<li><a href="https://common-error.techidaily.com/disable-antivirus-software-temporarily/"><u>Disable Antivirus Software Temporarily</u></a></li>
<li><a href="https://activate-lock.techidaily.com/easy-tutorial-for-activating-icloud-from-apple-iphone-se-2022-safe-and-legal-by-drfone-ios/"><u>Easy Tutorial for Activating iCloud from Apple iPhone SE (2022) Safe and Legal</u></a></li>
<li><a href="https://video-capture.techidaily.com/farmers-hangout-top-10-friendly-agricultural-games-to-bond-with-friends/"><u>Farmers' Hangout  Top 10 Friendly Agricultural Games to Bond With Friends</u></a></li>
<li><a href="https://common-error.techidaily.com/from-pitch-black-to-bright-ideas-repairing-full-screen-darkness-in-google-chrome/"><u>From Pitch Black to Bright Ideas: Repairing Full-Screen Darkness in Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-the-print-screen-feature-with-windowsplusshiftpluss-on-modern-windows-systems/"><u>Guide to Restoring the 'Print Screen' Feature with Windows+Shift+S on Modern Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-visible-touchpad-pointer-on-windows-11/"><u>Guide to Restoring Visible Touchpad Pointer on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-restoring-vcruntime140dll-file-to-fix-your-windows-10-app-startup-errors/"><u>Guide: Restoring VCRUNTIME140.dll File to Fix Your Windows 10 App Startup Errors</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-to-fix-incorrect-website-activity-reporting-in-your-iphones-screen-time/"><u>How to Fix Incorrect Website Activity Reporting in Your iPhone's Screen Time</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-laptop-running-again-fast-charging-solutions/"><u>How to Get Your Laptop Running Again: Fast Charging Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-scrolling-problems-with-your-pcs-touchpad-on-windows-10/"><u>How to Repair Scrolling Problems with Your PC's Touchpad on Windows 10</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fix-nubia-z50-ultra-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Nubia Z50 Ultra Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-inshot-alternatives-for-laptop-editors/"><u>In 2024, Inshot Alternatives for Laptop Editors</u></a></li>
<li><a href="https://common-error.techidaily.com/internal-structures-like-baffles-and-weirs-can-enhance-sedimentation-by-reducing-turbulence-and-controlling-outflow-rates-for-maximum-contact-time-within-se151/"><u>Internal Structures Like Baffles and Weirs Can Enhance Sedimentation by Reducing Turbulence and Controlling Outflow Rates for Maximum Contact Time Within Settling Zones.</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-resolution-eliminate-code-0x800f0831-with-ease-using-windows-update-features/"><u>Mastering Error Resolution: Eliminate Code 0X800^F0831 with Ease Using Windows Update Features</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-a-broken-right-click-a-windows-11-users-manual/"><u>Quick Fixes for a Broken Right Click: A Windows 11 User's Manual</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-missing-bluetooth-on-your-windows-10-device-expert-tips-and-tricks/"><u>Quick Fixes for Missing Bluetooth on Your Windows 10 Device: Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-addressing-and-correcting-stop-errors-in-hamachi/"><u>Quick Guide: Addressing and Correcting Stop Errors in Hamachi</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-resolving-windows-update-hanging-at-zero-percent/"><u>Quick Solutions for Resolving Window's Update Hanging at Zero Percent</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-msvcp140dll-integrity/"><u>Restoring MSVCP140.dll Integrity</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-functionality-of-lenovos-biometric-scanner/"><u>Step-by-Step Guide: Restoring Functionality of Lenovo's Biometric Scanner</u></a></li>
<li><a href="https://fox-links.techidaily.com/symbolizing-sound-designing-a-captivating-podcast-image/"><u>Symbolizing Sound  Designing a Captivating Podcast Image</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-how-to-securely-connect-your-airpods-to-windows-10-and-11-latest-troubleshooting-techniques/"><u>The Ultimate Fix: How to Securely Connect Your AirPods to Windows 10 and 11 (Latest Troubleshooting Techniques)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-issues-when-opening-geforce-experience/"><u>Troubleshooting Guide: Resolving Issues When Opening GeForce Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-power-surge-issues-at-the-networking-hub/"><u>Troubleshooting Guide: Resolving Power Surge Issues at the Networking Hub</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-no-speakers-solving-audio-device-installation-problems-in-windows/"><u>Troubleshooting No Speakers: Solving Audio Device Installation Problems in Windows</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-in-2024-discover-the-best-10-animated-text-software-for-stunning-visuals/"><u>Updated In 2024, Discover the Best 10 Animated Text Software for Stunning Visuals</u></a></li>
<li><a href="https://common-error.techidaily.com/wireless-woes-no-more-a-comprehensive-guide-to-sync-your-airpods-with-windows-pcs/"><u>Wireless Woes No More: A Comprehensive Guide to Sync Your AirPods with Windows PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->