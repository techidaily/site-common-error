---
title: Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10
date: 2024-08-15T11:08:56.205Z
updated: 2024-08-16T11:08:56.205Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10
excerpt: This Article Describes Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10
thumbnail: https://thmb.techidaily.com/e4e90e7c9acadc523d8e4202425b18a9d8056d3f1cd618361a73d2cd13f94e4f.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4610657&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2024/06/emeditor_chat_ai.png" border="0">
EmEditor is a fast, lightweight, yet extensible, easy-to-use text editor, code editor, CSV editor, and large file viewer for Windows. Both native 64-bit and 32-bit builds are available, and moreover, the 64-bit includes separate builds for SSE2 (128-bit), AVX-2 (256-bit), and AVX-512 (512-bit) instruction sets. New versions support AI-assisted writing.</a>
<!-- affiliate ads end -->
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872496/14483" target="_top" id="1872496"><img src="//a.impactradius-go.com/display-ad/14483-1872496" border="0" alt="" width="750" height="625"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872496/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=22889392&QTY=1&AFFILIATE=108875&CART=1"><img src="http://webstatic.nero.com/nero2015-com-wAssets/img/affiliate/media/banner728-90eng.jpg" border="0"></a>
<!-- affiliate ads end -->
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068416/7443" target="_top" id="2068416"><img src="//a.impactradius-go.com/display-ad/7443-2068416" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068416/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-videos.techidaily.com/new-fb-a-resource-for-video-discovery-enthusiasts/"><u>[New] FB   A Resource for Video Discovery Enthusiasts</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-how-to-watch-twitter-videos-in-full-hd/"><u>[New] How To Watch Twitter Videos in Full HD?</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-fusing-data-and-design-for-dynamic-fb-video-campaigns/"><u>[New] In 2024, Fusing Data & Design for Dynamic FB Video Campaigns</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-keep-your-content-safe-guidelines-for-clearance-of-tiktok-videos/"><u>[New] In 2024, Keep Your Content Safe  Guidelines for Clearance of TikTok Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-overcoming-missed-frames-in-real-time-streaming/"><u>[New] Overcoming Missed Frames in Real-Time Streaming</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-art-of-profit-from-20-second-videography-a-guide-for-creators/"><u>[New] The Art of Profit From 20-Second Videography  A Guide for Creators</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-10-wont-boot-after-update/"><u>[Solved] Windows 10 Won't Boot After Update</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-video-sharing-warriors-which-fights-better-obs-or-twitch-studio/"><u>[Updated] 2024 Approved  Video Sharing Warriors  Which Fights Better - OBS or Twitch Studio?</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-divide-and-conquer-adding-chapters-to-vimeo/"><u>[Updated] Divide and Conquer  Adding Chapters to Vimeo</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-counteract-fake-views-boosting-genuine-audience-size/"><u>[Updated] In 2024, Counteract Fake Views  Boosting Genuine Audience Size</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-from-playtime-to-prestige-capturing-sims-mastery/"><u>[Updated] In 2024, From Playtime to Prestige  Capturing Sims Mastery</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-advances-in-photography-with-lut-technology/"><u>2024 Approved  Advances in Photography with LUT Technology</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-bold-broadcasters-on-a-budget-youtube-live-not-1000plus-supporters/"><u>2024 Approved  Bold Broadcasters on a Budget  YouTube LIVE, Not 1000+ Supporters</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-ultimate-blueprint-for-srt-file-excellence/"><u>2024 Approved  The Ultimate Blueprint for SRT File Excellence</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-understanding-why-your-camera-stops-in-the-mid-action/"><u>2024 Approved  Understanding Why Your Camera Stops in the Mid-Action</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/4-ways-to-transfer-messages-from-apple-iphone-xs-max-to-iphone-including-iphone-15-drfone-by-drfone-transfer-from-ios/"><u>4 Ways to Transfer Messages from Apple iPhone XS Max to iPhone Including iPhone 15 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-darkness-expert-tips-for-solving-obs-game-capturing-issues/"><u>Beat the Darkness: Expert Tips for Solving OBS Game Capturing Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/beating-destiny-2s-loading-hurdle-fixing-initialization-errors-effectively/"><u>Beating Destiny 2'S Loading Hurdle - Fixing Initialization Errors Effectively</u></a></li>
<li><a href="https://activate-lock.techidaily.com/best-ways-to-bypass-icloud-activation-lock-on-apple-iphone-12-proipadipod-by-drfone-ios/"><u>Best Ways to Bypass iCloud Activation Lock on Apple iPhone 12 Pro/iPad/iPod</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205038782-breeze-through-windows-11s-persistent-restart-issue-easy-solutions-inside/"><u>Breeze Through Windows 11'S Persistent Restart Issue - Easy Solutions Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/call-of-duty-ww2-bug-code-easy-troubleshooting-steps-to-correct-errors/"><u>Call of Duty WW2 Bug Code 지표: Easy Troubleshooting Steps to Correct Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-correcting-power-management-problems-with-windows-drivers/"><u>Diagnosing and Correcting Power Management Problems with Windows Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-solutions-eradicating-the-windows-error-code-entry-point-not-present/"><u>DIY Solutions: Eradicating the Windows Error Code - Entry Point Not Present</u></a></li>
<li><a href="https://win-amazing.techidaily.com/easy-fix-fresh-installation-of-intel-optane-driver-for-enhanced-performance-on-windows-pcs/"><u>Easy Fix: Fresh Installation of Intel Optane Driver for Enhanced Performance on Windows PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-and-tips-for-resolving-the-ce-34878-code-on-your-ps4-console/"><u>Effective Fixes and Tips for Resolving the 'CE-34878' Code on Your PS4 Console</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/effortless-melodies-free-facebook-download/"><u>Effortless Melodies  Free Facebook Download</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-correcting-system-critical-process-failed-error-on-your-pc-0xc00000e9-explained/"><u>Expert Advice: Correcting System Critical Process Failed Error on Your PC (0XC00000E9 Explained)</u></a></li>
<li><a href="https://common-error.techidaily.com/feature-update-to-windows-10-version-1803-failed-solved/"><u>Feature Update to Windows 10 Version 1803 Failed [SOLVED]</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/how-to-effortlessly-record-screens-on-your-hp-device/"><u>How to Effortlessly Record Screens on Your HP Device</u></a></li>
<li><a href="https://driver-download.techidaily.com/how-to-install-asus-mousepad-software-on-your-windows-pc/"><u>How to Install ASUS Mousepad Software on Your Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-critical-imaging-errors-in-your-windows-11-or-10-pc/"><u>How to Overcome Critical Imaging Errors in Your Windows 11 or 10 PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-poco-c55-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Poco C55? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/hp-laptop-keyboard-malfunction-heres-how-to-fix-it-quickly/"><u>HP Laptop Keyboard Malfunction? Here's How to Fix It Quickly</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-apex-artists-youtubes-most-followed-sages/"><u>In 2024, Apex Artists  YouTube's Most-Followed Sages</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-zte-nubia-flip-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, ZTE Nubia Flip 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-pc-restart-overcoming-trouble-with-windows-10-power-down/"><u>Mastering PC Restart: Overcoming Trouble with Windows 10 Power Down</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mind-your-words-with-ai-keep-secrets-safe/"><u>Mind Your Words with AI; Keep Secrets Safe</u></a></li>
<li><a href="https://common-error.techidaily.com/noise-troubleshooting-a-comprehensive-guide-to-fixing-forza-horizon-4s-muted-gameplay/"><u>Noise Troubleshooting: A Comprehensive Guide to Fixing Forza Horizon 4'S Muted Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-class-unregistered-on-windows-11-error-tips-and-tricks-inside/"><u>Overcoming 'Class Unregistered on Windows 11' Error – Tips & Tricks Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-mouse-right-click-challenges-in-windows-11-with-easy-fixes/"><u>Overcoming Mouse Right Click Challenges in Windows 11 with Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/printer-driver-was-not-installed-access-is-denied/"><u>Printer Driver Was Not Installed: Access Is Denied</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-taskbar-delays-effective-solutions/"><u>Resolving Windows 10 Taskbar Delays: Effective Solutions</u></a></li>
<li><a href="https://media-tips.techidaily.com/selecting-the-top-wtv-to-mp4-converter-software-compatible-with-windows-operating-systems-7-8-10/"><u>Selecting the Top WTV to MP4 Converter Software Compatible with Windows Operating Systems (7, 8, 10)</u></a></li>
<li><a href="https://common-error.techidaily.com/shift-key-failure-solved-tips-for-restoring-functionality/"><u>Shift Key Failure Solved: Tips for Restoring Functionality</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/smooth-playing-on-advanced-rtx-setup/"><u>Smooth Playing on Advanced RTX Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-the-media-unresponsive-problem-in-windows-a-step-by-step-guide/"><u>Solve the 'Media Unresponsive' Problem in Windows - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/steam-game-installation-woes-fixing-disk-write-problems-made-simple/"><u>Steam Game Installation Woes? Fixing Disk Write Problems Made Simple</u></a></li>
<li><a href="https://common-error.techidaily.com/system-downfall-critical-error-detected/"><u>System Downfall: Critical Error Detected</u></a></li>
<li><a href="https://common-error.techidaily.com/system-seizure-irreparable-device-error/"><u>System Seizure: Irreparable Device Error</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-opencl-library-file-errors/"><u>Tackling OpenCL Library File Errors</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-interactive-sphere-instagram-tiktok-synergy-guide-for-2024/"><u>The Interactive Sphere  Instagram-TikTok Synergy Guide for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-ultimate-guide-to-leveraging-openais-powerful-api-for-cutting-edge-applications/"><u>The Ultimate Guide to Leveraging OpenAI's Powerful API for Cutting-Edge Applications</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-motorola-edge-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-gpu-consumption-by-the-desktop-window-manager-on-windows-10-and-11/"><u>Top 5 Solutions for Reducing GPU Consumption by the Desktop Window Manager on Windows 10 & 11</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-7-phone-number-locators-to-track-vivo-y100i-power-5g-location-drfone-by-drfone-virtual-android/"><u>Top 7 Phone Number Locators To Track Vivo Y100i Power 5G Location | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-tricks-for-resolving-issues-with-your-playstation-4-headset-audio/"><u>Top Tricks for Resolving Issues with Your PlayStation 4 Headset Audio</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-bluetooth-devices-that-appear-paired-but-remain-unconnected-in-windows-10/"><u>Troubleshooting Bluetooth Devices That Appear Paired But Remain Unconnected in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-code-0x80-windows-1110-expert-tips-and-solutions/"><u>Troubleshooting Error Code 0X80^ (Windows 11/10): Expert Tips & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-reactivating-your-windows-update-functionality-efficiently/"><u>Troubleshooting Tips: Reactivating Your Windows Update Functionality Efficiently</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-advanced-audio-editing-in-adobe-premiere-pro-effortless-track-mixing-methods/"><u>Updated Advanced Audio Editing in Adobe Premiere Pro Effortless Track Mixing Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/why-arent-the-function-keys-responding-solving-problems-with-your-asus-laptop/"><u>Why Aren't the Function Keys Responding? Solving Problems with Your Asus Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/why-your-shift-key-wont-work-and-how-to-solve-it-effectively/"><u>Why Your Shift Key Won't Work and How to Solve It Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-setup-fails-overcome-error-code-80240020-for-successful-installation/"><u>Windows 10 Setup Fails: Overcome Error Code 80240020 for Successful Installation</u></a></li>
</ul></div>
