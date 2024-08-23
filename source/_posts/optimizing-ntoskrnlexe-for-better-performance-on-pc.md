---
title: Optimizing ntoskrnl.exe for Better Performance on PC
date: 2024-08-22T19:25:30.971Z
updated: 2024-08-23T19:25:30.971Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Optimizing ntoskrnl.exe for Better Performance on PC
excerpt: This Article Describes Optimizing ntoskrnl.exe for Better Performance on PC
thumbnail: https://thmb.techidaily.com/7bb5cd6c098dcc354a1616a8cf729a503ba552ba0d30358349d319e43f0bdaa3.jpg
---

## Optimizing ntoskrnl.exe for Better Performance on PC

 If your Windows is working slowly, and when you check your Task Manager and find that the**System** item is hogging much of your CPU (or Disk in some cases) usage, you’re not alone. Many Windows users are reporting this problem. Don’t worry, it’s possible to fix.

**\*** Right-click the**System** item and click**Properties** , you’ll see a new item called**ntoskrnl.exe** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b0f9d613fd6.png)

## What is ntoskrnl.exe?

 Ntoskrnl.exe, short for**Windows NT operating system kernel** , is a fundamental part of the system. Usually, when you see the uncommon usage of high CPU or memory, you should shut down the possible programs that are causing the problem.

 If this happens a lot, you should see if there is something wrong with certain application settings or files in your system.

## How do I fix it?

 Here are 4 methods for you to try. You may not have to try them all; just work your way down until you find the one that works for you.

* **[Method 1: Disable Windows Search Service](#a)**
* **[Method 2: Check Incompatible Programs](#b)**
* **[Method 3: Run SFC and DISM](#c)**
* **[Method 4: Disable Runtime Broker](#d)** [](#d)

 It is always suggested that you keep your device drivers updated to eliminate the possibility of such problems.

 Driver Easy is a tool that detects, downloads, and updates drivers (if you go Pro). You can use it to fix any driver problems. If you go to Pro, you can even update all drivers with just one click. If the high system CPU usage problem is caused by drivers, you can use Driver Easy to fix it quickly.

 You can update your drivers automatically with either the [**7 days free trial**](https://tools.techidaily.com/drivereasy/download/) or the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. It takes just 2 clicks, and you get full support and a 30-day money-back guarantee with the Pro version:

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2020/10/6_0_scan-now.jpg)
3. Click the**Activate & Update** button next to the flagged device to automatically download and install the correct version of this driver.  

 Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (You’ll need the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  for this – when you select Update All, you’ll get a prompt to upgrade. If you’re not prepared to purchase the Pro version yet, Driver Easy provides a 7-day trial at no cost, granting access to all Pro features like fast downloads and easy installation. No charges will occur until after your 7-day trial period ends.)  
![](https://www.drivereasy.com/wp-content/uploads/2021/05/NVIDIA-GeForce-RTX-3090-Ti-3.jpg)
4. After updating, restart your computer to take effect.

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 1: Disable Windows Search service

 A lot of users suggested that disabling Windows Search helps to reduce the CPU and Disk usage caused by ntoskrnl.exe. To see if this does the trick for you as well:

1. On your keyboard, press the **Windows key** and**X** at the same time, then click **Computer management** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/computer-management.png)
2. Expand**Services and Applications** and click**Services** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/services-and-applications.jpg)
3. Double-click**Windows Search** .  
<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=4535075&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/GU-500_672.png" border="0">Glary Utilities PRO -  Premium all-in-one utility to clean, speed up, maintain and protect your PC</a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/windwos-search-6101.jpg)
4. In the**General** tab, click **Stop** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/stop-button.jpg)
5. Wait for the service to stop, then press**OK** to save the change and exit.  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/ok-to-save-the-change-6104.jpg)

## Method 2: Check incompatible programs

 Some users say that this only happens when they use certain programs. Especially when they have antivirus software running in the background. The antivirus software might have some conflicts with certain programs. The next time you encounter this situation, try to pay extra attention to see if you can find the program that is messing with your system. If such a program can be located, try reinstallingit or uninstalling it completely.

## Method 3: Run SFC and DISM

 Corrupted system files may cause high CPU and disk usage with ntoskrnl.exe, but luckily, there are two built-in tools that can help to identify and repair such bad system files. The whole process could take some time, and we suggest you don’t run any other programs when doing the test. To run these tools:

### 3.1\. Scan corrupt files with System File Checker

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** at the same time to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following command and hit**Enter** .

sfc /scannow

 3) System File Checker will then scan all system files and repair any corrupted or missing ones it detected. This may take 3-5 minutes.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/scan-now.jpg)

