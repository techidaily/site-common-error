---
title: How to Overcome Pairing Problems with Bluetooth Devices on Windows 10 - Tips
date: 2024-09-24T20:46:02.819Z
updated: 2024-09-26T20:01:38.339Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Overcome Pairing Problems with Bluetooth Devices on Windows 10 - Tips
excerpt: This Article Describes How to Overcome Pairing Problems with Bluetooth Devices on Windows 10 - Tips
thumbnail: https://thmb.techidaily.com/a23ef58f3369824904efee9f97817b15b093c9dc4ea1ce81d7226560e11dda64.jpg
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
<li><a href="https://some-techniques.techidaily.com/new-guide-switching-on-windows-11s-dynamic-hdr-mode/"><u>[New] Guide Switching on Windows 11'S Dynamic HDR Mode</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-kickstarting-a-vlog-key-hardware-and-apps/"><u>[New] Kickstarting a Vlog Key Hardware & Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-leveraging-famebits-expertise-for-maximum-youtube-affiliate-gains/"><u>[New] Leveraging FameBit's Expertise for Maximum YouTube Affiliate Gains</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-in-2024-the-reality-of-youtubes-fast-subscribe-technique/"><u>[Updated] In 2024, The Reality of YouTube's Fast Subscribe Technique</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-non-responsive-lenovo-mouse-pads-in-various-windows-versions/"><u>Effective Solutions for Non-Responsive Lenovo Mouse Pads in Various Windows Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209900034-elaborate-on-how-solving-problems-aids-personal-growth-and-self-reliance/"><u>Elaborate on How Solving Problems Aids Personal Growth and Self-Reliance</u></a></li>
<li><a href="https://some-guidance.techidaily.com/explore-the-best-18-windows-compatible-movies-created-for-professional-use-on-windows-os-versions-1087/"><u>Explore the Best 18 Windows-Compatible Movies Created for Professional Use on Windows OS Versions 10/8/7</u></a></li>
<li><a href="https://tech-revival.techidaily.com/gpts-role-in-achieving-career-aspirations/"><u>GPT's Role in Achieving Career Aspirations</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-corrupted-windows-store-database-a-complete-guide/"><u>How to Fix a Corrupted Windows Store Database - A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-your-aoc-monitors-functionality-on-a-windows-11-system/"><u>How to Restore Your AOC Monitor's Functionality on a Windows 11 System</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-will-the-ipogo-get-you-banned-and-how-to-solve-it-on-samsung-galaxy-f54-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Will the iPogo Get You Banned and How to Solve It On Samsung Galaxy F54 5G | Dr.fone</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/smartphone-cinematics-samsungs-guide-to-time-lapse-for-2024/"><u>Smartphone Cinematics Samsung's Guide to Time-Lapse for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-resolve-windows-11-update-error-code-0x80e705b4/"><u>Step-by-Step Solutions to Resolve Windows 11 Update Error Code 0X80e705B4</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-resolving-disappeared-desktop-icon-issues-in-win10/"><u>Troubleshooting and Resolving Disappeared Desktop Icon Issues in Win10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-windows-11-update-error-code-0x80240034/"><u>Troubleshooting Guide: Resolving Windows 11 Update Error Code 0X80240034</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-infinix-note-30-by-fonelab-android-recover-photos/"><u>Undelete lost photos from Infinix Note 30.</u></a></li>
<li><a href="https://common-error.techidaily.com/wd-my-passport-ultra-not-showing-up-in-device-manager-solutions-to-try/"><u>WD My Passport Ultra Not Showing Up in Device Manager – Solutions to Try</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528693/16446" target="_top" id="1528693">
  <img src="//a.impactradius-go.com/display-ad/16446-1528693" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528693/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
