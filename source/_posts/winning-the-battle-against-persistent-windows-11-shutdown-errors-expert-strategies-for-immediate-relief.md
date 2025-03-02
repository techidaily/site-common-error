---
title: Winning the Battle Against Persistent Windows 11 Shutdown Errors – Expert Strategies for Immediate Relief
date: 2025-02-26T22:41:54.106Z
updated: 2025-03-01T20:25:11.018Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Winning the Battle Against Persistent Windows 11 Shutdown Errors – Expert Strategies for Immediate Relief
excerpt: This Article Describes Winning the Battle Against Persistent Windows 11 Shutdown Errors – Expert Strategies for Immediate Relief
thumbnail: https://thmb.techidaily.com/cb70e57700d07e1f21d91f89b112cf1e7299f5606065c397aa28c9965f8c1a6d.jpg
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
<li><a href="https://remote-screen-capture.techidaily.com/new-premium-audio-capabilities-1-10-free-desktop-tools/"><u>[New] Premium Audio Capabilities #1-#10 Free Desktop Tools</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-elevate-your-online-presence-advanced-techniques-in-zoom-video-sharing/"><u>[Updated] 2024 Approved Elevate Your Online Presence Advanced Techniques in Zoom Video Sharing</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-getting-started-with-iphone-speech-recordings/"><u>[Updated] 2024 Approved Getting Started with iPhone Speech Recordings</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-lifes-journey-videos-creating-authentic-online-experiences-for-2024/"><u>[Updated] Life's Journey Videos Creating Authentic Online Experiences for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-error-8007000e-streamlined-strategies-to-restore-windows-updates/"><u>Bypassing Error 8007000E: Streamlined Strategies to Restore Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-restoring-damaged-registry-and-system-files-in-windows-11/"><u>Complete Guide: Restoring Damaged Registry and System Files in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-a-broken-system-restore-feature-in-windows-10/"><u>Effective Fixes for a Broken System Restore Feature in Windows 10</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/expert-advice-to-recover-missing-thumbnails-from-videos-for-2024/"><u>Expert Advice to Recover Missing Thumbnails From Videos for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-expert-tips-for-dealing-with-the-notorious-reddit-blue-screen/"><u>Fixed! Expert Tips for Dealing with the Notorious REDdit Blue Screen</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-digitize-your-old-photos-and-turn-them-into-videos-for-2024/"><u>How to Digitize Your Old Photos and Turn Them Into Videos for 2024</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/joining-friends-showtime-on-tiktok-with-ease-for-2024/"><u>Joining Friends’ Showtime on TikTok with Ease for 2024</u></a></li>
<li><a href="https://win-able.techidaily.com/master-the-fixes-for-madden-22-issues-in-minutes/"><u>Master the Fixes for Madden 22 Issues in Minutes</u></a></li>
<li><a href="https://common-error.techidaily.com/oddworld-soulstorm-for-pc-stability-hacks-and-fixes-a-comprehensive-solution/"><u>Oddworld: Soulstorm for PC Stability Hacks and Fixes – A Comprehensive Solution</u></a></li>
<li><a href="https://blog-min.techidaily.com/reconnect-with-whats-gone-wonderfox-successfully-revives-lost-webpages/"><u>Reconnect with What's Gone: WonderFox Successfully Revives Lost Webpages!</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/revolutionary-free-fb-story-magicians-for-extensions-and-mobile-for-2024/"><u>Revolutionary Free FB Story Magicians for Extensions & Mobile for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-rectify-missing-msvcp140dll/"><u>Steps to Rectify Missing MSVCP140.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-keystroke-errors-and-mistyped-letters/"><u>Troubleshooting Keystroke Errors and Mistyped Letters</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-lowering-graphics-card-load-in-win11s-desktop-manager-settings/"><u>Ultimate Guide to Lowering Graphics Card Load in Win11’s Desktop Manager Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/wi-fi-connection-restored-tips-to-reestablish-your-devices-lost-wireless-functionality/"><u>Wi-Fi Connection Restored - Tips to Reestablish Your Device's Lost Wireless Functionality</u></a></li>
</ul></div>

