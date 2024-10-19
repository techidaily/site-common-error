---
title: "Resolving High CPU Usage by the Windows Sound Isolation Feature: Easy Solutions"
date: 2024-10-16T02:03:18.992Z
updated: 2024-10-18T22:27:44.088Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving High CPU Usage by the Windows Sound Isolation Feature: Easy Solutions"
excerpt: "This Article Describes Resolving High CPU Usage by the Windows Sound Isolation Feature: Easy Solutions"
thumbnail: https://thmb.techidaily.com/ea52c7c75e7b3032041ebf8f7a073a81be868964630fead8d644714b724c8d98.jpg
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528685/16446" target="_top" id="1528685">
  <img src="//a.impactradius-go.com/display-ad/16446-1528685" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528685/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411">
  <img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134236/18498" target="_top" id="2134236">
  <img src="//a.impactradius-go.com/display-ad/18498-2134236" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134236/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115951/19272" target="_top" id="2115951">
  <img src="//a.impactradius-go.com/display-ad/19272-2115951" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115951/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137228/26400" target="_top" id="2137228">
  <img src="//a.impactradius-go.com/display-ad/26400-2137228" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137228/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-essential-guide-broadcast-360-videos-on-facebook/"><u>[New] In 2024, Essential Guide Broadcast 360 Videos on Facebook</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-the-definitive-io-screen-recorder-guidebook/"><u>[New] In 2024, The Definitive IO Screen Recorder Guidebook</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-the-ultimate-playbook-for-splitting-views-in-facebook-livestreams/"><u>[New] The Ultimate Playbook for Splitting Views in Facebook Livestreams</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-strategizing-an-attention-grabbing-tiktok-signoff/"><u>[Updated] Strategizing an Attention-Grabbing TikTok Signoff</u></a></li>
<li><a href="https://fox-ssl.techidaily.com/easy-guide-to-saving-movies-and-shows-from-atresplayer-for-windows-and-macos-users/"><u>Easy Guide to Saving Movies and Shows From Atresplayer for Windows & macOS Users</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-ethernet-functionality-in-windows-11-and-7-systems/"><u>Expert Tips for Restoring Ethernet Functionality in Windows 11 and 7 Systems</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-the-fundamentals-of-transfer-learning-in-ai-systems/"><u>Exploring the Fundamentals of Transfer Learning in AI Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-api-error-core-dll-missing-on-pc/"><u>Fixing API Error: Core DLL Missing on PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-it-nokia-g22-wont-turn-on-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix It Nokia G22 Wont Turn On | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-pixel-7a-by-fonelab-android-recover-music/"><u>How to recover old music from your Pixel 7a</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-tips-of-transferring-messages-from-poco-x6-to-iphone-1415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Tips of Transferring Messages from Poco X6 to iPhone 14/15 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/optimize-system-performance-addressing-msmpengine-high-cpu-drainage-in-windows-11-easily/"><u>Optimize System Performance: Addressing MsMpEngine High CPU Drainage in Windows 11 Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-initializing-a-hosted-network-in-windows-10/"><u>Overcoming Issues with Initializing a Hosted Network in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-11-touchpad-problems-expert-advice-on-fixing-scroll-shortcuts/"><u>Overcoming Windows 11 Touchpad Problems: Expert Advice on Fixing Scroll Shortcuts</u></a></li>
<li><a href="https://common-error.techidaily.com/preventing-unwanted-win11-restarts/"><u>Preventing Unwanted Win11 Restarts</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-your-lenovo-fingerprint-reader-easy-fixes-inside/"><u>Resolving Issues with Your Lenovo Fingerprint Reader: Easy Fixes Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-of-steam-updates-failing-to-download/"><u>Solving the Dilemma of Steam Updates Failing to Download</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206375056-troubleshoot-and-correct-system-error-0x887a0006-a-step-by-step-guide-to-a-swift-solution/"><u>Troubleshoot and Correct System Error 0X887A0006: A Step-by-Step Guide to a Swift Solution</u></a></li>
<li><a href="https://os-tips.techidaily.com/unlocking-hidden-messages-a-guide-to-viewing-blocked-incoming-calls-on-your-iphone/"><u>Unlocking Hidden Messages: A Guide to Viewing Blocked Incoming Calls on Your iPhone</u></a></li>
</ul></div>

