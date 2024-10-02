---
title: Step-by-Step Solution for Fixing Steam Update Download Failures
date: 2024-09-30T17:32:48.983Z
updated: 2024-10-01T21:44:52.094Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for Fixing Steam Update Download Failures
excerpt: This Article Describes Step-by-Step Solution for Fixing Steam Update Download Failures
thumbnail: https://thmb.techidaily.com/3940086541c823408b7e3893cd4adcfe04714cf8a1d0ceb2c3d06364d867bc68.png
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2016148/19272" target="_top" id="2016148">
  <img src="//a.impactradius-go.com/display-ad/19272-2016148" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016148/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130887/7443" target="_top" id="2130887">
  <img src="//a.impactradius-go.com/display-ad/7443-2130887" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130887/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)**Still in Command Prompt, type these commands and press Enter after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Run Windows Update and check to see if your computer can install the 1607 update.

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148635/16836" target="_top" id="2148635">
  <img src="//a.impactradius-go.com/display-ad/16836-2148635" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148635/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

## Method 4: Temporarily disable your antivirus software

Sometimes your system can’t install new updates due to the interference from your**antivirus software**. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.**IMPORTANT:**Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://snapchat-videos.techidaily.com/new-the-beginners-guide-to-easy-multi-snap-chat-videos-and-edits-for-2024/"><u>[New] The Beginner's Guide to Easy Multi-Snap Chat Videos & Edits for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-top-9-live-stream-networks-revealed-secrets/"><u>[New] Top 9 Live Stream Networks - Revealed Secrets</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-a-glimpse-at-the-best-curating-a-list-of-5-exceptional-book-tts/"><u>[Updated] 2024 Approved A Glimpse at the Best Curating a List of 5 Exceptional Book TTs</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-clearscreenstreamer-seamless-easy-w11-screenshots/"><u>[Updated] In 2024, ClearScreenStreamer Seamless, Easy W11 Screenshots</u></a></li>
<li><a href="https://win11.techidaily.com/addressing-non-functional-cortana-on-windows-11/"><u>Addressing Non-Functional Cortana on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/avoid-game-pauses-with-x3daudio17dll-restoration/"><u>Avoid Game Pauses with X3DAudio1_7.dll Restoration</u></a></li>
<li><a href="https://common-error.techidaily.com/crucial-specification-your-system-requires-directx-11-capable-video-card-to-operate-this-application/"><u>Crucial Specification: Your System Requires DirectX 11 Capable Video Card to Operate This Application</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204344134-easily-repair-unresponsive-buttons-on-your-hp-laptop-step-by-step-guide/"><u>Easily Repair Unresponsive Buttons on Your HP Laptop - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-reinstating-logildadll/"><u>Fast-Track: Reinstating LogiLDA.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212081531-hearthstone-slowness-bypass-lag-issues-using-simple-fixes/"><u>Hearthstone Slowness? Bypass Lag Issues Using Simple Fixes</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-erase-an-apple-iphone-14-plus-without-apple-id-by-drfone-ios/"><u>How to Erase an Apple iPhone 14 Plus without Apple ID?</u></a></li>
<li><a href="https://win-solutions.techidaily.com/how-to-speed-up-your-sluggish-spotify-web-player-a-step-by-step-fix/"><u>How to Speed Up Your Sluggish Spotify Web Player - A Step-by-Step Fix</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-ispoofer-update-on-itel-p55-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will iSpoofer update On Itel P55 5G | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/optimizing-speed-on-vimeo-content-for-2024/"><u>Optimizing Speed on Vimeo Content for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-startup-issues-with-easy-tips-for-stuck-at-getting-ready-errors/"><u>Overcome Startup Issues with Easy Tips for 'Stuck at Getting Ready' Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-inactive-function-keys-on-your-computer/"><u>Overcoming Issues with Inactive Function Keys on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-stuck-windows-11-screens-tips-to-get-it-running-smoothly-again/"><u>Troubleshooting Stuck Windows 11 Screens: Tips to Get It Running Smoothly Again</u></a></li>
</ul></div>

