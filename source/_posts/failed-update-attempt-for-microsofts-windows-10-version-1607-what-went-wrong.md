---
title: Failed Update Attempt for Microsoft's Windows 10 Version 1607 - What Went Wrong?
date: 2025-01-15T20:51:20.922Z
updated: 2025-01-22T18:52:36.019Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Failed Update Attempt for Microsoft's Windows 10 Version 1607 - What Went Wrong?
excerpt: This Article Describes Failed Update Attempt for Microsoft's Windows 10 Version 1607 - What Went Wrong?
thumbnail: https://thmb.techidaily.com/d0c9b7047797b18daa1e1aa41be92c363eb13ba8f8bfa2b570a90a8bfa430bd1.jpg
---

## Persistent Windows Update Problems? Here's What You Need To Do

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb080685ea1.png)

 Many Windows users are having an issue with their Windows Update. If they check for updates on their Windows system, they get an error that says “ **Windows Update cannot currently check for updates, because the service is not running** “. And they can’t install updates for their system.

 This is an annoying issue. And trying to fix it is just as annoying, because you’ll spend a lot of time reading suggestions on the Internet, and most won’t work.

 But don’t worry. The following are some methods that have helped many Windows users fix their error.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### Try these fixes

 You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Run Windows Update troubleshooter**](#a)
2. [**Check for malicious software**](#b)
3. [**Restart your Windows Update associated services**](#c)
4. [**Clear the SoftwareDistribution folder**](#d)
5. [**Update your device drivers**](#e)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nlwr9LjJ-ng?si=I6UNAtfBkY2FTceu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Run Windows Update troubleshooter

 Windows has a built-in troubleshooter that can check and fix issues with Windows Update. You should run it when an error occurs on your Windows Update. To do so:

### on Windows 10

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** Select**Update & Security** .

![](https://www.drivereasy.com/wp-content/uploads/2023/10/Windows-10-Update-and-Security.jpg)

**2)** Click**Troubleshoot > Additional troubleshooters** .

**3)** Find**Windows Update** and click**Run the troubleshooter** .

**4)** Follow the on-screen instructions to complete the troubleshooting process.

**5)** Run your Windows Update again and see if your error is fixed.

### on Windows 11

**1)** On your keyboard, press the**Windows logo + I keys** simultaneously to open Settings.

**2)** From the left navigation panel, select**System** . Click**Troubleshoot** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-System-Troubleshoot-1200x699.jpg)

**3)** Click**Other troubleshooters** .

![](https://www.drivereasy.com/wp-content/uploads/2022/06/win11-Other-troubleshooters-1200x699.jpg)

**4)** Click on the**Run** button next to**Windows Update** .

![](https://www.drivereasy.com/wp-content/uploads/2023/12/win11-Troubleshooter-Windows-Update-1200x616.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**5)** Follow the on-screen instructions to complete the troubleshooting process.

**6)** Run your Windows Update again and see if your error is fixed.

## Method 2: Check for malicious software

 Your error may occur because of interference from malicious software. You should run a scan on your computer for any malicious program.

 You can use the **[Malicious Software Removal Tool](https://www.microsoft.com/en-us/download/malicious-software-removal-tool-details.aspx)**  released by Microsoft. Download the tool and run it on your computer. Then follow its instructions to complete the scanning process. If this method works for you, you won’t see the error on your Windows Update again.

## Method 3: Restart your Windows Update associated services

 You may get the service not running error because the services associated with your Windows Update are disabled. You should restart those services and see if this fixes your error. To do so:

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK** to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

**3)** Double click **Background Intelligent Transfer Service** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb31524505e.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3214c6b1e.jpg)

**5)** Double click**Cryptographic Services** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2d8b6d4e7.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QRaEdFMU-Xc?si=OjaiTvlogJy5wHhN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2f73c5553.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0dOfcihxjiw?si=_fkp1S1Uw0N1dp6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**7)** Double click**Windows Update** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb327c20a47.jpg)

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb361957d5c.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**5)**  Restore the_Services_ snap-in. Then click**Windows Update** and click**Start** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3f4e427ba.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JlX-G8rBs1w?si=iIhUoWAq5x3YK9rA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://common-error.techidaily.com/1723203476262-fix-reclaim-your-devices-efficiency-direct-steps-to-resolve-high-system-load-from-shell-infrastructures/"><u>[Fix] Reclaim Your Device’s Efficiency: Direct Steps To Resolve High System Load From Shell Infrastructures</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-breaking-barriers-to-sound-in-twitters-visual-share/"><u>[Updated] Breaking Barriers to Sound in Twitter's Visual Share</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-freepaid-audio-cleanup-tools-for-higher-video-quality-for-2024/"><u>[Updated] Free/Paid Audio-Cleanup Tools for Higher Video Quality for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-nighttime-portrait-etiquette-dos-and-donts/"><u>[Updated] Nighttime Portrait Etiquette Do's and Don'ts</u></a></li>
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-infinix-hot-40-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Infinix Hot 40 without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-blue-screen-of-death-win32-kernal-exception-0xc0-similar-problem-for-us-audience/"><u>Fixing the 'Blue Screen of Death: Win32 Kernal Exception' (0XC0 # Similar Problem for US Audience</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/get-ahead-with-technology-introducing-the-new-enhancements-for-apple-airpods-pro-2-step-by-step-update-instructions/"><u>Get Ahead with Technology: Introducing The New Enhancements for Apple AirPods Pro 2 - Step-by-Step Update Instructions</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-oppo-a56s-5g-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Oppo A56s 5G Phone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-steps-to-acquire-fcp-for-zero-dollars/"><u>In 2024, Steps to Acquire FCP for Zero Dollars</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-wwe-2k-battlegrounds-directx-11-version-100-troubleshooting-challenge/"><u>Overcoming the WWE 2K Battlegrounds DirectX 11 Version 10.0 Troubleshooting Challenge</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-laptop-screen-turn-off-problems-quickly-and-effectively/"><u>Resolve Laptop Screen Turn-Off Problems Quickly and Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-geforce-experience-cannot-fetch-configurations-issue/"><u>Resolved: Fixing 'GeForce Experience Cannot Fetch Configurations' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-com-surrogate-has-stopped-working/"><u>Solved: COM Surrogate Has Stopped Working</u></a></li>
</ul></div>

