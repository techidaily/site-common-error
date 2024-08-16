---
title: "Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved!"
date: 2024-08-15T11:11:14.444Z
updated: 2024-08-16T11:11:14.444Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved!"
excerpt: "This Article Describes Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved!"
thumbnail: https://thmb.techidaily.com/fe961e2cb838e9277b3f939887a164216256186200a3f57210ef49bd6287bae1.jpg
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

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)
<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2084396/18498" target="_top" id="2084396"><img src="//a.impactradius-go.com/display-ad/18498-2084396" border="0" alt="" width="1920" height="700"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2084396/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->

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
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://turtlebeachus.sjv.io/c/5597632/1988416/23719" target="_top" id="1988416"><img src="//a.impactradius-go.com/display-ad/23719-1988416" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1988416/23719" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-improve-video-loading-times-in-instagram/"><u>[New] Improve Video Loading Times in Instagram</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-premium-8k-vision-selecting-the-superior-cameras/"><u>[New] Premium 8K Vision  Selecting the Superior Cameras</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-10-essential-tips-to-turnback-a-live-twitch-session/"><u>[Updated] 10 Essential Tips to Turnback a Live Twitch Session</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-camstudio-screen-recorder-complete-review/"><u>[Updated] 2024 Approved  CamStudio Screen Recorder Complete Review</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-dissecting-viral-trends-for-immersive-fb-ad-content-for-2024/"><u>[Updated] Dissecting Viral Trends for Immersive FB Ad Content for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-why-choose-youtubes-av1-for-impeccable-video-playback/"><u>[Updated] Why Choose YouTube's AV1 for Impeccable Video Playback?</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mastering-iphones-ringtone-personalization/"><u>2024 Approved  Mastering iPhone's Ringtone Personalization</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-sxs-side-by-side-configurations-resolving-compatibility-issues-in-windows-11/"><u>Correcting SxS (Side-by-Side) Configurations: Resolving Compatibility Issues in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/dxgidll-woes-now-a-thing-of-past-in-pubg/"><u>Dxgi.dll Woes: Now a Thing of Past in PUBG</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-pc-wont-exit-windows-10-properly/"><u>Effective Fixes for When Your PC Won't Exit Windows 10 Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-inoperative-usb-slots-on-windows-11-pcs/"><u>Effective Solutions for Inoperative USB Slots on Windows 11 PCs</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/effortless-image-incorrante-on-instagram-for-2024/"><u>Effortless Image Incorrante on Instagram for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/enhancing-wdf-efficiency-to-reduce-high-cpu-consumption-problems/"><u>Enhancing WDF Efficiency to Reduce High CPU Consumption Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-why-teredo-qualification-fails-and-how-to-fix-it/"><u>Expert Guide: Why Teredo Qualification Fails and How to Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-overcoming-microphone-challenges-in-the-latest-microsoft-os-windows-11-edition/"><u>Expert Tips: Overcoming Microphone Challenges in the Latest Microsoft OS - Windows 11 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-application-startup-problems-a-guide-for-built-in-admin-accounts/"><u>Fixing Application Startup Problems: A Guide for Built-In Admin Accounts</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-memory-corruption-in-ftdisk-systems-due-to-incompatible-drives/"><u>Fixing Memory Corruption in FTDisk Systems Due to Incompatible Drives</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-sound-hiccups-heres-how-to-address-the-cut-out-issue-with-your-logitech-g930/"><u>Fixing Sound Hiccups? Here's How to Address the Cut-Out Issue with Your Logitech G930</u></a></li>
<li><a href="https://change-location.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Samsung Galaxy S23 | Dr.fone</u></a></li>
<li><a href="https://driver-error.techidaily.com/how-to-disable-always-active-bluetooth-on-win11/"><u>How To Disable Always Active Bluetooth on Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-damaged-files-and-directories-that-wont-open/"><u>How to Fix Damaged Files & Directories That Won't Open</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-vivo-s18-without-the-home-button-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Vivo S18 Without the Home Button | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-connection-problems-on-your-minecraft-lan-setup/"><u>How to Resolve Connection Problems on Your Minecraft LAN Setup</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-nokia-c210-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Nokia C210 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-debunking-myths-top-10-realities-of-instagram-reels/"><u>In 2024, Debunking Myths  Top 10 Realities of Instagram Reels</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-unlocking-timelapse-magic-with-your-gopro/"><u>In 2024, Unlocking Timelapse Magic with Your GoPro</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-silence-no-more-effortless-solutions-to-restore-sounds/"><u>Netflix Silence No More: Effortless Solutions to Restore Sounds</u></a></li>
<li><a href="https://sound-issues.techidaily.com/optimize-audio-quality-by-disabling-enhancements-in-windows-10/"><u>Optimize Audio Quality by Disabling Enhancements in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-geforce-experience-not-opening-an-easy-fix/"><u>Overcoming Issues with GeForce Experience Not Opening: An Easy Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unstable-visual-glitches-in-your-windows-10-device/"><u>Overcoming Unstable Visual Glitches in Your Windows 10 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-resolving-non-functioning-lenovo-fingerprint-scanner-issues/"><u>Quick Fixes: Resolving Non-Functioning Lenovo Fingerprint Scanner Issues</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-solutions-for-restoring-sound-on-skype/"><u>Quick Solutions for Restoring Sound on Skype</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-guide-turning-off-a-non-responsive-windows-11-system/"><u>Resolved Guide: Turning Off a Non-Responsive Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-launch-errors-what-to-do-when-minecraft-fails-to-start-in-windows/"><u>Resolving Launch Errors: What to Do When Minecraft Fails to Start in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-missing-opencl-dynamic-library-errors/"><u>Resolving Missing OpenCL Dynamic Library Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-common-update-failed-mistakes-in-warframe-a-comprehvee-guide/"><u>Resolving the Common 'Update Failed' Mistakes in Warframe - A Comprehvee Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-non-appearance-of-wi-fi-settings-on-windows-11-devices/"><u>Resolving the Non-Appearance of Wi-Fi Settings on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-brightness-control-problem-for-a-perfect-display-setup/"><u>Resolving the Windows 11 Brightness Control Problem for a Perfect Display Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201594479-shockwave-flash-issues-in-google-chrome-follow-our-updated-solution-guide/"><u>Shockwave Flash Issues in Google Chrome? Follow Our Updated Solution Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-fixing-shockwave-flash-issues-on-google-chrome/"><u>Solution Steps: Fixing Shockwave Flash Issues on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-why-cant-my-geforce-experience-load-preferences/"><u>Solution Steps: Why Can't My GeForce Experience Load Preferences?</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-networking-issue-code-0x80n0704cf-explained-and-resolved/"><u>Solving Windows Networking Issue: Code 0X80n0704CF Explained and Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201318600-steelseries-arctis-5-audio-trouble-heres-how-to-fix-the-mic-problem-permanently/"><u>SteelSeries Arctis 5 Audio Trouble? Here's How to Fix the Mic Problem Permanently!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211260772-step-by-step-guide-to-restore-lost-devices-in-overwatch-quick-resolution-tips/"><u>Step-by-Step Guide to Restore Lost Devices in Overwatch - Quick Resolution Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-integrity-of-windows-os-file-system/"><u>Step-by-Step Guide: Restoring Integrity of Windows OS File System</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-update-error-code-0x80240034-on-windows-10-devices/"><u>Step-by-Step Solution to Overcome 'Update Error' Code 0X80240034 on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-tackling-and-overcoming-delayed-shutdowns-in-windows-10/"><u>The Ultimate Fix: Tackling and Overcoming Delayed Shutdowns in Windows 10</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-unseen-secrets-of-optimizing-win11-performance/"><u>The Unseen Secrets of Optimizing Win11 Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-kodi-a-comprehensive-guide/"><u>Troubleshooting and Fixing Kodi: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-oddworld-soulstorm-crashes-on-personal-computers/"><u>Troubleshooting Guide for Oddworld: Soulstorm Crashes on Personal Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-common-issues-with-your-oculus-device/"><u>Troubleshooting Guide: Resolving Common Issues with Your Oculus Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-windows-10-issues-with-the-duo-approach-system-file-checker-sfc-and-deployment-image-servicing-dism/"><u>Troubleshooting Tips for Windows 10 Issues with The Duo Approach: System File Checker (SFC) and Deployment Image Servicing (DISM).</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-triumph-how-to-successfully-address-the-red-error-message/"><u>Troubleshooting Triumph: How to Successfully Address the Red Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-minimizing-dwms-impact-on-gpu-performance-in-windows-10-and-11/"><u>Ultimate Guide: Minimizing DWM's Impact on GPU Performance in Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-your-pcs-persistent-freezing-problem/"><u>Ultimate Guide: Solving Your PC's Persistent Freezing Problem</u></a></li>
</ul></div>
