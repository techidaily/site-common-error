---
title: Troubleshooting Microsoft's Error 80240020 on Your PC for Successful Windows 11 Setup
date: 2024-08-31T17:44:29.639Z
updated: 2024-09-01T17:44:29.639Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Microsoft's Error 80240020 on Your PC for Successful Windows 11 Setup
excerpt: This Article Describes Troubleshooting Microsoft's Error 80240020 on Your PC for Successful Windows 11 Setup
thumbnail: https://thmb.techidaily.com/3fc4ce39cf32e051d437369f1ad4829a21ac17b8d3ad76e322c0705c64d5daa2.png
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048963/16384" target="_top" id="2048963"><img src="//a.impactradius-go.com/display-ad/16384-2048963" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048963/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296985&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9cea886b9f44a3c2df1163730ab64994/products/copy_nero_burning_rom_cart.png" border="0">
</a>
<!-- affiliate ads end -->
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/2072819/17059" target="_top" id="2072819"><img src="//a.impactradius-go.com/display-ad/17059-2072819" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072819/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296740&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/biu/Nero_BackItUp_Screen_2.webp" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-cheap-microphones-for-youtubers-on-a-budget/"><u>[New] 2024 Approved  Cheap Microphones for Youtubers on a Budget</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/new-engaging-tactics-for-increased-subscriber-count/"><u>[New] Engaging Tactics for Increased Subscriber Count</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-effortless-techniques-crafting-youtube-shorts-images-on-the-fly/"><u>[New] In 2024, Effortless Techniques  Crafting YouTube Shorts Images on the Fly</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-effortlessly-sync-youtube-videos-with-fb-feeds-using-autoplay-mode/"><u>[New] In 2024, Effortlessly Sync YouTube Videos with FB Feeds Using Autoplay Mode</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-fn-keys-on-my-asus-laptop-not-working/"><u>[Solved] Fn Keys on My ASUS Laptop Not Working</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-seamless-shoot-and-stream-perfecting-dslr-broadcasts-from-home-pcsmacs/"><u>[Updated] 2024 Approved  Seamless Shoot & Stream  Perfecting DSLR Broadcasts From Home PCs/Macs</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-best-screenshot-and-recorder-software-for-professors/"><u>[Updated] In 2024, Best Screenshot and Recorder Software for Professors</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-low-cost-pc-screen-grabbing-options-ranked-for-2024/"><u>[Updated] Low-Cost PC Screen Grabbing Options Ranked for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-strategies-to-fast-track-vimeo-content/"><u>[Updated] Strategies to Fast-Track Vimeo Content</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-precise-color-correction-mastery-in-gopro-studio/"><u>2024 Approved  Precise Color Correction Mastery in GoPro Studio</u></a></li>
<li><a href="https://common-error.techidaily.com/a-step-by-step-solution-to-restore-your-windows-11-sound-settings-when-the-volume-wont-respond/"><u>A Step-by-Step Solution to Restore Your Windows 11 Sound Settings When the Volume Won't Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-dns-unresponsive-issues-a-guide-to-fast-fixes-and-solutions/"><u>Addressing 'DNS Unresponsive' Issues: A Guide to Fast Fixes and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/apex-legends-resolving-the-simple-cheating-detector-glitch/"><u>Apex Legends - Resolving the Simple Cheating Detector Glitch</u></a></li>
<li><a href="https://unlock-android.techidaily.com/best-tecno-phantom-v-flip-pattern-lock-removal-tools-remove-android-pattern-lock-without-losing-data-by-drfone-android/"><u>Best Tecno Phantom V Flip Pattern Lock Removal Tools Remove Android Pattern Lock Without Losing Data</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fix-for-non-responsive-lenovo-mouse-pads-on-various-windows-systems/"><u>Comprehensive Fix for Non-Responsive Lenovo Mouse Pads on Various Windows Systems</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ing-historical-wisdom-the-ultimate-student-friendly-channel-list-1-10/"><u>Curating Historical Wisdom  The Ultimate Student-Friendly Channel List (#1-10)</u></a></li>
<li><a href="https://common-error.techidaily.com/deciphering-and-solving-non-writable-errors-to-specified-0x-memory-locations-in-systems/"><u>Deciphering and Solving Non-Writable Errors to Specified 0X Memory Locations in Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/display-compatibility-issue-hdcp-free-screen-resolution/"><u>Display Compatibility Issue: HDCP-Free Screen Resolution</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-the-common-disk-write-error-in-steam-platform/"><u>Effortless Fixes for the Common 'Disk Write Error' In Steam Platform</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/elevate-your-videos-top-rated-ipad-video-editors-for-2024/"><u>Elevate Your Videos Top-Rated iPad Video Editors for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-gaming-experience-on-steam-fixing-installation-and-update-hiccups-swiftly/"><u>Error-Free Gaming Experience on Steam - Fixing Installation and Update Hiccups Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/ftdisk-system-warning-how-incorrect-driver-installation-affects-memory-safety/"><u>FTDisk System Warning: How Incorrect Driver Installation Affects Memory Safety</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-motorola-moto-e13-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Motorola Moto E13 | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/future-of-virtuality-best-metaverse-headsets-ranked/"><u>Future of Virtuality  Best Metaverse Headsets Ranked</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-flash-dead-realme-12-pro-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Realme 12 Pro 5G Safely | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-photos-from-android-gallery-app-on-oneplus-nord-n30-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>How to Recover Deleted Photos from Android Gallery App on OnePlus Nord N30 5G</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-high-end-streaming-gear-for-professionals/"><u>In 2024, High-End Streaming Gear for Professionals</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-change-your-sim-pin-code-on-your-motorola-moto-g23-phone-by-drfone-android/"><u>In 2024, How To Change Your SIM PIN Code on Your Motorola Moto G23 Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-common-problems-with-keyboard-light-features-on-mac-and-windows-devices/"><u>Overcoming Common Problems with Keyboard Light Features on Mac and Windows Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-frozen-updates-on-outdated-operating-systems-latest-solutions-for-users-seeking-assistance-in-the-year-of-our-lord-two-thousand-and-twenty-four-g85/"><u>Overcoming Frozen Updates On Outdated Operating Systems – Latest Solutions for Users Seeking Assistance In The Year Of Our Lord Two Thousand And Twenty Four (Guide, Helpful Tips & Troubleshooting Steps)</u></a></li>
<li><a href="https://common-error.techidaily.com/quickly-restore-missing-bluetooth-on-your-windows-11-pc-with-ease/"><u>Quickly Restore Missing Bluetooth on Your Windows 11 PC with Ease!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/recognizing-suspicious-websites-a-guide-for-detecting-chatgpt-scams/"><u>Recognizing Suspicious Websites: A Guide for Detecting ChatGPT Scams</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-insufficient-system-resources-error-to-fulfill-your-service-needs/"><u>Resolved: Fixing 'Insufficient System Resources' Error to Fulfill Your Service Needs</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-failed-secure-connection-errors-in-mozilla-firefox/"><u>Resolving 'Failed Secure Connection' Errors in Mozilla Firefox</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolving-the-itbm-driver-unavailable-issue-quickly/"><u>Resolving the 'ITBM Driver Unavailable' Issue Quickly</u></a></li>
<li><a href="https://network-issues.techidaily.com/restore-original-screen-vision-order/"><u>Restore Original Screen Vision Order</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-tricks-to-prevent-your-computer-from-going-to-sleep-unexpectedly/"><u>Simple Tricks to Prevent Your Computer From Going To Sleep Unexpectedly</u></a></li>
<li><a href="https://windows11.techidaily.com/smooth-save-experience-top-6-strategies-to-tackle-ppt-errors/"><u>Smooth Save Experience: Top 6 Strategies to Tackle PPT Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-overcoming-opengl-glitches-in-minecraft/"><u>Step-by-Step Fixes for Overcoming OpenGL Glitches in Minecraft</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-when-you-encounter-internet-explorer-has-stopped-working/"><u>Step-by-Step Solutions When You Encounter 'Internet Explorer Has Stopped Working'</u></a></li>
<li><a href="https://common-error.techidaily.com/strategies-for-addressing-the-device-is-not-ready-error-swiftly/"><u>Strategies for Addressing The Device Is Not Ready Error Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207757346-troubleshoot-and-solve-call-of-duty-world-war-iis-persistent-error-code-angs-12320/"><u>Troubleshoot and Solve Call of Duty: World War II's Persistent Error Code Angs 12320</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-non-functional-usb-ports-on-windows-10-and-11/"><u>Troubleshooting and Fixing Non-Functional USB Ports on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-silent-pc-fixing-installed-audio-device-errors-on-windows-11/"><u>Troubleshooting Silent PC: Fixing Installed Audio Device Errors on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-re-enable-your-devices-wireless-features/"><u>Troubleshooting Steps to Re-Enable Your Device's Wireless Features</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-your-ps4s-sound-problems-expert-guide-to-identifying-and-fixing/"><u>Understanding Your PS4's Sound Problems: Expert Guide to Identifying and Fixing</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206539025-unstuck-from-microsoft-store-problems-heres-how-to-open-it-successfully/"><u>Unstuck From Microsoft Store Problems? Here's How to Open It Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211824429-wacom-pen-issues-heres-your-guide-to-fix-it-in-windows-11-and-windows-10/"><u>Wacom Pen Issues? Here's Your Guide to Fix It in Windows 11 and Windows 10</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-nokia-g310-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Nokia G310 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205644040-windows-11-update-why-cant-i-print-to-pdf-with-microsoft-heres-help/"><u>Windows 11 Update: Why Can't I Print to PDF with Microsoft? Here’s Help</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-10-reset-failures-expert-fixes-for-pc-restoration-errors-in-depth-guide/"><u>Winning Against Windows 10 Reset Failures: Expert Fixes for PC Restoration Errors [In-Depth Guide]</u></a></li>
</ul></div>
