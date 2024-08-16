---
title: Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION
date: 2024-08-15T11:03:16.526Z
updated: 2024-08-16T11:03:16.526Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION
excerpt: This Article Describes Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION
thumbnail: https://thmb.techidaily.com/7ba25f196f1fd36b2bff5ba5871f3da3d2f6d119166da5162e1c6bea9b39b80e.jpg
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
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698832&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/karaoki-new-searchresultspane.jpg" border="0">PCDJ Karaoki is the complete professional karaoke software designed for KJs and karaoke venues. Karaoki includes an advanced automatic singer rotation list with singer history, key control, news ticker, next singers screen, a song book exporter and printer, a jukebox background music player and many other features designed so you can host karaoke shows faster and easier! 
 PCDJ Karaoki (WINDOWS ONLY Professional Karaoke Software - 3 Activations)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee8fe2d3c.jpg)
  
 3\. Then you will see the Windows Install screen, select**Repair your computer** at the bottom left corner.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afee63020fa.png)
  
 4\. In Choose an option screen, select**Troubleshoot** .  
  
<!-- affiliate ads begin -->
<a href="https://caperobbin.sjv.io/c/5597632/2006123/18460" target="_top" id="2006123"><img src="//a.impactradius-go.com/display-ad/18460-2006123" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2006123/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58afef1de6d4e.png)
  
 5\. Then select**Advanced options** .  
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726960&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/5f4f7141b65a730b4efb0e0d51f63e94/products/forexrobotronbox.gif" border="0">Forex Robotron Basic Package</a>
<!-- affiliate ads end -->
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
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BSQL%2BRecovery"><img src="https://www.systoolsgroup.com/box/sql-recovery.png" border="0"></a>
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
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35504869&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/1_FR-200-1.png" border="0">Glarysoft File Recovery Pro Annually -  Helps to recover your lost file/data, even permanently deleted data. 
</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/02/img_58affd826668f.png)
  
**Run a system file check**
  
 Follow steps below:  
  
 1\. Open**Command Prompt** as an administrator.  
  
 2\. Type or paste**sfc /scannow** and hit**Enter** . The process will also take some time to complete.  
  
<!-- affiliate ads begin -->
<a href="https://cowinaudio.pxf.io/c/5597632/1116855/13794" target="_top" id="1116855"><img src="//a.impactradius-go.com/display-ad/13794-1116855" border="0" alt="" width="767" height="285"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1116855/13794" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-mastering-teams-personalized-call-banners/"><u>[New] 2024 Approved  Mastering Teams' Personalized Call Banners</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-streamlining-video-workflow-capture-save-refine-using-adobe-connect-for-2024/"><u>[New] Streamlining Video Workflow  Capture, Save, Refine Using Adobe Connect for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-infinite-loading-screen-on-valorant-a-guide-to-getting-you-back-into-action/"><u>[Solved] Infinite Loading Screen on Valorant: A Guide to Getting You Back Into Action</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-ps4-controller-wont-charge/"><u>[SOLVED] PS4 Controller Won’t Charge</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/3-best-tools-to-hard-reset-vivo-y36i-drfone-by-drfone-reset-android-reset-android/"><u>3 Best Tools to Hard Reset Vivo Y36i | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/activating-bluetooth-on-a-windows-7-machine-a-comprehensive-tutorial/"><u>Activating Bluetooth on a Windows 7 Machine - A Comprehensive Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/all-systems-checked-yet-one-component-idles/"><u>All Systems Checked, Yet One Component Idles</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-solving-dolby-audio-issues-in-windows-10-systems/"><u>Comprehensive Guide: Solving Dolby Audio Issues in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207691717-cracking-the-code-to-successfully-register-classes-on-windows-10-detailed-fixes-revealed/"><u>Cracking the Code to Successfully Register Classes on Windows 10 - Detailed Fixes Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-overcoming-driverpowerstatefailure-errors/"><u>Effective Solutions for Overcoming DRIVER_POWER_STATE_FAILURE Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/enhance-win10-efficiency-cpu-reduction-steps/"><u>Enhance Win10 Efficiency: CPU Reduction Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-getting-minecraft-back-running-on-windows-after-launch-problems/"><u>Expert Advice: Getting Minecraft Back Running on Windows After Launch Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-faulty-driver-issues-fast-a-comprehensive-tutorial/"><u>Fixing Faulty Driver Issues Fast: A Comprehensive Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-issues-with-unsuccessful-torrent-downloads/"><u>How to Fix Issues with Unsuccessful Torrent Downloads</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-to-bypass-frp-from-vivo-v29-by-drfone-android/"><u>In 2024, How to Bypass FRP from Vivo V29?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-check-if-your-xiaomi-redmi-note-13-pro-5g-is-unlocked-by-drfone-android/"><u>In 2024, How To Check if Your Xiaomi Redmi Note 13 Pro 5G Is Unlocked</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-reset-the-security-questions-of-your-apple-id-on-your-iphone-11-pro-by-drfone-ios/"><u>In 2024, How To Reset the Security Questions of Your Apple ID On Your iPhone 11 Pro</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-your-oppo-find-x6-lock-screen-password-by-drfone-android/"><u>In 2024, How to Reset your Oppo Find X6 Lock Screen Password</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/introducing-newcomers-to-english/"><u>Introducing Newcomers to English</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210391878-keyboard-navigation-failure-revitalize-those-arrow-buttons-here/"><u>Keyboard Navigation Failure? Revitalize Those Arrow Buttons Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/no-more-pdf-print-troubles-effective-remedies-for-immediate-relief/"><u>No More PDF Print Troubles - Effective Remedies for Immediate Relief</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-the-notorious-windows-10-crimson-display-problem/"><u>Resolved: Fixing the Notorious Windows 10 Crimson Display Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-common-causes-and-fixes-for-unresponsive-lenovo-keyboards/"><u>Resolved! Common Causes and Fixes for Unresponsive Lenovo Keyboards</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-blue-screen-a-step-by-step-guide-to-correcting-system-error-code-c00000e9/"><u>Resolving the Blue Screen: A Step-by-Step Guide to Correcting System Error Code C00000e9</u></a></li>
<li><a href="https://fake-location.techidaily.com/spoofing-life360-how-to-do-it-on-honor-magic-6-lite-drfone-by-drfone-virtual-android/"><u>Spoofing Life360 How to Do it on Honor Magic 6 Lite? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-functionality-for-the-windows-key-combo-shiftpluss-in-windows-operating-systems/"><u>Step-by-Step Guide to Restoring Functionality for the Windows Key Combo (Shift+S) in WIndows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-solution-ensuring-seamless-airpods-integration-with-windows-11/"><u>The Definitive Solution : Ensuring Seamless AirPods Integration with Windows 11</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/things-you-should-know-when-unlocking-total-wireless-of-iphone-14-plus-by-drfone-ios/"><u>Things You Should Know When Unlocking Total Wireless Of iPhone 14 Plus</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-persistent-computer-hibernation-issues-with-easy-solutions/"><u>Troubleshoot Persistent Computer Hibernation Issues with Easy Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-notorious-red-screen-of-error-in-your-device/"><u>Ultimate Guide: Resolving the Notorious 'Red Screen of Error' In Your Device</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-wow-performance-sluggishness/"><u>Ultimate Guide: Solving 'WoW' Performance Sluggishness</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpectedly-turned-off-computers-diagnosis-and-repair-techniques/"><u>Unexpectedly Turned Off Computers: Diagnosis and Repair Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/unreal-engine-hangs-in-balance-with-d3d-status/"><u>Unreal Engine Hangs in Balance with D3D Status</u></a></li>
</ul></div>
