---
title: "Comprehensive TroubleShooting Guide: Solving the 0X800705B4 Fault During Windows 10 Updates"
date: 2024-09-09T08:50:35.326Z
updated: 2024-09-10T08:50:35.326Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Comprehensive TroubleShooting Guide: Solving the 0X800705B4 Fault During Windows 10 Updates"
excerpt: "This Article Describes Comprehensive TroubleShooting Guide: Solving the 0X800705B4 Fault During Windows 10 Updates"
thumbnail: https://thmb.techidaily.com/ba04435a9c29d64e6b54466059bc1d63c6b55c0d271d3714cb63b43e99d25c0a.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135360/19272" target="_top" id="2135360">
  <img src="//a.impactradius-go.com/display-ad/19272-2135360" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135360/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134229/18498" target="_top" id="2134229">
  <img src="//a.impactradius-go.com/display-ad/18498-2134229" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134229/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098705/14409" target="_top" id="2098705">
  <img src="//a.impactradius-go.com/display-ad/14409-2098705" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098705/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120867/26400?prodsku=mars" target="_top" id="2120867">
  <img src="//a.impactradius-go.com/display-ad/26400-2120867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120867/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123466/16836" target="_top" id="2123466">
  <img src="//a.impactradius-go.com/display-ad/16836-2123466" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123466/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134490/18498" target="_top" id="2134490">
  <img src="//a.impactradius-go.com/display-ad/18498-2134490" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134490/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129738/7443" target="_top" id="2129738">
  <img src="//a.impactradius-go.com/display-ad/7443-2129738" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://common-error.techidaily.com/1723212541975-net-framework-35-installation-woes-heres-how-to-fix-error-code-0x800f081f/"><u>.NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F!</u></a></li>
