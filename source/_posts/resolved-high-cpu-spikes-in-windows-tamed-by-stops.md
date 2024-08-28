---
title: "[RESOLVED] High CPU Spikes in Windows Tamed by Stops"
date: 2024-08-27T13:45:53.592Z
updated: 2024-08-28T13:45:53.592Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [RESOLVED] High CPU Spikes in Windows Tamed by Stops
excerpt: This Article Describes [RESOLVED] High CPU Spikes in Windows Tamed by Stops
thumbnail: https://thmb.techidaily.com/e1ed595629cf0acf64739097580ce2ff94b5302319e9c30131e9c1501214a06c.jpg
---

## Resolving High CPU Usage by MsMpEng.exe on Windows 10 - Solved

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2067133&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/gcb/banScrn.jpg" border="0">Greeting Card Builder</a>
<!-- affiliate ads end -->
 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/solved-usb-to-hdmi-adapter-not-working/"><u>[SOLVED] USB to HDMI Adapter Not Working</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-videographers-guide-to-capturing-sports-competitions-for-2024/"><u>[Updated] Videographer's Guide to Capturing Sports Competitions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/accelerate-your-pcs-shutdown-time-with-these-tips-for-windows-11-users/"><u>Accelerate Your PC's Shutdown Time with These Tips for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/combat-high-cpu-load-from-desktop-window-manager-with-these-5-powerful-windows-1110-tweaks/"><u>Combat High CPU Load From Desktop Window Manager with These 5 Powerful Windows 11/10 Tweaks</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-fixing-inoperative-webcams-on-a-windows-machine/"><u>Comprehensive Solutions for Fixing Inoperative Webcams on a Windows Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-the-silent-microphone-problem-in-your-corsair-hs50-setup/"><u>Diagnosing and Fixing the Silent Microphone Problem in Your Corsair HS50 Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-malfunctioning-usb-hubs-on-windows-11-systems/"><u>Diagnosing and Repairing Malfunctioning USB Hubs on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-the-unsuccessful-deployment-of-windows-10s-version-1903-upgrade/"><u>Effective Solutions for the Unsuccessful Deployment of Windows 10'S Version 1903 Upgrade</u></a></li>
<li><a href="https://win11.techidaily.com/eradicating-ms-store-problem-fix-code-0x0-error-on-pcs/"><u>Eradicating MS Store Problem - Fix Code 0X0 Error on PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-geforce-experience-error-how-to-restore-missing-configuration/"><u>Fixing GeForce Experience Error: How to Restore Missing Configuration</u></a></li>
<li><a href="https://common-error.techidaily.com/haitian/"><u>Haitian</u></a></li>
<li><a href="https://common-error.techidaily.com/how-i-resolved-the-prolonged-shutdown-problem-on-my-windows-10-pc/"><u>How I Resolved the Prolonged Shutdown Problem on My Windows 10 PC</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-exit-android-factory-mode-on-poco-m6-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Exit Android Factory Mode On Poco M6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-microsoft-print-to-pdf-problem-on-windows-11-devices/"><u>How To Troubleshoot 'Microsoft Print to PDF' Problem on Windows 11 Devices</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-oppo-reno-11f-5g-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Oppo Reno 11F 5G Location on Skout | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-navigating-iphone-album-organizing-techniques-and-icloud-uploads/"><u>In 2024, Navigating iPhone Album Organizing Techniques and iCloud Uploads</u></a></li>
<li><a href="https://extra-support.techidaily.com/leverage-smart-organization-in-mematic-for-2024/"><u>Leverage Smart Organization in Mematic for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/no-copyright-worries-10-best-public-domain-image-sites/"><u>No Copyright Worries 10 Best Public Domain Image Sites</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-error-code-39-on-your-dvd-or-cd-rom-a-comprehensive-guide-to-restoring-functionality/"><u>Quick Solutions for Error Code 39 on Your DVD or CD ROM: A Comprehensive Guide to Restoring Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/rapid-remedy-for-missing-logilda/"><u>Rapid Remedy for Missing LogiLDA</u></a></li>
<li><a href="https://common-error.techidaily.com/steam-file-error-resolved-complete-restoration-of-missing-game-content/"><u>Steam File Error Resolved: Complete Restoration of Missing Game Content</u></a></li>
<li><a href="https://common-error.techidaily.com/system-update-alert-do-you-need-a-d3d11-compatible-graphics-card-for-optimal-performance/"><u>System Update Alert: Do You Need a D3D11 Compatible Graphics Card for Optimal Performance?</u></a></li>
<li><a href="https://common-error.techidaily.com/the-expert-solution-when-your-tablet-is-plugged-in-but-not-charging-now-fixed/"><u>The Expert Solution: When Your Tablet Is Plugged In But Not Charging - Now Fixed!</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-restoring-windows-11s-corrupt-data-files/"><u>The Ultimate Guide to Restoring Windows 11'S Corrupt Data Files</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-10-professional-360-degree-cameras/"><u>Top 10 Professional 360 Degree Cameras</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/troubleshooting-steps-for-unopenable-microsoft-word-documents/"><u>Troubleshooting Steps For Unopenable Microsoft Word Documents</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-non-functional-astro-a40-mic-step-by-step-guide-to-a-fix/"><u>Troubleshooting the Non-Functional Astro A40 Mic - Step by Step Guide to a Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-how-to-resolve-driverpowerstatefailure-malfunctions/"><u>Troubleshooting Tips: How to Resolve DRIVER_POWER_STATE_FAILURE Malfunctions</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/why-does-the-pokemon-go-battle-league-not-available-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>Why does the pokemon go battle league not available On Nokia C110 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11s-troublesome-touchscreen-try-these-five-fixes/"><u>Windows 11'S Troublesome Touchscreen? Try These Five Fixes!</u></a></li>
</ul></div>
