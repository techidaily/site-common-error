---
title: "How to Optimize Your System: Resolving High Graphics Usage by Desktop Window Manager in Windows"
date: 2024-09-09T15:48:34.447Z
updated: 2024-09-15T12:15:58.871Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Optimize Your System: Resolving High Graphics Usage by Desktop Window Manager in Windows"
excerpt: "This Article Describes How to Optimize Your System: Resolving High Graphics Usage by Desktop Window Manager in Windows"
thumbnail: https://thmb.techidaily.com/26dcef27c207b8605e3fcf4585ee0822110eeb8a794c85ff8e27071c7786d452.jpg
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

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-pinnacle-video-devices-for-windows-11-enthusiasts/"><u>[New] 2024 Approved Pinnacle Video Devices for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-stream-smarter-with-float-mastery-over-pip-on-netflix/"><u>[New] Stream Smarter with Float Mastery Over PIP on Netflix</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/2024-approved-streamlabs-vs-obs-assessing-the-leading-livestream-tools/"><u>2024 Approved Streamlabs Vs. OBS Assessing the Leading Livestream Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-blues-handling-and-correcting-microsoft-update-error-0x8024402c-on-windows/"><u>Beat the Blues: Handling and Correcting Microsoft Update Error 0X8024402C on Windows</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-lava-blaze-pro-5g-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Lava Blaze Pro 5G Hard Reset | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-change-location-on-yik-yak-for-your-honor-x9b-to-enjoy-more-fun-drfone-by-drfone-virtual-android/"><u>In 2024, Change Location on Yik Yak For your Honor X9b to Enjoy More Fun | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-optimizing-your-xbox-experience-with-advanced-screen-capture-methods/"><u>In 2024, Optimizing Your Xbox Experience with Advanced Screen Capture Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/instantaneous-solutions-for-preventing-your-csgo-from-crashing-unexpectedly/"><u>Instantaneous Solutions for Preventing Your CSGO From Crashing Unexpectedly</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-remote-connection-fixes-overcoming-communication-barriers-with-servers/"><u>Mastering Remote Connection Fixes: Overcoming Communication Barriers with Servers</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-mac-video-editors-similar-to-vsdc-top-picks/"><u>New Mac Video Editors Similar to VSDC Top Picks</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-how-to-troubleshoot-and-repair-your-overwatch-voice-communication-problems/"><u>Quick Fixes: How to Troubleshoot and Repair Your Overwatch Voice Communication Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-0x80244022-bug-comprehensive-guide-for-fixing-windows-update-issues/"><u>Solving the 0X80244022 Bug: Comprehensive Guide for Fixing Windows Update Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubled-by-the-0x80071ac3-error-heres-how-to-fix-your-volumes-corruption-problem/"><u>Troubled by the 0X80071AC3 Error? Here's How to Fix Your Volume's Corruption Problem</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/troubleshooting-and-resolving-graphics-card-acceleration-errors-on-your-pc/"><u>Troubleshooting and Resolving Graphics Card Acceleration Errors on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-the-ce-34878-0-issue-on-your-playstation-4/"><u>Troubleshooting Guide: Resolving the CE-34878-0 Issue on Your PlayStation 4</u></a></li>
</ul></div>

