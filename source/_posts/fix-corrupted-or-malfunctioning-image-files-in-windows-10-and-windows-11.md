---
title: Fix Corrupted or Malfunctioning Image Files in Windows 10 and Windows 11
date: 2024-09-04T20:27:52.545Z
updated: 2024-09-05T20:27:52.545Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fix Corrupted or Malfunctioning Image Files in Windows 10 and Windows 11
excerpt: This Article Describes Fix Corrupted or Malfunctioning Image Files in Windows 10 and Windows 11
thumbnail: https://thmb.techidaily.com/675ce17ef0dabd739aa8ee3e2aac7844c7deb38c517ca3120730f7fc3392ff08.jpg
---

## Troubleshooting Nonfunctional USB Ports on Windows 10/11 - Fixed

 If you find one of your USB devices on Windows 10 isn’t working, read on. Whether it’s a USB mouse, keyboard, pen drive, printer, or some other USB devices altogether, this guide should resolve your problem.

 Note that there are 5 possible solutions here. You may not need to try them all; just start at the top of the list and work your way down.

[1:**Check if the device itself is faulty**](#1)
[2:**Check your power supply**](#2)
[3: **Check your power management settings**](#3)
[4:**Check your USB device drivers**](#4)
[5:**Check your USB ports**](#5)

## **Method 1: Check if the device itself is faulty**

 If the USB device was working before you upgraded to Windows 10, it’s unlikely to be faulty. But coincidences do occur. It’s certainly_possible_ that your device just happened to die right at the same time that you upgraded Windows. So it’s best to rule that possibility out for sure before spending time on more complex troubleshooting.

 To check if the USB device is faulty, simply unplug it (‘Eject’ it if it’s a USB storage device) and plug it into another computer. If it works, the device is fine. If it doesn’t, then you’ve isolated the problem! You just need to buy a replacement.

## **Method 2: Check your power supply (laptop only)**

 Your laptop’s power supply delivers power to your USB ports. If, for some reason, it fails to do this properly, the devices plugged into those USB ports may stop working. Sometimes, this can be fixed quite simply:

1) Unplug the power supply and charger plug from your laptop

2) Restart your laptop

3) Connect your USB device to the laptop again

4) Plug the power supply back in

## **Method 3: Check your power management settings**

 In order to save power, by default, Windows switches your USB controllers off when they’re not in use, and switches them back on again when they’re needed. Unfortunately, sometimes this approach doesn’t work as intended, and Windows fails to switch your USB controllers on again.

 To rule this out as the cause of your USB woes, just stop Windows from ‘managing’ power to your USB controllers and devices:

 1) Open Device Manager (type “Device Manager” in the Windows search field)

![](https://www.drivereasy.com/wp-content/uploads/2015/11/run-devmgmt.msc_.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118323/7443" target="_top" id="2118323">
  <img src="//a.impactradius-go.com/display-ad/7443-2118323" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118323/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Expand the**Universal Serial Bus controllers** branch

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430ac388d01.png)

 3) Double-click the first **USB Root Hub** device in the list (if you see only one USB Root Hub device, that’s fine)  

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430af9a6bc2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4) Click the **Power Management**  tab  

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342d99c355a.png)

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5) Un-check the **Allow the computer to turn off this device to save power**  checkbox, and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2016/05/img_57342dd22bb58.png)

 6) Repeat steps 3-5 for each  USB Root Hub device in your list of Universal Serial Bus controllers

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_59430b577123a.png)

