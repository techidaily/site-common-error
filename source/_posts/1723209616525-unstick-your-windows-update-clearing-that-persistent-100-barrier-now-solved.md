---
title: "Unstick Your Windows Update: Clearing that Persistent 100%% Barrier – Now Solved"
date: 2024-09-10T16:11:39.025Z
updated: 2024-09-15T16:08:39.276Z
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
<li><a href="https://instagram-videos.techidaily.com/new-desktop-and-mobile-solutions-how-to-rotate-videos-for-instagram/"><u>[New] [Desktop & Mobile Solutions] How to Rotate Videos for Instagram?</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-2024-approved-comparative-assessment-youtube-vs-dailymention/"><u>[Updated] 2024 Approved Comparative Assessment YouTube Vs. DailyMention</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-strategies-to-restore-functionality-of-mic-on-playstation-4-console/"><u>Expert Strategies to Restore Functionality of Mic on PlayStation 4 Console</u></a></li>
<li><a href="https://win-answers.techidaily.com/expert-tips-addressing-game-crash-problems-in-persona-3-portable-edition-for-pc-users/"><u>Expert Tips: Addressing Game Crash Problems in Persona 3: Portable Edition for PC Users</u></a></li>
<li><a href="https://tech-haven.techidaily.com/fivefold-transformation-ais-influence-on-cybercriminal-techniques/"><u>Fivefold Transformation: AI's Influence on Cybercriminal Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-sims-4-opening-errors-quick-and-effective-solutions/"><u>Fixes for Sims 4 Opening Errors - Quick and Effective Solutions</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-total-war-warhammer-ii-stability-problems-solutions-and-tips/"><u>Fixing Total War: Warhammer II Stability Problems - Solutions & Tips</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-three-ways-to-sim-unlock-poco-m6-pro-4g-by-drfone-android/"><u>In 2024, Three Ways to Sim Unlock Poco M6 Pro 4G</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-print-screen-failure-in-windows-10-and-windows-11-operating-systems/"><u>Resolving Print Screen Failure in Windows 10 and Windows 11 Operating Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-virtual-vanguard-of-humor-your-blueprint-for-metaspace-meme-creation-for-2024/"><u>The Virtual Vanguard of Humor – Your Blueprint for Metaspace Meme Creation for 2024</u></a></li>
<li><a href="https://tech-hub.techidaily.com/1721856656913-unlock-your-access-to-openais-latest-specialized-gpt-shopping-experience-right-away/"><u>Unlock Your Access to OpenAI's Latest Specialized GPT Shopping Experience Right Away</u></a></li>
<li><a href="https://extra-hints.techidaily.com/which-player-enhances-media-experience-more-vlc-vs-mx/"><u>Which Player Enhances Media Experience More? VLC Vs. MX</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123465/16836" target="_top" id="2123465">
  <img src="//a.impactradius-go.com/display-ad/16836-2123465" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123465/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
