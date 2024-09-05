---
title: "Error Code E80240020 Explained: Solving the Windows 10 Installation Failure"
date: 2024-09-04T20:25:12.116Z
updated: 2024-09-05T20:25:12.116Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code E80240020 Explained: Solving the Windows 10 Installation Failure"
excerpt: "This Article Describes Error Code E80240020 Explained: Solving the Windows 10 Installation Failure"
thumbnail: https://thmb.techidaily.com/7b4e6458caaa3e9950165c60cd6d036d2d81733c195f98fbf5326f59e3a1eeef.jpg
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-timing-and-frequency-their-effect-on-youtube-rankings/"><u>[New] 2024 Approved  Timing & Frequency  Their Effect on YouTube Rankings</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-unveiling-the-power-of-three-tiers-in-crafting-fb-ad-engaging-messages/"><u>[New] 2024 Approved  Unveiling the Power of Three Tiers in Crafting FB Ad Engaging Messages</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-capturing-life-on-a-macbook-air-the-comprehensive-guide-to-screen-recording/"><u>[New] In 2024, Capturing Life on a MacBook Air  The Comprehensive Guide to Screen Recording</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-smart-snip-skills-advanced-tips-for-iphone-photo-cropping/"><u>[New] Smart Snip Skills  Advanced Tips for iPhone Photo Cropping</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-step-by-step-guide-to-enhance-video-content-via-srt-transcoding/"><u>[New] Step-by-Step Guide to Enhance Video Content via SRT Transcoding</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-visionvoice-tips-for-perfectly-sized-insta-posts/"><u>[New] VisionVoice  Tips for Perfectly Sized Insta Posts</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-igtv-to-fb-exposure-guide-5-top-methods/"><u>[Updated] 2024 Approved  IGTV to FB Exposure Guide (5 Top Methods)</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-swiftly-flip-and-swivel-movies-for-a-better-viewing-experience-using-vlc/"><u>[Updated] 2024 Approved  Swiftly Flip and Swivel Movies for a Better Viewing Experience Using VLC</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-best-practices-for-documenting-live-streamed-sporting-matches/"><u>[Updated] In 2024, Best Practices for Documenting Live-Streamed Sporting Matches</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-apps-upgrade-your-mobile-movies-instantly/"><u>[Updated] Top Apps  Upgrade Your Mobile Movies Instantly</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-ions-bold-step-forward-with-pro-3-a-comprehensive-camera-review/"><u>2024 Approved  ION's Bold Step Forward with Pro 3 - A Comprehensive Camera Review</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204279423-argue-how-problem-solving-leads-to-creative-thinking-innovation-and-progress-in-various-fields-eg-technology-medicine/"><u>Argue How Problem-Solving Leads to Creative Thinking, Innovation, and Progress in Various Fields (E.g., Technology, Medicine).</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/awaken-with-ease-the-ultimate-list-of-our-favorite-alarm-clock-apps/"><u>Awaken with Ease: The Ultimate List of Our Favorite Alarm Clock Apps</u></a></li>
<li><a href="https://android-unlock.techidaily.com/best-ways-on-how-to-unlockbypassswiperemove-motorola-edge-40-pro-fingerprint-lock-by-drfone-android/"><u>Best Ways on How to Unlock/Bypass/Swipe/Remove Motorola Edge 40 Pro Fingerprint Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-broken-usb-input-devices-in-microsofts-windows-xpvista7-platform/"><u>Effective Fixes for Broken USB Input Devices in Microsoft's Windows XP/Vista/7 Platform</u></a></li>
<li><a href="https://blog-min.techidaily.com/einfach-und-schnell-konvertieren-sie-ihr-acsm-gewahrtes-ebook-ins-universelle-epub-dateiformat/"><u>Einfach Und Schnell: Konvertieren Sie Ihr ACSM-Gewährtes eBook Ins Universelle EPUB-Dateiformat</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-the-long-delay-alert-in-semaphore-systems-fix-for-error-code-0x80070079/"><u>Eliminate the Long Delay Alert in Semaphore Systems - Fix for Error Code 0X80070079</u></a></li>
<li><a href="https://program-issues.techidaily.com/five-quick-ways-to-prevent-your-bluestacks-app-from-crashing-again/"><u>Five Quick Ways to Prevent Your BlueStacks App From Crashing Again</u></a></li>
<li><a href="https://common-error.techidaily.com/from-darkness-to-display-troubleshooting-guide-to-fix-google-chromes-black-out-problem/"><u>From Darkness to Display: Troubleshooting Guide to Fix Google Chrome's Black Out Problem</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/fueled-by-innovative-cookiebot-solutions/"><u>Fueled by Innovative Cookiebot Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/google-chrome-black-screen-error-step-by-step-solutions-for-a-clear-display/"><u>Google Chrome Black Screen Error - Step-by-Step Solutions for a Clear Display</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-camera-functionality-on-lenovo-devices/"><u>Guide to Restoring Camera Functionality on Lenovo Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-resolving-failed-to-initialize-network-error-in-dragon-ball-fighterz-gaming-experience/"><u>Guide: Resolving 'Failed to Initialize Network' Error in Dragon Ball FighterZ Gaming Experience</u></a></li>
<li><a href="https://android-frp.techidaily.com/how-to-bypass-frp-on-oppo-a78-5g-by-drfone-android/"><u>How to Bypass FRP on Oppo A78 5G?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-failing-remote-procedure-call-comprehensive-guide/"><u>How to Fix a Failing Remote Procedure Call - Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-master-bluetooth-on-windows-11-expert-strategies-for-flawless-device-sync/"><u>How to Master Bluetooth on Windows 11: Expert Strategies for Flawless Device Sync</u></a></li>
<li><a href="https://common-error.techidaily.com/non-responsive-component-in-correctly-configured-system/"><u>Non-Responsive Component in Correctly Configured System</u></a></li>
<li><a href="https://common-error.techidaily.com/optimal-cameras-compatible-with-windows-hello/"><u>Optimal Cameras Compatible with Windows Hello</u></a></li>
<li><a href="https://common-error.techidaily.com/origin-gaming-troubleshooting-guide-resolving-issues-in-your-game-configuration/"><u>Origin Gaming - Troubleshooting Guide: Resolving Issues in Your Game Configuration</u></a></li>
<li><a href="https://common-error.techidaily.com/preventing-unsolicited-boot-solving-the-mystery-of-self-activating-pcs-in-windows-10/"><u>Preventing Unsolicited Boot: Solving the Mystery of Self-Activating PCs in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-inoperative-touchpad-scrolling-glitches-on-your-windows-11-device/"><u>Resolve Inoperative Touchpad Scrolling Glitches on Your Windows 11 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-what-to-do-when-your-symbol-wont-type/"><u>Solving the Problem: What to Do When Your '@' Symbol Won't Type</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203164294-struggling-with-pdf-printer-issues-heres-how-to-overcome-them/"><u>Struggling with PDF Printer Issues? Here's How to Overcome Them!</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-ultimate-deck-to-deck-users-manual-for-durecorder-for-2024/"><u>The Ultimate Deck-to-Deck User's Manual for DuRecorder for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-desktop-window-managers-gpu-consumption-on-windows/"><u>Top 5 Solutions for Reducing Desktop Window Manager's GPU Consumption on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-repair-resolving-keyboard-problems-on-hp-computers-fast/"><u>Troubleshoot & Repair: Resolving Keyboard Problems on HP Computers Fast!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-the-this-device-is-missing-code-24-on-windows-platforms/"><u>Troubleshooting Guide: Fixing the 'This Device Is Missing (Code 24)' On Windows Platforms</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208660770-troubleshooting-hp-laptop-usb-connectivity-fixes-and-solutions/"><u>Troubleshooting HP Laptop USB Connectivity: Fixes & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-rdr2-memory-errors-enhancing-page-file-size/"><u>Troubleshooting RDR2 Memory Errors: Enhancing Page File Size</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/upgrade-your-ai-interaction-signing-up-for-plugin-features/"><u>Upgrade Your AI Interaction: Signing Up for Plugin Features</u></a></li>
<li><a href="https://common-error.techidaily.com/win11-and-win10-overcoming-additional-display-problems/"><u>Win11 & Win10: Overcoming Additional Display Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-v1607-upgrade-process-fails-to-complete/"><u>Windows 11 v1607 Upgrade Process Fails to Complete</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="2135472">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135472%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135472/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->