---
title: Solution to Dragon Ball FighterZ's Network Start-Up Error
date: 2024-09-30T23:28:12.212Z
updated: 2024-10-07T06:41:27.338Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solution to Dragon Ball FighterZ's Network Start-Up Error
excerpt: This Article Describes Solution to Dragon Ball FighterZ's Network Start-Up Error
thumbnail: https://thmb.techidaily.com/50d4bf6106cc2e789648c53429943f049229011e6f572fe9945c7d91985d72b7.jpg
---

## .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8a7b95c3a7.png)

 If you are seeing an error code**0x800F081F** when you try to install .NET Framework 3.5 on your Windows computer, you are not alone. Many Windows users are reporting it. But the good news is you can fix this error. Here are two fixes you can try:

 Method 1:[**Configure Group Policy**](https://tools.techidaily.com/drivereasy/download/)
 Method 2:[**Install .NET Framework 3.5 using DISM**](https://tools.techidaily.com/drivereasy/download/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2043856/7443" target="_top" id="2043856">
  <img src="//a.impactradius-go.com/display-ad/7443-2043856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151865/7443" target="_top" id="2151865">
  <img src="//a.impactradius-go.com/display-ad/7443-2151865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151865/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-learn-to-screen-capture-flawlessly-on-mac-using-just-keys/"><u>[New] In 2024, Learn to Screen Capture Flawlessly on Mac Using Just Keys</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ptimal-options-high-performance-laptops-for-videographers-for-2024/"><u>[New] Optimal Options High-Performance Laptops for Videographers for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/can-i-recover-permanently-deleted-photos-from-k11-5g-by-stellar-photo-recovery-android-mobile-photo-recover/"><u>Can I recover permanently deleted photos from K11 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-non-functional-laptop-trackpad-on-windows-10-8-and-7-step-by-step-solutions/"><u>Fix Your Non-Functional Laptop Trackpad on Windows 10, 8 & 7: Step by Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-fortnite-initial-start-up-problems/"><u>Fixed Fortnite Initial Start-Up Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-initializing-hurdle-in-destiny-2-comprehensive-fix-guide/"><u>Fixing the 'Initializing' Hurdle in Destiny 2 - Comprehensive Fix Guide</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/freefall-into-success-top-hashtags-and-vlogging-techniques/"><u>FreeFall Into Success Top Hashtags and Vlogging Techniques</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-on-samsung-galaxy-a05-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock on Samsung Galaxy A05 Phones with/without a PC</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-getting-the-pokemon-go-gps-signal-not-found-11-error-in-vivo-s17-pro-drfone-by-drfone-virtual/"><u>In 2024, Getting the Pokemon Go GPS Signal Not Found 11 Error in Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-11-solutions-for-missing-class-registration-issues/"><u>Mastering Windows 11: Solutions for Missing Class Registration Issues</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-from-still-to-stunning-how-to-achieve-the-ken-burns-effect-for-2024/"><u>New From Still to Stunning How to Achieve the Ken Burns Effect for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-failed-directx-graphics-driver-instantiation/"><u>Overcoming the Challenge of Failed DirectX Graphics Driver Instantiation</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-fixing-mouse-right-click-problems-in-windows-11/"><u>Step-by-Step Solutions for Fixing Mouse Right-Click Problems in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/top-12-playeres-de-dvd-free-para-windows-11-guia-completo-do-winxdvd/"><u>Top 12 Playeres De DVD Free Para Windows 11: Guia Completo Do WinXDVD</u></a></li>
<li><a href="https://blog-min.techidaily.com/ultimate-guide-the-most-effective-h265-codec-tools-and-services-for-windowsmac-users/"><u>Ultimate Guide: The Most Effective H.265 Codec Tools & Services for Windows/Mac Users</u></a></li>
</ul></div>

