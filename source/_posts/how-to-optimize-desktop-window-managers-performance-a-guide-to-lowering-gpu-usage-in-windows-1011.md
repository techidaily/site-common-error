---
title: "How to Optimize Desktop Window Manager's Performance: A Guide to Lowering GPU Usage in Windows 10/11"
date: 2024-10-13T00:26:50.200Z
updated: 2024-10-19T01:33:52.232Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Optimize Desktop Window Manager's Performance: A Guide to Lowering GPU Usage in Windows 10/11"
excerpt: "This Article Describes How to Optimize Desktop Window Manager's Performance: A Guide to Lowering GPU Usage in Windows 10/11"
thumbnail: https://thmb.techidaily.com/150327f2d987016a4ee34ba4bcfca25233b747d0406c31e769e57594f793215f.jpg
---

## Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037351/7443" target="_top" id="2037351">
  <img src="//a.impactradius-go.com/display-ad/7443-2037351" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037351/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528696/16446" target="_top" id="1528696">
  <img src="//a.impactradius-go.com/display-ad/16446-1528696" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528696/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144280/7443" target="_top" id="2144280">
  <img src="//a.impactradius-go.com/display-ad/7443-2144280" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144280/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2139322/26400" target="_top" id="2139322">
  <img src="//a.impactradius-go.com/display-ad/26400-2139322" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2139322/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/new-harmonizing-clips-with-soundtracks-in-imovie/"><u>[New] Harmonizing Clips with Soundtracks in iMovie</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-unveiling-the-virtual-realms-of-meta-and-omni/"><u>[New] Unveiling the Virtual Realms of Meta and Omni</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-a-decade-of-digital-disguise-expert-tips-on-snapchat-filters/"><u>[Updated] In 2024, A Decade of Digital Disguise Expert Tips on Snapchat Filters</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-ultimate-gameplay-best-4k-hdmi-21-display-for-players/"><u>[Updated] Ultimate Gameplay Best 4K (HDMI 2.1) Display for Players</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-apple-iphone-15-pro-max-drfone-by-drfone-virtual-ios/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Apple iPhone 15 Pro Max | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/astro-a40-audio-problem-solved-reviving-the-built-in-microphone/"><u>Astro A40 Audio Problem Solved: Reviving the Built-In Microphone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-character-errors-in-keyboard-input-effective-techniques-and-tips/"><u>Overcoming Character Errors in Keyboard Input: Effective Techniques and Tips</u></a></li>
<li><a href="https://win-manuals.techidaily.com/quick-tips-cost-free-conversion-of-pdf-documents-into-jpeg-images/"><u>Quick Tips: Cost-Free Conversion of PDF Documents Into JPEG Images</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-vcruntime140dll-missing-file-alert-step-by-step-fix-guide/"><u>Resolve VCRUNTIME140.dll Missing File Alert - Step-by-Step Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-steps-to-successfully-complete-a-windows-10-update-hanging/"><u>Resolved! Steps to Successfully Complete a Windows 10 Update Hanging</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-abrupt-system-turnoffs-during-gaming-across-various-windows-systems-win11-win10-win7-win81-and-win8/"><u>Resolving Abrupt System Turnoffs During Gaming Across Various Windows Systems (Win11, Win10, Win7, Win8.1 & Win8)</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-huion-pen-5-rapid-fixes-for-a-smooth-drawing-experience/"><u>Reviving Your Huion Pen: 5 Rapid Fixes for a Smooth Drawing Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-fixing-off-screen-window-issues-on-your-computer-display/"><u>Solved: Fixing Off-Screen Window Issues on Your Computer Display</u></a></li>
<li><a href="https://extra-skills.techidaily.com/stay-ahead-in-the-metaverse-with-this-list-of-must-haves-for-2024/"><u>Stay Ahead in the Metaverse with This List of Must-Haves for 2024</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/this-article-focuses-on-telling-you-the-top-10-free-and-best-quicktime-mov-movie-editors-all-of-them-are-very-easy-to-use/"><u>This Article Focuses on Telling You the Top 10 FREE and Best QuickTime (MOV) Movie Editors. All of Them Are Very Easy to Use</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-is-a-sim-network-unlock-pin-get-your-samsung-galaxy-xcover-6-pro-tactical-edition-phone-network-ready-by-drfone-android/"><u>What Is a SIM Network Unlock PIN? Get Your Samsung Galaxy XCover 6 Pro Tactical Edition Phone Network-Ready</u></a></li>
</ul></div>

