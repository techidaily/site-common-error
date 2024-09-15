---
title: Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
date: 2024-09-09T14:24:22.986Z
updated: 2024-09-15T03:46:20.554Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
excerpt: This Article Describes Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
thumbnail: https://thmb.techidaily.com/7f38f48d6c1e2e7dd4ffc2cf3530de002749e2e66d038be493fc55f20cd91a70.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://location-fake.techidaily.com/4-methods-to-turn-off-life-360-on-samsung-galaxy-s21-fe-5g-2023-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>4 Methods to Turn off Life 360 On Samsung Galaxy S21 FE 5G (2023) without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-productivity-with-file-explorer-in-windows-11-a-beginners-guide/"><u>Boost Productivity with File Explorer in Windows 11 - A Beginner's Guide</u></a></li>
<li><a href="https://android-location.techidaily.com/for-people-wanting-to-mock-gps-on-nokia-c12-devices-drfone-by-drfone-virtual/"><u>For People Wanting to Mock GPS on Nokia C12 Devices | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-samsung-galaxy-a14-5g-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Samsung Galaxy A14 5G Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-reduce-high-network-activity-caused-by-svchostexe-netsvcs/"><u>How to Reduce High Network Activity Caused by svchost.exe NETSVCS</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-your-typing-setup-when-the-at-symbol-doesnt-work/"><u>How To Repair Your Typing Setup When the 'At' Symbol Doesn’t Work</u></a></li>
<li><a href="https://techidaily.com/how-to-update-or-downgrade-apple-iphone-15-plus-without-data-loss-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade Apple iPhone 15 Plus Without Data Loss? | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-process-of-screen-sharing-nubia-z50s-pro-to-pc-detailed-steps-drfone-by-drfone-android/"><u>In 2024, Process of Screen Sharing Nubia Z50S Pro to PC- Detailed Steps | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-11-update-obstacles-expert-advice-and-solutions/"><u>Overcoming Windows 11 Update Obstacles: Expert Advice & Solutions</u></a></li>
<li><a href="https://extra-support.techidaily.com/palette-perfection-unveiling-top-5-premium-color-tvs-for-2024/"><u>Palette Perfection Unveiling Top 5 Premium Color TVs for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

