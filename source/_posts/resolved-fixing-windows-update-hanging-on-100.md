---
title: "Resolved: Fixing Windows Update Hanging on 100%%"
date: 2024-10-29T05:01:07.332Z
updated: 2024-11-04T17:47:16.857Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing Windows Update Hanging on 100%%"
excerpt: "This Article Describes Resolved: Fixing Windows Update Hanging on 100%%"
thumbnail: https://thmb.techidaily.com/e6c7c0aea059b2b9594111c92d9d243c60708ba7355f3daa30e8aeaa265b4225.jpg
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
<li><a href="https://screen-capture.techidaily.com/new-how-to-record-iphoneipads-screen-2023-latest-method-for-2024/"><u>[New] How to Record iPhone/iPad’s Screen [2023 Latest Method] for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-seeing-beyond-our-elite-rankings-of-camera-lenses-1-10/"><u>[Updated] 2024 Approved Seeing Beyond Our Elite Rankings of Camera Lenses #1-10</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-dashboard-directions-entering-google-meet-pcmobile/"><u>2024 Approved Dashboard Directions Entering Google Meet (PC/Mobile)</u></a></li>
<li><a href="https://technical-tips.techidaily.com/7-amazing-free-mobile-apps-every-student-should-use-before-returning-to-class/"><u>7 Amazing Free Mobile Apps Every Student Should Use Before Returning to Class</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-resolve-no-bootable-device-found-on-your-laptop-or-pc/"><u>Expert Tips to Resolve 'No Bootable Device Found' On Your Laptop or PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-crash-alert-aw-snap-when-using-google-chrome/"><u>Fixing Crash Alert 'Aw, Snap!' When Using Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-windows-network-error-code-0x800704cf/"><u>How to Resolve Windows Network Error Code 0X800704CF</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-msvcp140dll-shortage/"><u>Overcoming MSVCP140.dll Shortage</u></a></li>
<li><a href="https://win-solutions.techidaily.com/smooth-gaming-awaits-how-to-successfully-address-fortnites-lag-issues/"><u>Smooth Gaming Awaits: How to Successfully Address Fortnite's Lag Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-y100a-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Vivo Y100A? | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/understanding-your-pcs-health-with-windows-10s-built-in-battery-analysis-tool/"><u>Understanding Your PC's Health with Windows 10'S Built-In Battery Analysis Tool</u></a></li>
<li><a href="https://win11-tips.techidaily.com/unveiling-windows-security-settings-through-gpo/"><u>Unveiling Windows Security Settings Through GPO</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080342/19272" target="_top" id="2080342">
  <img src="//a.impactradius-go.com/display-ad/19272-2080342" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080342/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

