---
title: .NET Framework 3.5 Trouble? Here's How to Fix Error Code 0X800F081F During Installation
date: 2024-10-06T04:45:40.851Z
updated: 2024-10-06T17:11:32.362Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes .NET Framework 3.5 Trouble? Here's How to Fix Error Code 0X800F081F During Installation
excerpt: This Article Describes .NET Framework 3.5 Trouble? Here's How to Fix Error Code 0X800F081F During Installation
thumbnail: https://thmb.techidaily.com/dc8c23798056f26fbb4ba042d36186a35f13e6ccd93d9efde90962c264b99c13.jpg
---

## WinUpdate Trouble? Here's How to Fix Error 0X80240017 for Good

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137207/26400" target="_top" id="2137207">
  <img src="//a.impactradius-go.com/display-ad/26400-2137207" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137207/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1983473">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983473.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983473">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983473.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983473%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983473/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/new-21-edition-synopsis-unraveling-the-future-of-online-betting-with-vegas-pro-for-2024/"><u>[New] '21 Edition Synopsis – Unraveling the Future of Online Betting with Vegas Pro for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-in-2024-engaging-verbal-communicator-study-part-8/"><u>[New] In 2024, Engaging Verbal Communicator Study, Part 8</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-dealing-with-download-timeouts-on-the-web/"><u>Comprehensive Solutions for Dealing with Download Timeouts on the Web</u></a></li>
<li><a href="https://media-tips.techidaily.com/diy-steps-transform-your-computer-into-a-cost-free-airplay-media-server-for-ios-devices/"><u>DIY Steps: Transform Your Computer Into a Cost-Free AirPlay Media Server for iOS Devices</u></a></li>
<li><a href="https://hardware-help.techidaily.com/free-downloads-setup-your-logitech-racing-wheel-on-pc-compatible-with-win-7-8-and-10/"><u>Free Downloads: Setup Your Logitech Racing Wheel on PC – Compatible with Win 7, 8 & 10</u></a></li>
<li><a href="https://vp-tips.techidaily.com/gratuit-konverteren-van-aac-naar-mp4-online-movavi-de-beste-oplossing/"><u>Gratuit Konverteren Van AAC Naar MP4 Online: Movavi De Beste Oplossing</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209911636-how-to-do-a-clean-install-of-windows-10-quickly-and-easily/"><u>How to Do a Clean Install of Windows 10, Quickly and Easily</u></a></li>
<li><a href="https://extra-resources.techidaily.com/how-to-easily-and-quickly-draw-on-photos-app-in-windows-11/"><u>How to Easily and Quickly Draw on Photos App in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-to-your-broken-backspace-key-on-a-pc-or-mac/"><u>How to Restore Functionality to Your Broken Backspace Key on a PC or Mac</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-samsung-galaxy-z-fold-5-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Samsung Galaxy Z Fold 5 Without PUK Codes</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-fast-track-to-1000-subscribers-in-youtube-landscape/"><u>In 2024, Fast-Track To 1,000 Subscribers in Youtube Landscape</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some Pro Tips for Pokemon Go PvP Battles On ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-defender-and-system-file-checker-hurdles-a-step-by-estep-guide/"><u>Overcoming Windows Defender and System File Checker Hurdles: A Step-by-eStep Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/restart-your-computer/"><u>Restart Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-your-bluetooth-connection-effective-solutions-for-the-unresponsive-issue/"><u>Restore Your Bluetooth Connection: Effective Solutions for the Unresponsive Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-quick-jump-feature-in-windows-11-explore-stop-scroll-bar-rushing-to-top/"><u>Solving the Quick Jump Feature in Windows 11 Explore - Stop Scroll Bar Rushing to Top</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-when-your-lenovo-mouse-pad-fails-on-windows-windows-11-8-and-7/"><u>Step-by-Step Fixes for When Your Lenovo Mouse Pad Fails on Windows [Windows 11, 8 & 7]</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-repairing-an-unsupported-or-absent-operating-system-error/"><u>The Ultimate Guide to Repairing an Unsupported or Absent Operating System Error</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/top-picks-the-best-family-friendly-films-streaming-on-amazon-prime-video-this-july/"><u>Top Picks: The Best Family-Friendly Films Streaming on Amazon Prime Video This July</u></a></li>
</ul></div>

