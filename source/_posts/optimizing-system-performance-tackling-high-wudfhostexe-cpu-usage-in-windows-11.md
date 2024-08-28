---
title: "Optimizing System Performance: Tackling High WUDFHost.exe CPU Usage in Windows 11"
date: 2024-08-27T13:33:14.039Z
updated: 2024-08-28T13:33:14.039Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Optimizing System Performance: Tackling High WUDFHost.exe CPU Usage in Windows 11"
excerpt: "This Article Describes Optimizing System Performance: Tackling High WUDFHost.exe CPU Usage in Windows 11"
thumbnail: https://thmb.techidaily.com/7886b93aef2a0639ec1e094763681d9231c505608c149e23de7fcb6df36e4813.JPG
---

## Optimize Windows 11 Performance by Managing MsMpEngine CPU Drainage - Now Solved

**MsMpEng.exe** , aka **antimalware service executable** , is a native antivirus, anti-malware & spyware program in Windows 10\. While running in background, it scans for any suspicious virus and takes active steps to prevent them from further infecting our computer.

 Note that **MsMpEng.exe** can also be a resource-hungry program and that’s why **MsMpEng.exe** has been eating up so much of your CPU usage, causing computer slowdown, lagging and even**100% Disk Usage**  issues.

 But don’t worry, here in this article, we’ll provide 3 effective workarounds for you to put this nasty problem to bed in no time…

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3 Fixes for MsMpEng.exe Eating Up Too Much CPU

 You may not have to try all these fixes; just work your way down the list until the problem is resolved.

1. **[Prevent Windows Defender from scanning its own folder](https://tools.techidaily.com/drivereasy/download/)**
2. **[Disable Real-Time Protection and reschedule your Windows Defender](https://tools.techidaily.com/drivereasy/download/)**
3. **[Use the Local Group Policy Editor to turn off Windows Defender](https://tools.techidaily.com/drivereasy/download/)**

### **Fix 1: Prevent Windows Defender from scanning its own folder**

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
1) On your keyboard, press **the**   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  , then copy & paste **Virus & threat protection** into the box and click**Virus & threat protection** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48478e47ae3.jpg)

 2) Click **Virus & threat protection settings** .

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484832a46a2.jpg)

 3) Scroll down to the bottom and click**Add or remove exclusions** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4727541&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/copy_copy_forexrobotronbox.gif" border="0">Forex Robotron Gold Package</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4848b874e63.jpg)

 4) Click**Add an exclusion** \>**Folder** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b484924c3bad.jpg)

 5) Copy & paste **C:\\Program Files\\Windows Defender** into the box and click Select**Folder** .

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4849bf2c80f.jpg)

 6) See if MsMpEng.exe is still hogging your CPU usage. If the problem persists, move on to**Fix 2** .

### **Fix 2: Disable Real-Time Protection and r** **eschedule your Windows Defender**

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time , then copy & paste **taskschd.msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4823e1f27c3.png)

 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

<!-- affiliate ads begin -->
<iframe id="iframe_672" src="//a.impactradius-go.com/gen-ad-code/5597632/1959812/17834/" width="720" height="300" scrolling="no" frameborder="0" marginheight="0" marginwidth="0"></iframe>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

