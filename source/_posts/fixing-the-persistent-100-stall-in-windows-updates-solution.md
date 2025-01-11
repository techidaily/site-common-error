---
title: Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION
date: 2025-01-07T21:37:08.343Z
updated: 2025-01-10T21:25:32.356Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION
excerpt: This Article Describes Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION
thumbnail: https://thmb.techidaily.com/7ba25f196f1fd36b2bff5ba5871f3da3d2f6d119166da5162e1c6bea9b39b80e.jpg
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
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-breaking-barriers-with-iphone-x-fixing-facial-detection/"><u>[Updated] In 2024, Breaking Barriers with iPhone X Fixing Facial Detection</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-movavi-pro-review-the-next-level-of-video-editing/"><u>[Updated] Movavi Pro Review The Next Level of Video Editing</u></a></li>
<li><a href="https://solve-latest.techidaily.com/cookiebot-enabled-boost-your-websites-performance-and-user-experience/"><u>Cookiebot-Enabled: Boost Your Website's Performance & User Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/defeat-the-0x800705b4-error-in-your-windows-11-update-process-with-these-proven-strategies/"><u>Defeat the 0X800705B4 Error in Your Windows 11 Update Process with These Proven Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-troubleshooting-overcoming-the-initialization-hurdle/"><u>Destiny 2 Troubleshooting: Overcoming the 'Initialization' Hurdle</u></a></li>
<li><a href="https://fox-pages.techidaily.com/easy-tutorial-how-to-sync-and-reflect-your-android-with-a-different-android-smartphone/"><u>Easy Tutorial: How To Sync and Reflect Your Android with a Different Android Smartphone</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/exciting-vr-technologies-shaping-gaming-for-2024/"><u>Exciting VR Technologies Shaping Gaming for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-malfunctioning-mic-troubleshooting-microphone-issues-in-windows-11/"><u>Fixing a Malfunctioning Mic: Troubleshooting Microphone Issues in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-kodi-malfunctions-effective-tips-and-tricks-unveiled/"><u>Fixing Kodi Malfunctions: Effective Tips & Tricks Unveiled</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fixing-persistent-load-times-solutions-for-minecraft-lag-problems/"><u>Fixing Persistent Load Times: Solutions for Minecraft Lag Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unwritable-0x-memory-references-a-step-by-nstep-guide/"><u>Fixing Unwritable 0X Memory References: A Step-by-nStep Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/halo-4-ue4-2024-edition-resolving-the-persistent-critical-error-and-eliminating-system-crashes/"><u>Halo 4 UE4 2024 Edition: Resolving the Persistent Critical Error and Eliminating System Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-the-dx11-feature-level-100-flaw-in-wwe-2k-battlegrounds/"><u>How To Repair The 'DX11 Feature Level 10.0' Flaw in WWE 2K Battlegrounds</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-fast-snap-restoration-guide/"><u>In 2024, Fast Snap Restoration Guide</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-full-guide-to-unlock-your-google-by-drfone-android/"><u>In 2024, Full Guide to Unlock Your Google</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Nokia C32? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-resource-identification-challenges-within-overwatch-gameplay/"><u>Overcoming Resource Identification Challenges Within Overwatch Gameplay</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/pixel-personality-through-tunes-and-sounds-for-2024/"><u>Pixel Personality Through Tunes and Sounds for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/revived-stalled-discord-audio/"><u>Revived Stalled Discord Audio</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

