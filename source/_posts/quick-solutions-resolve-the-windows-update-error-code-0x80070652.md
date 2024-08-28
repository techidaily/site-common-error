---
title: "Quick Solutions: Resolve the Window's Update Error Code 0X80070652"
date: 2024-08-27T13:34:09.402Z
updated: 2024-08-28T13:34:09.402Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Quick Solutions: Resolve the Window's Update Error Code 0X80070652"
excerpt: "This Article Describes Quick Solutions: Resolve the Window's Update Error Code 0X80070652"
thumbnail: https://thmb.techidaily.com/61f98fc4d9e1af032d9fc6896b875fde870b9cc610ca573f8ea2783fc3752f47.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095369/26400" target="_top" id="2095369"><img src="//a.impactradius-go.com/display-ad/26400-2095369" border="0" alt="" width="1024" height="512"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095369/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
**net stop wuauserv**  
**net stop cryptSvc**  
**net stop bits**  
**net stop msiserver**  
 **ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old**  
**ren C:\\Windows\\System32\\catroot2 catroot2.old**  
**net start wuauserv**  
**net start cryptSvc**  
**net start bits**  
**net start msiserver**  
**pause**  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-spreadsheet-free-excel-editor-online-offline-1x.93e269d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633281&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/2_premium-icon.png" border="0"> Take advantage of PREMIUM features. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Monthly Membership</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.

 Open Windows Update to download and install updates and it should working now.

 So there you have it – Hope this post helps in resolving your**Windows Update error** **0x80240017** . If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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
