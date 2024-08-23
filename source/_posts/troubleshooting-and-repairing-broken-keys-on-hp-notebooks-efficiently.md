---
title: Troubleshooting and Repairing Broken Keys on HP Notebooks Efficiently
date: 2024-08-22T19:22:21.728Z
updated: 2024-08-23T19:22:21.728Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Repairing Broken Keys on HP Notebooks Efficiently
excerpt: This Article Describes Troubleshooting and Repairing Broken Keys on HP Notebooks Efficiently
thumbnail: https://thmb.techidaily.com/571a13bc6404d66e8575f828248d5c770574159f8a7664c56c7e33516dab19ed.jpg
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
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
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
<li><a href="https://common-error.techidaily.com/dll-diagnosis-resolve-kernel-fails/"><u>[DLL Diagnosis] Resolve Kernel Fails</u></a></li>
<li><a href="https://extra-tips.techidaily.com/new-capture-the-skyline-horizontal-photos-in-a-phone/"><u>[New] Capture the Skyline  Horizontal Photos in a Phone</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-precision-videoplayers-for-high-definition-on-android/"><u>[New] Precision Videoplayers for High Definition on Android</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-troubleshooting-obs-fullscreen-failure/"><u>[Updated] 2024 Approved  Troubleshooting OBS Fullscreen Failure</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-converting-tweeted-videos-into-playable-mp3-tracks/"><u>[Updated] Converting Tweeted Videos Into Playable MP3 Tracks</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-dive-into-the-world-of-expertise-with-youtubes-top-10-makeup-vloggers/"><u>[Updated] In 2024, Dive Into the World of Expertise with YouTube's Top 10 Makeup Vloggers</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-zoom-mastery-for-top-tier-tiktok-live-events/"><u>[Updated] Zoom Mastery for Top-Tier TikTok Live Events</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pro-audio-integration-essential-tips-for-podcasters/"><u>2024 Approved  Pro Audio Integration  Essential Tips for Podcasters</u></a></li>
<li><a href="https://common-error.techidaily.com/airpods-wont-pair-heres-how-to-get-your-earbuds-working-on-windows-11-updated-guide/"><u>AirPods Won't Pair? Here's How to Get Your Earbuds Working on Windows 11 (Updated Guide)</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-pause-a-comprehensive-guide-on-solving-twitch-error-4000-issues/"><u>Beat the Pause: A Comprehensive Guide on Solving Twitch Error 4000 Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-resolving-logitech-keyboard-connectivity-issues-in-windows-11/"><u>Diagnosing and Resolving Logitech Keyboard Connectivity Issues in Windows 11</u></a></li>
<li><a href="https://audio-editing.techidaily.com/effective-ways-to-shrink-large-scale-digital-media-downscale-for-2024/"><u>Effective Ways to Shrink Large Scale Digital Media Downscale for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-diagnosing-and-repairing-the-system-access-violation-error-0xc00e0005-in-windows/"><u>Expert Advice: Diagnosing and Repairing the System Access Violation (Error 0xC00e0005) in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-to-fixing-microsofts-print-to-pdf-functionality-on-windows-11/"><u>Expert Guide to Fixing Microsoft's Print-to-PDF Functionality on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-solutions-for-monster-hunter-world-continuous-freezing-on-pc/"><u>Fixes and Solutions for 'Monster Hunter: World' Continuous Freezing on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-brightness-control-glitch-on-windows-11/"><u>Fixing the Issue: Brightness Control Glitch on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-vcruntime140dll-missing-file-issue-comprehensive-solutions/"><u>Fixing the VCRUNTIME140.dll Missing File Issue: Comprehensive Solutions</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-tecno-phantom-v-fold-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Tecno Phantom V Fold? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-bluetooth-disappearing-on-windows-10-simple-tips-for-seamless-connection/"><u>How To Fix Bluetooth Disappearing on Windows 10: Simple Tips for Seamless Connection</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unresponsive-usb-connections-on-windows-11-pcs/"><u>How to Fix Unresponsive USB Connections on Windows 11 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-key-not-working-in-windows-10/"><u>How to Fix Windows Key Not Working in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-incorrect-characters-while-typing-on-your-keyboard/"><u>How to Fix: Incorrect Characters While Typing on Your Keyboard</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-data-from-apple-iphone-12-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Data from Apple iPhone 12? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-for-explorerexe-crash-in-windows/"><u>Quick Fix for Explorer.exe Crash in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-laptops-mic-wont-work-now-resolved/"><u>Quick Fixes for When Your Laptop's Mic Won't Work – Now Resolved!</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-how-to-resolve-the-d3dx943dll-is-missing-error-in-windows/"><u>Quick Solutions: How to Resolve the 'd3dx9_43.dll Is Missing' Error in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-1087-trackpad-issues-easy-steps-for-restoration-of-functionality/"><u>Solving Windows 10/8/7 Trackpad Issues: Easy Steps for Restoration of Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-non-syncing-ps4-controller-expert-tips-and-advice/"><u>Troubleshooting a Non-Syncing PS4 Controller: Expert Tips & Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-step-by-step-how-to-install-device-drivers-for-windows-7-successfully/"><u>Troubleshooting Step-by-Step: How to Install Device Drivers for Windows 7 Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-fixes-for-windows-media-device-connectivity-failures/"><u>Ultimate Fixes for Windows Media Device Connectivity Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202673984-valorant-wont-load-tips-and-tricks-to-fix-stuck-loading-scenarios/"><u>Valorant Won’t Load? Tips and Tricks to Fix Stuck Loading Scenarios</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->