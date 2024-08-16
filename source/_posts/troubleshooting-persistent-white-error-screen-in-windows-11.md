---
title: Troubleshooting Persistent White Error Screen in Windows 11
date: 2024-08-15T10:59:50.268Z
updated: 2024-08-16T10:59:50.268Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Persistent White Error Screen in Windows 11
excerpt: This Article Describes Troubleshooting Persistent White Error Screen in Windows 11
thumbnail: https://thmb.techidaily.com/6bdcba73a44ac207e8fdf00ab1c5febff71a5d180b14959fd7d55488ff318cda.jpg
---

## Troubleshooting Persistent Loops in Windows 10 Automatic Repairs - Solved

<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
<!-- affiliate ads end -->
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=38729081&QTY=1&AFFILIATE=108875&CART=1"><img src="https://website-prod.cache.wpscdn.com/img/wps-writer-free-word-processor-1x.3d9c80d.png" border="0">
WPS Office Premium ( File Recovery, Photo Scanning, Convert PDF)--Yearly</a>
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://extra-approaches.techidaily.com/new-master-the-art-of-social-media-stardom-with-these-9-strategies/"><u>[New] Master the Art of Social Media Stardom with These 9 Strategies</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-elevating-your-film-utilizing-drones-effectively-for-2024/"><u>[Updated] Elevating Your Film  Utilizing Drones Effectively for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-discover-the-leading-youtube-to-webm-converter-tools/"><u>[Updated] In 2024, Discover the Leading YouTube-to-WebM Converter Tools</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-mobile-media-posting-videos-not-retweets-for-2024/"><u>[Updated] Mobile Media Posting  Videos, Not Retweets for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/0x80244022-windows-update-error-solved/"><u>0X80244022 Windows Update Error [SOLVED]</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-unraveling-whatsapps-voice-transmission-techniques/"><u>2024 Approved  Unraveling WhatsApp's Voice Transmission Techniques</u></a></li>
<li><a href="https://android-frp.techidaily.com/about-sony-xperia-1-v-frp-bypass-by-drfone-android/"><u>About Sony Xperia 1 V FRP Bypass</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-obstacle-winning-against-windows-11-error-0x800f0922-with-easy-fixes/"><u>Bypassing the Obstacle: Winning Against Windows 11 Error 0X800f0922 with Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-for-repairing-compromised-hardware-drivers-fast/"><u>Effortless Solutions for Repairing Compromised Hardware Drivers Fast</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1603-deciphered-a-step-by-step-guide-to-solving-fatal-setup-issues/"><u>Error 1603 Deciphered: A Step-by-Step Guide to Solving Fatal Setup Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-execution-issues-in-windows-media-players-server-functionality/"><u>Expert Tips for Fixing Execution Issues in Windows Media Player's Server Functionality</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/firefox-recording-tools-and-extensions-for-2024/"><u>Firefox Recording Tools & Extensions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208689449-fixing-a-laptop-that-wont-exit-the-startup-display-issue-solution-included/"><u>Fixing a Laptop That Won't Exit the Startup Display Issue - Solution Included!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-excessive-gpu-usage-in-windows-1n-a-guide-to-optimizing-the-desktop-window-manager/"><u>Fixing Excessive GPU Usage in Windows 1N: A Guide to Optimizing the Desktop Window Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-lack-of-sound-devices-message-on-windows-10-and-11-systems/"><u>Fixing Lack of Sound Devices Message on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-oculus-hardware-problems-expert-tips/"><u>Fixing Your Oculus Hardware Problems - Expert Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-lenovo-mouse-pad-working-again-on-any-version-of-windows-comprehensive-fixes/"><u>Get Your Lenovo Mouse Pad Working Again on Any Version of Windows - Comprehensive Fixes!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-samsung-galaxy-m34-screen-sharing-drfone-by-drfone-android/"><u>How To Do Samsung Galaxy M34 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-windows-10-microphone-working-again-expert-tips-and-tricks/"><u>How to Get Your Windows 10 Microphone Working Again – Expert Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-common-netflix-connectivity-problems-when-things-dont-work/"><u>How to Resolve Common Netflix Connectivity Problems When Things Don't Work</u></a></li>
<li><a href="https://screen-capture.techidaily.com/how-to-snappify-your-macs-viewport-for-2024/"><u>How To Snappify Your Mac's Viewport for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-11-free-apps-to-check-imei-on-tecno-spark-10-pro-phones-by-drfone-android/"><u>In 2024, Top 11 Free Apps to Check IMEI on Tecno Spark 10 Pro Phones</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-repair-of-oculus-gear-expert-solutions-for-common-hardware-glitches/"><u>Mastering Repair of Oculus Gear: Expert Solutions for Common Hardware Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/obs-game-streaming-flawlessness-solving-the-elusive-black-screen-hurdle/"><u>OBS Game Streaming Flawlessness: Solving the Elusive Black Screen Hurdle</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-windows-could-not-install-in-minutes-with-these-tips/"><u>Resolve 'Windows Could Not Install' In Minutes with These Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-of-inactive-number-keys-on-your-computer-keypad/"><u>Resolving the Issue of Inactive Number Keys on Your Computer Keypad</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11-login-issues-steps-to-repair-user-profile-service-failures/"><u>Resolving Windows 11 Login Issues: Steps to Repair User Profile Service Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-disappeared-desktop-icon-issues-in-windows-10-made-easy/"><u>Restoring Disappeared Desktop Icon Issues in Windows 10 Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/secure-guide-acquiring-permissions-from-trustedinstaller-for-file-modification-tasks/"><u>Secure Guide: Acquiring Permissions From TrustedInstaller for File Modification Tasks</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-streaming-woes-permanent-fix-for-kodi-stutter-and-buffering/"><u>Solve Your Streaming Woes: Permanent Fix for Kodi Stutter & Buffering</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-repair-for-semaphore-timeout-period-has-expired-error/"><u>Step-by-Step Repair for 'Semaphore Timeout Period Has Expired' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-the-windows-ebx-11-copy-p-paste-problem/"><u>Step-by-Step Solutions for the Windows Ebx 11 Copy-P Paste Problem</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/taking-console-crown-to-new-heights-an-experts-take-on-the-xbox-one-x-performance/"><u>Taking Console Crown to New Heights: An Expert's Take on the Xbox One X Performance</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/the-ultimate-guide-to-get-the-rare-candy-on-pokemon-go-fire-red-on-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>The Ultimate Guide to Get the Rare Candy on Pokemon Go Fire Red On Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-overcome-your-game-installation-woes-with-quick-tips-to-solve-steam-errors/"><u>Troubleshoot & Overcome Your Game Installation Woes with Quick Tips to Solve Steam Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-corrective-measures-for-windows-file-repair-service-sfc-malfunction/"><u>Troubleshooting Guide: Corrective Measures for Windows File Repair Service (SFC) Malfunction</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-success-quick-solution-for-error-1053-when-service-fails-to-react-timely/"><u>Troubleshooting Success: Quick Solution for Error 1053 When Service Fails to React Timely</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/unmatched-virtual-speedway-showdowns-top-5-list/"><u>Unmatched Virtual Speedway Showdowns  Top 5 List</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-do-when-laptopdesktop-wont-turn-on-essential-fixes/"><u>What to Do When Laptop/Desktop Won't Turn On - Essential Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-reboots-without-warning/"><u>Windows Reboots without Warning</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-strategies-to-overcome-continuous-windows-10-startup-issues/"><u>Winning Strategies to Overcome Continuous Windows 10 Startup Issues</u></a></li>
</ul></div>