<!-- affiliate ads begin -->
<span id="1702748">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1702748.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18544-1702748">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1702748.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftwopages.pxf.io%2Fc%2F5597632%2F1702748%2F18544'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702748/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 4: Check your USB device drivers**

 Your USB ports not working problem is probably being caused by driver issues. The steps above may resolve it, but if they don’t, or you’re not confident playing around with drivers manually,  you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a 30-day money-back guarantee):

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_594841d4c15c1.jpg)

 3) Click the**Update** button next to a flagged USB driver to automatically download and install the correct version of this driver (you can do this with the FREE version).

 Or click**Update All**  to automatically download and install the correct version of_all_ the drivers that are missing or out of date on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/06/img_5948dbf290aa4.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2024338/7443" target="_top" id="2024338">
  <img src="//a.impactradius-go.com/display-ad/7443-2024338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2024338/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**The Pro version of Driver Easy** comes with full technical support.  
 If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868575/19272" target="_top" id="1868575">
  <img src="//a.impactradius-go.com/display-ad/19272-1868575" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868575/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Method 5: Check your USB ports**

 If none of the above methods resolve your problem, your USB ports might be damaged. To find out, you can take your PC to a repair store and ask them to check. If your USB ports are damaged, the repairer should be able to replace them fairly inexpensively.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://extra-support.techidaily.com/new-pro-cloud-storage-guide-optimal-options-highlighted/"><u>[New] Pro-Cloud Storage Guide  Optimal Options Highlighted</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-art-of-patience-mastering-the-craft-of-producing-captivating-slow-motion-videos-and-photos-for-instagram-for-2024/"><u>[New] The Art of Patience  Mastering the Craft of Producing Captivating Slow Motion Videos and Photos for Instagram for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-the-ultimate-list-5-premium-live-stream-recorders-for-2024/"><u>[New] The Ultimate List  5 Premium Live Stream Recorders for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-the-ultimate-voyage-guide-from-novice-to-esteemed-travel-blogger/"><u>[New] The Ultimate Voyage Guide  From Novice to Esteemed Travel Blogger</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-2024-approved-effective-method-for-personalizing-fb-page-coverage/"><u>[Updated] 2024 Approved  Effective Method for Personalizing FB Page Coverage</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-academic-journey-across-time-top-10-history-youtubers/"><u>[Updated] Academic Journey Across Time  Top 10 History YouTubers</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-affordable-mic-picks-for-aspiring-yt-bands/"><u>[Updated] Affordable Mic Picks for Aspiring YT Bands</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-discovering-the-roots-of-visual-content-through-reverse-scans-fb/"><u>[Updated] In 2024, Discovering the Roots of Visual Content Through Reverse Scans (FB)</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-quintessential-filters-to-perfect-ocean-shoots/"><u>[Updated] Quintessential Filters to Perfect Ocean Shoots</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-expert-picks-top-10-live-broadcast-apps-for-basketball-and-soccer-fans/"><u>2024 Approved  Expert Picks  Top 10 Live-Broadcast Apps for Basketball and Soccer Fans</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-safaris-picture-in-picture-on-ios-and-ipad-how-to-use/"><u>2024 Approved  Safari's Picture-in-Picture on iOS & iPad  How to Use</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-call-logs-on-xperia-10-v-by-fonelab-android-recover-call-logs/"><u>Complete guide for recovering call logs on Xperia 10 V</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-tips-resolving-issues-when-usb-drives-go-missing-on-your-computer/"><u>DIY Repair Tips: Resolving Issues When USB Drives Go Missing on Your Computer</u></a></li>
