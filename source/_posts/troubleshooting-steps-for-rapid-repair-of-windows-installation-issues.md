---
title: Troubleshooting Steps for Rapid Repair of Windows Installation Issues
date: 2024-08-27T13:41:39.173Z
updated: 2024-08-28T13:41:39.173Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Rapid Repair of Windows Installation Issues
excerpt: This Article Describes Troubleshooting Steps for Rapid Repair of Windows Installation Issues
thumbnail: https://thmb.techidaily.com/1c29d979a20696d19bd8c5c3e9d947157133fd882c32bc816c08287c2bc4feb3.jpg
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
<li><a href="https://common-error.techidaily.com/alert-paste-problematic-windows-11-feature/"><u>[ALERT] Paste Problematic Windows 11 Feature</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-innovate-in-fb-advertising-access-no-cost-video-tools/"><u>[New] 2024 Approved  Innovate in FB Advertising - Access No-Cost Video Tools</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-capturing-nintendo-joy-in-the-best-cards-for-2024/"><u>[New] Capturing Nintendo Joy in the Best Cards for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-in-2024-the-obs-strategy-for-high-quality-skype-screens/"><u>[New] In 2024, The OBS Strategy for High-Quality Skype Screens</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-youtube-dimensions-demystified-a-complete-aspect-ratio-handbook/"><u>[New] YouTube Dimensions Demystified  A Complete Aspect Ratio Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-device-not-migrated-on-windows-11/"><u>[Solved] Device Not Migrated on Windows 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-best-practices-to-avoid-missed-frames-during-video-capture-for-2024/"><u>[Updated] Best Practices to Avoid Missed Frames During Video Capture for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-finding-premium-free-music-without-breaking-copyrights/"><u>[Updated] In 2024, Finding Premium, Free Music Without Breaking Copyrights</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-remedies-for-disabling-obs-fullscreen/"><u>2024 Approved  Remedies for Disabling OBS Fullscreen</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/asias-top-verbal-formulas-priority-store-reverse-order/"><u>Asia’s Top Verbal Formulas: Priority Store, Reverse Order</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-installation-issues-resolved-a-comprehensive-guide/"><u>BattlEye Installation Issues Resolved - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-buffs-expert-hacks-for-fast-tracking-league-of-legends-game-setup/"><u>Bypass Buffs: Expert Hacks for Fast-Tracking League of Legends Game Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolve-windows-update-error-0x8024002e-once-and-for-all/"><u>Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All!</u></a></li>
<li><a href="https://common-error.techidaily.com/decrease-your-computers-workload-combating-high-resource-demand-by-wudfhostexe-on-windows-fixed/"><u>Decrease Your Computer's Workload: Combating High Resource Demand by WUDFHost.exe on Windows ([Fixed])</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-resolving-your-netflix-audio-problems-in-a-jiffy/"><u>Easy Solutions: Resolving Your Netflix Audio Problems in a Jiffy</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-to-combat-excessive-cpu-usage-by-microsofts-msmpengexe-in-win-11-environments/"><u>Effective Fixes to Combat Excessive CPU Usage by Microsoft's MsMpEng.exe in Win 11 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-for-overcoming-the-windows-update-error-0x80070002/"><u>Effortless Solutions for Overcoming the Windows Update Error 0X80070002</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205009552-effortlessly-fix-windows-10-bluetooth-disappearance-issues-in-minutes/"><u>Effortlessly Fix Windows 10 Bluetooth Disappearance Issues in Minutes</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-speaker-noise-on-your-pc-top-fixes-for-windows-11-and-7-systems/"><u>Eliminate Speaker Noise on Your PC: Top Fixes for Windows 11 and 7 Systems</u></a></li>
<li><a href="https://hardware-help.techidaily.com/expert-tips-easy-windows-7-webcam-driver-installation-and-setup/"><u>Expert Tips: Easy Windows 7 Webcam Driver Installation and Setup.</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-computer-freezes-when-playing-games-easily/"><u>Fix Computer Freezes when Playing Games [Easily]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-tips-troubleshooting-a-non-functional-mic-on-windows-10/"><u>Fixes & Tips: Troubleshooting a Non-Functional Mic on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-non-functional-dell-webcam-on-windows-step-by-step-guide/"><u>Fixing a Non-Functional Dell Webcam on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-non-compatible-hardware-drivers-for-a-smoother-world-of-warcraft-experience/"><u>Fixing Non-Compatible Hardware Drivers for a Smoother World of Warcraft Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-d3derr-notavailable/"><u>How To Fix D3DERR NOTAVAILABLE</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211467650-how-to-get-your-astro-a40s-mic-up-and-running-again/"><u>How To Get Your Astro A40's Mic Up and Running Again</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-illumination-on-a-non-responsive-corsair-keyboard/"><u>How to Restore Illumination on a Non-Responsive Corsair Keyboard</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-amplify-visual-appeal-in-tiktok-clips/"><u>In 2024, Amplify Visual Appeal in TikTok Clips</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-can-we-bypass-asus-rog-phone-8-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Asus ROG Phone 8 FRP?</u></a></li>
<li><a href="https://common-error.techidaily.com/navigate-and-organize-files-flawlessly-in-windows-10/"><u>Navigate and Organize Files Flawlessly in Windows 지정기 10</u></a></li>
<li><a href="https://common-error.techidaily.com/oddworld-soulstorm-crashing-on-pc-solved/"><u>Oddworld: Soulstorm Crashing On PC [SOLVED]</u></a></li>
<li><a href="https://howto.techidaily.com/oneplus-nord-n30-5g-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>OnePlus Nord N30 5G Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-how-to-resolve-undetected-battery-problems/"><u>Quick Troubleshooting: How to Resolve Undetected Battery Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-warframe-update-issues-fixed/"><u>Resolving 'Warframe Update' Issues: Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-microsoft-print-to-pdf-malfunction-in-windows-11-systems/"><u>Solving the Microsoft Print to PDF Malfunction in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-connecting-your-microsoft-dock-with-windows-10-resolved/"><u>Step-by-Step Solution for Connecting Your Microsoft Dock with Windows 10 [Resolved]</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-launching-the-hosted-network-feature-in-windows-11-after-common-hurdles/"><u>Successfully Launching the Hosted Network Feature in Windows 11 After Common Hurdles</u></a></li>
<li><a href="https://common-error.techidaily.com/top-solutions-to-resolve-the-werfaultexe-crashing-issue-in-windows-systems/"><u>Top Solutions to Resolve the werFault.exe Crashing Issue in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solutions-for-windows-resource-protection-failures/"><u>Troubleshooting and Solutions for Windows Resource Protection Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-get-dell-webcam-operational-on-windows-systems/"><u>Troubleshooting Guide: How to Get Dell Webcam Operational on Windows Systems</u></a></li>
<li><a href="https://win-able.techidaily.com/ubisoft-connect-problems-heres-the-solution-for-a-smooth-experience/"><u>Ubisoft Connect Problems? Here's the Solution for a Smooth Experience</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/video-splitting-made-easy-a-step-by-step-guide-for-windows-live-movie-maker/"><u>Video Splitting Made Easy A Step-by-Step Guide for Windows Live Movie Maker</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->