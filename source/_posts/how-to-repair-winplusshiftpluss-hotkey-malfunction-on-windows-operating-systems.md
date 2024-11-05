---
title: How to Repair Win+Shift+S Hotkey Malfunction on Windows Operating Systems
date: 2024-11-03T00:48:06.311Z
updated: 2024-11-05T09:03:22.210Z
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
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-leveraging-likes-and-comments-enhancing-engagement-on-instagram-stories/"><u>[Updated] 2024 Approved Leveraging Likes and Comments Enhancing Engagement on Instagram Stories</u></a></li>
<li><a href="https://discover-answers.techidaily.com/1-come-superare-lissue-del-blocchaggio-di-itunes-durante-la-sincronizzazione-dei-backup/"><u>1. Come Superare L'Issue Del Blocchaggio Di iTunes Durante La Sincronizzazione Dei Backup</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-steps-for-retrieving-personal-hidden-snapchat-photos/"><u>2024 Approved Steps for Retrieving Personal, Hidden Snapchat Photos</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-realme-v30t-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Realme V30T to Roku | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/decoding-gptbot-understanding-its-role-and-bans/"><u>Decoding GPTBot: Understanding Its Role and Bans</u></a></li>
<li><a href="https://common-error.techidaily.com/device-unveiled-revolutionary-speed-boost-achieved/"><u>Device Unveiled: Revolutionary Speed Boost Achieved!</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-malfunctioning-usb-inputoutput-on-modern-windows-systems/"><u>Diagnosing and Repairing Malfunctioning USB Input/Output on Modern Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-charging-windows-11-laptop-even-when-its-plugged-in-expert-tips-and-solutions/"><u>How to Fix a Non-Charging Windows 11 Laptop Even When It's Plugged In - Expert Tips & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-night-light-functionality-on-your-pc-running-windows-10-or-11/"><u>How to Restore Night Light Functionality on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-skillful-tactics-for-procuring-image-archives/"><u>In 2024, Skillful Tactics for Procuring Image Archives</u></a></li>
<li><a href="https://technical-tips.techidaily.com/instant-access-your-guide-to-direct3d-downloads/"><u>Instant Access: Your Guide to Direct3D Downloads</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/is-your-computers-security-at-risk-research-reveals-data-and-photo-vulnerabilities-with-certain-technicians/"><u>Is Your Computer's Security at Risk? Research Reveals Data and Photo Vulnerabilities with Certain Technicians</u></a></li>
<li><a href="https://tech-hub.techidaily.com/microsoft-copilot-setup-guide-for-mac-users/"><u>Microsoft Copilot Setup Guide for Mac Users</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unresponsive-function-keys-a-comprehensive-guide/"><u>Troubleshooting Unresponsive Function Keys: A Comprehensive Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

