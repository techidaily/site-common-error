---
title: Unreal's Future Tethered to D3D Device Availability
date: 2025-01-19T20:39:54.591Z
updated: 2025-01-22T19:27:34.047Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Unreal's Future Tethered to D3D Device Availability
excerpt: This Article Describes Unreal's Future Tethered to D3D Device Availability
thumbnail: https://thmb.techidaily.com/7a3bff4e2eede5438bb2fccedcb9095f7ad51baa5a8f2d8fdc6330db34850673.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8U3ooyFiAB4?si=yXPQrDhMBEJwN2EZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3C51hzX46eY?si=o5qiDSkT7mXUGm3F" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-scrutinized-screen-recording-tools-top-8-picks/"><u>[New] In 2024, Scrutinized Screen Recording Tools Top 8 Picks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-achieve-visual-harmony-optimal-sizing-for-instagram-videos/"><u>[Updated] 2024 Approved Achieve Visual Harmony Optimal Sizing for Instagram Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-how-to-use-gopro-for-time-lapse-shooting/"><u>[Updated] How to Use GoPro for Time-Lapse Shooting</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-compendium-of-camera-types-for-professional-videos/"><u>2024 Approved Compendium of Camera Types for Professional Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/breaking-through-barriers-wow-unlocks-3d-acceleration/"><u>Breaking Through Barriers: WoW Unlocks 3D Acceleration</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208987911-dell-laptop-usb-woes-heres-how-you-can-get-your-ports-working-again/"><u>Dell Laptop USB Woes? Here's How You Can Get Your Ports Working Again</u></a></li>
<li><a href="https://win-able.techidaily.com/effortless-audio-removal-for-windows-11-users-a-comprehensive-guide-with-bulk-file-support/"><u>Effortless Audio Removal for Windows 11 Users: A Comprehensive Guide with Bulk File Support</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-cannot-perform-a-dual-role-issues-due-to-limited-system-capacity/"><u>Fixing 'Cannot Perform a Dual Role' Issues Due to Limited System Capacity</u></a></li>
<li><a href="https://common-error.techidaily.com/function-key-issues-solved-how-to-restore-button-responsiveness/"><u>Function Key Issues Solved: How to Restore Button Responsiveness</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-nokia-g310-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Nokia G310? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-swiftly-resolve-a-broken-logiteche-keyboard-problem/"><u>How to Swiftly Resolve a Broken Logiteche Keyboard Problem</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/is-the-performance-boost-worth-it-with-a-new-rtx-gpu/"><u>Is the Performance Boost Worth It with a New RTX GPU?</u></a></li>
<li><a href="https://common-error.techidaily.com/navigate-and-fix-common-issues-in-windows-11-file-explorer-quickly/"><u>Navigate and Fix Common Issues in Windows 11 File Explorer Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-network-hurdles-correcting-ethernet-problems-under-windows-10-and-7/"><u>Overcoming Network Hurdles: Correcting Ethernet Problems Under Windows 10 & 7</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/screensnapper-prox-the-premier-pc-screen-recorder-by-apowersoft-for-2024/"><u>ScreenSnapper ProX The Premier PC Screen Recorder by Apowersoft for 2024</u></a></li>
<li><a href="https://buynow-help.techidaily.com/smart-photo-editor-review-for-windows-and-mac/"><u>Smart Photo Editor Review for Windows and Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-d3derr-not-available-error-comprehensive-guide/"><u>Solving the D3DERR Not Available Error: Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-port-reset-error-a-step-by-step-guide-to-troubleshoot-your-usb-devices-on-windows-10/"><u>Solving the Port Reset Error: A Step-by-Step Guide to Troubleshoot Your USB Devices on Windows 10</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-get-retro-with-fcp-simple-vhs-effect-techniques-for-2024/"><u>Updated Get Retro with FCP Simple VHS Effect Techniques for 2024</u></a></li>
</ul></div>

