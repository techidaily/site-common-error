---
title: Understanding and Fixing [InetErr] Resource Not Found Challenges in IT Systems
date: 2024-12-18T17:30:42.669Z
updated: 2024-12-25T20:55:58.071Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Understanding and Fixing [InetErr] Resource Not Found Challenges in IT Systems
excerpt: This Article Describes Understanding and Fixing [InetErr] Resource Not Found Challenges in IT Systems
thumbnail: https://thmb.techidaily.com/29b1b2904297da87da55ea288cd0a44b14a4d2e985940c7f874a6ef2e9aec11a.jpg
---

## Getting Microsoft's Latest Patches? Reviving Your Stalled Windows Update Service

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Method 3: Restart your Windows Update associated services

 You may get the service not running error because the services associated with your Windows Update are disabled. You should restart those services and see if this fixes your error. To do so:

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK** to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/q4-YQ9Wjtfg?si=6afn1fydg_Wb9B8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Double click **Background Intelligent Transfer Service** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb31524505e.jpg)

**4)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3214c6b1e.jpg)

**5)** Double click**Cryptographic Services** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2d8b6d4e7.jpg)

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2f73c5553.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**7)** Double click**Windows Update** .

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb327c20a47.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**6)** Make sure the_startup type_ is set to**Automatic** . Then click the**Start** button (if the Start button is_in gray_ , click the**Stop** button and then click the**Start** button). Then click**OK** to close the window.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb361957d5c.jpg)

**7)** Close the Services snap-in and restart your computer. Then check to see if this resolves your problem.

## Method 4: Clear the SoftwareDistribution folder

 The SoftwareDistribution folder stores temporary files for Windows Update. You may get the error due to corruption issues with these files. To see if these files are the cause, you should remove all the content of this folder.

**1)** Press the**Windows logo key** and**R** on your keyboard to invoke the Run box.

**2)** Type “_services.msc_ ” and click**OK**  to open the_Services_ snap-in.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb2aa01cd2e.png)

**3)** Click**Windows Update** and then click**Stop** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3bc020986.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Open_File Explorer_ (press the**Windows logo** key and**E** on your keyboard at the same time), then go to **C:\\Windows\\SoftwareDistribution** and**delete** all the files and folders there.

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3da65b40b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**5)**  Restore the_Services_ snap-in. Then click**Windows Update** and click**Start** (the service).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5acb3f4e427ba.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)**  Click the **Update**  button next to your each of your devices to download the latest and correct driver for it. You can also click the **Update All**  button at the bottom right to automatically update all outdated or missing drivers on your computer (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  — you will be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ac9f8a62a090.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-supreme-memetric-creation-tool-for-2024/"><u>[New] Supreme Memetric Creation Tool for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-streamlining-short-film-previews-for-channels-for-2024/"><u>[Updated] Streamlining Short Film Previews for Channels for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-transfer-music-from-itel-p55-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Transfer Music from Itel P55 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unresponsive-laptop-keys-on-windows-11-8-and-7-step-by-step-solutions/"><u>Fixing Unresponsive Laptop Keys on Windows 11, 8 & 7: Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-pc-a-step-by-step-solution-for-failed-feature-update-to-windows-10-v1903/"><u>Fixing Your PC: A Step-by-Step Solution for Failed Feature Update to Windows 10 V1903</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-and-overcome-insufficient-resources-system-issue-effectively/"><u>How to Address and Overcome 'Insufficient Resources' System Issue Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-solve-the-pc-version-of-monster-hunter-worlds-disconnect-woes/"><u>How to Solve the PC Version of Monster Hunter World's Disconnect Woes</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-resolution-overcoming-temporary-unavailability-of-windows-smartscreen/"><u>Immediate Resolution: Overcoming Temporary Unavailability of Windows SmartScreen</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-xiaomi-redmi-a2-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/in-depth-evaluation-of-the-huion-kamvas-gt-191-tablet-splendid-and-spacious-for-digital-artists/"><u>In-Depth Evaluation of the Huion Kamvas GT-191 Tablet: Splendid and Spacious for Digital Artists</u></a></li>
<li><a href="https://common-error.techidaily.com/is-unreals-demise-linked-to-d3d-device-failure/"><u>Is Unreal's Demise Linked to D3D Device Failure?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/real-time-narrative-builder/"><u>Real-Time Narrative Builder</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/the-dual-lens-approach-gaining-audience-insight-with-3-pov-strategies-for-youtube-reactions-for-2024/"><u>The Dual Lens Approach Gaining Audience Insight with 3 POV Strategies for YouTube Reactions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-ethernet-connection-problems-in-windows-10-and-7/"><u>Troubleshooting Ethernet Connection Problems in Windows 10 and 7</u></a></li>
<li><a href="https://win-tricks.techidaily.com/upgrading-avoided-smart-alternatives-to-windows-11-you-should-know-about/"><u>Upgrading Avoided: Smart Alternatives to Windows 11 You Should Know About</u></a></li>
</ul></div>

