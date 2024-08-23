---
title: "Overcoming the Difficulties of the 0X80072EFD Error: A Comprehensive Fix for Windows 10 Users"
date: 2024-08-22T19:15:53.882Z
updated: 2024-08-23T19:15:53.882Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming the Difficulties of the 0X80072EFD Error: A Comprehensive Fix for Windows 10 Users"
excerpt: "This Article Describes Overcoming the Difficulties of the 0X80072EFD Error: A Comprehensive Fix for Windows 10 Users"
thumbnail: https://thmb.techidaily.com/c74a6f4cbc3131991d1108cc0cd3851c9f4624d9f7132bc54e3318b3d6ad9b70.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-office-pdf-editor-1x.890dbda.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002162&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/1_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (1 PC) Free upgrade. No monthly fees ever. 
</a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-navigating-social-media-comparing-igtv-and-youtube-features/"><u>[New] 2024 Approved  Navigating Social Media  Comparing IGTV and YouTube Features</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-channel-branding-made-simple-and-free-for-2024/"><u>[New] Channel Branding Made Simple & Free for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-transform-subtitles-quickly-best-8-converters-from-sub-to-streamlined-srtr/"><u>[New] In 2024, Transform Subtitles Quickly! Best 8 Converters From SUB to Streamlined SRTR</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-troubleshooting-missing-video-display-on-sony-a6400/"><u>[New] Troubleshooting Missing Video Display on Sony A6400</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-prepare-your-fb-content-hv-orientation-matters-for-2024/"><u>[Updated] How to Prepare Your FB Content  H/V Orientation Matters for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-channel-design-mastery-selecting-the-right-yt-banner-and-art-sizes/"><u>[Updated] In 2024, Channel Design Mastery  Selecting the Right YT Banner & Art Sizes</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-embrace-artistic-expression-incorporating-anime-into-snapchat/"><u>[Updated] In 2024, Embrace Artistic Expression  Incorporating Anime Into Snapchat</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-the-art-of-balancing-video-quality-and-adsense-revenue/"><u>2024 Approved  The Art of Balancing Video Quality & AdSense Revenue</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-filmography-mastering-cinematic-shots-and-lighting/"><u>2024 Filmography  Mastering Cinematic Shots and Lighting</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/best-oppo-a58-4g-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Oppo A58 4G Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://extra-hints.techidaily.com/cloud-marketplace-dissecting-cost-structures-for-2024/"><u>Cloud Marketplace  Dissecting Cost Structures for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-fix-the-windows-update-failed-with-code-0x8024002e/"><u>Effective Solutions to Fix the 'Windows Update Failed with Code 0X8024002E'</u></a></li>
<li><a href="https://extra-information.techidaily.com/elite-androidiphone-slow-speed-capture-applications-reviews/"><u>Elite Android/iPhone Slow-Speed Capture Applications, Reviews</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1603-deciphered-a-step-by-step-guide-to-solving-fatal-setup-issues/"><u>Error 1603 Deciphered: A Step-by-Step Guide to Solving Fatal Setup Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-lack-of-sound-devices-message-on-windows-10-and-11-systems/"><u>Fixing Lack of Sound Devices Message on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-oculus-hardware-problems-expert-tips/"><u>Fixing Your Oculus Hardware Problems - Expert Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/from-broken-to-secure-fixing-problematic-windows-update-processes/"><u>From Broken to Secure: Fixing Problematic Windows Update Processes</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-lenovo-mouse-pad-working-again-on-any-version-of-windows-comprehensive-fixes/"><u>Get Your Lenovo Mouse Pad Working Again on Any Version of Windows - Comprehensive Fixes!</u></a></li>
<li><a href="https://windows11.techidaily.com/guide-to-silencing-game-recommendations-on-w11/"><u>Guide to Silencing Game Recommendations on W11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-disk-check-stuck-situations-in-your-windows-10-device-effortlessly/"><u>How to Overcome Disk Check Stuck Situations in Your Windows 10 Device Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-common-netflix-connectivity-problems-when-things-dont-work/"><u>How to Resolve Common Netflix Connectivity Problems When Things Don't Work</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-undetected-bluetooth-gadgets-in-windows-10/"><u>How to Resolve Undetected Bluetooth Gadgets in Windows 10</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-learn-how-everything-works-on-honor-magic5-ultimate-drfone-by-drfone-virtual-android/"><u>Life360 Learn How Everything Works On Honor Magic5 Ultimate | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/obs-game-streaming-flawlessness-solving-the-elusive-black-screen-hurdle/"><u>OBS Game Streaming Flawlessness: Solving the Elusive Black Screen Hurdle</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-windows-could-not-install-in-minutes-with-these-tips/"><u>Resolve 'Windows Could Not Install' In Minutes with These Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-disappeared-desktop-icon-issues-in-windows-10-made-easy/"><u>Restoring Disappeared Desktop Icon Issues in Windows 10 Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/secure-guide-acquiring-permissions-from-trustedinstaller-for-file-modification-tasks/"><u>Secure Guide: Acquiring Permissions From TrustedInstaller for File Modification Tasks</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-of-inaccessible-windows-security-feature-smartscreen-troubleshoot-tips/"><u>Solving the Issue of Inaccessible Windows Security Feature – SmartScreen Troubleshoot Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-windows-entry-point-missing-error-fix/"><u>Step-by-Step Solution for Windows 'Entry Point Missing' Error Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-the-windows-ebx-11-copy-p-paste-problem/"><u>Step-by-Step Solutions for the Windows Ebx 11 Copy-P Paste Problem</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-realme-11-pro-device-by-drfone-android/"><u>The Ultimate Guide How to Bypass Swipe Screen to Unlock on Realme 11 Pro Device</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-motorola-moto-g13-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Motorola Moto G13 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-lenovo-mouse-pad-in-windows-operating-systems/"><u>Troubleshooting Non-Responsive Lenovo Mouse Pad in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-success-quick-solution-for-error-1053-when-service-fails-to-react-timely/"><u>Troubleshooting Success: Quick Solution for Error 1053 When Service Fails to React Timely</u></a></li>
<li><a href="https://win-howtos.techidaily.com/ultimate-guide-troubleshooting-steps-when-your-pc-wont-respond/"><u>Ultimate Guide: Troubleshooting Steps When Your PC Won't Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-for-valorant-how-to-stop-screen-tearing-once-and-for-all/"><u>Ultimate Troubleshooting for Valorant: How To Stop Screen Tearing Once and For All</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-do-when-laptopdesktop-wont-turn-on-essential-fixes/"><u>What to Do When Laptop/Desktop Won't Turn On - Essential Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-reboots-without-warning/"><u>Windows Reboots without Warning</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-strategies-to-overcome-continuous-windows-10-startup-issues/"><u>Winning Strategies to Overcome Continuous Windows 10 Startup Issues</u></a></li>
</ul></div>
