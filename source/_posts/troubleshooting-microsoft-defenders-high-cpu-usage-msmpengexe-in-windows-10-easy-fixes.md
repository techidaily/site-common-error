---
title: Troubleshooting Microsoft Defender's High CPU Usage (MsMpEng.exe) in Windows 10 - Easy Fixes
date: 2024-09-11T16:01:43.501Z
updated: 2024-09-15T16:07:08.672Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Microsoft Defender's High CPU Usage (MsMpEng.exe) in Windows 10 - Easy Fixes
excerpt: This Article Describes Troubleshooting Microsoft Defender's High CPU Usage (MsMpEng.exe) in Windows 10 - Easy Fixes
thumbnail: https://thmb.techidaily.com/01214d410faf08a8a9dafcfa23316cefdeb8c6cafadbefb4d241744b10bac7c7.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2132160/7443" target="_top" id="2132160">
  <img src="//a.impactradius-go.com/display-ad/7443-2132160" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2132160/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5) Restart your computer and see if your computer runs normally now.

## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-the-essential-guide-to-making-top-tier-educational-videos/"><u>[New] 2024 Approved The Essential Guide to Making Top-Tier Educational Videos</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-masterful-fb-watching-essential-top-10-players/"><u>[New] Masterful FB Watching Essential Top 10 Players</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-refining-your-craft-making-youtube-friendly-videos-for-2024/"><u>[New] Refining Your Craft Making YouTube-Friendly Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-in-2024-cutting-edge-creativity-on-tiktok-mastering-video-designs-in-minutes/"><u>[Updated] In 2024, Cutting-Edge Creativity on TikTok Mastering Video Designs in Minutes</u></a></li>
<li><a href="https://common-error.techidaily.com/airpods-wont-pair-with-windows-heres-how-you-can-solve-it/"><u>AirPods Won't Pair with Windows? Here's How You Can Solve It</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-check-confirm-presence-of-a-d3d11-ready-graphics-card-before-launch/"><u>Compatibility Check: Confirm Presence of a D3D11 Ready Graphics Card Before Launch</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209303466-how-to-fix-windows-update-freezing-at-98-or-100-solution-now/"><u>How to Fix Windows Update Freezing at 98% or 100% - SOLUTION NOW</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-boost-cinematographic-capabilities-essential-iphone-gear/"><u>In 2024, Boost Cinematographic Capabilities Essential iPhone Gear</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-m14-5gfrp-lock-by-drfone-android/"><u>In 2024, Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy M14 5GFRP Lock</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-maximize-mp4-audio-quality-with-srt-integration-your-comprehensive-guide/"><u>In 2024, Maximize MP4 Audio Quality with SRT Integration - Your Comprehensive Guide</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-the-art-of-realignment-for-chatgpt-service-errors/"><u>Mastering the Art of Realignment for ChatGPT Service Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/radeon-management-tools-not-responding-solutions-and-tips/"><u>Radeon Management Tools Not Responding - Solutions and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-google-chromes-black-screen-dilemma-with-these-easy-fixes/"><u>Resolve Your Google Chrome's Black Screen Dilemma with These Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/revealing-the-trick-restoring-hidden-windows-from-outside-your-screen/"><u>Revealing the Trick: Restoring Hidden Windows From Outside Your Screen</u></a></li>
</ul></div>