<li><a href="https://facebook.techidaily.com/enhancing-your-social-media-presence-incorporating-your-avatar-in-covers/"><u>Enhancing Your Social Media Presence: Incorporating Your Avatar in Covers</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x802n-2400d-winning-the-battle-against-windows-update-failures-strategies-discussed/"><u>Error 0X802n-2400D: Winning the Battle Against Windows Update Failures [STRATEGIES DISCUSSED]</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-overcoming-bluetooth-offline-problems/"><u>Expert Advice on Overcoming 'Bluetooth Offline' Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/failed-to-initialize-battleye-service-generic-error-fixed/"><u>Failed to Initialize BattlEye Service: Generic Error [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-the-missing-power-alert-a-simple-guide-for-immediate-relief/"><u>Fix the Missing Power Alert: A Simple Guide for Immediate Relief</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-cannot-reach-system-event-notification-service-error-message/"><u>Fixing 'Windows Cannot Reach System Event Notification Service' Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-skype-video-glitches-in-no-time-on-windows-11/"><u>Fixing Skype Video Glitches in No Time on Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/from-software-to-functionality-ms-workspace-on-windows-1011/"><u>From Software to Functionality: MS Workspace on Windows 10/11</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-leave-a-life360-group-on-vivo-y100a-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How To Leave a Life360 Group On Vivo Y100A Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/instant-remedies-mend-your-google-hangouts-microphone-without-hassle/"><u>Instant Remedies: Mend Your Google Hangouts Microphone Without Hassle</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/inventory-management/"><u>Inventory Management</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/mac-dvd-ripper-iphoneipadappletvmp4dvd/"><u>Mac用 DVD Ripper - iPhone、iPad、AppleTV、MP4への簡単DVDコピーガイド</u></a></li>
<li><a href="https://common-error.techidaily.com/navigated-through-stalled-nvidia-installation/"><u>Navigated Through Stalled NVIDIA Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-issues-is-the-service-down-and-what-can-you-do-about-it/"><u>Netflix Issues: Is the Service Down, and What Can You Do About It?</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-fixing-driver-failure-due-to-incorrect-user-preferences/"><u>Resolved Issue: Fixing 'Driver Failure' Due to Incorrect User Preferences</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-for-fixing-0x800705b4-error-in-your-windows-11-system/"><u>Resolved: Step-by-Step Guide for Fixing 0X800705b4 Error in Your Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-device-unavailable-error-code-24-on-windows-1187/"><u>Resolving 'Device Unavailable' Error Code 24 on Windows 11/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solution-resolving-the-steam-disk-writes-failed-issue-without-hassle/"><u>Simple Solution: Resolving the 'Steam Disk Writes Failed' Issue Without Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-when-google-chrome-freezes-up-and-wont-respond/"><u>Solution for When Google Chrome Freezes Up and Won’t Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guided-troubleshooting-windows-cannot-access-system-event-notifier-service/"><u>Solution Guided: Troubleshooting Windows Cannot Access System Event Notifier Service</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-to-reactivate-dimmed-or-dead-keylights-in-your-laptop/"><u>Solution Steps to Reactivate Dimmed or Dead Keylights in Your Laptop</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/soundtrack-your-youtube-videos-7-free-audio-selections/"><u>Soundtrack Your YouTube Videos  7 Free Audio Selections</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-joining-an-itunes-shared-album-with-your-iphone/"><u>Step-by-Step Guide: Joining an iTunes Shared Album with Your iPhone</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-struggling-with-an-inverted-laptop-screen-easy-fixes-inside/"><u>Stop Struggling with an Inverted Laptop Screen: Easy Fixes Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-printing-your-pdf-discover-fast-solutions/"><u>Trouble Printing Your PDF? Discover Fast Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206026261-troubleshoot-the-windows-11-bluetooth-not-detected-problem-fast-solutions/"><u>Troubleshoot the Windows 11 Bluetooth Not Detected Problem - Fast Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-0x80072efd-error-in-windows-10-effortlessly/"><u>Troubleshooting and Fixing the 0X80072EFD Error in Windows 10 Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-audio-glitches-solving-crackling-sounds-in-windows-os/"><u>Troubleshooting Audio Glitches: Solving Crackling Sounds in Windows OS</u></a></li>
<li><a href="https://youtube-web.techidaily.com/-affiliates-a-roadmap-to-financial-growth-for-2024/"><u>Video Affiliates  A Roadmap to Financial Growth for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-hello-isnt-available-on-this-device-on-windows-10-solved/"><u>Windows Hello Isn’t Available on This Device on Windows 10 [Solved]</u></a></li>
</ul></div>
