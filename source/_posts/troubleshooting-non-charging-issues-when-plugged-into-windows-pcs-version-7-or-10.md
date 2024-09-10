---
title: Troubleshooting Non-Charging Issues When Plugged Into Windows PCs (Version 7 or 10)
date: 2024-09-09T08:55:01.680Z
updated: 2024-09-10T08:55:01.680Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Non-Charging Issues When Plugged Into Windows PCs (Version 7 or 10)
excerpt: This Article Describes Troubleshooting Non-Charging Issues When Plugged Into Windows PCs (Version 7 or 10)
thumbnail: https://thmb.techidaily.com/1d6ebdf0f9be5148c3910502b3b0ab4551af7a691410cfb2889b0e38a1326e66.jpg
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
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135402/19272" target="_top" id="2135402">
  <img src="//a.impactradius-go.com/display-ad/19272-2135402" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135402/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
<!-- affiliate ads begin -->
<span id="1492813">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1492813.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1492813">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1492813.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1492813%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1492813/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2\. If prompted to overwrite existing files, type**All** and hit **Enter** .  
  
 3\. Type exit and hit**Enter** to close the Command Prompt window.  
  
 4\. Restart your computer.  
  
**Solution 2: Disable Automatic Startup Repair**
  
 1\. In Command Prompt, type**bcdedit** and hit**Enter** . Then you will see the result displayed. Look for**resumeobject** item and note the number next to it (In below case, the number is 7ce0dd34-d277-11e4-8263-68f7286346fb).  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff3f6500f3.jpg)
  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134239/18498" target="_top" id="2134239">
  <img src="//a.impactradius-go.com/display-ad/18498-2134239" border="0" alt="https://techidaily.com" width="721" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134239/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affee4bc504.png)
  
<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2121335/18498" target="_top" id="2121335">
  <img src="//a.impactradius-go.com/display-ad/18498-2121335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2121335/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-videos.techidaily.com/new-a-journey-to-viral-tiktok-filmora-edition-of-reaction-mastery/"><u>[New] A Journey to Viral TikTok  Filmora Edition of Reaction Mastery</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-best-5-minute-timelapse-video-maker-top-for-2024/"><u>[New] Best 5-Minute Timelapse Video Maker #Top for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/usting-the-top-10-vloggers-fears-strategies-for-success-for-2024/"><u>[New] Busting the Top 10 Vloggers' Fears  Strategies for Success for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-m1-chip-wins-smoothness-in-every-edit-every-time/"><u>[Updated] 2024 Approved  M1 Chip Wins  Smoothness in Every Edit, Every Time</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-duel-masters-switch-edition-the-best-of-ten-for-2024/"><u>[Updated] Duel Masters  Switch Edition - The Best of Ten for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-rise-and-shine-on-these-overlooked-meme-platforms-for-2024/"><u>[Updated] Rise and Shine on These Overlooked Meme Platforms for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-expand-your-creative-toolkit-incorporating-custom-fonts-into-after-effects/"><u>2024 Approved  Expand Your Creative Toolkit  Incorporating Custom Fonts Into After Effects</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-step-by-step-tutorials-to-excel-at-google-meet-free-edition/"><u>2024 Approved  Step-by-Step Tutorials to Excel at Google Meet (Free Edition)</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-to-restoring-your-lenovo-mousepad-functionality-in-windows-environments/"><u>Complete Guide to Restoring Your Lenovo Mousepad Functionality in Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolving-event-id-1000-in-windows-7810-systems/"><u>Comprehensive Guide: Resolving Event ID 1000 in Windows 7/8/10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-fixes-for-restoring-access-to-vanished-steam-file-permissions/"><u>Essential Fixes for Restoring Access to Vanished Steam File Permissions</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-non-operational-copy-and-paste-in-windows-os/"><u>Fixing Non-Operational Copy and Paste in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unresponsive-touchpad-scroll-issues-in-windows-11/"><u>Fixing Unresponsive Touchpad Scroll Issues in Windows 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/from-dull-to-dynamic-top-11-techniques-for-enhanced-hues/"><u>From Dull to Dynamic  Top 11 Techniques for Enhanced Hues</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-logitech-brio-camcorders-software-for-windows-1110/"><u>Get Your Logitech BRIO Camcorder's Software for Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-the-0x80072efd-error-in-windows-11-systems/"><u>How to Correctly Address the 0X80072EFD Error in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-svchostexe-consuming-too-much-cpu-power-in-windows-10-solution-guide/"><u>How to Fix svchost.exe Consuming Too Much CPU Power in Windows 10 - Solution Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-mirror-your-tecno-phantom-v-flip-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>How to Mirror Your Tecno Phantom V Flip Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-brightness-functionality-on-your-windows-10-display/"><u>How to Restore Brightness Functionality on Your Windows 10 Display</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-safeguard-your-browser-tackling-the-deceptive-google-chrome-critical-error-scam/"><u>How to Safeguard Your Browser: Tackling the Deceptive 'Google Chrome Critical Error' Scam</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-your-iphone-12-pro-passcode-4-easy-methods-with-or-without-itunes-drfone-by-drfone-ios/"><u>In 2024, How to Unlock Your iPhone 12 Pro Passcode 4 Easy Methods (With or Without iTunes) | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-top-7-skype-hacker-to-hack-any-skype-account-on-your-honor-magic-vs-2-drfone-by-drfone-virtual-android/"><u>In 2024, Top 7 Skype Hacker to Hack Any Skype Account On your Honor Magic Vs 2 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209807541-keyboard-problems-at-boot-up-heres-your-solution/"><u>Keyboard Problems at Boot-Up? Here's Your Solution!</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-canon-dr-c225-driver-download-instructions-for-windows-operating-systems/"><u>Latest Canon DR-C225 Driver Download Instructions for Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/nvidia-share-not-responding-solved/"><u>NVIDIA Share Not Responding [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-hdcp-restrictions-for-better-display-performance-a-complete-guide/"><u>Overcoming HDCP Restrictions for Better Display Performance: A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/program-cant-start-running/"><u>Program Can't Start Running</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208681245-resolve-win10-upgrade-stuck-on-99-proven-solutions-that-work/"><u>Resolve Win10 Upgrade Stuck on 99%%: Proven Solutions That Work!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-overcoming-issues-with-creating-directx-graphics-device-d3d/"><u>Resolved: Overcoming Issues with Creating DirectX Graphics Device (D3D)</u></a></li>
