---
title: Correctly Resolving 'The Program Can’t Start, Error Code Is 0xC000007B' - A Comprehensive Fixer
date: 2024-08-15T11:05:33.567Z
updated: 2024-08-16T11:05:33.567Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Correctly Resolving 'The Program Can’t Start, Error Code Is 0xC000007B' - A Comprehensive Fixer
excerpt: This Article Describes Correctly Resolving 'The Program Can’t Start, Error Code Is 0xC000007B' - A Comprehensive Fixer
thumbnail: https://thmb.techidaily.com/63775cec08bea1f18045b716f908366237290c85d227f82f60742199283d96d9.jpg
---

## Unraveling the Mystery Behind .NET Framework 3.5'S Error Code 0X800F081F - Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8a7b95c3a7.png)

 If you are seeing an error code**0x800F081F** when you try to install .NET Framework 3.5 on your Windows computer, you are not alone. Many Windows users are reporting it. But the good news is you can fix this error. Here are two fixes you can try:

 Method 1:[**Configure Group Policy**](https://tools.techidaily.com/drivereasy/download/)
 Method 2:[**Install .NET Framework 3.5 using DISM**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Configure Group Policy

 The 0x800F081F error may occur because the component setting in Group Policy is disabled. You should enable it to see if this fixes the error. To do so:

**1)** On your keyboard, press the   **Windows logo key![](https://images.drivereasy.com/wp-content/uploads/2017/08/img_59a516b53b983.png)**  and**R** **key** at the same time to invoke the Run box.

**2)**  Type “**gpedit.msc** ” and press**Enter** on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b46182da0.png)

**3)**  Go to **Computer Configuration -> Administrative Templates -> System** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8b4b628c80.jpg)

**4)** Double click **Specify settings for optional component installation and component repair** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cb90d9ace.jpg)

**5)** Select**Enabled** . Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8cd1538e66.jpg)

**6)** Try installing .NET Framework 3.5\. If this method works for you, you won’t see the error again. Otherwise, you should try the method below.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1821134/17882" target="_top" id="1821134"><img src="//a.impactradius-go.com/display-ad/17882-1821134" border="0" alt="" width="320" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1821134/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=40085955&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f702defbc67edb455949f46babab0c18/products/2_logo9.png" border="0">FX PRO (Gold Robot + Silver Robot(Basic Package))</a>
<!-- affiliate ads end -->

