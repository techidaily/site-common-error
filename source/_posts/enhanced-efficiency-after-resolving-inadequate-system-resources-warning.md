---
title: Enhanced Efficiency After Resolving Inadequate System Resources Warning
date: 2024-08-27T13:33:50.846Z
updated: 2024-08-28T13:33:50.846Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Enhanced Efficiency After Resolving Inadequate System Resources Warning
excerpt: This Article Describes Enhanced Efficiency After Resolving Inadequate System Resources Warning
thumbnail: https://thmb.techidaily.com/104fcc0c1e7ba0020bac11684b73c47c97661f3e4742e08d1374a286a48bed4c.jpg
---

## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4691139&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/SU-200-1.png" border="0">Software Update Pro - Check and update software installed on your computer. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
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
<li><a href="https://common-error.techidaily.com/solved-computer-shuts-down-while-gaming-windows-11-10-7-81-and-8/"><u>[Solved] Computer Shuts Down While Gaming | Windows 11, 10, 7, 8.1 & 8.</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-integral-rulebook-ensuring-harmonious-video-sharing/"><u>[Updated] 2024 Approved  Integral Rulebook  Ensuring Harmonious Video Sharing</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-cutting-edge-videographer-software-for-vimeo-expertise/"><u>[Updated] Cutting Edge Videographer Software for Vimeo Expertise</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-elite-e-learning-leader-labeler-for-2024/"><u>[Updated] Elite E-Learning Leader Labeler for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-earning-big-on-youtube-shorts-what-you-need-and-how-much-can-you-make/"><u>[Updated] In 2024, Earning Big on Youtube Shorts  What You Need & How Much Can You Make?</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-on-your-realme-11-pro-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock on your Realme 11 Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-fixing-windows-10-update-issue-with-error-0x80070541/"><u>Comprehensive Guide: Fixing Windows 10 Update Issue with Error 0X80070541</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-steps-to-fix-your-pcs-inability-to-load-operating-system-at-startup/"><u>Comprehensive Steps to Fix Your PC's Inability to Load Operating System at Startup</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-common-keyboard-mistakes-for-better-typing-accuracy/"><u>Correcting Common Keyboard Mistakes for Better Typing Accuracy</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnose-and-repair-the-problem-of-non-detectable-usb-devices-on-a-windows-11-system/"><u>Diagnose and Repair the Problem of Non-Detectable USB Devices on a Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-repairing-power-surge-warnings-in-usb-ports-while-using-windows-10/"><u>Expert Advice: Repairing 'Power Surge' Warnings in USB Ports While Using Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-the-persistent-0x80e72fed-problem-in-windows-10-systems/"><u>Expert Tips for Fixing the Persistent 0X80e72fed Problem in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-error-there-is-a-problem-with-your-games-setup-origin-games/"><u>Fix Error There Is a Problem with Your Game's Setup | Origin Games</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209195588-fixing-unending-load-screens-in-skyrim-now-solved/"><u>Fixing Unending Load Screens in Skyrim - Now Solved!</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/full-guide-to-bypass-nubia-red-magic-8s-proplus-frp-by-drfone-android/"><u>Full Guide to Bypass Nubia Red Magic 8S Pro+ FRP</u></a></li>
<li><a href="https://common-error.techidaily.com/geforce-experience-wont-launch-heres-how-you-can-get-it-working-again/"><u>GeForce Experience Won't Launch? Here’s How You Can Get It Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-repairing-windows-11-screen-brightness-command-issues/"><u>Guide: Repairing Windows 11 Screen Brightness Command Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-malfunctioning-keyboard-before-logging-into-windows/"><u>How to Fix a Malfunctioning Keyboard Before Logging Into Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-not-launching-errors-in-pubg-2024-a-step-by-step-guide/"><u>How to Resolve 'Not Launching' Errors in PUBG 2024 – A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-non-loading-structures-in-pubg-solutions-applied/"><u>How to Resolve Non-Loading Structures in PUBG - Solutions Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-invalid-directory-name-error-message/"><u>How to Resolve the 'Invalid Directory Name' Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-repair-a-pc-that-fails-to-start-correctly-now-resolved/"><u>How to Successfully Repair a PC That Fails to Start Correctly - Now Resolved!</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-samsung-galaxy-f34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to use Snapchat Location Spoofer to Protect Your Privacy On Samsung Galaxy F34 5G? | Dr.fone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/insider-tips-the-best-5-cameras-for-extended-zoom/"><u>Insider Tips  The Best 5 Cameras for Extended Zoom</u></a></li>
<li><a href="https://common-error.techidaily.com/instant-insight-into-fixing-detected-no-battery-a-step-by-step-guide/"><u>Instant Insight Into Fixing 'Detected No Battery' - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-technique-to-prevent-frequent-resets-on-your-windows-10-system/"><u>Mastering the Technique to Prevent Frequent Resets on Your Windows 10 System</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211694512-nba-2k21s-ultimate-green-glitch-now-fixed/"><u>NBA 2K21's Ultimate Green Glitch: Now Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209799322-non-specific-symptoms-like-cough-and-weight-loss-are-common-in-lung-cancer-but-not-diagnostic-on-their-own/"><u>Non-Specific Symptoms Like Cough and Weight Loss Are Common in Lung Cancer but Not Diagnostic on Their Own</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/obs-masterclass-for-successful-instagram-broadcasts/"><u>OBS Masterclass for Successful Instagram Broadcasts</u></a></li>
<li><a href="https://common-error.techidaily.com/overcame-issue-windows-cant-communicate-with-the-system-event-service-now/"><u>Overcame Issue: Windows Can't Communicate with the System Event Service Now</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-the-challenge-effective-solutions-for-error-code-0x80070643-in-windows-updateinstallation/"><u>Overcome the Challenge: Effective Solutions for Error Code 0X80070643 in Windows Update/Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-11-casting-hurdles-successful-connection-tips/"><u>Overcome Windows 11 Casting Hurdles - Successful Connection Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolve-the-persistent-windows-update-error-code-0x80070652/"><u>Quick Solutions: Resolve the Persistent Windows Update Error Code 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/reclaim-missing-touchpad-from-device-manager/"><u>Reclaim Missing Touchpad From Device Manager!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-windows-system-file-checker-sfc-failed-to-initiate-repair-process/"><u>Resolved Issue: Windows System File Checker (SFC) Failed to Initiate Repair Process</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-overcoming-hdcp-incompatibility-in-modern-video-displays/"><u>Resolved: Overcoming HDCP Incompatibility in Modern Video Displays</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-driver-failure-correcting-set-user-settings/"><u>Resolving 'Driver Failure' - Correcting Set User Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-applicationexe-failed-to-run-issue-successfully/"><u>Resolving the 'Application.exe Failed to Run' Issue Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-error-code-224403-now-your-videos-will-play-smoothly/"><u>Solving 'Error Code 224403': Now Your Videos Will Play Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-microsofts-windows-11-print-to-pdf-not-working-dilemma-tips-and-tricks/"><u>Solving Microsoft's Windows 11 Print to PDF Not Working Dilemma: Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-wdf-for-improved-processor-resource-management/"><u>Troubleshooting WDF for Improved Processor Resource Management</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-solution-resolving-the-dell-laptops-black-screen-problem-complete-tutorial/"><u>Ultimate Solution: Resolving the Dell Laptop's Black Screen Problem (Complete Tutorial)</u></a></li>
<li><a href="https://win-answers.techidaily.com/winning-over-latency-effective-solutions-for-outriders-lag-issues/"><u>Winning Over Latency: Effective Solutions for Outriders Lag Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-microsoft-wireless-display-adapter-glitches-on-windows-11/"><u>Winning the Battle Against Microsoft Wireless Display Adapter Glitches on Windows 11</u></a></li>
</ul></div>