<li><a href="https://facebook-video-recording.techidaily.com/new-broadcast-strategies-combining-facebook-and-tv/"><u>[New] Broadcast Strategies  Combining Facebook and TV</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-flashfacts-the-social-media-spark-of-video-tweet/"><u>[New] In 2024, FlashFacts  The Social Media Spark of Video Tweet</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-navigating-instagrams-video-talk-essentials/"><u>[New] In 2024, Navigating Instagram's Video Talk Essentials</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ank-8-real-world-video-promoters-for-success/"><u>[New] Rank 8 Real-World Video Promoters for Success</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-pc-friendly-non-inshot-editing-software/"><u>[Updated] PC-Friendly Non-Inshot Editing Software</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-premier-eco-friendly-camera-systems-for-filmmakers/"><u>[Updated] Premier Eco-Friendly Camera Systems for Filmmakers</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-high-end-uavs-purchase-without-delay/"><u>2024 Approved  High-End UAVs  Purchase Without Delay</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-winning-instagram-viewers-with-impactful-videos/"><u>2024 Approved  Winning Instagram Viewers with Impactful Videos</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/cutting-through-pixels-disable-mouse-acceleration-in-5-simple-steps/"><u>Cutting Through Pixels: Disable Mouse Acceleration in 5 Simple Steps</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cutting-to-the-chase-mastering-zoom-in-videoleap-videos/"><u>Cutting to the Chase  Mastering Zoom in Videoleap Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/directx-error-resolved-master-techniques-to-correct-severe-system-glitches/"><u>DirectX Error Resolved? Master Techniques to Correct Severe System Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-you-encounter-a-missing-binkw32dll-error/"><u>Effective Solutions for When You Encounter a Missing binkw32.dll Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/effortless-pdf-splitting-techniques-3-simple-ways-to-divide-your-pdf-document/"><u>Effortless PDF Splitting Techniques: 3 Simple Ways to Divide Your PDF Document</u></a></li>
<li><a href="https://common-error.techidaily.com/exploring-msda80dll-file-why-preserve-it-for-optimal-performance/"><u>Exploring MSDA80.DLL File: Why Preserve It for Optimal Performance</u></a></li>
<li><a href="https://technical-tips.techidaily.com/exploring-the-extents-of-mobile-roaming-with-t-mobiles-metro-service/"><u>Exploring the Extents of Mobile Roaming with T-Mobile's Metro Service</u></a></li>
<li><a href="https://common-error.techidaily.com/five-effective-techniques-to-repair-windows-10-touchscreen-issues/"><u>Five Effective Techniques to Repair Windows 10 Touchscreen Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-applicationexe-stopped-functioning-error-solutions-and-tips/"><u>Fixes for 'Application.exe Stopped Functioning' Error: Solutions & Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-common-issues-with-torrents-that-wont-download-a-step-by-step-guide/"><u>Fixing Common Issues with Torrents that Won't Download - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-fix-intermittent-screen-freezes-in-windows-os/"><u>How to Diagnose and Fix Intermittent Screen Freezes in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-elevated-cpu-utilization-by-iastordatasvc-on-your-32-bit-windows-11-machine-step-by-step-solution/"><u>How to Fix Elevated CPU Utilization by IAstorDataSvc on Your 32-Bit Windows 11 Machine - Step by Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unable-to-use-desktop-in-systemprofile-on-windows-pcs/"><u>How to Fix Unable to Use Desktop in SystemProfile on Windows PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-11s-hosted-network-startup-problem-solved/"><u>How to Fix Windows 11'S Hosted Network Startup Problem – Solved!</u></a></li>
<li><a href="https://techidaily.com/how-to-install-the-latest-ios-beta-version-on-apple-iphone-x-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Install the Latest iOS Beta Version on Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-unexpected-termination-with-error-1067-on-your-pc-solutions-explored/"><u>How to Stop Unexpected Termination with Error 1067 on Your PC - Solutions Explored</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-reset-your-pc-overcoming-errors-in-windows-10-guide/"><u>How to Successfully Reset Your PC: Overcoming Errors in Windows 10 [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-and-solve-error-message-0x80004005/"><u>How to Troubleshoot and Solve Error Message 0X80004005</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-turn-off-google-location-to-stop-tracking-you-on-realme-c55-drfone-by-drfone-virtual-android/"><u>How to Turn Off Google Location to Stop Tracking You on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-can-i-create-my-pokemon-overworld-maps-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Create My Pokemon Overworld Maps On Apple iPhone X? | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-honor-play-8t-by-drfone-android/"><u>In 2024, How to Bypass FRP from Honor Play 8T?</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-how-to-transfer-everything-from-apple-iphone-15-pro-max-to-iphone-8x11-drfone-by-drfone-transfer-from-ios/"><u>In 2024, How to Transfer Everything from Apple iPhone 15 Pro Max to iPhone 8/X/11 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-fixation-successfully-solving-error-0x8024002e-on-windows-systems/"><u>Mastering Error Fixation: Successfully Solving Error 0X8024002E on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/mitigating-excessive-cpudisk-load-by-ntoskrnlexe/"><u>Mitigating Excessive CPU/Disk Load by ntoskrnl.exe</u></a></li>
<li><a href="https://common-error.techidaily.com/no-delay-just-playtime-in-epic-battle-royale/"><u>No Delay, Just Playtime in Epic Battle Royale</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-is-getting-ready-to-start-freeze-on-your-personal-computer/"><u>Overcoming 'Windows Is Getting Ready to Start' Freeze on Your Personal Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-minecraft-performance-issues-caused-by-windows-graphics-driver-errors-fixed/"><u>Overcoming Minecraft Performance Issues Caused by Windows Graphics Driver Errors - Fixed</u></a></li>
<li><a href="https://win-dash.techidaily.com/quick-steps-to-improve-your-dell-g7-performance-with-driver-updates/"><u>Quick Steps to Improve Your Dell G7 Performance with Driver Updates</u></a></li>
<li><a href="https://driver-install.techidaily.com/reinstalling-and-setting-printer-drivers-correctly/"><u>Reinstalling and Setting Printer Drivers Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-with-microsoft-store-launch-failure/"><u>Resolved: Issue with Microsoft Store Launch Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-trackpad-ultimate-guide-for-fixing-inoperative-touchpad-scrolling-today/"><u>Revive Your Trackpad: Ultimate Guide for Fixing Inoperative Touchpad Scrolling Today</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-troubleshooting-steps-for-an-unresponsive-xbox-one-on-xbox-live-networks/"><u>Solved! Troubleshooting Steps for an Unresponsive Xbox One on Xbox Live Networks</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-hp-laptops-webcam-issue-on-windows-11-a-step-by-step-guide/"><u>Solving Your HP Laptop's Webcam Issue on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-stop-your-laptop-from-randomly-freezing-up/"><u>Step-by-Step Guide to Stop Your Laptop From Randomly Freezing Up</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-enabling-bluetooth-options-in-windows-10-control-panel/"><u>Step-by-Step Guide: Enabling Bluetooth Options In Windows 10 Control Panel</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-solve-error-0x800f0831-easily-via-windows-update-tool/"><u>Step-by-Step Guide: Solve Error 0X800f0831 Easily via Windows Update Tool</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-correcting-windows-driver-power-management-errors/"><u>Step-by-Step Tutorial: Correcting Windows Driver Power Management Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-successfully-complete-your-windows-installations-faster-than-ever-before/"><u>Troubleshoot and Successfully Complete Your Windows Installations Faster Than Ever Before</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-sound-problems-on-your-pc-fixing-no-audio-output-device-installed-error-in-windows/"><u>Troubleshoot Sound Problems on Your PC: Fixing 'No Audio Output Device Installed' Error in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-cannot-start-this-hardware-device-in-windows-11-with-registry-issues-error-19/"><u>Troubleshooting 'Windows Cannot Start This Hardware Device' In Windows 11 with Registry Issues - Error 19</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-0x80071ac3-solutions-for-handling-a-dirty-volume-issue/"><u>Troubleshooting Error 0X80071AC3: Solutions for Handling a 'Dirty Volume' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-when-microsofts-wireless-display-stick-fails-to-link-up-with-windows-10-systems/"><u>Troubleshooting Guide: When Microsoft's Wireless Display Stick Fails to Link Up With Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/wind-down-your-windows-11-without-disturbances/"><u>Wind Down Your Windows 11 Without Disturbances</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-10-pc-reset-errors-a-step-by-step-fix-guide/"><u>Winning Against Windows 10 PC Reset Errors: A Step-by-Step Fix [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-update-error-code-0x80070652-a-user-friendly-guide/"><u>Winning Against Windows Update Error Code 0X80070652: A User-Friendly Guide</u></a></li>
</ul></div>
