---
title: "[Solved] Error Code 0X80073cf9 in Windows 10 Store"
date: 2024-08-15T11:12:33.460Z
updated: 2024-08-16T11:12:33.460Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [Solved] Error Code 0X80073cf9 in Windows 10 Store
excerpt: This Article Describes [Solved] Error Code 0X80073cf9 in Windows 10 Store
thumbnail: https://thmb.techidaily.com/ee549b864de6102ff48675fa7bf1a7613a21bc32bbc71908950ecf0a34fbb345.jpg
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
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-achieve-proficiency-in-audio-upload-with-google/"><u>[New] 2024 Approved  Achieve Proficiency in Audio Upload with Google</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-enhance-your-social-media-experience-with-these-top-tools/"><u>[New] 2024 Approved  Enhance Your Social Media Experience with These Top Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-turn-the-clock-back-reverse-video-mastery-in-instagram/"><u>[New] 2024 Approved  Turn the Clock Back  Reverse Video Mastery in Instagram</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-decoding-youtube-shorts-all-you-need-to-understand/"><u>[New] Decoding YouTube Shorts  All You Need to Understand</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-harmonizing-your-calendar-with-zoom-appointments-on-all-screens/"><u>[New] In 2024, Harmonizing Your Calendar With Zoom Appointments on All Screens</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-mastering-fb-video-promos-access-free-video-toolkit/"><u>[New] In 2024, Mastering FB Video Promos  Access Free Video Toolkit</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-step-up-your-streams-advanced-practices-for-capturing-vr-playtimes-for-2024/"><u>[New] Step Up Your Streams  Advanced Practices for Capturing VR Playtimes for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-top-10-secrets-to-skyrocket-your-social-media-engagement-on-fb/"><u>[New] Top 10 Secrets to Skyrocket Your Social Media Engagement on FB</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-audiovisual-power-evaluating-mirrorless-vs-dslr-cameras/"><u>[Updated] Audiovisual Power  Evaluating Mirrorless vs DSLR Cameras</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-capture-and-save-video-images-on-windows-11/"><u>[Updated] Capture and Save Video Images on Windows 11</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-iconic-imagery-transforming-audio-into-visual-podcast-identity/"><u>[Updated] Iconic Imagery  Transforming Audio Into Visual Podcast Identity</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-qualitysound-check/"><u>[Updated] In 2024, QualitySound Check</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-netflix-archive-the-complete-guide-to-screencapturing-your-views-for-2024/"><u>[Updated] Netflix Archive  The Complete Guide to ScreenCapturing Your Views for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-realme-12-proplus-5g-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Realme 12 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-ios-meets-android-an-in-depth-look-at-facial-tech/"><u>2024 Approved  IOS Meets Android  An In-Depth Look at Facial Tech</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-masterpieces-in-3d-graphics-and-golden-displaytexts-online/"><u>2024 Approved  Masterpieces in 3D Graphics and Golden DisplayTexts Online</u></a></li>
<li><a href="https://data-wizards.techidaily.com/app-support-mandate/"><u>App Support Mandate</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/bending-words-altering-text-images/"><u>Bending Words  Altering Text Images</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-free-from-code-breakdowns-quick-windows-fixes/"><u>Breaking Free From Code Breakdowns: Quick Windows Fixes</u></a></li>
<li><a href="https://extra-tips.techidaily.com/breaking-ground-in-video-marketing-setting-up-a-review-chain/"><u>Breaking Ground in Video Marketing  Setting Up a Review Chain</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-stop-error-in-hamachi-service-a-step-by-step-guide-to-restoration/"><u>Bypassing the Stop Error in Hamachi Service - A Step-by-Step Guide to Restoration</u></a></li>
<li><a href="https://common-error.techidaily.com/class-not-registered-on-windows-10-solved/"><u>Class Not Registered on Windows 10 [Solved]</u></a></li>
<li><a href="https://techtrends.techidaily.com/comprehensive-guide-to-repair-vcompdll-missing-issues-a-users-manual/"><u>Comprehensive Guide to Repair vcomp.dll Missing Issues: A User's Manual</u></a></li>
<li><a href="https://common-error.techidaily.com/conclusion-drivers-dont-support-opengl/"><u>Conclusion: Drivers Don't Support OpenGL</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-failed-installs-of-windows-11-build-1607-features/"><u>Diagnosing Failed Installs of Windows 11, Build 1607 Features</u></a></li>
<li><a href="https://common-error.techidaily.com/disable-antivirus-software-temporarily/"><u>Disable Antivirus Software Temporarily</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-the-best-intel-wi-fi-6-ax200-drivers-with-updates-for-optimal-functionality-on-windows-11-and-10-computers/"><u>Download the Best Intel Wi-Fi 6 AX200 Drivers with Updates for Optimal Functionality on Windows 11 and 10 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/endgame-interruptions-fixing-pc-pauses-on-the-go/"><u>Endgame Interruptions: Fixing PC Pauses On-the-Go</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208069021-enhance-windows-7-launch-speed-top-solutions-to-combat-delays/"><u>Enhance Windows 7 Launch Speed: Top Solutions to Combat Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-malfunctioning-microphone-on-your-laptop-step-by-step-guide/"><u>Fixing a Malfunctioning Microphone on Your Laptop - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unavailable-steamapi64-dll-in-game/"><u>Fixing Unavailable Steam_api64 DLL in Game</u></a></li>
<li><a href="https://driver-install.techidaily.com/flawless-lenovo-z50-70-driver-improvements/"><u>Flawless Lenovo Z50-70 Driver Improvements</u></a></li>
<li><a href="https://common-error.techidaily.com/from-pitch-black-to-bright-ideas-repairing-full-screen-darkness-in-google-chrome/"><u>From Pitch Black to Bright Ideas: Repairing Full-Screen Darkness in Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-diagnose-and-fix-screen-fluctuations-in-windows-10-environment/"><u>Guide to Diagnose and Fix Screen Fluctuations in Windows 10 Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-the-print-screen-feature-with-windowsplusshiftpluss-on-modern-windows-systems/"><u>Guide to Restoring the 'Print Screen' Feature with Windows+Shift+S on Modern Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-visible-touchpad-pointer-on-windows-11/"><u>Guide to Restoring Visible Touchpad Pointer on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-overcoming-errors-when-steams-vac-cant-validate-your-match/"><u>Guide: Overcoming Errors when Steam's VAC Can’t Validate Your Match</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-restoring-vcruntime140dll-file-to-fix-your-windows-10-app-startup-errors/"><u>Guide: Restoring VCRUNTIME140.dll File to Fix Your Windows 10 App Startup Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-laptop-running-again-fast-charging-solutions/"><u>How to Get Your Laptop Running Again: Fast Charging Solutions</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-install-and-update-hardware-device-drivers-manually-in-windows-11-by-drivereasy-guide/"><u>How to install and update hardware device drivers manually in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-scrolling-problems-with-your-pcs-touchpad-on-windows-10/"><u>How to Repair Scrolling Problems with Your PC's Touchpad on Windows 10</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-3-ways-to-track-apple-iphone-6s-plus-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>In 2024, 3 Ways to Track Apple iPhone 6s Plus without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-direct-link-sharing-twitter-writes-on-whatsapp/"><u>In 2024, Direct Link  Sharing Twitter' Writes on WhatsApp</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-essential-playgrounds-for-virtual-escapades/"><u>In 2024, Essential Playgrounds for Virtual Escapades</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-remove-and-reset-face-id-on-apple-iphone-11-by-drfone-ios/"><u>In 2024, How to Remove and Reset Face ID on Apple iPhone 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-oneplus-nord-ce-3-lite-5g-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track OnePlus Nord CE 3 Lite 5G by Phone Number | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/internal-structures-like-baffles-and-weirs-can-enhance-sedimentation-by-reducing-turbulence-and-controlling-outflow-rates-for-maximum-contact-time-within-se151/"><u>Internal Structures Like Baffles and Weirs Can Enhance Sedimentation by Reducing Turbulence and Controlling Outflow Rates for Maximum Contact Time Within Settling Zones.</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-resolution-eliminate-code-0x800f0831-with-ease-using-windows-update-features/"><u>Mastering Error Resolution: Eliminate Code 0X800^F0831 with Ease Using Windows Update Features</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-dark-mode-controls-fix-needed/"><u>Missing Dark Mode Controls: Fix Needed</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-how-to-successfully-power-off-your-computer-running-windows-11/"><u>Quick Fix: How to Successfully Power Off Your Computer Running Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-a-broken-right-click-a-windows-11-users-manual/"><u>Quick Fixes for a Broken Right Click: A Windows 11 User's Manual</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-missing-bluetooth-on-your-windows-10-device-expert-tips-and-tricks/"><u>Quick Fixes for Missing Bluetooth on Your Windows 10 Device: Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-addressing-and-correcting-stop-errors-in-hamachi/"><u>Quick Guide: Addressing and Correcting Stop Errors in Hamachi</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-resolving-windows-update-hanging-at-zero-percent/"><u>Quick Solutions for Resolving Window's Update Hanging at Zero Percent</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-msvcp140dll-integrity/"><u>Restoring MSVCP140.dll Integrity</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-intermittent-sounds-in-your-logitech-g930-wireless-earphones/"><u>Solution for Intermittent Sounds in Your Logitech G930 Wireless Earphones</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-no-audio-output-devices-found-on-windows-11/"><u>Solving 'No Audio Output Devices Found' On Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-windows-update-failed-with-code-0x80070643/"><u>Step-by-Step Fix for Windows Update Failed with Code 0X80070643</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-functionality-of-lenovos-biometric-scanner/"><u>Step-by-Step Guide: Restoring Functionality of Lenovo's Biometric Scanner</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-fixing-disconnected-remote-servers/"><u>Step-by-Step Solutions for Fixing Disconnected Remote Servers</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-how-to-securely-connect-your-airpods-to-windows-10-and-11-latest-troubleshooting-techniques/"><u>The Ultimate Fix: How to Securely Connect Your AirPods to Windows 10 and 11 (Latest Troubleshooting Techniques)</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-10-solutions-for-troubleshooting-your-wireless-adapteraccess-point-issues/"><u>Top 10 Solutions for Troubleshooting Your Wireless Adapter/Access Point Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-issues-when-opening-geforce-experience/"><u>Troubleshooting Guide: Resolving Issues When Opening GeForce Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-power-surge-issues-at-the-networking-hub/"><u>Troubleshooting Guide: Resolving Power Surge Issues at the Networking Hub</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-no-speakers-solving-audio-device-installation-problems-in-windows/"><u>Troubleshooting No Speakers: Solving Audio Device Installation Problems in Windows</u></a></li>
<li><a href="https://android-location-track.techidaily.com/ways-to-stop-parent-tracking-your-xiaomi-redmi-note-12r-drfone-by-drfone-virtual-android/"><u>Ways to stop parent tracking your Xiaomi Redmi Note 12R | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/wireless-woes-no-more-a-comprehensive-guide-to-sync-your-airpods-with-windows-pcs/"><u>Wireless Woes No More: A Comprehensive Guide to Sync Your AirPods with Windows PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->