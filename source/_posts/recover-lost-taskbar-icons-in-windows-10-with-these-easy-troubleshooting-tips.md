---
title: Recover Lost Taskbar Icons in Windows 10 with These Easy Troubleshooting Tips!
date: 2024-09-04T20:22:00.065Z
updated: 2024-09-05T20:22:00.065Z
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
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-video-flexibility-unleashed-5-powerful-online-methods-to-edit-videos-on-vimeo/"><u>[New] In 2024, Video Flexibility Unleashed  5 Powerful Online Methods to Edit Videos on Vimeo</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-the-search-for-master-video-artists/"><u>[New] Navigating the Search for Master Video Artists</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-gamers-galaxy-100plus-spaces-of-play-for-2024/"><u>[Updated] Gamer's Galaxy  100+ Spaces of Play for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-hue-harmonization-handbook-for-experts/"><u>2024 Approved  Hue Harmonization Handbook for Experts</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-master-the-art-of-marketing-with-these-top-phrases/"><u>2024 Approved  Master the Art of Marketing with These Top Phrases</u></a></li>
<li><a href="https://tech-haven.techidaily.com/delving-into-ais-role-in-crafting-prompts-and-job-market-adaptability/"><u>Delving Into AI's Role in Crafting Prompts & Job Market Adaptability</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-non-functional-fn-buttons-on-an-asus-notebook/"><u>Diagnosing and Repairing Non-Functional Fn Buttons on an ASUS Notebook</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/enhancing-content-reach-keeping-creative-commons-engagement-high/"><u>Enhancing Content Reach  Keeping Creative Commons Engagement High</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-modifying-windows-settings-under-corporate-governance/"><u>Expert Guide: Modifying Windows Settings Under Corporate Governance</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210270675-fixing-kodi-malfunctions-effective-tips-and-tricks-unveiled/"><u>Fixing Kodi Malfunctions: Effective Tips & Tricks Unveiled!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-phantom-cursor-on-windows-11-a-step-by-step-solution-for-users/"><u>Fixing the Phantom Cursor on Windows 11: A Step-by-Step Solution for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204948165-fortnite-troubleshooting-launch-success/"><u>Fortnite Troubleshooting: Launch Success!</u></a></li>
<li><a href="https://common-error.techidaily.com/hosted-network-troubleshooting-successfully-resolved-for-windows-11-users/"><u>Hosted Network Troubleshooting Successfully Resolved for Windows 11 Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/how-to-download-and-convert-youtube-twittersongs-videos-to-mp3-for-2024/"><u>How to Download and Convert YouTube Twittersongs (Videos) to MP3 for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-unresponsive-numeric-keys-on-a-computer-keyboard/"><u>How to Repair Unresponsive Numeric Keys on a Computer Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-your-computers-inability-to-initialize-properly/"><u>How to Resolve Your Computer's Inability to Initialize Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/icue-fixes-at-hand-tackling-the-device-not-detected-problem-easily/"><u>ICUE Fixes at Hand: Tackling the 'Device Not Detected' Problem Easily</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-sign-out-of-apple-id-from-iphone-6-plus-without-password-by-drfone-ios/"><u>In 2024, How to Sign Out of Apple ID From iPhone 6 Plus without Password?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-xr-apples-new-iphone-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone XR, Apples New iPhone</u></a></li>
<li><a href="https://fake-location.techidaily.com/looking-for-a-location-changer-on-honor-x50iplus-look-no-further-drfone-by-drfone-virtual-android/"><u>Looking For A Location Changer On Honor X50i+? Look No Further | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-startup-struggles-break-free-from-constant-restarts-in-windows-1110/"><u>Overcome Startup Struggles: Break Free From Constant Restarts in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-connectivity-hurdles-a-thorough-guide-to-diagnosing-and-fixing-nat-types/"><u>PS4 Connectivity Hurdles? A Thorough Guide to Diagnosing & Fixing NAT Types</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204042973-quick-fixes-for-defective-usb-connections-expert-tips/"><u>Quick Fixes for Defective USB Connections - Expert Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-unable-to-reach-file-location-in-windows-error-quickly/"><u>Resolving 'Unable to Reach File Location in Windows' Error Quickly</u></a></li>
<li><a href="https://extra-support.techidaily.com/reviewing-the-pinnacle-of-tv-tech-lg-27ud88-uhd-oled-hdtv-for-2024/"><u>Reviewing the Pinnacle of TV Tech - LG 27UD88-UHD OLED HDTV for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-typing-experience-a-step-by-step-guide-to-restarting-your-keyboard/"><u>Revive Your Typing Experience: A Step-by-Step Guide to Restarting Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-stuck-keys-on-your-windows-pc-comprehensive-fixes-inside/"><u>Reviving Stuck Keys on Your Windows PC - Comprehensive Fixes Inside</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/seamless-operation-windows-plus-nvidia-card/"><u>Seamless Operation: Windows + Nvidia Card</u></a></li>
<li><a href="https://extra-resources.techidaily.com/shoot-in-slow-motion-essential-gopro-hero-10-techniques/"><u>Shoot in Slow Motion  Essential GoPro Hero 10 Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-enabling-and-starting-your-hosted-network-on-windows-10-successfully/"><u>Solution Guide: Enabling and Starting Your Hosted Network on Windows 10 Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-ps4-mic-problems-the-best-methods-explored/"><u>Solving PS4 Mic Problems: The Best Methods Explored</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-clearing-and-solving-errcachemiss-errors-in-chrome/"><u>Step-by-Step Guide: Clearing and Solving ERR_CACHE_MISS Errors in Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-repair-tips-correcting-windows-1110-error-code-0x80ebase-f/"><u>Step-by-Step Repair Tips: Correcting Windows 11/10 Error Code 0X80ebase F</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-restore-functionality-of-your-left-click-mouse/"><u>Step-by-Step Solutions to Restore Functionality of Your Left Click Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/the-role-of-msda80dll-in-your-pcs-functionality-keep-or-remove/"><u>The Role of MSDA80.DLL in Your PC's Functionality - Keep or Remove?</u></a></li>
<li><a href="https://win-blog.techidaily.com/troubleshooting-resolving-the-vanguard-missing-error-in-valorant-gameplay/"><u>Troubleshooting: Resolving the Vanguard Missing Error in Valorant Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-making-your-lenovo-mouse-pad-work-again-on-pcs-with-windows-1187-operating-systems/"><u>Ultimate Guide: Making Your Lenovo Mouse Pad Work Again on PCs with Windows 11/8/7 Operating Systems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1374820">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1374820.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1374820">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1374820.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1374820%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1374820/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->