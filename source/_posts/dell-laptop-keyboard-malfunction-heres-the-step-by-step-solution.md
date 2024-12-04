---
title: Dell Laptop Keyboard Malfunction? Here's the Step-by-Step Solution
date: 2024-11-28T16:51:22.841Z
updated: 2024-12-03T23:20:43.723Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Dell Laptop Keyboard Malfunction? Here's the Step-by-Step Solution
excerpt: This Article Describes Dell Laptop Keyboard Malfunction? Here's the Step-by-Step Solution
thumbnail: https://thmb.techidaily.com/f15d1bc826d6244cad0ae98fe7b4565620a90c9525864662d718cce49121a5e7.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MTb4xHzeQEk?si=9Sqq-gFWnHc8x3_P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-crafting-quieter-sounds-a-garageband-expertise/"><u>[New] 2024 Approved Crafting Quieter Sounds A Garageband Expertise</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-2024-approved-windows-10-game-recording-5-methods/"><u>[Updated] 2024 Approved Windows 10 Game Recording [5 Methods]</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-elevate-your-mobile-shoot-ranking-the-best-9-camgear-innovations/"><u>[Updated] Elevate Your Mobile Shoot - Ranking the Best 9 CamGear Innovations</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-identifying-affordable-cloud-providers-for-businesses/"><u>[Updated] Identifying Affordable Cloud Providers for Businesses</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-macsnap-gallery-builder/"><u>[Updated] MacSnap Gallery Builder</u></a></li>
<li><a href="https://video-capture.techidaily.com/bandicam-unveiled-a-comprehensive-screen-recorder-analysis-for-2024/"><u>Bandicam Unveiled A Comprehensive Screen Recorder Analysis for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/dell-laptop-keyboard-malfunction-heres-how-you-can-fix-it-quickly/"><u>Dell Laptop Keyboard Malfunction? Here's How You Can Fix It Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/disregarded-sd-card-dont-despair-solutions-await/"><u>Disregarded SD Card, Don't Despair! Solutions Await</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-overcome-and-fix-code-28-device-manager-issues-on-your-pc/"><u>Effective Techniques to Overcome and Fix Code 28 Device Manager Issues on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unresponsive-number-keys-on-your-keyboard/"><u>Fixing Unresponsive Number Keys on Your Keyboard</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/flashy-design-robust-connectivity-a-detailed-look-at-the-netgear-nighthawk-rax80-routers-wi-fi-6-capabilities/"><u>Flashy Design, Robust Connectivity: A Detailed Look at the Netgear Nighthawk RAX80 Router's Wi-Fi 6 Capabilities</u></a></li>
<li><a href="https://win-news.techidaily.com/guide-complet-comment-configurer-les-sauvegardes-automatiques-du-serveur-avec-python-en-2022-3-approches/"><u>Guide Complet: Comment Configurer Les Sauvegardes Automatiques Du Serveur Avec Python en 2022 (3 Approches)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-motorola-moto-g34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-latency-effective-ways-to-eliminate-lag-in-your-windows-10-keyboard/"><u>Overcome Latency: Effective Ways to Eliminate Lag in Your Windows 10 Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-slow-booting-in-windows-7-users/"><u>Quick Fixes for Slow Booting in Windows 7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-desktop-mouse-stops-working/"><u>Quick Fixes for When Your Desktop Mouse Stops Working</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207936743-solution-found-compatibility-issues-with-display-input-timing-fixed/"><u>Solution Found: Compatibility Issues with Display Input Timing Fixed</u></a></li>
</ul></div>

