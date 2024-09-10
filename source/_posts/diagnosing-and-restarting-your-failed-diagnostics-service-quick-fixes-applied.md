---
title: Diagnosing and Restarting Your Failed Diagnostics Service - Quick Fixes Applied
date: 2024-09-09T08:50:22.443Z
updated: 2024-09-10T08:50:22.443Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Restarting Your Failed Diagnostics Service - Quick Fixes Applied
excerpt: This Article Describes Diagnosing and Restarting Your Failed Diagnostics Service - Quick Fixes Applied
thumbnail: https://thmb.techidaily.com/c4666c711fc9c9a338b2d08e469c371e9c8d5fe0d21f3a3c14a777e4b40a0530.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120864/26400?prodsku=Mercury" target="_top" id="2120864">
  <img src="//a.impactradius-go.com/display-ad/26400-2120864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120864/26400?prodsku=Mercury" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123481/16836" target="_top" id="2123481">
  <img src="//a.impactradius-go.com/display-ad/16836-2123481" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123481/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137209/26400" target="_top" id="2137209">
  <img src="//a.impactradius-go.com/display-ad/26400-2137209" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137209/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136620/26400" target="_top" id="2136620">
  <img src="//a.impactradius-go.com/display-ad/26400-2136620" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136620/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123748/7443" target="_top" id="2123748">
  <img src="//a.impactradius-go.com/display-ad/7443-2123748" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123748/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://common-error.techidaily.com/fixed-how-to-fix-minecraft-lagging-issue/"><u>[FIXED] How To Fix Minecraft Lagging Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/issue-resolved-steps-for-fixing-new-world-easy-anti-cheat-service-failure-to-initiate/"><u>[ISSUE RESOLVED] Steps for Fixing 'New World Easy Anti-Cheat Service Failure to Initiate'</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-bluetooth-remotes-and-controllers-for-easy-shooting-for-2024/"><u>[New] Bluetooth Remotes and Controllers for Easy Shooting for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/n-2024-first-steps-in-filmmaking-essentials-for-new-youtube-talents/"><u>[New] In 2024, First Steps in Filmmaking Essentials for New YouTube Talents</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-expedite-your-pcs-performance-get-rid-of-high-cpu-load-stuck-by-shell-infrastructures/"><u>[Solution] Expedite Your PC's Performance - Get Rid of High CPU Load Stuck by Shell Infrastructures</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-deciding-on-itop-recorder-an-indispensable-tool-in-2024/"><u>[Updated] Deciding on ITop Recorder - An Indispensable Tool, In 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-from-novice-to-expert-crafting-top-tier-reddit-posts/"><u>[Updated] From Novice to Expert Crafting Top-Tier Reddit Posts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-realms-of-play-top-10-costless-online-roleplayers-for-2024/"><u>[Updated] Realms of Play Top 10 Costless Online Roleplayers for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-dvd-dvd5/"><u>2024 年の無料 DVD 書き込み、埋め込み、DVD制作ソフトウェアベスト5ランキングをご紹介</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-master-the-art-of-superior-image-quality-enable-youtubes-av1/"><u>2024 Approved Master the Art of Superior Image Quality Enable YouTube's AV1</u></a></li>
