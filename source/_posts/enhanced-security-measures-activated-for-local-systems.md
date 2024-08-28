---
title: Enhanced Security Measures Activated for Local Systems
date: 2024-08-27T13:40:31.886Z
updated: 2024-08-28T13:40:31.886Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Enhanced Security Measures Activated for Local Systems
excerpt: This Article Describes Enhanced Security Measures Activated for Local Systems
thumbnail: https://thmb.techidaily.com/e85743b34dfe1708fd7baeaabbf4be530a9d0acc972c34955c94cad23467f1e0.jpg
---

## Critical LSA Shield Fully Operational: Revamp Your System's Local Security Today

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

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803115/14559" target="_top" id="1803115"><img src="//a.impactradius-go.com/display-ad/14559-1803115" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803115/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=39694080&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/nbr/fire/Screenshot_1red_gb.jpg" border="0">Nero Burning ROM:
The ultimate burning program for all your needs!</a>
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-iphone-slow-motion-shooting-essentials/"><u>[New] 2024 Approved  IPhone Slow Motion Shooting Essentials</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-facebooks-best-eight-free-link-collector-tools-for-2024/"><u>[New] Facebook's Best  Eight FREE Link Collector Tools for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-obs-game-capture-black-screen-issue/"><u>[SOLVED] OBS Game Capture Black Screen Issue</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-2024-approved-the-spectacular-journey-of-q500s-4k/"><u>[Updated] 2024 Approved  The Spectacular Journey of Q500's 4K</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-how-to-recover-my-eyes-only-pictures-on-snapchat/"><u>[Updated] In 2024, How To Recover My Eyes Only Pictures On Snapchat</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-rotation-producer-series/"><u>2024 Approved  Rotation Producer Series</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-failed-steam-update-downloads-a-step-by-step-tutorial/"><u>Diagnosing & Fixing Failed Steam Update Downloads - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/end-of-buffering-woes-ultimate-fix-guide-for-kodi-users/"><u>End of Buffering Woes: Ultimate Fix Guide for Kodi Users</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-tackling-and-solving-power-surges-in-hub-terminals/"><u>Expert Advice for Tackling and Solving Power Surges in Hub Terminals</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-restore-microphone-functionality-in-the-latest-windows-11-update/"><u>Expert Tips to Restore Microphone Functionality in the Latest Windows 11 Update</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-resolving-the-critical-windows-update-problem-0x80070490-quickly/"><u>Expert Tips: Resolving the Critical Windows Update Problem 0X80070490 Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-bluetooth-missing-from-windows-device-manager/"><u>Fix Guide: Bluetooth Missing From Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-unresolved-nvidia-setup-mishaps/"><u>Fix: Unresolved NVIDIA Setup Mishaps</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-connection-hitch-for-dragon-ball-fighterz-players/"><u>Fixing the Connection Hitch for Dragon Ball FighterZ Players</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-installation-glitches-for-origin-platform-gaming-titles/"><u>Guide to Fixing Installation Glitches for Origin Platform Gaming Titles</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-reducing-microsoft-compatibility-telemetrys-impact-on-disk-usage-in-windows-10-systems/"><u>Guide: Reducing Microsoft Compatibility Telemetry's Impact on Disk Usage in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/hassle-free-guide-to-correcting-windows-update-error-code-0x80070eb5/"><u>Hassle-Free Guide to Correcting Windows Update Error Code 0X80070eb5</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-configure-your-drivers-when-you-encounter-set-user-settings-to-driver-failed/"><u>How to Correctly Configure Your Drivers When You Encounter 'Set User Settings To Driver Failed'</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-update-error-code-0x8024002e-easily/"><u>How to Fix Windows Update Error Code 0X8024002E Easily!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-photos-from-samsung-galaxy-a54-5g-by-fonelab-android-recover-photos/"><u>How to Rescue Lost Photos from Samsung Galaxy A54 5G?</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-8-budget-friendly-cross-platform-video-conferencing-tools-revealed/"><u>In 2024, 8 Budget-Friendly, Cross-Platform Video Conferencing Tools Revealed</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-honor-play-40c-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/low-cpu-strategies-for-streamlined-operation-of-windows-driver-foundation-components/"><u>Low-CPU Strategies for Streamlined Operation of Windows Driver Foundation Components</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/obs-screen-recorder-review-for-2024/"><u>OBS Screen Recorder Review for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202981193-operating-system-not-found-or-missing-operating-system-error-fixed/"><u>Operating System Not Found Or Missing Operating System Error Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-crc-faults-in-your-data-transmission-now-solved/"><u>Overcoming CRC Faults in Your Data Transmission - Now Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-display-issues-missing-touchpad-and-hardware-buttons-functionality/"><u>Resolving Display Issues: Missing Touchpad and Hardware Buttons Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-installation-issues-with-windows-11-version-1607-updates/"><u>Solving Installation Issues with Windows 11 Version 1607 Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-scroll-pad-issues-in-windows-11-for-enhanced-user-experience/"><u>Step-by-Step Guide to Fix Scroll Pad Issues in Windows 11 for Enhanced User Experience</u></a></li>
<li><a href="https://windows11.techidaily.com/top-windows-techniques-for-enjoying-high-definition-adventures-with-scummvm/"><u>Top Windows Techniques for Enjoying High-Definition Adventures with ScummVM</u></a></li>
<li><a href="https://common-error.techidaily.com/triumph-over-tech-fixing-windows-inability-to-locate-matching-printer-drivers/"><u>Triumph Over Tech: Fixing Windows' Inability to Locate Matching Printer Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-eliminate-recurring-system-lockups-on-your-laptop-or-desktop/"><u>Troubleshoot and Eliminate Recurring System Lockups on Your Laptop or Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-excessive-cpu-usage-by-microsofts-antivirus-msmpengexe-on-windows-11-learn-how-to-resolve/"><u>Troubleshooting Excessive CPU Usage by Microsoft's Antivirus (MsMpEng.exe) on Windows 11 - Learn How to Resolve</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211075518-troubleshooting-techniques-for-windows-11-non-shutting-desktops-solutions/"><u>Troubleshooting Techniques for Windows 11 Non-Shutting Desktops - Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixing-non-detectable-usb-drives-effortlessly/"><u>Troubleshooting Tips: Fixing Non-Detectable USB Drives Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-usb-success-stories-overcoming-port-reset-failed-hurdles-on-your-windows-11-machine/"><u>Unlocking USB Success Stories: Overcoming 'Port Reset Failed' Hurdles on Your Windows 11 Machine</u></a></li>
</ul></div>
