---
title: .NET Framework 3.5 Installation Woes? Here's How to Fix Error Code 0X800F081F
date: 2024-09-04T20:26:57.988Z
updated: 2024-09-05T20:26:57.988Z
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-easier-than-ever-top-9-uncomplicated-no-cost-video-tools-for-you/"><u>[New] 2024 Approved  Easier Than Ever  Top 9 Uncomplicated, No-Cost Video Tools for You</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-fire-up-the-connections-maintaining-long-lasting-streaks/"><u>[New] Fire Up the Connections  Maintaining Long-Lasting Streaks</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-why-does-windows/"><u>[Troubleshooting Guide] Why Does Windows</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-efficient-file-migration-pc-to-ios-device/"><u>[Updated] 2024 Approved  Efficient File Migration  PC to iOS Device</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-2024-approved-tailored-tricks-building-a-personalized-youtube-follow-buttons/"><u>[Updated] 2024 Approved  Tailored Tricks  Building a Personalized YouTube Follow Buttons</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-iron-out-glitches-restore-missing-facebook-watch-icons/"><u>[Updated] Iron Out Glitches - Restore Missing Facebook Watch Icons</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-how-does-youtube-count-views-its-not-as-simple-as-you-think/"><u>2024 Approved  How Does YouTube Count Views? It's Not as Simple as You Think</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-easy-solutions-to-hard-reset-nokia-c02-drfone-by-drfone-reset-android-reset-android/"><u>3 Easy Solutions to Hard Reset Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/brighten-your-display-fix-blurry-screen-on-windows-10-with-these-simple-tweaks/"><u>Brighten Your Display: Fix Blurry Screen on Windows 10 with These Simple Tweaks</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-check-needed-verify-if-you-have-an-appropriate-d3d11-ready-gpu/"><u>Compatibility Check Needed: Verify if You Have an Appropriate D3D11-Ready GPU</u></a></li>
<li><a href="https://common-error.techidaily.com/end-window-11s-restart-loop-once-and-for-all-easy-troubleshooting-tips-inside/"><u>End Window 11'S Restart Loop Once and For All - Easy Troubleshooting Tips Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/ending-taskbar-troubles-in-windows-10-effective-solutions-and-tips/"><u>Ending Taskbar Troubles in Windows 10: Effective Solutions & Tips</u></a></li>
<li><a href="https://tech-revival.techidaily.com/envisioning-tomorrow-exploring-gpts-significant-innovations/"><u>Envisioning Tomorrow: Exploring GPT's Significant Innovations</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-vcruntime140dll-file-missing-issue-a-comprehensive-guide/"><u>Fixing the VCRUNTIME140.dll File Missing Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-fixing-and-improving-touchpad-scrolling-in-windows-11-systems/"><u>Guide: Fixing & Improving Touchpad Scrolling in Windows 11 Systems</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-x-to-other-iphone-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone X to other iPhone? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-solution-for-non-functioning-keys-on-your-hp-laptop/"><u>Immediate Solution for Non-Functioning Keys on Your HP Laptop</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-delete-gmail-account-withwithout-password-on-motorola-moto-g24-by-drfone-android/"><u>In 2024, Delete Gmail Account With/Without Password On Motorola Moto G24</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-does-find-my-friends-work-on-samsung-galaxy-z-fold-5-drfone-by-drfone-virtual-android/"><u>In 2024, Does find my friends work on Samsung Galaxy Z Fold 5 | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-effortless-visual-transitions-using-instagram-chroma-keying/"><u>In 2024, Effortless Visual Transitions Using Instagram Chroma Keying</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-ios-screen-recording-a-no-nonsense-approach/"><u>In 2024, IOS Screen Recording  A No-Nonsense Approach</u></a></li>
<li><a href="https://common-error.techidaily.com/lung-adenocarcinoma-is-the-most-common-type-of-lung-cancer-in-non-smokers/"><u>Lung Adenocarcinoma Is the Most Common Type of Lung Cancer in Non-Smokers.</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/mastering-live-photos-iphone-usage-tips/"><u>Mastering Live Photos  IPhone Usage Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-infinite-loading-loop-in-valorant-effective-solutions-inside/"><u>Overcome Infinite Loading Loop in Valorant: Effective Solutions Inside.</u></a></li>
<li><a href="https://common-error.techidaily.com/quickly-restore-bluetooth-functionality-on-your-windows-11-pc-easy-methods-inside/"><u>Quickly Restore Bluetooth Functionality on Your Windows 11 PC: Easy Methods Inside!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/resolve-hyperx-cloud-stinger-microphone-failure-with-these-simple-fixes/"><u>Resolve HyperX Cloud Stinger Microphone Failure with These Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-cannot-access-device-pathfile-in-windows-fix-guide/"><u>Solving 'Cannot Access Device Path/File' In Windows - Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-troubleshooting-sims-4-failure-to-launch/"><u>Solving the Problem: Troubleshooting Sims 4 Failure to Launch</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/-up-viewers-innovative-cooking-channel-naming-tips/"><u>Spice Up Viewers  Innovative Cooking Channel Naming Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/steam-users-guide-correcting-problems-when-setting-upupgrading-video-games/"><u>Steam User's Guide: Correcting Problems When Setting Up/Upgrading Video Games</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-windows-10s-critical-0x800705b4-update-failure-and-how-to-prevent-it/"><u>Step-by-Step Fix for Windows 10'S Critical 0X800705B4 Update Failure and How to Prevent It</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-activating-bluetooth-on-windows-11-and-10-no-more-problems/"><u>Step-by-Step Guide: Activating Bluetooth on Windows 11 and 10 - No More Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-common-werfaultexe-windows-issues-with-minimal-hassle/"><u>Step-by-Step Guide: Repairing Common werFault.exe Windows Issues with Minimal Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-for-enabling-bluetooth-on-your-pc-windows-11-and-10/"><u>Step-by-Step Instructions for Enabling Bluetooth on Your PC (Windows 11 and 10)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-repair-tips-for-a-broken-fingerprint-reader-on-lenovo-devices/"><u>Step-by-Step Repair Tips for a Broken Fingerprint Reader on Lenovo Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-correcting-windows-updates-setup-issues/"><u>Step-by-Step Solutions for Correcting Windows Updates Setup Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/stuck-on-a-pdf-not-printing-heres-how-you-can-solve-the-problem-fast/"><u>Stuck on a PDF Not Printing? Here's How You Can Solve the Problem Fast</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-art-of-blending-audio-with-video-in-premiere-pro-for-2024/"><u>The Art of Blending Audio with Video in Premiere Pro for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-a-malfunctioning-torrent-download/"><u>Troubleshooting Steps for a Malfunctioning Torrent Download</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-a-surface-device-that-is-plugged-in-but-not-charging/"><u>Troubleshooting Steps for a Surface Device That Is Plugged In But Not Charging</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-enabling-night-mode-on-windows-10-and-11-systems/"><u>Troubleshooting Tips for Enabling Night Mode on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-microsoft-surface-stays-plugged-in-but-fails-to-charge/"><u>Troubleshooting: Microsoft Surface Stays Plugged in but Fails to Charge</u></a></li>
<li><a href="https://common-error.techidaily.com/usb-connection-issues-beat-device-descriptor-request-failed-with-our-expert-tips/"><u>USB Connection Issues? Beat 'Device Descriptor Request Failed' With Our Expert Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/western-digital-my-passport-ultra-detection-fix-a-step-by-step-guide-for-windows-users/"><u>Western Digital My Passport Ultra Detection Fix - A Step-by-Step Guide for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-do-when-your-pc-cant-install-windows-11-version-1607/"><u>What to Do When Your PC Can't Install Windows 11 Version 1607</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1975658">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975658.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975658">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975658.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975658%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975658/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->