---
title: How to Overcome Pairing Problems with Bluetooth Devices on Windows 10 - Tips
date: 2024-09-25T16:51:13.989Z
updated: 2024-10-01T17:36:50.786Z
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
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-craft-the-perfect-gif-message-in-snapchat-easy-steps/"><u>[Updated] 2024 Approved Craft the Perfect Gif Message in Snapchat [Easy Steps]</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-photobooth-hiccups-resolving-frozen-playback-issues-for-2024/"><u>[Updated] Photobooth Hiccups Resolving Frozen Playback Issues for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-quick-start-easy-iphone-screen-capture-methods/"><u>[Updated] Quick Start Easy iPhone Screen Capture Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/5-proven-fixes-if-your-mouse-wont-stay-connected-a-comprehensive-tutorial/"><u>5 Proven Fixes If Your Mouse Won't Stay Connected – A Comprehensive Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-overcoming-issues-with-remote-server-connection-failures/"><u>Comprehensive Guide: Overcoming Issues with Remote Server Connection Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-restoring-windows-system-file-integrity-for-version-10-and-11/"><u>Expert Advice on Restoring Windows System File Integrity for Version 10 & 11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/fbx-for-gamers-expert-tips-on-recording-playthroughs-for-2024/"><u>FBX for Gamers Expert Tips on Recording Playthroughs for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcoming-server-access-problems-in-steam-games-and-media-streaming/"><u>Guide to Overcoming Server Access Problems in Steam Games and Media Streaming</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-can-i-get-more-stardust-in-pokemon-go-on-xiaomi-redmi-12-5g-drfone-by-drfone-virtual-android/"><u>How can I get more stardust in pokemon go On Xiaomi Redmi 12 5G? | Dr.fone</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-overcome-the-camera-unavailable-issue-in-snapchat-issue-solved/"><u>How to Overcome the 'Camera Unavailable' Issue in Snapchat (Issue Solved)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-free-premiere-pro-starter-kit-with-top-templates/"><u>In 2024, Free Premiere Pro Starter Kit with Top Templates</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-mastering-media-preservation-instagram-to-iphone-saved/"><u>In 2024, Mastering Media Preservation Instagram to iPhone Saved</u></a></li>
<li><a href="https://common-error.techidaily.com/resetting-keyboards-made-simple-tips-and-tricks/"><u>Resetting Keyboards Made Simple - Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fix-the-driver-failed-due-to-user-setting-errors/"><u>Step-by-Step Guide: Fix the 'Driver Failed Due to User Setting Errors'</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-renderer-initiation-after-patch-implementation-fixes-issues/"><u>Successful Renderer Initiation After Patch Implementation (Fixes Issues)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087239/19272" target="_top" id="2087239">
  <img src="//a.impactradius-go.com/display-ad/19272-2087239" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087239/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

