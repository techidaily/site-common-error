---
title: Resolving Windows 10 Update Loop at 99%% or Full - Get Back on Track Now!
date: 2024-08-31T17:45:08.314Z
updated: 2024-09-01T17:45:08.314Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Windows 10 Update Loop at 99%% or Full - Get Back on Track Now!
excerpt: This Article Describes Resolving Windows 10 Update Loop at 99%% or Full - Get Back on Track Now!
thumbnail: https://thmb.techidaily.com/14a22e63716263e4dbf21490561e8b1d60bb16b34f9d12286d81f3b90aa95801.jpg
---

## How to Fix Windows Update Freezing at 98% or 100% - SOLUTION NOW

 If you see the message **“Working on updates, 100% complete. Don’t turn off your computer”** when performing a Windows update, don’t worry!

 Although it’s incredibly frustrating, you’re not the only person to experience this issue. Thousands of Windows users have recently reported the very same issue. More importantly, you should be able to fix it pretty easily…

## Try these fixes

 Here’s a list of fixes that have resolved this problem for other Windows users. You don’t have to try them all. Just work your way through the list until you find the one that does the trick for you.

1. **[Remove any USB peripherals and wait for the update process to finish](#f1)**
2. **[Force restart your PC](#f2)**
3. **[Run Windows Update troubleshooter](#f3)**
4. **[Reset Windows Update components](#f4)**
5. **[Download updates from Microsoft Update Catalog manually](#f5)**
6. **[Pro tip: Want us to fix the problem for you?](#p)**

### Fix 1: Remove any USB peripherals and wait for the update process to finish

 If you seldom check for Windows updates, it may take a long time for Windows to complete the update process. Maybe your PC is not “stuck” at Windows update, and Windows is just configuring and installing update packages.

 If you temporarily don’t need to use your PC, you can just wait for 2 to 3 hours to see if the update process can be completed. If there are any USB devices (like printers, USB flash drives, etc.) connected to your PC, you can try removing them from your PC. Some Windows users reported that after they disconnect all the USB peripherals from their PCs, the update process completes quickly.

 See if this issue persists after you wait for 2 to 3 hours. If it persists, try the next fix below to force restart your PC.

<!-- affiliate ads begin -->

<!-- affiliate ads end -->
### Fix 2: Force restart your PC

 If Your PC gets stuck at 100% when you’re performing a Windows update, you need to force restart your PC first. If you don’t know how to do it, you can follow the instructions below:

1. Press and **keep holding** the power button on your computer case **until your PC shuts down** .
2. **Disconnect** any external power supply or remove the battery from your laptop.
3. **Hold down** the power button for about **15** seconds.
4. **Wait a few minutes** and then plug in your PC or connect the battery to your laptop.
5. Press the power button again to reboot your system.
6. **Select the option to boot normally** if you get a notice that the computer shuts down improperly.

 If you still cannot access the desktop, you can try starting your PC in safe mode with the network. When you sign into your Windows system in safe mode with the network, try the next fix below to run the Windows Update troubleshooter.

### Fix 3: Run Windows Update troubleshooter

 Windows Update troubleshooter is a built-in tool that can help you analyze and resolve issues related to Windows updates. Try running Windows Update troubleshooter to see if you can resolve this issue. Here is how to do it:

#### If you’re on Windows 10

1. On your keyboard, press **the Windows logo key** and type **troubleshoot** . In the list of search results, select **Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap465-1.png)
2. In the pop-up window, select **Windows Update** and click **Run the troubleshooter** . You’ll be prompted for permission. Click **Yes** to run Windows Update troubleshooter.  
<!-- affiliate ads begin -->
<a href="https://getlyla.pxf.io/c/5597632/1455723/15391" target="_top" id="1455723"><img src="//a.impactradius-go.com/display-ad/15391-1455723" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1455723/15391" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap466-1.png)
3. Click **Apply this fix** to continue.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap467-1.png)
4. Follow the on-screen instructions to troubleshoot this issue.

#### If you’re using Windows 11

1. On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.
2. From the left navigation panel, select**System** . Find**Troubleshoot** and click on it.  
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot.jpg)
3. Click**Other troubleshooters** .  
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters.jpg)
4. Click on the**Run** button next to Windows Update. Then wait for it to troubleshoot your issues.  
![](https://www.drivereasy.com/wp-content/uploads/2023/11/win11-run-Windows-Update-troubleshooter.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
 Perform a Windows update again to see if you can install the update. If this issue reappears, try the next fix, below.

### Fix 4: Reset Windows Update components

 If Windows Update components are corrupted, Windows Update may not work properly. Maybe that’s the reason behind this issue. To resolve it, try resetting Windows Update components. Here is how to do it:

1. On your keyboard, press **the Windows logo key** and **R** at the same time to invoke the Run dialog. Type **cmd** and press **Ctrl** , **Shift** and **Enter** at the same time to **run Command Prompt as administrator** . You’ll be prompted for permission. Click **Yes** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap468-1.png)
2. In Command Prompt, type the command lines below and press Enter on your keyboard after typing each:  

 net stop bits  
 net stop wuauserv  
 net stop appidsvc  
 net stop cryptsvc  

 Note: The Windows Update-related system services will be stopped after executing the command lines above.
3. In Command Prompt, type the following command lines and press Enter after typing each:  

 ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old  
 ren %systemroot%\\system32\\catroot2 catroot2.old  

 Note: You will rename the SoftwareDistribution and catroot2 folder as SoftwareDistribution.old and catroot2.old after you run these two command lines. These two folders are used by Windows Update to save temporary update files.  

 By renaming these two folders, Windows will think these two folders are missing, and Windows will create new ones to store Windows update files. By doing that, you can avoid many Windows Update issues caused by the old corrupted temporary files in these two folders.
4. In Command Prompt, type the following command lines and press Enter after each:  

 net start bits  
 net start wuauserv  
 net start appidsvc  
 net start cryptsvc  

 Note: After you execute the command lines above, you start the Windows Update-related system services.

 Check to see if this resolves your Windows Update problem. Hopefully, it did. But if not, try the next fix, below.

### Fix 5: Download updates from Microsoft Update Catalog manually

**[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  offers updates for Windows 2000 SP3 and later versions of the Windows operating system. You can try downloading the updates you failed to install from the Microsoft Update Catalog and install them manually to see if you can fix this issue.

 Before you download updates, you need to **check the system type** of your Windows OS. If you don’t know how to do it, follow the instructions below to view your system type:

1. On your keyboard, press **the Windows Logo key** and **R** at the same time to open the Run dialog. Type **cmd** and press **Enter** to open Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap471-1.png)
2. Type the command line **systeminfo** and press **Enter** to view your system type.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap472-1.png)  

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=174416&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.easygifanimator.net/images/gif-animator.png" border="0">Easy GIF Animator is a powerful animated GIF editor and the top tool for creating animated pictures, banners, buttons and GIF videos. You get extensive animation editing features, animation effects, unmatched image quality and optimization for the web. No other GIF animation software matches our features and ease of use, that's why Easy GIF Animator is so popular.</a>
<!-- affiliate ads end -->
 Note: “**X64-based PC** ” indicates that your Windows OS is **64-bit** ; “**X86-based PC** ” means that your Windows OS is **32-bit** .

Now, you can follow the steps below to download Windows updates manually:

1. On your keyboard, press **the Windows logo key** and type **windows update** , then press **Enter** to open **Windows Update** .
2. Click **View update history** to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download that update and install it manually.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap470-1.png)
3. Visit **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)**  .
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
4. Type the update number that you want to download. In this example, type KB3006137 and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap473-1.png)
5. In the list of search results, select the correct update for your operating system and click **Download** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4599951&QTY=1&AFFILIATE=108875&CART=1"><iframe width="864" height="500" src="https://www.youtube.com/embed/jVnfr5HudQw" title="The Latest and Easiest Solution to Remove Kindle DRM on Windows (without Degrading)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
Epubor Ultimate for Win：Helps you read books anywhere, including the best eBook Converter + eBook DRM Removal functions.</a>
<!-- affiliate ads end -->

 Note: If your **Windows OS is 64-bit** , you should download the update whose name contains “**x64-based** ”.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap474-1.png)