**5)**  Try installing .NET Framework 3.5 and see if the error disappears.

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
<li><a href="https://common-error.techidaily.com/fixed-failed-to-initialize-unity-graphics-error/"><u>[Fixed] Failed to Initialize Unity Graphics Error</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-chromes-favorite-video-clippers-from-facebook-for-2024/"><u>[New] Chromes' Favorite Video Clippers From Facebook for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-craft-compelling-snapchats-on-ios-and-android-top-6-apps-for-2024/"><u>[New] Craft Compelling Snapchats on iOS & Android - Top 6 Apps for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-streamline-fb-video-downloads-the-best-firefox-plugins-and-tools-of-the-year/"><u>[New] In 2024, Streamline FB Video Downloads  The Best Firefox Plugins and Tools of the Year</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-in-depth-insight-on-effortless-photo-and-video-importers-in-windows-10/"><u>[New] In-Depth Insight on Effortless Photo & Video Importers in Windows 10</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-cinematic-mastery-starts-here-the-best-cameras-of-all-levels/"><u>[Updated] 2024 Approved  Cinematic Mastery Starts Here  The Best Cameras of All Levels</u></a></li>
<li><a href="https://location-social.techidaily.com/4-feasible-ways-to-fake-location-on-facebook-for-your-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>4 Feasible Ways to Fake Location on Facebook For your Honor X50 GT | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/a-shared-gaming-experience-for-everyone/"><u>A Shared Gaming Experience for Everyone</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-strategies-to-correctly-address-error-code-31-on-a-windows-machine/"><u>Comprehensive Strategies to Correctly Address Error Code 31 on a Windows Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminating-the-unwanted-mouse-double-click-problem-expert-advice/"><u>Eliminating the Unwanted Mouse Double-Click Problem: Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-tips-for-repairing-unresponsive-fn-buttons-on-dell-computers/"><u>Essential Tips for Repairing Unresponsive FN Buttons on Dell Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-error-code-0x887a0006-instantly-a-step-by-step-guide/"><u>Fix Error Code 0X887A0006 Instantly: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-dells-locked-function-key-back-to-work-expert-fixes-and-tips/"><u>Getting Your Dell's Locked Function Key Back to Work: Expert Fixes & Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-repairing-https-errors-and-securing-firefox-connections-effectively/"><u>Guide: Repairing HTTPS Errors and Securing Firefox Connections Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/hacked-out-the-launch-glitches-in-fortnite/"><u>Hacked Out the Launch Glitches in Fortnite</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-detect-and-remove-spyware-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>How to Detect and Remove Spyware on Google Pixel 8? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-easily-troubleshoot-a-windows-update-that-wont-go-past-0/"><u>How to Easily Troubleshoot a Windows Update That Won't Go Past 0%%</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-class-not-registered-errors-on-windows-10/"><u>How to Fix 'Class Not Registered' Errors on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-revive-audio-output-on-an-acer-laptop-with-no-sound-issues/"><u>How to Revive Audio Output on an Acer Laptop with No Sound Issues</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-vivo-y02t-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Vivo Y02T online without jailbreak</u></a></li>
<li><a href="https://common-error.techidaily.com/icue-no-device-trouble-heres-how-you-can-fix-it/"><u>ICUE 'No Device' Trouble? Here's How You Can Fix It!</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-unleash-creativity-with-ezvides-tool-for-capturing-your-desktop/"><u>In 2024, Unleash Creativity with EZvide's Tool for Capturing Your Desktop</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-unlocking-the-potential-in-your-podcasts-xml-structure/"><u>In 2024, Unlocking the Potential in Your Podcast's XML Structure</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-restoring-functionality-to-windows-keyboards-with-sticking-keys/"><u>Mastering the Art of Restoring Functionality to Windows Keyboards with Sticking Keys.</u></a></li>
<li><a href="https://common-error.techidaily.com/night-light-feature-malfunction-on-recent-windows-versions-solutions-and-fixes-inside/"><u>Night Light Feature Malfunction on Recent Windows Versions - Solutions and Fixes Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/repaired-non-typing-functionality-of-keyboard/"><u>Repaired: Non-Typing Functionality of Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-woes-expert-tips-for-fixing-error-code-0x8024200d-during-updates-includes-video-guide/"><u>Resolve Your Windows Woes: Expert Tips for Fixing Error Code 0X8024200d During Updates [INCLUDES VIDEO GUIDE]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-bluetooth-device-connectivity-issues-in-windows-10/"><u>Resolved: Fixing Bluetooth Device Connectivity Issues in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-the-video-playback-failed-error-code-224003/"><u>Resolved: Fixing the 'Video Playback Failed - Error Code 224003'</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-typing-troubles-how-to-fix-non-responsive-letters-on-windows-11-keyboards/"><u>Resolved: Typing Troubles – How To Fix Non-Responsive Letters on Windows 11 Keyboards</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-dilemma-fixing-windows-update-error-code-80070103/"><u>Resolving the Dilemma: Fixing Windows Update Error Code 80070103</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-functionality-to-your-windows-10-touch-display-with-these-simple-fixes/"><u>Restore Functionality to Your Windows 10 Touch Display with These Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210496398-simple-fixes-for-windows-11-users-struggling-with-the-disappearing-bluetooth-feature/"><u>Simple Fixes for Windows 11 Users Struggling with the Disappearing Bluetooth Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-when-your-torrent-fails-to-download-correctly/"><u>Solutions When Your Torrent Fails to Download Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-delayed-key-reactions-on-your-windows-1n-11-pc/"><u>Solving Delayed Key Reactions on Your Windows 1N 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-on-resolving-persistent-system-freezes-and-hangs/"><u>Step-by-Step Tips on Resolving Persistent System Freezes and Hangs</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-disable-touchpad-sync-when-you-connect-an-external-mouse-in-windows-11/"><u>Step-by-Step: Disable Touchpad Sync when You Connect an External Mouse in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210724719-surface-book-pro-n-cam-trouble-on-windows-11-solutions-inside/"><u>Surface Book (Pro N) Cam Trouble on Windows 11 - Solutions Inside!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-ultimate-guide-to-meta-and-omni-versions/"><u>The Ultimate Guide to Meta & Omni Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204732927-tips-for-successful-smartaudio-activation-after-initial-failures-resolved/"><u>Tips for Successful SmartAudio Activation After Initial Failures - Resolved!</u></a></li>
<li><a href="https://common-error.techidaily.com/top-solutions-how-to-overcome-windows-11s-error-0x800f0922-during-updates/"><u>Top Solutions: How to Overcome Windows 11'S Error 0X800F0922 During Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-recovering-from-file-system-corruption-issues/"><u>Troubleshooting and Recovering From File System Corruption Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-destiny-2-solutions-when-the-game-server-wont-connect/"><u>Troubleshooting Destiny 2: Solutions When the Game Server Won't Connect</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-endless-stalling-during-valorant-startup-expert-advice/"><u>Troubleshooting Endless Stalling During Valorant Startup: Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-the-right-click-function-on-a-mouse-in-windows-11/"><u>Troubleshooting Guide: Fixing the Right-Click Function on a Mouse in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-techniques-for-persistent-steam-update-issues/"><u>Troubleshooting Techniques for Persistent Steam Update Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-lenovo-mouse-pad-solutions-for-windows-10-8-and-7-users/"><u>Troubleshooting Your Lenovo Mouse Pad: Solutions for Windows 10, 8, and 7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-why-is-my-touchpad-cursor-missing-on-windows-11/"><u>Troubleshooting: Why Is My Touchpad Cursor Missing on Windows 11?</u></a></li>
<li><a href="https://common-error.techidaily.com/turn-up-the-volume-on-your-racing-experience-solutions-for-silent-playthroughs-in-forza-horizon-4/"><u>Turn Up the Volume on Your Racing Experience: Solutions for Silent Playthroughs in Forza Horizon 4</u></a></li>
</ul></div>
