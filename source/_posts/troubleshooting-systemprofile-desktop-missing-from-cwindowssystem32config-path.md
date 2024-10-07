---
title: "Troubleshooting SystemProfile Desktop Missing From C:\\Windows\\system32\\config Path"
date: 2024-10-04T17:20:53.776Z
updated: 2024-10-07T11:45:33.858Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting SystemProfile Desktop Missing From C:\\Windows\\system32\\config Path"
excerpt: "This Article Describes Troubleshooting SystemProfile Desktop Missing From C:\\Windows\\system32\\config Path"
thumbnail: https://thmb.techidaily.com/14a25359b86e19d1002308583500dde5e5cec05558fa18656a09087a1aaee21b.jpg
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
<li><a href="https://on-screen-recording.techidaily.com/new-2024-approved-leading-edge-group-chat-apps-on-android-5plus-users/"><u>[New] 2024 Approved Leading Edge Group Chat Apps on Android (5+ Users)</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-file-explorer-keeps-crashing-on-windows-1110/"><u>[SOLVED] Windows File Explorer Keeps Crashing on Windows 11/10</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-high-quality-8-android-video-callers-for-groups-above-four/"><u>[Updated] 2024 Approved High-Quality 8 Android Video Callers for Groups Above Four</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-ace-your-reel-rankings-by-following-leading-tiktok-strategies-for-2024/"><u>[Updated] Ace Your Reel Rankings by Following Leading TikTok Strategies for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-photo-fables-the-best-ios-and-android-text-apps-for-pictures-for-2024/"><u>[Updated] Photo Fables The Best iOS & Android Text Apps for Pictures for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-mastering-3d-text-illustration-in-adobe-illustrator/"><u>2024 Approved Mastering 3D Text Illustration in Adobe Illustrator</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-retrace-your-steps-flipping-iphone-videography/"><u>2024 Approved Retrace Your Steps Flipping iPhone Videography</u></a></li>
<li><a href="https://common-error.techidaily.com/clear-solutions-for-victims-of-the-misleading-google-chrome-urgent-alert-fraud/"><u>Clear Solutions for Victims of the Misleading Google Chrome Urgent Alert Fraud</u></a></li>
<li><a href="https://common-error.techidaily.com/crack-the-code-effective-solutions-to-tackle-windows-11-update-error-0x80240034/"><u>Crack the Code: Effective Solutions to Tackle Windows 11 Update Error 0X80240034</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-device-drivers-not-found-issue-when-setting-up-windows-7-comprehensive-guide/"><u>How to Fix: 'Device Drivers Not Found' Issue When Setting Up Windows 7 [Comprehensive Guide]</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-samsung-galaxy-s23-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Samsung Galaxy S23? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/incompatibility-issues-in-ftdi-systems-leading-to-unintended-memory-guard-removal/"><u>Incompatibility Issues in FTDI Systems Leading to Unintended Memory Guard Removal</u></a></li>
<li><a href="https://common-error.techidaily.com/new-world-update-release-fixing-the-easy-anti-cheat-startup-issue/"><u>New World Update Release - Fixing the Easy Anti-Cheat Startup Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-hidden-or-gone-mouse-icons-in-windows-10-effective-fixes-and-advice/"><u>Overcoming Hidden or Gone Mouse Icons in Windows 10: Effective Fixes and Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-a-non-functioning-logitech-keyboard/"><u>Quick Fixes for a Non-Functioning Logitech Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-geforce-experience-doesnt-start-problem-complete-solution/"><u>Resolving the 'GeForce Experience Doesn't Start' Problem - Complete Solution</u></a></li>
<li><a href="https://technical-tips.techidaily.com/step-by-step-solution-overcoming-the-netflix-error-ui-800-3/"><u>Step-by-Step Solution: Overcoming the Netflix Error (UI-800-3)</u></a></li>
<li><a href="https://extra-resources.techidaily.com/the-new-era-of-mac-os-embracing-big-sur/"><u>The New Era of Mac OS Embracing Big Sur</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-eliminate-monitor-blank-screen-mistake/"><u>Troubleshooting Tips: Eliminate Monitor Blank Screen Mistake</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

