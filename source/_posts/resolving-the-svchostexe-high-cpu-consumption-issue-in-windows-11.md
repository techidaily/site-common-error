---
title: Resolving the svchost.exe High CPU Consumption Issue in Windows 11
date: 2024-08-15T11:07:52.353Z
updated: 2024-08-16T11:07:52.353Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving the svchost.exe High CPU Consumption Issue in Windows 11
excerpt: This Article Describes Resolving the svchost.exe High CPU Consumption Issue in Windows 11
thumbnail: https://thmb.techidaily.com/51ab56587e08f47d807c9660276e637958571843dacf99014ff4e035dcf2337d.jpg
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

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793233/19578" target="_top" id="1793233"><img src="//a.impactradius-go.com/display-ad/19578-1793233" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793233/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 1: Prevent Windows Defender from scanning its own folder**

1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Scroll down to the bottom and click**Add or remove exclusions** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4081991&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/wt-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)
<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)
<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851655&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=45152810&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/842ca578342915ccb8ae069595ba7233/products/copy_bootit-ss1_178x139.jpg" border="0">The BootIt Collection covers multi-booting, partitioning, and disk imaging on traditional PC's using the standard BIOS and  newer PC's using UEFI.   The collection includes BootIt Bare Metal (BIBM) for standard BIOS systems and BootIt UEFI (BIU) for UEFI system. 
</a>
<!-- affiliate ads end -->

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=19080710&QTY=1&AFFILIATE=108875&CART=1"><img src="https://smart-seo-tool.com/images/SmartSEOAuditorBox.png" border="0"></a>
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
<li><a href="https://video-capture.techidaily.com/new-videovantage-warriors-for-2024/"><u>[New] VideoVantage Warriors for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-capturing-the-essence-of-facetime-on-facebook-for-2024/"><u>[Updated] Capturing the Essence of FaceTime on Facebook for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-the-art-of-perfection-in-tiktok-production-with-designed-video-templates/"><u>[Updated] In 2024, The Art of Perfection in TikTok Production with Designed Video Templates</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-mastering-pc-tiktok-live-streams-a-step-by-step-guide-for-2024/"><u>[Updated] Mastering PC TikTok Live Streams  A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/address-and-repair-the-infamous-red-screen-error-in-windows-10-system/"><u>Address and Repair the Infamous Red Screen Error in Windows 10 System</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-setup-will-exit-unrecognized-os-message-with-proven-solutions/"><u>Bypass 'Setup Will Exit - Unrecognized OS' Message with Proven Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/ce-34878-0-bugs-in-ps4-heres-a-step-by-step-solution/"><u>CE-34878-0 Bugs in PS4? Here's a Step-by-Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-unexpected-boot-sequences-for-windows-11-systems/"><u>Diagnosing Unexpected Boot Sequences for Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-you-cant-find-binkw32dll-file/"><u>Effective Solutions for When You Can't Find binkw32.dll File</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-repairing-your-mouses-right-click-capability-under-windows-11/"><u>Expert Tips: Repairing Your Mouse's Right Click Capability Under Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209420268-fix-computer-keeps-going-to-sleep-issue-easily/"><u>Fix Computer Keeps Going to Sleep Issue. Easily!</u></a></li>
<li><a href="https://extra-tips.techidaily.com/from-zero-to-hero-in-advertising-top-strategies-unveiled-by-experts/"><u>From Zero to Hero in Advertising  Top Strategies Unveiled by Experts</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-erase-iphone-13-pro-data-permanently-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>How To Erase iPhone 13 Pro Data Permanently | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206299156-how-to-quickly-solve-google-hangouts-microphone-malfunction-easy-steps-inside/"><u>How to Quickly Solve Google Hangouts Microphone Malfunction - Easy Steps Inside!</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-unlock-oppo-find-x7-ultra-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock Oppo Find X7 Ultra Phone Without Password?</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-instant-techniques-to-shuffle-youtube-song-sequences/"><u>In 2024, Instant Techniques to Shuffle YouTube Song Sequences</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-next-gen-thrills-with-intova-x-action-tech/"><u>In 2024, Next-Gen Thrills with Intova X Action Tech</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tailored-treasure-troves-the-ultimate-list-of-online-box-sellers/"><u>In 2024, Tailored Treasure Troves  The Ultimate List of Online Box Sellers</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-unlock-the-power-of-personal-branding-insider-secrets-for-flawless-biographies/"><u>In 2024, Unlock the Power of Personal Branding  Insider Secrets for Flawless Biographies</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-challenges-with-windows-system-file-verification-processes/"><u>Overcoming Challenges with Windows System File Verification Processes</u></a></li>
<li><a href="https://games-able.techidaily.com/1719166993933-pinnacle-game-boy-advance-simulation-apps-for-iphone/"><u>Pinnacle Game Boy Advance Simulation Apps for iPhone!</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolve-skype-video-issues-on-windows-10/"><u>Quick Solutions: Resolve Skype Video Issues on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-the-clipboard-tips-for-fixing-copy-and-paste-errors-on-windows-11/"><u>Reviving the Clipboard: Tips for Fixing Copy and Paste Errors on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-troubleshoot-your-lenovos-non-responsive-fingerprint-scanner/"><u>Simple Solutions: Troubleshoot Your Lenovo's Non-Responsive Fingerprint Scanner</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-for-print-driver-host-stopped-working-in-32-bit-applications/"><u>Solution Found for 'Print Driver Host Stopped Working' In 32-Bit Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-common-error-messages-encountered-when-updatinginstalling-steam-games/"><u>Solving Common Error Messages Encountered When Updating/Installing Steam Games</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-tackling-errors-in-windows-version-1903-deployment/"><u>Step-by-Step Fix: Tackling Errors in Windows Version 1903 Deployment</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-non-responsive-keyboard-keys-in-windows-os/"><u>Step-by-Step Solutions for Non-Responsive Keyboard Keys in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-strategies-for-overcoming-failed-d3d-device-setup-problems/"><u>Successful Strategies for Overcoming Failed D3D Device Setup Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208822085-tackling-the-troublesome-green-issue-in-nba-2k21-now-resolved/"><u>Tackling the Troublesome Green Issue in NBA 2K21 - Now Resolved!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-incompatible-usb-hardware-in-windows-11-with-our-step-by-step-fixes/"><u>Troubleshoot Incompatible USB Hardware in Windows 11 with Our Step-by-Step Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-critical-process-dying-error-the-ultimate-guide-to-solving-windows-error-code-0xc00000e9/"><u>Troubleshooting and Fixing Critical Process Dying Error: The Ultimate Guide to Solving Windows Error Code 0xC00000E9</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-graphics-drivers-to-enhance-your-minecraft-adventures-in-windows/"><u>Troubleshooting Graphics Drivers to Enhance Your Minecraft Adventures in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolve-livekernelevent-error-code-117/"><u>Troubleshooting Guide: Resolve LiveKernelEvent Error Code 117</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-functional-keys-on-windows-1011/"><u>Troubleshooting Non-Functional Keys on Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixing-keyboard-malfunctions-and-reboots/"><u>Troubleshooting Tips: Fixing Keyboard Malfunctions and Reboots</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-the-mystery-how-to-restore-controlplusaltplusdelete-on-your-pc/"><u>Unlocking The Mystery: How To Restore Control+Alt+Delete On Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/win11-update-issue-resolving-error-0xc19e208-quickly-and-easily-fixed/"><u>Win11 Update Issue: Resolving Error 0xC19e208 Quickly and Easily [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/xinput13dll-vitality-and-implications-of-its-absence/"><u>XINPUT1_3.dll Vitality and Implications of Its Absence</u></a></li>
</ul></div>
