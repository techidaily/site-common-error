---
title: "Optimize Your PC: Fixing the WUDFHost.exe CPU Usage Surge in Windows nX"
date: 2025-01-03T01:42:22.462Z
updated: 2025-01-04T02:50:24.839Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimize Your PC: Fixing the WUDFHost.exe CPU Usage Surge in Windows nX"
excerpt: "This Article Describes Optimize Your PC: Fixing the WUDFHost.exe CPU Usage Surge in Windows nX"
thumbnail: https://thmb.techidaily.com/8ff8906f51872923e9c5692da8760464bdd1f9c3eac0a2d615e95926075c7419.jpg
---

## Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oB9V7rZzotw?si=d4xrCbq1jKHXGAWN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4YCkNXJjC3c?si=9Tn8KiqKGTZi1o7E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xtylXDY9YfA?si=VonzSiDFGCpJm2uC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E1ax-vnGdeo?si=bgTkOhOEwDTlRQE3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-masterful-instagram-storytelling-with-templates-and-hacks/"><u>[New] 2024 Approved Masterful Instagram Storytelling with Templates & Hacks</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ow-does-youtube-work-after-a-video-is-uploaded/"><u>[New] How Does YouTube Work After a Video Is Uploaded</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-reawakening-dormant-connections-with-your-obs-cam/"><u>[New] In 2024, Reawakening Dormant Connections with Your OBS Cam</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-the-ultimate-guide-to-adjusting-to-new-facebook-ranking-criteria/"><u>[New] The Ultimate Guide to Adjusting to New Facebook Ranking Criteria</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-guide-to-fetching-superior-quality-fb-videos/"><u>2024 Approved Guide to Fetching Superior Quality FB Videos</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-methods-to-access-apples-podcast-library/"><u>2024 Approved Innovative Methods to Access Apple's Podcast Library</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-error-code-963-on-google-play-of-honor-100-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Error Code 963 on Google Play Of Honor 100 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/avoid-rough-terrain-limit-driving-over-bumpy-or-uneven-surfaces-that-could-cause-additional-stress-on-your-vehiclecuots-suspension-system/"><u>Avoid Rough Terrain: Limit Driving over Bumpy or Uneven Surfaces that Could Cause Additional Stress on Your Vehicle'cuot;s Suspension System</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-resolving-dell-laptops-black-display-issue-step-by-step-solutions/"><u>Complete Guide: Resolving Dell Laptop's Black Display Issue - Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-tackle-fatal-system-mishaps-in-black-ops-4/"><u>Effective Techniques to Tackle Fatal System Mishaps in Black Ops 4</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unknown-usb-device-port-reset-failed-issue-for-windows-10/"><u>How to Fix Unknown USB Device (Port Reset Failed) Issue for Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-non-responsive-mousepad-in-windows-operating-systems-guides-for-xpvistawindows-7810-users/"><u>How to Resolve Non-Responsive Mousepad in Windows Operating Systems - Guides for XP/Vista/Windows 7/8/10 Users</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-zte-blade-a73-5g-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track ZTE Blade A73 5G Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-vivo-y100-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restore-right-click-functionality-for-mice-on-windows-10/"><u>Step-by-Step Guide to Restore Right-Click Functionality for Mice on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-windows-1011-night-mode-wont-turn-on/"><u>Troubleshooting Tips for When Windows 10/11 Night Mode Won't Turn On</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-why-your-windows-10-upgrade-is-halted-at-99-and-how-to-fix-it/"><u>Troubleshooting: Why Your Windows 10 Upgrade Is Halted at 99% and How to Fix It</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ways-to-trade-pokemon-go-from-far-away-on-tecno-spark-20-proplus-drfone-by-drfone-virtual-android/"><u>Ways to trade pokemon go from far away On Tecno Spark 20 Pro+? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208469743-why-does-my-computer-freeze-with-windows-11-learn-the-fixes/"><u>Why Does My Computer Freeze with Windows 11? Learn the Fixes</u></a></li>
</ul></div>

