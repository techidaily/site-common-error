---
title: ntoskrnl.exe High CPU or Disk Usage on Windows [Solved]
date: 2025-02-24T22:17:50.790Z
updated: 2025-03-02T06:04:14.161Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes ntoskrnl.exe High CPU or Disk Usage on Windows [Solved]
excerpt: This Article Describes ntoskrnl.exe High CPU or Disk Usage on Windows [Solved]
thumbnail: https://thmb.techidaily.com/de2a2439a12942f0b9808810580359ed4223c732cf24aad5cc401c9c124e67ae.jpeg
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

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

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
<li><a href="https://youtube-blog.techidaily.com/-step-by-step-guide-on-applying-cc-rights-effectively/"><u>[New] A Step-by-Step Guide on Applying CC Rights Effectively</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-understanding-luts-to-amplify-your-photo-quality-for-2024/"><u>[New] Understanding LUTs to Amplify Your Photo Quality for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-gtx-gems-the-best-for-high-res-gaming/"><u>[Updated] 2024 Approved GTX Gems The Best for High-Res Gaming</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-immediate-access-best-5-convertors-no-download-required/"><u>[Updated] Immediate Access Best 5 Convertors, No Download Required</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-navigating-neat-networks-of-needle-precision-racing-games/"><u>2024 Approved Navigating Neat Networks of Needle-Precision Racing Games</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/2024-approved-transform-youtube-live-with-these-must-know-secrets/"><u>2024 Approved Transform YouTube Live with These Must-Know Secrets</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-24-a-step-by-step-solution-for-missing-devices-in-windows-10-8-and-7/"><u>Error Code 24 - A Step-by-Step Solution for Missing Devices in Windows 10, 8 & 7</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-reset-a-nokia-c210-phone-that-is-locked-by-drfone-android/"><u>How to Reset a Nokia C210 Phone that is Locked?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-innovative-title-generators-for-youtube-visionaries/"><u>In 2024, Innovative Title Generators for YouTube Visionaries</u></a></li>
<li><a href="https://article-posts.techidaily.com/joketileart-imagehumorhub/"><u>JokeTileArt ImageHumorHub</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-disabled-wi-fi-functionality-a-comprehensive-guide/"><u>Resolving Issues with Disabled Wi-Fi Functionality: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-print-screen-failure-in-windows-10-and-windows-11-operating-systems/"><u>Resolving Print Screen Failure in Windows 10 and Windows 11 Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/technical-guide-to-optimal-playability-why-your-pc-must-have-a-d3d11-graphics-card-compatibility-to-run-the-engine-flawlessly/"><u>Technical Guide to Optimal Playability: Why Your PC Must Have a D3D11 Graphics Card Compatibility to Run the Engine Flawlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-windows-10-laptops-that-wont-charge-despite-being-plugged-in/"><u>The Ultimate Fix for Windows 10 Laptops That Won't Charge Despite Being Plugged In</u></a></li>
<li><a href="https://common-error.techidaily.com/wheel-alignment-keep-your-wheels-properly-aligned-to-reduce-undue-stress-on-suspension-components-misalignment-can-cause-premature-wear-and-potentially-dama141/"><u>Wheel Alignment: Keep Your Wheels Properly Aligned to Reduce Undue Stress on Suspension Components. Misalignment Can Cause Premature Wear and Potentially Damage Other Parts of the Vehicle if Not Addressed Promptly.</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211145723-windows-11-mic-not-working-heres-what-you-need-to-do-next/"><u>Windows 11 Mic Not Working? Here's What You Need to Do Next!</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-at-windows-11-essential-tweaks-to-elevate-your-gaming-capabilities/"><u>Winning at Windows 11: Essential Tweaks to Elevate Your Gaming Capabilities</u></a></li>
</ul></div>

