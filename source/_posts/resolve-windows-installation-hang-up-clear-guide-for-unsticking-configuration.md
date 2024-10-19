---
title: "Resolve Windows Installation Hang-Up: Clear Guide for Unsticking Configuration"
date: 2024-10-15T03:17:39.538Z
updated: 2024-10-18T21:56:26.124Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolve Windows Installation Hang-Up: Clear Guide for Unsticking Configuration"
excerpt: "This Article Describes Resolve Windows Installation Hang-Up: Clear Guide for Unsticking Configuration"
thumbnail: https://thmb.techidaily.com/82ace019181fb90d20c533db44f7982f837c984d09bf52bb3d1445c9e89ae06d.jpg
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

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144282/7443" target="_top" id="2144282">
  <img src="//a.impactradius-go.com/display-ad/7443-2144282" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144282/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<span id="1983471">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983471%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983471/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100537/7443" target="_top" id="2100537">
  <img src="//a.impactradius-go.com/display-ad/7443-2100537" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100537/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043661/7443" target="_top" id="2043661">
  <img src="//a.impactradius-go.com/display-ad/7443-2043661" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043661/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-master-your-live-video-setting-up-dslr-on-laptop-or-desktop/"><u>[New] 2024 Approved Master Your Live Video Setting Up DSLR on Laptop or Desktop</u></a></li>
<li><a href="https://screen-recording.techidaily.com/best-virtual-background-for-google-meet-for-2024/"><u>Best Virtual Background for Google Meet for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/breaking-free-from-frozen-windows-updates-on-older-operating-systems-expert-advice-for-users-seeking-assistance-edition-helpful-tips-and-guides/"><u>Breaking Free From Frozen Windows Updates on Older Operating Systems – Expert Advice for Users Seeking Assistance Edition! (Helpful Tips and Guides.)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/bridging-the-gap-connecting-instagram-to-your-facebook-account-for-2024/"><u>Bridging the Gap Connecting Instagram to Your Facebook Account for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/edit-and-send-fake-location-on-telegram-for-your-samsung-galaxy-s21-fe-5g-2023-in-3-ways-drfone-by-drfone-virtual-android/"><u>Edit and Send Fake Location on Telegram For your Samsung Galaxy S21 FE 5G (2023) in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-the-too-many-redirects-error-instantly-simple-solutions/"><u>Fix the 'Too Many Redirects' Error Instantly - Simple Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-windows-11-display-flickers-step-by-step-guide-for-a-stable-viewing-experience/"><u>Fix Your Windows 11 Display Flickers: Step-by-Step Guide for a Stable Viewing Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-right-click-functionality-on-a-windows-10-computer/"><u>How to Repair Right Click Functionality on a Windows 10 Computer</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-motorola-edge-2023-drfone-by-drfone-virtual-android/"><u>In 2024, The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Motorola Edge 2023 | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/movavimp4mp3/"><u>Movaviで簡単なMP4とMP3のフリーコンバートガイド -無料オンライン</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/navigating-through-amazon-luna-a-surprisingly-effortless-cloud-gaming-journey/"><u>Navigating Through Amazon Luna: A Surprisingly Effortless Cloud Gaming Journey</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/premium-virtual-playstation-simulators-for-modern-computers-for-2024/"><u>Premium Virtual PlayStation Simulators for Modern Computers for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/repairing-an-unresponsive-hp-laptop-webcam-when-using-windows-11-best-practices/"><u>Repairing an Unresponsive HP Laptop Webcam When Using Windows 11 - Best Practices</u></a></li>
<li><a href="https://common-error.techidaily.com/silencing-false-warnings-how-to-defend-against-and-eradicate-the-google-chrome-critical-warning-scam/"><u>Silencing False Warnings: How to Defend Against and Eradicate the Google Chrome Critical Warning Scam</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-when-your-usb-to-hdmi-converter-wont-connect/"><u>Solving the Issue: When Your USB To HDMI Converter Won't Connect</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-complete-guide-to-live-streaming-on-instagram-via-obs-for-2024/"><u>The Complete Guide to Live Streaming on Instagram via OBS for 2024</u></a></li>
</ul></div>

