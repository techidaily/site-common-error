---
title: "Step-by-Step Tutorial: Correcting Corrupt OS Files in Windows 10 and 11"
date: 2024-08-22T19:18:44.491Z
updated: 2024-08-23T19:18:44.491Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Tutorial: Correcting Corrupt OS Files in Windows 10 and 11"
excerpt: "This Article Describes Step-by-Step Tutorial: Correcting Corrupt OS Files in Windows 10 and 11"
thumbnail: https://thmb.techidaily.com/cfb0e1f2c6527b7d4431251ab8890078af21f0bc88406680edc99866453f0d22.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

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
<li><a href="https://digital-screen-recording.techidaily.com/new-2024-approved-unveiling-the-best-skype-recorders-of-this-year/"><u>[New] 2024 Approved  Unveiling the Best Skype Recorders of This Year</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-cut-to-perfection-editing-video-duration-on-youtube/"><u>[New] In 2024, Cut to Perfection  Editing Video Duration on YouTube</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-unlocking-vr-advertising-potential/"><u>[Updated] 2024 Approved  Unlocking VR Advertising Potential</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-newbies-manual-to-vector-art-grasping-different-kinds-and-software/"><u>[Updated] Newbie’s Manual to Vector Art  Grasping Different Kinds & Software</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-unveiling-the-cutting-edge-cost-free-platforms-for-professional-video-editing/"><u>[Updated] Unveiling The Cutting-Edge, Cost-Free Platforms for Professional Video Editing</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-pro-windows-10-handbook-for-efficiency/"><u>2024 Approved  Pro WINDOWS 10 Handbook for Efficiency</u></a></li>
<li><a href="https://buynow-info.techidaily.com/discover-the-premier-online-education-platforms-ranked-1-10/"><u>Discover the Premier Online Education Platforms Ranked #1-10</u></a></li>
<li><a href="https://common-error.techidaily.com/dll-deficiency-win-core-library-not-present/"><u>DLL Deficiency: Win Core Library Not Present</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-overcome-unknown-usb-device-and-port-reset-failed-errors-in-windows-11/"><u>Effective Solutions to Overcome 'Unknown USB Device' & 'Port Reset Failed' Errors in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-the-common-windows-update-service-failure-error-code-0x80070652/"><u>Effortless Fixes for the Common 'Windows Update Service Failure' (Error Code 0X80070652)</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-resolving-overwatchs-voice-chat-problems/"><u>Effortless Solutions: Resolving Overwatch's Voice Chat Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-rectifying-the-no-sound-issue-with-windows-operating-systems/"><u>Expert Tips: Rectifying the 'No Sound' Issue with Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-solutions-resolving-nier-automata-pc-game-crashes/"><u>Fixes and Solutions: Resolving Nier Automata PC Game Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-slow-data-transfer-between-your-epson-scanner-and-print-device/"><u>Fixing Slow Data Transfer Between Your Epson Scanner and Print Device</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-problem-of-unsupported-hardware-drivers-for-your-pclaptop/"><u>Fixing the Problem of Unsupported Hardware Drivers for Your PC/Laptop</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-does-transfer-learning-power-up-ai-unveiling-the-intricacies/"><u>How Does Transfer Learning Power Up AI? Unveiling the Intricacies</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-an-unresponsive-usb-port-in-hp-computers-guide/"><u>How to Repair an Unresponsive USB Port in HP Computers (Guide)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-everlasting-loading-during-skyrim-gameplay-tips-and-tricks-unveiled/"><u>How to Stop Everlasting Loading During Skyrim Gameplay: Tips & Tricks Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-windows-1110-continuously-rebooting-solutions-inside/"><u>How to Stop Windows 11/10 Continuously Rebooting - Solutions Inside!</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/in-2024-amazon-prime-videos-social-stardom-on-twitter/"><u>In 2024, Amazon Prime Video's Social Stardom on Twitter</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/in-2024-warmth-amidst-cold-selecting-perfect-winter-backdrops/"><u>In 2024, Warmth Amidst Cold  Selecting Perfect Winter Backdrops</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-when-and-how-to-address-improper-pc-boot-problems/"><u>Mastering The Fix: When and How To Address Improper PC Boot Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/next-level-playtime-tweaking-your-pc-settings-for-top-gaming-on-windows-11/"><u>Next-Level Playtime: Tweaking Your PC Settings for Top Gaming on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-server-outages-in-destiny-2-effective-strategies-and-solutions/"><u>Overcoming Server Outages in Destiny 2: Effective Strategies and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-typing-obstacles-a-guide-for-keyboard-problems-in-various-windows-systems/"><u>Overcoming Typing Obstacles: A Guide for Keyboard Problems in Various Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unspecified-error-masterclass-on-fixing-error-0x80004005/"><u>Overcoming Unspecified Error: Masterclass on Fixing Error 0X80004005</u></a></li>
<li><a href="https://common-error.techidaily.com/pubg-bug-solved-steps-to-ensure-all-buildings-load-correctly-now/"><u>PUBG Bug Solved: Steps to Ensure All Buildings Load Correctly Now</u></a></li>
<li><a href="https://common-error.techidaily.com/quiet-your-console-effective-strategies-for-resolving-loud-playstation-4/"><u>Quiet Your Console: Effective Strategies for Resolving Loud PlayStation 4</u></a></li>
<li><a href="https://driver-error.techidaily.com/repair-serial-bus-regulation-flaw/"><u>Repair Serial Bus Regulation Flaw</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-unknown-usb-device-error-on-windows-11-a-step-by-step-guide/"><u>Resolving 'Unknown USB Device' Error on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-call-of-duty-wwii-issue-fixing-error-code-4220/"><u>Resolving Call of Duty WWII Issue: Fixing Error Code 4220</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-usb-malfunctions-a-comprehensive-guide-to-correcting-descriptor-request-failed-notifications/"><u>Resolving USB Malfunctions: A Comprehensive Guide to Correcting 'Descriptor Request Failed' Notifications</u></a></li>
<li><a href="https://common-error.techidaily.com/reveal-hidden-bluetooth-settings-a-comprehensive-walkthrough-on-windows-device-manager/"><u>Reveal Hidden Bluetooth Settings: A Comprehensive Walkthrough on Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/scam-alert-how-to-eradicate-the-deceptive-google-chrome-critical-error-from-your-system/"><u>Scam Alert: How to Eradicate the Deceptive Google Chrome Critical Error From Your System</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/step-by-step-process-of-setting-up-your-logitech-webcam-for-video/"><u>Step-by-Step Process of Setting Up Your Logitech Webcam for Video</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-connect-and-repair-a-nonfunctional-ps4-controller/"><u>Step-by-Step Troubleshooting: Connect and Repair a Nonfunctional PS4 Controller</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-untold-story-10-pro-vlc-tricks-for-better-playback/"><u>The Untold Story  10 Pro-VLC Tricks for Better Playback</u></a></li>
<li><a href="https://common-error.techidaily.com/top-strategies-to-resolve-windows-11-update-issue-error-0x800f0922/"><u>Top Strategies to Resolve Windows 11 Update Issue: Error 0X800F0922</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-your-hp-laptops-webcam-problem-under-windows-11/"><u>Troubleshooting and Repairing Your HP Laptop's Webcam Problem Under Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-failed-intel-realsense-services-on-microsofts-latest-os/"><u>Troubleshooting Failed Intel Realsense Services on Microsoft's Latest OS</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-event-id-1000-across-windows-vista-to-10/"><u>Troubleshooting Guide: Fixing Event ID 1000 Across Windows Vista to 10</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-how-to-fix-your-ps4s-troublesome-nat-type-problem/"><u>Ultimate Guide: How to Fix Your PS4's Troublesome NAT Type Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211510886-video-not-showing-follow-these-simple-steps-to-solve-the-problem/"><u>Video Not Showing? Follow These Simple Steps to Solve the Problem!</u></a></li>
<li><a href="https://common-error.techidaily.com/why-cant-i-update-to-the-latest-features-of-windows-10-version-1607-tips/"><u>Why Can't I Update to the Latest Features of Windows 10? Version 1607 Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212462334-windows-11-icon-dilemma-solved-bring-back-disappearing-desktop-icons-now/"><u>Windows 11 Icon Dilemma Solved: Bring Back Disappearing Desktop Icons Now</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->