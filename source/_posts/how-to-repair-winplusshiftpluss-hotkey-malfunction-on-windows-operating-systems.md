---
title: How to Repair Win+Shift+S Hotkey Malfunction on Windows Operating Systems
date: 2024-12-10T19:54:58.651Z
updated: 2024-12-16T21:04:41.288Z
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
<li><a href="https://fox-info.techidaily.com/new-master-the-art-of-photo-display-with-best-frames/"><u>[New] Master the Art of Photo Display with Best Frames</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-saga-selection-the-top-10-best-action-adventure-games/"><u>[Updated] 2024 Approved Saga Selection The Top 10 Best Action-Adventure Games</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/a-comprehensive-guide-to-iphone-xs-max-blacklist-removal-tips-and-tools-drfone-by-drfone-ios/"><u>A Comprehensive Guide to iPhone XS Max Blacklist Removal Tips and Tools | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solution-implemented-for-hardware-monitoring-driver-loading-errors/"><u>Effective Solution Implemented for Hardware Monitoring Driver Loading Errors</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-you-when-your-apple-iphone-se-2020-is-off-drfone-by-drfone-virtual-ios/"><u>In 2024, Can Life360 Track You When Your Apple iPhone SE (2020) is off? | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/latin-quest-exciting-classroom-experiences/"><u>Latin Quest: Exciting Classroom Experiences</u></a></li>
<li><a href="https://fox-web3.techidaily.com/mastering-energy-efficiency-adapting-yls-power-management-tools-for-optimal-performance/"><u>Mastering Energy Efficiency: Adapting YL's Power Management Tools for Optimal Performance</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-take-your-gopro-videos-to-the-next-level-best-alternative-editing-software-for-2024/"><u>New Take Your GoPro Videos to the Next Level Best Alternative Editing Software for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-the-unforeseen-shutdown-of-programs-error-1067-in-windows/"><u>Resolved: Fixing the Unforeseen Shutdown of Programs (Error 1067) in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-a-non-functional-windows-internal-camera-expert-guidance/"><u>Reviving a Non-Functional Windows Internal Camera - Expert Guidance</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-dealing-with-the-troublesome-windows-update-error-code-0x8024401c-in-newest-windows-releases/"><u>Step-by-Step Fixes: Dealing with the Troublesome Windows Update Error Code 0X8024401c in Newest Windows Releases</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-unresponsive-keyboard-keys-in-windows/"><u>Step-by-Step Guide to Fix Unresponsive Keyboard Keys in Windows</u></a></li>
<li><a href="https://win-outstanding.techidaily.com/top-ranked-klonos-utilities-for-silicon-power-ssd-on-windows-111087/"><u>Top Ranked KlonOS Utilities for Silicon Power SSD on Windows 11/10/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-improve-your-pcs-gpu-usage-tackling-windows-1n-desktop-manager-issues/"><u>Troubleshoot and Improve Your PC's GPU Usage – Tackling Windows 1N Desktop Manager Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-system-error-code-5-in-windows-1178-expert-solutions/"><u>Troubleshooting and Fixing System Error Code 5 in Windows 11/7/8 – Expert Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-key-malfunction-on-your-device/"><u>Ultimate Guide: Resolving the '@' Key Malfunction on Your Device</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-persistent-livekernelevent-117-issue/"><u>Ultimate Guide: Resolving the Persistent LiveKernelEvent 117 Issue</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-install-kinemaster-on-mac-a-comprehensive-tutorial-for-2024/"><u>Updated Install KineMaster on Mac A Comprehensive Tutorial for 2024</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/why-cant-i-install-the-ipogo-on-apple-iphone-13-drfone-by-drfone-virtual-ios/"><u>Why cant I install the ipogo On Apple iPhone 13 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

