---
title: Troubleshooting and Repairing Broken Keys on HP Notebooks Efficiently
date: 2024-12-15T01:20:03.717Z
updated: 2024-12-16T17:44:46.589Z
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
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-ultimate-guide-to-remote-podcast-recording/"><u>[Updated] 2024 Approved Ultimate Guide to Remote Podcast Recording</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-a-guide-to-discovering-virtual-augmentations/"><u>[Updated] A Guide to Discovering Virtual Augmentations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-mastering-snapchat-posts-top-15-game-changers/"><u>[Updated] Mastering Snapchat Posts Top 15 Game-Changers</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-perfect-your-igtv-shooting-skills-tips-for-smartphonedslr-cameras/"><u>[Updated] Perfect Your IGTV Shooting Skills Tips for Smartphone/DSLR Cameras</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-transform-your-vision-30-video-presentation-tips-for-2024/"><u>[Updated] Transform Your Vision 30 Video Presentation Tips for 2024</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-you-when-your-vivo-x100-is-off-drfone-by-drfone-virtual-android/"><u>Can Life360 Track You When Your Vivo X100 is off? | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/le-non-specific-youtube-video-alerts-for-2024/"><u>Disable Non-Specific YouTube Video Alerts for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/enabling-virtual-reality-on-your-phone-a-step-by-step-approach-for-2024/"><u>Enabling Virtual Reality on Your Phone A Step-by-Step Approach for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-resolving-microsoft-print-to-pdf-problems-across-windows-1011-systems/"><u>Expert Tips: Resolving Microsoft Print to PDF Problems Across Windows 10/11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-audio-control-problems-in-windows-11-a-step-by-step-guide-to-restoring-functionality/"><u>Fixing Audio Control Problems in Windows 11 – A Step-by-Step Guide to Restoring Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-invalid-directory-name-error-expert-solutions/"><u>Fixing the 'Invalid Directory Name' Error – Expert Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-name-is-not-a-valid-directory-mistake-easily/"><u>How to Fix the 'Name Is Not a Valid Directory' Mistake Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210441599-how-to-resolve-there-was-an-error-setting-up-your-pc-bug-in-windows-11-fixed-now/"><u>How to Resolve 'There Was an Error Setting up Your PC' Bug in Windows 11 - Fixed Now!</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/24-ultimate-selection-of-free-youtube-introduction-makers/"><u>In 2024, Ultimate Selection of Free YouTube Introduction Makers</u></a></li>
<li><a href="https://common-error.techidaily.com/optimize-your-pc-solve-msmpengexe-overloading-cpu-on-windows-11-systems/"><u>Optimize Your PC: Solve MsMpEng.exe Overloading CPU on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-how-to-resolve-wacom-tablet-malfunctions-easily/"><u>Troubleshooting Tips: How to Resolve Wacom Tablet Malfunctions Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-troubleshooting-and-solutions-for-persistent-usb-connection-issues/"><u>Ultimate Guide: Troubleshooting & Solutions for Persistent USB Connection Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RhLjZsruC9M?si=-861oUSfrUde2Ykt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

