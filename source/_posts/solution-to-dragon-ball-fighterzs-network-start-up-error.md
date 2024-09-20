---
title: Solution to Dragon Ball FighterZ's Network Start-Up Error
date: 2024-09-16T17:02:42.117Z
updated: 2024-09-20T18:39:19.854Z
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

## Method 2: Enable the .NET Framework 3.5 feature using DISM

 It is also possible that the error occurs because the .NET Framework 3.5 feature has not been enabled in your system. You can use a DISM command to enable it.

**NOTE** : You need to have installation media or an ISO image for your Windows version to perform this method.

To enable the .NET Framework 3.5 feature using DISM:

**1)** Put the Windows installation media into your computer, or mount the Windows ISO image in your system.

**2)** Press the**Windows logo key** on your keyboard. Then type “**_cmd_** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b7455a57b7b.png)

**3)** Right-click “**Command Prompt** ” and select “**Run as administrator** “.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b75954000f6.png)

**4)** Type “ _**Dism /online /enable-feature /featurename:NetFx3 /All /Source:**_ **<DRIVE>** _**:\\sources\\sxs /LimitAccess**_ ” and press**Enter** on your keyboard. (Note that you need to replace the**<DRIVE>** here with the drive letter for the installation media drive or the ISO drive.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b8d9fc19402.png)

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
<li><a href="https://digital-screen-recording.techidaily.com/new-top-multi-user-platforms-for-effective-talks-for-2024/"><u>[New] Top Multi-User Platforms for Effective Talks for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-realme-narzo-n53-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Realme Narzo N53 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/explorer-down-restore-it-now/"><u>Explorer Down? Restore It Now!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-nokia-c300-mirror-screen-to-pc-drfone-by-drfone-android/"><u>How Nokia C300 Mirror Screen to PC? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-hang-ups-in-windows-11-for-smooth-operation/"><u>Overcoming Hang-Ups in Windows 11 for Smooth Operation</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ering-the-way-with-innovative-approaches-to-youtube-banners-for-2024/"><u>Pioneering the Way with Innovative Approaches to YouTube Banners for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/restore-missing-app-icon-on-samsung-galaxy-a15-5g-step-by-step-solutions-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Restore Missing App Icon on Samsung Galaxy A15 5G Step-by-Step Solutions | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-usb-tethering-setup-on-windows-10-made-simple/"><u>Seamless USB Tethering Setup on Windows 10 Made Simple</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722964302911-speedy-install-grab-your-ftdi-chip-usb-to-rs232-serial-driver-today/"><u>Speedy Install: Grab Your FTDI Chip USB to RS232 Serial Driver Today!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

