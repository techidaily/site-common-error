---
title: "Expert Guide: Resolving Installation Errors Code 0X80070643 on Your Windows Device"
date: 2024-10-21T19:57:27.856Z
updated: 2024-10-24T22:13:15.581Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Guide: Resolving Installation Errors Code 0X80070643 on Your Windows Device"
excerpt: "This Article Describes Expert Guide: Resolving Installation Errors Code 0X80070643 on Your Windows Device"
thumbnail: https://thmb.techidaily.com/92290ca438acc7b53d6d463fb220788f23c7aae03036a5859c384dd9ace3b529.jpg
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
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-visualizationvirtue-the-art-of-resizing-photos-and-videos-in-instagram/"><u>[Updated] 2024 Approved VisualizationVirtue The Art of Resizing Photos and Videos in Instagram</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-edge-techniques-for-effective-video-cropping-and-exporting/"><u>[Updated] Instagram Edge Techniques for Effective Video Cropping and Exporting</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-10-must-have-accessories-for-sj4000/"><u>[Updated] Top 10 Must Have Accessories for SJ4000</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/efficiently-archive-social-media-videos-with-top-5-pick/"><u>Efficiently Archive Social Media Videos with Top 5 Pick</u></a></li>
<li><a href="https://some-tips.techidaily.com/gratuit-gebaseerd-3gp-toeeinden-in-animated-gifs-onlinereputatie-zeer-goed/"><u>Gratuit Gebaseerd 3GP-Toeëinden in Animated GIFs - Onlinereputatie Zeer Goed!</u></a></li>
<li><a href="https://change-location.techidaily.com/how-pgsharp-save-you-from-ban-while-spoofing-pokemon-go-on-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual-android/"><u>How PGSharp Save You from Ban While Spoofing Pokemon Go On Xiaomi Redmi Note 12 Pro 4G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-high-msmpengexe-cpu-usage-in-windows-11-solutions-and-tips/"><u>How to Fix High MsMpEng.exe CPU Usage in Windows 11: Solutions & Tips</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-android-unlock-code-sim-unlock-your-honor-play-8t-phone-and-remove-locked-screen-by-drfone-android/"><u>In 2024, Android Unlock Code Sim Unlock Your Honor Play 8T Phone and Remove Locked Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/interface-issue-no-more-key-woes/"><u>Interface Issue - No More Key Woes</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fix-overcoming-buildings-not-loading-glitches-in-playerunknowns-battlegrounds/"><u>Master the Fix: Overcoming 'Buildings Not Loading' Glitches in PlayerUnknown’s Battlegrounds</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-critical-media-device-drivers-missing-from-your-pc/"><u>Solved: Critical Media Device Drivers Missing From Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-microphone-problems-on-windows-11-pcs/"><u>Troubleshooting Microphone Problems on Windows 11 PCs</u></a></li>
<li><a href="https://games-able.techidaily.com/unboxing-the-robust-msi-gm30-from-clutch-gaming-durable-and-ergonomic-review/"><u>Unboxing the Robust MSI GM30 From Clutch Gaming - Durable & Ergonomic Review</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657386/16446" target="_top" id="1657386">
  <img src="//a.impactradius-go.com/display-ad/16446-1657386" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657386/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

