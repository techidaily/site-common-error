---
title: Diagnosing and Restarting Your Failed Diagnostics Service - Quick Fixes Applied
date: 2025-01-26T21:10:01.469Z
updated: 2025-01-29T23:44:55.876Z
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

## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLO5dwmJAVs?si=1OYH8rv8aPaMsCiU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

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
<li><a href="https://extra-guidance.techidaily.com/updated-minimizing-noise-subtle-audio-tweaks-for-pc-mac/"><u>[Updated] Minimizing Noise Subtle Audio Tweaks for PC, Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-handling-missing-d3dsvmdll-files-on-your-pc/"><u>Comprehensive Fixes: Handling Missing d3dsvm.dll Files on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-restarting-audio-services-that-arent-working-on-windows-11/"><u>Comprehensive Guide: Restarting Audio Services That Aren't Working on Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/cutting-down-on-time-spent-error-0x800736cc-in-windows-update/"><u>Cutting Down on Time Spent: Error 0X800736CC in Windows Update</u></a></li>
<li><a href="https://fox-http.techidaily.com/enhance-your-iphone-footage-from-speed-to-extended-muted-visuals/"><u>Enhance Your iPhone Footage From Speed to Extended, Muted Visuals</u></a></li>
<li><a href="https://extra-resources.techidaily.com/exclusive-vr-movie-experiences/"><u>Exclusive VR Movie Experiences</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-streamline-your-experience-with-file-explorer-on-windows-11/"><u>Expert Tips to Streamline Your Experience with File Explorer on Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/firefox-optimization-made-easy-10-steps-towards-getting-5-times-faster-surfing/"><u>Firefox Optimization Made Easy: 10 Steps Towards Getting 5 Times Faster Surfing</u></a></li>
<li><a href="https://android-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-realme-11-pro-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Realme 11 Pro FRP Locks</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/in-2024-discovering-the-power-of-asmr-for-quality-rest/"><u>In 2024, Discovering the Power of ASMR for Quality Rest</u></a></li>
<li><a href="https://common-error.techidaily.com/no-sd-card-detection-resolve-it-now/"><u>No SD Card Detection? Resolve It Now</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-fixing-the-issue-when-your-igfx-modules-fail/"><u>Solution Found! Fixing the Issue When Your iGFX Modules Fail</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-step-by-step-guide-to-repairing-error-code-0xc0000098-in-windows/"><u>Solving the Mystery: Step-by-Step Guide to Repairing Error Code 0xC0000098 in Windows</u></a></li>
<li><a href="https://win-answers.techidaily.com/step-by-step-guide-to-resolving-cyberpunk-2077-download-errors-on-steam/"><u>Step-by-Step Guide to Resolving Cyberpunk 2077 Download Errors on Steam</u></a></li>
<li><a href="https://unlock-android.techidaily.com/top-4-sim-location-trackers-to-easily-find-your-lost-oppo-find-n3-flip-device-by-drfone-android/"><u>Top 4 SIM Location Trackers To Easily Find Your Lost Oppo Find N3 Flip Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-monster-hunting-disconnections-on-pc/"><u>Troubleshooting and Fixing Monster Hunting Disconnections on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-non-responsive-google-chrome-browser/"><u>Troubleshooting Steps for Non-Responsive Google Chrome Browser</u></a></li>
<li><a href="https://techtrends.techidaily.com/unlock-endless-entertainment-without-spending-our-picks-for-free-streams-like-netflix/"><u>Unlock Endless Entertainment Without Spending: Our Picks for Free Streams Like Netflix</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-how-to-restore-brightness-slider-functionality/"><u>Windows 11: How to Restore Brightness Slider Functionality</u></a></li>
</ul></div>

