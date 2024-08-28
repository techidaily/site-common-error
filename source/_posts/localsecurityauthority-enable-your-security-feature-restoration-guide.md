---
title: "LocalSecurityAuthority: Enable Your Security Feature - Restoration Guide"
date: 2024-08-27T13:36:36.658Z
updated: 2024-08-28T13:36:36.658Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes LocalSecurityAuthority: Enable Your Security Feature - Restoration Guide"
excerpt: "This Article Describes LocalSecurityAuthority: Enable Your Security Feature - Restoration Guide"
thumbnail: https://thmb.techidaily.com/2ceae87a9b9364e8de7f8199f6943542799e9e444d1e94cece6744b91d0b78e1.jpg
---

## LSA Safety Measures Fully Operational Again - Secure Your System Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

## Try these fixes to enable the Local Security Authority Protection

 As mentioned, in most cases, your Local Security Authority is off because of a UI bug with a Windows patch, so the first method should be enough to help. If it doesn’t, please move on to methods 2 and 3.

1. **[Install Windows Update patch KB5007651](#m1)**
2. **[Modify Registry Editor](#m2)**
3. **[Configure Group Policy Editor](#m3)**

---

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/300__250banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006118/18460" target="_top" id="2006118"><img src="//a.impactradius-go.com/display-ad/18460-2006118" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006118/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2039292/17094" target="_top" id="2039292"><img src="//a.impactradius-go.com/display-ad/17094-2039292" border="0" alt="BLUETTI NEW LAUNCH AC240" width="954" height="1020"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2039292/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=195080&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrwonder/images/screensaver-software.png" border="0">With Screensaver Wonder you can easily make a screensaver from your own pictures and video files. Create screensavers for your own computer or create standalone, self-installing screensavers for easy sharing with your friends. Together with its sister product Screensaver Factory, Screensaver Wonder is one of the most popular screensaver software products in the world, helping thousands of users decorate their computer screens quickly and easily.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4576829&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/9e740b84bb48a64dde25061566299467/products/copy_1_jp_box_big.png" border="0">Jet Profiler for MySQL, Enterprise Version： Jet Profiler for MySQL is real-time query performance and diagnostics tool for the MySQL database server. Its detailed query information, graphical interface and ease of use makes this a great tool for finding performance bottlenecks in your MySQL databases. </a>
<!-- affiliate ads end -->
## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1047974&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-04_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

 Fortect comes with a 60-day Money-Back Guarantee. If you’re not satisfied with Fortect, you can contact <support@fortect.com> for a full refund.

 Still unsure if Fortect is what you need? Check this [Fortec Review](https://tools.techidaily.com/drivereasy/download/) !

---

 The above is what we have to offer regarding “Local Security Authority protection is off” problem. If you have any other suggestions, please feel free to leave a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-crafting-engaging-gamers-banners-using-pre-made-themes/"><u>[New] 2024 Approved  Crafting Engaging Gamers' Banners  Using Pre-Made Themes</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/new-united-reviews-the-expert-on-easeus/"><u>[New] United Reviews  The Expert on EaseUS</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-buyers-guide-to-exceptional-hdr-photography-equipment/"><u>[Updated] A Buyer's Guide to Exceptional HDR Photography Equipment</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-binge-on-christmas-classics-enjoy-9-whole-film-flicks-no-charge-for-2024/"><u>[Updated] Binge on Christmas Classics  Enjoy 9 Whole-Film Flicks No Charge for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-eco-friendly-recorder-ads-absolved/"><u>[Updated] Eco-Friendly Recorder - Ads Absolved</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/action-camera-faceoff-gopro-hero-vs-yi-4k-new-edition-review-for-2024/"><u>Action Camera Faceoff  GoPro Hero Vs. Yi 4K - New Edition Review for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-and-resolve-unity-graphics-error-during-launch-successfully-now/"><u>Bypass and Resolve Unity Graphics Error During Launch Successfully Now</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-keyboard-revamp-fixes-and-tips-for-restoring-backlight-functionality/"><u>Corsair Keyboard Revamp: Fixes and Tips for Restoring Backlight Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/deciphering-administrative-controls-tweaking-corporate-configurations-in-windows-environment/"><u>Deciphering Administrative Controls: Tweaking Corporate Configurations in Windows Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/dell-laptop-keyboard-malfunction-heres-the-step-by-step-solution/"><u>Dell Laptop Keyboard Malfunction? Here's the Step-by-Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-for-non-functional-hp-laptop-cameras-in-the-windows-10-operating-system/"><u>DIY Fixes for Non-Functional HP Laptop Cameras in the Windows 10 Operating System</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/dxgkrnlsys-windows-freeze-success-story/"><u>dxgkrnl.sys Windows Freeze - Success Story</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/easy-installation-how-to-get-hp-officejet-5740-drivers-on-windows-11-10-or-8/"><u>Easy Installation: How to Get HP Officejet 5740 Drivers on Windows 11, 10 or 8</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-realme-narzo-60x-5g-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Realme Narzo 60x 5G in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-repair-techniques-for-windows-n-utilizing-system-file-checker-and-deployment-image-services/"><u>Effective Repair Techniques for Windows N: Utilizing System File Checker & Deployment Image Services</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x80004005-decoded-understanding-and-solving-unspecified-issues/"><u>Error 0X80004005 Decoded: Understanding and Solving Unspecified Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-semaphore-timeout-period-error-resolution-causes-for-0x80070079/"><u>Expert Advice on 'Semaphore Timeout Period' Error Resolution, Causes for 0X80070079</u></a></li>
<li><a href="https://howto.techidaily.com/fix-unfortunately-settings-has-stopped-on-lenovo-thinkphone-quickly-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Unfortunately Settings Has Stopped on Lenovo ThinkPhone Quickly | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-invalid-directory-name-issue-a-comprehensive-guide/"><u>Fixing the 'Invalid Directory Name' Issue - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-chrome-errsslprotocolerror-for-smooth-browsing/"><u>How to Correctly Address 'Chrome ERR_SSL_PROTOCOL_ERROR' For Smooth Browsing</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-pictures-from-oneplus-open-by-fonelab-android-recover-pictures/"><u>How to recover deleted pictures from OnePlus Open.</u></a></li>
<li><a href="https://techidaily.com/how-to-reset-realme-12-proplus-5g-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Reset Realme 12 Pro+ 5G without Losing Data | Dr.fone</u></a></li>
<li><a href="https://techtrends.techidaily.com/hulus-errorrununk13-bug-easy-fixes-and-workarounds/"><u>Hulu's ERROR_RUNUNK13 Bug: Easy Fixes and Workarounds</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-honor-90-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Honor 90 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-xiaomi-redmi-k70-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Xiaomi Redmi K70 Phone Network-Ready</u></a></li>
<li><a href="https://extra-information.techidaily.com/initiating-seamless-zoom-gatherings/"><u>Initiating Seamless Zoom Gatherings</u></a></li>
<li><a href="https://common-error.techidaily.com/is-my-netflix-not-working-top-tips-for-restoring-video-playback-quickly/"><u>Is My Netflix Not Working? Top Tips for Restoring Video Playback Quickly</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/monetary-returns-for-one-million-youtube-watchers/"><u>Monetary Returns for One Million YouTube Watchers</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-opencl-dynamic-link-deficiencies/"><u>Overcoming OpenCL Dynamic Link Deficiencies</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-touchpad-glitches-making-your-windows-11-pad-responsive-again/"><u>Overcoming Touchpad Glitches: Making Your Windows 11 Pad Responsive Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/pubg-game-crash-resolving-non-loading-buildings-for-smoother-playtime/"><u>PUBG Game Crash: Resolving Non-Loading Buildings for Smoother Playtime</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-common-problems-with-windows-key-plus-shift-plus-s-on-windows-operating-systems-windows-11-and-10/"><u>Resolving Common Problems with Windows Key + Shift + S on Windows Operating Systems (Windows 11 and 10)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-error-code-1000-across-win7-win8-and-win10-a-comprehensive-guide/"><u>Resolving Error Code 1000 Across Win7, Win8 & Win10: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-steps-to-overcome-a-black-screen-on-google-chrome/"><u>Resolving the Issue: Steps to Overcome a Black Screen on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-provided-trouble-in-establishing-connection-between-windows-and-sensvc/"><u>Solution Provided: Trouble in Establishing Connection Between Windows and SENSVC</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-unresponsive-keyboard-arrows-how-to-restore-functionality/"><u>Solutions for Unresponsive Keyboard Arrows – How to Restore Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-unable-to-connect-issues-with-a-remote-server-a-step-by-step-guide/"><u>Solving 'Unable to Connect' Issues with a Remote Server: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-resolving-common-issues-in-call-of-duty-black-ops-4/"><u>Step-by-Step Tutorial: Resolving Common Issues in Call of Duty Black Ops 4</u></a></li>
<li><a href="https://win-howtos.techidaily.com/the-ultimate-fix-for-when-your-dell-computers-usb-port-stops-responding/"><u>The Ultimate Fix for When Your Dell Computer's USB Port Stops Responding</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/thriving-on-youtube-using-creative-studio-tools/"><u>Thriving on YouTube Using Creative Studio Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-event-id-1000-across-windows-vista7810-a-comprehensive-guide/"><u>Troubleshooting Event ID 1000 Across Windows Vista/7/8/10: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-oddworld-soulstorm-pc-overcoming-crash-problems-and-playing-smoothly/"><u>Troubleshooting Oddworld: Soulstorm [PC] – Overcoming Crash Problems & Playing Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-application-failed-to-initialize-correctly-overcoming-the-0xc000007b-hurdle/"><u>Troubleshooting Tips for 'Application Failed to Initialize Correctly' – Overcoming the 0xC000007B Hurdle</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-2024-approved-pc-video-dubbing-made-easy-top-software-options/"><u>Updated 2024 Approved PC Video Dubbing Made Easy Top Software Options</u></a></li>
<li><a href="https://video-capture.techidaily.com/voice-customization-made-simple-with-these-top-apps/"><u>Voice Customization Made Simple with These Top Apps</u></a></li>
</ul></div>
