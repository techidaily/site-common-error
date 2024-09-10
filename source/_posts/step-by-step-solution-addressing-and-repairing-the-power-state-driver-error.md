---
title: "Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
date: 2024-09-09T09:02:20.470Z
updated: 2024-09-10T09:02:20.470Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
excerpt: "This Article Describes Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
thumbnail: https://thmb.techidaily.com/7143579495d0f62e1a2cda12fd626d9036d87a576b32c356f772aa95549b6f82.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137222/26400" target="_top" id="2137222">
  <img src="//a.impactradius-go.com/display-ad/26400-2137222" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137222/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123481/16836" target="_top" id="2123481">
  <img src="//a.impactradius-go.com/display-ad/16836-2123481" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123481/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-seamless-android-screen-grabber/"><u>[New] 2024 Approved Seamless Android Screen Grabber</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/inding-equilibrium-between-professional-life-and-youtubing/"><u>[New] Finding Equilibrium Between Professional Life and YouTubing</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-translate-compressed-files-into-subtitle-format-srt/"><u>[New] In 2024, Translate Compressed Files Into Subtitle Format (SRT)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-simplifying-video-production-in-captivate-software-for-2024/"><u>[New] Simplifying Video Production in Captivate Software for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-social-simulacrum-sculpting-crafting-exaggerated-profiles/"><u>[Updated] 2024 Approved Social Simulacrum Sculpting Crafting Exaggerated Profiles</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-nailing-the-perfect-timelapse-with-ios-devices/"><u>[Updated] In 2024, Nailing the Perfect Timelapse with iOS Devices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-secret-sonic-snatchers-6-in-the-shadows-voice-recording-apps/"><u>[Updated] Secret Sonic Snatchers 6 In-the-Shadows Voice Recording Apps</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-toggle-your-youtube-video-with-picture-in-picture-on-ios/"><u>2024 Approved Toggle Your YouTube Video with Picture-in-Picture on iOS</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/a-glimpse-into-the-past-ancient-crt-hit-remarkable-700hz-lowers-clarity-for-ultra-fast-refresh-rates/"><u>A Glimpse Into the Past: Ancient CRT Hit Remarkable 700Hz, Lowers Clarity for Ultra-Fast Refresh Rates</u></a></li>
