---
title: "Unstick Your Windows Update: Clearing that Persistent 100%% Barrier – Now Solved"
date: 2024-10-11T19:08:03.982Z
updated: 2024-10-12T18:37:02.092Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Unstick Your Windows Update: Clearing that Persistent 100%% Barrier – Now Solved"
excerpt: "This Article Describes Unstick Your Windows Update: Clearing that Persistent 100%% Barrier – Now Solved"
thumbnail: https://thmb.techidaily.com/5599db5b0351dfe7fe4d3ef01a51b823176684e86c63c43fb2d60eaab80af0aa.jpg
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
<li><a href="https://article-knowledge.techidaily.com/updated-2024-approved-why-cant-i-watch-video-on-sony-a6400-camera/"><u>[Updated] 2024 Approved Why Can't I Watch Video on Sony A6400 Camera?</u></a></li>
<li><a href="https://common-error.techidaily.com/0x80073712-error-code-in-windows-10-solved/"><u>0X80073712 Error Code in Windows 10 [SOLVED]</u></a></li>
<li><a href="https://youtube-data.techidaily.com/approved-download-youtube-images-with-ease-online/"><u>2024 Approved Download YouTube Images with Ease Online</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-inside-look-whatsapps-voice-message-technology/"><u>2024 Approved Inside Look WhatsApp's Voice Message Technology</u></a></li>
<li><a href="https://techtrends.techidaily.com/a-beginners-guide-accessing-hulu-through-your-lg-smart-tv/"><u>A Beginner's Guide: Accessing Hulu Through Your LG Smart TV</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/guide-to-mirror-your-vivo-y100i-to-other-android-devices-drfone-by-drfone-android/"><u>Guide to Mirror Your Vivo Y100i to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-windows-update-problem-0x80070643-for-uninterrupted-pc-performance/"><u>How to Overcome Windows Update Problem 0X80070643 for Uninterrupted PC Performance</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-forgotten-the-voicemail-password-of-samsung-galaxy-a05s-try-these-fixes-by-drfone-android/"><u>In 2024, Forgotten The Voicemail Password Of Samsung Galaxy A05s? Try These Fixes</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/pertama-tersedia-sederhana-perbaikan-akcesor-feedback-untuk-pengucapan-windows-11-explorer-gading/"><u>Pertama-Tersedia Sederhana Perbaikan Akcesor Feedback Untuk Pengucapan Windows 11 Explorer Gading</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-unresponsive-right-click-problem-on-windows-11-pcs/"><u>Resolving the Unresponsive Right-Click Problem on Windows 11 PCs</u></a></li>
<li><a href="https://win11-tips.techidaily.com/tackling-the-transformation-from-a-simple-pin-to-a-stronger-passphrase-in-windows-11/"><u>Tackling the Transformation: From a Simple PIN to a Stronger Passphrase in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/tech-support-guide-best-practices-for-dealing-with-a-sluggish-windows-11-experience/"><u>Tech Support Guide: Best Practices for Dealing with a Sluggish Windows 11 Experience</u></a></li>
<li><a href="https://techidaily.com/video-file-repair-how-to-fix-corrupted-video-files-of-gt-5-by-stellar-video-repair-mobile-video-repair/"><u>Video File Repair - How to Fix Corrupted video files of GT 5?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1166360/14483" target="_top" id="1166360">
  <img src="//a.impactradius-go.com/display-ad/14483-1166360" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://electronicx.pxf.io/i/5597632/1166360/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

