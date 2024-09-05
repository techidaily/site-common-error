---
title: Fixes for Non-Functioning Night Light Feature in Windows 11
date: 2024-09-04T20:17:12.673Z
updated: 2024-09-05T20:17:12.673Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixes for Non-Functioning Night Light Feature in Windows 11
excerpt: This Article Describes Fixes for Non-Functioning Night Light Feature in Windows 11
thumbnail: https://thmb.techidaily.com/b2e687db976d53413ad200065943dddbaf2bd03eb2c28e9e47c24fc4c8af2aa4.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

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
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<span id="1834903">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834903.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834903">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834903.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834903%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834903/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094419/7443" target="_top" id="2094419">
  <img src="//a.impactradius-go.com/display-ad/7443-2094419" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094419/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-aspect-ratio-compliance-for-youtube-style-tweets-for-2024/"><u>[New] Aspect Ratio Compliance for YouTube-Style Tweets for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-speak-out-leverage-ai-gratis/"><u>[Updated] Speak Out, Leverage AI Gratis</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-the-potential-of-monetized-vlogs/"><u>[Updated] Unlocking the Potential of Monetized Vlogs</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-contacts-files-on-samsung-galaxy-m34-by-fonelab-android-recover-contacts/"><u>Complete guide for recovering contacts files on Samsung Galaxy M34.</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-tackle-videodxgkrnl-fatal-issues-on-windows-machines/"><u>Comprehensive Solutions to Tackle Video_Dxgkrnl Fatal Issues on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-initialization-errors-for-windows-10-system-settings/"><u>Diagnosing and Repairing Initialization Errors for Windows 10 System Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-windows-update-error-0x80070652/"><u>Easy to Fix Windows Update Error 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-critical-issue-0x8024200d-during-windows-update-process-complete/"><u>Effective Fixes for Critical Issue 0X8024200d During Windows Update Process [COMPLETE]</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-fixes-for-quick-recovery-from-windows-setup-errors/"><u>Fast Fixes for Quick Recovery From Windows Setup Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-frozen-screen-top-tips-for-dealing-with-windows-10-freezes/"><u>Fixing a Frozen Screen: Top Tips for Dealing with Windows 10 Freezes</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-delayed-typing-fast-and-easy-methods-for-a-responsive-keyboard/"><u>Fixing Delayed Typing - Fast & Easy Methods for a Responsive Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-wd-my-passport-ultra-missing-from-windows-device-manager/"><u>Fixing the Issue: WD My Passport Ultra Missing From Windows Device Manager</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/garageband-guide-gently-dissolve-decibels-for-2024/"><u>Garageband Guide  Gently Dissolve Decibels for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-enabling-bluetooth-connectivity-in-windows-7-solutions-revealed/"><u>Guide: Enabling Bluetooth Connectivity in Windows 7 - Solutions Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-device-not-detected-problem-fixing-error-code-24-on-windows-os/"><u>How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quiet-your-playstation-4-diagnosing-and-repairing-louder-than-usual-fan-sounds/"><u>How to Quiet Your PlayStation 4: Diagnosing and Repairing Louder-Than-Usual Fan Sounds</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-cards-of-vivo-v29-without-puk-codes-by-drfone-android/"><u>How To Unlock SIM Cards Of Vivo V29 Without PUK Codes</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-use-device-manager-to-update-drivers-in-windows-11-by-drivereasy-guide/"><u>How to use Device Manager to update drivers in Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-facebook-video-extravaganza-the-most-advanced-fire-browser-tools-updated/"><u>In 2024, Facebook Video Extravaganza  The Most Advanced Fire-Browser Tools, Updated</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-iphone-13-by-drfone-ios/"><u>In 2024, New Multiple Ways How To Remove iCloud Activation Lock On your iPhone 13</u></a></li>
<li><a href="https://common-error.techidaily.com/new-world-overcomes-previous-easy-anti-cheat-issues-now-fully-functional/"><u>New World Overcomes Previous Easy Anti-Cheat Issues: Now Fully Functional</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-obstacles-a-fixed-nvidia-error/"><u>Overcoming Obstacles: A Fixed NVIDIA Error</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-problems-with-starting-a-hosted-network-in-windows-11-solutions-and-guidance/"><u>Overcoming Problems with Starting a Hosted Network in Windows 11: Solutions and Guidance</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-overcoming-heathstone-game-lags/"><u>Quick Solutions for Overcoming Heathstone Game Lags</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rebuilding-corrupted-avchd-tapes/"><u>Rebuilding Corrupted AVCHD Tapes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-endless-windows-update-progress-at-100/"><u>Resolved: Troubleshooting Endless Windows Update Progress at 100%%</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-connection-errors-in-geforce-experience-settings-retrieval/"><u>Resolving Connection Errors in GeForce Experience Settings Retrieval</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-elevated-cpu-consumption-in-system-idle-process-a-comprehensive-guide/"><u>Resolving Elevated CPU Consumption in System Idle Process: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-folder-navigation-in-windows-10-easy-tips-for-using-file-explorer/"><u>Seamless Folder Navigation in Windows 10 - Easy Tips for Using File Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-steam-api-dll-errors/"><u>Solutions for Steam API DLL Errors</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-the-problem-of-constant-crashing-for-players-of-metro-exodus-pc-version/"><u>Solving the Problem of Constant Crashing for Players of Metro Exodus PC Version</u></a></li>
<li><a href="https://common-error.techidaily.com/speaker-crackling-in-windows-117-solved/"><u>Speaker Crackling in Windows 11/7 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/system-compliant-with-all-configurations-yet-lacking-response/"><u>System Compliant with All Configurations Yet Lacking Response</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208217755-the-ultimate-fix-guide-for-overcoming-error-1068-in-windows-expert-advice-included/"><u>The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-complete-battleye-installation-now-running-smoothly/"><u>Troubleshooting Complete: BattlEye Installation Now Running Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-a-non-responsive-microsoft-keyboard/"><u>Troubleshooting Guide for a Non-Responsive Microsoft Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-missing-device-drivers-on-windows-7-installation/"><u>Troubleshooting Guide: Missing Device Drivers on Windows 7 Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-overcoming-no-pentouch-issues-on-your-monitor/"><u>Troubleshooting Guide: Overcoming 'No Pen/Touch' Issues on Your Monitor</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-windows-error-0x80n04cf/"><u>Troubleshooting Tips for Fixing Windows Error 0X80n04CF</u></a></li>
</ul></div>
