---
title: Guide to Activate Windows Hello Security on Non-Compatible Devices Running Windows 10
date: 2024-09-27T18:30:38.101Z
updated: 2024-10-01T17:36:41.177Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Guide to Activate Windows Hello Security on Non-Compatible Devices Running Windows 10
excerpt: This Article Describes Guide to Activate Windows Hello Security on Non-Compatible Devices Running Windows 10
thumbnail: https://thmb.techidaily.com/4d82cc5d4830160f77be1be23b3b0d5c8cbc630ac82437e197dd592c77a4c46e.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047361/19272" target="_top" id="2047361">
  <img src="//a.impactradius-go.com/display-ad/19272-2047361" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Method 1: Using Group Policy Editor

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) Type **gpedit.msc**  and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279bde5ee8d.png)

**Note:**  If you cannot find gpedit.msc on your Windows 10,[here is the method to got it.](https://tools.techidaily.com/drivereasy/download/)
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``
 3) Go to **Computer Configuration** \> **Administrative** **Templates** \>**Windows Components** \> **Data Collection and Preview Builds** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``

 5) Select **Disabled** , then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279d1cdc304.jpg)

 6) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.  
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` `` `
` `
` `
` `
` `
` `
` `
` `
` `
`

### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943648/22993" target="_top" id="1943648">
  <img src="//a.impactradius-go.com/display-ad/22993-1943648" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123732/7443" target="_top" id="2123732">
  <img src="//a.impactradius-go.com/display-ad/7443-2123732" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123732/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135404/19272" target="_top" id="2135404">
  <img src="//a.impactradius-go.com/display-ad/19272-2135404" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135404/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4) Reboot your Windows 10 PC.

5) On your keyboard, press the **Ctrl**  +**Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

 **Note:** If you can’t find gpedit.msc on your Windows 10 computer, here’s how you can get it: 1\. Download gpedit.msc(Group Policy Editor) from Internet  
 2\. When it’s done, Go to C:\\Windows\\SysWOW64, and copy the followings:  
 folders: GroupPolicy  
 GroupPolicyUsers  
 gpedit.msc(console document)  
 3\. Paste them in the following locations:  
 C:\\Windows\\System  
 C:\\Windows\\System32

 Hopefully this article could help you fix the problem. Feel free to comment below with your own experiences.

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
<li><a href="https://fox-http.techidaily.com/new-in-2024-dynamic-visual-storytelling-integrating-luts-into-spark-ar-projects/"><u>[New] In 2024, Dynamic Visual Storytelling Integrating LUTs Into Spark AR Projects</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-the-mobile-way-to-youtube-fame-streamlined-channel-creation-process/"><u>[Updated] In 2024, The Mobile Way to YouTube Fame Streamlined Channel Creation Process</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-a-step-by-step-guide-to-utilizing-bandicams-capture-feature/"><u>2024 Approved A Step-by-Step Guide to Utilizing Bandicam's Capture Feature</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/additional-tips-about-sinnoh-stone-for-apple-iphone-12-pro-drfone-by-drfone-virtual-ios/"><u>Additional Tips About Sinnoh Stone For Apple iPhone 12 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-for-a-non-responsive-igfxem-processor-chip-a-step-by-step-guide/"><u>DIY Fixes for a Non-Responsive Igfxem Processor Chip – A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-resolving-problems-with-the-lenovo-fingerprint-authentication-feature/"><u>Expert Guide: Resolving Problems with the Lenovo Fingerprint Authentication Feature</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-repair-your-broken-obs-microphone-expert-solutions-and-tips-updated/"><u>How to Repair Your Broken OBS Microphone - Expert Solutions and Tips (Updated )</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-usb-port-functionality-on-your-windows-10-or-11-pc/"><u>How to Restore USB Port Functionality on Your Windows 10 or 11 PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-vivo-s17t-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Vivo S17t Phone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-from-snap-to-stunning-photo-editing-secrets/"><u>In 2024, From Snap to Stunning Photo Editing Secrets</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-samsung-galaxy-a15-4g-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Samsung Galaxy A15 4G to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-youtube-marketing-boosted-by-free-downloadable-templates/"><u>In 2024, YouTube Marketing Boosted by Free Downloadable Templates</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-malfunctions-resolve-non-working-keys-in-windows-10-and-11-quickly/"><u>Keyboard Malfunctions? Resolve Non-Working Keys in Windows 10 and 11 Quickly!</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-mobile-hotspot-connectivity-using-usb-tethering-on-windows-11/"><u>Mastering Mobile Hotspot Connectivity Using USB Tethering on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-performance-how-to-fix-excessive-cpu-usage-from-wudfhostexe-in-windows-11/"><u>Optimizing Performance: How to Fix Excessive CPU Usage From WUDFHost.exe in Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/recmaster-screen-recorder-review-2023-for-2024/"><u>Recmaster Screen Recorder Review 2023 for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-stuck-on-configuration-issue-quick-guide-for-windows-setup/"><u>Solve Your Stuck on Configuration Issue - Quick Guide for Windows Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-compliance-gap-in-tactile-display-resolved/"><u>SOLVED: Compliance Gap in Tactile Display Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-wow-performance-problems-a-step-by-step-guide/"><u>Solving 'WoW' Performance Problems: A Step-by-Step Guide</u></a></li>
</ul></div>