<li><a href="https://fox-http.techidaily.com/new-in-2024-carving-out-your-place-in-the-design-world/"><u>[New] In 2024, Carving Out Your Place in the Design World</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-quick-fix-for-clearer-focus-in-google-meet/"><u>[New] In 2024, Quick Fix for Clearer Focus in Google Meet</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-in-depth-analysis-the-best-livestreaming-video-tech/"><u>[New] In-Depth Analysis The Best Livestreaming Video Tech</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-snagit-screen-recording-a-guide/"><u>[New] Snagit Screen Recording A Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-essential-tutorial-navigating-mobizen-recording-features/"><u>[Updated] 2024 Approved Essential Tutorial Navigating Mobizen Recording Features</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-engage-and-enthrall-viewers-gaming-via-obs-studio/"><u>[Updated] In 2024, Engage and Enthrall Viewers Gaming via OBS Studio</u></a></li>
<li><a href="https://common-error.techidaily.com/0x800705b4-error-in-windows-update-in-windows-11-solved/"><u>0X800705b4 Error in Windows Update in Windows 11 [Solved]</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-pc-compatible-sony-ps3-mimicry-tools-top-picks/"><u>2024 Approved PC-Compatible Sony PS3 Mimicry Tools Top Picks</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-frustration-expert-tips-for-correcting-the-0xc000012f-error-in-windows-instantly/"><u>Bypassing Frustration: Expert Tips for Correcting the 0Xc000012f Error in Windows Instantly</u></a></li>
<li><a href="https://win11.techidaily.com/customize-your-windows-mouse-experience/"><u>Customize Your Windows Mouse Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/dell-usb-failure-discover-effective-solutions-and-get-it-working-again/"><u>Dell USB Failure? Discover Effective Solutions and Get It Working Again!</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/download-vllo-for-mac-and-uncover-its-competitors/"><u>Download VLLO for Mac and Uncover Its Competitors</u></a></li>
<li><a href="https://common-error.techidaily.com/dragon-ball-fighterz-overcome-previous-network-setup-malfunction/"><u>Dragon Ball FighterZ Overcome Previous Network Setup Malfunction</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-resolve-windows-10-patching-errors-and-enable-seamless-functionality/"><u>Effective Techniques to Resolve Windows 10 Patching Errors and Enable Seamless Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-persistent-keyboard-delay-issues-on-windows-10/"><u>Fixing Persistent Keyboard Delay Issues on Windows 10</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-samsung-galaxy-f15-5g-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Samsung Galaxy F15 5G to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/full-guide-on-mirroring-your-tecno-spark-20-proplus-to-your-pcmac-drfone-by-drfone-android/"><u>Full Guide on Mirroring Your Tecno Spark 20 Pro+ to Your PC/Mac | Dr.fone</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/how-much-footage-does-instagram-allow-for-2024/"><u>How Much Footage Does Instagram Allow for 2024</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-unlock-apple-id-activation-lock-on-apple-iphone-11-pro-max-by-drfone-ios/"><u>How to Unlock Apple ID Activation Lock On Apple iPhone 11 Pro Max?</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-ways-to-track-oppo-f25-pro-5g-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Track Oppo F25 Pro 5G without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-broadcast-battle-obs-against-wirecast/"><u>In 2024, Broadcast Battle OBS Against Wirecast</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-vivo-g2-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Vivo G2</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-easily-through-trending-youtube-comments/"><u>In 2024, Navigating Easily Through Trending YouTube Comments</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-pathway-to-viral-fame-mastering-instagram-with-these-9-essential-strategies/"><u>In 2024, The Pathway to Viral Fame Mastering Instagram with These 9 Essential Strategies</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-video-platform-profiles-vimeo-vs-youtube-comparison/"><u>In 2024, Video Platform Profiles Vimeo vs YouTube Comparison</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-connection-top-tips-for-pairing-airpods-with-windows-11-systems-updated/"><u>Mastering the Connection: Top Tips for Pairing AirPods with Windows 11 Systems (Updated )</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-sds-whisper-declare-them-visible/"><u>Missing SD's Whisper? Declare Them Visible</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-directx-hardware-configuration-errors-for-seamless-graphic-devices/"><u>Overcoming DirectX Hardware Configuration Errors for Seamless Graphic Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-obstacle-of-error-0x800n1ac3-comprehensive-steps-for-cleaning-a-corrupted-volume/"><u>Overcoming the Obstacle of Error 0X800n1AC3: Comprehensive Steps for Cleaning a Corrupted Volume</u></a></li>
<li><a href="https://common-error.techidaily.com/regain-control-of-your-network-with-these-nce-strategies-for-unresponsive-dns-servers/"><u>Regain Control of Your Network with These Nce Strategies for Unresponsive DNS Servers</u></a></li>
<li><a href="https://win11.techidaily.com/remedying-system-call-failure-in-win1011-systems/"><u>Remedying System Call Failure in Win10/11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-laptop-not-charging-on-windows-7-and-10/"><u>Resolved: How to Fix Laptop Not Charging on Windows 7 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-uninstallable-dilemma-a-comprehensive-guide-to-fixing-windows-10-error-code-80240020-fixed/"><u>Resolving the Uninstallable Dilemma: A Comprehensive Guide to Fixing Windows 10 - Error Code 80240020 | [Fixed]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11s-screen-disturbance-a-step-by-step-guide/"><u>Resolving Windows 11'S Screen Disturbance: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-laptops-stuck-keys-problem-across-various-windows-platforms/"><u>Solve Your Laptop's Stuck Keys Problem Across Various Windows Platforms!</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-troubleshooting-and-fixing-a-nonfunctional-shift-key/"><u>Solved: Troubleshooting and Fixing a Nonfunctional Shift Key</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-the-unresponsive-night-light-feature-in-windows-10-and-11/"><u>Troubleshooting Guide: Fixing the Unresponsive Night Light Feature in Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-issues-when-the-steam-store-wont-load/"><u>Troubleshooting Guide: Resolving Issues When The Steam Store Won't Load</u></a></li>
<li><a href="https://common-error.techidaily.com/unknown-usb-device-device-descriptor-request-failed-solved/"><u>Unknown USB Device (Device Descriptor Request Failed) [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/why-does-my-pc-freeze-on-windows-7-essential-fixes-to-keep-your-system-running-smoothly/"><u>Why Does My PC Freeze on Windows 7? Essential Fixes to Keep Your System Running Smoothly</u></a></li>
</ul></div>
