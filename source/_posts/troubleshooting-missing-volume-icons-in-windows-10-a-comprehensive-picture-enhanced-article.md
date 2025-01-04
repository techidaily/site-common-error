---
title: Troubleshooting Missing Volume Icons in Windows 10 - A Comprehensive Picture-Enhanced Article
date: 2024-12-31T23:06:50.535Z
updated: 2025-01-03T17:41:43.093Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Missing Volume Icons in Windows 10 - A Comprehensive Picture-Enhanced Article
excerpt: This Article Describes Troubleshooting Missing Volume Icons in Windows 10 - A Comprehensive Picture-Enhanced Article
thumbnail: https://thmb.techidaily.com/2c72878e4c5b851b7d621c520b7075b9d80e911d0e1db9a60b0603055e403b62.jpg
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-tips-from-pros-elevating-your-twitch-video-quality/"><u>[New] 2024 Approved Tips From Pros Elevating Your Twitch Video Quality</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-masterful-monitoring-with-the-latest-asus-proart-4k-display/"><u>[Updated] 2024 Approved Masterful Monitoring with the Latest ASUS ProArt 4K Display</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-sound-first-screen-second-podcasts-vs-youtube-analysis/"><u>[Updated] Sound First, Screen Second – Podcasts Vs YouTube Analysis</u></a></li>
<li><a href="https://common-error.techidaily.com/eradicating-input-lag-for-a-smoother-experience-with-windows-11-computers/"><u>Eradicating Input Lag for a Smoother Experience with Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-solutions-for-fixing-werfaultexe-errors-in-windows/"><u>Essential Solutions for Fixing werfault.exe Errors in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-miracast-streaming-despite-errors-a-step-by-step-guide/"><u>How to Enable Miracast Streaming Despite Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-error-0x8024401c-during-updates-on-windows-11/"><u>How To Overcome The Error 0X8024401C During Updates On Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-share-location-in-messenger-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Share Location in Messenger On Apple iPhone XS? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/revamp-mail-calendar-on-windows-using-chosen-images/"><u>Revamp Mail, Calendar on Windows Using Chosen Images</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-airpods-connection-issues-on-windows-1011-top-tips-for-2-cufflinks/"><u>Solving the AirPods Connection Issues on Windows 10/11: Top Tips for 2 Cufflinks</u></a></li>
<li><a href="https://win11-tips.techidaily.com/step-by-step-tutorial-for-turning-on-windows-11s-quick-start/"><u>Step-by-Step Tutorial for Turning On Windows 11'S Quick Start</u></a></li>
<li><a href="https://common-error.techidaily.com/touchpad-lag-or-no-response-heres-how-you-can-resolve-it/"><u>Touchpad Lag or No Response? Here's How You Can Resolve It</u></a></li>
<li><a href="https://techtrends.techidaily.com/trasformare-i-video-ogg-in-ogv-gratuitamente-tramite-movavi-guida-passo-passo/"><u>Trasformare I Video OGG in OGV Gratuitamente Tramite Movavi - Guida Passo-Passo</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/video-editor-selection-guide-understanding-filmora-and-democracy-creator/"><u>Video Editor Selection Guide Understanding Filmora and Democracy Creator</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

