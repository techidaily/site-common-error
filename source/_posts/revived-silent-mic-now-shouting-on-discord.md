---
title: Revived Silent Mic, Now Shouting on Discord
date: 2024-08-27T13:41:16.792Z
updated: 2024-08-28T13:41:16.792Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Revived Silent Mic, Now Shouting on Discord
excerpt: This Article Describes Revived Silent Mic, Now Shouting on Discord
thumbnail: https://thmb.techidaily.com/dcfda18db33cd62e49e998a15226cf50935f6371594750217f925e9fab66f62b.jpg
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
<li><a href="https://desktop-recording.techidaily.com/new-how-to-record-video-presentations-using-adobe-presenter-for-2024/"><u>[New] How to Record Video Presentations Using Adobe Presenter for 2024</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-how-to-ensure-accurate-game-saves-with-fbx-recorder/"><u>[Updated] 2024 Approved  How to Ensure Accurate Game Saves with FBX Recorder</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-elitemac-pro-the-best-in-high-quality-video-and-audio-recording-for-2024/"><u>[Updated] EliteMac Pro  The Best in High-Quality Video & Audio Recording for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-from-amateur-to-pro-instagram-video-tutorials/"><u>[Updated] In 2024, From Amateur to Pro  Instagram Video Tutorials</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-online-fb-music-collection-now/"><u>[Updated] Online FB Music Collection Now</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-optimizing-audio-quality-during-video-calls-on-win11/"><u>[Updated] Optimizing Audio Quality During Video Calls on Win11</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-vdq-video-snatcher-assessment-comprehensive-analysis-for-2024/"><u>[Updated] VDQ Video Snatcher Assessment  Comprehensive Analysis for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-vivo-v27e-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Vivo V27e? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/boosting-windows-7-boot-times-effective-solutions/"><u>Boosting Windows 7 Boot Times: Effective Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-methods-to-revive-charging-on-your-laptop-battery/"><u>Effortless Methods to Revive Charging on Your Laptop Battery!</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-error-5-tackling-unable-to-perform-file-operation-in-temp-folder-and-completing-setup-successfully/"><u>Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/enhance-your-gaming-experience-by-fixing-screen-tearing-in-valorant-a-comprehensive-guide/"><u>Enhance Your Gaming Experience by Fixing Screen Tearing in Valorant - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-stuck-disk-error-on-windows-10-a-step-by-step-guide/"><u>Fix Your Stuck Disk Error on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-microsofts-print-to-pdf-feature-fails-on-windows-10-and-11/"><u>Fixing the Issue: Microsoft's Print to PDF Feature Fails on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-netflix-blackout-a-complete-guide/"><u>Fixing the Netflix Blackout: A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-taskbar-visibility-issues-a-comprehensive-guide/"><u>Fixing Windows 11 Taskbar Visibility Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-solving-wwe-2k-games-dx11-at-level-100-problem/"><u>Guide to Solving WWE 2K Game's DX11 at Level 10.0 Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-broken-windows-1n-update-process-for-optimal-performance/"><u>How to Repair a Broken Windows 1N Update Process for Optimal Performance</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-a-detailed-vpna-fake-gps-location-free-review-on-nokia-c32-drfone-by-drfone-virtual-android/"><u>In 2024, A Detailed VPNa Fake GPS Location Free Review On Nokia C32 | Dr.fone</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-change-your-apple-iphone-12-apple-id-on-macbook-by-drfone-ios/"><u>In 2024, How To Change Your Apple iPhone 12 Apple ID on MacBook</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-logo-genius-10-tips-for-memorable-podcast-imagery/"><u>In 2024, Logo Genius  10 Tips for Memorable Podcast Imagery</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-maximizing-efficiency-in-remote-group-meetings/"><u>In 2024, Maximizing Efficiency in Remote Group Meetings</u></a></li>
<li><a href="https://tech-haven.techidaily.com/mastering-regular-meditation-techniques-using-insights-from-chatgpt/"><u>Mastering Regular Meditation Techniques Using Insights From ChatGPT</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/new-exclusive-listing-of-the-top-11-cost-free-speech-adjustment-software-for-ios-and-android-users-for-2024/"><u>New Exclusive Listing of the Top 11 Cost-Free Speech Adjustment Software for iOS & Android Users for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-final-cut-pro-x-for-filmmakers-creating-visually-stunning-videos/"><u>New In 2024, Final Cut Pro X for Filmmakers Creating Visually Stunning Videos</u></a></li>
<li><a href="https://extra-hints.techidaily.com/room-arrangement-for-immersive-vr-experience/"><u>Room Arrangement for Immersive VR Experience</u></a></li>
<li><a href="https://hardware-help.techidaily.com/rtx-2080-super-graphics-card-drivers-download-and-update-guide-for-windows-11/"><u>RTX 2080 Super Graphics Card Drivers Download & Update Guide for Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/shift-key-issues-heres-how-you-can-get-it-working-again/"><u>Shift Key Issues? Here's How You Can Get It Working Again</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/stellars-top-advice-a-comprehensive-guide-to-safe-data-purging-techniques/"><u>Stellar's Top Advice: A Comprehensive Guide to Safe Data Purging Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fixing-the-non-functional-hp-laptop-camera-in-windows-10-systems/"><u>Step-by-Step Guide: Fixing the Non-Functional HP Laptop Camera in Windows 10 Systems</u></a></li>
<li><a href="https://screen-recording.techidaily.com/step-by-step-obs-studio-setup-for-android-users/"><u>Step-by-Step OBS Studio Setup for Android Users</u></a></li>
<li><a href="https://fox-that.techidaily.com/1721462175907-struggling-with-ios-updates-for-your-device-here-are-9-fixes-that-work/"><u>Struggling with iOS Updates for Your Device? Here Are 9 Fixes that Work!</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-windows-troubles-heres-how-you-can-resolve-error-0x8024402c-on-your-pc/"><u>Tackling Windows Troubles? Here's How You Can Resolve Error 0X8024402C on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-free-guide-to-repairing-nonfunctional-keys-on-hp-notebooks/"><u>Trouble-Free Guide to Repairing Nonfunctional Keys on HP Notebooks</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-failed-to-initialize-network-in-dragon-ball-fighterz/"><u>Troubleshooting Steps for 'Failed to Initialize Network' In Dragon Ball FighterZ</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-0x80-grove-2f8f-error-in-windows-11-and-10/"><u>Troubleshooting the 0X80 Grove 2F8f Error in Windows 11 and 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-startup-failure-error-0xc000007b/"><u>Troubleshooting Tips for Fixing Startup Failure (Error 0Xc000007b)</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-touchpad-woes-heres-how-to-fix-sluggish-or-nonfunctional-scroll-buttons/"><u>Windows 10 Touchpad Woes? Here's How to Fix Sluggish or Nonfunctional Scroll Buttons</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208592788-winupdate-trouble-learn-how-to-restart-and-resolve-issues-quickly/"><u>WinUpdate Trouble? Learn How to Restart and Resolve Issues Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/yac568-yamahaaturbosound-ii-sound-module-based-on-the-ymf794gymu3x-dsp-plus-midi-synthesader-plus-codec-and-256-mb-of-spiram-for-sample-storage-instead-of-r23/"><u>YAC568 - Yamaha'aturboSound II Sound Module Based on the YMF794G/YMU^3X (DSP + MIDI Synthesader + Codec) and 256 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->