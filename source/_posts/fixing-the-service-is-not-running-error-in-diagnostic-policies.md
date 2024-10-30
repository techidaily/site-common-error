---
title: Fixing the 'Service Is Not Running' Error in Diagnostic Policies
date: 2024-10-29T17:04:51.242Z
updated: 2024-10-30T16:41:21.505Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing the 'Service Is Not Running' Error in Diagnostic Policies
excerpt: This Article Describes Fixing the 'Service Is Not Running' Error in Diagnostic Policies
thumbnail: https://thmb.techidaily.com/b0e0b3709f1348652118c2459af9389796059e0f6579c4e1ae20b05da950739b.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144271/7443" target="_top" id="2144271">
  <img src="//a.impactradius-go.com/display-ad/7443-2144271" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144271/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094479/7443" target="_top" id="2094479">
  <img src="//a.impactradius-go.com/display-ad/7443-2094479" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094479/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-craft-standout-videos-with-professional-free-banner-samples/"><u>[New] In 2024, Craft Standout Videos with Professional, Free Banner Samples</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-2024-approved-visionary-screen-supercharging-ultimate-hd-transformation/"><u>[Updated] 2024 Approved Visionary Screen Supercharging Ultimate HD Transformation</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-quick-correction-quest-how-to-skillfully-edit-images-on-win10/"><u>2024 Approved Quick Correction Quest How to Skillfully Edit Images on WIN10</u></a></li>
<li><a href="https://common-error.techidaily.com/conquer-your-windows-woes-unsticking-updates-stalled-at-completion-mark/"><u>Conquer Your Windows Woes: Unsticking Updates Stalled at Completion Mark</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-device-not-working-error-when-casting-on-windows-11/"><u>Diagnosing and Repairing 'Device Not Working' Error When Casting on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-what-to-do-if-your-pc-freezes-on-windows-10/"><u>Effective Solutions: What to Do if Your PC Freezes on Windows 10</u></a></li>
<li><a href="https://program-issues.techidaily.com/effortless-fixes-to-overcome-wwe-2k20s-pc-crashing-problems/"><u>Effortless Fixes to Overcome WWE 2K20's PC Crashing Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-videos-from-your-honor-magic-6-pro-by-fonelab-android-recover-video/"><u>How to recover old videos from your Honor Magic 6 Pro</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-motorola-moto-e13-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Motorola Moto E13? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-art-of-enhanced-visual-interaction-in-microsoft-teams/"><u>In 2024, The Art of Enhanced Visual Interaction in Microsoft Teams</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/maximizing-impact-with-instagrams-top-marketing-tactics-for-2024/"><u>Maximizing Impact with Instagram's Top Marketing Tactics for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-windows-grope-to-combat-excessive-resource-use-by-microsoft-compatibility-telemetry/"><u>Optimizing Windows Grope to Combat Excessive Resource Use by Microsoft Compatibility Telemetry</u></a></li>
<li><a href="https://win-blog.techidaily.com/smooth-sailing-through-appalachia-eradicating-stutter-frames-in-fallout-76/"><u>Smooth Sailing Through Appalachia: Eradicating Stutter Frames in Fallout 76</u></a></li>
<li><a href="https://facebook.techidaily.com/the-mystery-behind-excluded-social-media-content/"><u>The Mystery Behind Excluded Social Media Content</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-audio-issues-resolving-audio-output-device-not-installed-on-windows-11/"><u>Troubleshooting Audio Issues: Resolving 'Audio Output Device Not Installed' On Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-ethernet-connection-problems-in-windows-10-and-windows-7/"><u>Troubleshooting Steps: Resolving Ethernet Connection Problems in Windows 10 and Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-steam-shop-when-it-wont-load-anymore-top-solutions/"><u>Troubleshooting Your Steam Shop When It Won't Load Anymore: Top Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-resolving-write-protection-issues-with-usbs-sd-cards-and-cd-discs-in-windows/"><u>Troubleshooting: Resolving Write Protection Issues with USBs, SD Cards, and CD Discs in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-miracast-functionality-correct-graphics-drivers-make-a-world-of-difference/"><u>Unlocking Miracast Functionality: Correct Graphics Drivers Make a World of Difference</u></a></li>
</ul></div>

