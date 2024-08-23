---
title: "Deciphering Administrative Controls: Tweaking Corporate Configurations in Windows Environment"
date: 2024-08-22T19:29:31.761Z
updated: 2024-08-23T19:29:31.761Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Deciphering Administrative Controls: Tweaking Corporate Configurations in Windows Environment"
excerpt: "This Article Describes Deciphering Administrative Controls: Tweaking Corporate Configurations in Windows Environment"
thumbnail: https://thmb.techidaily.com/228e79977939cec81e9b9a3337281ae057b8c153534fece429948183b0ad342f.png
---

## Winning the Battle Against MsMpEng.exe: Reducing CPU Usage in Windows 11 – Effective Strategies Inside

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
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
 2) Locate and double-click on**Task Schedule Library** \> **Microsoft** \>**Windows** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48247e04d53.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2201613&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macdvdripperpro.com/images/devices-3.png" border="0"></a>
<!-- affiliate ads end -->
 3) Scroll down to the bottom, double-click on**Windows Defender** , then right-click on**Windows Defender Scheduled Scan** and click**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48254c26e3f.jpg)

 4) In the**General** tab, un-check**the box** before**Run with highest privileges** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4845e5ee219.jpg)

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Click the**Conditions** tab, make sure**the boxes** in this window are**unchecked** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48462bea585.jpg)

 5) Click the**Triggers** tab >**New…** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482828900da.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
 6) Schedule your own**Windows Defender** scan. Carefully choose the frequency, scan time and date at your own convenience and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4828bca7be2.jpg)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
 7) Restart your computer. Hopefully this time your **MsMpEng.exe** won’t be hogging too much of your CPU usage.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=12730965&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/w5/03_WBSX5_728x90_red_CTA.jpg" border="0"></a>
<!-- affiliate ads end -->
### **Fix 3: Use the Local Group Policy Editor to turn off Windows Defender**

 Note that**Fix 3** is about to turn off your**Windows Defender** program which might leave your computer at the mercy of virus and malware attacks. Please proceed with caution.

1) On your keyboard, press **the**   **Windows logo key**  and**R** at the same time, then copy & paste**gpedit.** **msc** into the box and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4829b314bed.png)

 2) Locate and double-click on **Computer Configuration** \>**Administrative Templates** \>**Windows Components** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b482ad2bedf6.jpg)

 3) Locate and double-click on**Windows Defender Antivirus** (aka. **Windows Defender** , same as below). Then double-click on **Turn off Windows Defender Antivirus** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b48417e7d299.jpg)

 4) Choose the**Enabled** option, and click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4841ef0331d.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4693127&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.videosoftdev.com/images/video_editor/screenshots/1.jpg" border="0">
VSDC Pro Video Editor is a light professional non-linear video editing suite for creating a movie of any complexity. It supports the most popular video/audio formats and codecs, including 4K, HD and GoPro videos. Preconfigured profiles make the creation of videos for various multimedia and mobile devices absolutely hassle-free.

Key features:

