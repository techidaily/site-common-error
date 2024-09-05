---
title: How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS
date: 2024-09-04T20:22:02.768Z
updated: 2024-09-05T20:22:02.768Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS
excerpt: This Article Describes How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS
thumbnail: https://thmb.techidaily.com/e6c7c0aea059b2b9594111c92d9d243c60708ba7355f3daa30e8aeaa265b4225.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975807/19272" target="_top" id="1975807">
  <img src="//a.impactradius-go.com/display-ad/19272-1975807" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975807/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Now try to install Windows Updates now.

After the fixes above, Windows Update should be good to go now.

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
<li><a href="https://eaxpv-info.techidaily.com/new-affordable-options-selecting-the-right-cam-for-your-needs-for-2024/"><u>[New] Affordable Options  Selecting the Right Cam for Your Needs for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-turn-your-vlogs-into-tunes-with-an-insta-mp3-conversion-hack/"><u>[New] In 2024, Turn Your Vlogs Into Tunes with an Insta-Mp3 Conversion Hack</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-ultimate-guide-to-sharper-meeting-experience-with-google/"><u>[New] In 2024, Ultimate Guide to Sharper Meeting Experience with Google</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-navigating-the-world-of-digital-gifs-for-2024/"><u>[New] Navigating the World of Digital GIFs for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-dxgierrordevicehung-easily/"><u>[SOLVED] DXGI_ERROR_DEVICE_HUNG [Easily]</u></a></li>
<li><a href="https://screen-capture.techidaily.com/a-comprehensive-guide-to-ps3-gameplay-recording/"><u>A Comprehensive Guide to PS3 Gameplay Recording</u></a></li>
<li><a href="https://common-error.techidaily.com/adobe-shockwave-and-flash-player-issues-in-google-chrome-solutions/"><u>Adobe Shockwave and Flash Player Issues in Google Chrome - Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/code-blocked-operation-on-hold/"><u>Code Blocked: Operation on Hold</u></a></li>
<li><a href="https://common-error.techidaily.com/cursor-that-wont-quit-learn-how-to-make-it-stop-blinking/"><u>Cursor that Won't Quit? Learn How to Make It Stop Blinking</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203710291-essential-multimedia-drivers-reinstalled-your-pc-is-fully-compatible/"><u>Essential Multimedia Drivers Reinstalled - Your PC Is Fully Compatible!</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guidance-managing-and-repairing-overload-at-port-terminal/"><u>Expert Guidance: Managing and Repairing Overload at Port Terminal</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-handling-and-correcting-your-windows-10-system-restore-errors/"><u>Expert Tips for Handling and Correcting Your Windows 10 System Restore Errors</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/failed-to-play-mp4-movies-with-xiaomi-mix-fold-3-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Failed to play MP4 movies with Xiaomi Mix Fold 3</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-windows-10-mouse-problems-getting-the-right-click-to-work-again/"><u>Fix Windows 10 Mouse Problems: Getting the Right Click to Work Again</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-bluetooth-troubles-visible-now-in-device-manager/"><u>Fix Your Bluetooth Troubles: Visible Now in Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/google-chrome-stuck-heres-how-we-fixed-it-and-ensured-smooth-browsing/"><u>Google Chrome Stuck? Here's How We Fixed It and Ensured Smooth Browsing!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-touchpad-functionality-and-fix-scrolling-on-your-windows-10-device/"><u>How to Restore Touchpad Functionality and Fix Scrolling on Your Windows 10 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-register-missing-classes-on-windows-11-systems/"><u>How to Successfully Register Missing Classes on Windows 11 Systems</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/new-2024-approved-is-virtualdub-still-the-best-choice-a-review-and-comparison-of-top-alternatives/"><u>New 2024 Approved Is Virtualdub Still the Best Choice? A Review and Comparison of Top Alternatives</u></a></li>
<li><a href="https://common-error.techidaily.com/nvidia-web-helper-no-disk-issue-comprehensive-solutions-and-fixes/"><u>Nvidia Web Helper 'No Disk' Issue: Comprehensive Solutions and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-graphic-glitches-in-valorant-a-step-by-step-fix-for-screen-anomalies/"><u>Overcome Graphic Glitches in VALORANT - A Step-by-Step Fix for Screen Anomalies</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premier-playwrights-lair-for-2024/"><u>Premier Playwright's Lair for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-failed-creation-of-a-d3d-vertex-shader-context/"><u>Resolving Failed Creation of a D3D Vertex Shader Context</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10s-persistent-problem-unsuccessful-shutdown-followed-by-unexpected-reboot/"><u>Resolving Windows 10'S Persistent Problem: Unsuccessful Shutdown, Followed by Unexpected Reboot</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-youtube-sound-issues-fixing-the-audio-renderer-bug-in-windows-10/"><u>Resolving YouTube Sound Issues: Fixing the Audio Renderer Bug in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/revived-fix-and-illuminate-your-corsair-keyboard-with-ease/"><u>Revived: Fix & Illuminate Your Corsair Keyboard with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-non-functional-astro-a40-mic-how-to/"><u>Solution Steps for Non-Functional Astro A40 Mic – How To</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-ethernet-connection-problems-in-windows-11-and-7-a-comprehensive-guide/"><u>Solving Ethernet Connection Problems in Windows 11 and 7: A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/solving-the-nero-advrcntr2dll-not-found-issue-a-step-by-step-guide/"><u>Solving the Nero advrcntr2.dll Not Found Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-resolving-mic-issues-with-your-laptop-now-fixed/"><u>Step-by-Step Guide to Resolving Mic Issues with Your Laptop - Now Fixed!</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-guide-updating-your-password-on-the-revamped-x-platform/"><u>Step-by-Step Guide: Updating Your Password on the Revamped X Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-on-correcting-ps4-nat-problems-for-optimal-connectivity/"><u>Step-by-Step Tutorial on Correcting PS4 NAT Problems for Optimal Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210456860-troubleshooting-stuck-personalization-features-solutions-found/"><u>Troubleshooting Stuck Personalization Features: Solutions Found!</u></a></li>
</ul></div>
