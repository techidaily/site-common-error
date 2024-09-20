---
title: Winning the Battle Against 'werfuel.exe' - 6 Crucial Tips for Seamless Operations on Windows
date: 2024-09-19T19:37:16.102Z
updated: 2024-09-20T18:02:05.311Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Winning the Battle Against 'werfuel.exe' - 6 Crucial Tips for Seamless Operations on Windows
excerpt: This Article Describes Winning the Battle Against 'werfuel.exe' - 6 Crucial Tips for Seamless Operations on Windows
thumbnail: https://thmb.techidaily.com/3c08a238b64ec62b2aa9f38ae909ae6c80252893c9fb975f46ca921fe1059ab2.jpg
---

## Winning the Battle Against MsMpEng.exe: Resolve Its CPU Hogging on Windows 10

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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136613/26400" target="_top" id="2136613">
  <img src="//a.impactradius-go.com/display-ad/26400-2136613" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136613/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/rofessional-thumbnail-creation-for-youtube-macos-style-for-2024/"><u>[New] Professional Thumbnail Creation for YouTube (macOS Style) for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-secrets-to-free-hd-video-grabs-from-facebook/"><u>[Updated] 2024 Approved Secrets to Free HD Video Grabs From Facebook</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-enhance-your-gaming-sims-4-on-camera-techniques/"><u>2024 Approved Enhance Your Gaming Sims 4 on Camera Techniques</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-guffaw-glory-top-downloads-of-jingles/"><u>2024 Approved Guffaw Glory Top Downloads of Jingles</u></a></li>
<li><a href="https://common-error.techidaily.com/defeating-the-ps4-error-code-ce-34878-0-with-simple-fixes/"><u>Defeating the PS4 Error Code CE-34878-0 with Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-blanked-dual-display-in-new-os-systems/"><u>Fix Blanked Dual Display in New OS Systems</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/getting-to-know-the-new-galaxy-z-fold-9th-generation-release-info-cost-analysis-and-technical-insights/"><u>Getting to Know the New Galaxy Z Fold (9Th Generation): Release Info, Cost Analysis, and Technical Insights</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/latest-nvidia-geforce-rtx-1080-driver-update-for-windows-7-systems/"><u>Latest NVIDIA GeForce RTX 1080 Driver Update for Windows 7 Systems</u></a></li>
<li><a href="https://extra-skills.techidaily.com/pioneering-prospects-cutting-edge-strategies-in-telegram-advertising-for-2024/"><u>Pioneering Prospects Cutting-Edge Strategies in Telegram Advertising for 2024</u></a></li>
<li><a href="https://data-wizards.techidaily.com/revolutionize-your-visual-media-with-grau-gmbhs-advanced-video-repair-suite-ideal-for-tech-enthusiasts/"><u>Revolutionize Your Visual Media with Grau GmbH's Advanced Video Repair Suite - Ideal for Tech Enthusiasts!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-nonfunctional-night-light-in-windows-operating-systems/"><u>Step-by-Step Fixes for Nonfunctional Night Light in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-note-detects-any-devices-via-bluetooth/"><u>Troubleshooting: Windows Note Detects Any Devices via Bluetooth</u></a></li>
</ul></div>

