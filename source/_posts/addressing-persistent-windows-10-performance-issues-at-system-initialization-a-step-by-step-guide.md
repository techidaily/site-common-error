---
title: Addressing Persistent Windows 10 Performance Issues at System Initialization - A Step-by-Step Guide
date: 2024-09-23T19:08:31.634Z
updated: 2024-09-26T19:16:58.806Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Addressing Persistent Windows 10 Performance Issues at System Initialization - A Step-by-Step Guide
excerpt: This Article Describes Addressing Persistent Windows 10 Performance Issues at System Initialization - A Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/c38adae2e42bb33172470753ec027ccdb4d1aafb812ed418ac2e91f37424af9f.jpg
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
<li><a href="https://fox-access.techidaily.com/updated-in-2024-top-10-gif-apps-for-iphone-x876/"><u>[Updated] In 2024, Top 10 GIF Apps for iPhone X/8/7/6</u></a></li>
<li><a href="https://common-error.techidaily.com/dragon-ball-fighterz-network-initialization-problem-solved-game-now-works-smoothly/"><u>Dragon Ball FighterZ Network Initialization Problem Solved – Game Now Works Smoothly!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/easily-unlock-your-infinix-hot-40-pro-device-sim-by-drfone-android/"><u>Easily Unlock Your Infinix Hot 40 Pro Device SIM</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-lock-your-realme-note-50-phone-in-style-the-top-5-gesture-lock-screen-apps-by-drfone-android/"><u>In 2024, Lock Your Realme Note 50 Phone in Style The Top 5 Gesture Lock Screen Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-dns-communication-breakdowns-using-these-4-strategies/"><u>Overcome DNS Communication Breakdowns Using These 4 Strategies</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-messages-from-tecno-by-fonelab-android-recover-messages/"><u>Possible solutions to restore deleted messages from Tecno</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-connectivity-issues-easily-overcome-failing-nat-type-problems-with-our-guide/"><u>PS4 Connectivity Issues? Easily Overcome Failing NAT Type Problems with Our Guide</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/the-elite-list-discover-the-top-10-photo-repair-programs-for-your-computer-system/"><u>The Elite List: Discover the Top 10 Photo Repair Programs for Your Computer System</u></a></li>
<li><a href="https://common-error.techidaily.com/uncovering-your-touchpad-steps-to-reveal/"><u>Uncovering Your Touchpad: Steps to Reveal</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-the-semaphore-timeout-period-has-expired-error-code-0x80070079/"><u>Understanding and Fixing 'The Semaphore Timeout Period Has Expired' Error Code 0X80070079</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/vyncs-link-assessment-report-sturdy-surveillance-app-with-disorientating-plan-structures/"><u>Vyncs Link Assessment Report: Sturdy Surveillance App with Disorientating Plan Structures</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

