---
title: Master the Troubleshooting of Persistent Windows 10 Update Failures
date: 2024-10-19T16:42:55.096Z
updated: 2024-10-24T20:25:41.062Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Master the Troubleshooting of Persistent Windows 10 Update Failures
excerpt: This Article Describes Master the Troubleshooting of Persistent Windows 10 Update Failures
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-expert-tips-perfecting-npc-closures-in-roblox-games/"><u>[New] 2024 Approved Expert Tips Perfecting NPC Closures in Roblox Games</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-secrets-to-professional-streams-selecting-from-the-best-9-filters/"><u>[New] Secrets to Professional Streams Selecting From the Best 9 Filters</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-a-step-by-step-guide-through-youtubes-aspect-ratio-landscapes/"><u>[Updated] In 2024, A Step-by-Step Guide Through YouTube's Aspect Ratio Landscapes</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-pixelmaster-elite-os-xwin-edition-for-2024/"><u>[Updated] PixelMaster Elite OS X/Win Edition for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-intense-moment-capture-iphone-burst-mode/"><u>2024 Approved Intense Moment Capture IPhone Burst Mode</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-nba-experience-top-15-ways-to-watch-games-online/"><u>2024 Approved The Ultimate NBA Experience - Top 15 Ways to Watch Games Online</u></a></li>
<li><a href="https://discover-bytes.techidaily.com/court-appearance-required-for-suspects-accused-of-conducting-online-child-predation-frauds-via-malwarefox-platform/"><u>Court Appearance Required for Suspects Accused of Conducting Online Child Predation Frauds via MalwareFox Platform</u></a></li>
<li><a href="https://win-manuals.techidaily.com/effortless-hard-drive-swap-for-faster-performance-clone-intel-based-hdds-as-ssds-on-windows-systems/"><u>Effortless Hard Drive Swap for Faster Performance - Clone Intel-Based HDDs as SSDs on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-windows-start-menu-back-to-normal-helpful-strategies-for-quick-repair/"><u>Getting Your Windows ˈStart Menu Back to Normal: Helpful Strategies for Quick Repair</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quickly-fix-the-0x80n0f0922-error-during-windows-10-updates/"><u>How to Quickly Fix the 0X80n0f0922 Error During Windows 10 Updates</u></a></li>
<li><a href="https://some-approaches.techidaily.com/protonvpn-introduces-new-stealth-mode-for-windows-users/"><u>ProtonVPN Introduces New Stealth Mode for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-aoc-monitor-problem-for-windows-10-expert-tips-and-fixes/"><u>Resolve Your AOC Monitor Problem for Windows 10: Expert Tips and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-why-isnt-the-cut-copy-and-paste-function-working-on-windows-11/"><u>Resolved: Why Isn't the Cut, Copy, and Paste Function Working on Windows 11?</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-strategy-to-eliminate-your-livekernelevent-117-problem/"><u>The Definitive Strategy to Eliminate Your LiveKernelEvent 117 Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-function-keys-issue-on-your-dell-pc/"><u>Ultimate Guide: Resolving the Function Keys Issue on Your Dell PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

