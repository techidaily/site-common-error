---
title: Troubleshooting Non-Responsive Keys on Windows 10/11 - A Step-by-Step Guide
date: 2024-08-27T13:53:25.244Z
updated: 2024-08-28T13:53:25.244Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Non-Responsive Keys on Windows 10/11 - A Step-by-Step Guide
excerpt: This Article Describes Troubleshooting Non-Responsive Keys on Windows 10/11 - A Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/85e69845f10f793c5b081e6eac45cea976095820d8ff765825e636a33b833fec.jpg
---

## Troubleshooting Missing Desktop Icons on Windows 11 – Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

### Tip 1: Enable Show desktop icons

Make sure you have enabled the “Show desktop icon” feature on Windows 10:

1. Right-click your desktop, click **View**, and check **Show desktop icons**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf52ca259fe4.jpg)
2. Check to see if your desktop icons are back. If not, try Tip 2, below.

---

<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482"><img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  
<!-- affiliate ads begin -->
<a href="https://aspironcom.sjv.io/c/5597632/1941789/21554" target="_top" id="1941789"><img src="//a.impactradius-go.com/display-ad/21554-1941789" border="0" alt="" width="650" height="800"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1941789/21554" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
taskkill /F /IM explorer.exe  
cd /d %userprofile%\AppData\Local  
attrib –h IconCache.db  
del IconCache.db  
start explorer.exe
3. Check if it helps restore your desktop icons. If not, try Tip 4, below.

---

### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40203538&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/cc4b82e826b52ec41c810301548e8f48/products/audio-to-text-transcription-software.png" border="0">EaseText Audio to Text Converter for Windows (Personal Edition) - An intelligent tool to transcribe & convert audio to text freely </a>
<!-- affiliate ads end -->
### Bonus tip

A missing or outdated graphics driver may also stop items from appearing properly on PC. You should make sure your graphics card driver is up to date. There are two ways to update your graphics driver: **manually** and **automatically**.

**Update your graphics driver manually** — You can update your driver manually by going to the hardware manufacturer’s website, and searching for the latest driver for your graphics card. But if you take this approach, be sure to choose the driver that’s compatible with the exact model number of your hardware, and your version of Windows.

OR

