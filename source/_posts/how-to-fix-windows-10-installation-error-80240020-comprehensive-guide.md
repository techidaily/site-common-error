---
title: How to Fix Windows 10 Installation Error 802^40020 - Comprehensive Guide
date: 2024-09-19T16:43:47.289Z
updated: 2024-09-20T17:04:06.525Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows 10 Installation Error 802^40020 - Comprehensive Guide
excerpt: This Article Describes How to Fix Windows 10 Installation Error 802^40020 - Comprehensive Guide
thumbnail: https://thmb.techidaily.com/4c4986b04e4e4ffb246b5a08b4cb8ab42716db3ec20badd6e4149efabbe9ecee.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

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
<li><a href="https://extra-lessons.techidaily.com/new-achieve-side-by-side-viewing-on-chrome-the-pip-method/"><u>[New] Achieve Side-by-Side Viewing on Chrome The PIP Method</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-restoring-functionality-for-broken-login-keyboards/"><u>Expert Advice: Restoring Functionality for Broken Login Keyboards</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-restarting-intel-realsense-streaming-technology-in-windows-10-systems/"><u>Guide: Restarting Intel RealSense Streaming Technology in Windows 10 Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/masterpiece-makers-top-10-android-collage-tools/"><u>Masterpiece Makers Top 10 Android Collage Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/revolutionize-your-photos-pro-level-pixlr-techniques/"><u>Revolutionize Your Photos Pro-Level Pixlr Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-restore-functionality-in-windows-11-sound-volume-buttons/"><u>Solved: How To Restore Functionality in Windows 11 Sound Volume Buttons</u></a></li>
<li><a href="https://howto.techidaily.com/top-10-fixes-for-phone-keep-disconnecting-from-wi-fi-on-xiaomi-redmi-a2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 10 Fixes for Phone Keep Disconnecting from Wi-Fi On Xiaomi Redmi A2 | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlock-your-vivo-y100-5g-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>Unlock Your Vivo Y100 5G Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://audio-editing.techidaily.com/updated-the-vocal-navigator-discovering-premium-online-text-to-speech-providers-for-2024/"><u>Updated The Vocal Navigator Discovering Premium Online Text to Speech Providers for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/your-roadmap-to-prominence-top-30-cooler-disco-tags-for-2024/"><u>Your Roadmap to Prominence Top 30 Cooler Disco Tags for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
