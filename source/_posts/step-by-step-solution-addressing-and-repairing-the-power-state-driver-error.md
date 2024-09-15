---
title: "Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
date: 2024-09-14T00:48:17.308Z
updated: 2024-09-14T19:56:39.996Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
excerpt: "This Article Describes Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
thumbnail: https://thmb.techidaily.com/7143579495d0f62e1a2cda12fd626d9036d87a576b32c356f772aa95549b6f82.jpg
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
<li><a href="https://common-error.techidaily.com/fixed-aoc-usb-monitor-not-working-on-windows-11/"><u>[FIXED] AOC USB Monitor Not Working on Windows 11</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-audio-recording-made-easy-free-x-recorder-for-pc/"><u>[Updated] 2024 Approved Audio Recording Made Easy Free X-Recorder for PC</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205500665-copy-pasting-woes-heres-how-to-fix-it-on-your-windows-11-machine/"><u>Copy-Pasting Woes? Here's How to Fix It on Your Windows 11 Machine!</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-correcting-the-unresponsive-spacebar-problem-on-your-windows-10-device/"><u>Diagnosing and Correcting the Unresponsive Spacebar Problem on Your Windows 10 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-the-rendering-api-update-for-dota-2-error-202/"><u>Fix the 'Rendering API Update' For Dota 2 Error 202</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-can-we-unlock-our-samsung-galaxy-a14-5g-phone-screen-by-drfone-android/"><u>How Can We Unlock Our Samsung Galaxy A14 5G Phone Screen?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-install-audio-devices-when-none-are-recognized-on-windows-11/"><u>How to Install Audio Devices When None Are Recognized on Windows 11</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-hacks-to-do-pokemon-go-trainer-battles-for-oppo-a58-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Hacks to do pokemon go trainer battles For Oppo A58 4G | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-poco-c65-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Poco C65 Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/reviewing-the-pinnacle-of-tv-tech-lg-27ud88-uhd-oled-hdtv/"><u>Reviewing the Pinnacle of TV Tech - LG 27UD88-UHD OLED HDTV</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-restore-microphone-functionality-in-your-steelseries-arctis-5/"><u>Solved: How to Restore Microphone Functionality in Your SteelSeries Arctis 5</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/top-8-immersive-virtual-reality-adventures-on-oculus/"><u>Top 8 Immersive Virtual Reality Adventures on Oculus</u></a></li>
<li><a href="https://fox-that.techidaily.com/troubleshooting-a-disabled-ios-device-how-to-regain-access-quickly/"><u>Troubleshooting a Disabled iOS Device: How to Regain Access Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207435318-troubleshooting-guide-starting-the-hosted-network-in-windows-10-fixed/"><u>Troubleshooting Guide: Starting the Hosted Network in Windows 10 Fixed!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014854/22899" target="_top" id="2014854">
  <img src="//a.impactradius-go.com/display-ad/22899-2014854" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014854/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

