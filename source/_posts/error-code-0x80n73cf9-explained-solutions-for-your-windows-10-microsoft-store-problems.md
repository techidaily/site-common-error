---
title: "Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems"
date: 2024-08-27T13:36:13.507Z
updated: 2024-08-28T13:36:13.507Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems"
excerpt: "This Article Describes Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems"
thumbnail: https://thmb.techidaily.com/576613d76775eba96e07a16efe944a1e36820bdf585d7f2830fda9d8a084962a.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=28010250&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/336__280a.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-dos-and-donts-in-night-portraits/"><u>[New] 2024 Approved  Dos and Don'ts in Night Portraits</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-fixing-the-no-thumbnail-issue-in-youtubes-shorts-videos/"><u>[New] 2024 Approved  Fixing the No-Thumbnail Issue in YouTubes Shorts Videos</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-in-depth-exploration-of-durecorder-features/"><u>[New] 2024 Approved  In-Depth Exploration of DuRecorder Features</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-premier-filmmakers-digital-backdrop-changer/"><u>[New] In 2024, Premier Filmmaker's Digital Backdrop Changer</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-instagrams-hottest-meme-accounts-laughter-and-sorrow-sideshow/"><u>[New] Instagram's Hottest Meme Accounts  Laughter & Sorrow Sideshow</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-linux-users-guide-best-8-screenshot-apps/"><u>[Updated] 2024 Approved  Linux Users Guide  Best 8 Screenshot Apps</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-boost-your-igtv-views-top-5-tactics-for-increased-engagement/"><u>[Updated] Boost Your IGTV Views  Top 5 Tactics for Increased Engagement</u></a></li>
<li><a href="https://common-error.techidaily.com/5-effective-methods-to-repair-your-windows-10-touchscreen-a-step-by-step-guide/"><u>5 Effective Methods to Repair Your Windows 10 Touchscreen: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-the-issue-of-microsoft-telemetrys-heavy-disk-load-on-your-windows-11-system-a-step-by-step-solution/"><u>Addressing the Issue of Microsoft Telemetry's Heavy Disk Load on Your Windows 11 System: A Step-by-Step Solution</u></a></li>
<li><a href="https://fake-location.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-nokia-xr21-drfone-by-drfone-virtual-android/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Nokia XR21 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-mistyped-characters-when-using-a-keyboard/"><u>Correcting Mistyped Characters When Using a Keyboard</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-now-newly-released-all-in-one-hp-deskjet-3755-drivers-fully-supports-windows-1087-systems/"><u>Download Now: Newly Released All-In-One HP DeskJet 3755 Drivers – Fully Supports Windows 10/8/7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-repair-for-non-functioning-skype-camera-on-windows-10-devices/"><u>Effortless Repair for Non-Functioning Skype Camera on Windows 10 Devices</u></a></li>
<li><a href="https://youtube-help.techidaily.com/find-out-the-best-8-youtube-engagement-tools-for-2024/"><u>Find Out  The Best 8 Youtube Engagement Tools for 2024</u></a></li>
<li><a href="https://win-answers.techidaily.com/fixes-applied-overcoming-technical-glitches-in-modern-warfare-for-a-seamless-pc-gaming-experience/"><u>Fixes Applied: Overcoming Technical Glitches in Modern Warfare for a Seamless PC Gaming Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/get-help-with-file-explorer-in-windows-11-easily/"><u>Get Help with File Explorer in Windows 11, Easily!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-machine-that-gets-stuck-on-its-boot-interface-expert-advice/"><u>How To Fix A Machine That Gets Stuck On Its Boot Interface: Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-responsive-microphone-on-your-laptop-a-step-by-step-guide/"><u>How to Fix a Non-Responsive Microphone on Your Laptop: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-casting-issues-to-devices-from-your-windows-11-pc/"><u>How to Fix Casting Issues to Devices From Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-improve-keyboard-performance-and-reduce-delay-on-windows-10-systems/"><u>How To Improve Keyboard Performance & Reduce Delay on Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-non-functional-lenovo-function-fn-key-simple-fixes/"><u>How to Repair a Non-Functional Lenovo Function (Fn) Key - Simple Fixes</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-infinix-smart-8-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Infinix Smart 8</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-id-on-your-iphone-6s-without-security-questions-by-drfone-ios/"><u>In 2024, How to Unlock Apple ID On your iPhone 6s without Security Questions?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-iphone-x-drfone-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your iPhone X | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-youtube-banner-blueprints-a-gamers-design-handbook/"><u>In 2024, YouTube Banner Blueprints  A Gamers' Design Handbook</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/in-depth-gadget-analysis-by-toms-electronics-guide/"><u>In-Depth Gadget Analysis by Tom's Electronics Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/performance-problems-gaming-disruptions-on-os/"><u>Performance Problems: Gaming Disruptions on OS</u></a></li>
<li><a href="https://common-error.techidaily.com/persistent-mouse-disappearance-in-windows-10-how-to-resolve-it-once-and-for-all/"><u>Persistent Mouse Disappearance in Windows 10 - How to Resolve It Once and For All</u></a></li>
<li><a href="https://common-error.techidaily.com/rectify-malfunctioning-keyboard-arrow-presses-top-recommended-fixes/"><u>Rectify Malfunctioning Keyboard Arrow Presses – Top Recommended Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-widevine-content-decryption-module-out-of-date-problem-on-pc/"><u>Resolving 'Widevine Content Decryption Module' Out-of-Date Problem on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/shopping-guide-cameras-and-windows-hello/"><u>Shopping Guide: Cameras & Windows Hello</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-typing-problems-on-your-pc-windows-11-7-and-8/"><u>Solving Typing Problems on Your PC (Windows 11, 7 & 8)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-addressing-the-unknown-usb-device-and-port-reset-complications-in-your-windows-10-system/"><u>Step-by-Step Instructions: Addressing the 'Unknown USB Device' And Port Reset Complications in Your Windows 10 System</u></a></li>
<li><a href="https://common-error.techidaily.com/tango-evdo-rev-a-6-mbits-download/"><u>Tango – EVDO Rev A, 6 Mbit/S Download</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/the-ultimate-review-for-the-stylishly-engineered-samsung-galaxy-smartwatch/"><u>The Ultimate Review for the Stylishly Engineered Samsung Galaxy Smartwatch</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-replace-resolving-the-d3dx943dll-error-in-windows-easily/"><u>Troubleshoot & Replace: Resolving the d3dx9_43.dll Error in Windows Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202969172-troubleshooting-windows-amo-touchscreen-issues-top-five-solutions-you-need-to-try/"><u>Troubleshooting Windows Amo-Touchscreen Issues: Top Five Solutions You Need to Try!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/unraveling-the-mystery-a-comprehensive-guide-to-understanding-memes/"><u>Unraveling the Mystery: A Comprehensive Guide to Understanding Memes</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-unleash-creativity-top-free-video-effects-apps-for-iphone-and-android/"><u>Updated Unleash Creativity Top Free Video Effects Apps for iPhone and Android</u></a></li>
<li><a href="https://screen-capture.techidaily.com/victorious-ventures-in-the-top-12-tycoons-your-ultimate-gaming-goal-for-2024/"><u>Victorious Ventures in the Top 12 Tycoons - Your Ultimate Gaming Goal for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/why-isnt-my-razer-keyboard-lighting-up-solutions-inside/"><u>Why Isn't My Razer Keyboard Lighting Up? Solutions Inside!</u></a></li>
</ul></div>
