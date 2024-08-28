---
title: Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
date: 2024-08-27T13:49:52.943Z
updated: 2024-08-28T13:49:52.943Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
excerpt: This Article Describes Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
thumbnail: https://thmb.techidaily.com/b024a84a41e25a10e99a735d71f0138708aa747c63be7c3be4720f86eba5080f.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

### Method 1: Using Group Policy Editor

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) Type **gpedit.msc**  and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279bde5ee8d.png)

**Note:**  If you cannot find gpedit.msc on your Windows 10,[here is the method to got it.](https://tools.techidaily.com/drivereasy/download/)
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``
 3) Go to **Computer Configuration** \> **Administrative** **Templates** \>**Windows Components** \> **Data Collection and Preview Builds** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``

 5) Select **Disabled** , then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279d1cdc304.jpg)

 6) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.  
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` `` `
` `
` `
` `
` `
` `
` `
` `
` `
`

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

4) Reboot your Windows 10 PC.

5) On your keyboard, press the **Ctrl**  +**Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

 **Note:** If you can’t find gpedit.msc on your Windows 10 computer, here’s how you can get it: 1\. Download gpedit.msc(Group Policy Editor) from Internet  
 2\. When it’s done, Go to C:\\Windows\\SysWOW64, and copy the followings:  
 folders: GroupPolicy  
 GroupPolicyUsers  
 gpedit.msc(console document)  
 3\. Paste them in the following locations:  
 C:\\Windows\\System  
 C:\\Windows\\System32

 Hopefully this article could help you fix the problem. Feel free to comment below with your own experiences.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-essential-online-websites-for-acquiring-thrones-rhythms/"><u>[New] In 2024, Essential Online Websites for Acquiring Thrones Rhythms</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-in-2024-the-photographers-edge-innovating-with-instagrams-bokeh-features/"><u>[New] In 2024, The Photographer's Edge  Innovating with Instagram’s Bokeh Features</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-superior-third-ranked-ipad-recording-apps-for-2024/"><u>[New] Superior Third-Ranked iPad Recording Apps for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-video-editing-tips-for-beginner-editors/"><u>[New] YouTube Video Editing Tips for Beginner Editors</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2024-approved-protecting-ideas-avoidance-of-rash-removals/"><u>[Updated] 2024 Approved  Protecting Ideas  Avoidance of Rash Removals</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-fresh-footage-feature-film-reviews/"><u>[Updated] Fresh Footage Feature Film Reviews</u></a></li>
<li><a href="https://android-unlock.techidaily.com/a-perfect-guide-to-remove-or-disable-google-smart-lock-on-motorola-by-drfone-android/"><u>A Perfect Guide To Remove or Disable Google Smart Lock On Motorola</u></a></li>
<li><a href="https://common-error.techidaily.com/accelerate-your-typing-remedy-slow-keyboard-lags-with-these-fixes/"><u>Accelerate Your Typing: Remedy Slow Keyboard Lags with These Fixes</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/affordable-pc-monitoring-software/"><u>Affordable PC Monitoring Software</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/chart-your-course-in-crypto-selecting-the-best-7-art-converters/"><u>Chart Your Course in Crypto - Selecting the Best 7 Art Converters</u></a></li>
<li><a href="https://program-issues.techidaily.com/dauntless-desktop-crash-solved-tips-and-fixes-for-smooth-gaming/"><u>Dauntless Desktop Crash Solved: Tips and Fixes for Smooth Gaming</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/elevate-your-farm-the-top-7-stardew-modifications-for-2024/"><u>Elevate Your Farm  The Top 7 Stardew Modifications for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-gaming-experience-a-step-by-step-origin-setup-guide/"><u>Error-Free Gaming Experience: A Step-by-Step Origin Setup Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204366949-fix-windows-11s-bluetooth-connection-problems-with-these-simple-steps/"><u>Fix Windows 11'S Bluetooth Connection Problems with These Simple Steps!</u></a></li>
<li><a href="https://program-issues.techidaily.com/half-life-alyx-pc-optimization-guide-fixes-for-tackling-frame-drops-and-jittery-playback/"><u>Half-Life: Alyx PC Optimization Guide – Fixes for Tackling Frame Drops and Jittery Playback</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-location-on-facebook-dating-for-your-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>How to Change Location On Facebook Dating for your Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208456509-how-to-do-a-clean-install-of-windows-11-quickly-and-easily/"><u>How to Do a Clean Install of Windows 11, Quickly and Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-elevated-disk-consumption-by-microsofts-telemetry-feature-in-windows-10/"><u>How to Fix Elevated Disk Consumption by Microsoft's Telemetry Feature in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-hosted-wi-fi-connection-problems-on-windows-11/"><u>How to Resolve Hosted Wi-Fi Connection Problems on Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-honor-90-pro-by-drfone-android/"><u>How to Show Wi-Fi Password on Honor 90 Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-your-computer-from-constantly-turning-on-and-off/"><u>How to Stop Your Computer From Constantly Turning On and Off</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208101350-how-to-tackle-excessive-cpu-consumption-by-runtime-broker-on-your-windows-11-pc-solutions-included/"><u>How to Tackle Excessive CPU Consumption by Runtime Broker on Your Windows 11 PC – Solutions Included</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-photos-from-nubia-z50-ultra-to-samsung-galaxy-s21-ultra-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Photos From Nubia Z50 Ultra to Samsung Galaxy S21 Ultra | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-vr-game-creators-to-watch/"><u>In 2024, Top VR Game Creators To Watch</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-trackpad-malfunctions-in-windows-operating-systems-a-comprehensive-fix-for-win1087/"><u>Laptop TrackPad Malfunctions in Windows Operating Systems: A Comprehensive Fix for Win10/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/logitech-g930-cutting-out-heres-how-to-restore-full-functionality/"><u>Logitech G930 Cutting Out? Here's How to Restore Full Functionality!</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/magnify-marvel-the-ultimate-10-camera-lens-guide-for-2024/"><u>Magnify Marvel  The Ultimate 10 Camera Lens Guide for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-shutdown-procedures-troubleshooting-tips-for-a-smooth-exit-in-windows-11-devices/"><u>Mastering Shutdown Procedures: Troubleshooting Tips for a Smooth Exit in Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/miracast-not-supported-by-graphics-driver-fixed/"><u>Miracast: Not Supported by Graphics Driver [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-laptop-compatibility-hurdles-get-your-usb-mouse-working-now/"><u>Overcoming Laptop Compatibility Hurdles – Get Your USB Mouse Working Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-for-typing-issues-how-to-reinitialize-your-keyboard-settings/"><u>Quick Fix for Typing Issues: How to Reinitialize Your Keyboard Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-hosted-network-couldnt-be-started-errors-on-windows-10-computers/"><u>Resolving 'Hosted Network Couldn't Be Started' Errors on Windows 10 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-error-loading-player-issue-with-unavailable-content-on-windows-systems/"><u>Resolving the ‘Error Loading Player’ Issue with Unavailable Content on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-airpods-connection-issue-with-windows-11-top-tips-and-tricks-of-2e24/"><u>Solving the AirPods Connection Issue with Windows 11: Top Tips and Tricks of 2E24</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-overcoming-the-red-screen-challenge-in-windows-11/"><u>Step-by-Step Guide: Overcoming the Red Screen Challenge in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-overcoming-black-ops-n-death-glitches/"><u>Step-by-Step Troubleshooting: Overcoming Black Ops N' Death Glitches</u></a></li>
<li><a href="https://fox-that.techidaily.com/top-6-tips-to-correct-autocorrect-errors-and-improve-your-iphones-typing-accuracy/"><u>Top 6 Tips to Correct AutoCorrect Errors & Improve Your iPhone's Typing Accuracy</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-step-by-step-correcting-error-e80240020-for-successful-windows-10-setup/"><u>Troubleshooting Step-by-Step: Correcting Error E80240020 for Successful Windows 10 Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-how-to-fix-diagnostic-monitoring-service-wont-start/"><u>Troubleshooting Steps: How to Fix 'Diagnostic Monitoring Service Won't Start'</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-tips-for-fixing-windows-11-update-error-0xc1900208/"><u>Ultimate Troubleshooting Tips for Fixing Windows 11 Update Error 0Xc1900208</u></a></li>
<li><a href="https://common-error.techidaily.com/unreals-future-tethered-to-d3d-device-availability/"><u>Unreal's Future Tethered to D3D Device Availability</u></a></li>
<li><a href="https://common-error.techidaily.com/usb-mouse-not-responding-discover-how-to-get-it-working-again/"><u>USB Mouse Not Responding? Discover How to Get It Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-invisible-mouse-buttons-in-windows-10-solutions/"><u>Winning the Battle Against Invisible Mouse Buttons in Windows 10 [Solutions]</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/xml-files-demystified-a-beginners-guide-to-fcpx-for-2024/"><u>XML Files Demystified A Beginners Guide to FCPX for 2024</u></a></li>
</ul></div>
