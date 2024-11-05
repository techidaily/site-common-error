---
title: Recover Lost Taskbar Icons in Windows 10 with These Easy Troubleshooting Tips!
date: 2024-11-02T10:42:17.027Z
updated: 2024-11-04T22:48:18.064Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Recover Lost Taskbar Icons in Windows 10 with These Easy Troubleshooting Tips!
excerpt: This Article Describes Recover Lost Taskbar Icons in Windows 10 with These Easy Troubleshooting Tips!
thumbnail: https://thmb.techidaily.com/a5bbe71d28db5297dd251335f2aaa3c6aeec5c7c669607905f5ab705b440efbb.jpg
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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-unleash-your-creativity-effective-techniques-for-crafting-podcast-scripts/"><u>[New] 2024 Approved Unleash Your Creativity Effective Techniques for Crafting Podcast Scripts</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-building-a-successful-facebook-charity-competition/"><u>[Updated] Building a Successful Facebook Charity Competition</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-screenscape-innovations-an-unbiased-look-at-apeaksoft-2023-edition-for-2024/"><u>[Updated] Screenscape Innovations An Unbiased Look at Apeaksoft, 2023 Edition for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-step-by-step-guide-to-high-quality-zoom-recordings-for-podcasters/"><u>[Updated] Step-by-Step Guide to High-Quality Zoom Recordings for Podcasters</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-sxs-side-by-side-configurations-resolving-compatibility-issues-in-windows-11/"><u>Correcting SxS (Side-by-Side) Configurations: Resolving Compatibility Issues in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/cr2-beelten-in-jpeg-format-wiskundig-met-movavi-gratis-online/"><u>CR2-Beelten in JPEG Format Wiskundig Met Movavi, Gratis Online</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-inoperative-usb-slots-on-windows-11-pcs/"><u>Effective Solutions for Inoperative USB Slots on Windows 11 PCs</u></a></li>
<li><a href="https://article-tips.techidaily.com/excellence-on-screen-the-top-15-in-stop-motion-cinema-for-2024/"><u>Excellence on Screen The Top 15 in Stop Motion Cinema for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-application-startup-problems-a-guide-for-built-in-admin-accounts/"><u>Fixing Application Startup Problems: A Guide for Built-In Admin Accounts</u></a></li>
<li><a href="https://tech-revival.techidaily.com/hackers-motives-exploiting-chatgpt-technology/"><u>Hackers’ Motives: Exploiting ChatGPT Technology</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-realme-c53-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Realme C53 | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/premier-at-home-weather-sensors-a-comparative-guide-to-the-best-of-2-groceries/"><u>Premier At-Home Weather Sensors: A Comparative Guide to the Best of 2 Groceries</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/real-world-impact-of-instagram-reels-10-things-you-should-know-for-2024/"><u>Real-World Impact of Instagram Reels (10 Things You Should Know) for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-non-appearance-of-wi-fi-settings-on-windows-11-devices/"><u>Resolving the Non-Appearance of Wi-Fi Settings on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-brightness-control-problem-for-a-perfect-display-setup/"><u>Resolving the Windows 11 Brightness Control Problem for a Perfect Display Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201594479-shockwave-flash-issues-in-google-chrome-follow-our-updated-solution-guide/"><u>Shockwave Flash Issues in Google Chrome? Follow Our Updated Solution Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-update-error-code-0x80240034-on-windows-10-devices/"><u>Step-by-Step Solution to Overcome 'Update Error' Code 0X80240034 on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-tackling-and-overcoming-delayed-shutdowns-in-windows-10/"><u>The Ultimate Fix: Tackling and Overcoming Delayed Shutdowns in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-triumph-how-to-successfully-address-the-red-error-message/"><u>Troubleshooting Triumph: How to Successfully Address the Red Error Message</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886003/19272" target="_top" id="1886003">
  <img src="//a.impactradius-go.com/display-ad/19272-1886003" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886003/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

