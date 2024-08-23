---
title: Troubleshooting Steps for Unpairing Devices From a Windows 10 PC (Tips )
date: 2024-08-22T19:17:56.253Z
updated: 2024-08-23T19:17:56.253Z
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-comparing-vsdc-to-best-screen-recording-software/"><u>[New] 2024 Approved  Comparing VSDC to Best Screen Recording Software</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-key-approaches-converting-visual-content-on-pinterest-to-audio/"><u>[New] 2024 Approved  Key Approaches  Converting Visual Content on Pinterest To Audio</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-the-2-step-guide-to-smoothly-record-google-hangoutsmeetings/"><u>[New] The 2-Step Guide to Smoothly Record Google Hangouts/Meetings</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fixing-mistaken-face-id-in-facebook-chats/"><u>[Updated] Fixing Mistaken Face ID in Facebook Chats</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-6-virtual-venues-propelling-professional-connections/"><u>2024 Approved  Leading 6 Virtual Venues Propelling Professional Connections</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/audio-enhancement-strategies-using-premiere-pro/"><u>Audio Enhancement Strategies Using Premiere Pro</u></a></li>
<li><a href="https://techidaily.com/best-fixes-for-huawei-nova-y71-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Best Fixes For Huawei Nova Y71 Hard Reset | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/best-solutions-for-the-non-working-print-to-pdf-feature-on-windows-11-platforms/"><u>Best Solutions for the Non-Working Print to PDF Feature on Windows 11 Platforms</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comparing-future-cloud-bill-predictions-for-2024/"><u>Comparing Future Cloud Bill Predictions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/dragon-ball-fighterz-network-error-resolved-initialization-successful/"><u>Dragon Ball FighterZ Network Error Resolved – Initialization Successful</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-steams-latest-patches-wont-download/"><u>Effective Fixes for When Steam's Latest Patches Won’t Download</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-overcoming-windows-10-not-shutdown-errors-on-pc-solved/"><u>Effective Solutions: Overcoming Windows 10 Not Shutdown Errors on PC – SOLVED!</u></a></li>
<li><a href="https://common-error.techidaily.com/effortlessly-fix-the-missing-bluetooth-on-your-windows/"><u>Effortlessly Fix the Missing Bluetooth on Your Windows 지급</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/exploring-streaming-options-vimeo-vs-youtubes-popularity/"><u>Exploring Streaming Options  Vimeo vs YouTube's Popularity</u></a></li>
<li><a href="https://common-error.techidaily.com/findings-no-drivers-supporting-opengl-use/"><u>Findings: No Drivers Supporting OpenGL Use</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-microsofts-print-to-pdf-issue-on-windows-11-a-step-by-step-guide/"><u>Fixing Microsoft's Print to PDF Issue on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/freedom-in-gaming-ps3-wirelessly-on-windows/"><u>Freedom in Gaming: PS3 Wirelessly on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-correcting-the-absence-of-binkw32dll-tips-and-tricks/"><u>Guide to Correcting the Absence of binkw32.dll: Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-repair-what-to-do-when-your-google-chrome-stops-responding/"><u>Guide to Repair: What to Do When Your Google Chrome Stops Responding</u></a></li>
<li><a href="https://common-error.techidaily.com/hardware-monitor-driver-installation-issue-how-to-fix-unsuccessful-loading/"><u>Hardware Monitor Driver Installation Issue: How to Fix Unsuccessful Loading</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-vivo-y56-5g-lock-screen-password-by-drfone-android/"><u>How To Change Vivo Y56 5G Lock Screen Password?</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-realme-gt-5-pro-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Realme GT 5 Pro</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-unified-social-media-platforms-insta-tik-techniques/"><u>In 2024, Unified Social Media Platforms  Insta-Tik Techniques</u></a></li>
<li><a href="https://techidaily.com/is-your-honor-magic-5-pro-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Honor Magic 5 Pro working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/miracast-troubleshooting-solutions-for-devices-with-limited-support/"><u>Miracast Troubleshooting : Solutions for Devices With Limited Support</u></a></li>
<li><a href="https://common-error.techidaily.com/msdia80dll-explained-do-you-need-to-keep-it-running/"><u>mSdIA80.DLL Explained: Do You Need to Keep It Running?</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-reset-failed-issue-a-step-by-step-guide-to-fixing-pc-restore-errors-in-windows-11/"><u>Resolve 'Reset Failed' Issue: A Step-by-Step Guide to Fixing PC Restore Errors in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-ftdi-bus-malfunction-from-non-compatible-device-drivers/"><u>Resolving FTDI Bus Malfunction From Non-Compatible Device Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-touchpad-scrolling-problems-on-a-laptop/"><u>Resolving Window's Touchpad Scrolling Problems on a Laptop</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/revolutionizing-video-speed-in-social-networks/"><u>Revolutionizing Video Speed in Social Networks</u></a></li>
<li><a href="https://win-solutions.techidaily.com/starfield-cpu-performance-optimization-guide-key-adjustments-to-enhance-gameplay-as-of-2024/"><u>Starfield CPU Performance Optimization Guide: Key Adjustments to Enhance Gameplay as of 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-right-click-problems-on-your-windows-10-mouse/"><u>Step by Step Guide: Repairing Right-Click Problems on Your Windows 10 Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-overcoming-issues-with-the-microsoft-store-not-opening-correctly/"><u>Successfully Overcoming Issues with the Microsoft Store Not Opening Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-why-does-my-windows-10-computer-power-on-spontaneously/"><u>Troubleshooting Guide: Why Does My Windows 10 Computer Power On Spontaneously?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-livekernelevent-mishap-with-error-117/"><u>Troubleshooting Tips for Fixing LiveKernelEvent Mishap with Error #117</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/unlocking-the-secrets-of-ios-visual-data-repository-for-2024/"><u>Unlocking the Secrets of IO's Visual Data Repository for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/unveiling-leading-edge-vr-developers-for-2024/"><u>Unveiling Leading-Edge VR Developers for 2024</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-2024-approved-the-ultimate-list-of-mac-video-metadata-editors-top-picks/"><u>Updated 2024 Approved The Ultimate List of Mac Video Metadata Editors Top Picks</u></a></li>
<li><a href="https://common-error.techidaily.com/win-7-freeze-frustration-heres-how-to-stabilize-your-pc-and-avoid-surprises/"><u>Win 7 Freeze Frustration? Here's How to Stabilize Your PC and Avoid Surprises</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->