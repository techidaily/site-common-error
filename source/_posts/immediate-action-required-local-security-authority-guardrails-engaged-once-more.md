---
title: "Immediate Action Required: Local Security Authority Guardrails Engaged Once More"
date: 2024-08-31T17:45:44.844Z
updated: 2024-09-01T17:45:44.844Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Immediate Action Required: Local Security Authority Guardrails Engaged Once More"
excerpt: "This Article Describes Immediate Action Required: Local Security Authority Guardrails Engaged Once More"
thumbnail: https://thmb.techidaily.com/fb282d9804e61f76170ce10cf4356b1c491a6302864785ed4f9f0f7226141ae1.jpg
---

## Local Security Defenses Restored – Ensure Safe Operations Today

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
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-seamless-streaming-5-chrome-tools-to-secure-fb-videos/"><u>[New] In 2024, Seamless Streaming  5 Chrome Tools to Secure FB Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-dell-camera-not-working-on-windows/"><u>[SOLVED] Dell Camera Not Working on Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-in-2024-gratuitous-high-quality-ideas-for-profitable-slideshows/"><u>[Updated] In 2024, Gratuitous, High-Quality Ideas for Profitable Slideshows</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-take-your-photography-to-new-heights-with-lightrooms-hdr-capabilities-for-2024/"><u>[Updated] Take Your Photography to New Heights with Lightroom’s HDR Capabilities for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-on-set-questions-answered-quickly/"><u>2024 Approved  On-Set Questions Answered Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-miracast-not-available-hurdle-top-strategies-for-ensuring-device-compatibility-in-2hren/"><u>Beat the 'Miracast Not Available' Hurdle - Top Strategies for Ensuring Device Compatibility in 2Hren</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-woes-no-more-a-step-by-step-fix-for-pairing-problems-on-windows-11-insider-tips/"><u>Bluetooth Woes No More: A Step-by-Step Fix for Pairing Problems on Windows 11 - Insider Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-errors-that-prevent-your-machine-from-booting-up/"><u>Diagnosing and Fixing Errors That Prevent Your Machine From Booting Up</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x8024200d-demystified-effortless-solutions-to-restore-your-windows-update-functionality/"><u>Error 0X8024200D Demystified: Effortless Solutions to Restore Your Windows Update Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-fix-windows-update-failure-error-0x80240017-effectively/"><u>Expert Tips to Fix Windows Update Failure (Error 0X80240017) Effectively</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-that-android-parsing-error-in-8-simple-steps-expert-advice-and-strategies/"><u>Fix That Android Parsing Error in 8 Simple Steps: Expert Advice and Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-activate-directx-11-features-if-your-gpu-does-not-support-them-initially/"><u>How to Activate DirectX 11 Features if Your GPU Does Not Support Them Initially</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-a-directory-name-error-on-your-website/"><u>How to Correct a Directory Name Error on Your Website</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-easily-solve-the-persistent-0x800705b4-problem-on-your-windows-10-system/"><u>How to Easily Solve the Persistent 0X800705b4 Problem on Your Windows 10 System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-discontinued-shockwave-flash-problem-on-google-chrome/"><u>How to Fix the Discontinued Shockwave Flash Problem on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-error-1053-service-failure-to-start-promptly-on-your-pc/"><u>How to Resolve 'Error 1053: Service Failure to Start Promptly' On Your PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-maximizing-collaboration-zoom-session-setup-and-management/"><u>In 2024, Maximizing Collaboration  Zoom Session Setup and Management</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-double-edged-sword-of-virtual-reality/"><u>In 2024, The Double-Edged Sword of Virtual Reality</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-the-dark-we-trust-iphone-photography-for-2024/"><u>In the Dark We Trust, iPhone Photography for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/lullaby-movies-assessment-and-overview-for-2024/"><u>Lullaby Movies Assessment & Overview for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-twitch-stability-in-depth-fixes-for-overcoming-error-4000/"><u>Mastering Twitch Stability: In-Depth Fixes for Overcoming Error 4000</u></a></li>
<li><a href="https://common-error.techidaily.com/minecraft-network-problems-heres-how-you-can-restore-lan-play-smoothly/"><u>Minecraft Network Problems? Here's How You Can Restore LAN Play Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-initialization-woes-fixing-network-connection-in-dragon-ball-fighterz/"><u>Overcoming Initialization Woes: Fixing Network Connection in Dragon Ball FighterZ</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-10-update-freeze-expert-solutions-to-restart-your-system-effortlessly/"><u>Overcoming Windows 10 Update Freeze: Expert Solutions to Restart Your System Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-how-to-resolve-logitech-keyboard-malfunction/"><u>Quick Solutions: How To Resolve Logitech Keyboard Malfunction</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-network-disconnection-glitches-in-monster-hunter-world-for-pc/"><u>Resolving Network Disconnection Glitches in Monster Hunter World for PC</u></a></li>
<li><a href="https://common-error.techidaily.com/restarting-your-night-shift-feature-on-the-latest-windows-operating-system/"><u>Restarting Your Night Shift Feature on the Latest Windows Operating System</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-tecno-spark-10-5g-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Tecno Spark 10 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-for-microsoft-print-to-pdf-failure-on-windows-1011-computers/"><u>Solution Guide for Microsoft Print to PDF Failure on Windows 10/11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-windows-resource-protection-unable-to-begin-fixing-files-error/"><u>Solution Steps for 'Windows Resource Protection' Unable To Begin Fixing Files Error</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-addressing-windows-11s-unresponsive-night-light-feature/"><u>Solution Steps: Addressing Windows 11'S Unresponsive Night Light Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-the-windows-camera-malfunction-error-code-0xa00f4292/"><u>Step-by-Step Solution for the Windows Camera Malfunction: Error Code 0xA00F4292</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-hp-laptop-usb-connectivity-issues/"><u>Step-by-Step Solutions for HP Laptop USB Connectivity Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-repairing-the-0x8024402c-windows-update-issue-resolved/"><u>Step-by-Step Solutions for Repairing the 0X8024402C Windows Update Issue [Resolved]</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-excessive-disk-load-by-disabling-mst-in-windows-11-for-smoother-performance/"><u>Tackling Excessive Disk Load by Disabling MST in Windows 11 for Smoother Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/the-end-of-an-era-unreal-engine-and-d3d/"><u>The End of an Era: Unreal Engine and D3D</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-object-enumeration-failed-problem-in-windows-nplus1-setup-expert-advice-solved/"><u>Troubleshooting the Object Enumeration Failed Problem in Windows N+1 Setup – Expert Advice [Solved]</u></a></li>
</ul></div>