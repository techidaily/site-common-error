---
title: "Fixing the Issue: How to Start Your Diagnostic Policy Service When It's Stopped"
date: 2024-08-22T19:16:24.837Z
updated: 2024-08-23T19:16:24.837Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Issue: How to Start Your Diagnostic Policy Service When It's Stopped"
excerpt: "This Article Describes Fixing the Issue: How to Start Your Diagnostic Policy Service When It's Stopped"
thumbnail: https://thmb.techidaily.com/6005b95475aa59c8b39a7a2eee1863dfc772797dd0dfe7b149de977900ab8a06.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

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
<li><a href="https://facebook-video-share.techidaily.com/new-elevate-your-youtube-livestream-game-plan-for-2024/"><u>[New] Elevate Your YouTube Livestream Game Plan for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-free-online-archive-copyright-free-gaming-harmonies/"><u>[New] Free Online Archive  Copyright-Free Gaming Harmonies</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-black-screen-on-startup-in-monster-hunter-world/"><u>[Solved] Black Screen on Startup in Monster Hunter: World</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-bluetooth-not-found-in-logitech-mouse/"><u>[Solved] Bluetooth Not Found in Logitech Mouse</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-filmoras-recipe-for-captivating-youtube-trailers/"><u>2024 Approved  Filmora’s Recipe for Captivating YouTube Trailers</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-streamline-your-shots-a-windows-11-guide/"><u>2024 Approved  Streamline Your Shots  A Windows 11 Guide</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-flood-resistant-cams-reviewed-7-edition/"><u>2024 Approved  Top Flood-Resistant Cams Reviewed – #7 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-tips-for-hd-streaming-without-hdcp-supported-devices/"><u>Compatibility Tips for HD Streaming Without HDCP Supported Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-handling-parameter-misconfiguration-messages/"><u>Comprehensive Fixes for Handling Parameter Misconfiguration Messages</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-overcoming-error-87-for-successful-dll-loads/"><u>Comprehensive Guide: Overcoming Error 87 for Successful DLL Loads</u></a></li>
<li><a href="https://facebook.techidaily.com/controlling-direct-browser-within-fb-app/"><u>Controlling Direct Browser Within FB App</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/dissecting-the-emerging-trends-in-facebook-short-videos/"><u>Dissecting the Emerging Trends in Facebook Short Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/easily-fix-no-devices-detected-during-setup-in-windows-7-with-this-comprehensive-tutorial/"><u>Easily Fix 'No Devices Detected During Setup' In Windows 7 with This Comprehensive Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-resolve-usb-not-detected-issues-with-your-flash-drive/"><u>Easy Steps to Resolve 'USB Not Detected' Issues with Your Flash Drive</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-0x80072f8f-on-your-computer-heres-how-you-can-troubleshoot-windows-1110-issues-easily/"><u>Error Code 0X80072F8F on Your Computer? Here's How You Can Troubleshoot Windows 11/10 Issues Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204366949-fix-windows-11s-bluetooth-connection-problems-with-these-simple-steps/"><u>Fix Windows 11'S Bluetooth Connection Problems with These Simple Steps!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-with-computer-and-headphone-connection-problems/"><u>Fixing Issues with Computer and Headphone Connection Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-class-not-registered-error-on-your-windows-1-1-system-solutions-and-tips/"><u>Fixing the 'Class Not Registered' Error on Your Windows 1 1 System: Solutions and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-valorant-overcome-the-endless-load-screen-dilemma/"><u>Fixing Valorant: Overcome the Endless Load Screen Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-audio-issues-when-no-output-device-is-recognized/"><u>Fixing Windows 11 Audio Issues – When No Output Device Is Recognized</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-eliminate-lag-when-typing-on-a-windows-10-keyboard/"><u>How to Eliminate Lag When Typing on a Windows 10 Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-video-file-unplayable-resolve-code-224003-issue/"><u>How to Fix 'Video File Unplayable' - Resolve Code 224003 Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-typing-incorrect-characters-on-your-keyboard/"><u>How to Fix Typing Incorrect Characters on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-hosted-wi-fi-connection-problems-on-windows-11/"><u>How to Resolve Hosted Wi-Fi Connection Problems on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-overcoming-issues-with-stopped-igfx-modules/"><u>How to Restore Functionality: Overcoming Issues with Stopped iGFX Modules</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-motorola-moto-g24-phone-without-password-by-drfone-android/"><u>How To Unlock Motorola Moto G24 Phone Without Password?</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-compreenhensive-guide-to-selecting-and-cultivating-valheim-seeds/"><u>In 2024, Compreenhensive Guide to Selecting & Cultivating Valheim Seeds</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-6-best-sim-unlock-services-that-actually-work-on-your-honor-magic-v2-device-by-drfone-android/"><u>In 2024, The 6 Best SIM Unlock Services That Actually Work On Your Honor Magic V2 Device</u></a></li>
<li><a href="https://buynow-help.techidaily.com/lg-k92-5g-review-not-worth-it-just-for-5g/"><u>LG K92 5G Review: Not Worth It Just for 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/miracast-not-supported-by-graphics-driver-fixed/"><u>Miracast: Not Supported by Graphics Driver [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-device-connection-errors-in-windows-10-complete-fix/"><u>Overcoming Device Connection Errors in Windows 10 [Complete Fix]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-how-to-enable-your-devices-wireless-connectivity/"><u>Resolving Issues: How to Enable Your Device's Wireless Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-feature-level-100-issue-in-wwe-2k-battlegrounds-on-direct-x-11/"><u>Resolving the 'Feature Level 10.0' Issue in WWE 2K Battlegrounds on Direct X 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-installer-service-unavailable-error-a-comprehensive-guide/"><u>Resolving the 'Windows Installer Service Unavailable' Error - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-error-code-0xc0000098-a-step-by-step-guide/"><u>Resolving Windows Error Code 0xC0000098: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-thawing-out-your-unresponsive-pc/"><u>Simple Solutions: Thawing Out Your Unresponsive PC</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-restore-illumination-on-your-non-responsive-corsair-keyboard/"><u>Solved: How to Restore Illumination on Your Non-Responsive Corsair Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-0x80070643-error-comprehensive-guide-to-fix-windows-updates-and-installations/"><u>Solving the 0X80070643 Error: Comprehensive Guide to Fix Windows Updates and Installations</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202167542-speedy-remedies-for-out-of-memory-crashes-in-red-dead-redemption-2-adjust-and-overcome/"><u>Speedy Remedies for Out of Memory Crashes in Red Dead Redemption 2 – Adjust and Overcome</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-logitech-g930-earphones-intermittent-sound-issues/"><u>Step-by-Step Fix: Logitech G930 Earphones Intermittent Sound Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-overcoming-the-red-screen-challenge-in-windows-11/"><u>Step-by-Step Guide: Overcoming the Red Screen Challenge in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-secured-browsing-on-firefox-after-failures/"><u>Step-by-Step Guide: Restoring Secured Browsing on Firefox After Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-a-non-functional-corsair-hs50-headset-microphone/"><u>Troubleshooting Guide: Fixing a Non-Functional Corsair HS50 Headset Microphone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-how-to-fix-diagnostic-monitoring-service-wont-start/"><u>Troubleshooting Steps: How to Fix 'Diagnostic Monitoring Service Won't Start'</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-missing-cursor-anomaly-on-your-windows-11-devices-touchpad/"><u>Troubleshooting the Missing Cursor Anomaly on Your Windows 11 Device's Touchpad</u></a></li>
<li><a href="https://fox-direct.techidaily.com/understanding-the-edge-of-av1-in-video-encoding/"><u>Understanding the Edge of AV1 in Video Encoding</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-battle-with-endless-windows-updates-issue-resolved/"><u>Winning Battle with Endless Windows Updates? [ISSUE RESOLVED]</u></a></li>
</ul></div>
