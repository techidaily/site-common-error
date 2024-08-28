---
title: "Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution"
date: 2024-08-27T13:49:10.951Z
updated: 2024-08-28T13:49:10.951Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution"
excerpt: "This Article Describes Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution"
thumbnail: https://thmb.techidaily.com/0039be476e652be6e9e02b60752db5e1733ea22d9d841af5f5ee6bd2b62676ef.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-how-does-t-series-generate-revenue/"><u>[New] 2024 Approved  How Does T-Series Generate Revenue?</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-immersive-escapes-androidioss-favorite-ar-games/"><u>[New] Immersive Escapes  Android/iOS's Favorite AR Games</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-in-depth-guide-to-game-capturing-roblox-and-mac-integration/"><u>[New] In 2024, In-Depth Guide to Game Capturing  Roblox & Mac Integration</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-instantly-optimize-iphone-videos-in-size-and-duration/"><u>[New] Instantly Optimize iPhone Videos in Size and Duration</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-smooth-cuts-and-seamless-edits-top-6-mac-videos-editors/"><u>[New] Smooth Cuts and Seamless Edits  Top 6 Mac Videos Editors</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-fabricate-funny-faces/"><u>2024 Approved  Fabricate Funny Faces</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/complete-guide-for-recovering-pictures-files-on-xiaomi-by-fonelab-android-recover-pictures/"><u>Complete guide for recovering pictures files on Xiaomi .</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-failed-steam-update-downloads-a-step-by-step-tutorial/"><u>Diagnosing & Fixing Failed Steam Update Downloads - A Step-by-Step Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/end-of-buffering-woes-ultimate-fix-guide-for-kodi-users/"><u>End of Buffering Woes: Ultimate Fix Guide for Kodi Users</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-tackling-and-solving-power-surges-in-hub-terminals/"><u>Expert Advice for Tackling and Solving Power Surges in Hub Terminals</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-handling-and-correcting-missing-d3dx9nn-dll-files-in-your-programs/"><u>Expert Tips for Handling and Correcting Missing D3dx9_nN Dll Files in Your Programs</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-restore-microphone-functionality-in-the-latest-windows-11-update/"><u>Expert Tips to Restore Microphone Functionality in the Latest Windows 11 Update</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-resolving-the-critical-windows-update-problem-0x80070490-quickly/"><u>Expert Tips: Resolving the Critical Windows Update Problem 0X80070490 Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-bluetooth-missing-from-windows-device-manager/"><u>Fix Guide: Bluetooth Missing From Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-installation-glitches-for-origin-platform-gaming-titles/"><u>Guide to Fixing Installation Glitches for Origin Platform Gaming Titles</u></a></li>
<li><a href="https://common-error.techidaily.com/hassle-free-guide-to-correcting-windows-update-error-code-0x80070eb5/"><u>Hassle-Free Guide to Correcting Windows Update Error Code 0X80070eb5</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-configure-your-drivers-when-you-encounter-set-user-settings-to-driver-failed/"><u>How to Correctly Configure Your Drivers When You Encounter 'Set User Settings To Driver Failed'</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-update-error-code-0x8024002e-easily/"><u>How to Fix Windows Update Error Code 0X8024002E Easily!</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-complete-review-and-guide-to-techeligible-frp-bypass-and-more-for-xiaomi-redmi-note-12-pro-5g-by-drfone-android/"><u>In 2024, Complete Review & Guide to Techeligible FRP Bypass and More For Xiaomi Redmi Note 12 Pro 5G</u></a></li>
<li><a href="https://extra-tips.techidaily.com/iphone-images-jpg-png-straightforward-conversion-guide/"><u>IPhone Images (JPG, PNG) - Straightforward Conversion Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/low-cpu-strategies-for-streamlined-operation-of-windows-driver-foundation-components/"><u>Low-CPU Strategies for Streamlined Operation of Windows Driver Foundation Components</u></a></li>
<li><a href="https://common-error.techidaily.com/make-your-aoc-screen-function-again-in-win10-step-by-step-guide/"><u>Make Your AOC Screen Function Again in Win10: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202981193-operating-system-not-found-or-missing-operating-system-error-fixed/"><u>Operating System Not Found Or Missing Operating System Error Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-crc-faults-in-your-data-transmission-now-solved/"><u>Overcoming CRC Faults in Your Data Transmission - Now Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-display-issues-missing-touchpad-and-hardware-buttons-functionality/"><u>Resolving Display Issues: Missing Touchpad and Hardware Buttons Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-installation-issues-with-windows-11-version-1607-updates/"><u>Solving Installation Issues with Windows 11 Version 1607 Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-scroll-pad-issues-in-windows-11-for-enhanced-user-experience/"><u>Step-by-Step Guide to Fix Scroll Pad Issues in Windows 11 for Enhanced User Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-your-laptop-from-falling-asleep-unexpectedly-with-these-easy-solutions/"><u>Stop Your Laptop From Falling Asleep Unexpectedly with These Easy Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-eliminate-recurring-system-lockups-on-your-laptop-or-desktop/"><u>Troubleshoot and Eliminate Recurring System Lockups on Your Laptop or Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211075518-troubleshooting-techniques-for-windows-11-non-shutting-desktops-solutions/"><u>Troubleshooting Techniques for Windows 11 Non-Shutting Desktops - Solutions!</u></a></li>
<li><a href="https://tech-revival.techidaily.com/unlocking-potential-beyond-chatgpts-tokens/"><u>Unlocking Potential Beyond ChatGPT’s Tokens</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-usb-success-stories-overcoming-port-reset-failed-hurdles-on-your-windows-11-machine/"><u>Unlocking USB Success Stories: Overcoming 'Port Reset Failed' Hurdles on Your Windows 11 Machine</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/what-does-enter-puk-code-mean-and-why-did-the-sim-get-puk-blocked-on-oppo-reno-9a-device-by-drfone-android/"><u>What Does Enter PUK Code Mean And Why Did The Sim Get PUK Blocked On Oppo Reno 9A Device</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://turbotech.pxf.io/c/5597632/1450763/17212" target="_top" id="1450763"><img src="//a.impactradius-go.com/display-ad/17212-1450763" border="0" alt="" width="2560" height="1440"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1450763/17212" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->