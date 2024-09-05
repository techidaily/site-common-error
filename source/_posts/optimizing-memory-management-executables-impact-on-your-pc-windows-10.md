---
title: Optimizing Memory Management Executable's Impact on Your PC [WINDOWS 10]
date: 2024-09-04T20:22:03.708Z
updated: 2024-09-05T20:22:03.708Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Optimizing Memory Management Executable's Impact on Your PC [WINDOWS 10]
excerpt: This Article Describes Optimizing Memory Management Executable's Impact on Your PC [WINDOWS 10]
thumbnail: https://thmb.techidaily.com/950d846f8fcee250021d944b4596b6aafb3f396fb97820df6fae0f8fc53f28aa.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030391/7443" target="_top" id="2030391">
  <img src="//a.impactradius-go.com/display-ad/7443-2030391" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030391/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094480/7443" target="_top" id="2094480">
  <img src="//a.impactradius-go.com/display-ad/7443-2094480" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094480/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896546/19272" target="_top" id="1896546">
  <img src="//a.impactradius-go.com/display-ad/19272-1896546" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896546/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-ultimate-guide-to-zoom-transcription-software-fee-based/"><u>[New] In 2024, Ultimate Guide to Zoom Transcription Software (Fee-Based)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-perfecting-cinematography-for-reddit-amas-for-2024/"><u>[New] Perfecting Cinematography for Reddit AMAs for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-navigating-netizens-youtubes-footprint-in-facebook/"><u>[Updated] 2024 Approved  Navigating Netizens  YouTube’s Footprint in Facebook</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-exclusive-android-3d-video-enthusiasts-choice/"><u>[Updated] Exclusive Android 3D Video Enthusiasts' Choice</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-inside-look-how-mycam-shapes-your-visual-storytelling-for-2024/"><u>[Updated] Inside Look  How MyCam Shapes Your Visual Storytelling for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-quietude-creation-garageband-volume-control-methods-for-2024/"><u>[Updated] Quietude Creation  Garageband Volume Control Methods for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-secrets-of-effortless-online-video-downloading-on-pinterest/"><u>[Updated] Secrets of Effortless Online Video Downloading on Pinterest</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-issue-detected-monitor-ignores-active-signal-frequency/"><u>Compatibility Issue Detected - Monitor Ignores Active Signal Frequency</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-diagnosing-and-repairing-frozen-movements-in-your-laptop-mouse/"><u>Comprehensive Guide to Diagnosing & Repairing Frozen Movements in Your Laptop Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-restoring-functionality-for-dell-laptop-input-devices/"><u>Diagnosing and Restoring Functionality for Dell Laptop Input Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-techniques-restoring-access-to-your-destiny-2-game-servers/"><u>DIY Repair Techniques: Restoring Access to Your Destiny 2 Game Servers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-function-keys-fail-to-work-properly/"><u>Effective Solutions for When Function Keys Fail to Work Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-solve-no-signal-detected-monitor-glitches/"><u>Effective Techniques to Solve 'No Signal Detected' Monitor Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-clearing-up-disk-detection-failures-during-a-windows-10-system-reset/"><u>Expert Advice: Clearing Up Disk Detection Failures During a Windows 10 System Reset</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-troubleshooting-battery-not-recognized-error-solved-effortlessly/"><u>Fast Track Troubleshooting: 'Battery Not Recognized' Error Solved Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/gameplay-might-force-a-shutdown/"><u>Gameplay Might Force a Shutdown</u></a></li>
<li><a href="https://hardware-help.techidaily.com/1722961276075-get-your-xbox-controllers-ready-fast-track-xbox-wireless-adapter-drivers/"><u>Get Your Xbox Controllers Ready - Fast-Track Xbox Wireless Adapter Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/halo-4-in-unreal-engine-4-fixing-the-persistent-crash-bug-of-2024/"><u>Halo 4 in Unreal Engine 4: Fixing the Persistent Crash Bug of 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quickly-correct-the-troublesome-windows-update-issue-error-0x80070652/"><u>How to Quickly Correct the Troublesome Windows Update Issue: Error 0X80070652</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-7-top-ways-to-resolve-apple-id-not-active-issue-for-iphone-x-drfone-by-drfone-ios/"><u>In 2024, 7 Top Ways To Resolve Apple ID Not Active Issue For iPhone X | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/innovative-qanda-strategy-for-attracting-audio-lovers-for-2024/"><u>Innovative Q&A Strategy for Attracting Audio Lovers for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-gameplay-interruptions-stop-your-pc-from-shutting-off-on-any-windows-version/"><u>Overcoming Gameplay Interruptions: Stop Your PC From Shutting Off on Any Windows Version!</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-to-restore-bluetooth-functionality-on-windows-10/"><u>Quick Guide to Restore Bluetooth Functionality on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-dead-laptop-battery-fast-and-effortlessly/"><u>Revive Your Dead Laptop Battery Fast & Effortlessly</u></a></li>
<li><a href="https://program-issues.techidaily.com/solution-steps-preventing-slime-rancher-2-from-crashing-on-windowsmac/"><u>Solution Steps: Preventing Slime Rancher 2 From Crashing on Windows/Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-no-audio-output-problem-on-your-pc-a-step-by-step-guide/"><u>Solving the 'No Audio Output' Problem on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-overcome-image-troubles-in-windows-11-and-windows-10-environments/"><u>Step-by-Step Solutions to Overcome Image Troubles in Windows 11 and Windows 10 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-a-non-functional-wacom-pen-in-windows-11-and-10/"><u>Troubleshooting Guide: Fixing a Non-Functional Wacom Pen in Windows 11 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixing-non-functional-brightness-settings-on-windows-10/"><u>Troubleshooting: Fixing Non-Functional Brightness Settings on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/unmute-netflix-effortless-fixes-to-bring-back-sound/"><u>Unmute Netflix: Effortless Fixes to Bring Back Sound</u></a></li>
</ul></div>
