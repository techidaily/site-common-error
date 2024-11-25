---
title: ntoskrnl.exe High CPU or Disk Usage on Windows [Solved]
date: 2024-11-22T00:58:55.955Z
updated: 2024-11-24T22:37:18.940Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FLlUft1ZxI0?si=pBd5QdHEE27qsNlN&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vQbNyknjJJ8?si=RGVIEWLdPbvRC_r6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-raisingthebarbeyondmycam-cameras/"><u>[New] 2024 Approved RaisingTheBarBeyondMyCam Cameras</u></a></li>
<li><a href="https://youtube-data.techidaily.com/oost-your-content-access-free-vocal-sfx/"><u>[New] Boost Your Content Access Free Vocal SFX!</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-expert-ai-visualization-toolset/"><u>[Updated] 2024 Approved Expert AI Visualization Toolset</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminating-opencldll-non-existence-anomalies/"><u>Eliminating OpenCL.dll Non-Existence Anomalies</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-applied-unavailable-touch-response-and-software-input-methods-restored/"><u>Fix Applied: Unavailable Touch Response and Software Input Methods Restored</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-update-issues-expert-guide-to-enable-the-service/"><u>Fixing Windows Update Issues: Expert Guide to Enable the Service</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-icloud-activation-lock-with-imei-code-from-iphone-8-plus-by-drfone-ios/"><u>In 2024, Bypass iCloud Activation Lock with IMEI Code From iPhone 8 Plus</u></a></li>
<li><a href="https://facebook.techidaily.com/iphones-escape-from-app-surveillance-prowess/"><u>IPhones Escape From App Surveillance Prowess</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-call-of-duty-ww2-challenge-error-code-amoji-4220-solutions/"><u>Overcoming Call of Duty WW2 Challenge: Error Code Amoji 4220 Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-fixes-for-the-persistent-problem-of-windows-10-spontaneous-reboots/"><u>Simple Fixes for the Persistent Problem of Windows 10 Spontaneous Reboots</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-laptop-touchpad-issues-on-windows-1087-a-comprehensive-guide/"><u>Solving Laptop Touchpad Issues on Windows 10/8/7: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-driverpowerstatefailures/"><u>Step-by-Step Solution to Overcome DRIVER_POWER_STATE_FAILUREs</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/the-next-big-thing-all-you-need-to-know-about-the-new-foldable-iphones-price-speculations-and-release-details/"><u>The Next Big Thing? All You Need to Know About the New Foldable iPhones - Price Speculations and Release Details</u></a></li>
<li><a href="https://games-able.techidaily.com/top-5-impressions-lenovos-legion-go-showcase-at-ifa/"><u>Top 5 Impressions: Lenovo's Legion Go Showcase at IFA</u></a></li>
<li><a href="https://extra-resources.techidaily.com/transformative-tools-unveiling-top-6-nft-platforms-for-artists/"><u>Transformative Tools Unveiling Top 6 NFT Platforms For Artists</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-unsupported-device-for-casting-via-miracast/"><u>Troubleshooting Guide: Resolving 'Unsupported Device for Casting via Miracast'</u></a></li>
<li><a href="https://win-solutions.techidaily.com/why-wont-my-game-of-stardew-valley-begin-quick-fixes-for-a-seamless-start/"><u>Why Won’t My Game of Stardew Valley Begin? Quick Fixes for a Seamless Start</u></a></li>
</ul></div>

