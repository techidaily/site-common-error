---
title: Resolving 'No Device Drivers Detected' Error During Windows 7 Setup
date: 2024-08-09T00:49:27.950Z
updated: 2024-08-10T00:49:27.950Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving 'No Device Drivers Detected' Error During Windows 7 Setup
excerpt: This Article Describes Resolving 'No Device Drivers Detected' Error During Windows 7 Setup
thumbnail: https://thmb.techidaily.com/e082df8e991a0ed032e389702a1a1fbbc04b4810305a265213fc94683f22a3e9.jpg
---

## Guide to Restarting Your Windows Update Service – Problems Solved

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718728&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/vMixCallScreenshot1-large.jpg" border="0"> vMix Basic HD - Software based live production. vMix Basic HD includes 4 inputs, 3 cameras, streaming, recording, playlist. 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb080685ea1.png)

 Many Windows users are having an issue with their Windows Update. If they check for updates on their Windows system, they get an error that says “ **Windows Update cannot currently check for updates, because the service is not running** “. And they can’t install updates for their system.

 This is an annoying issue. And trying to fix it is just as annoying, because you’ll spend a lot of time reading suggestions on the Internet, and most won’t work.

 But don’t worry. The following are some methods that have helped many Windows users fix their error.

### Try these fixes

 You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Run Windows Update troubleshooter**](#a)
2. [**Check for malicious software**](#b)
3. [**Restart your Windows Update associated services**](#c)
4. [**Clear the SoftwareDistribution folder**](#d)
5. [**Update your device drivers**](#e)

## Method 1: Run Windows Update troubleshooter

 Windows has a built-in troubleshooter that can check and fix issues with Windows Update. You should run it when an error occurs on your Windows Update. To do so:

### on Windows 10

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** Select**Update & Security** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4715391&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2023/10/Windows-10-Update-and-Security.jpg)

**2)** Click**Troubleshoot > Additional troubleshooters** .

**3)** Find**Windows Update** and click**Run the troubleshooter** .

**4)** Follow the on-screen instructions to complete the troubleshooting process.

**5)** Run your Windows Update again and see if your error is fixed.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
### on Windows 11

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** From the left navigation panel, select**System** . Click**Troubleshoot** .

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot-1200x699.jpg)

**3)** Click**Other troubleshooters** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters-1200x699.jpg)

**4)** Click on the**Run** button next to**Windows Update** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-Troubleshooter-Windows-Update-1200x616.jpg)

**5)** Follow the on-screen instructions to complete the troubleshooting process.

**6)** Run your Windows Update again and see if your error is fixed.

## Method 2: Check for malicious software

 Your error may occur because of interference from malicious software. You should run a scan on your computer for any malicious program.

 You can use the **[Malicious Software Removal Tool](https://www.microsoft.com/en-us/download/malicious-software-removal-tool-details.aspx)**  released by Microsoft. Download the tool and run it on your computer. Then follow its instructions to complete the scanning process. If this method works for you, you won’t see the error on your Windows Update again.

## Method 3: Restart your Windows Update associated services

 You may get the service not running error because the services associated with your Windows Update are disabled. You should restart those services and see if this fixes your error. To do so:

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK** to open the_Services_ snap-in.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

**3)** Double click **Background Intelligent Transfer Service** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb31524505e.jpg)

**4)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3214c6b1e.jpg)

**5)** Double click**Cryptographic Services** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2d8b6d4e7.jpg)

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2f73c5553.jpg)

**7)** Double click**Windows Update** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb327c20a47.jpg)

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

<!-- affiliate ads begin -->
<a href="https://ukaidot.sjv.io/c/5597632/1793234/19578" target="_top" id="1793234"><img src="//a.impactradius-go.com/display-ad/19578-1793234" border="0" alt="" width="678" height="452"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793234/19578" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb361957d5c.jpg)

**7)** Close the Services snap-in and restart your computer. Then check to see if this resolves your problem.

## Method 4: Clear the SoftwareDistribution folder

 The SoftwareDistribution folder stores temporary files for Windows Update. You may get the error due to corruption issues with these files. To see if these files are the cause, you should remove all the content of this folder.

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK**  to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

**3)** Click**Windows Update** and then click**Stop** (the service).

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3bc020986.jpg)

**4)** Open_File Explorer_ (press the**Windows logo** key and**E** on your keyboard at the same time), then go to **C:\\Windows\\SoftwareDistribution** and**delete** all the files and folders there.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3da65b40b.jpg)

**5)**  Restore the_Services_ snap-in. Then click**Windows Update** and click**Start** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3f4e427ba.jpg)

**6)** Restart your computer. Then run Windows Update see if this helps you get rid of the Windows Update service not running error.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4621764&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.x-mirage.com/x-mirage/img/page-home.jpg" border="0"></a>
<!-- affiliate ads end -->
## Method 5: Update your device drivers

 Your error may occur because you’re using a wrong device driver or it’s out of date. To see if that’s the case for you, you should check your computer and update all those outdated or wrong drivers.

 Updating drivers can consume a lot of time. But if you want to do it easily and quickly, you can use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

**Driver Easy**  will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can download and install your drivers by using either Free or **Pro**  version of Driver Easy. But with the Pro version it takes only **2**  clicks (and you get **full support** and a **30-day money back guarantee** ):

**1)** [**Download**](https://tools.techidaily.com/drivereasy/download/) and install **Driver Easy** .

**2)** Run **Driver Easy** and click the **Scan Now** button. **Driver Easy**  will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399"><img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ac9e7d372aa0.png)

**3)**  Click the **Update**  button next to your each of your devices to download the latest and correct driver for it. You can also click the **Update All**  button at the bottom right to automatically update all outdated or missing drivers on your computer (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  — you will be prompted to upgrade when you click Update All).

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529"><img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ac9f8a62a090.jpg)

**4)** Restart your computer. Then run you Windows Update to see if this resolves your problem.

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
