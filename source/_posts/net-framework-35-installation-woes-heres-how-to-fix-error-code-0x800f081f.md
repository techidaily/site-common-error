---
title: .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F
date: 2024-11-01T22:55:03.220Z
updated: 2024-11-05T09:02:09.827Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F
excerpt: This Article Describes .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F
thumbnail: https://thmb.techidaily.com/fe961e2cb838e9277b3f939887a164216256186200a3f57210ef49bd6287bae1.jpg
---

## .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F

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
<a href="https://appsumo.8odi.net/c/5597632/2105866/7443" target="_top" id="2105866">
  <img src="//a.impactradius-go.com/display-ad/7443-2105866" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105866/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134223/18498" target="_top" id="2134223">
  <img src="//a.impactradius-go.com/display-ad/18498-2134223" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134223/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-cloud.techidaily.com/new-in-2024-big-sur-basics-for-system-and-hardware-enthusiasts/"><u>[New] In 2024, Big Sur Basics for System & Hardware Enthusiasts</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-expert-tips-for-efficient-instagram-to-mp4-transformation/"><u>[New] In 2024, Expert Tips for Efficient Instagram to MP4 Transformation</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-optimize-obs-encoding-quick-solutions/"><u>[New] In 2024, Optimize OBS Encoding Quick Solutions</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-2024-approved-integrating-video-conferencing-within-gmail-ecosystem-with-zoom/"><u>[Updated] 2024 Approved Integrating Video Conferencing Within Gmail Ecosystem with Zoom</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-capturing-virtual-conversations-in-real-time-for-2024/"><u>[Updated] Capturing Virtual Conversations in Real Time for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-toontown-full-analysis-and-tutorial-24-edition/"><u>[Updated] ToonTown Full Analysis & Tutorial '24 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/chrome-errssl-error-troubleshooting-guide-for-secure-connection-issues/"><u>Chrome ERR_SSL Error: Troubleshooting Guide for Secure Connection Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-oppo-reno-10-proplus-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Oppo Reno 10 Pro+ 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-favorite-frameworks-top-instagram-filters/"><u>In 2024, Favorite Frameworks Top Instagram Filters</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-from-your-iphone-13-pro-max-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status From Your iPhone 13 Pro Max</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-dll-errors-focus-on-msvcp140dll/"><u>Overcoming DLL Errors: Focus on MSVCP140.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solution-guide-overcoming-delayed-startcontrol-errors-service-id-1053/"><u>Quick Solution Guide: Overcoming Delayed Start/Control Errors (Service ID 1053)</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-fixing-windows-unable-to-access-system-events-error/"><u>Solution Guide: Fixing 'Windows Unable to Access System Events' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-of-your-unresponsive-laptops-trackpad-or-external-mouse/"><u>Solving the Dilemma of Your Unresponsive Laptop's Trackpad or External Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reconnect-your-airpods-to-windows-10-or-11/"><u>Step-by-Step Guide: Reconnect Your AirPods to Windows 10 or 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-cutting-out-problems-in-logitech-g930-speakersmicrophone/"><u>Step-by-Step Solution for Cutting Out Problems in Logitech G930 Speakers/Microphone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-stubborn-dns-server-top-4-solutions-revealed/"><u>Troubleshooting Your Stubborn DNS Server: Top 4 Solutions Revealed</u></a></li>
<li><a href="https://windows11.techidaily.com/unveiling-systems-peak-performance-limits/"><u>Unveiling System's Peak Performance Limits</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-optimization-tips-for-a-superior-gaming-experience/"><u>Windows 11 Optimization Tips for a Superior Gaming Experience</u></a></li>
</ul></div>