•	Import from any devices and cams, including GoPro and drones. All formats supported. Сurrently the only free video editor that allows users to export in a new H265/HEVC codec, something essential for those working with 4K and HD.
•	Everything for hassle-free basic editing: cut, crop and merge files, add titles and favorite music
•	Visual effects, advanced color correction and trendy Instagram-like filters   
•	All multimedia processing done from one app: video editing capabilities reinforced by  a video converter, a screen capture, a video capture, a disc burner and a YouTube uploader
•	Non-linear editing: edit several files with simultaneously 
•	Easy export to social networks: special profiles for YouTube, Facebook, Vimeo, Twitter and Instagram
•	High quality export – no conversion quality loss, double export speed even of HD files due to hardware acceleration
•	Stabilization tool will turn shaky or jittery footage into a more stable video automatically. 
•	Essential toolset for professional video editing: blending modes, Mask tool, advanced multiple-color Chroma Key  
</a>
<!-- affiliate ads end -->
5) Restart your computer and see if your computer runs normally now.

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
<li><a href="https://common-error.techidaily.com/fixed-print-driver-host-for-32bit-applications-has-stopped-working/"><u>[Fixed] Print Driver Host for 32Bit Applications Has Stopped Working</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-facebook-video-orientation-dilemma-for-2024/"><u>[New] Facebook  Video Orientation Dilemma for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-grit-vs-glory-hitbox-versus-twitch-titans/"><u>[New] Grit vs Glory  Hitbox Versus Twitch Titans</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-hunters-picks-best-video-recorders-reviewed-for-2024/"><u>[New] Hunters' Picks  Best Video Recorders Reviewed for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-11-brightness-control-not-working/"><u>[Solved] Windows 11 Brightness Control Not Working</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-best-vocal-modification-software-for-content-creators-for-2024/"><u>[Updated] Best Vocal Modification Software for Content Creators for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-filmora-edits-explained-addressing-common-concerns-and-questions/"><u>[Updated] Filmora Edits Explained  Addressing Common Concerns and Questions</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-download-mastery-securing-the-livestream-lifeline/"><u>[Updated] In 2024, Download Mastery  Securing the Livestream Lifeline</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-strategies-to-maximize-viewership-on-igtv-from-h-videos/"><u>[Updated] In 2024, Strategies to Maximize Viewership on IGTV From H-Videos</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-the-role-of-motion-leveraging-fb-ads-for-outstanding-roi/"><u>[Updated] In 2024, The Role of Motion  Leveraging FB Ads for Outstanding ROI</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-understanding-and-optimizing-your-social-media-videos-on-fb/"><u>[Updated] In 2024, Understanding & Optimizing Your Social Media Videos on FB</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-the-art-of-monetizing-snapchat-content/"><u>[Updated] The Art of Monetizing Snapchat Content</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-thriving-despite-youtubes-rigorous-copyright-strike-system/"><u>[Updated] Thriving Despite YouTube's Rigorous Copyright Strike System</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/emier-sci-tech-vloggers-for-enlightened-learning-for-2024/"><u>15 Premier Sci-Tech Vloggers for Enlightened Learning for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-restoring-correct-self-image-amidst-message-distortion/"><u>2024 Approved  Restoring Correct Self-Image Amidst Message Distortion</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-top-100-virtual-bicycle-escapades-to-experience/"><u>2024 Approved  Top 100 Virtual Bicycle Escapades to Experience</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-understanding-the-basics-of-audio-crossfading/"><u>2024 Approved  Understanding the Basics of Audio Crossfading</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-unlocking-windows-hdr-capabilities-for-cutting-edge-video-workflows/"><u>2024 Approved  Unlocking Windows' HDR Capabilities for Cutting-Edge Video Workflows</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/2024-approved-visual-identity-shielding-adding-watermark-and-logo-to-youtube-media/"><u>2024 Approved  Visual Identity Shielding  Adding Watermark & Logo to YouTube Media</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/comprehensive-guide-to-advanced-screen-capture-via-adobe-captive-for-2024/"><u>Comprehensive Guide to Advanced Screen Capture via Adobe Captive for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-error-code-0x80004005-a-comprehensive-solution-to-the-undefined-issue-in-email-clients/"><u>Dealing with 'Error Code 0X80004005': A Comprehensive Solution to the Undefined Issue in Email Clients</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-solving-black-screen-problems-with-your-asus-built-in-webcam-on-windows-10/"><u>DIY Fixes: Solving Black Screen Problems with Your ASUS Built-In Webcam on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209054213-easy-ways-to-fix-error-code-0x80070002-during-windows-system-updates-now/"><u>Easy Ways to Fix Error Code 0X80070002 During Windows System Updates - Now</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-guide-to-troubleshoot-unknown-usb-device-and-descriptor-issues-solved/"><u>Effective Guide to Troubleshoot 'Unknown USB Device' And Descriptor Issues [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-the-failed-to-initialize-directx-problem/"><u>Effective Remedies for the 'Failed to Initialize DirectX' Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-continuous-usb-recognition-failures-on-your-pc/"><u>Effective Solutions for Continuous USB Recognition Failures on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-overcoming-the-absence-of-an-audio-device-on-your-windows-computer-system/"><u>Expert Tips for Overcoming the Absence of an Audio Device on Your Windows Computer System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-audio-functionality-when-windows-10-fails/"><u>Expert Tips for Restoring Audio Functionality When Windows 10 Fails</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/eyoyo-em1n05-the-ultimate-compact-and-cost-effective-choice-in-portable-105-display-tech/"><u>Eyoyo EM1n05: The Ultimate Compact & Cost-Effective Choice in Portable 10.5” Display Tech</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-a-blinking-cursor-simple-troubleshooting-steps/"><u>Fix a Blinking Cursor: Simple Troubleshooting Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-when-the-diagnostics-policy-service-wont-start/"><u>Fixing Issues When the Diagnostics Policy Service Won't Start</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/from-flavor-to-verse-chocolate-speeches-across-nations/"><u>From Flavor to Verse: Chocolate Speeches Across Nations</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-tecno-spark-go-2024-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Tecno Spark Go (2024)? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-errcachemiss-error-encountered-in-chrome-browser/"><u>How to Correctly Address ERR_CACHE_MISS Error Encountered in Chrome Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-high-disk-usage-caused-by-microsoft-telemetry-on-windows-10-systems/"><u>How to Fix High Disk Usage Caused by Microsoft Telemetry on Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-your-lenovo-mouse-mat-compatibility-with-windows-10-8-and-7-systems/"><u>How to Repair Your Lenovo Mouse Mat Compatibility with Windows 10, 8 & 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-problematic-windows-11-update-1607-installation-failures/"><u>How to Resolve Problematic Windows 11 Update 1607 Installation Failures</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-oppo-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Oppo Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-fix-problems-with-configuring-your-windows-updates/"><u>How to Successfully Fix Problems with Configuring Your Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205926497-hp-laptops-unresponsive-keys-master-the-rapid-restoration-methods-today/"><u>HP Laptops' Unresponsive Keys? Master the Rapid Restoration Methods Today</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-video-craft-decoding-filmora-questions-for-2024/"><u>Mastering Video Craft  Decoding Filmora Questions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/minecraft-wont-start-here-are-the-solutions-for-launch-issues-on-windows-machines/"><u>Minecraft Won’t Start? Here Are the Solutions for Launch Issues on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unspecified-error-code-0x80004005-expert-solutions/"><u>Overcoming Unspecified Error Code 0X80004005: Expert Solutions</u></a></li>
<li><a href="https://win11.techidaily.com/preventing-read-only-mode-on-windows-folders/"><u>Preventing Read-Only Mode on Windows Folders</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-excessive-cpu-consumption-by-windows-audio-hardware-acceleration/"><u>Resolve Excessive CPU Consumption by Windows Audio Hardware Acceleration</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-minecraft-error-code-5-a-step-by-step-guide/"><u>Resolving Minecraft Error Code 5: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-spacebar-z-r-ren/"><u>Resolving Windows ˈSPACEBAR Ɪz ʏɑːrŋ Ɜːrɡən</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-windows-11-hosted-mode-connectivity-failure/"><u>Solving the Problem: Windows 11 Hosted Mode Connectivity Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-windows-10-device-connection-casting-errors-efficiently/"><u>Solving Your Windows 10 Device Connection Casting Errors Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reducing-microsoft-telemetry-impact-on-storage-in-windows-cuhceroesystem/"><u>Step-by-Step Guide: Reducing Microsoft Telemetry Impact on Storage in Windows Cuhceroesystem</u></a></li>
<li><a href="https://common-error.techidaily.com/tackle-error-code-0x887a0006-easy-fixes-for-immediate-relief/"><u>Tackle Error Code 0X887A0006: Easy Fixes for Immediate Relief!</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-sony-xperia-5-v-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Sony Xperia 5 V Reset Code | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-inability-of-application-to-launch-correctly-error-0xc000007b/"><u>Troubleshooting and Fixing the Inability of Application to Launch Correctly [Error 0XC000007B]</u></a></li>
<li><a href="https://win-answers.techidaily.com/troubleshooting-persistent-sony-vegas-crashes-get-your-project-up-and-running/"><u>Troubleshooting Persistent Sony Vegas Crashes - Get Your Project Up and Running!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-nonfunctioning-camera-on-lenovo-computers-expert-advice/"><u>Troubleshooting the Nonfunctioning Camera on Lenovo Computers - Expert Advice</u></a></li>
<li><a href="https://printer-issues.techidaily.com/tutorial-connecting-hp-printer-to-windows-pc/"><u>Tutorial: Connecting HP Printer to Windows PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/ultimate-music-streams-network-for-2024/"><u>Ultimate Music Streams Network for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/unblocked-horizons-wow-breaks-free-from-3d-restrictions/"><u>Unblocked Horizons: WoW Breaks Free From 3D Restrictions</u></a></li>
<li><a href="https://ai-video.techidaily.com/updated-in-2024-how-to-translate-audiovideo-content-from-spanish-to-english-and-vice-versa/"><u>Updated In 2024, How to Translate Audio/Video Content From Spanish to English and Vice Versa?</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-shutdown-speeding-tips-get-a-faster-logoff/"><u>Windows 10 Shutdown Speeding Tips - Get a Faster Logoff</u></a></li>
</ul></div>
