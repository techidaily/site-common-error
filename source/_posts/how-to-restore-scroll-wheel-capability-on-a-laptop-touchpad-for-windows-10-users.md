---
title: How to Restore Scroll Wheel Capability on a Laptop Touchpad for Windows 10 Users
date: 2024-10-12T23:57:34.239Z
updated: 2024-10-19T03:15:33.477Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Restore Scroll Wheel Capability on a Laptop Touchpad for Windows 10 Users
excerpt: This Article Describes How to Restore Scroll Wheel Capability on a Laptop Touchpad for Windows 10 Users
thumbnail: https://thmb.techidaily.com/8ec7f9d19b5395810145f1bf31b1db142a6ba9be6ed8b5f1e4a621d2eef1f390.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://extra-tips.techidaily.com/new-a-step-by-step-guide-to-video-aspect-ratio-selection/"><u>[New] A Step-by-Step Guide to Video Aspect Ratio Selection</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-unlock-clearer-depths-with-instas-bokeh-effects-for-2024/"><u>[New] Unlock Clearer Depths with Insta's Bokeh Effects for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-in-2024-affordable-online-education-hosting-on-youtube/"><u>[Updated] In 2024, Affordable Online Education Hosting on YouTube</u></a></li>
<li><a href="https://screen-capture.techidaily.com/1715860296457-2024-approved-immerse-in-pc-game-moments-capture-perfectly/"><u>2024 Approved Immerse in PC Game Moments - Capture Perfectly!</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/approved-motivating-hr-chronicles-the-best-ten-vids/"><u>2024 Approved Motivating HR Chronicles - The Best Ten Vids</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-precision-protests-unveiling-the-difference-between-hero5-black-and-session/"><u>2024 Approved Precision Protests Unveiling the Difference Between Hero5 Black and Session</u></a></li>
<li><a href="https://extra-information.techidaily.com/affordable-flight-masters-top-drone-selections-below-500/"><u>Affordable Flight Masters Top Drone Selections Below $500</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-overwatch-voice-communication-problems-quickly-and-effectively/"><u>Fix Overwatch Voice Communication Problems Quickly and Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-a-device-management-error-28-code-in-your-windows-system/"><u>How to Overcome a Device Management 'Error 28' Code in Your Windows System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-your-bluetooth-connectivity-problems-in-windows-10-ultimate-fixes/"><u>How to Resolve Your Bluetooth Connectivity Problems in Windows 10 - Ultimate Fixes</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-use-phone-clone-to-migrate-your-infinix-hot-30-5g-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Use Phone Clone to Migrate Your Infinix Hot 30 5G Data? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-unresponsive-devices-hooked-up-to-mainframe-resolution-achieved/"><u>Overcoming Issues with Unresponsive Devices Hooked Up to Mainframe [Resolution Achieved]</u></a></li>
<li><a href="https://driver-error.techidaily.com/resolution-achieved-enablement-successful/"><u>Resolution Achieved: Enablement Successful</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-device-cast-errors-in-windows-11-expert-advice-and-fixes/"><u>Resolving Device Cast Errors in Windows 11: Expert Advice & Fixes</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

