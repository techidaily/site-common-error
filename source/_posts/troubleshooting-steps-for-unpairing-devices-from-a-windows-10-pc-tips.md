---
title: Troubleshooting Steps for Unpairing Devices From a Windows 10 PC (Tips )
date: 2024-12-14T00:07:59.043Z
updated: 2024-12-16T18:02:12.161Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Unpairing Devices From a Windows 10 PC (Tips )
excerpt: This Article Describes Troubleshooting Steps for Unpairing Devices From a Windows 10 PC (Tips )
thumbnail: https://thmb.techidaily.com/5d3200ea7acc8a267e33f7e3f6be29344352dcba610c7cb281d20c740b294fae.jpg
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
<li><a href="https://tiktok-video-files.techidaily.com/new-in-2024-savory-selections-international-foodie-frenzy-on-tiktok/"><u>[New] In 2024, Savory Selections International Foodie Frenzy on TikTok</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-in-2024-perfect-the-art-of-posting-on-snapchat-15-tips/"><u>[Updated] In 2024, Perfect the Art of Posting on Snapchat (15 Tips)</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-breaking-the-screens-top-10-most-popular-female-youtubers/"><u>2024 Approved Breaking the Screens Top 10 Most Popular Female YouTubers</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-solving-sims-grope-wont-open-error-on-pcmac/"><u>Diagnosing and Solving Sims Grope Won't Open Error on PC/Mac</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-official-method-to-unlock-your-iphone-14-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 14 Official Method to Unlock Your iPhone 14</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-radio-dramas-peak-of-creative-scripting/"><u>In 2024, Radio Dramas Peak of Creative Scripting</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-unlock-iphone-14-pro-without-passcode-easily-by-drfone-ios/"><u>In 2024, Unlock iPhone 14 Pro Without Passcode Easily</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-audio-file-conversion-transforming-flac-into-m4a-with-ease-on-your-pc-and-online-platforms/"><u>Mastering Audio File Conversion: Transforming FLAC Into M4A with Ease on Your PC & Online Platforms</u></a></li>
<li><a href="https://review-topics.techidaily.com/remove-frp-lock-on-v27-pro-by-drfone-android-unlock-remove-google-frp/"><u>Remove FRP Lock on V27 Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-approach-to-overcome-windows-11-kb4056892-installation-challenges/"><u>Step-by-Step Approach to Overcome Windows 11 KB4056892 Installation Challenges</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-updating-fixing-the-windows-11-v1n607-deployment-hitches/"><u>Trouble Updating? Fixing the Windows 11 V1n607 Deployment Hitches</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-ps4-console-noise-issues-causes-and-solutions/"><u>Troubleshooting PS4 Console Noise Issues: Causes and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205158907-unraveling-the-mystery-behind-google-chrome-critical-error-solutions-at-hand/"><u>Unraveling The Mystery Behind Google Chrome Critical Error - Solutions at Hand</u></a></li>
<li><a href="https://common-error.techidaily.com/why-does-my-wireless-mouse-stop-working-on-windows-troubleshooting-tips-for-win10win11-users/"><u>Why Does My Wireless Mouse Stop Working on Windows? Troubleshooting Tips for Win10/Win11 Users</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

