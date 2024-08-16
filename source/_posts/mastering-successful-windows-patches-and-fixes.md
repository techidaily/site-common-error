---
title: Mastering Successful Windows Patches and Fixes
date: 2024-08-15T11:08:43.608Z
updated: 2024-08-16T11:08:43.608Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Mastering Successful Windows Patches and Fixes
excerpt: This Article Describes Mastering Successful Windows Patches and Fixes
thumbnail: https://thmb.techidaily.com/baa0ab8cd5a07fe136f1cc2c4fb3a4d9f403c6961da236a4542ceaa49684d0f3.jpg
---

## How To Successfully Repair Windows Update Glitches, Now

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
<a href="https://estore.macxdvd.com/order/checkout.php?PRODS=4526659&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.macxdvd.com/affiliate/new-banner/vcp-500x500.jpg" border="0"></a>
<!-- affiliate ads end -->
## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)
<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)
<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)
<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863039/11832" target="_top" id="863039"><img src="//a.impactradius-go.com/display-ad/11832-863039" border="0" alt="" width="300" height="250"/></a>
<!-- affiliate ads end -->

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)
<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072200/17885" target="_top" id="2072200"><img src="//a.impactradius-go.com/display-ad/17885-2072200" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072200/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Follow the on-screen instructions to choose a system restore point and restore your Windows.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc712671f3.png)

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-free-flicks-galore-cutting-edge-cinema-recommendations-online/"><u>[New] 2024 Approved  Free Flicks Galore  Cutting-Edge Cinema Recommendations Online</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-step-by-step-to-stellar-video-youtube-studio-edition/"><u>[New] In 2024, Step-by-Step to Stellar Video  YouTube Studio Edition</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-mold-your-own-online-giggle-piece/"><u>[New] Mold Your Own Online Giggle Piece</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-deciding-on-a-digital-domain-obs-vs-twitch-studio/"><u>[Updated] 2024 Approved  Deciding on a Digital Domain  OBS Vs Twitch Studio</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-a-comprehensive-guide-for-novices-on-simple-nft-making/"><u>2024 Approved  A Comprehensive Guide for Novices on Simple NFT Making</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-accessories-for-travel-footage-production/"><u>2024 Approved  Accessories for Travel Footage Production</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-beginners-choices-superior-gopro-accessories/"><u>2024 Approved  Beginner’s Choices  Superior GoPro Accessories</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-infinix-note-30-vip-racing-edition-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Infinix Note 30 VIP Racing Edition to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206559286-african-americans/"><u>African Americans:</u></a></li>
<li><a href="https://common-error.techidaily.com/bring-back-the-click-overcoming-keyboard-issues-on-your-dell-device-effectively/"><u>Bring Back the Click: Overcoming Keyboard Issues on Your Dell Device Effectively</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/eco-visuals-cost-free-download/"><u>Eco Visuals, Cost-Free Download</u></a></li>
<li><a href="https://win11-tips.techidaily.com/eliminating-windows-error-0xc0000001-quick-fixes/"><u>Eliminating Windows Error 0xC0000001: Quick Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1053-corrected-enhancing-system-response-time-for-services/"><u>Error 1053 Corrected: Enhancing System Response Time for Services</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-directory-not-recognized-message-a-step-by-step-guide/"><u>Fixing the 'Directory Not Recognized' Message: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unresponsive-file-explorer-in-windows-10-resolved-guide/"><u>How to Fix Unresponsive File Explorer in Windows 10 - Resolved Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-leave-a-life360-group-on-realme-v30t-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>How To Leave a Life360 Group On Realme V30T Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-resolve-the-there-was-an-issue-error-when-restoring-windows-10/"><u>How to Successfully Resolve the 'There Was an Issue' Error When Restoring Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/issue-resolved-how-to-repair-broken-numeric-keys-on-a-computer-keyboard/"><u>Issue Resolved: How to Repair Broken Numeric Keys on a Computer Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-no-device-found-challenge-with-icue-drivers/"><u>Overcoming the 'No Device Found' Challenge with iCUE Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-the-troublesome-win32-app-crash-error-code-0x80070652/"><u>Quick Solutions for the Troublesome Win32 App Crash (Error Code: 0X80070652)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-failed-to-detect-latest-updates-problem-quickly/"><u>Resolving 'Windows Failed To Detect Latest Updates' Problem Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-connectivity-problems-with-external-media-in-windows-environments/"><u>Resolving Connectivity Problems with External Media in Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-delayed-keyboard-responses-easy-solutions-inside/"><u>Resolving Delayed Keyboard Responses: Easy Solutions Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-something-went-wrong-issue-when-restoring-or-refreshing-windows-10-a-comprehensive-guide/"><u>Resolving the 'Something Went Wrong' Issue When Restoring or Refreshing Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://extra-skills.techidaily.com/sleek-design-and-stunning-video-quality-in-sony-xperia-xz-for-2024/"><u>Sleek Design and Stunning Video Quality in Sony Xperia XZ for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-when-your-geforce-experience-wont-load/"><u>Step-by-Step Solution for When Your GeForce Experience Won't Load</u></a></li>
<li><a href="https://unlock-android.techidaily.com/tips-and-tricks-for-setting-up-your-itel-p55-5g-phone-pattern-lock-by-drfone-android/"><u>Tips and Tricks for Setting Up your Itel P55 5G Phone Pattern Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-repair-your-steelseries-arctis-cued-headphones-microphone-step-by-step-solutions/"><u>Troubleshoot & Repair Your SteelSeries Arctis Cued Headphones Microphone – Step by Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-missing-bluetooth-on-windows-11-simple-solutions/"><u>Troubleshoot Missing Bluetooth on Windows 11 - Simple Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-correcting-livekernelevent-error-144/"><u>Troubleshooting Steps for Correcting LiveKernelEvent Error 144</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-10-fix-the-non-functional-touchpad-scroll-problem/"><u>Troubleshooting Windows 10: Fix the Non-Functional Touchpad Scroll Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/untangling-the-causes-of-windows-11-update-failure-error-0xc1900208-a-complete-solution-guide/"><u>Untangling the Causes of Windows 11 Update Failure (Error 0Xc1900208) - A Complete Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/why-isnt-my-hdmi-working-through-usb-common-issues-and-fixes/"><u>Why Isn't My HDMI Working Through USB? Common Issues and Fixes</u></a></li>
</ul></div>
