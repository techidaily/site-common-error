---
title: How to Restart and Solve Windows Update Service Issues
date: 2024-12-02T22:28:52.824Z
updated: 2024-12-04T07:29:31.533Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Restart and Solve Windows Update Service Issues
excerpt: This Article Describes How to Restart and Solve Windows Update Service Issues
thumbnail: https://thmb.techidaily.com/7b383aed23b1ada69f4ef595191e5a033238c1b3df9ba6a1aa455dbcac03eedf.jpg
---

## Guide to Restarting Your Windows Update Service – Problems Solved

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Run Windows Update troubleshooter

 Windows has a built-in troubleshooter that can check and fix issues with Windows Update. You should run it when an error occurs on your Windows Update. To do so:

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### on Windows 10

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** Select**Update & Security** .

![](https://www.drivereasy.com/wp-content/uploads/2023/10/Windows-10-Update-and-Security.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**2)** Click**Troubleshoot > Additional troubleshooters** .

**3)** Find**Windows Update** and click**Run the troubleshooter** .

**4)** Follow the on-screen instructions to complete the troubleshooting process.

**5)** Run your Windows Update again and see if your error is fixed.

### on Windows 11

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** From the left navigation panel, select**System** . Click**Troubleshoot** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot-1200x699.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Click**Other troubleshooters** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters-1200x699.jpg)

**4)** Click on the**Run** button next to**Windows Update** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-Troubleshooter-Windows-Update-1200x616.jpg)

**5)** Follow the on-screen instructions to complete the troubleshooting process.

**6)** Run your Windows Update again and see if your error is fixed.

## Method 2: Check for malicious software

 Your error may occur because of interference from malicious software. You should run a scan on your computer for any malicious program.

 You can use the **[Malicious Software Removal Tool](https://www.microsoft.com/en-us/download/malicious-software-removal-tool-details.aspx)**  released by Microsoft. Download the tool and run it on your computer. Then follow its instructions to complete the scanning process. If this method works for you, you won’t see the error on your Windows Update again.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SgRVYjqB70s?si=My_2cDvJVdincQRu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Restart your Windows Update associated services

 You may get the service not running error because the services associated with your Windows Update are disabled. You should restart those services and see if this fixes your error. To do so:

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK** to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

**3)** Double click **Background Intelligent Transfer Service** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb31524505e.jpg)

**4)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3214c6b1e.jpg)

**5)** Double click**Cryptographic Services** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2d8b6d4e7.jpg)

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2f73c5553.jpg)

**7)** Double click**Windows Update** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb327c20a47.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Iz2LYWd8EqI?si=G_3CqFRAmeVPczjj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb361957d5c.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**7)** Close the Services snap-in and restart your computer. Then check to see if this resolves your problem.

## Method 4: Clear the SoftwareDistribution folder

 The SoftwareDistribution folder stores temporary files for Windows Update. You may get the error due to corruption issues with these files. To see if these files are the cause, you should remove all the content of this folder.

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK**  to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

**3)** Click**Windows Update** and then click**Stop** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3bc020986.jpg)

**4)** Open_File Explorer_ (press the**Windows logo** key and**E** on your keyboard at the same time), then go to **C:\\Windows\\SoftwareDistribution** and**delete** all the files and folders there.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3da65b40b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Lp78eFEGwVU?si=-4orJBLvJJrggCJ2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**5)**  Restore the_Services_ snap-in. Then click**Windows Update** and click**Start** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3f4e427ba.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**6)** Restart your computer. Then run Windows Update see if this helps you get rid of the Windows Update service not running error.

## Method 5: Update your device drivers

 Your error may occur because you’re using a wrong device driver or it’s out of date. To see if that’s the case for you, you should check your computer and update all those outdated or wrong drivers.

 Updating drivers can consume a lot of time. But if you want to do it easily and quickly, you can use [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

**Driver Easy**  will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can download and install your drivers by using either Free or **Pro**  version of Driver Easy. But with the Pro version it takes only **2**  clicks (and you get **full support** and a **30-day money back guarantee** ):

**1)** [**Download**](https://tools.techidaily.com/drivereasy/download/) and install **Driver Easy** .

**2)** Run **Driver Easy** and click the **Scan Now** button. **Driver Easy**  will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ac9e7d372aa0.png)

**3)**  Click the **Update**  button next to your each of your devices to download the latest and correct driver for it. You can also click the **Update All**  button at the bottom right to automatically update all outdated or missing drivers on your computer (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  — you will be prompted to upgrade when you click Update All).

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

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/new-top-5-ios-platforms-mimicking-ps2/"><u>[New] Top 5 iOS Platforms Mimicking PS2</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-direct-from-instagram-masterful-techniques-for-igtv-video-transferring/"><u>[Updated] In 2024, Direct From Instagram Masterful Techniques for IGTV Video Transferring</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-steps-to-crossfade-audio-in-logic-pro-x/"><u>[Updated] Steps To Crossfade Audio In Logic Pro X</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-resolving-the-persistent-restart-problem-in-windows-10/"><u>Effortless Fixes for Resolving the Persistent Restart Problem in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203659471-effortless-guide-to-overcome-too-many-redirects-error-swiftly/"><u>Effortless Guide to Overcome Too Many Redirects Error Swiftly</u></a></li>
<li><a href="https://sound-issues.techidaily.com/fixing-a-non-functional-headphone-port-on-your-laptop-a-comprehensive-guide/"><u>Fixing a Non-Functional Headphone Port on Your Laptop: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-resolving-google-chromes-serious-malfunction-and-security-threat/"><u>Guide to Resolving Google Chrome's Serious Malfunction and Security Threat</u></a></li>
<li><a href="https://common-error.techidaily.com/hack-the-errors-reinstating-x3daudio17dll/"><u>Hack the Errors: Reinstating X3DAudio1_7.dll</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-poco-m6-pro-4g-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Poco M6 Pro 4G</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-10-fake-gps-location-apps-on-android-of-your-honor-play-40c-drfone-by-drfone-virtual/"><u>In 2024, 10 Fake GPS Location Apps on Android Of your Honor Play 40C | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-current-outage-of-your-computers-windows-security-feature-smartscreen/"><u>Resolving Current Outage of Your Computer's Windows Security Feature: SmartScreen</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-graphics-glitches-troubleshoot-failed-to-create-d3d9-device/"><u>Solve Your Graphics Glitches: Troubleshoot Failed to Create D3D9 Device</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-verdict-on-samsungs-cf591-a-comprehensive-review-for-enthusiasts/"><u>The Verdict on Samsung's CF591: A Comprehensive Review for Enthusiasts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/toms-tech-insights-comprehensive-guide-to-computer-hardware/"><u>Tom's Tech Insights: Comprehensive Guide to Computer Hardware</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210743255-troubleshooting-destiny-2-get-your-game-up-and-running-again/"><u>Troubleshooting Destiny 2: Get Your Game Up and Running Again</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-wax-video-editing-software-tips-tricks-and-tutorials-for-2024/"><u>Updated Wax Video Editing Software Tips, Tricks, and Tutorials for 2024</u></a></li>
</ul></div>

