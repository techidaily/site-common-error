---
title: Troubleshooting Steps for Forcing a Shutdown on Windows 11 Systems
date: 2024-08-27T13:51:08.488Z
updated: 2024-08-28T13:51:08.488Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Forcing a Shutdown on Windows 11 Systems
excerpt: This Article Describes Troubleshooting Steps for Forcing a Shutdown on Windows 11 Systems
thumbnail: https://thmb.techidaily.com/502bcc92fd452403f6c08525ae02c0d2e78a33616170701a3383a08e8dcec924.jpg
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
<li><a href="https://vimeo-videos.techidaily.com/new-beyond-vimeo-a-compilation-of-premier-video-editors-for-2024/"><u>[New] Beyond Vimeo  A Compilation of Premier Video Editors for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-explore-a-world-of-delicious-treats-top-rated-cookie-shops-for-2024/"><u>[New] Explore a World of Delicious Treats  Top-Rated Cookie Shops for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-elevating-your-videos-visual-impact-youtubthumbnail-design-on-macos/"><u>[New] In 2024, Elevating Your Video's Visual Impact  YoutubThumbnail Design on macOS</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-quick-tips-for-ios-screen-record-for-2024/"><u>[New] Quick Tips for iOS Screen Record for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-premier-ios-platform-for-psp-emulation-1-5/"><u>[Updated] 2024 Approved  Premier iOS Platform for PSP Emulation #1-5</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-streamlining-your-digital-workspace-mastering-zoom-sessions/"><u>[Updated] 2024 Approved  Streamlining Your Digital Workspace  Mastering Zoom Sessions</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-enabling-dynamic-hdr-in-windows-11-os-for-2024/"><u>[Updated] Enabling Dynamic HDR in Windows 11 OS for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leading-sound-transformation-tools-magic-edition-included/"><u>2024 Approved  Leading Sound Transformation Tools, Magic Edition Included</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-missing-link-prime-free-speech-to-text-on-macos/"><u>2024 Approved  Missing Link  Prime Free Speech to Text on macOS</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-oppo-a78-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Oppo A78 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/api-dependency-not-met-cruntimel1-1-0-unavailable/"><u>API Dependency Not Met, cRuntimeL1-1-0 Unavailable</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-blockade-error-0x80004005-expert-strategies-for-fixing-the-mysterious-unspecified-error/"><u>Bypassing Blockade Error 0X80004005 - Expert Strategies for Fixing the Mysterious 'Unspecified Error'</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-windows-11-errors-during-pc-restore-tips-and-tricks-for-a-smooth-fix/"><u>Bypassing Windows 11 Errors During PC Restore: Tips and Tricks for a Smooth Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/chrome-in-crisis-effective-ways-to-address-your-browsers-sudden-nightfall/"><u>Chrome in Crisis: Effective Ways to Address Your Browser’s Sudden Nightfall</u></a></li>
<li><a href="https://win11.techidaily.com/cure-for-local-security-guard-off-error-message/"><u>Cure for 'Local Security Guard Off' Error Message</u></a></li>
<li><a href="https://article-posts.techidaily.com/cutting-edge-components-in-desktops-for-2024/"><u>Cutting-Edge Components in Desktops for 2024</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-how-to-bypass-htc-frp-android-10111213-by-drfone-android/"><u>Easy Guide How To Bypass HTC FRP Android 10/11/12/13</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-for-unidentified-flash-memory-devices-overcoming-device-descriptor-request-failed-errors/"><u>Easy Solutions for Unidentified Flash Memory Devices: Overcoming 'Device Descriptor Request Failed' Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-how-to-troubleshoot-a-non-functional-xbox-one-headset/"><u>Fixing Issues: How to Troubleshoot a Non-Functional Xbox One Headset</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-cannot-cast-to-device-issue-in-windows-10-comprehensive-guide/"><u>Fixing the 'Cannot Cast to Device' Issue in Windows 10 - Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-resolving-the-persistent-windows-update-error-code-0x8007001f/"><u>Guide: Resolving the Persistent Windows Update Error Code 0X8007001F</u></a></li>
<li><a href="https://win11-tips.techidaily.com/guidelines-to-rectify-windows-bluetooth-outputs-music-only/"><u>Guidelines to Rectify Windows Bluetooth Outputs - Music Only</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-honor-90-gtmirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Honor 90 GTMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-computer-not-recognizing-headphones/"><u>How To Fix Computer Not Recognizing Headphones</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-handle-system-crashes-due-to-absence-of-xinput13dll/"><u>How to Handle System Crashes Due to Absence of XINPUT1_3.dll</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-nokia-150-2023-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Nokia 150 (2023) | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-how-to-bypass-frp-on-oppo-a59-5g-by-drfone-android/"><u>In 2024, How to Bypass FRP on Oppo A59 5G?</u></a></li>
<li><a href="https://extra-support.techidaily.com/laughs-lab-innovator-for-2024/"><u>Laughs Lab Innovator for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-camera-issues-with-error-0xa00f4292-solutions-in-detail/"><u>Overcome Windows Camera Issues with Error 0XA00F4292 Solutions in Detail</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-inaccessible-windows-installer-quick-fixes-and-tips/"><u>Overcoming Issues with Inaccessible Windows Installer: Quick Fixes and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-network-startup-hurdles-in-dragon-ball-fighterz-comprehensive-troubleshooting-tips/"><u>Overcoming Network Startup Hurdles in Dragon Ball FighterZ – Comprehensive Troubleshooting Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209002585-overcoming-the-kernel-power-hurdle-addressing-windows-error-code-0xc00pressure-to-ensure-a-healthy-environment/"><u>Overcoming the 'Kernel Power' Hurdle: Addressing Windows Error Code 0xC00pressure to Ensure a Healthy Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-a-malfunctioning-touchscreen-in-your-windows-11-device-5-methods/"><u>Quick Fixes for a Malfunctioning Touchscreen in Your Windows 11 Device [5 Methods]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-excessive-cpu-load-troubleshooting-wudfhostexe-on-windows-11/"><u>Resolving Excessive CPU Load: Troubleshooting wudfhost.exe on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-of-a-missing-cursor-on-your-windows-11-touchpad/"><u>Resolving the Issue of a Missing Cursor on Your Windows 11 Touchpad</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-the-issue-overcoming-challenges-in-starting-evil-genius-2/"><u>Resolving the Issue: Overcoming Challenges in Starting Evil Genius 2</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-hp-laptops-webcam-expert-fixes-compatible-with-windows-11-operating-system/"><u>Revive Your HP Laptop's Webcam: Expert Fixes Compatible with Windows 11 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/security-update-successful-restrictions-lifted-for-file-download-functionality/"><u>Security Update Successful: Restrictions Lifted for File Download Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-resolving-driver-power-cycle-issues-in-windows/"><u>Solutions for Resolving Driver Power Cycle Issues in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-correcting-your-pcs-failure-to-boot-successfully/"><u>Step-by-Step Guide: Correcting Your PC’s Failure to Boot Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-the-parameter-is-incorrect-problem-in-library-loading/"><u>Step-by-Step Solution to the 'Parameter Is Incorrect' Problem in Library Loading</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-connection-fix-microsoft-wireless-display-adapter-issues-on-windows-10-resolved/"><u>Successful Connection Fix: Microsoft Wireless Display Adapter Issues on Windows 10 Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-ps4-nat-types-with-this-detailed-walkthrough/"><u>Troubleshoot and Fix PS4 NAT Types with This Detailed Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solutions-for-wows-slow-performance-expert-advice/"><u>Troubleshooting and Solutions for Wow's Slow Performance - Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-airdrop-issues-fast/"><u>Troubleshooting Guide: Fixing AirDrop Issues Fast</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-ps4-connection-a-comprehensive-fix-for-failed-nat-types/"><u>Troubleshooting PS4 Connection: A Comprehensive Fix for Failed NAT Types</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-non-responsive-wacom-graphic-tables/"><u>Troubleshooting Steps for Non-Responsive Wacom Graphic Tables</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-stuck-file-explorer-in-windows-10-easy-fixes-for-seamless-navigation/"><u>Troubleshooting Stuck File Explorer in Windows 10 - Easy Fixes for Seamless Navigation</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-dxgkrnl-fatal-crash-during-video-streaming-on-windows/"><u>Troubleshooting the Dxgkrnl Fatal Crash During Video Streaming on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-fixes-resolving-windows-11s-dark-display-dilemma/"><u>Troubleshooting the Fixes: Resolving Windows 11'S Dark Display Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixing-windows-11-startup-issues-post-update/"><u>Troubleshooting Tips: Fixing Windows 11 Startup Issues Post-Update</u></a></li>
<li><a href="https://android-location-track.techidaily.com/two-ways-to-track-my-boyfriends-vivo-y100i-without-him-knowing-drfone-by-drfone-virtual-android/"><u>Two Ways to Track My Boyfriends Vivo Y100i without Him Knowing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-fixes-for-persistent-windows-update-failure-code-0x8024002e/"><u>Ultimate Fixes for Persistent Windows Update Failure - Code 0X8024002E</u></a></li>
<li><a href="https://some-skills.techidaily.com/uncovering-superior-free-viewers-for-your-webm-media-files-for-2024/"><u>Uncovering Superior, Free Viewers for Your WebM Media Files for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/unstick-your-windows-10-update-dilemma-easy-repair-techniques-explained/"><u>Unstick Your Windows 10 Update Dilemma – Easy Repair Techniques Explained</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/vn-video-editor-android-review-a-comprehensive-guide-for-2024/"><u>VN Video Editor Android Review A Comprehensive Guide for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-nubia-red-magic-9-pro-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Nubia Red Magic 9 Pro Phones</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://electronicx.pxf.io/c/5597632/1872456/14483" target="_top" id="1872456"><img src="//a.impactradius-go.com/display-ad/14483-1872456" border="0" alt="" width="500" height="375"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1872456/14483" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->