---
title: "Essential Steps: How to Grant Admin Rights for Operations in Windows 11, 10 & 7"
date: 2024-10-11T22:39:37.273Z
updated: 2024-10-18T18:47:53.724Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Essential Steps: How to Grant Admin Rights for Operations in Windows 11, 10 & 7"
excerpt: "This Article Describes Essential Steps: How to Grant Admin Rights for Operations in Windows 11, 10 & 7"
thumbnail: https://thmb.techidaily.com/e15a312e87a88bc573209c8d23ec08d406e2cad56bb144772919196db397e16b.jpg
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-explore-the-best-0-image-editing-tools-on-smartphones-today/"><u>[New] In 2024, Explore the Best $0 Image Editing Tools on Smartphones Today</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-start-live-webcam-recording-with-vlc-media/"><u>[Updated] In 2024, Start Live Webcam Recording with VLC Media</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-screenflow-mastery-on-macos-uncovered-for-2024/"><u>[Updated] ScreenFlow Mastery on macOS Uncovered for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-meme-madness-twitters-funniest-video-threads/"><u>2024 Approved Meme Madness Twitter's Funniest Video Threads</u></a></li>
<li><a href="https://common-error.techidaily.com/critical-requirement-a-compatible-d3d11-graphics-processor-is-mandatory/"><u>Critical Requirement: A Compatible D3D11 Graphics Processor Is Mandatory</u></a></li>
<li><a href="https://fox-http.techidaily.com/evening-stories-visualized-evaluations-for-2024/"><u>Evening Stories Visualized Evaluations for 2024</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-xiaomi-redmi-note-13-5g-phone-without-password-by-drfone-android/"><u>How To Unlock Xiaomi Redmi Note 13 5G Phone Without Password?</u></a></li>
<li><a href="https://common-error.techidaily.com/minimizing-gpu-demand-by-the-desktop-window-manager-in-windows-11-a-5-step-guide/"><u>Minimizing GPU Demand by the Desktop Window Manager in Windows 11: A 5-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-problem-of-being-unable-to-connect-to-your-remote-server/"><u>Resolving the Problem of Being Unable to Connect to Your Remote Server</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-common-problems-and-solutions-for-an-unresponsive-xbox-one-headset/"><u>Solved! Common Problems and Solutions for an Unresponsive Xbox One Headset</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-of-steam-store-wont-load-a-comprehensive-guide/"><u>Solving the Issue of 'Steam Store Won't Load': A Comprehensive Guide</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-the-mystery-of-a-missing-gsdll32dll-file-step-by-step-repair-guide/"><u>Solving the Mystery of a Missing gsdll32.dll File: Step-by-Step Repair Guide</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-poco-x5-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Poco X5 Bricked Devices | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

