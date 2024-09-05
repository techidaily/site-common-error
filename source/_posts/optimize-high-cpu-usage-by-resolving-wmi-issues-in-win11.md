---
title: Optimize High CPU Usage by Resolving WMI Issues in Win11
date: 2024-09-04T20:17:24.874Z
updated: 2024-09-05T20:17:24.874Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Optimize High CPU Usage by Resolving WMI Issues in Win11
excerpt: This Article Describes Optimize High CPU Usage by Resolving WMI Issues in Win11
thumbnail: https://thmb.techidaily.com/8b677f86d933a2dc57f7b5d236aa4e6146da7e283f8be4d58f50e47e9bc2eba3.jpg
---

## Solving MsMpEng.exe High CPU Usage Issue on Windows 10 - Fixed

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037475/7443" target="_top" id="2037475">
  <img src="//a.impactradius-go.com/display-ad/7443-2037475" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934142/19272" target="_top" id="1934142">
  <img src="//a.impactradius-go.com/display-ad/19272-1934142" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934142/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902324/19272" target="_top" id="1902324">
  <img src="//a.impactradius-go.com/display-ad/19272-1902324" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902324/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Want us to fix the problem for you?

 If the fix above didn’t work, and you don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is **[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

 That’s it – top 3 fixes for your **MsMpEng.exe-eating-up-too-much-CPU-in-Windows 10** problem. Hope this helps and feel free to comment below if you have any further questions. 🙂

* [high CPU](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-the-complete-blueprint-record-whatsapp-conversations-effectively/"><u>[New] In 2024, The Complete Blueprint  Record WhatsApp Conversations Effectively</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-unlock-facebook-potential-with-effective-engagement-strategies/"><u>[New] Unlock Facebook Potential with Effective Engagement Strategies</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-redefining-the-silver-screen-virtual-reality-cinema/"><u>[Updated] 2024 Approved  Redefining the Silver Screen  Virtual Reality Cinema</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exclusive-listing-of-best-5-sd-cards-for-gopro-hero-cameras/"><u>[Updated] Exclusive Listing of Best 5 SD Cards for GoPro HERO Cameras</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-video-pioneer-record-pcmac-screens-youtube-uploading-made-easy/"><u>[Updated] Video Pioneer  Record PC/Mac Screens, YouTube Uploading Made Easy</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-leading-the-way-in-affordable-video-conferencing-technology/"><u>2024 Approved  Leading the Way in Affordable Video Conferencing Technology</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206534915-arrow-keys-not-working-check-out-these-effective-repair-strategies/"><u>Arrow Keys Not Working? Check Out These Effective Repair Strategies!</u></a></li>
<li><a href="https://extra-hints.techidaily.com/best-tales-woven-on-airwaves/"><u>Best Tales Woven on Airwaves</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-strategies-to-overcome-driver-power-interruption-on-pcs-running-windows/"><u>Comprehensive Strategies to Overcome Driver Power Interruption on PCs Running Windows</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/die-top-5-strategien-zum-kostenlosen-konvertieren-von-grossen-avi-dateien-zu-mp4/"><u>Die Top 5 Strategien Zum Kostenlosen Konvertieren Von Großen AVI-Dateien Zu MP4</u></a></li>
<li><a href="https://common-error.techidaily.com/efficient-methods-to-address-and-fix-hamachi-service-stopped-alerts/"><u>Efficient Methods to Address and Fix 'Hamachi Service Stopped' Alerts</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-sony-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Sony Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-torrent-that-isnt-downloading-successfully/"><u>How to Fix a Torrent That Isn’t Downloading Successfully?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-common-kodi-software-glitches-solutions-uncovered/"><u>How to Resolve Common Kodi Software Glitches - Solutions Uncovered</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-critical-failures-and-fatal-mistakes-in-call-of-duty-black-ops-4/"><u>How to Resolve Critical Failures & Fatal Mistakes in Call of Duty: Black Ops 4</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-windows-10-bluetooth-not-connecting-expert-tips-and-fixes/"><u>How to Resolve Windows 10 Bluetooth Not Connecting: Expert Tips & Fixes</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-8-withwithout-sim-card-by-drfone-ios/"><u>How to Unlock iPhone 8 with/without SIM Card</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-watch-avchd-mts-video-on-htc-u23-pro-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to watch AVCHD MTS video on HTC U23 Pro?</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-automated-opener-your-srt-files-windows-and-mac/"><u>In 2024, Automated Opener  Your SRT Files, Windows & Mac</u></a></li>
<li><a href="https://audio-editing.techidaily.com/in-2024-tutorials-for-beginners-how-to-add-audio-to-imovie/"><u>In 2024, Tutorials for Beginners How to Add Audio to iMovie</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-how-to-fix-the-persistent-0x80072fde-issue-in-your-windows-10-system/"><u>Mastering How to Fix the Persistent 0X80072FDE Issue in Your Windows 10 System</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205781512-mesothelioma-is-associated-with-asbestos-exposure-and-affects-the-pleura-rather-than-lung-parenchyma/"><u>Mesothelioma Is Associated with Asbestos Exposure and Affects the Pleura Rather than Lung Parenchyma</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-from-footage-to-film-a-mac-users-guide-to-movie-making/"><u>New From Footage to Film A Mac Users Guide to Movie Making</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-resolving-constant-reboots-on-windows-11-a-step-by-step-guide/"><u>Quick Fixes for Resolving Constant Reboots on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-a-corrupted-windows-store-cache/"><u>Resolved: Fixing a Corrupted Windows Store Cache</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-incompatible-device-drivers-on-windows-operating-systems/"><u>Resolved: Incompatible Device Drivers on Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-system-error-5-across-windows-11-7-and-8-comprehensive-guide/"><u>Resolving 'System Error 5' Across Windows 11, 7, and 8 - Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-resource-limitations-that-prevent-completion-of-services/"><u>Resolving Resource Limitations That Prevent Completion of Services</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-binkw32dll-not-found-issue-a-step-by-step-guide/"><u>Resolving the binkw32.dll Not Found Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212020589-revive-your-malfunctioning-huion-pen-fast-and-easy-fixes/"><u>Revive Your Malfunctioning Huion Pen: Fast and Easy Fixes</u></a></li>
<li><a href="https://extra-support.techidaily.com/rise-to-greatness-with-these-10-elevating-films-for-2024/"><u>Rise to Greatness with These 10 Elevating Films for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-detecting-wd-my-passport-ultra-on-non-responsive-windows-devices/"><u>Solution Steps for Detecting WD My Passport Ultra on Non-Responsive Windows Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-the-mystery-why-is-my-dell-usb-port-not-responding/"><u>Solve the Mystery: Why Is My Dell USB Port Not Responding?</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-keyboard-dilemmas-how-to-repair-non-functional-arrow-keys/"><u>Solving Keyboard Dilemmas: How to Repair Non-Functional Arrow Keys</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-the-dxgi-device-freeze-error-with-straightforward-remedies/"><u>Tackling the DXGI Device Freeze Error with Straightforward Remedies</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/the-elite-5-facebooks-novel-innovations-spotlighted-for-2024/"><u>The Elite 5  Facebook's Novel Innovations Spotlighted for 2024</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-vivo-y200e-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Vivo Y200e 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202175401-trouble-with-your-huion-pen-heres-how-to-repair-it-fast/"><u>Trouble with Your Huion Pen? Here's How to Repair It Fast</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-non-functional-microsoft-print-to-pdf-feature-in-latest-windows-os/"><u>Troubleshooting Steps for Non-Functional Microsoft Print to PDF Feature in Latest Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/typing-troubles/"><u>Typing Troubles</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-solving-windows-error-0x8071ac3c-disk-has-issues/"><u>Understanding and Solving Windows Error 0X80#71ac3c 'Disk Has Issues'</u></a></li>
<li><a href="https://win-dash.techidaily.com/update-your-samsung-960-evo-storage-to-new-firmware-in-windows/"><u>Update Your Samsung 960 EVO Storage to New Firmware in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-keyboard-response-slowdown-heres-how-to-address-it-effectively/"><u>Windows 11 Keyboard Response Slowdown? Here's How to Address It Effectively!</u></a></li>
</ul></div>
