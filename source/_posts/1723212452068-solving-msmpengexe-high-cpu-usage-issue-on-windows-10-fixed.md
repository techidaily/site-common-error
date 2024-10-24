---
title: Solving MsMpEng.exe High CPU Usage Issue on Windows 10 - Fixed
date: 2024-10-23T22:23:03.665Z
updated: 2024-10-24T21:54:40.231Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving MsMpEng.exe High CPU Usage Issue on Windows 10 - Fixed
excerpt: This Article Describes Solving MsMpEng.exe High CPU Usage Issue on Windows 10 - Fixed
thumbnail: https://thmb.techidaily.com/9dc3437ed1a0c4e12ecf0fe73c74b8d72b51654a1b0d3ea6af6735c5a10c75f4.jpg
---

## Solving MsMpEng.exe High CPU Usage Issue on Windows 10 - Fixed

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044585/7443" target="_top" id="2044585">
  <img src="//a.impactradius-go.com/display-ad/7443-2044585" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044585/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135405/19272" target="_top" id="2135405">
  <img src="//a.impactradius-go.com/display-ad/19272-2135405" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135405/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144289/7443" target="_top" id="2144289">
  <img src="//a.impactradius-go.com/display-ad/7443-2144289" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144289/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-info.techidaily.com/new-2024-approved-understanding-the-essentials-of-firefox-split-screen-feature/"><u>[New] 2024 Approved Understanding the Essentials of Firefox Split Screen Feature</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-mastering-the-art-of-ifunny-memes/"><u>[New] Mastering the Art of iFunny Memes</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-top-15-royalty-free-music-hideouts-for-video-artists/"><u>[New] Top 15 Royalty-Free Music Hideouts for Video Artists</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-choose-your-perfect-wedding-tales-youtubes-finest-8/"><u>[Updated] Choose Your Perfect Wedding Tales - Youtube's Finest 8</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-macs-finest-choices-for-mkv-file-handling/"><u>2024 Approved Mac's Finest Choices for MKV File Handling</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/3-ways-for-android-pokemon-go-spoofing-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>3 Ways for Android Pokemon Go Spoofing On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/discover-the-greatest-disney-pixar-films-ever-created-a-definitive-top-10-list/"><u>Discover the Greatest Disney Pixar Films Ever Created: A Definitive Top 10 List</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-address-unregistered-class-errors-on-windows-11-systems/"><u>Effective Techniques to Address Unregistered Class Errors on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-keyboard-solutions-when-left-right-and-up-arrow-keys-fail/"><u>Fixing Your Keyboard: Solutions When Left, Right, and Up Arrow Keys Fail</u></a></li>
<li><a href="https://win-amazing.techidaily.com/get-your-windows-11107-up-and-running-realtek-sound-driver-download/"><u>Get Your Windows 11/10/7 Up and Running: Realtek Sound Driver Download</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208249116-how-to-troubleshoot-pc-game-crashes-in-nier-automata-solved/"><u>How to Troubleshoot PC Game Crashes in Nier: Automata - Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-mouse-pad-woes-fix-your-device-on-windows-10-8-and-7-here/"><u>Lenovo Mouse Pad Woes? Fix Your Device on Windows 10, 8 & 7 Here</u></a></li>
<li><a href="https://common-error.techidaily.com/managing-antivirus-impact-reducing-msmppingexes-cpu-drain-on-windows-11-fixed/"><u>Managing Antivirus Impact: Reducing msmpping.exe's CPU Drain on Windows 11 [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-system-performance-curbing-wudfhostexes-high-cpu-usage-on-windows-11/"><u>Optimizing System Performance: Curbing wudfhost.exe's High CPU Usage on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/reappearing-desktop-icons-fix-and-prevention-strategies-for-windows-11-users/"><u>Reappearing Desktop Icons: Fix and Prevention Strategies for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-driver-framework-for-reduced-processor-load/"><u>Resolving Window's Driver Framework for Reduced Processor Load</u></a></li>
<li><a href="https://win11-tips.techidaily.com/setting-your-own-windows-activity-limit/"><u>Setting Your Own Windows Activity Limit</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-fixing-windows-setup-interruption-issues-easily/"><u>Solution Found! Fixing Windows Setup Interruption Issues Easily</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-magnificent-art-of-pokemon-go-streaming-on-xiaomi-redmi-k70-drfone-by-drfone-virtual-android/"><u>The Magnificent Art of Pokemon Go Streaming On Xiaomi Redmi K70? | Dr.fone</u></a></li>
</ul></div>