<!-- affiliate ads begin -->
<a href="https://mindmanager.sjv.io/c/5597632/1787667/20231" target="_top" id="1787667"><img src="//a.impactradius-go.com/display-ad/20231-1787667" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1787667/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### 3.2\. Run dism.exe

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following commands and hit**Enter** after each line:

dism.exe /online /cleanup-image /scanhealth

dism.exe /online /cleanup-image /restorehealth

2) When the process finishes:

* If the DISM tool gives you errors, you can always try this command line. This will take up to 2 hours.

dism /online /cleanup-image /startcomponentcleanup

* If you get **Error: 0x800F081F** , reboot your computer, then open Command Prompt as administrator again (step 1) and run this command line instead:

Dism.exe /Online /Cleanup-Image /AnalyzeComponentStore

 When these tests are done, see if the ntoskrnl.exe high CPU or disk usage problem remains. If the problem still persists, please move on to the next fix.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Method 4: Disable Runtime Broker

 Normally, the runtime broker process should only use a very low CPU resource, but if things go wrong, it could take up to 100% CPU and disk usage, making your Windows run slowly and buggy. In this case, you can try to disable it to see if it helps. To do so:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here: [How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the **Windows** key and the **R** key together. Type **regedit** and hit **Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\TimeBroker`  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker.png)
4. On the right side, double-click**Start** , and change its value to**4** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker-4.png)
5. Restart your computer for the changes to take effect.
<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

See if the ntoskrnl.exe high CPU or disk usage problem remains.

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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-accessing-the-archives-of-social-media-history-pc-and-mobile-guide/"><u>[New] 2024 Approved  Accessing the Archives of Social Media History  PC & Mobile Guide</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-expert-strategies-on-calculating-your-youtube-audience-impact-and-revenue/"><u>[New] 2024 Approved  Expert Strategies on Calculating Your YouTube Audience Impact and Revenue</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-professional-video-editing-simplified-with-mac-mp4-cutters/"><u>[New] In 2024, Professional Video Editing Simplified with Mac MP4 Cutters</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-unleash-creativity-with-gopros-time-lapse-technology/"><u>[New] Unleash Creativity with GoPro's Time-Lapse Technology</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-2024-approved-from-live-to-recorded-a-skilled-approach-to-skype-chat-documentation/"><u>[Updated] 2024 Approved  From Live to Recorded  A Skilled Approach to Skype Chat Documentation</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-capture-the-action-the-fastest-most-effective-home-filmmaking-tricks/"><u>[Updated] Capture the Action  The Fastest, Most Effective Home Filmmaking Tricks</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-instagram-exit-wave-analysis/"><u>[Updated] In 2024, Instagram Exit Wave Analysis</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-upload-wizardry-selecting-the-best-youtube-to-twitter-convertors/"><u>[Updated] Upload Wizardry  Selecting the Best YouTube to Twitter Convertors</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-the-art-of-instagram-video-craftsmanship/"><u>2024 Approved  The Art of Instagram Video Craftsmanship</u></a></li>
<li><a href="https://extra-resources.techidaily.com/best-windows-sketchpad-selections-cost-free-and-premium-plans-for-2024/"><u>Best Windows Sketchpad Selections  Cost-Free & Premium Plans for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-your-gameplay-expert-tips-to-overcome-minecraft-lag-issues/"><u>Boost Your Gameplay: Expert Tips to Overcome Minecraft Lag Issues</u></a></li>
<li><a href="https://win11.techidaily.com/breaking-barriers-easily-uninstall-applications-in-win-11/"><u>Breaking Barriers: Easily Uninstall Applications in Win 11</u></a></li>
<li><a href="https://common-error.techidaily.com/common-fixes-for-launching-minecraft-successfully-on-a-window-os/"><u>Common Fixes for Launching Minecraft Successfully on a Window OS</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/concurrent-code-switching-course/"><u>Concurrent Code-Switching Course</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-unintended-typographical-errors-while-keyboarding/"><u>Correcting Unintended Typographical Errors While Keyboarding</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210502992-corsair-keyboard-malfunction-heres-how-to-make-it-glow-again/"><u>Corsair Keyboard Malfunction? Here's How to Make It Glow Again</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-sims-4-game-wont-start-correctly/"><u>Effective Fixes for When Your Sims 4 Game Won't Start Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-resolving-the-persistent-restart-problem-in-windows-10/"><u>Effortless Fixes for Resolving the Persistent Restart Problem in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203659471-effortless-guide-to-overcome-too-many-redirects-error-swiftly/"><u>Effortless Guide to Overcome Too Many Redirects Error Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminating-the-dxgkrnl-fatal-error-for-smooth-video-playback-on-windows/"><u>Eliminating the DXGKRNL Fatal Error for Smooth Video Playback on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-win11s-troublesome-0x80072efd-error-a-step-by-step-guide/"><u>Fixing Win11's Troublesome 0X80072EFD Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-resolving-google-chromes-serious-malfunction-and-security-threat/"><u>Guide to Resolving Google Chrome's Serious Malfunction and Security Threat</u></a></li>
<li><a href="https://common-error.techidaily.com/hack-the-errors-reinstating-x3daudio17dll/"><u>Hack the Errors: Reinstating X3DAudio1_7.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-latency-problems-with-the-keyboard-on-a-windows-10-system/"><u>How to Overcome Latency Problems with the Keyboard on a Windows 10 System</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-5-simple-ways-to-save-your-youtube-content/"><u>In 2024, 5 Simple Ways to Save Your YouTube Content</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-ringtune-recipe-mixing-and-mastering-tamil-music-for-alerts/"><u>In 2024, RingTune Recipe  Mixing & Mastering Tamil Music for Alerts</u></a></li>
<li><a href="https://common-error.techidaily.com/level-up-your-gaming-rig-how-to-achieve-peak-performance-in-windows-11-games/"><u>Level Up Your Gaming Rig: How to Achieve Peak Performance in Windows 11 Games</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fixes-for-persistent-error-code-0x800f0922-on-your-windows-10-machine/"><u>Master the Fixes for Persistent Error Code 0X800f0922 on Your Windows 10 Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/microsoft-compatibility-telemetry-eating-up-too-much-disk-space-on-windows-10-solutions-and-fixes-available-now/"><u>Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now</u></a></li>
<li><a href="https://common-error.techidaily.com/multiracial-americans/"><u>Multiracial Americans:</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-the-ultimate-list-of-affordable-and-premium-online-recording-studios-2023-edition/"><u>New The Ultimate List of Affordable and Premium Online Recording Studios 2023 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/offline-no-access-to-blizzard-services/"><u>Offline - No Access To Blizzard Services</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205901536-ps4-controllers-not-powering-up-here-are-the-solutions/"><u>PS4 Controllers Not Powering Up? Here Are the Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-error-code-0x800f0831-utilize-windows-updates/"><u>Quick Fixes for Error Code 0X800f0831: Utilize Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-no-playable-sources-error-during-game-launch-on-windows-a-comprehensive-guide/"><u>Resolving 'No Playable Sources' Error During Game Launch on Windows - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-current-outage-of-your-computers-windows-security-feature-smartscreen/"><u>Resolving Current Outage of Your Computer's Windows Security Feature: SmartScreen</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-ps4-noise-issues-understanding-causes-and-solutions/"><u>Resolving PS4 Noise Issues: Understanding Causes and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-hp-laptop-webcam-a-step-by-step-guide-for-windows-10-users/"><u>Revive Your HP Laptop Webcam: A Step-by-Step Guide for Windows 10 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/sfc-and-dism-windows-11-repair-options/"><u>SFC and DISM: Windows 11 Repair Options</u></a></li>
<li><a href="https://fox-blue.techidaily.com/sky-high-technology-unleashed-compreeive-review-of-dji-phantom-4-for-2024/"><u>Sky High Technology Unleashed  Compreeive Review of DJI Phantom 4 for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-graphics-glitches-troubleshoot-failed-to-create-d3d9-device/"><u>Solve Your Graphics Glitches: Troubleshoot Failed to Create D3D9 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-errors-encountered-while-installing-or-updating-on-steam/"><u>Step-by-Step Fixes for Errors Encountered While Installing or Updating on Steam</u></a></li>
<li><a href="https://common-error.techidaily.com/streamlining-pasting-processes-in-windows-10-devices/"><u>Streamlining Pasting Processes in Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/sudden-repeated-restarts-windows-11-pcs/"><u>Sudden Repeated Restarts Windows 11 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-svchostexe-overuse-lowering-cpu-usage-on-windows-10-systems-step-by-step-fix/"><u>Tackling svchost.exe Overuse: Lowering CPU Usage on Windows 10 Systems [Step-by-Step Fix]</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ing-the-mystery-of-missing-shorts-video-images-for-2024/"><u>Tackling the Mystery of Missing Shorts Video Images for 2024</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/the-comprehensive-guide-to-next-gen-tech-features-spotted-at-toms-gadgets-forum/"><u>The Comprehensive Guide to Next-Gen Tech: Features Spotted at Tom's Gadgets Forum</u></a></li>
<li><a href="https://common-error.techidaily.com/top-techniques-utilizing-system-file-checker-sfc-and-deployment-image-service-and-management-dism-for-resolving-windows-11-problems/"><u>Top Techniques: Utilizing System File Checker (SFC) and Deployment Image Service and Management (DISM) for Resolving Windows 11 Problems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/transform-your-footage-tips-for-youtube-studios-video-editing/"><u>Transform Your Footage  Tips for YouTube Studio's Video Editing</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-resolving-errcachemiss-errors-on-chrome-browsers/"><u>Troubleshooting and Resolving ERR_CACHE_MISS Errors on Chrome Browsers</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210743255-troubleshooting-destiny-2-get-your-game-up-and-running-again/"><u>Troubleshooting Destiny 2: Get Your Game Up and Running Again</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-missing-binkw32dll-errors-on-your-pc/"><u>Troubleshooting Missing binkw32.dll Errors on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-a-damaged-windows-store-cache-issue-fixed/"><u>Troubleshooting Tips for a Damaged Windows Store Cache Issue [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-a-non-functional-backspace-button/"><u>Troubleshooting Tips for a Non-Functional Backspace Button</u></a></li>
<li><a href="https://common-error.techidaily.com/unstick-your-windows-update-clearing-that-persistent-100-barrier-now-solved/"><u>Unstick Your Windows Update: Clearing that Persistent 100%% Barrier – Now Solved!</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-traffic-triumph-key-youtube-seo-tools-for-2024/"><u>Video Traffic Triumph - Key YouTube SEO Tools for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-live-location-is-not-updating-and-how-to-fix-on-your-nokia-c12-plus-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Live Location is Not Updating and How to Fix on your Nokia C12 Plus | Dr.fone</u></a></li>
</ul></div>
