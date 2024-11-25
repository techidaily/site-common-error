---
title: Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved
date: 2024-11-20T00:08:13.879Z
updated: 2024-11-25T00:46:31.421Z
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-content-creators-den-for-2024/"><u>[Updated] Content Creator's Den for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-making-history-shine-again-instagram-effects-for-your-archive/"><u>[Updated] Making History Shine Again Instagram Effects for Your Archive</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-seamless-integration-of-srt-files-in-windows-macos/"><u>[Updated] Seamless Integration of SRT Files in Windows, MacOS</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-legality-of-reproducing-your-watched-youtube-videos/"><u>2024 Approved Legality of Reproducing Your Watched YouTube Videos</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-perfecting-the-art-of-documentation-in-virtual-gatherings-google-meet/"><u>2024 Approved Perfecting the Art of Documentation in Virtual Gatherings (Google Meet)</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-poco-m6-pro-4g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Poco M6 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catch-or-beat-sleeping-snorlax-on-pokemon-go-for-poco-f5-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Catch or Beat Sleeping Snorlax on Pokemon Go For Poco F5 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-nokia-c12-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Nokia C12? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-windows-n11-performance-tackling-compatibility-telemetry-disk-overuse/"><u>Optimizing Windows N11 Performance: Tackling Compatibility Telemetry Disk Overuse</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-pubg-server-latency-problems-tips-and-tricks-for-optimal-performance/"><u>Overcoming PUBG Server Latency Problems - Tips & Tricks for Optimal Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-error-8007000e-in-windows-updates-quick-fixes-inside/"><u>Resolve Error 8007000E in Windows Updates: Quick Fixes Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-night-light-malfunction-problems-on-your-pc-running-windows-10-or-11/"><u>Resolving the Night Light Malfunction Problems on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://common-error.techidaily.com/text-duplicate-fails-in-windows-11/"><u>Text Duplicate Fails in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-non-functional-backspace-key-solutions/"><u>Troubleshooting a Non-Functional Backspace Key: Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

