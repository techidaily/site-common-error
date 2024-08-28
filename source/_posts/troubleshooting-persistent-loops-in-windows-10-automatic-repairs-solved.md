---
title: Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved
date: 2024-08-27T13:46:35.613Z
updated: 2024-08-28T13:46:35.613Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved
excerpt: This Article Describes Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-engineering-captivating-video-teasers-for-online-presence/"><u>[New] 2024 Approved  Engineering Captivating Video Teasers for Online Presence</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-vimeo-in-a-nutshell-the-video-sharing-experience/"><u>[New] 2024 Approved  Vimeo in a Nutshell  The Video Sharing Experience</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-behind-the-scenes-mastering-the-craft-of-streaming-archiving/"><u>[New] In 2024, Behind the Scenes  Mastering the Craft of Streaming Archiving</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-unlock-your-tech-potential-mastering-macs-screen-capturing-with-just-shortcuts/"><u>[Updated] 2024 Approved  Unlock Your Tech Potential  Mastering Mac's Screen Capturing with Just Shortcuts</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-best-camera-lenses-for-youtube-for-2024/"><u>[Updated] Best Camera Lenses for YouTube for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-mastering-the-art-of-capturing-sims-4-essential-techniques-unveiled/"><u>[Updated] Mastering the Art of Capturing Sims 4 – Essential Techniques Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-road-warriors-top-virtual-races-listed-for-2024/"><u>[Updated] Road Warriors  Top Virtual Races Listed for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-constructing-captivating-podcast-vignettes/"><u>2024 Approved  Constructing Captivating Podcast Vignettes</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-driving-traffic-and-likes-a-guide-for-instagram-pros/"><u>2024 Approved  Driving Traffic & Likes  A Guide for Instagram Pros</u></a></li>
<li><a href="https://fake-location.techidaily.com/apply-these-techniques-to-improve-how-to-detect-fake-gps-location-on-itel-a60s-drfone-by-drfone-virtual-android/"><u>Apply These Techniques to Improve How to Detect Fake GPS Location On Itel A60s | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-effortless-steps-to-reboot-your-keyboard/"><u>Complete Guide: Effortless Steps to Reboot Your Keyboard</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/1722869626620-concerts-by-international-orchestras-and-vocal-ensembles-opera-operetta-at-prague-castle/"><u>Concerts by International Orchestras and Vocal Ensembles (Opera, Operetta) at Prague Castle</u></a></li>
<li><a href="https://common-error.techidaily.com/csgo-stability-solutions-fix-game-crashes-with-simple-techniques/"><u>CSGO Stability Solutions: Fix Game Crashes with Simple Techniques</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/elevate-youtube-video-quality-minimize-distractions-for-2024/"><u>Elevate YouTube Video Quality, Minimize Distractions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-ensuring-successful-bluetooth-pairing-on-your-windows-11-device/"><u>Expert Advice : Ensuring Successful Bluetooth Pairing on Your Windows 11 Device</u></a></li>
<li><a href="https://hardware-help.techidaily.com/high-precision-alpine-navigation-mouse-software/"><u>High-Precision Alpine Navigation Mouse Software</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-to-bypass-google-frp-on-nokia-c12-by-drfone-android-unlock-remove-google-frp/"><u>How To Bypass Google FRP on Nokia C12</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-silence-a-noisy-ps4-system-for-quiet-gaming-sessions/"><u>How to Silence a Noisy PS4 System for Quiet Gaming Sessions</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-realme-note-50-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Realme Note 50 in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-mastering-screencasts-a-step-by-step-manual/"><u>In 2024, Mastering Screencasts  A Step-by-Step Manual</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-problems-at-boot-up-heres-your-solution/"><u>Keyboard Problems at Boot-Up? Here's Your Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/oncogenes-activation-and-tumor-suppressors-inactivation/"><u>Oncogenes Activation and Tumor Suppressors Inactivation</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-miracast-connectivity-challenges-caused-by-outdated-or-incompatible-drivers/"><u>Overcoming Miracast Connectivity Challenges Caused by Outdated or Incompatible Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-startup-problems-solutions-to-unstick-your-computer-during-windows-boot-up/"><u>Overcoming Startup Problems: Solutions to Unstick Your Computer During Windows Boot-Up</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-frustration-a-guide-to-deciphering-and-correcting-minecraft-error-code-5/"><u>Overcoming the Frustration: A Guide to Deciphering and Correcting Minecraft Error Code 5</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-11-connectivity-challenges-microsoft-wireless-display-adapter-solutions-revealed/"><u>Overcoming Windows 11 Connectivity Challenges: Microsoft Wireless Display Adapter Solutions Revealed</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/removing-user-pin-authentication-from-windows-10-easy-instructions-inside/"><u>Removing User Pin Authentication From Windows 10 – Easy Instructions Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/renderer-setup-difficulties-resolved-by-2021-patch-implementations/"><u>Renderer Setup Difficulties Resolved by 2021 Patch Implementations</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-non-operational-status-of-diagnostics-management-service/"><u>Resolving the Non-Operational Status of Diagnostics Management Service</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-win32-app-crash-with-code-0xc0000005-a-step-by-step-guide/"><u>Resolving the Win32 App Crash with Code 0xC0000005: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/revealing-the-hidden-making-bluetooth-appear-on-device-manager-guide/"><u>Revealing the Hidden: Making Bluetooth Appear on Device Manager [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-speeding-up-your-windows-10-system-shutdown/"><u>Solution for Speeding Up Your Windows 10 System Shutdown</u></a></li>
<li><a href="https://win-able.techidaily.com/solving-your-dilemma-ultimate-guide-to-troubleshoot-cs-go-failure-to-start/"><u>Solving Your Dilemma: Ultimate Guide to Troubleshoot CS: GO Failure to Start</u></a></li>
<li><a href="https://common-error.techidaily.com/the-essentials-of-msdia80dll-its-functions-and-importance-in-windows/"><u>The Essentials of msdia80.dll: Its Functions & Importance in Windows</u></a></li>
<li><a href="https://video-capture.techidaily.com/the-essentials-to-record-save-and-refine-videography-on-adobe-connect-for-2024/"><u>The Essentials to Record, Save, & Refine Videography on Adobe Connect for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/the-laptop-headset-harmony-breakthrough-solution/"><u>The Laptop-Headset Harmony Breakthrough Solution</u></a></li>
<li><a href="https://buynow-help.techidaily.com/the-ultimate-gamers-guide-to-the-samsung-q6nq-led-4k-smart-tv-review/"><u>The Ultimate Gamers Guide to the Samsung Q6nQ LED 4K Smart TV Review</u></a></li>
<li><a href="https://common-error.techidaily.com/top-tips-to-eliminate-slow-connections-and-improve-csgo-ping/"><u>Top Tips to Eliminate Slow Connections and Improve CS:Go Ping</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolving-issues-with-your-dells-usb-connection/"><u>Troubleshooting Tips: Resolving Issues with Your Dell's USB Connection</u></a></li>
<li><a href="https://common-error.techidaily.com/uncovered-missing-core-library-loader-dll/"><u>Uncovered Missing Core Library Loader Dll</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-windows-1110-shortcut-mysteries-solving-windows-plus-shift-plus-s-not-working-dilemma/"><u>Unlocking Windows 11/10 Shortcut Mysteries: Solving 'Windows + Shift + S' Not Working Dilemma</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/utilizing-the-innovative-solutions-provided-by-cookiebot/"><u>Utilizing the Innovative Solutions Provided by Cookiebot</u></a></li>
<li><a href="https://common-error.techidaily.com/warframe-no-longer-receiving-updates-diagnosing-and-fixing-the-error/"><u>Warframe No Longer Receiving Updates: Diagnosing and Fixing the Error</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-typing-troubles-heres-how-to-eliminate-keyboard-delay/"><u>Windows 10 Typing Troubles? Here's How to Eliminate Keyboard Delay!</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-update-error-overcoming-incessant-restart-cycles-in-win-1110/"><u>Windows Update Error - Overcoming Incessant Restart Cycles in Win 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-wudfhostexe-tackling-overwhelming-cpu-usage-in-windows-11-environments/"><u>Winning the Battle Against WUDFHost.exe: Tackling Overwhelming CPU Usage in Windows 11 Environments</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://parisrhonecom.sjv.io/c/5597632/1896607/21553" target="_top" id="1896607"><img src="//a.impactradius-go.com/display-ad/21553-1896607" border="0" alt="" width="750" height="422"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1896607/21553" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->