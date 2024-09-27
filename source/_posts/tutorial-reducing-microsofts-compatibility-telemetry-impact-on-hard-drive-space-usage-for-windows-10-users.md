---
title: "Tutorial: Reducing Microsoft's Compatibility Telemetry Impact on Hard Drive Space Usage for Windows 10 Users"
date: 2024-09-25T00:23:19.122Z
updated: 2024-09-26T19:06:16.539Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Tutorial: Reducing Microsoft's Compatibility Telemetry Impact on Hard Drive Space Usage for Windows 10 Users"
excerpt: "This Article Describes Tutorial: Reducing Microsoft's Compatibility Telemetry Impact on Hard Drive Space Usage for Windows 10 Users"
thumbnail: https://thmb.techidaily.com/f8511b1b508552460f630419c51d2d616ebcbf19dbd124bdf2e50582d197ea31.jpg
---

## Include Key Search Terms: Ensure that High-Value Keywords (E.g., Microsoft Compatibility Telemetry, High Disk Usage) Are Prominent in Your Title to Improve Visibility and Relevance for Those Searching on Related Topics

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075476/7443" target="_top" id="2075476">
  <img src="//a.impactradius-go.com/display-ad/7443-2075476" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075476/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134501/19576" target="_top" id="2134501">
  <img src="//a.impactradius-go.com/display-ad/19576-2134501" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134501/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398449/3022" target="_top" id="398449">
  <img src="//a.impactradius-go.com/display-ad/3022-398449" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398449/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151870/7443" target="_top" id="2151870">
  <img src="//a.impactradius-go.com/display-ad/7443-2151870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151870/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

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
<a href="https://aligracehair.sjv.io/c/5597632/1880931/19272" target="_top" id="1880931">
  <img src="//a.impactradius-go.com/display-ad/19272-1880931" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880931/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-clearsnap-for-windows-quick-and-clean-shots/"><u>[New] 2024 Approved ClearSnap for Windows Quick & Clean Shots</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-latest-trends-in-360-cameras-a-shoppers-companion/"><u>[New] In 2024, Latest Trends in 360 Cameras – A Shopper's Companion</u></a></li>
<li><a href="https://extra-information.techidaily.com/all-encompassing-outline-googles-podcast-app-at-a-glance/"><u>All-Encompassing Outline Google's Podcast App at a Glance</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-windows-it-tn-side-by-side-error-step-by-step-solutions-for-smooth-operation/"><u>Correcting Windows ˈiːtʃ Tɛn Side-by-Side Error: Step-by-Step Solutions for Smooth Operation</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-and-fixing-the-critical-error-0x800705b4-in-updating-windows-11/"><u>Decoding and Fixing the Critical Error 0X800705b4 in Updating Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-bypass-windows-error-0x800704b3/"><u>How to Bypass Windows Error 0X800704B3</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-usb-multi-functional-gadget-working-with-usb-30-comprehensive-solution/"><u>How to Get Your USB Multi-Functional Gadget Working with USB 3.0 [COMPREHENSIVE SOLUTION]</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-solve-airpods-syncing-problems-on-windows-11-expert-tips-and-tricks-2n4/"><u>How to Solve AirPods Syncing Problems on Windows 11 - Expert Tips & Tricks (2N4)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-sweeten-your-messaging-top-phrases-to-impact-audiences/"><u>In 2024, Sweeten Your Messaging Top Phrases to Impact Audiences</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/learn-how-to-create-compelling-youtube-closures-economically/"><u>Learn How To Create Compelling YouTube Closures Economically</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-oneplus-nord-ce-3-lite-5g-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on OnePlus Nord CE 3 Lite 5G Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/skype-capture-manual-unveiling-the-best-free-and-paid-practices-windowsmac/"><u>Skype Capture Manual Unveiling the Best Free and Paid Practices (Windows/Mac)</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-12-no-cost-defragmentation-utilities-july-2024-edition/"><u>Top 12 No-Cost Defragmentation Utilities: July 2024 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-windows-update-error-code-0x80240017/"><u>Troubleshooting Guide: Fixing Windows Update Error Code 0X80240017</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-usb-recognition-issues-solutions-for-the-persistent-error-message/"><u>Troubleshooting USB Recognition Issues - Solutions for the Persistent Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-updates-solutions-and-fixes/"><u>Troubleshooting Windows Updates: Solutions and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-your-pcs-persistent-freezing-problems/"><u>Ultimate Guide: Resolving Your PC's Persistent Freezing Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-unintended-startups-how-to-stop-your-windows-11-pc-from-auto-booting/"><u>Understanding Unintended Startups: How to Stop Your Windows 11 PC From Auto-Booting</u></a></li>
<li><a href="https://solve-lab.techidaily.com/winxvideo-ai-utilize-gpu-acceleration-for-rapid-video-and-audio-conversion/"><u>WinxVideo AI: Utilize GPU Acceleration for Rapid Video and Audio Conversion</u></a></li>
</ul></div>