6. In the pop-up window, click the link to start downloading the updates.  
<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/Snap475-1.png)
7. **Double-click** the downloaded file and follow the on-screen instructions to install the update.
<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your PC to see if this issue persists. If not, congratulations! You’ve resolved this annoying issue! But if this issue reappears, you can try the last fix, below.

### Pro tip: Want us to fix the problem for you?

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you. All you need to do is [buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/) (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:** Please attach **the URL of this article** when you contact us, so we can help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the **Driver Easy Feedback tool** . To learn how to use this tool, please visit this link:  
[https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

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
<li><a href="https://extra-support.techidaily.com/new-iphone-hacks-filming-and-modifying-lengthy-video-sequences/"><u>[New] IPhone Hacks  Filming & Modifying Lengthy Video Sequences</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-proper-techniques-to-snag-free-secure-vlc-on-a-mac-device/"><u>[New] Proper Techniques to Snag Free, Secure VLC on a Mac Device</u></a></li>
<li><a href="https://common-error.techidaily.com/a-step-by-step-solution-to-restore-your-windows-11-sound-settings-when-the-volume-wont-respond/"><u>A Step-by-Step Solution to Restore Your Windows 11 Sound Settings When the Volume Won't Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-dns-unresponsive-issues-a-guide-to-fast-fixes-and-solutions/"><u>Addressing 'DNS Unresponsive' Issues: A Guide to Fast Fixes and Solutions</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723012553635-black-desert-pc-issues-resolved-no-more-crashes-here/"><u>Black Desert PC Issues Resolved - No More Crashes Here</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fix-for-non-responsive-lenovo-mouse-pads-on-various-windows-systems/"><u>Comprehensive Fix for Non-Responsive Lenovo Mouse Pads on Various Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/display-compatibility-issue-hdcp-free-screen-resolution/"><u>Display Compatibility Issue: HDCP-Free Screen Resolution</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-the-common-disk-write-error-in-steam-platform/"><u>Effortless Fixes for the Common 'Disk Write Error' In Steam Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-gaming-experience-on-steam-fixing-installation-and-update-hiccups-swiftly/"><u>Error-Free Gaming Experience on Steam - Fixing Installation and Update Hiccups Swiftly</u></a></li>
<li><a href="https://video-capture.techidaily.com/expert-tips-for-high-quality-minecraft-saves/"><u>Expert Tips for High-Quality Minecraft Saves</u></a></li>
<li><a href="https://common-error.techidaily.com/ftdisk-system-warning-how-incorrect-driver-installation-affects-memory-safety/"><u>FTDisk System Warning: How Incorrect Driver Installation Affects Memory Safety</u></a></li>
<li><a href="https://tools.techidaily.com/wondershare/drfone/ios-screen-mirror/"><u>iOS Screen Mirror</u></a></li>
<li><a href="https://extra-information.techidaily.com/iphoneandroid-stabilization-elite-photo-tripods/"><u>IPhone/Android Stabilization  Elite Photo Tripods</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-common-problems-with-keyboard-light-features-on-mac-and-windows-devices/"><u>Overcoming Common Problems with Keyboard Light Features on Mac and Windows Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-frozen-updates-on-outdated-operating-systems-latest-solutions-for-users-seeking-assistance-in-the-year-of-our-lord-two-thousand-and-twenty-four-g85/"><u>Overcoming Frozen Updates On Outdated Operating Systems – Latest Solutions for Users Seeking Assistance In The Year Of Our Lord Two Thousand And Twenty Four (Guide, Helpful Tips & Troubleshooting Steps)</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/pokemon-go-error-12-failed-to-detect-location-on-nokia-c12-drfone-by-drfone-virtual-android/"><u>Pokemon Go Error 12 Failed to Detect Location On Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quickly-restore-missing-bluetooth-on-your-windows-11-pc-with-ease/"><u>Quickly Restore Missing Bluetooth on Your Windows 11 PC with Ease!</u></a></li>
<li><a href="https://program-issues.techidaily.com/red-dead-redemption-2-performance-improved-pc-crashes-no-longer-an-issue/"><u>Red Dead Redemption 2 Performance Improved: PC Crashes No Longer an Issue</u></a></li>
<li><a href="https://win-howtos.techidaily.com/steam-game-troubles-tackling-installation-and-updating-problems-efficiently/"><u>Steam Game Troubles: Tackling Installation & Updating Problems Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/strategies-for-addressing-the-device-is-not-ready-error-swiftly/"><u>Strategies for Addressing The Device Is Not Ready Error Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207757346-troubleshoot-and-solve-call-of-duty-world-war-iis-persistent-error-code-angs-12320/"><u>Troubleshoot and Solve Call of Duty: World War II's Persistent Error Code Angs 12320</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-non-functional-usb-ports-on-windows-10-and-11/"><u>Troubleshooting and Fixing Non-Functional USB Ports on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-re-enable-your-devices-wireless-features/"><u>Troubleshooting Steps to Re-Enable Your Device's Wireless Features</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-your-ps4s-sound-problems-expert-guide-to-identifying-and-fixing/"><u>Understanding Your PS4's Sound Problems: Expert Guide to Identifying and Fixing</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206539025-unstuck-from-microsoft-store-problems-heres-how-to-open-it-successfully/"><u>Unstuck From Microsoft Store Problems? Here's How to Open It Successfully</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-in-2024-the-best-free-avi-video-rotators-a-comprehensive-multi-platform-review/"><u>Updated In 2024, The Best Free AVI Video Rotators A Comprehensive Multi-Platform Review</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211824429-wacom-pen-issues-heres-your-guide-to-fix-it-in-windows-11-and-windows-10/"><u>Wacom Pen Issues? Here's Your Guide to Fix It in Windows 11 and Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205644040-windows-11-update-why-cant-i-print-to-pdf-with-microsoft-heres-help/"><u>Windows 11 Update: Why Can't I Print to PDF with Microsoft? Here’s Help</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-10-reset-failures-expert-fixes-for-pc-restoration-errors-in-depth-guide/"><u>Winning Against Windows 10 Reset Failures: Expert Fixes for PC Restoration Errors [In-Depth Guide]</u></a></li>
</ul></div>
