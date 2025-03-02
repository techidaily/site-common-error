---
title: Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved!
date: 2025-02-24T09:58:07.957Z
updated: 2025-03-02T04:25:23.972Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved!
excerpt: This Article Describes Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved!
thumbnail: https://thmb.techidaily.com/bd73d50e5d9ed4daeccbe66a94668b925bf784c3cbb50495af3357fea0a04a08.png
---

## Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

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

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

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
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-top-spots-for-virtual-reality-experiences/"><u>[Updated] 2024 Approved Top Spots for Virtual Reality Experiences</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/2024-approved-crafting-allure-in-online-visuals-for-beauty/"><u>2024 Approved Crafting Allure in Online Visuals for Beauty</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-premium-after-effects-text-enhancements/"><u>2024 Approved Premium After Effects Text Enhancements</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-the-blueprint-for-youtube-educational-video-success-stories/"><u>2024 Approved The Blueprint for YouTube Educational Video Success Stories</u></a></li>
<li><a href="https://common-error.techidaily.com/all-three-at-bedtime-to-minimize-interactions/"><u>All Three at Bedtime to Minimize Interactions</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-when-your-laptop-mousepad-wont-work-on-windows-quick-fixes-for-win-10-8-and-7/"><u>Fix Guide: When Your Laptop Mousepad Won’t Work on Windows - Quick Fixes for Win 10, 8 & 7</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-samsung-galaxy-f14-5g-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Samsung Galaxy F14 5G? | Dr.fone</u></a></li>
<li><a href="https://discover-great.techidaily.com/iphonemp3/"><u>IPhoneにおけるMP3ファイルの再生技術とトラブルシューティング</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-7-update-issues-why-updates-arent-installing-and-how-to-fix-them/"><u>Mastering Windows 7 Update Issues: Why Updates Aren't Installing and How to Fix Them</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/o-video-stream-mp3-to-youtube-in-3-easy-steps/"><u>MP3 to Video Stream MP3 to YouTube in 3 Easy Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211048300-quick-fix-guide-to-fast-league-of-legends-downloading-say-goodbye-to-delays/"><u>Quick-Fix Guide to Fast League of Legends Downloading: Say Goodbye to Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-restoring-touchpad-scroll-functionality-in-windows-10-systems/"><u>Step-by-Step Solution for Restoring Touchpad Scroll Functionality in Windows 10 Systems</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719579525638-the-power-of-croatian-revealing-the-top-7-learning-benefits-now/"><u>The Power of Croatian: Revealing the Top 7 Learning Benefits Now</u></a></li>
<li><a href="https://common-error.techidaily.com/update-brief-starcraft-ii-graphics-problem-corrected-successfully/"><u>Update Brief: StarCraft II Graphics Problem Corrected Successfully</u></a></li>
<li><a href="https://tech-revival.techidaily.com/why-switching-to-chatgpts-desktop-application-is-a-smart-choice-over-using-its-online-version/"><u>Why Switching to ChatGPT's Desktop Application Is a Smart Choice Over Using Its Online Version</u></a></li>
</ul></div>

