---
title: "Addressing Freezing During Windows 11 Updates: Best Fixes & Techniques"
date: 2024-08-22T19:27:15.988Z
updated: 2024-08-23T19:27:15.988Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Addressing Freezing During Windows 11 Updates: Best Fixes & Techniques"
excerpt: "This Article Describes Addressing Freezing During Windows 11 Updates: Best Fixes & Techniques"
thumbnail: https://thmb.techidaily.com/74045d9d6303c7a70563d004d7c7b11c2909530a50d24fd1a27318344d95b256.jpg
---

## Winning the Battle Against Failing Windows Updates - Now Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fddb113ec0.png)

Window Update is an important component of your Windows system. It helps you install updates on your system. Windows Update is designed to keep your Windows up to date and healthy and it usually does. But unfortunately, in many cases, it fails to do so and instead become the source of multiple annoying problems. Many Windows users have reported that they have got this or that kind of issues with their Windows Update. They have been told that Windows Update “failed to install” certain updates or these updates’ “installation failed”. They’ve got an error popping up with a code and an associated message, which stops them from installing updates. Or they couldn’t download or install the updates with no clear message but get stuck in the update process. No matter how these issues look like, it stops you from installing the updates on your Windows. You can’t fix your system security vulnerabilities, fix bugs, and enjoy new system features without those updates. This can be extremely frustrating. But don’t panic. All Windows Update issues can be fixed. You can fix them by trying the methods below. You don’t have to try them all; just work your way down the list until you find the one that really works for you.**Methods that fix your Windows Update issues:**

