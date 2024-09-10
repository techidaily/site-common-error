---
title: Dealing with High CPU Usage by MsMpEng.exe in Windows 11 - A Comprehensive Guide
date: 2024-09-09T08:55:04.778Z
updated: 2024-09-10T08:55:04.778Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Dealing with High CPU Usage by MsMpEng.exe in Windows 11 - A Comprehensive Guide
excerpt: This Article Describes Dealing with High CPU Usage by MsMpEng.exe in Windows 11 - A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/185bd2e3ee5add750b89a3f134c1fcf3132bd93146cc3a0d22887acdb0a82b64.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130890/7443" target="_top" id="2130890">
  <img src="//a.impactradius-go.com/display-ad/7443-2130890" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130890/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139109/17108" target="_top" id="2139109">
  <img src="//a.impactradius-go.com/display-ad/17108-2139109" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139109/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120867/26400?prodsku=mars" target="_top" id="2120867">
  <img src="//a.impactradius-go.com/display-ad/26400-2120867" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120867/26400?prodsku=mars" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<span id="1374819">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374819.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374819">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374819.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374819%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374819/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115948/19272" target="_top" id="2115948">
  <img src="//a.impactradius-go.com/display-ad/19272-2115948" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115948/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<span id="1993654">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993654.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993654">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993654.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993654%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993654/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<span id="1516072">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1516072.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1516072">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1516072.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1516072%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1516072/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137379/7443" target="_top" id="2137379">
  <img src="//a.impactradius-go.com/display-ad/7443-2137379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2134502/19576" target="_top" id="2134502">
  <img src="//a.impactradius-go.com/display-ad/19576-2134502" border="0" alt="https://techidaily.com" width="672" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2134502/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-info.techidaily.com/new-in-2024-cha-cha-chickadees/"><u>[New] In 2024, Cha-Cha Chickadees</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-alt-tab-not-working/"><u>[Solved] Alt Tab Not Working</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-reset-a-keyboard/"><u>[Solved] How to Reset a Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-the-request-failed-due-to-a-fatal-device-hardware-error/"><u>[SOLVED] The Request Failed Due to a Fatal Device Hardware Error</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-the-fundamentals-of-earnings-on-youtube/"><u>[Updated] 2024 Approved  The Fundamentals of Earnings on YouTube</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-mastering-discord-message-pinning-essentials-for-2024/"><u>[Updated] Mastering Discord  Message Pinning Essentials for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-simplify-curating-create-a-flawless-youtube-playlist-today-for-2024/"><u>[Updated] Simplify Curating  Create a Flawless YouTube Playlist Today for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/corrective-steps-for-accidental-character-inputs-in-typing/"><u>Corrective Steps for Accidental Character Inputs in Typing</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-microsofts-print-to-pdf-not-working-on-windows-11/"><u>Effective Solutions for Microsoft’s Print to PDF Not Working on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-driver-restoration-techniques-a-step-by-step-guide/"><u>Effortless Driver Restoration Techniques - A Step-by-Step Guide</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/effortlessly-organize-and-navigate-your-google-tv-with-our-cutting-edge-home-screen-enhancement/"><u>Effortlessly Organize and Navigate Your Google TV with Our Cutting-Edge Home Screen Enhancement</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-updating-made-simple-overcoming-windows-0x80070652-mishap-with-ease/"><u>Error-Free Updating Made Simple: Overcoming Windows 0X80070652 Mishap with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-overcoming-common-problems-with-your-lenovo-keyboard-not-working/"><u>Expert Advice: Overcoming Common Problems with Your Lenovo Keyboard Not Working</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-overcome-your-laptops-white-or-black-screen-hurdles-easily/"><u>Expert Tips: Overcome Your Laptop's White or Black Screen Hurdles Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-ctrlplusaltplusdel-issues-ultimate-guide-to-restoring-functionality/"><u>Fixing Ctrl+Alt+Del Issues: Ultimate Guide to Restoring Functionality</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/from-screens-to-gifs-the-art-of-converting-vimeo-footage-for-2024/"><u>From Screens to Gifs  The Art of Converting Vimeo Footage for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-alternatives-after-disabling-adobe-shockwave-in-chrome/"><u>How To Enable Alternatives After Disabling Adobe Shockwave in Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-msmpengexe-high-cpu-usage-on-your-windows-10-pc-solution-guide/"><u>How to Fix MsMpEng.exe High CPU Usage on Your Windows 10 PC – Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-release-a-stuck-update-on-legacy-oss-like-windows-seven-latest-techniques-and-solutions-for-better-user-experience-in-the-year-of-our-lord-two-thousa24/"><u>How To Release A Stuck Update On Legacy OSs Like WIndows Seven - Latest Techniques & Solutions For Better User Experience In The Year Of Our Lord Two Thousand And Twenty Four Edition! (Helpful Tips and Troubleshooting Steps.)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-video-not-detected-problem-on-your-screen-a-detailed-walkthrough/"><u>How to Resolve the 'Video Not Detected' Problem on Your Screen - A Detailed Walkthrough</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-full-guide-to-fix-itoolab-anygo-not-working-on-xiaomi-civi-3-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Fix iToolab AnyGO Not Working On Xiaomi Civi 3 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fix-handling-and-repairing-hamachi-errors-effectively/"><u>Master the Fix: Handling and Repairing Hamachi Errors Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-install-a-users-guide-to-correcting-error-0x800f081f-on-net-framework/"><u>Mastering the Install: A User's Guide to Correcting Error 0X800F081F on .NET Framework</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-rdr2-out-of-memory-error-with-this-simple-step-expand-your-page-file/"><u>Overcome 'RDR2 Out Of Memory' Error with This Simple Step – Expand Your Page File</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11-usb-port-issues-a-step-by-step-guide/"><u>Resolving Windows 11 USB Port Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reactivating-custom-settings-that-wont-respond/"><u>Step-by-Step Guide: Reactivating Custom Settings That Won't Respond</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/toms-tech-reviews-in-depth-insights-on-latest-gadgets/"><u>Tom's Tech Reviews: In-Depth Insights on Latest Gadgets</u></a></li>
<li><a href="https://tech-revival.techidaily.com/top-10-methods-seamless-iphone-to-mac-photo-transfer-guide/"><u>Top 10 Methods: Seamless iPhone to Mac Photo Transfer Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-bluetooth-issues-on-windows-7-computers/"><u>Troubleshooting and Fixing Bluetooth Issues on Windows 7 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-minecraft-launch-problems-on-a-windows-pc/"><u>Troubleshooting Guide: Resolving Minecraft Launch Problems on a Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-overcoming-steam-bootstrapper-errors-now-resolved/"><u>Troubleshooting Tips for Overcoming Steam Bootstrapper Errors – Now Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-what-to-do-when-you-encounter-a-missing-module-issue/"><u>Troubleshooting: What to Do When You Encounter a Missing Module Issue</u></a></li>
<li><a href="https://win11.techidaily.com/unlocking-perpetual-inactivity-in-windows-11s-defender-feature/"><u>Unlocking Perpetual Inactivity in Windows 11'S Defender Feature</u></a></li>
<li><a href="https://howto.techidaily.com/why-your-motorola-razr-40-ultra-screen-might-be-unresponsive-and-how-to-fix-it-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Why Your Motorola Razr 40 Ultra Screen Might be Unresponsive and How to Fix It | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/why-your-smartphone-isnt-charging-even-though-its-plugged-in-fixes-and-tips/"><u>Why Your Smartphone Isn’t Charging Even Though It's Plugged In – Fixes & Tips</u></a></li>
</ul></div>
