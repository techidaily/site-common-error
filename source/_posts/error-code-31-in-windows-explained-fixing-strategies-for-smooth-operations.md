---
title: "Error Code 31 in Windows Explained: Fixing Strategies for Smooth Operations"
date: 2024-10-02T03:35:40.351Z
updated: 2024-10-07T04:40:26.968Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 31 in Windows Explained: Fixing Strategies for Smooth Operations"
excerpt: "This Article Describes Error Code 31 in Windows Explained: Fixing Strategies for Smooth Operations"
thumbnail: https://thmb.techidaily.com/80e5cdef4afad3cdaa6f71026bfd555865de3d18de62989f967049cc703431b5.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-instagram-to-music-directing-videos-to-mp3-outputs/"><u>[New] 2024 Approved Instagram to Music Directing Videos to MP3 Outputs</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-simplify-information-storage-via-mematic/"><u>[New] Simplify Information Storage via Mematic</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-iphone-filmmaking-achieving-complete-circles/"><u>2024 Approved IPhone Filmmaking Achieving Complete Circles</u></a></li>
<li><a href="https://common-error.techidaily.com/bring-your-dells-non-functional-wireless-keyboard-back-to-life-with-these-tips/"><u>Bring Your Dell's Non-Functional Wireless Keyboard Back to Life with These Tips</u></a></li>
<li><a href="https://video-capture.techidaily.com/comprehensive-tutorial-on-adjusting-video-orientation-in-vlc/"><u>Comprehensive Tutorial on Adjusting Video Orientation in VLC</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-how-to-resolve-unresponsive-google-chrome-issues/"><u>Fix: How to Resolve Unresponsive Google Chrome Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-class-unregistered-errors-in-windows-11-a-comprehensive-guide/"><u>Fixing 'Class Unregistered' Errors in Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-xiaomi-civi-3-disney-100th-anniversary-edition-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Xiaomi Civi 3 Disney 100th Anniversary Edition? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-samsung-galaxy-s24-drfone-by-drfone-virtual-android/"><u>In 2024, How to get the dragon scale and evolution-enabled pokemon On Samsung Galaxy S24? | Dr.fone</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-next-level-entertainment-exclusive-windows-10-gaming-and-apps/"><u>In 2024, Next-Level Entertainment Exclusive Windows 10 Gaming & Apps</u></a></li>
<li><a href="https://win-amazing.techidaily.com/latest-hp-deskjet-2600-driver-downloads-for-enhanced-performance-on-windows-systems-win7win8win10/"><u>Latest HP DeskJet 2600 Driver Downloads for Enhanced Performance on Windows Systems (Win7/Win8/Win10)</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-1ntricacies-effective-fixes-for-error-0x80072efd-on-windows-11-systems/"><u>Overcoming Windows 1Ntricacies: Effective Fixes for Error 0X80072EFD on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-0x80n0705b4-windows-update-issue-on-windows-10-detailed-solutions/"><u>Resolving 0X80n0705b4 Windows Update Issue on Windows 10 [Detailed Solutions]</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-address-the-problem-of-being-plugged-in-but-laptop-wont-charge-in-windows-710/"><u>Step-by-Step Guide to Address the Problem of Being Plugged In but Laptop Won’t Charge in Windows 7/10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/1062447/7443" target="_top" id="1062447">
  <img src="//a.impactradius-go.com/display-ad/7443-1062447" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/1062447/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