5) Restart your computer and see if your computer runs normally now.

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-mastering-youtube-brand-identity-increasing-subscriber-count/"><u>[New] 2024 Approved  Mastering YouTube Brand Identity  Increasing Subscriber Count</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-high-definition-spectacle-top-ten-4ks/"><u>[New] High Definition Spectacle – Top Ten 4Ks</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-trimming-footage-for-insta-on-macos/"><u>[New] In 2024, Trimming Footage for Insta on macOS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-rhythm-and-reels-for-music-masters-on-ig/"><u>[New] Rhythm & Reels for Music Masters on IG</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-top-25-instagram-hashtags-to-get-more-likes-and-followers-for-2024/"><u>[New] Top 25 Instagram Hashtags to Get More Likes and Followers for 2024</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-elevate-your-story-game-with-multiple-image-strategies/"><u>[Updated] In 2024, Elevate Your Story Game with Multiple Image Strategies</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-photographers-path-to-perfected-colors/"><u>[Updated] The Photographer's Path to Perfected Colors</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-effortlessly-turning-words-into-texts-for-free/"><u>2024 Approved  Effortlessly Turning Words Into Texts – For Free</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/approved-essential-tools-for-efficient-mp4-segmentation-on-mac/"><u>2024 Approved  Essential Tools for Efficient MP4 Segmentation on Mac</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-understanding-the-streaming-landscape-twitch-vs-youtube-compared/"><u>2024 Approved  Understanding the Streaming Landscape  Twitch Vs YouTube Compared</u></a></li>
<li><a href="https://review-topics.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-xiaomi-14-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211218181-address-counterarguments-eg-some-may-argue-that-other-qualities-are-more-important-for-professional-success-and-rebut-them-with-convincing-evidence/"><u>Address Counterarguments (E.g., some May Argue that Other Qualities Are More Important for Professional Success) and Rebut Them with Convincing Evidence</u></a></li>
<li><a href="https://driver-error.techidaily.com/1721104340272-built-in-internal-wi-fi-and-bt-wont-stop-in-win10-need-help/"><u>Built-In Internal Wi-Fi and BT Won't Stop in Win10 – Need Help</u></a></li>
<li><a href="https://fox-glue.techidaily.com/calendar-imprinting-techniques-in-photography-for-2024/"><u>Calendar Imprinting Techniques in Photography for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/connect-and-engage-on-major-platforms-facebook-twitter-instagram-and-youtube/"><u>Connect and Engage on Major Platforms: Facebook, Twitter, Instagram & YouTube</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/cultural-immersion-mastering-indonesian-social-exchanges/"><u>Cultural Immersion: Mastering Indonesian Social Exchanges</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-you-encounter-a-missing-binkw32dll-error/"><u>Effective Solutions for When You Encounter a Missing binkw32.dll Error</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-functionality-a-comprehensive-guide-to-keyboard-resets/"><u>Expert Tips for Restoring Functionality - A Comprehensive Guide to Keyboard Resets</u></a></li>
<li><a href="https://common-error.techidaily.com/five-effective-techniques-to-repair-windows-10-touchscreen-issues/"><u>Five Effective Techniques to Repair Windows 10 Touchscreen Issues</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-oppo-find-x7-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-lenovo-laptops-video-camera-back-to-working-order-tips-and-tricks/"><u>Getting Your Lenovo Laptop's Video Camera Back to Working Order: Tips & Tricks</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-13-pro-max-to-the-previous-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 13 Pro Max to the Previous iOS Version? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-elevated-cpu-utilization-by-iastordatasvc-on-your-32-bit-windows-11-machine-step-by-step-solution/"><u>How to Fix Elevated CPU Utilization by IAstorDataSvc on Your 32-Bit Windows 11 Machine - Step by Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-brightness-control-on-your-windows-11-system/"><u>How To Restore Brightness Control on Your Windows 11 System</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-unraveling-the-merits-of-stabilized-photo-editing-with-adobe/"><u>In 2024, Unraveling the Merits of Stabilized Photo Editing with Adobe</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/inside-scoop-on-computing-the-ultimate-guide-by-toms-hardware-specialists/"><u>Inside Scoop on Computing: The Ultimate Guide by Tom's Hardware Specialists</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-functions-intermittently/"><u>Keyboard Functions Intermittently</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-fixation-successfully-solving-error-0x8024002e-on-windows-systems/"><u>Mastering Error Fixation: Successfully Solving Error 0X8024002E on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/no-delay-just-playtime-in-epic-battle-royale/"><u>No Delay, Just Playtime in Epic Battle Royale</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-how-to-resolve-dns-server-not-responding-issues/"><u>Quick Solutions: How to Resolve 'DNS Server Not Responding' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-overcoming-unable-to-confirm-match-by-vac-issues/"><u>Solution Guide: Overcoming 'Unable To Confirm Match by VAC' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-modulenotfounderror-a-comprehensive-guide/"><u>Solving the 'ModuleNotFoundError': A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-strategies-for-fixing-world-of-warcraft-delays/"><u>Step-by-Step Strategies for Fixing World of Warcraft Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-hard-drive-not-detected-problems-on-your-pc-resolved/"><u>The Ultimate Fix for 'Hard Drive Not Detected' Problems on Your PC [RESOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209221170-troubleshoot-and-fix-disk-read-errors-on-your-windows-10-pc-today/"><u>Troubleshoot and Fix Disk Read Errors on Your Windows 10 PC Today</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-resource-protection-error-resolution-steps/"><u>Troubleshooting 'Windows Resource Protection' Error: Resolution Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-a-non-charging-playstation-4-controller/"><u>Troubleshooting Tips for a Non-Charging PlayStation 4 Controller</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-when-your-system-cant-find-a-required-module/"><u>Troubleshooting When Your System Can’t Find a Required Module</u></a></li>
<li><a href="https://common-error.techidaily.com/verify-organization-level-settings-enforcement-on-your-windows-machine/"><u>Verify Organization-Level Settings Enforcement on Your Windows Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/wind-down-your-windows-11-without-disturbances/"><u>Wind Down Your Windows 11 Without Disturbances</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-10-pc-reset-errors-a-step-by-step-fix-guide/"><u>Winning Against Windows 10 PC Reset Errors: A Step-by-Step Fix [Guide]</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/zoomview-partition-inspection/"><u>ZoomView Partition Inspection</u></a></li>
</ul></div>