1. [**Run Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restart Windows Update related services**](https://tools.techidaily.com/drivereasy/download/)
3. [**Manually download and install updates**](https://tools.techidaily.com/drivereasy/download/)
4. [**Run DISM and System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Disable your antivirus**](https://tools.techidaily.com/drivereasy/download/)
6. [**Update your drivers**](https://tools.techidaily.com/drivereasy/download/)
7. [**Restore your Windows**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Run Windows Update Troubleshooter

Windows Update Troubleshooter is a tool released by Microsoft that can help you troubleshoot issues with your Windows Update. You can run it to check your Windows Update when it fails to work properly. To do so:**1)**Download **[Windows Update Troubleshooter](https://aka.ms/diag%5Fwu)** (the program is from a Microsoft site and it’s verified and safe).**2)** Run the tool you’ve just downloaded and follow the on-screen instructions to complete the troubleshooting process.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c046d056cc.png)

##  Method 2: Reset the Windows Update related components

Your Windows Update may fail to update your Windows because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this can fix your problem. To reset these components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right-click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)** In Command Prompt, type these commands and press**Enter**after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Check your Windows Update to see if it works fine.

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=36245101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/zang_box_trust.png" border="0">ZoneAlarm Extreme Security NextGen</a>
<!-- affiliate ads end -->
## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

<!-- affiliate ads begin -->
<a href="https://godlikehost.sjv.io/c/5597632/1920054/21774" target="_top" id="1920054"><img src="//a.impactradius-go.com/display-ad/21774-1920054" border="0" alt="" width="320" height="100"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1920054/21774" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901369&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix 4K - Software based live production. vMix 4K includes everything in vMix HD plus 4K support, PTZ control, External/Fullscreen output, 4 Virtual Outputs, 1 Replay, 4 vMix Call, and 2 Recorders. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1678785/12108" target="_top" id="1678785"><img src="//a.impactradius-go.com/display-ad/12108-1678785" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->
**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
**3)** Follow the on-screen instructions to choose a system restore point and restore your Windows.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc712671f3.png)

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
**4)** Wait for the restore process to complete and then check to see if your Windows Update gets back to normal.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-video-capture.techidaily.com/updated-enhance-pc-listening-experience-install-x-recorder/"><u>[Updated] Enhance PC Listening Experience - Install X-Recorder</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-restart-tecno-spark-20-proplus-without-power-button-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Restart Tecno Spark 20 Pro+ Without Power Button | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/device-disconnection-amidst-accurate-configuration/"><u>Device Disconnection Amidst Accurate Configuration</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-strategies-to-correct-oculus-equipment-failures-in-the-new-year-2024-edition/"><u>DIY Repair Strategies to Correct Oculus Equipment Failures in the New Year, 2024 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-for-reviving-a-failing-laptop-battery-lightning-fast-results/"><u>Easy Steps for Reviving a Failing Laptop Battery – Lightning-Fast Results</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-http-error-503-service-unavailable/"><u>Easy to Fix HTTP Error 503 Service Unavailable</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-file-management-on-windows-11-mastering-the-art-of-file-explorer/"><u>Effortless File Management on Windows 11: Mastering the Art of File Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-the-persistent-restart-problem-in-windows-11/"><u>Effortless Fixes for the Persistent Restart Problem in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x887a0006-resolved-fast-and-simple-solutions-inside/"><u>Error 0X887A0006 Resolved: Fast and Simple Solutions Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-restoring-your-lenovos-malfunctioning-camera-feature/"><u>Expert Advice on Restoring Your Lenovo's Malfunctioning Camera Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-solutions-for-resolving-application-launch-errors-code-0xc000007b-in-windows-os/"><u>Expert Solutions for Resolving Application Launch Errors (Code 0Xc000007b) in Windows OS</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-oppo-find-n3-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/how-and-where-to-find-a-shiny-stone-pokemon-for-samsung-galaxy-xcover-7-drfone-by-drfone-virtual-android/"><u>How and Where to Find a Shiny Stone Pokémon For Samsung Galaxy XCover 7? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-resource-protection-unable-to-complete-the-operation-message-efficiently/"><u>How to Fix 'Windows Resource Protection Unable To Complete The Operation' Message Efficiently</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-honor-play-7t-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Honor Play 7T</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-innovating-content-creation-vimeo-edition/"><u>In 2024, Innovating Content Creation  Vimeo Edition</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-optimal-hue-refiner-app/"><u>In 2024, Optimal Hue Refiner App</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/innovative-approaches-to-live-broadcasting-on-youtube-with-wirecast/"><u>Innovative Approaches to Live Broadcasting on Youtube with WireCast</u></a></li>
<li><a href="https://common-error.techidaily.com/make-western-digital-my-passport-ultra-visible-again-on-your-windows-system/"><u>Make Western Digital My Passport Ultra Visible Again on Your Windows System</u></a></li>
<li><a href="https://win-solutions.techidaily.com/revitalize-your-stagnant-business-essential-steps-to-overcome-non-launch-issues/"><u>Revitalize Your Stagnant Business: Essential Steps to Overcome Non-Launch Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-of-unresponsive-volume-control-in-windows-11/"><u>Solving the Problem of Unresponsive Volume Control in Windows 11</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-problem-troubleshooting-steps-when-your-mac-app-wont-launch/"><u>Solving the Problem: Troubleshooting Steps When Your Mac App Won't Launch</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-resolve-windows-camera-error-code-0xa00f4292-efficiently/"><u>Step-by-Step Guide to Resolve Windows Camera Error Code 0xA00F4292 Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reviving-the-scroll-wheel-in-a-malfunctioning-logitech-mouse/"><u>Step-by-Step Guide: Reviving the Scroll Wheel in a Malfunctioning Logitech Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-resolution-overcoming-hub-port-electrical-fluctuations/"><u>Step-by-Step Resolution: Overcoming Hub Port Electrical Fluctuations</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-windows-1ns-absent-bluetooth-feature-with-simple-fixes/"><u>Troubleshoot Windows 1N's Absent Bluetooth Feature with Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-cxfreeze-catastrophic-failures-with-ease/"><u>Troubleshooting Guide: Solving Cx_Freeze Catastrophic Failures with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-rpc-server-availability-problems-in-windows-systems-effectively/"><u>Troubleshooting RPC Server Availability Problems in Windows Systems Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-dota-2-2024-rendering-api-mishap-efficiently/"><u>Troubleshooting the Dota 2 2024 Rendering API Mishap Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-usb-mouse-issues-effective-solutions-for-when-it-fails-on-your-laptop/"><u>Troubleshooting Your USB Mouse Issues: Effective Solutions for When It Fails on Your Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-auto-startup-diagnosing-why-windows-11-turns-on-by-itself/"><u>Unexpected Auto Startup: Diagnosing Why Windows 11 Turns On by Itself</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/unlock-insightful-revelations-instagram-snapshot-audiences/"><u>Unlock Insightful Revelations  Instagram Snapshot Audiences</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/k-the-power-of-social-sharing-for-your-youtube-videos/"><u>Unlock the Power of Social Sharing for Your YouTube Videos</u></a></li>
</ul></div>