<li><a href="https://common-error.techidaily.com/anaplastic-thyroid-carcinoma-exhibits-a-diverse-array-of-genetic-changes-that-contribute-to-its-aggressive-behavior-and-resistance-to-conventional-treatment68/"><u>Anaplastic Thyroid Carcinoma Exhibits a Diverse Array of Genetic Changes that Contribute to Its Aggressive Behavior and Resistance to Conventional Treatments</u></a></li>
<li><a href="https://common-error.techidaily.com/beating-the-easy-anti-cheat-challenge-in-apex-legends-your-complete-guide-to-solutions/"><u>Beating the Easy Anti-Cheat Challenge in Apex Legends – Your Complete Guide to Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-vivo-v30-lite-5g-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Vivo V30 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-pairing-established-on-windows-11-but-still-fails-to-transfer-data-fixes-needed/"><u>Bluetooth Pairing Established on Windows 11 but Still Fails to Transfer Data - Fixes Needed?</u></a></li>
<li><a href="https://common-error.techidaily.com/chrome-not-responding-heres-how-to-relaunch-and-continue-seamlessly/"><u>Chrome Not Responding? Here's How to Relaunch and Continue Seamlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201528006-corrupt-system-drivers-master-swift-fix-techniques-today/"><u>Corrupt System Drivers? Master Swift Fix Techniques Today</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-unsuccessful-rpcs-learn-how-to-correct-them-here/"><u>Dealing With Unsuccessful RPCs? Learn How To Correct Them Here</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-ways-to-overcome-steams-disc-writing-mistakes/"><u>Effortless Ways to Overcome Steam's Disc Writing Mistakes</u></a></li>
<li><a href="https://common-error.techidaily.com/ensuring-seamless-operation-addressing-driver-mismatches-in-the-ftdi-system/"><u>Ensuring Seamless Operation: Addressing Driver Mismatches in the FTDI System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-overcome-the-windows-hresult-error-0xc0000098/"><u>Expert Tips to Overcome the Windows HRESULT Error 0xC0000098</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-window-speakers-with-intermittent-sound-issues/"><u>How to Fix Window Speakers with Intermittent Sound Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-xbox-one-connection-issues-with-xbox-live-solved/"><u>How to Fix Your Xbox One Connection Issues with Xbox Live (Solved)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quiet-down-a-loud-playstation-4-fan-diagnosis-and-repair-tips/"><u>How to Quiet Down a Loud PlayStation 4 Fan – Diagnosis and Repair Tips</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-vivo-s17t-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Vivo S17t</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-top-12-prominent-poco-x6-pro-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Poco X6 Pro Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/initiation-denied-by-script/"><u>Initiation Denied by Script</u></a></li>
<li><a href="https://discover-blog.techidaily.com/leveraging-cookiebot-technology-for-advanced-web-engagement-insights/"><u>Leveraging Cookiebot Technology for Advanced Web Engagement Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/logitech-mouse-scroll-troubles-easy-fixes-and-solutions/"><u>Logitech Mouse Scroll Troubles: Easy Fixes and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-your-windows-experience-leveraging-system-file-checker-and-deployment-image-servicing-for-troubleshooting/"><u>Optimizing Your Windows Experience: Leveraging System File Checker and Deployment Image Servicing for Troubleshooting</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-fan-loud-why-and-how-to-fix-it/"><u>PS4 Fan Loud: Why & How to Fix It?</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-the-dreaded-black-or-blank-screen-on-your-laptop/"><u>Resolved: How to Fix the Dreaded Black or Blank Screen on Your Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203114476-resolving-apex-legends-cheating-issues-the-simple-fix-youve-been-waiting-for/"><u>Resolving Apex Legends Cheating Issues: The Simple Fix You've Been Waiting For</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-typewriter-keys-malfunction-across-windows-operating-systems-windows-10-7-8/"><u>Resolving Typewriter Keys Malfunction Across Windows Operating Systems (Windows 10, 7, 8)</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-microsoft-store-errors-a-comprehensive-solution-walkthrough/"><u>Solving Microsoft Store Errors: A Comprehensive Solution Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-eliminate-windows-wireless-speaker-crackle-on-win11-and-win7/"><u>Step-by-Step Guide: Eliminate Window's Wireless Speaker Crackle on Win11 & Win7</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-gpu-load-caused-by-the-desktop-window-manager-on-windows-10-and-11/"><u>Top 5 Solutions for Reducing GPU Load Caused by the Desktop Window Manager on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-errconnectionrefused-error-with-visual-aids/"><u>Troubleshooting ERR_CONNECTION_REFUSED Error with Visual Aids</u></a></li>
<li><a href="https://driver-download.techidaily.com/troubleshooting-guide-for-linksys-ae1200-wireless-router-driver-installation-best-practices-and-fixes/"><u>Troubleshooting Guide for Linksys AE1200 Wireless Router Driver Installation – Best Practices & Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-minecraft-local-area-network-lan-connection-issues/"><u>Troubleshooting Guide: Fixing Minecraft Local Area Network (LAN) Connection Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-windows-10-and-11-file-system-issues-efficiently/"><u>Troubleshooting Guide: Resolving Windows 10 & 11 File System Issues Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-when-windows-cant-identify-the-right-printer-driver/"><u>Troubleshooting Guide: When Windows Can't Identify the Right Printer Driver</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/ultimate-guide-removing-unwanted-pre-installed-apps-from-your-android-device/"><u>Ultimate Guide: Removing Unwanted Pre-Installed Apps From Your Android Device</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-the-incorrect-parameter-in-loadlibrary-failures-error-87/"><u>Understanding and Resolving the 'Incorrect Parameter' In LoadLibrary Failures (Error 87)</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/webcam-wonders-unveiling-tools-for-top-video-quality/"><u>Webcam Wonders - Unveiling Tools for Top Video Quality</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-oversleeper-dilemma-computer-wont-wake/"><u>Windows' Oversleeper Dilemma - Computer Won't Wake</u></a></li>
</ul></div>
