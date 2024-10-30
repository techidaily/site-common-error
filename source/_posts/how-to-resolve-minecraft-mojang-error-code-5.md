---
title: How to Resolve Minecraft Mojang Error Code 5
date: 2024-10-25T17:34:45.485Z
updated: 2024-10-30T16:04:37.391Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Resolve Minecraft Mojang Error Code 5
excerpt: This Article Describes How to Resolve Minecraft Mojang Error Code 5
thumbnail: https://thmb.techidaily.com/fea6185edc685da72ba963a46eed57a3a71d461697393364ab3bd89b9977de72.jpg
---

## Resolving the Critical Installer Crash - How to Fix Error Code 1603

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca1709cae9.png)

You may encounter an error with a code of **1603** when you are attempting to install something on your Windows. The error message is basically something like “**Error: -1603 Fatal error during installation.**” It usually occurs when you are using a Windows Installer package to install the program. You can try the methods below that can be help you fix the error. **1)[Change installation location](https://tools.techidaily.com/drivereasy/download/)**   **2) [Completely uninstall the same program installed](https://tools.techidaily.com/drivereasy/download/)**   **3)[Start and re-register Microsoft Installer service](https://tools.techidaily.com/drivereasy/download/)**   **4)[Acquire full permissions on the drive for installation](https://tools.techidaily.com/drivereasy/download/)**

## 1) Change installation location

You may encounter an error 1603 because the installation location is you choose is not available due to various reasons — such as being encrypted. You can use another installation folder to install the program and see if the error is gone.

## 2) Completely uninstall the same program installed

If you have previously installed the same program (or its earlier version), the error can occur when you try to install the application again. If you want to install your program successfully, you need to perform a **clean uninstall** of the one installed on your computer. This means you need to remove all the temporary files and preferences it leaves in addition to the major program. Sometimes you may lose the desktop shortcut of a program due to some reasons and therefore you may forget that you have installed it. In this case you can go to**Control Panel**to check if it is still on your computer: Press**Win + R**, and enter “ _**control**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9bf012d25.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868499/19272" target="_top" id="1868499">
  <img src="//a.impactradius-go.com/display-ad/19272-1868499" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868499/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Find and open**Programs and Features**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9c81105c5.png)

Then you can check if the application is listed here. If it is, uninstall it.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595c9d00544d7.png)

## 3) Start and re-register Microsoft Installer service

There may be something going wrong with**Microsoft Installer service**and therefore resulting in error 1603\. You can fix the problem by (re)starting and re-registering Microsoft Installer service. To**start**Windows Installer service:**a)** Press**Win + R**and enter “_**services.msc**_“;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca68fd8714.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012420/19272" target="_top" id="2012420">
  <img src="//a.impactradius-go.com/display-ad/19272-2012420" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012420/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**b)** Find and double click on**Windows Installer**;

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca70c399c1.png)

**c)** Hit**Start**button under**Service status**and hit**OK**. (If its service status is**running**, you should click on**Stop**first and then hit**Start**.)

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca7cbbdf36.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135401/19272" target="_top" id="2135401">
  <img src="//a.impactradius-go.com/display-ad/19272-2135401" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135401/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

To**re-register**Windows Installer service:**a)** Press**Win + R**, type “_**msiexec /unregister**_” and hit**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9370d810.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151873/7443" target="_top" id="2151873">
  <img src="//a.impactradius-go.com/display-ad/7443-2151873" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**b)** Press**Win + R** again and enter “ _**msiexec /regserve** **r**_ “.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595ca9952ad21.png)

## 4) Acquire full permissions on the drive for installation

It is possible that the error 1603 occurs because you don’t have**full permissions**on the file location. Try getting the permissions on the drive you are installing your application to and see if this fixes the problem.**a)** Open**File Explorer**, right click on the drive containing the installation location and select**Properties**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cac402cfce.png)

**b)** Go to**Security**tab and click on**Edit**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595caf24696ae.png)

