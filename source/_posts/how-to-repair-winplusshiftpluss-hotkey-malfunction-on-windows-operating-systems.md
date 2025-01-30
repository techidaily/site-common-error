---
title: How to Repair Win+Shift+S Hotkey Malfunction on Windows Operating Systems
date: 2025-01-27T19:12:31.665Z
updated: 2025-01-29T20:21:27.477Z
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
<li><a href="https://extra-hints.techidaily.com/new-10-groundbreaking-examples-of-the-metaverse-unpacked/"><u>[New] 10 Groundbreaking Examples of the Metaverse Unpacked</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ow-to-safely-capture-your-favorite-youtube-audio-for-free/"><u>[New] How to Safely Capture Your Favorite YouTube Audio for Free</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-the-untold-elements-of-instagram-story-engagement-for-2024/"><u>[New] The Untold Elements of Instagram Story Engagement for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-navigate-to-facebooks-recently-viewed-videos-for-2024/"><u>[Updated] Navigate to Facebook's Recently Viewed Videos for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-realme-narzo-n55-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Realme Narzo N55 Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/dell-laptop-malfunction-how-to-troubleshoot-and-repair-unresponsive-keys-easily/"><u>Dell Laptop Malfunction? How To Troubleshoot and Repair Unresponsive Keys Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-auto-boot-issues-on-a-windows-11-system-solutions-inside/"><u>Diagnosing Auto-Boot Issues on a Windows 11 System – Solutions Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-easily-overcome-the-frustrating-windows-update-problem-x0x80070652-bug/"><u>How to Easily Overcome the Frustrating Windows Update Problem: X0X80070652 Bug</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-tackle-and-solve-the-frustrating-0x80073712-error-code-in-windows-11/"><u>How to Tackle and Solve the Frustrating 0X80073712 Error Code in Windows 11</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-easy-ways-to-copy-contacts-from-samsung-galaxy-a15-4g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Easy Ways to Copy Contacts from Samsung Galaxy A15 4G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-full-guide-to-bypass-vivo-y17s-frp-by-drfone-android/"><u>In 2024, Full Guide to Bypass Vivo Y17s FRP</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-semaphore-error-0x80070079-connection-timeout-issue/"><u>Troubleshooting Steps for Semaphore Error 0X80070079 - Connection Timeout Issue</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/ultimate-list-of-heartwarming-movies-ideal-for-a-mother-daughter-movie-night/"><u>Ultimate List of Heartwarming Movies Ideal for a Mother-Daughter Movie Night</u></a></li>
<li><a href="https://extra-resources.techidaily.com/ultimate-selection-free-photo-enhancement-tools-for-iphones/"><u>Ultimate Selection Free Photo Enhancement Tools for iPhones</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-7-and-bluetooth-made-easy-turn-on-and-fix-common-issues/"><u>Windows 7 and Bluetooth Made Easy - Turn On & Fix Common Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9sk53d1bBhY?si=yaTeDogLb3D4dYu1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

