---
title: How to Fix Excessive Disk Space Consumption by MS Compatibility Telemetry on Win 10
date: 2024-09-04T20:24:56.192Z
updated: 2024-09-05T20:24:56.192Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Excessive Disk Space Consumption by MS Compatibility Telemetry on Win 10
excerpt: This Article Describes How to Fix Excessive Disk Space Consumption by MS Compatibility Telemetry on Win 10
thumbnail: https://thmb.techidaily.com/c16b1e731514b90b733ef5726536377276b9f0da4bb0ae7f591c4a5f178d3c77.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

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

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

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

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

<!-- affiliate ads begin -->
<span id="1484963">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1484963.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1484963">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1484963.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1484963%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1484963/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886019/19272" target="_top" id="1886019">
  <img src="//a.impactradius-go.com/display-ad/19272-1886019" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886019/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-action-sequels-the-best-games-like-grand-theft-auto/"><u>[New] 2024 Approved  Action Sequels  The Best Games Like Grand Theft Auto</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-end-scene-excellence-your-guide-to-yt-outro-mastery/"><u>[New] 2024 Approved  End Scene Excellence  Your Guide to YT Outro Mastery</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-building-a-brand-in-the-metaverse-ecosystem/"><u>[New] Building a Brand in the Metaverse Ecosystem</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-interactive-stories-in-real-time-with-fb-screen-features/"><u>[Updated] In 2024, Interactive Stories in Real-Time with FB Screen Features</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-incorporating-jump-cuts-for-smoother-edits-for-2024/"><u>[Updated] Incorporating Jump Cuts for Smoother Edits for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-technique-to-implement-youtube-playlists-smoothly-into-web-pages/"><u>2024 Approved  Technique to Implement YouTube Playlists Smoothly Into Web Pages</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-ultimate-black-battery-compatibility-with-gopro-hero5/"><u>2024 Approved  Ultimate Black Battery Compatibility with GoPro Hero5</u></a></li>
<li><a href="https://common-error.techidaily.com/best-fixes-for-audio-services-not-responding-windows-11/"><u>Best Fixes for Audio Services Not Responding Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-frustration-solved-restoring-functionality-between-keyboard-and-computer/"><u>Bluetooth Frustration Solved: Restoring Functionality Between Keyboard and Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/critical-windows-update-features-now-fixed-and-operational/"><u>Critical Windows Update Features Now Fixed and Operational</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-restore-connection-with-external-media-on-a-windows-machine/"><u>Effective Strategies to Restore Connection with External Media on a Windows Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-gaming-experience-with-fixed-xbox-one-console/"><u>Enhanced Gaming Experience with Fixed Xbox One Console</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-repairing-the-aw-snap-mishap-in-chrome/"><u>Expert Advice on Repairing the 'Aw, Snap!' Mishap in Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-keyboard-not-typing-issue-on-windows-11-7-and-8/"><u>Fix Keyboard Not Typing Issue on Windows 11, 7 & 8</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-disappearing-bluetooth-icon-tips-for-windows-11-users/"><u>Fixing a Disappearing Bluetooth Icon – Tips for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-sound-settings-how-to-restore-volume-control/"><u>Fixing Windows 11 Sound Settings: How To Restore Volume Control</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-vivo-s17e-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Vivo S17e FRP Locks</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-0xc000012f-error-in-windows-easily/"><u>How to Fix 0Xc000012f Error in Windows Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-your-laptop-stuck-at-plugged-in-but-not-charging-situation-in-windows-7-or-10/"><u>How to Resolve Your Laptop Stuck at Plugged In but Not Charging Situation in Windows 7 or 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-windows-11-display-from-flickering-solutions-and-tips/"><u>How to Stop Windows 11 Display From Flickering: Solutions and Tips</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-data-from-oppo-a58-4g-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Data from Oppo A58 4G to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-a-roadmap-to-reigning-in-the-realm-of-social-media-management-smm/"><u>In 2024, A Roadmap to Reigning in the Realm of Social Media Management (SMM)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-asus-rog-phone-7-ultimate-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Asus ROG Phone 7 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-sharpfocusx7-size-your-photography-right/"><u>In 2024, SharpFocusX7  Size Your Photography Right</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-the-science-of-captivating-youtube-thumbnails/"><u>In 2024, The Science of Captivating YouTube Thumbnails</u></a></li>
<li><a href="https://fake-location.techidaily.com/is-pgsharp-legal-when-you-are-playing-pokemon-on-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>Is pgsharp legal when you are playing pokemon On Tecno Spark 10 4G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-your-game-launch-tackling-common-origins-setup-problems/"><u>Mastering Your Game Launch: Tackling Common Origins Setup Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207374264-persistent-mouse-disconnection-woes-heres-how-to-keep-your-cursor-steady/"><u>Persistent Mouse Disconnection Woes? Here's How to Keep Your Cursor Steady</u></a></li>
<li><a href="https://location-social.techidaily.com/proven-ways-in-how-to-hide-location-on-life360-for-infinix-zero-5g-2023-turbo-drfone-by-drfone-virtual-android/"><u>Proven Ways in How To Hide Location on Life360 For Infinix Zero 5G 2023 Turbo | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209966933-quick-fixes-for-when-your-device-reports-no-battery-easy-steps-inside/"><u>Quick Fixes for When Your Device Reports No Battery – Easy Steps Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205607496-resolving-eternal-wait-times-during-skyrim-loading-sequences-success/"><u>Resolving Eternal Wait Times During Skyrim Loading Sequences - Success!</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-game-stutters-and-lock-ups-in-fallout-3-on-windows-11/"><u>Resolving Game Stutters and Lock-Ups in Fallout 3 on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-window-10-explore-bar-erratic-top-hook-scrolling-problem/"><u>Resolving the Window 10 Explore Bar Erratic Top-Hook Scrolling Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/silent-shutdown-hardware-emergency/"><u>Silent Shutdown: Hardware Emergency</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-common-problems-with-your-usb-to-hdmi-adapter-fixes-inside/"><u>Solving Common Problems with Your USB to HDMI Adapter (Fixes Inside)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-resolving-the-persistent-windows-10-update-error-0xc1e900208/"><u>Step-by-Step Solution for Resolving the Persistent Windows 10 Update Error 0Xc1e900208</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-excessive-svchostexe-cpu-load-in-windows-11/"><u>Step-by-Step Solutions for Excessive Svchost.exe CPU Load in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-the-problem-of-automatic-mouse-shifting/"><u>Tackling the Problem of Automatic Mouse Shifting</u></a></li>
<li><a href="https://common-error.techidaily.com/the-simplest-way-to-correct-the-windows-update-failure-error-0x80070652/"><u>The Simplest Way to Correct the Windows Update Failure (Error 0X80070652)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-random-computer-turnoffs-tips-for-a-stable-system/"><u>Troubleshooting Random Computer Turnoffs: Tips for a Stable System</u></a></li>
</ul></div>
