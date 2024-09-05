---
title: "Battle the High Resource Hog svchost.exe: Strategies to Optimize Windows 11 Performance"
date: 2024-09-04T20:22:04.269Z
updated: 2024-09-05T20:22:04.269Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Battle the High Resource Hog svchost.exe: Strategies to Optimize Windows 11 Performance"
excerpt: "This Article Describes Battle the High Resource Hog svchost.exe: Strategies to Optimize Windows 11 Performance"
thumbnail: https://thmb.techidaily.com/c3feb7e5b167df5f057578cdbf724989b5f25148052cd8949359804b1109e7ca.png
---

## Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside

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
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826">
  <img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082539/7443" target="_top" id="2082539">
  <img src="//a.impactradius-go.com/display-ad/7443-2082539" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082539/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044586/7443" target="_top" id="2044586">
  <img src="//a.impactradius-go.com/display-ad/7443-2044586" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044586/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027195/19272" target="_top" id="2027195">
  <img src="//a.impactradius-go.com/display-ad/19272-2027195" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027195/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1977023">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977023.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977023">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977023.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977023%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977023/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-integrating-social-video-platforms-with-hdtv/"><u>[New] In 2024, Integrating Social Video Platforms with HDTV</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-easy-ios-screen-recording-tips-and-tricks/"><u>2024 Approved  Easy iOS Screen Recording Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210640802-accelerate-your-typing-experience-effective-fixes-for-lagging-keys-in-the-latest-windows-operating-system/"><u>Accelerate Your Typing Experience: Effective Fixes for Lagging Keys in the Latest Windows Operating System.</u></a></li>
<li><a href="https://common-error.techidaily.com/call-of-duty-world-war-ii-error-4220-steps-to-repair-your-gameplay-experience/"><u>Call of Duty World War II Error 4220 - Steps to Repair Your Gameplay Experience</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-tecno-phantom-v-flip-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for Tecno Phantom V Flip Hard Reset | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/crafting-the-ultimate-documentary-experience-for-2024/"><u>Crafting the Ultimate Documentary Experience for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-to-restore-logitech-mouse-scroll-wheel-functionality/"><u>DIY Fixes to Restore Logitech Mouse Scroll Wheel Functionality</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722973838345-download-epson-wf-2760-printer-drivers-compatible-with-windows-11-10-and-8/"><u>Download Epson WF-2760 Printer Drivers Compatible with Windows 11, 10 & 8</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-straightening-gridlines-on-monitors/"><u>Effective Solutions for Straightening Gridlines on Monitors</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-media-driver-missing-fix-now/"><u>Essential Media Driver Missing? Fix Now!</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/expertly-choosing-the-leading-5-facebook-video-grabers-for-2024/"><u>Expertly Choosing the Leading 5 Facebook Video Grabers for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/handling-and-solving-google-chrome-freezing-errors-solutions-overview/"><u>Handling and Solving Google Chrome Freezing Errors - Solutions Overview</u></a></li>
<li><a href="https://common-error.techidaily.com/high-performance-windows-driver-setup-keeping-cpu-usage-low/"><u>High-Performance Windows Driver Setup: Keeping CPU Usage Low</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-a-nubia-red-magic-9-pro-phone-that-is-locked-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset a Nubia Red Magic 9 Pro Phone That Is Locked | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resync-an-unresponsive-xbox-one-controller-with-the-console-a-comprehensive-guide/"><u>How to Resync an Unresponsive Xbox One Controller with the Console - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-solve-windows-10-keeps-restarting-issue-easily/"><u>How To Solve Windows 10 Keeps Restarting Issue Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/hp-notebook-usb-dilemma-solved-how-to-restore-functionality/"><u>HP Notebook USB Dilemma Solved: How to Restore Functionality</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-clash-of-kings-royal-games-top-10-titles/"><u>In 2024, Clash of Kings  Royal Games' Top 10 Titles</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-leveraging-cloud-based-voice-storage-a-closer-look-at-vocaroos-capabilities-for-2024/"><u>New Leveraging Cloud-Based Voice Storage A Closer Look at Vocaroos Capabilities for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-initialization-issues-with-windows-11-settings-expert-advice/"><u>Overcoming Initialization Issues with Windows 11 Settings: Expert Advice</u></a></li>
<li><a href="https://win-forum.techidaily.com/race-away-from-restarts-7-surefire-fixes-for-forza-horizon-5-freeze/"><u>Race Away From Restarts: 7 Surefire Fixes for Forza Horizon 5 Freeze</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-freezing-glitches-during-the-initial-launch-of-windows-11/"><u>Resolving Freezing Glitches During the Initial Launch of Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-understanding-and-fixing-cod-wwii-error-code-4220/"><u>Resolving the Issue: Understanding and Fixing COD WWII Error Code 4220</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-windows-10-error-code-80240020-during-installation/"><u>Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-eliminating-the-this-device-is-absent-problem-on-win10-win8-and-win7-error-code-24/"><u>Step-by-Step Solution: Eliminating the 'This Device Is Absent' Problem on Win10, Win8 & Win7 (Error Code 24)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-stuck-keys-on-your-microsoft-windows-laptop-or-desktop/"><u>Troubleshooting and Repairing Stuck Keys on Your Microsoft Windows Laptop or Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-persistent-loops-in-windows-10-automatic-repairs-solved/"><u>Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-updates-how-to-fix-service-not-running-error/"><u>Troubleshooting Windows Updates: How to Fix 'Service Not Running' Error</u></a></li>
<li><a href="https://tech-revival.techidaily.com/truthgpt-coin-explained-separating-myth-from-reality-in-crypto-spaces/"><u>TruthGPT Coin Explained: Separating Myth From Reality in Crypto Spaces</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-steps-for-overcoming-twitch-error-4n007-error-4000/"><u>Ultimate Troubleshooting Steps for Overcoming Twitch Error 4N007 (Error 4000)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205981819-windows-11-copy-paste-malfunction-heres-how-to-restore-it/"><u>Windows 11 Copy-Paste Malfunction? Here's How to Restore It!</u></a></li>
</ul></div>
