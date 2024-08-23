---
title: System Overheats, Rests After Gaming
date: 2024-08-22T19:24:29.590Z
updated: 2024-08-23T19:24:29.590Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes System Overheats, Rests After Gaming
excerpt: This Article Describes System Overheats, Rests After Gaming
thumbnail: https://thmb.techidaily.com/c930e94b907356f9a15f0bf147840ab473cafcc143e2f86bb990ae121e306783.png
---

## LSA Safety Measures Fully Operational Again - Secure Your System Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

## Try these fixes to enable the Local Security Authority Protection

 As mentioned, in most cases, your Local Security Authority is off because of a UI bug with a Windows patch, so the first method should be enough to help. If it doesn’t, please move on to methods 2 and 3.

1. **[Install Windows Update patch KB5007651](#m1)**
2. **[Modify Registry Editor](#m2)**
3. **[Configure Group Policy Editor](#m3)**

---

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
 Fortect comes with a 60-day Money-Back Guarantee. If you’re not satisfied with Fortect, you can contact <support@fortect.com> for a full refund.

 Still unsure if Fortect is what you need? Check this [Fortec Review](https://tools.techidaily.com/drivereasy/download/) !

---

 The above is what we have to offer regarding “Local Security Authority protection is off” problem. If you have any other suggestions, please feel free to leave a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-webinar-mastery-record-without-monetary-burden/"><u>[New] 2024 Approved  Webinar Mastery  Record Without Monetary Burden</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-channel-boost-achieve-youtube-affiliate-milestone-with-10k-vistas/"><u>[New] Channel Boost  Achieve YouTube Affiliate Milestone with 10K Vistas</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-perfecting-package-adventure-for-all-for-2024/"><u>[Updated] Perfecting Package Adventure for All for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-streaming-services-app-investigation-findings/"><u>2024 Approved  Streaming Services App Investigation Findings</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-top-5-slow-motion-video-gear/"><u>2024 Approved  Top 5 Slow-Motion Video Gear</u></a></li>
<li><a href="https://android-unlock.techidaily.com/7-ways-to-unlock-a-locked-samsung-galaxy-f04-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Samsung Galaxy F04 Phone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/accelerated-learning-lithuanias-language-online/"><u>Accelerated Learning: Lithuania's Language Online</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-poco-c65-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Poco C65</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/cross-platform-comedy-best-meme-contenders-for-2024/"><u>Cross-Platform Comedy  Best Meme Contenders for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-to-overcome-entry-point-not-found-errors-in-windows-environments/"><u>Easy Solutions to Overcome Entry Point Not Found Errors in Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-address-and-fix-error-0x80070079-semaphore-timed-out/"><u>Effective Solutions to Address and Fix Error 0X80070079: Semaphore Timed Out</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207770097-effortless-methods-to-revive-charging-on-your-laptop-battery/"><u>Effortless Methods to Revive Charging on Your Laptop Battery</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x8024002e-explained-a-comprehensive-guide-to-successfully-update-windows-without-issues/"><u>Error 0X8024002E Explained: A Comprehensive Guide to Successfully Update Windows Without Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-communication-restored-tackling-the-crc-error-effectively/"><u>Error-Free Communication Restored: Tackling the CRC Error Effectively</u></a></li>
<li><a href="https://extra-tips.techidaily.com/expertise-in-virtual-assessment-vll-of-apps/"><u>Expertise in Virtual Assessment  VLL of Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-battleye-installation-errors-a-comprehensive-tutorial/"><u>Fixes for BattlEye Installation Errors: A Comprehensive Tutorial</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-apple-iphone-14-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From Apple iPhone 14? Heres the Best Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-the-youtube-audio-processor-failure-on-your-windows-10-device/"><u>How to Correct the Youtube Audio Processor Failure on Your Windows 10 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-error-when-your-app-wont-launch-resolving-application-failed-to-initialize-properly-error-code-0xc000007b/"><u>How to Fix the Error When Your App Won't Launch: Resolving 'Application Failed to Initialize Properly (Error Code 0xC000007B)'</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-hidefake-snapchat-location-on-your-honor-x9a-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Honor X9a | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722964125454-how-to-install-and-update-corsair-mouse-programs-click-to-learn-more/"><u>How to Install and Update Corsair Mouse Programs - Click to Learn More!</u></a></li>
<li><a href="https://common-error.techidaily.com/hp-keyboard-malfunctions-5-easy-steps-to-restore-functionality/"><u>HP Keyboard Malfunctions? 5 Easy Steps to Restore Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/iastordatasvc-32-bit-high-cpu-usage-caused-on-windows-11-solved/"><u>IAStorDataSvc (32 Bit) High CPU Usage Caused on Windows 11 [Solved]</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-honor-x7b-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Honor X7b to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-honor-90-lite-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Honor 90 Lite | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-lava-agni-2-5g-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Lava Agni 2 5G via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-google-frp-lock-on-oppo-a18-devices-by-drfone-android/"><u>In 2024, How to Bypass Google FRP Lock on Oppo A18 Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-without-jailbreak-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location without Jailbreak On Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-perfect-synergy-discover-5-superior-webcams-with-sound-tech/"><u>In 2024, Perfect Synergy  Discover 5 Superior Webcams with Sound Tech</u></a></li>
<li><a href="https://common-error.techidaily.com/login-blues-overcoming-keyboard-errors-during-boot-process/"><u>Login Blues: Overcoming Keyboard Errors During Boot Process</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-directx-initialization-troubleshooting-tips-for-a-smooth-launch/"><u>Mastering DirectX Initialization: Troubleshooting Tips for a Smooth Launch</u></a></li>
<li><a href="https://tech-hub.techidaily.com/maximizing-efficiency-the-freelancers-manual-for-using-chatgpt/"><u>Maximizing Efficiency: The Freelancer's Manual for Using ChatGPT</u></a></li>
<li><a href="https://common-error.techidaily.com/nba-2k21-eco-friendly-bug-fixes-and-updates/"><u>NBA 2K21 Eco-Friendly Bug Fixes and Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/optimize-your-pc-reducing-high-resource-usage-of-microsoft-compatibility-telemetry-on-windows-11/"><u>Optimize Your PC: Reducing High Resource Usage of Microsoft Compatibility Telemetry on Windows 11</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-not-working-on-realme-10t-5g-8-solutions-inside-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Not Working On Realme 10T 5G? 8 Solutions Inside | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-solve-your-sims-4-launching-issues-today/"><u>Quick Guide: Solve Your Sims 4 Launching Issues Today!</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/reel-in-the-solution-to-instagram-video-glitches-for-2024/"><u>Reel in the Solution to Instagram Video Glitches for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-rpc-server-deserialization-error-on-your-windows-machine/"><u>Resolving the 'RPC Server Deserialization Error' On Your Windows Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-pressure-related-device-casting-problems-a-step-by-step-solution/"><u>Resolving Windows Pressure-Related Device Casting Problems – A Step by Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/runtime-rejection-in-effect/"><u>Runtime Rejection in Effect</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-dns-server-not-responding-discover-4-easy-fixes-to-restore-connectivity/"><u>Solve 'DNS Server Not Responding': Discover 4 Easy Fixes to Restore Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-print-screen-not-working-errors-in-modern-windows-operating-systems/"><u>Solving Print Screen Not Working Errors in Modern Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-unknown-usb-device-error-with-port-reset-issues-in-windows-10/"><u>Solving the 'Unknown USB Device' Error with Port Reset Issues in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-how-to-fix-your-valorant-games-screen-tearing-problem/"><u>Step-by-Step Guide: How To Fix Your Valorant Game's Screen Tearing Problem</u></a></li>
<li><a href="https://tech-revival.techidaily.com/taming-your-numbers-nightmare-excel-plus-chatgpt-strategies/"><u>Taming Your Numbers Nightmare: Excel + ChatGPT Strategies</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-unlisted-conundrum-dissecting-non-indexed-youtube-videos-for-2024/"><u>The Unlisted Conundrum  Dissecting Non-Indexed YouTube Videos for 2024</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-guide-resolving-wi-fi-connection-issues-on-your-microsoft-surface-pro/"><u>Troubleshooting Guide: Resolving Wi-Fi Connection Issues on Your Microsoft Surface Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolving-ethernet-connectivity-problems-in-windows-10-and-7/"><u>Troubleshooting Tips: Resolving Ethernet Connectivity Problems in Windows 10 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-user-privilege-issues-for-critical-operations-on-windows-versions/"><u>Troubleshooting User Privilege Issues for Critical Operations on Windows Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-optimizing-minecraft-gameplay-and-eliminating-lags/"><u>Ultimate Guide to Optimizing Minecraft Gameplay and Eliminating Lags</u></a></li>
<li><a href="https://common-error.techidaily.com/warframe-update-not-working-heres-how-you-can-successfully-retry-the-process/"><u>Warframe Update Not Working? Here's How You Can Successfully Retry the Process</u></a></li>
<li><a href="https://common-error.techidaily.com/wwe-2k-battlegrounds-troubleshooting-fixing-dx11-feature-level-100-error/"><u>WWE 2K Battlegrounds Troubleshooting - Fixing DX11 Feature Level 10.0 Error</u></a></li>
</ul></div>
