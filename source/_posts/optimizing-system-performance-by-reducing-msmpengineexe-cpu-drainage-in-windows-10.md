---
title: Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10
date: 2024-12-27T20:43:58.058Z
updated: 2025-01-04T00:03:35.775Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10
excerpt: This Article Describes Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10
thumbnail: https://thmb.techidaily.com/db3dbeacfdd5ea435b3f8eb406f01646288938a037fe9e28d65cbe9fbebcdbb0.png
---

## Optimizing System Performance by Reducing MsMpEngine.exe CPU Drainage in Windows 10

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/H2cXnI9oOvM?si=3nz2sBB124ln-83T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RBN1gYY5hUs?si=p89CMiMzeJzU0wGu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PKZUYice-ws?si=L8iMa9T3h7TMSWdQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZblaBc-v2vs?si=CKW1gJwXQT2vZJYo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-seamless-tweet-to-facebook-video-transfers-users/"><u>[New] 2024 Approved Seamless Tweet-to-Facebook Video Transfers Users</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-insta-boomerang-strategies-for-engaging-loops/"><u>[New] Insta-Boomerang Strategies for Engaging Loops</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-mastering-video-aspects-online/"><u>[New] Mastering Video Aspects Online</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-top-10-elite-battle-royale-contenders-for-2024/"><u>[New] Top 10 Elite Battle Royale Contenders for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-adventure-companion-unveiling-panasonic-hx-a1-actioncam/"><u>2024 Approved The Adventure Companion Unveiling Panasonic HX-A1 ActionCam</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-the-absence-of-opencl-drivers/"><u>Addressing the Absence of OpenCL Drivers</u></a></li>
<li><a href="https://win-amazing.techidaily.com/ensure-smooth-printing-with-the-updated-epson-l3150-drivers-for-windows-11-8-and-7/"><u>Ensure Smooth Printing with the Updated Epson L3150 Drivers for Windows 11, 8 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208133743-errtoomanyredirects-clear-it-up-in-minutes-with-these-tips/"><u>ERR_TOO_MANY_REDIRECTS? Clear It Up in Minutes with These Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-to-fixing-error-code-0x887a0006-a-speedier-solution-guide/"><u>Fast Track to Fixing Error Code 0X887A0006 – A Speedier Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-correcting-the-troublesome-0x8024401c-update-glitch-in-windows-1011-platforms/"><u>Guide to Correcting the Troublesome 0X8024401C Update Glitch in Windows 10/11 Platforms</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208971806-how-to-fix-your-game-requires-a-system-restart-to-play-valorant/"><u>How to Fix “Your Game Requires a System Restart to Play” Valorant</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-call-logs-from-your-vivo-v30-lite-5g-by-fonelab-android-recover-call-logs/"><u>How to recover old call logs from your Vivo V30 Lite 5G?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-ways-to-stop-parent-tracking-your-xiaomi-redmi-k70-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to stop parent tracking your Xiaomi Redmi K70 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook.techidaily.com/navigating-sarcasm-facebooks-updated-guidelines/"><u>Navigating Sarcasm: Facebook's Updated Guidelines</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-computer-how-to-tame-unwarranted-system-load-caused-by-infrastructure-shell-on-windowslinux/"><u>Reviving Your Computer: How to Tame Unwarranted System Load Caused By Infrastructure Shell on Windows/Linux</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212279268-troubleshooting-and-repairing-windows-cant-reset-your-pc-message-solved/"><u>Troubleshooting and Repairing 'Windows Can't Reset Your PC' Message – Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/tuning-in-again-overcoming-the-mute-challenge-in-forza-horizon-4-gaming/"><u>Tuning In Again: Overcoming the Mute Challenge in Forza Horizon 4 Gaming</u></a></li>
<li><a href="https://win-manuals.techidaily.com/two-effective-techniques-for-building-vcenter-templates-a-comprehensive-guide/"><u>Two Effective Techniques for Building vCenter Templates: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/user-friendly-fixes-for-werfaultexe-software-malfunction/"><u>User-Friendly Fixes for werFault.exe Software Malfunction</u></a></li>
</ul></div>

