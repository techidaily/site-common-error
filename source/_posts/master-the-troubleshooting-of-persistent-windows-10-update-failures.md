---
title: Master the Troubleshooting of Persistent Windows 10 Update Failures
date: 2024-09-09T09:00:01.092Z
updated: 2024-09-10T09:00:01.092Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master the Troubleshooting of Persistent Windows 10 Update Failures
excerpt: This Article Describes Master the Troubleshooting of Persistent Windows 10 Update Failures
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afe2f523108.jpg)

When you met boot error with Windows 10, you hoped that automatic repair will help fix the problem. But it got you more troubles. The worse thing is that repair process seems never end. Then what to do to end the loop? Read on to find the solutions.  

 Since the Windows keeps restarting, it is impossible for you access Advanced Options, that you can fix the problem there. In this case, you can boot from a USB or DVD.
  
 To use the solutions below, you’ll need to prepare a bootable USB or a DVD with an installation file on it. If you are not sure how to create a bootable USB, refer [How to Burn Windows 10 ISO to USB](https://tools.techidaily.com/drivereasy/download/) . Note you need to do this on another computer.
  
 **First start your PC from the USB or DVD and open Command Prompt**
  
 1.  
  
 For USB bootable way:  
  
 Plug the USB the computer that has the problem.After you power on the computer, press function key, usually F2 or F12, to enter boot menu. The key to enter boot menu depends on the computers that you are using. You can go to the PC manufacturer’s website to check for it.
  
 For DVD bootable way:  
  
 Insert the DVD to the computer that has the problem. Wait until you see the message “Press any key to boot from CD or DVD”. Press any key to continue. If you don’t see this message, you probably have to change the boot order in the BIOS (Basic Input/Output System) .  
  
 Learn[How to Boot from a USB Drive, DVD or CD](https://tools.techidaily.com/drivereasy/download/) .  
  
 2\. When you go to the setup screen, select the Language that you wish to use.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137203/26400" target="_top" id="2137203">
  <img src="//a.impactradius-go.com/display-ad/26400-2137203" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137203/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
<!-- affiliate ads begin -->
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58b004f363cc4.png)
  
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2\. Type **bcdedit /set GUID recoveryenabled No** and hit**Enter** . Replace GUID with the number that you noted in last step. (For example, if the number is 7ce0dd34-d277-11e4-8263-68f7286346fb, the full command will be “bcdedit /set 7ce0dd34-d277-11e4-8263-68f7286346fb recoveryenabled No”)  
  
 3\. Reboot your PC and Windows should start without no problem.

 **Solution 3: Remove Your RAM**
  
 The loop error can be fixed by simply removing the RAM. You can try this solution. Before removing, remember to turn off the PC.If you have more than one RAM, remove one at a time then start your PC without it. You might need to do this a few times until you test every RAM module.

 After entering Windows, run a disk check to check if there is any problem with the disk, and run a system file check to check if some system files are corrupted. If neither of them work, try to restore Windows registry.  
  
**Run a disk check**
  
 Follow steps below:  
  
 1\. Open[**Command Prompt**](https://tools.techidaily.com/drivereasy/download/) as an administrator.
  
 2\. Type**chkdsk /f /r** and hit**Enter** . You need to wait a while until the process completes.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
<!-- affiliate ads begin -->
<span id="1982508">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982508.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982508">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982508.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982508%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982508/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affee4bc504.png)
  
 Hope the solutions here will help you fix the Windows 10 Automatic Repair loop error.

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
<li><a href="https://youtube-sure.techidaily.com/024-approved-enhance-engagement-mastering-template-based-video-description-writing/"><u>[New] 2024 Approved Enhance Engagement Mastering Template-Based Video Description Writing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-filmmaker-tips-youtube-trailers-using-filmora/"><u>[New] 2024 Approved Filmmaker Tips YouTube Trailers Using Filmora</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-boost-youtube-videos-appeal-3-ways-to-incorporate-neon-borders/"><u>[New] In 2024, Boost YouTube Videos' Appeal - 3 Ways to Incorporate Neon Borders</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-scale-up-snaps-no-loss-in-detail/"><u>[New] Scale Up Snaps - No Loss in Detail</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-usb-to-hdmi-adapter-not-working/"><u>[SOLVED] USB to HDMI Adapter Not Working</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-iphoneipad-top-10-free-youtube-video-editing-apps-for-2024/"><u>[Updated] IPhone/iPad Top 10 Free YouTube Video Editing Apps for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-memes-galore-download-and-share-joy/"><u>[Updated] Memes Galore Download & Share Joy</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-step-by-step-method-for-posting-youtube-videos-in-instagram-stories/"><u>[Updated] Step-by-Step Method for Posting YouTube Videos in Instagram Stories</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-innovative-strategies-for-effective-documentary-scripts/"><u>2024 Approved Innovative Strategies for Effective Documentary Scripts</u></a></li>
<li><a href="https://common-error.techidaily.com/accelerate-your-pcs-shutdown-time-with-these-tips-for-windows-11-users/"><u>Accelerate Your PC's Shutdown Time with These Tips for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-correcting-error-code-0x80072efd-on-your-windows-11-pc/"><u>Comprehensive Guide to Correcting Error Code 0X80072EFD on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-fixing-inoperative-webcams-on-a-windows-machine/"><u>Comprehensive Solutions for Fixing Inoperative Webcams on a Windows Machine</u></a></li>
<li><a href="https://win-able.techidaily.com/1723011723526-conquer-the-nba-2k21-black-screen-challenge-with-our-proven-2024-fixes/"><u>Conquer the NBA 2K21 Black Screen Challenge with Our Proven 2024 Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-directx-errors-that-cant-be-fixed-insightful-strategies-for-success/"><u>Dealing With DirectX Errors That Can’t Be Fixed - Insightful Strategies for Success</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-the-silent-microphone-problem-in-your-corsair-hs50-setup/"><u>Diagnosing and Fixing the Silent Microphone Problem in Your Corsair HS50 Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-malfunctioning-usb-hubs-on-windows-11-systems/"><u>Diagnosing and Repairing Malfunctioning USB Hubs on Windows 11 Systems</u></a></li>
<li><a href="https://win-dash.techidaily.com/easy-installation-guide-epson-workforce-ds-30-driver-compatible-with-windows-1087/"><u>Easy Installation Guide: Epson WorkForce DS-30 Driver Compatible with Windows 10/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-the-unsuccessful-deployment-of-windows-10s-version-1903-upgrade/"><u>Effective Solutions for the Unsuccessful Deployment of Windows 10'S Version 1903 Upgrade</u></a></li>
<li><a href="https://common-error.techidaily.com/errtoomanyredirects-fixed-fast-solutions/"><u>ERR_TOO_MANY_REDIRECTS Fixed: Fast Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1000-troubleshooting-for-windows-operating-systems-win7win8win10/"><u>Error 1000 Troubleshooting for Windows Operating Systems (Win7/Win8/Win10)</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-functionality-to-your-windows-computers-cddvd-drive/"><u>Expert Tips for Restoring Functionality to Your Windows Computer's CD/DVD Drive</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-how-to-troubleshoot-when-your-keyboards-number-keys-stop-responding/"><u>Fixed: How To Troubleshoot When Your Keyboard's Number Keys Stop Responding</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcome-inability-of-windows-to-locate-printer-drivers-fixed/"><u>Guide to Overcome Inability of Windows to Locate Printer Drivers [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-and-rectify-a-failed-directx-device-initialization/"><u>How to Address and Rectify a Failed DirectX Device Initialization</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-fix-a-stuck-cddvd-player-with-error-message-39-expert-advice/"><u>How to Diagnose and Fix a Stuck CD/DVD Player with Error Message 39 – Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-drive-where-windows-is-installed-is-locked-in-windows-11/"><u>How to Fix 'The Drive Where Windows Is Installed Is Locked' In Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-call-of-duty-wwii-error-code-4220-a-comprehensive-guide/"><u>How to Fix Call of Duty WWII Error Code 4220 – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-10-when-it-keeps-restarting-instead-of-shutting-down/"><u>How to Fix Windows 10 When It Keeps Restarting Instead of Shutting Down</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-pc-when-it-refuses-to-power-off-on-windows-11-step-by-step-guide/"><u>How to Fix Your PC When It Refuses to Power Off on Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210593508-how-to-successfully-set-up-battleye-anti-cheat-problems-solved/"><u>How To Successfully Set Up BattlEye Anti-Cheat: Problems Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209842352-how-to-troubleshoot-and-repair-ps4-controller-power-problems-solutions-found/"><u>How to Troubleshoot and Repair PS4 Controller Power Problems - Solutions Found!</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/in-2024-free-video-tools-working-across-systems-seamlessly/"><u>In 2024, Free VIDEO Tools Working Across Systems Seamlessly</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-lock-your-poco-x6-pro-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Poco X6 Pro Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-nokia-c02-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For Nokia C02 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/install-necessary-media-controller-drivers-a-comprehhavisive-guide/"><u>Install Necessary Media Controller Drivers: A Comprehhavisive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-touchpad-malfunctioning-here-are-fixes-for-windows-users/"><u>Laptop Touchpad Malfunctioning? Here Are Fixes for Windows Users!</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-refresh-and-reset-for-optimal-windows-11-performance/"><u>Mastering the Art of Refresh and Reset for Optimal Windows 11 Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-sound-issues-in-forza-horizon-4-proven-fixes-for-an-immersive-racing-experience/"><u>Overcome Sound Issues in Forza Horizon 4: Proven Fixes for an Immersive Racing Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/rapid-remedy-for-missing-logilda/"><u>Rapid Remedy for Missing LogiLDA</u></a></li>
<li><a href="https://techidaily.com/remove-itel-a60-unlock-screen-by-drfone-android-unlock-android-unlock/"><u>Remove Itel A60 unlock screen</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-service-registry-missing-errors-in-windows-10/"><u>Resolving 'Service Registry Missing' Errors in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-your-windows-11s-elusive-trackpad-arrow-issue/"><u>Resolving Your Windows 11'S Elusive Trackpad Arrow Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/silent-no-more-how-to-restore-speaker-function-on-an-acer-laptop/"><u>Silent No More: How to Restore Speaker Function on an Acer Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/simplified-repair-methods-for-fixing-boot-selection-issues-in-windows-systems/"><u>Simplified Repair Methods for Fixing Boot Selection Issues in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/steam-file-error-resolved-complete-restoration-of-missing-game-content/"><u>Steam File Error Resolved: Complete Restoration of Missing Game Content</u></a></li>
<li><a href="https://common-error.techidaily.com/taming-the-beast-reducing-microsoft-malicious-software-removal-tools-cpu-usage-in-windows-10-issue-resolved/"><u>Taming the Beast: Reducing Microsoft Malicious Software Removal Tool's CPU Usage in Windows 10 [ISSUE RESOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-ethernet-not-detected-problems-in-windows-10-and-7/"><u>Troubleshooting Guide: Solving 'Ethernet Not Detected' Problems in Windows 10 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-image-malfunctions-in-microsofts-latest-operating-systems/"><u>Troubleshooting Image Malfunctions in Microsoft's Latest Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-non-functional-astro-a40-mic-step-by-step-guide-to-a-fix/"><u>Troubleshooting the Non-Functional Astro A40 Mic - Step by Step Guide to a Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-overcoming-the-xerox-update-error-0x800f020b-on-pcs/"><u>Troubleshooting Tips for Overcoming the Xerox Update Error: 0X800F020B on PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/unveiling-foddian-games-origins-explored/"><u>Unveiling Foddian Games: Origins Explored</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/v770-a-cheap-luxury-discovery/"><u>V770 - A Cheap Luxury Discovery</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-xiaomi-redmi-note-13-proplus-5g-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Xiaomi Redmi Note 13 Pro+ 5G Phones</u></a></li>
<li><a href="https://common-error.techidaily.com/what-is-msdia80dll-and-why-should-or-shouldnt-you-retain-this-system-file/"><u>What Is msdia80.dll and Why Should (or Shouldn't) You Retain This System File?</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-mic-not-working-heres-how-to-solve-the-problem/"><u>Windows 10 Mic Not Working? Here's How to Solve the Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11s-troublesome-touchscreen-try-these-five-fixes/"><u>Windows 11'S Troublesome Touchscreen? Try These Five Fixes!</u></a></li>
</ul></div>
