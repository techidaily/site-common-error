---
title: How to Repair Win+Shift+S Hotkey Malfunction on Windows Operating Systems
date: 2024-11-26T18:45:20.527Z
updated: 2024-12-03T23:50:36.459Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Repair Win+Shift+S Hotkey Malfunction on Windows Operating Systems
excerpt: This Article Describes How to Repair Win+Shift+S Hotkey Malfunction on Windows Operating Systems
thumbnail: https://thmb.techidaily.com/755e6887211290e7a3605c3c466915e29d575ef749d02f8bbbc7b8223952f6c6.jpg
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
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-crafting-perfect-images-with-ios-size-modification-skills/"><u>[New] 2024 Approved Crafting Perfect Images with iOS Size Modification Skills</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-expert-advice-on-achieving-high-quality-gopro-videos/"><u>[New] Expert Advice on Achieving High-Quality GoPro Videos</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-the-guide-to-instagram-video-advancement-a-planning-primer/"><u>[Updated] 2024 Approved The Guide to Instagram Video Advancement A Planning Primer</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-detailed-guide-to-mastering-recordings-with-audacity/"><u>[Updated] Detailed Guide to Mastering Recordings with Audacity</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-flash-flick-narrative-template-for-2024/"><u>[Updated] Flash Flick Narrative Template for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/browsers-efficiency-ranking-ram-and-cpu-usage-across-oses/"><u>Browsers' Efficiency Ranking: RAM & CPU Usage Across OSes</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-sades-headset-drivers-for-windows-fully-secure-and-compatible/"><u>Download Sades Headset Drivers for Windows - Fully Secure and Compatible</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/mastering-the-reset-process-for-stuck-airpods-a-comprehensive-guide/"><u>Mastering the Reset Process for Stuck AirPods – A Comprehensive Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/maximizing-battery-lifespan-a-walkthrough-of-windows-10s-energy-monitoring-capabilities/"><u>Maximizing Battery Lifespan: A Walkthrough of Windows 10'S Energy Monitoring Capabilities</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-google-chrome-stalling-is-it-time-for-a-fresh-start/"><u>Overcome Google Chrome Stalling: Is It Time for a Fresh Start?</u></a></li>
<li><a href="https://common-error.techidaily.com/renderer-boot-sequence-issue-corrected-for-enhanced-stability-new-fixes-applied/"><u>Renderer Boot Sequence Issue Corrected for Enhanced Stability - New Fixes Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-failed-connection-to-windows-system-event-notification-service/"><u>Resolved: Troubleshooting Failed Connection to Windows System Event Notification Service</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-crash-in-32-bit-applications-print-driver-host/"><u>Resolving the Crash in 32-Bit Applications' Print Driver Host</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-repair-unresponsive-fn-keys-on-your-pc-or-laptop/"><u>Step-by-Step Guide to Repair Unresponsive Fn Keys on Your PC or Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-tackling-windows-update-error-0x80240017-successfully/"><u>Step-by-Step Solutions for Tackling Windows Update Error 0X80240017 Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-call-of-duty-world-war-ii-overcoming-error-4220/"><u>Troubleshooting Guide for Call of Duty World War II - Overcoming Error 4220</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-microsoft-surface-pro-4s-non-responsive-touch-display-complete-solution/"><u>Troubleshooting Microsoft Surface Pro 4'S Non-Responsive Touch Display - Complete Solution</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