<li><a href="https://buynow-info.techidaily.com/amazon-basics-tablet-accessory-a-game-changer-for-mobile-device-enthusiasts/"><u>Amazon Basics Tablet Accessory: A Game-Changer for Mobile Device Enthusiasts</u></a></li>
<li><a href="https://common-error.techidaily.com/best-methods-to-unfreeze-your-windows-10-desktop-bar-a-guide/"><u>Best Methods to Unfreeze Your Windows 10 Desktop Bar: A Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-error-8007000e-streamlined-strategies-to-restore-windows-updates/"><u>Bypassing Error 8007000E: Streamlined Strategies to Restore Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-restoring-damaged-registry-and-system-files-in-windows-11/"><u>Complete Guide: Restoring Damaged Registry and System Files in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209505403-destiny-2-not-working-fix-connection-errors-to-the-game-servers-here/"><u>Destiny 2 Not Working? Fix Connection Errors to the Game Servers Here</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-the-spacebar-problem-in-windows-10-computers/"><u>Diagnosing and Fixing the Spacebar Problem in Windows 10 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-a-broken-system-restore-feature-in-windows-10/"><u>Effective Fixes for a Broken System Restore Feature in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-fixes-for-when-you-cant-reach-destiny-2-servers-a-players-handbook/"><u>Essential Fixes for When You Can't Reach Destiny 2 Servers: A Player's Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-hardware-update-your-system-needs-a-d3d11-compatible-graphics-card-to-function/"><u>Essential Hardware Update: Your System Needs a D3D11-Compatible Graphics Card to Function</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-insights-into-microsoft-security-essentials-mse-tackling-high-disk-utilization-issues-with-mssecesexe/"><u>Essential Insights Into Microsoft Security Essentials (MSE): Tackling High Disk Utilization Issues with msseces.exe</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-restoring-microphone-functionality-in-laptops/"><u>Expert Advice on Restoring Microphone Functionality in Laptops</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-resolving-stuck-windows-11-update-loop/"><u>Expert Tips: Resolving Stuck Windows 11 Update Loop</u></a></li>
<li><a href="https://sound-issues.techidaily.com/firefox-no-sound-problem-heres-how-you-can-get-your-audio-back/"><u>Firefox No Sound Problem? Here’s How You Can Get Your Audio Back</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-resolving-windows-10-update-error-code-0xc1900208/"><u>Fix Guide: Resolving Windows 10 Update Error Code 0xC1900208</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-expert-tips-for-dealing-with-the-notorious-reddit-blue-screen/"><u>Fixed! Expert Tips for Dealing with the Notorious REDdit Blue Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-incompatibility-updating-your-devices-driver-for-optimal-wow-performance/"><u>Fixing Incompatibility: Updating Your Device's Driver for Optimal WoW Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-minecraft-freezing-caused-by-incompatible-windows-graphic-drivers-guide/"><u>How to Fix Minecraft Freezing Caused by Incompatible Windows Graphic Drivers (Guide)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-acer-tablet-or-laptop-if-it-wont-accept-power/"><u>How to Fix Your Acer Tablet or Laptop if It Won’t Accept Power</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/how-to-resolve-the-0x00000019-bad-pool-header-issue-in-windows-operating-systems-guides/"><u>How to Resolve the 0X00000019 Bad Pool Header Issue in Windows Operating Systems [GUIDES]</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-your-pc-with-windows-11s-system-file-checker-and-deployment-image-servicing-management/"><u>How To Restore Your PC with Windows 11'S System File Checker & Deployment Image Servicing Management</u></a></li>
<li><a href="https://hardware-help.techidaily.com/how-to-update-your-logitech-speakers-with-latest-drivers-on-windows-operating-systems-windows-1078/"><u>How to Update Your Logitech Speakers with Latest Drivers on Windows Operating Systems (Windows 10/7/8)</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-oppo-a18-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Oppo A18</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-avoiding-disclosure-in-digital-footage/"><u>In 2024, Avoiding Disclosure in Digital Footage</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-resolve-your-apple-iphone-11-pro-keeps-asking-for-outlook-password-by-drfone-ios/"><u>In 2024, Resolve Your Apple iPhone 11 Pro Keeps Asking for Outlook Password</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-essentials-for-seamless-system-evolutions/"><u>In 2024, The Essentials for Seamless System Evolutions</u></a></li>
<li><a href="https://extra-support.techidaily.com/invigorate-snaps-implement-inner-blur-spread-in-cs-for-2024/"><u>Invigorate Snaps Implement Inner Blur Spread in CS for 2024</u></a></li>
<li><a href="https://techidaily.com/is-your-oneplus-nord-ce-3-5g-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your OnePlus Nord CE 3 5G working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/lexical-migration-how-other-cultures-shape-english/"><u>Lexical Migration: How Other Cultures Shape English</u></a></li>
<li><a href="https://discover-community.techidaily.com/live-streaming-made-simple-with-manycam-advanced-virtual-camera-solution/"><u>Live Streaming Made Simple with ManyCam - Advanced Virtual Camera Solution</u></a></li>
<li><a href="https://windows11.techidaily.com/mastery-over-malfunctioning-windows-easy-fixes-at-hand/"><u>Mastery Over Malfunctioning Windows: Easy Fixes at Hand!</u></a></li>
<li><a href="https://common-error.techidaily.com/oddworld-soulstorm-for-pc-stability-hacks-and-fixes-a-comprehensive-solution/"><u>Oddworld: Soulstorm for PC Stability Hacks and Fixes – A Comprehensive Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/pam-varies-amplitude-but-not-pulse-width-or-frequency/"><u>PAM Varies Amplitude but Not Pulse Width or Frequency.</u></a></li>
<li><a href="https://common-error.techidaily.com/pdf-wont-print-discover-swift-and-easy-troubleshooting-tips/"><u>PDF Won't Print? Discover Swift and Easy Troubleshooting Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-eliminating-delays-in-keyboard-responses-for-windows-11-users/"><u>Solution Found: Eliminating Delays in Keyboard Responses for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-non-compatible-hardware-drivers-on-your-pc-a-guide-to-overcoming-wow-issues/"><u>Solution Steps for Non-Compatible Hardware Drivers on Your PC - A Guide to Overcoming WoW Issues</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solve-your-borderlands-3-stuttering-problems-expert-tips-and-tricks/"><u>Solve Your Borderlands 3 Stuttering Problems - Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-audio-output-device-missing-on-windows-11/"><u>Solving 'Audio Output Device Missing' On Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-rectify-missing-msvcp140dll/"><u>Steps to Rectify Missing MSVCP140.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-that-constant-blink-the-ultimate-solution-for-persistent-cursors/"><u>Stop That Constant Blink: The Ultimate Solution for Persistent Cursors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-keystroke-errors-and-mistyped-letters/"><u>Troubleshooting Keystroke Errors and Mistyped Letters</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-resolve-destiny-n-initializing-problems/"><u>Troubleshooting Steps To Resolve Destiny N Initializing Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-lowering-graphics-card-load-in-win11s-desktop-manager-settings/"><u>Ultimate Guide to Lowering Graphics Card Load in Win11’s Desktop Manager Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-steps-resolving-xbox-one-controller-connectivity-issues-a-complete-walkthrough/"><u>Ultimate Troubleshooting Steps: Resolving Xbox One Controller Connectivity Issues - A Complete Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-reboot-triggers-in-win10/"><u>Unexpected Reboot Triggers in Win10</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlocking-apple-iphone-14-pro-max-passcode-without-a-computer-drfone-by-drfone-ios/"><u>Unlocking Apple iPhone 14 Pro Max Passcode without a Computer | Dr.fone</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlocking-creativity-with-gpt-e-a-comprehensive-walkthrough-for-openais-interactive-environment/"><u>Unlocking Creativity with GPT-E: A Comprehensive Walkthrough for OpenAI's Interactive Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/why-cant-i-access-my-pcs-integrated-antivirus-solving-windows-smartscreen-issues/"><u>Why Can't I Access My PC's Integrated Antivirus? Solving Windows SmartScreen Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/wi-fi-connection-restored-tips-to-reestablish-your-devices-lost-wireless-functionality/"><u>Wi-Fi Connection Restored - Tips to Reestablish Your Device's Lost Wireless Functionality</u></a></li>
</ul></div>
