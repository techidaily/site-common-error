---
title: Trouble with Updating to Windows 11 v1607? Here's What You Need to Know
date: 2024-08-22T19:22:05.908Z
updated: 2024-08-23T19:22:05.908Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Trouble with Updating to Windows 11 v1607? Here's What You Need to Know
excerpt: This Article Describes Trouble with Updating to Windows 11 v1607? Here's What You Need to Know
thumbnail: https://thmb.techidaily.com/2ca46c2a129dc1360b713c04a30f75e3e36c2cb0f971400d44a0a7430d69515d.jpg
---

## Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It

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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4708689&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.epubor.com/images/uppic/audible-converter-interface.png" border="0">Epubor Audible Converter for Win： Download and convert Audible AAXC/AA/AAX to MP3 with 100% original quality preserved.</a>
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1638364/17190" target="_top" id="1638364"><img src="//a.impactradius-go.com/display-ad/17190-1638364" border="0" alt="" width="1280" height="720"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1638364/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892107/21290" target="_top" id="1892107"><img src="//a.impactradius-go.com/display-ad/21290-1892107" border="0" alt="" width="1200" height="628"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892107/21290" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/fixed-windows-error-0x8000ffff/"><u>[Fixed] Windows Error 0X8000ffff</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-fun-on-faces-a-comprehensive-guide-to-cartoon-snaps/"><u>[New] 2024 Approved  Fun on Faces  A Comprehensive Guide to Cartoon Snaps</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-upload-guide-twitter-video-aspect-ratio-mandated/"><u>[Updated] In 2024, Upload Guide  Twitter Video Aspect Ratio Mandated</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-the-social-media-elite-writes-back-six-essential-tips-to-elevate-your-instagram-presence/"><u>[Updated] The Social Media Elite' Writes Back  Six Essential Tips to Elevate Your Instagram Presence</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-free-game-themes-and-melodies-10-best-websites/"><u>2024 Approved  Free Game Themes & Melodies – 10 Best Websites</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-pro-gopro-filming-tips-for-flawless-results/"><u>2024 Approved  Pro Gopro Filming Tips for Flawless Results</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-vivo-y100i-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Vivo Y100i | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204868401-bypassing-the-stubborn-windows-update-glitch-eliminate-error-0x80240017-now/"><u>Bypassing the Stubborn Windows Update Glitch: Eliminate Error 0X80240017 Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211778357-clear-explanations-eliminating-the-no-signal-monitor-problem-easy-steps-inside/"><u>Clear Explanations: Eliminating the 'No Signal' Monitor Problem Easy Steps Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-for-when-your-device-says-theres-no-battery-fix-now/"><u>Easy Solutions for When Your Device Says There's No Battery – Fix Now</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-logitech-g930-earbuds-disconnection-problems/"><u>Effective Solutions for Logitech G930 Earbuds Disconnection Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-miracast-problems-by-installing-the-right-graphics-driver-solved/"><u>Fix Your Miracast Problems by Installing the Right Graphics Driver [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-pc-failed-to-start-up-correctly-a-comprehensive-guide/"><u>Fixing the 'PC Failed to Start Up Correctly': A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-when-right-click-stops-responding-on-windows-10/"><u>Fixing the Issue: When Right-Click Stops Responding on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-chrome-back-on-track-expert-fixes-for-unresponsiveness/"><u>Get Your Chrome Back on Track: Expert Fixes for Unresponsiveness</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Tecno Pova 5? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-voice-chatting-capability-in-overwatch-fast/"><u>How to Restore Voice Chatting Capability in Overwatch Fast</u></a></li>
<li><a href="https://common-error.techidaily.com/innovative-solutions-stop-the-halt-on-your-hamachi-connection-now/"><u>Innovative Solutions: Stop the Halt on Your Hamachi Connection Now</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-fn-key-malfunction-heres-how-to-restore-it-effortlessly-and-promptly/"><u>Lenovo Fn Key Malfunction? Here’s How to Restore It Effortlessly & Promptly</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-repair-of-your-touchscreen-for-windows-10-5-proven-techniques-to-get-back-control/"><u>Mastering the Repair of Your Touchscreen for Windows 10 - 5 Proven Techniques to Get Back Control</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713961685281-new-are-you-thinking-of-learning-video-editing-in-the-final-cut-pro-software-in-this-article-you-will-learn-different-ways-of-splitting-and-merging-multiple/"><u>New Are You Thinking of Learning Video Editing in the Final Cut Pro Software? In This Article, You Will Learn Different Ways of Splitting and Merging Multiple Videos at Once as a New Skill to Get Your Business to a New Level for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-complete-guide-how-to-edit-movies-or-video-download-online-for-2024/"><u>New Complete Guide How to Edit Movies or Video Download Online for 2024</u></a></li>
<li><a href="https://extra-resources.techidaily.com/organizing-overflow-of-tiktok-saves-for-effective-edits/"><u>Organizing Overflow of TikTok Saves for Effective Edits</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/prime-methods-for-archiving-youtube-real-time-broadcasts/"><u>Prime Methods for Archiving YouTube Real-Time Broadcasts</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-and-effective-ways-to-stop-endless-restart-cycles-in-windows-11/"><u>Quick and Effective Ways to Stop Endless Restart Cycles in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-windows-11-display-dilemma-with-this-guide-to-fix-hdmi-tv-recognition/"><u>Resolve Your Windows 11 Display Dilemma with This Guide to Fix HDMI TV Recognition</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-a-403-forbidden-web-page-a-step-by-step-guide/"><u>Resolving a 403 Forbidden Web Page: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-persistent-windows-update-stalling-at-completion/"><u>Resolving Persistent Windows Update Stalling at Completion</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-binkw32dll-file-not-found-issue-a-step-by-step-guide/"><u>Resolving the 'binkw32.dll' File Not Found Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-update-0x80240034-failure-a-step-by-step-guide/"><u>Resolving the Windows 11 Update 0X80240034 Failure - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-a-step-by-step-guide-to-repairing-error-0xc0000098-on-your-pc/"><u>Solving the Mystery: A Step-by-Step Guide to Repairing Error 0xC0000098 on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-overcoming-elevation-requests-in-windows-os-versions-11107/"><u>Step-by-Step Guide: Overcoming Elevation Requests in Windows OS (Versions 11/10/7)</u></a></li>
<li><a href="https://howto.techidaily.com/stuck-at-android-system-recovery-of-realme-11-pro-fix-it-easily-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Stuck at Android System Recovery Of Realme 11 Pro ? Fix It Easily | Dr.fone</u></a></li>
<li><a href="https://windows11.techidaily.com/surviving-windows-11-blue-screen-adopting-11-key-approaches/"><u>Surviving Windows 11 Blue Screen: Adopting 11 Key Approaches</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-playbook-winning-at-ps1-gaming-on-windows-duckstation-edition/"><u>The Ultimate Playbook: Winning at PS1 Gaming on Windows - Duckstation Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-for-reducing-excessive-svchostexe-load-on-windows-10-system/"><u>Tips for Reducing Excessive svchost.exe Load on Windows 10 System</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-gpu-load-caused-by-the-windows-1011-desktop-window-manager/"><u>Top 5 Solutions for Reducing GPU Load Caused by the Windows 10/11 Desktop Window Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/triumph-over-silent-touchpad-in-device-realm/"><u>Triumph Over Silent Touchpad in Device Realm</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-non-functional-lenovo-mouse-pad-on-widows-os-solutions-for-vistaxp-too/"><u>Troubleshooting a Non-Functional Lenovo Mouse Pad on Widows OS - Solutions for Vista/XP Too</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixes-why-your-pcs-touchpad-scroll-function-fails-in-windows-10/"><u>Troubleshooting Fixes: Why Your PC's Touchpad Scroll Function Fails in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/uncover-the-mystery-why-are-my-desktop-icons-vanishing-in-windows-11-solved/"><u>Uncover the Mystery: Why Are My Desktop Icons Vanishing in Windows 11? [SOLVED]</u></a></li>
</ul></div>
