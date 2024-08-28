---
title: Troubleshooting Tips for Fixing ShadowPlay Setup Failures on Nvidia GPUs
date: 2024-08-27T13:34:08.230Z
updated: 2024-08-28T13:34:08.230Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Tips for Fixing ShadowPlay Setup Failures on Nvidia GPUs
excerpt: This Article Describes Troubleshooting Tips for Fixing ShadowPlay Setup Failures on Nvidia GPUs
thumbnail: https://thmb.techidaily.com/4285b91a5eec460b353e6cabe3924d845457ea4dd57027d124c1eda481947485.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

<!-- affiliate ads begin -->
<a href="https://store.iobit.com/order/checkout.php?PRODS=1468905&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/184260348236f9554fe9375772ff966e/ascscan_728x90.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->
### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152835&QTY=1&AFFILIATE=108875&CART=1"><img src="https://download.terabyteunlimited.com/banners/ad_800x450_d.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4713565&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Mac： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-acquiring-drone-racing-skills-and-exploring-top-fpv-drones/"><u>[New] In 2024, Acquiring Drone Racing Skills & Exploring Top FPV Drones</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-spotlight-on-8-trusted-youtube-growth-services/"><u>[New] Spotlight on 8 Trusted Youtube Growth Services</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-11-wi-fi-option-not-showing-up/"><u>[SOLVED] Windows 11 Wi-Fi Option Not Showing Up</u></a></li>
<li><a href="https://driver-error.techidaily.com/solved-wsd-print-device-doesnt-have-a-driver/"><u>[SOLVED] WSD Print Device Doesn’t Have a Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-xbox-one-headset-not-working/"><u>[Solved] Xbox One Headset Not Working</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-guide-to-securely-copying-youtube-music-tracks-safely-for-2024/"><u>[Updated] Guide to Securely Copying YouTube Music Tracks Safely for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-insightful-interviews-top-15-recruitment-dialogues/"><u>[Updated] Insightful Interviews - Top 15 Recruitment Dialogues</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-navigating-through-vlc-features-settings-and-troubleshooting-mac/"><u>[Updated] Navigating Through VLC Features, Settings & Troubleshooting (Mac)</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-path-to-youtube-riches-optimal-view-figures-for-monetization-success/"><u>[Updated] Path to YouTube Riches  Optimal View Figures for Monetization Success</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-elevating-edit-quality-the-ultimate-guide-for-obs-studios/"><u>2024 Approved  Elevating Edit Quality  The Ultimate Guide for OBS Studios</u></a></li>
<li><a href="https://win11-tips.techidaily.com/addressing-w11-issues-with-csgo/"><u>Addressing W11 Issues with CS:GO</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212439631-avoid-rough-terrain-limit-driving-over-bumpy-or-uneven-surfaces-that-could-cause-additional-stress-on-your-vehiclecuots-suspension-system/"><u>Avoid Rough Terrain: Limit Driving over Bumpy or Uneven Surfaces that Could Cause Additional Stress on Your Vehicle'cuot;s Suspension System.</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-error-0x887a0006-quickly-easy-step-by-step-repair-techniques-inside/"><u>Beat Error 0X887A0006 Quickly: Easy Step-by-Step Repair Techniques Inside</u></a></li>
<li><a href="https://extra-information.techidaily.com/decoding-the-appeal-what-makes-you-love-filmora-editing/"><u>Decoding the Appeal  What Makes You Love Filmora Editing?</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-solving-hardware-driver-problems-a-guide-to-completing-your-windows-7-installation-without-errors/"><u>Diagnosing and Solving Hardware Driver Problems: A Guide to Completing Your Windows 7 Installation Without Errors</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/mical-embellishments-free-youtube-template-packs/"><u>Economical Embellishments  FREE YouTube Template Packs</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-a-non-working-touchpad-scroll-wheel-on-windows-and-mac/"><u>Effective Fixes for a Non-Working Touchpad Scroll Wheel on Windows and Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-pvpnet-patchers-kernel-stops-functioning/"><u>Effective Fixes for When Your PvP.net Patcher's Kernel Stops Functioning</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-windows-1011-bad-image-errors-a-step-by-step-guide/"><u>Effective Fixes for Windows 10/11 Bad Image Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-correcting-corruption-issues-with-system-files-on-windows-11/"><u>Expert Advice: Correcting Corruption Issues with System Files on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-to-overcoming-wacom-tablet-technical-glitches-and-errors/"><u>Expert Guide to Overcoming Wacom Tablet Technical Glitches and Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-performance-issues-decreasing-desktop-window-managers-cpu-and-gpu-consumption-on-windows-1011/"><u>Fixing Performance Issues: Decreasing Desktop Window Manager's CPU and GPU Consumption on Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-persistent-keyboard-stutter-in-windows-10-operating-system/"><u>Fixing Persistent Keyboard Stutter in Windows 10 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-startup-issues-get-your-windows-based-minecraft-running-again/"><u>Fixing Startup Issues: Get Your Windows-Based Minecraft Running Again</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-stop-code-when-running-32-bit-print-drivers/"><u>Fixing the Issue: Stop Code When Running 32-Bit Print Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-broken-dell-webcam-solutions-and-troubleshooting-steps/"><u>Fixing Your Broken Dell Webcam: Solutions and Troubleshooting Steps</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/forgotten-the-voicemail-password-of-realme-c67-5g-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Realme C67 5G? Try These Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/fuse-rhythms-into-powerpoint-layouts/"><u>Fuse Rhythms Into PowerPoint Layouts</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-cure-your-dell-laptops-black-screen-woes-full-instructional-handbook/"><u>How to Diagnose & Cure Your Dell Laptop's Black Screen Woes: Full Instructional Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-broken-right-click-feature-on-a-mouse-for-windows-10-users/"><u>How to Fix the Broken Right-Click Feature on a Mouse for Windows 10 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-lower-gpu-usage-by-the-desktop-window-manager-in-windows-11-a-step-by-step-tutorial/"><u>How to Lower GPU Usage by the Desktop Window Manager in Windows 11: A Step-by-Step Tutorial</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-contacts-on-iphone-14-4-methods-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Restore Contacts on iPhone 14 (4 Methods) | Stellar</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-motorola-moto-g34-5g-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a Motorola Moto G34 5G Phone that is Locked?</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722974764877-install-updated-amd-radeon-driver-version-on-your-windows-7-pc-today/"><u>Install Updated AMD Radeon Driver Version on Your Windows 7 PC Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/interface-issue-addressed/"><u>Interface Issue Addressed</u></a></li>
<li><a href="https://extra-information.techidaily.com/manipulating-fonts-in-visual-media/"><u>Manipulating Fonts in Visual Media</u></a></li>
<li><a href="https://common-error.techidaily.com/microsoft-compatibility-telemetry-and-high-disk-utilization-issues-solutions-for-win-10-users/"><u>Microsoft Compatibility Telemetry & High Disk Utilization Issues – Solutions for Win 10 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209764696-noisy-playstation-4-heres-how-you-can-silence-the-racket/"><u>Noisy PlayStation 4? Here's How You Can Silence the Racket!</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-ntoskrnlexe-for-better-performance-on-pc/"><u>Optimizing ntoskrnl.exe for Better Performance on PC</u></a></li>
<li><a href="https://win-blog.techidaily.com/pc-gaming-fixes-enjoy-a-smooth-run-with-the-latest-patch-of-wrc-10-by-fia-world-rally-championship/"><u>PC Gaming Fixes: Enjoy a Smooth Run with the Latest Patch of WRC 10 by FIA World Rally Championship</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-to-resolve-your-pcs-ethernet-issues-on-microsoft-operating-systems-windows-11-and-7/"><u>Quick Fixes to Resolve Your PC's Ethernet Issues on Microsoft Operating Systems (Windows 11 & 7)</u></a></li>
<li><a href="https://common-error.techidaily.com/repair-malfunctioning-letter-keys-a-guide-for-windows-10-and-11-keyboard-issues/"><u>Repair Malfunctioning Letter Keys: A Guide for Windows 10 and 11 Keyboard Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-your-windows-10-touchscreen-functionality-with-these-five-remedies/"><u>Restore Your Windows 10 Touchscreen Functionality with These Five Remedies</u></a></li>
<li><a href="https://common-error.techidaily.com/silent-speakers-now-a-tale-of-two-devices/"><u>Silent Speakers, Now a Tale of Two Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-unraveling-the-mystery-of-auto-start-issues-in-your-windows-11-machine/"><u>Solved: Unraveling the Mystery of Auto-Start Issues in Your Windows 11 Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fixing-the-missing-wacom-pen-and-touchpad-driver-issue-on-windows-10/"><u>Step-by-Step Guide: Fixing the Missing Wacom Pen & Touchpad Driver Issue on Windows 10</u></a></li>
<li><a href="https://windows11.techidaily.com/taming-the-typhoon-of-erratic-windows-mouse-wheel/"><u>Taming the Typhoon of Erratic Windows Mouse Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-hack-speeding-up-your-lol-download-dilemma-now-fixed/"><u>The Ultimate Hack: Speeding Up Your LoL Download Dilemma (Now Fixed!)</u></a></li>
<li><a href="https://common-error.techidaily.com/third-monitor-not-detected-heres-the-real-fix/"><u>Third Monitor Not Detected? Here's the Real Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-elevated-cpu-utilization-by-iastordatasvc-in-a-32-bit-windows/"><u>Troubleshooting Elevated CPU Utilization by IAStorDataSvc in a 32-Bit Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-steam-shop-errors-and-restoring-functionality-quickly/"><u>Troubleshooting the Steam Shop Errors and Restoring Functionality Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-display-hiccups-in-windows-11-system/"><u>Understanding and Fixing Display Hiccups in Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-progress-how-to-resolve-frozen-update-states-on-outdated-oss-like-win7-solutions-and-troubleshooting-guide/"><u>Unlocking Progress: How to Resolve Frozen Update States on Outdated OSs Like Win7 (Solutions and Troubleshooting Guide)</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-update-failed-to-install-solved/"><u>Windows 10 Update Failed to Install [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-compatibility-fixing-connectivity-for-microsoft-wireless-display-adapters/"><u>Windows 11 Compatibility: Fixing Connectivity for Microsoft Wireless Display Adapters</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-couldnt-be-installed-error-code-80240020-solved/"><u>Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-update-quandary-breaking-through-when-progress-halts-at-100/"><u>Windows Update Quandary - Breaking Through When Progress Halts at 100%%</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207655767-xbox-one-online-connectivity-issues-heres-your-comprehensive-solution/"><u>Xbox One Online Connectivity Issues? Here's Your Comprehensive Solution</u></a></li>
</ul></div>