<li><a href="https://screen-recording.techidaily.com/reviving-the-full-screen-in-obs/"><u>Reviving the Full Screen in OBS</u></a></li>
<li><a href="https://extra-support.techidaily.com/samsungs-competitors-top-gear-360-alternative-cameras-of-the-year-for-2024/"><u>Samsung’s Competitors  Top Gear 360 Alternative Cameras of the Year for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-power-surge-on-hub-port/"><u>Solved: Power Surge on Hub Port</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-stuck-spacebar-problem-on-your-newly-installed-windows-11-pc/"><u>Solving the Stuck Spacebar Problem on Your Newly Installed Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-repair-brightness-control-malfunctions-on-windows-10-machines/"><u>Step-by-Step Guide to Repair Brightness Control Malfunctions on Windows 10 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-tips-for-dealing-with-twitch-error-4000/"><u>Step-by-Step Troubleshooting Tips for Dealing with Twitch Error 4000</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/step-by-step-tutorial-for-installing-blinks-outdoor-4-cameras-with-light-features/"><u>Step-by-Step Tutorial for Installing Blink's Outdoor 4 Cameras with Light Features</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-comprehensive-guide-to-best-trivia-shows/"><u>The Comprehensive Guide to Best Trivia Shows</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206019282-troubled-by-cs-go-keep-freezing-or-crashing-heres-how-to-fix-it-quickly/"><u>Troubled by CS: GO Keep Freezing or Crashing? Here's How to Fix It Quickly!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-connecting-your-airpods-to-pcs-windows-edition/"><u>Troubleshooting Steps for Connecting Your AirPods to PCs - Windows Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-your-pc-cant-close-windows-11-properly/"><u>Troubleshooting Tips for When Your PC Can't Close Windows 11 Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixing-the-non-functional-right-click-on-mouse-under-windows-10/"><u>Troubleshooting: Fixing the Non-Functional Right Click on Mouse Under Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-critical-issues-in-black-ops-4/"><u>Ultimate Guide: Resolving Critical Issues in Black Ops 4</u></a></li>
<li><a href="https://common-error.techidaily.com/untangling-the-complicated-web-of-windows-10s-0x80240034-a-step-by-step-guide-to-seamless-updates/"><u>Untangling the Complicated Web of Windows 10'S 0X80240034: A Step-by-Step Guide to Seamless Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/wacom-pen-not-responding-solutions-for-windows-10-and-windows-11-users/"><u>Wacom Pen Not Responding? Solutions for Windows 10 & Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-updates-not-installing-heres-your-comprehensive-solution-guide/"><u>Windows 10 Updates Not Installing? Here's Your Comprehensive Solution Guide</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/wireless-vs-wired-a-step-by-step-guide-to-connecting-your-laptop-to-a-printer/"><u>Wireless Vs. Wired: A Step-by-Step Guide to Connecting Your Laptop to a Printer</u></a></li>
</ul></div>
