---
title: Troubleshooting and Repairing Laptop Keyboards for Windows Users [WIN 10, 8 & 7]
date: 2024-10-19T21:26:21.814Z
updated: 2024-10-24T17:39:50.754Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Repairing Laptop Keyboards for Windows Users [WIN 10, 8 & 7]
excerpt: This Article Describes Troubleshooting and Repairing Laptop Keyboards for Windows Users [WIN 10, 8 & 7]
thumbnail: https://thmb.techidaily.com/e3894a6ad1afb8650d841abb2ecac55565ace18e9f7afc96402da4622392cb76.jpg
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
<li><a href="https://fox-http.techidaily.com/updated-in-2024-a-comprehensible-list-of-the-leading-5-online-title-innovators/"><u>[Updated] In 2024, A Comprehensible List of The Leading 5 Online Title Innovators</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/approved-affordable-methods-for-video-and-text-synergy/"><u>2024 Approved Affordable Methods for Video and Text Synergy</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-seamlessly-navigate-to-youtube-video-comments/"><u>2024 Approved Seamlessly Navigate to YouTube Video Comments</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-to-efficiently-upload-a-collection-of-photos-to-your-facebook-profile/"><u>How to Efficiently Upload a Collection of Photos to Your Facebook Profile</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-11-pc-reset-failure-solved/"><u>How to Fix: Windows 11 PC Reset Failure Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-mac-functionality-resolving-two-finger-swipe-issues/"><u>Mastering Mac Functionality - Resolving Two Finger Swipe Issues</u></a></li>
<li><a href="https://technical-tips.techidaily.com/mastering-the-fix-strategies-for-handling-missing-coredll-files/"><u>Mastering the Fix: Strategies for Handling Missing core.dll Files</u></a></li>
<li><a href="https://fox-access.techidaily.com/no-cost-upgrade-excellent-online-beat-detection-for-music-producers-for-2024/"><u>No Cost Upgrade Excellent Online Beat Detection for Music Producers for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-browser-lag-expert-guide-to-restarting-a-sluggish-chrome/"><u>Overcome Browser Lag - Expert Guide to Restarting a Sluggish Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209903253-quick-solutions-get-your-non-responsive-huion-pen-back-in-action/"><u>Quick Solutions: Get Your Non-Responsive Huion Pen Back in Action!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210989175-resolve-your-valorant-startup-hang-up-steps-to-end-infinite-loading/"><u>Resolve Your Valorant Startup Hang-Up: Steps to End Infinite Loading</u></a></li>
<li><a href="https://sound-issues.techidaily.com/silent-airpods-connected-to-your-pc-learn-to-rectify-the-problem-on-windows-1110-platforms/"><u>Silent AirPods Connected to Your PC? Learn to Rectify the Problem on Windows 11/10 Platforms</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ltimate-guide-to-refining-your-youtube-videos-after-publishing/"><u>The Ultimate Guide to Refining Your YouTube Videos After Publishing</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-tecno-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Tecno Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/your-network-settings-are-blocking-party-chat-solved/"><u>Your Network Settings Are Blocking Party Chat [SOLVED]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1977006">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977006.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977006">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977006.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977006%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977006/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