**Update your graphics driver automatically** — If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.
2. Run Driver Easy and click **Scan Now**. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)
3. Click **Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click **Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money-back guarantee.)  
![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

Hopefully, this can help you out.

If you have any other suggestions, please feel free to leave a comment below.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://common-error.techidaily.com/expert-tips-conquering-the-windows-error-80070103-on-your-system/"><u>[Expert Tips] Conquering the Windows Error 80070103 on Your System</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/024-approved-comprehensive-guide-to-youtube-video-captioning/"><u>[New] 2024 Approved  Comprehensive Guide to YouTube Video Captioning</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-chronicle-conversations-on-google-for-2024/"><u>[New] Chronicle Conversations on Google for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-a-comprehensive-guide-to-implementing-and-evaluating-fb-in-stream-ads/"><u>[New] In 2024, A Comprehensive Guide to Implementing & Evaluating FB In-Stream Ads</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-evaluating-itop-as-a-screen-recording-solution/"><u>[New] In 2024, Evaluating ITop as a Screen Recording Solution?</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-virtual-worlds-await-top-10-vr-videos/"><u>[New] In 2024, Virtual Worlds Await  Top 10 VR Videos</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-harness-facebook-videos-on-devices-with-new-tool-for-2024/"><u>[Updated] Harness Facebook Videos on Devices with New Tool for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-mastering-radial-blur-photoshop-edition/"><u>2024 Approved  Mastering Radial Blur  Photoshop Edition</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-tips-for-successful-youtube-audios/"><u>2024 Approved  Tips for Successful Youtube Audios</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-fix-no-sound-driver-installed-problem-in-windows-11/"><u>Comprehensive Solutions to Fix ‘No Sound Driver Installed’ Problem in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204929300-easy-guide-stop-that-constant-cursor-fix-blink-issue-now/"><u>Easy Guide: Stop That Constant Cursor - Fix Blink Issue Now</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-device-or-resource-unavailable-on-windows-systems/"><u>Effective Fixes for 'Device or Resource Unavailable' On Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-for-correcting-error-code-0x80070002-in-windows-updates-a-step-by-step-guide/"><u>Effective Techniques for Correcting Error Code 0X80070002 in Windows Updates - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-incompatible-drivers-can-cause-ftdi-memory-verification-failure/"><u>How Incompatible Drivers Can Cause FTDI Memory Verification Failure</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-check-distance-and-radius-on-google-maps-for-your-xiaomi-redmi-note-12-pro-5g-drfone-by-drfone-virtual-android/"><u>How to Check Distance and Radius on Google Maps For your Xiaomi Redmi Note 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-usb-device-not-recognized-error-a-comprehensive-guide/"><u>How to Fix 'USB Device Not Recognized' Error: A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-12-pro-max-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 12 Pro Max using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211732304-how-to-resolve-issues-with-computer-not-powering-off-in-windows-11-fixed/"><u>How to Resolve Issues with Computer Not Powering Off in Windows 11 – FIXED</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-oddworld-soulstorms-startup-problems-on-a-personal-laptop-solution-included/"><u>How To Resolve Oddworld: Soulstorm's Startup Problems On A Personal Laptop (Solution Included)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-a-quick-guide-to-infinix-zero-5g-2023-turbo-frp-bypass-instantly-by-drfone-android/"><u>In 2024, A Quick Guide to Infinix Zero 5G 2023 Turbo FRP Bypass Instantly</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-samsung-galaxy-a05-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Samsung Galaxy A05 | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/in-2024-engineering-a-standout-tiktok-endcap/"><u>In 2024, Engineering A Standout TikTok Endcap</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-explore-the-art-of-vocal-transformation-with-these-cost-free-alternatives/"><u>In 2024, Explore the Art of Vocal Transformation with These Cost-Free Alternatives</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Honor 100? | Dr.fone</u></a></li>
<li><a href="https://fox-direct.techidaily.com/lens-legends-library-your-query-guide/"><u>Lens Legends' Library  Your Query Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-monitor-troubles-how-to-get-your-aoc-screen-up-and-running-on-windows-11/"><u>Mastering Monitor Troubles: How to Get Your AOC Screen Up & Running on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/no-errors-found-just-an-unresponsive-device/"><u>No Errors Found; Just an Unresponsive Device</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-windows-10-cant-be-installed-error-code-abo)80240020-issue-solved/"><u>Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved!</u></a></li>
<li><a href="https://network-issues.techidaily.com/overcoming-unavailable-screen-configurations-in-nvidia/"><u>Overcoming Unavailable Screen Configurations in NVIDIA</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-windows-7-boot-delays-improve-system-performance-now/"><u>Quick Fixes for Windows 7 Boot Delays – Improve System Performance Now</u></a></li>
<li><a href="https://common-error.techidaily.com/repair-guide-for-defective-keyboard-letters-on-win-11-systems/"><u>Repair Guide for Defective Keyboard Letters on Win 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-steps-when-you-cant-reach-the-dhcp-server/"><u>Resolved: Troubleshooting Steps When You Can't Reach the DHCP Server</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11s-mysterious-mouse-cursor-problem-effective-solutions-revealed/"><u>Resolving Windows 11'S Mysterious Mouse Cursor Problem: Effective Solutions Revealed</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-launches-worlds-first-photo-recovery-and-repair-software/"><u>Stellar Launches World's First Photo Recovery & Repair Software</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-getting-your-windows-1011-night-mode-back-on-track/"><u>Step-by-Step: Getting Your Windows 10/11 Night Mode Back on Track</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-guide-to-repairing-windows-update-error-0x80244n2c-proven-solutions-applied/"><u>The Definitive Guide to Repairing Windows Update Error 0X80244n2c - Proven Solutions Applied</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-essential-blueprint-crafting-memes-that-perform-on-social-networks/"><u>The Essential Blueprint  Crafting Memes That Perform on Social Networks</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/the-rare-asus-maxximus-xiii-frankenboard-custom-motherboards-with-so-dimm-slot-support-and-exclusive-kingston-fury-imprint/"><u>The Rare ASUS Maxximus XIII Frankenboard - Custom Motherboards with SO-DIMM Slot Support and Exclusive Kingston Fury Imprint</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-3d-rendering-errors-fixing-d3derrnotavailable-issues/"><u>Troubleshooting 3D Rendering Errors: Fixing D3DERR_NOTAVAILABLE Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unresponsive-user-configuration-options-easily/"><u>Troubleshooting Unresponsive User Configuration Options Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-troubleshooting-windows-11s-bluetooth-connectivity-issues/"><u>Ultimate Guide: Troubleshooting Windows 11'S Bluetooth Connectivity Issues</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/unlock-apple-iphone-7-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>Unlock Apple iPhone 7 With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/why-does-microsoft-security-essentials-cause-high-disk-usage-exploring-the-role-of-mssecesexe/"><u>Why Does Microsoft Security Essentials Cause High Disk Usage? Exploring the Role of msseces.exe</u></a></li>
<li><a href="https://common-error.techidaily.com/x3daudio17dll-glitch-a-simple-guide-to-fixes/"><u>X3DAudio1_7.dll Glitch: A Simple Guide to Fixes</u></a></li>
</ul></div>
