---
title: Fixes for Persistent Reboot Loop in Windows 11 & 10 Systems
date: 2025-01-23T17:21:49.624Z
updated: 2025-01-30T08:40:59.925Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixes for Persistent Reboot Loop in Windows 11 & 10 Systems
excerpt: This Article Describes Fixes for Persistent Reboot Loop in Windows 11 & 10 Systems
thumbnail: https://thmb.techidaily.com/88b9d1a1839e87bc852a7b88397e12987972348fa38a161adde19f109b06aa2c.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-building-your-way-to-greatness-a-complete-guide-to-valorant-video-thumbnails/"><u>[New] In 2024, Building Your Way to Greatness A Complete Guide to Valorant Video Thumbnails</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-powerful-language-in-marketing-the-20-must-know-phrases-for-2024/"><u>[Updated] Powerful Language in Marketing - The 20 Must-Know Phrases for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-xiaomi-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Xiaomi support AVCHD video?</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-overcoming-minecraft-wont-open-in-windows-problems/"><u>Expert Advice for Overcoming 'Minecraft Won't Open in Windows' Problems</u></a></li>
<li><a href="https://driver-error.techidaily.com/integrated-camera-solution-fixed-asus-on-windows-10-platform/"><u>Integrated Camera Solution: Fixed ASUS on Windows 10 Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-fixing-critical-installation-failure-error-code-1603/"><u>Solved: Fixing Critical Installation Failure (Error Code 1603)</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-printer-problems-why-you-cant-print-without-the-right-driver/"><u>Solving Printer Problems: Why You Can't Print Without the Right Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-a-broken-dvd-or-cd-reader-on-windows-computers/"><u>Step-by-Step Guide to Fix a Broken DVD or CD Reader on Windows Computers</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-editors-insight-to-seamless-lut-integration-in-premiere-for-2024/"><u>The Editor's Insight to Seamless LUT Integration in Premiere for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/time-travel-through-tech-pinpointing-the-initial-discovery-of-artificial-intelligence/"><u>Time Travel Through Tech: Pinpointing the Initial Discovery of Artificial Intelligence</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/top-rated-non-sony-non-bose-soundbar-wows-with-unmatched-audio-experience-zdnet-insights/"><u>Top-Rated Non-Sony, Non-Bose Soundbar Wows With Unmatched Audio Experience | ZDNet Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-touchpad-solutions-for-nonfunctional-scroll-buttons/"><u>Troubleshooting Windows 11 Touchpad: Solutions for Nonfunctional Scroll Buttons</u></a></li>
<li><a href="https://win-able.techidaily.com/unlock-the-solution-tips-and-tricks-to-prevent-discord-from-crashing-down/"><u>Unlock the Solution: Tips and Tricks to Prevent Discord From Crashing Down</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209826247-windows-11-hangs-and-cant-turn-off-here-are-five-effective-solutions/"><u>Windows 11 Hangs and Can't Turn Off? Here Are Five Effective Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qv4Qm7kpeMs?si=9fv5SOS5a2DvixTK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

