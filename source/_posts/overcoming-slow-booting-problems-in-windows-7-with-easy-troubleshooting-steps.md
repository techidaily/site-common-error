---
title: Overcoming Slow Booting Problems in Windows 7 with Easy Troubleshooting Steps
date: 2024-08-27T13:37:05.293Z
updated: 2024-08-28T13:37:05.293Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming Slow Booting Problems in Windows 7 with Easy Troubleshooting Steps
excerpt: This Article Describes Overcoming Slow Booting Problems in Windows 7 with Easy Troubleshooting Steps
thumbnail: https://thmb.techidaily.com/cc47b698f923f727c15f0c1061cbe2a60849e3112495eb0d057b6f746e88f4ee.jpg
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
  
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef50c004c.png)
  
 6\. In Advanced Options screen, select**Command Prompt** . Then a new screen will be displayed with and open command prompt. If you are prompted to enter password, enter your Windows password.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58aff028a30cf.png)
  
 After opening the Command Prompt window, use below solutions to fix the loop error.  
  
 **Solution 1: Restore Windows Registry**
  
 Follow these steps: 1\. In Command Prompt, t ype **copy c:\\windows\\system32\\config\\RegBack\\\* c:\\windows\\system32\\config** and hit**Enter** .  
  
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/1853659/21526" target="_top" id="1853659"><img src="//a.impactradius-go.com/display-ad/21526-1853659" border="0" alt="" width="1920" height="750"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1853659/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=194977&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.blumentals.net/scrfactory/images/screensaver-software.png" border="0">Screensaver Factory, Create stunning professional screensavers within minutes. Create screensavers for yourself, for marketing or unlimited royalty-free commercial distribution. Make screensavers from images, video and swf flash, add background music and smooth sprite and transition effects. Screensaver Factory is very easy to use, and it enables you to make self-installing screensaver files and CDs for easy setup and distribution. Screensaver Factory is the most advanced software of its kind.</a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-glue.techidaily.com/new-convert-spoken-words-into-text-effortlessly-using-ms-word-for-2024/"><u>[New] Convert Spoken Words Into Text Effortlessly Using MS Word for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-valorant-stuck-on-infinite-loading-screen/"><u>[Solved] Valorant Stuck on Infinite Loading Screen</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-tutorial-quickly-convert-youtube-audio-to-mp3-on-mac/"><u>[Updated] 2024 Approved  Tutorial  Quickly Convert YouTube Audio to MP3 on Mac</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-essential-blueprint-for-inspiring-valorant-video-thumbnails/"><u>[Updated] The Essential Blueprint for Inspiring Valorant Video Thumbnails</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-cultivating-a-thriving-business-model-with-snapchat-insights/"><u>2024 Approved  Cultivating a Thriving Business Model with Snapchat Insights</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-step-by-step-io-screen-capture-tutorial/"><u>2024 Approved  Step-by-Step IO Screen Capture Tutorial</u></a></li>
<li><a href="https://android-location-track.techidaily.com/5-ways-to-track-tecno-spark-20-proplus-without-app-drfone-by-drfone-virtual-android/"><u>5 Ways to Track Tecno Spark 20 Pro+ without App | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/a-majority-of-respondents-say-global-equities-are-now-overbought-and-could-be-vulnerable-to-a-correction-in-coming-months-as-investors-begin-to-price-in-the92/"><u>A Majority of Respondents Say Global Equities Are Now Overbought and Could Be Vulnerable to a Correction in Coming Months as Investors Begin to Price in the Risk of Higher Inflation and Interest Rates.</u></a></li>
<li><a href="https://tech-haven.techidaily.com/beyond-the-screen-identifying-hidden-entities-in-cyberspace-with-the-ghost-internet-hypothesis/"><u>Beyond the Screen: Identifying Hidden Entities in Cyberspace with the Ghost Internet Hypothesis</u></a></li>
<li><a href="https://common-error.techidaily.com/cant-reach-windows-defender-smartscreen-here-are-some-possible-solutions/"><u>Can't Reach Windows Defender SmartScreen? Here Are Some Possible Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-0x80n73cf9-explained-solutions-for-your-windows-10-microsoft-store-problems/"><u>Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-persistent-latency-issues-on-a-windows-11-keyboard/"><u>Fixing Persistent Latency Issues on a Windows 11 Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-microsoft-wi-fi-dock-successful-connection-setup-on-windows-10/"><u>Fixing the Microsoft Wi-Fi Dock: Successful Connection Setup on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-vanished-desktop-shortcuts-on-windows-10-a-step-by-step-solution/"><u>Fixing Vanished Desktop Shortcuts on Windows 10: A Step-by-Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-oddworld-soulstorm-pc-game-launch-issues-complete-guide/"><u>How To Fix Oddworld Soulstorm PC Game Launch Issues - Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-a-stubborn-failed-to-update-warframe-issue/"><u>How to Resolve a Stubborn 'Failed to Update Warframe' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-a-suddenly-unresponsive-wireless-mouse-in-windows-10-or-11/"><u>How to Resolve a Suddenly Unresponsive Wireless Mouse in Windows 10 or 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-vcruntime140dll-missing-error-in-windows-applications/"><u>How To Resolve vcruntime140.dll Missing Error in Windows Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-of-right-click-on-a-windows-10-system/"><u>How to Restore Functionality of Right-Click on a Windows 10 System</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-step-by-step-lenovo-laptop-screen-recording/"><u>In 2024, Step-by-Step  Lenovo Laptop Screen Recording</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-crescendo-camera-making-music-videos-on-mobile-devices/"><u>In 2024, The Crescendo Camera  Making Music Videos on Mobile Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-your-pc-finding-and-using-the-start-button-on-windows-10/"><u>Mastering Your PC: Finding and Using the Start Button on Windows 10</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/new-in-2024-unlocking-clearer-listening-the-complete-process-of-audio-level-standardization-in-vlc/"><u>New In 2024, Unlocking Clearer Listening The Complete Process of Audio Level Standardization in VLC</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-device-not-migrated-errors-during-upgrades-to-windows-10-expert-advice-and-fixes/"><u>Overcoming 'Device Not Migrated' Errors During Upgrades to Windows 10: Expert Advice and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-security-error-messages-during-firefox-login-attempts/"><u>Overcoming Security Error Messages During Firefox Login Attempts</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-a-guide-to-correcting-icue-device-detection-failures/"><u>Overcoming the Challenge: A Guide to Correcting 'ICUE' Device Detection Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-no-audio-output-installation-issue-on-windows-10-and-11/"><u>Resolving the 'No Audio Output' Installation Issue on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-internet-explorer-not-responding-issues-a-step-by-step-guide/"><u>Solving 'Internet Explorer Not Responding' Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/the-video-studio-encyclopedia-xreviewers-edition/"><u>The Video Studio Encyclopedia  XReviewer's Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-windows-10s-lost-bluetooth-fast-solutions-inside/"><u>Troubleshoot Windows 10'S Lost Bluetooth: Fast Solutions Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-hp-laptop-usb-connectivity-fixes-and-solutions/"><u>Troubleshooting HP Laptop USB Connectivity: Fixes & Solutions!</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/updated-free-avi-video-combiner-top-10-options-to-join-avi-files-for-2024/"><u>Updated Free AVI Video Combiner Top 10 Options to Join AVI Files for 2024</u></a></li>
</ul></div>
