---
title: "Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside!"
date: 2024-11-22T20:57:17.172Z
updated: 2024-11-24T22:06:30.968Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside!"
excerpt: "This Article Describes Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside!"
thumbnail: https://thmb.techidaily.com/9a0ccdfbe8da8591524befa7834f5f64eb569a97d027f532be495df3d4cfc012.jpg
---

## Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hHPljBHrvkA?si=HwdfDM9rlbABSIrx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2NU63YqpVqw?si=uoJs0-nZYAkILqXx&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlYIdWQc-jw?si=ZQ5809CbQGEar0vg&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aRMCbJxLuwE?si=E5sfJvoqkv1qCMWz&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-activity-recording.techidaily.com/new-an-easy-to-follow-methodology-for-initiating-a-productive-skype-conversation-among-various-os-users-for-2024/"><u>[New] An Easy-to-Follow Methodology for Initiating a Productive Skype Conversation Among Various OS Users for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-gopro-vs-garmin-hero5-black-vs-virb-ultra-gadget-showdown/"><u>[New] In 2024, GoPro Vs. Garmin Hero5 Black Vs. VIRB Ultra - Gadget Showdown</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-mastering-game-streams-with-ai-enhanced-portraits-for-2024/"><u>[New] Mastering Game Streams with AI-Enhanced Portraits for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-core-understanding-of-narrative-frameworks/"><u>[Updated] Core Understanding of Narrative Frameworks</u></a></li>
<li><a href="https://video-capture.techidaily.com/windows-10apple-tvdvd/"><u>「無料アプリを使用して、Windows 10コンピューターからApple TVにDVDストリーミング方法」</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-invalid-folder-name-dilemeba-expert-tips-and-techniques/"><u>Bypassing the 'Invalid Folder Name' Dilemeba: Expert Tips & Techniques</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-honor-play-8t-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Honor Play 8T Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-activate-your-printer-and-solve-the-30-error/"><u>Easy Steps to Activate Your Printer and Solve the -30 Error</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-bring-your-vision-to-life-best-animation-software-for-mac-and-windows/"><u>In 2024, Bring Your Vision to Life Best Animation Software for Mac and Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-exploring-the-reasons-behind-instagram-disconnections/"><u>In 2024, Exploring the Reasons Behind Instagram Disconnections</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-key-not-working-easy-solutions-for-windows-1011-users/"><u>Keyboard Key Not Working? Easy Solutions for Windows 10/11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-fixing-failed-steam-updates-practical-advice-and-solutions/"><u>Mastering the Art of Fixing Failed Steam Updates: Practical Advice & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-challenges-in-initializing-direct3d-fixing-device-creation-errors-successfully/"><u>Overcoming Challenges in Initializing Direct3D: Fixing Device Creation Errors Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-netflix-dark-mode-dilemma-effective-troubleshooting-steps/"><u>Overcoming Netflix Dark Mode Dilemma - Effective Troubleshooting Steps</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/unleash-your-potential-detailed-guide-for-ps4-recordings-with-obs/"><u>Unleash Your Potential Detailed Guide for PS4 Recordings with OBS</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-customization-in-enterprises-a-look-at-managed-settings-options/"><u>Windows Customization in Enterprises: A Look at Managed Settings Options</u></a></li>
</ul></div>