**c)** Single click on **SYSTEM**and ensure that the**Allow**box of every item in**Permissions for SYSTEM** is checked (if it is checkable). Do the same check for**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb123f210b.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037355/7443" target="_top" id="2037355">
  <img src="//a.impactradius-go.com/display-ad/7443-2037355" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037355/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**d)** Click on**OK**to go back to**Properties**dialog. Then click on**Advanced**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb3cf25a0c.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**e)** Click on**Change Permissions**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb5c235c54.png)

**f)** On**Permissions**tab, double click on**Administrators**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb67382950.png)

**g)** Select**This folder, subfolders and files**for**Applies to**field and**tick** **all the available basic permissions**. After that hit**OK**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb7074c180.png)

**h)** Do the same operation above for**SYSTEM**.

![](https://images.drivereasy.com/wp-content/uploads/2017/07/img_595cb8202ef5a.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**i)** Click on**OK** all the way out. Now you have acquired full permissions on this drive. Try installing your application and see if the issue is fixed.

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
<li><a href="https://common-error.techidaily.com/1723208435044-fixed-this-device-is-not-present-code-24-windows-10-8-or-7/"><u>[Fixed] This Device Is Not Present (Code 24) – Windows 10, 8 or 7</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-unveiling-tv-friendly-practices-for-facebook-lives/"><u>[Updated] 2024 Approved Unveiling TV-Friendly Practices for Facebook Lives</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-download-free-youtube-pics-and-templates/"><u>[Updated] In 2024, Download Free YouTube Pics & Templates</u></a></li>
<li><a href="https://discover-great.techidaily.com/a-comprehensive-guide-to-converting-dvd-movies-into-compatible-quicktime-format-for-apples-technology/"><u>A Comprehensive Guide to Converting DVD Movies Into Compatible QuickTime Format for Apple's Technology</u></a></li>
<li><a href="https://sound-issues.techidaily.com/best-troubleshooting-steps-when-toshiba-laptop-fails-to-produce-sound/"><u>Best Troubleshooting Steps When Toshiba Laptop Fails to Produce Sound</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-when-experiencing-audio-interruptions-in-logitech-g930-headset/"><u>Effective Fixes When Experiencing Audio Interruptions in Logitech G930 Headset</u></a></li>
<li><a href="https://win-dash.techidaily.com/excel-basics-revealed-configuring-preferred-font-style-and-dimensions-for-fresh-spreadsheets/"><u>Excel Basics Revealed: Configuring Preferred Font Style and Dimensions for Fresh Spreadsheets</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-solve-the-persistent-windows-update-error-code-0x8007001f/"><u>Expert Tips to Solve the Persistent Windows Update Error Code 0X8007001f</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-clear-visuals-ahead-mastering-your-logitech-webcams-capabilities/"><u>In 2024, Clear Visuals Ahead Mastering Your Logitech Webcam's Capabilities</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-writable-obstacle-of-0x-pointed-out-memory-slot/"><u>Overcoming the Writable Obstacle of 0X Pointed-Out Memory Slot</u></a></li>
<li><a href="https://win-net.techidaily.com/paso-a-paso-como-actualizar-correctamente-tu-sistema-windows-11-sin-perdida-de-datos/"><u>Paso a Paso: Cómo Actualizar Correctamente Tu Sistema Windows 11 Sin Pérdida De Datos</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-a-faster-computer-proven-strategies-to-improve-system-performance/"><u>Quick Fixes for a Faster Computer: Proven Strategies to Improve System Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-when-your-corsair-keyboard-stops-working-correctly/"><u>Solution Steps for When Your Corsair Keyboard Stops Working Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/system-stabilizes-after-games-end/"><u>System Stabilizes After Games End</u></a></li>
<li><a href="https://win-bytes.techidaily.com/the-best-methods-for-moving-images-from-your-iphone-6-or-6s-to-pc/"><u>The Best Methods for Moving Images From Your iPhone 6 or 6S to PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-dealing-with-unresponsive-web-browsers/"><u>Troubleshooting Guide: Dealing with Unresponsive Web Browsers</u></a></li>
<li><a href="https://facebook.techidaily.com/uncovering-digital-tracings-a-detailed-examination-and-account-summary-on-fb/"><u>Uncovering Digital Tracings: A Detailed Examination and Account Summary on FB</u></a></li>
</ul></div>

