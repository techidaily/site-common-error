---
title: "Resolved: Fixing 'Video File Can't Play - Error 224003'"
date: 2024-08-22T19:28:43.709Z
updated: 2024-08-23T19:28:43.710Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing 'Video File Can't Play - Error 224003'"
excerpt: "This Article Describes Resolved: Fixing 'Video File Can't Play - Error 224003'"
thumbnail: https://thmb.techidaily.com/264e08da433495c55cd3d8de7fab0afb684fb451a8ac533f579ade7f75a2ecaa.png
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
<li><a href="https://facebook-record-videos.techidaily.com/new-10-top-editing-apps-at-no-cost-online-for-2024/"><u>[New] 10 Top Editing Apps at No Cost Online for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-erase-the-obvious-techniques-for-masked-youtube-content-for-2024/"><u>[New] Erase the Obvious  Techniques for Masked YouTube Content for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-leading-windows-apps-top-video-editing-picks/"><u>[New] Leading Windows Apps  Top Video Editing Picks</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-mastering-full-rotation-shoots-9-must-follow-rules/"><u>[New] Mastering Full-Rotation Shoots  9 Must-Follow Rules</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-microsoft-compatibility-telemetry-high-disk-usage-on-windows-11/"><u>[Solved] Microsoft Compatibility Telemetry High Disk Usage on Windows 11</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-discover-10-free-high-quality-live-stream-apps-for-iphones-and-androids/"><u>[Updated] 2024 Approved  Discover 10 Free, High-Quality Live Stream Apps for iPhones and Androids</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-in-2024-is-it-legal-to-record-youtube/"><u>[Updated] In 2024, Is It Legal to Record YouTube?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-step-by-step-techniques-for-efficiently-timestamp-youtube-content/"><u>[Updated] Step-by-Step Techniques for Efficiently Timestamp YouTube Content</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-turn-every-instagram-moment-into-a-shareable-mp4-file/"><u>[Updated] Turn Every Instagram Moment Into a Shareable MP4 File</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-top-ranked-hd-screen-capturing-tools/"><u>2024 Approved  Top-Ranked HD Screen Capturing Tools</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/3-part-blueprint-to-monitor-and-maximize-your-youtube-profits/"><u>3-Part Blueprint to Monitor and Maximize Your YouTube Profits</u></a></li>
<li><a href="https://blog-min.techidaily.com/best-3-software-to-transfer-files-tofrom-your-oppo-k11x-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Best 3 Software to Transfer Files to/from Your Oppo K11x via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-troubleshooting-tips-for-a-wireless-mouse-that-stops-working-intermittently-on-windows/"><u>Comprehensive Troubleshooting Tips for a Wireless Mouse That Stops Working Intermittently on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-lack-of-light-on-your-razer-illuminated-keyboard/"><u>Diagnosing and Fixing Lack of Light on Your Razer Illuminated Keyboard</u></a></li>
<li><a href="https://fox-info.techidaily.com/elevate-your-phones-alerts-personalizing-ringtones-and-sounds-on-android-for-2024/"><u>Elevate Your Phone's Alerts  Personalizing Ringtones & Sounds on Android for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/enhance-windows-7-boot-speed-with-proven-strategies-overcome-system-lags-easily/"><u>Enhance Windows 7 Boot Speed with Proven Strategies: Overcome System Lags Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/ensuring-smooth-gameplay-how-to-address-steam-download-problems-efficiently/"><u>Ensuring Smooth Gameplay: How to Address Steam Download Problems Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-fixing-the-update-error-in-windows-11-code-0x80240034/"><u>Expert Advice on Fixing the 'Update Error' In Windows 11 (Code 0X80240034)</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-analysis-of-cutting-edge-computing-equipment-by-toms-experts/"><u>Expert Analysis of Cutting-Edge Computing Equipment by Tom's Experts</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-dota-2-changerenderingapierror-2024-quickly-and-easily/"><u>Fix Dota 2 'ChangeRenderingAPI:Error 2024' Quickly and Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-comprehensive-guide-on-resolving-windows-camera-error-0xa00f4292/"><u>Fixing the Issue: Comprehensive Guide on Resolving Windows Camera Error 0xA00F4292</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-spacebar-issue-in-windows-10-a-step-by-step-guide/"><u>Fixing the Spacebar Issue in Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-windows-10-version-1903-upgrade-problems-successfully/"><u>Fixing the Windows 10 Version 1903 Upgrade Problems Successfully</u></a></li>
<li><a href="https://win-dash.techidaily.com/hassle-free-installation-comprehensive-guide-for-downloading-your-xbox-wireless-adapter-drivers/"><u>Hassle-Free Installation: Comprehensive Guide for Downloading Your Xbox Wireless Adapter Drivers</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-4-feasible-ways-to-fake-location-on-facebook-for-your-vivo-x100-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Feasible Ways to Fake Location on Facebook For your Vivo X100 Pro | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-ways-to-find-unlocking-codes-for-vivo-y27s-phones-by-drfone-android/"><u>In 2024, Ways To Find Unlocking Codes For Vivo Y27s Phones</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-nokia-xr21-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Live Location is Not Updating and How to Fix on your Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/learning-the-pixiz-method-for-photo-based-video-crafting/"><u>Learning the Pixiz Method for Photo-Based Video Crafting</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-microphone-issues-on-laptops-effective-solutions-unveiled/"><u>Mastering Microphone Issues on Laptops - Effective Solutions Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-11-update-obstacle-with-code-0x800f0922-fixes/"><u>Overcome Windows 11 Update Obstacle with Code 0X800F0922 Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/pilgrimage/"><u>Pilgrimage</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolving-the-common-windows-update-error-code-0x80070652/"><u>Quick Solutions: Resolving the Common Windows Update Error Code 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-d3dxt939dll-not-found-issues-a-step-by-step-guide/"><u>Resolving d3dxt9_39.dll Not Found Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-when-windows-security-feature-smartscreen-is-offline/"><u>Resolving Issues When Windows Security Feature SmartScreen Is Offline</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revolutionizing-the-joy-of-packet-opening/"><u>Revolutionizing the Joy of Packet Opening</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/setting-up-for-success-an-instagram-business-account-blueprint/"><u>Setting Up for Success  An Instagram Business Account Blueprint</u></a></li>
<li><a href="https://common-error.techidaily.com/shift-key-malfunctions-heres-how-you-can-get-it-fixed-now/"><u>Shift Key Malfunctions? Here's How You Can Get It Fixed Now</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-for-electric-spike-in-connector-junction/"><u>Solution Found for Electric Spike in Connector Junction</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-common-issues-fixing-non-downloading-torrents-made-easy/"><u>Solving Common Issues: Fixing Non-Downloading Torrents Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-incompatible-signal-issues-between-input-devices-and-displays/"><u>Solving Incompatible Signal Issues Between Input Devices and Displays</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-msmpengexe-high-cpu-usage-in-windows-11-a-comprehensive-guide/"><u>Solving MsMpEng.exe High CPU Usage in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-window-speaker-distortion-issues-on-windows-11-and-7-systems/"><u>Solving Window Speaker Distortion Issues on Windows 11 and 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-your-missing-bluetooth-icon-on-windows-11/"><u>Step-by-Step Guide: Restoring Your Missing Bluetooth Icon on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-what-to-do-if-your-key-is-malfunctioning/"><u>Step-by-Step Guide: What to Do If Your '@' Key Is Malfunctioning</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-for-solving-persistent-usb-device-unplugging-issues/"><u>Step-by-Step Tips for Solving Persistent USB Device Unplugging Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-restoring-functionality-of-your-lenovos-fingerprint-reader/"><u>Step-by-Step: Restoring Functionality of Your Lenovo's Fingerprint Reader</u></a></li>
<li><a href="https://win11-tips.techidaily.com/steps-to-resolve-iphone-image-failure-in-windows-os/"><u>Steps to Resolve iPhone Image Failure in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211894764-stop-your-laptop-from-falling-asleep-simple-solutions-now/"><u>Stop Your Laptop From Falling Asleep: Simple Solutions Now!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/techniques-to-boost-video-quality-on-web-browser-chrome/"><u>Techniques to Boost Video Quality on Web Browser Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-solution-to-a-non-visible-mouse-on-your-windows-10-device/"><u>The Ultimate Solution to a Non-Visible Mouse on Your Windows 10 Device</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-google-pixel-fold-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Google Pixel Fold? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-non-functional-usb-ports-on-windows-11/"><u>Troubleshooting and Fixing Non-Functional USB Ports on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-custom-setup-unresponsive-issues/"><u>Troubleshooting Steps for Custom Setup Unresponsive Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-fix-non-functional-usb-ports-on-windows-1011-computers/"><u>Troubleshooting Steps to Fix Non-Functional USB Ports on Windows 10/11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-your-microsoft-store-refuses-to-start-up/"><u>Troubleshooting Tips for When Your Microsoft Store Refuses to Start Up</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-if-vac-isnt-verifying-your-online-gaming-session/"><u>Troubleshooting Tips If VAC Isn't Verifying Your Online Gaming Session</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-the-mystery-of-error-1-4-a-detailed-guide-for-smoothing-out-livekernelevents/"><u>Unraveling the Mystery of Error 1# #4: A Detailed Guide for Smoothing Out LiveKernelEvents</u></a></li>
<li><a href="https://common-error.techidaily.com/utilizing-system-file-checker-and-dism-for-optimized-windows-11-recovery-options/"><u>Utilizing System File Checker & DISM for Optimized Windows 11 Recovery Options</u></a></li>
<li><a href="https://screen-capture.techidaily.com/virtual-producer-duel/"><u>Virtual Producer Duel</u></a></li>
<li><a href="https://common-error.techidaily.com/wins-kernel32-error-how-to-solve-it/"><u>Win's Kernel32 Error: How to Solve It?</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-usb-issues-resolved-tips-for-restoring-port-functionality/"><u>Windows 11 USB Issues Resolved: Tips for Restoring Port Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-failing-windows-updates-now-fixed/"><u>Winning the Battle Against Failing Windows Updates - Now Fixed!</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-svchostexes-heavy-load-on-your-windows-11-pc-detailed-strategies/"><u>Winning the Battle Against svchost.exe's Heavy Load on Your Windows 11 PC [Detailed Strategies]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->