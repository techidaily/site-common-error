---
title: "Coding Stalled: Command Refused"
date: 2024-08-31T17:41:35.127Z
updated: 2024-09-01T17:41:35.127Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Coding Stalled: Command Refused"
excerpt: "This Article Describes Coding Stalled: Command Refused"
thumbnail: https://thmb.techidaily.com/96d460ad778074a93b63a308714d13a6fb98bd643d60a66bb372b318524a5b70.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-finding-storylines-with-google-trends-analysis-techniques/"><u>[New] In 2024, Finding Storylines with Google Trends Analysis Techniques</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-one-minute-color-magic/"><u>[New] One Minute Color Magic</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/nleashing-potential-the-ultimate-pathway-to-effective-youtube-banners-for-2024/"><u>[New] Unleashing Potential  The Ultimate Pathway to Effective YouTube Banners for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-and-instagram-synergy-posting-content-easily/"><u>[New] YouTube and Instagram Synergy  Posting Content Easily</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-crafting-stunning-youtubers-imagery-a-comprehensive-walkthrough-for-2024/"><u>[Updated] Crafting Stunning YouTubers' Imagery  A Comprehensive Walkthrough for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-redefine-your-online-persona-with-a-new-tiktok-profile-for-2024/"><u>[Updated] Redefine Your Online Persona with a New TikTok Profile for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-small-scale-screenplay-idea/"><u>2024 Approved  Small-Scale Screenplay Idea</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-service-initialization-now-successful-resolved-generic-error-issues/"><u>BattlEye Service Initialization Now Successful - Resolved Generic Error Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/best-practices-for-troubleshooting-crc-mismatches-in-data-transfer/"><u>Best Practices for Troubleshooting CRC Mismatches in Data Transfer</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-error-code-80240020-a-troubleshooters-guide-to-successfully-installing-windows-10/"><u>Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-restoring-corrupted-data-on-your-windows-11-pc/"><u>Comprehensive Solutions for Restoring Corrupted Data on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/cracking-down-on-distorted-sounds-fix-your-windows-107-speaker-problems/"><u>Cracking Down on Distorted Sounds: Fix Your Windows 10/7 Speaker Problems</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/creativity-meets-strength-with-crealitys-new-flagship-k1c-3d-printer-learn-about-its-impressive-specs/"><u>Creativity Meets Strength with Creality's New Flagship K1C 3D Printer - Learn About Its Impressive Specs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-samsung-galaxy-f14-5g-support-mkv-video-files-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Samsung Galaxy F14 5G support MKV video files?</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-security-measures-activated-for-local-systems/"><u>Enhanced Security Measures Activated for Local Systems</u></a></li>
<li><a href="https://win11.techidaily.com/enhancing-user-interface-with-fn-key-modifications/"><u>Enhancing User Interface with FN Key Modifications</u></a></li>
<li><a href="https://common-error.techidaily.com/eternal-rest-for-my-system-wake-fail/"><u>Eternal Rest for My System: Wake Fail</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-prevent-and-solve-oddworld-soulstorm-freezing-on-desktop-pc/"><u>Expert Tips to Prevent and Solve Oddworld: Soulstorm Freezing on Desktop PC</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/guide-on-how-to-free-up-iphone-11-pro-max-space-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Free Up iPhone 11 Pro Max Space | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-the-disabled-right-click-on-your-pc-under-windows-11/"><u>How To Enable The Disabled Right Click on Your PC Under Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-unexpected-shutdowns-with-error-code-167-in-windows-systems/"><u>How to Resolve Unexpected Shutdowns with Error Code 1#67 in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-solve-the-mystery-of-missing-desktop-icons-in-your-new-windows-11/"><u>How To Solve The Mystery of Missing Desktop Icons in Your New Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208231568-hp-laptop-usb-dysfunction-heres-how-to-restore-its-functionality/"><u>HP Laptop USB Dysfunction? Here’s How to Restore Its Functionality!</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-apple-iphone-11-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Share/Fake Location on WhatsApp for Apple iPhone 11 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-mastering-borders-on-instagrams-short-films/"><u>In 2024, Mastering Borders on Instagram's Short Films</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-youtube-soundwaves-flow-into-imovie-effortlessly/"><u>In 2024, YouTube Soundwaves Flow Into iMovie Effortlessly</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/in-depth-gaomon-pd1560-tablet-analysis-unveiling-the-perfect-digital-canvas/"><u>In-Depth Gaomon PD1560 Tablet Analysis – Unveiling the Perfect Digital Canvas</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-dll-error-for-opencl-applications/"><u>Overcoming DLL Error for OpenCL Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-problems-with-windows-11-1607-feature-set-installation-errors/"><u>Overcoming Problems with Windows 11 1607 Feature Set Installation Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-guide-to-fast-league-of-legends-downloading-say-goodbye-to-delays/"><u>Quick-Fix Guide to Fast League of Legends Downloading: Say Goodbye to Delays!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-failed-to-initialize-unity-graphics-bug-quickly/"><u>Resolve 'Failed To Initialize' Unity Graphics Bug Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-sign-in-issues-fixing-user-profile-service-failures/"><u>Resolve Your Windows Sign-In Issues: Fixing User Profile Service Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-for-troubleshooting-error-0x8024401c-during-windows-updates-on-versions-1011/"><u>Step-by-Step Guide for Troubleshooting Error 0X8024401C During Windows Updates on Versions 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-installation-of-compatible-printer-drivers-on-windows-systems/"><u>Successful Installation of Compatible Printer Drivers on Windows Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-future-redefined-understanding-the-significance-of-gemini-15s-million-token-context-innovation/"><u>The Future Redefined: Understanding the Significance of Gemini 1.5'S Million Token Context Innovation</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-pelvis-is-a-common-site-for-osteolytic-lesions-because-of-its-high-red-marrow-content-and-blood-supply/"><u>The Pelvis Is a Common Site for Osteolytic Lesions because of Its High Red Marrow Content and Blood Supply.</u></a></li>
<li><a href="https://common-error.techidaily.com/top-tips-for-fixing-windows-11-stalling-issues/"><u>Top Tips for Fixing Windows 11 Stalling Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-csgo-issues-fast-fixes-for-no-more-game-crashes/"><u>Troubleshoot CSGO Issues - Fast Fixes for No More Game Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-when-file-explorer-wont-respond-in-windows-10/"><u>Troubleshooting Guide: When File Explorer Won't Respond in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-solving-windows-10-freezing-issues/"><u>Troubleshooting Tips: Solving Windows 10 Freezing Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-solving-your-windows-resource-shield-issue/"><u>Understanding and Solving Your Windows Resource Shield Issue</u></a></li>
<li><a href="https://program-issues.techidaily.com/1722996617835-utorrent-download-speed-issues-heres-how-to-get-faster-torrents/"><u>UTorrent Download Speed Issues? Here's How to Get Faster Torrents</u></a></li>
</ul></div>
