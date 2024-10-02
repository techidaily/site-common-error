---
title: "Guide: Correcting the Missing Audio Device Installation Error on Your Windows 11 PC"
date: 2024-09-27T02:40:41.161Z
updated: 2024-10-02T01:00:52.429Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Guide: Correcting the Missing Audio Device Installation Error on Your Windows 11 PC"
excerpt: "This Article Describes Guide: Correcting the Missing Audio Device Installation Error on Your Windows 11 PC"
thumbnail: https://thmb.techidaily.com/a54e5c701c009258ccb5e3ebc68c482a0352d900bfe7620286533aaa04ebdf62.png
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://vimeo-videos.techidaily.com/new-conquered-by-creatives-from-wmm-to-a-stellar-vimeo-presence/"><u>[New] Conquered By Creatives From WMM to a Stellar Vimeo Presence</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-how-to-capture-and-share-your-favorite-pics-on-social-platforms-with-obs-for-2024/"><u>[Updated] How to Capture and Share Your Favorite Pics on Social Platforms with OBS for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-flawless-video-calls-from-laptop-using-the-desktop-whatsapp-browser/"><u>[Updated] In 2024, Flawless Video Calls From Laptop Using the Desktop WhatsApp Browser</u></a></li>
<li><a href="https://location-fake.techidaily.com/6-ways-to-change-spotify-location-on-your-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>6 Ways to Change Spotify Location On Your Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/anonymizing-faces-a-compendium-of-photographic-shielders/"><u>Anonymizing Faces A Compendium of Photographic Shielders</u></a></li>
<li><a href="https://common-error.techidaily.com/error-resolved-print-spooler-service-failure-on-32-bit-software-fixed/"><u>Error Resolved: 'Print Spooler Service' Failure on 32-Bit Software Fixed</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-fix-unresponsive-phone-touchscreen-of-lenovo-thinkphone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Fix Unresponsive Phone Touchscreen Of Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-pc-when-its-not-responding-on-windows-1-hanging-scenarios/"><u>How to Fix Your PC When It's Not Responding on Windows 1# (Hanging Scenarios)</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-current-vr-devices-explored/"><u>In 2024, Current VR Devices Explored</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-expert-approved-audio-editing-software-for-high-quality-productions/"><u>New Expert-Approved Audio Editing Software for High-Quality Productions</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-overwatch-audio-glitches-instantly/"><u>Resolve Your Overwatch Audio Glitches Instantly!</u></a></li>
<li><a href="https://common-error.techidaily.com/top-2024-strategies-troubleshooting-your-pcs-bluetooth-connection-woes-in-windows-11/"><u>Top 2024 Strategies: Troubleshooting Your PC's Bluetooth Connection Woes in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/top-8-solutions-to-resolve-windows-10-error-code-0x800f0922-issue/"><u>Top 8 Solutions to Resolve Windows 10 Error Code 0X800F0922 Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-binkw32-dll-missing-error-on-your-pc-fixes-and-solutions/"><u>Troubleshooting BinkW32 DLL Missing Error on Your PC – Fixes and Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044583/7443" target="_top" id="2044583">
  <img src="//a.impactradius-go.com/display-ad/7443-2044583" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044583/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

