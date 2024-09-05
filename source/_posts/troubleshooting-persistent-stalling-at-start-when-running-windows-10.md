---
title: Troubleshooting Persistent Stalling at Start When Running Windows 10
date: 2024-09-04T20:22:01.860Z
updated: 2024-09-05T20:22:01.860Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Persistent Stalling at Start When Running Windows 10
excerpt: This Article Describes Troubleshooting Persistent Stalling at Start When Running Windows 10
thumbnail: https://thmb.techidaily.com/9929e26ad232462fb3012e528ec110b36cc8e34a7ab835cf659d05f21b4127d5.jpg
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
<li><a href="https://common-error.techidaily.com/fixed-high-cpu-usage-by-wudfhostexe-in-windows-11/"><u>[FIXED] High CPU Usage by WUDFHost.exe in Windows 11</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-sleek-arenas-2022s-olympic-skating/"><u>[New] Sleek Arenas  2022'S Olympic Skating</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-tutorial-guide-to-fade-out-music-in-premiere-pro/"><u>[New] Tutorial Guide To Fade Out Music In Premiere Pro</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-harnessing-hobbies-for-hefty-helpings-on-digital-domains/"><u>[Updated] Harnessing Hobbies for Hefty Helpings on Digital Domains</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-seizing-photographic-segments-from-videos-in-windows-11/"><u>2024 Approved  Seizing Photographic Segments From Videos in Windows 11</u></a></li>
<li><a href="https://discover-advanced.techidaily.com/abbyy-launches-advanced-ai-driven-automation-hub-in-lithuania-a-leap-towards-smart-process-transformation/"><u>Abbyy Launches Advanced AI-Driven Automation Hub in Lithuania: A Leap Towards Smart Process Transformation</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-to-repairing-windows-10-0x80072efd-error-easy-fixes-inside/"><u>Complete Guide to Repairing Windows 10 '0X80072EFD' Error - Easy Fixes Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-solution-for-fixing-the-0x80072efd-problem-on-windows-11-systems/"><u>Complete Solution for Fixing the '0X80072EFD' Problem on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-methods-to-rectify-loading-errors-on-the-steam-platform/"><u>Effective Methods to Rectify Loading Errors on the Steam Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-print-to-pdf-not-working-on-windows-11-devices/"><u>Effective Solutions for 'Print to PDF Not Working' On Windows 11 Devices</u></a></li>
<li><a href="https://extra-resources.techidaily.com/expert-iphoneandroid-blur-application-guide/"><u>Expert iPhone/Android Blur Application Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-on-rejuvenating-your-keyboard-settings-with-a-full-reboot/"><u>Expert Tips on Rejuvenating Your Keyboard Settings with a Full Reboot</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-removing-restrictions-and-dealing-with-403-headers-effectively/"><u>Expert Tips: Removing Restrictions and Dealing with 403 Headers Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-the-best-out-of-your-touchscreen-essential-tips-for-windows-10-users/"><u>Getting the Best Out of Your Touchscreen: Essential Tips for Windows 10 Users</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-repair-corrupt-mp4-and-mov-files-of-infinix-note-30-using-video-repair-utility-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>How to Repair corrupt MP4 and MOV files of Infinix Note 30 using Video Repair Utility on Windows? </u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-eternal-waiting-on-skyrims-start-up-screen-tutorial/"><u>How to Resolve Eternal Waiting on Skyrim's Start-Up Screen Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-speed-up-your-pcs-shutdown-process-in-windows-10/"><u>How to Speed Up Your PC's Shutdown Process in Windows 10</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-why-is-ipogo-not-working-on-oppo-a56s-5g-fixed-drfone-by-drfone-virtual-android/"><u>In 2024, Why is iPogo not working On Oppo A56s 5G? Fixed | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-keypad-not-working-in-windows-1087-solved/"><u>Laptop Keypad Not Working in Windows 10/8/7 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210515115-lenovo-fingerprint-recognition-problems-heres-how-you-can-repair-it-easily/"><u>Lenovo Fingerprint Recognition Problems? Here's How You Can Repair It Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/navigate-through-bluetooth-hurdles-a-comprehensive-fix-for-windows-11-users/"><u>Navigate Through Bluetooth Hurdles: A Comprehensive Fix for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-unavailable-desktop-error-in-systemprofile-folder-on-windows/"><u>Overcoming the Unavailable Desktop Error in SystemProfile Folder on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-for-windows-11-crashes/"><u>Quick Fix for Windows 11 Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-fixing-program-malfunction-a-complete-guide/"><u>Resolved Issue: Fixing Program Malfunction - A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-compatibility-problems-making-your-bluetooth-mouse-work-on-a-windows-pc-again/"><u>Resolving Compatibility Problems: Making Your Bluetooth Mouse Work on a Windows PC Again</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-steam-marketplace-connection-issues-a-step-by-step-guide/"><u>Solving Your Steam Marketplace Connection Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-overcoming-error-0x8024c01c-during-windows-system-updates/"><u>Step-by-Step Solution for Overcoming Error 0X802^4C01C During Windows System Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-unresponsive-usb-slots-on-an-hp-laptop-computer/"><u>Step-by-Step Solutions for Unresponsive USB Slots on an HP Laptop Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-tips-for-common-oculus-tech-issues/"><u>Step-by-Step Troubleshooting Tips for Common Oculus Tech Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-waiting-start-typing-smoothly-solve-keyboard-lag-in-windows-10/"><u>Stop Waiting, Start Typing Smoothly - Solve Keyboard Lag in Windows 10!</u></a></li>
<li><a href="https://win-amazing.techidaily.com/the-ultimate-guide-to-downloading-and-refreshing-your-asus-bluetooth-drivers/"><u>The Ultimate Guide to Downloading and Refreshing Your ASUS Bluetooth Drivers</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/top-review-of-mophies-ac-powerstation-balancing-convenience-against-expense/"><u>Top Review of Mophie's AC Powerstation: Balancing Convenience Against Expense</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-non-registered-classes-in-windows-10-systems/"><u>Troubleshooting and Solving Non-Registered Classes in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-audio-issues-resolving-crackling-sound-on-pcs-with-windows-11-or-7/"><u>Troubleshooting Audio Issues: Resolving Crackling Sound on PCs with Windows 11 or 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-total-war-rome-remastered-stability-issues-solution-found/"><u>Troubleshooting Guide for Total War Rome Remastered Stability Issues - SOLUTION FOUND!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-lenovo-mouse-pad-solutions-for-windows-10-8-and-7/"><u>Troubleshooting Your Lenovo Mouse Pad: Solutions for Windows 10, 8, and 7</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-corporate-control-over-windows-settings-a-comprehensive-guide-to-organizational-management/"><u>Unraveling Corporate Control Over Windows Settings – A Comprehensive Guide to Organizational Management</u></a></li>
<li><a href="https://common-error.techidaily.com/unstuck-your-windows-update-overcoming-the-stubborn-100-issue-resolved/"><u>Unstuck Your Windows Update! Overcoming the Stubborn 100%% Issue (Resolved)</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-samsung-galaxy-s23-fe-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Samsung Galaxy S23 FE? Here is How | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/352555/5172" target="_top" id="352555">
  <img src="//a.impactradius-go.com/display-ad/5172-352555" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/352555/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->