---
title: Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]
date: 2025-02-04T07:23:03.078Z
updated: 2025-02-11T02:10:01.336Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]
excerpt: This Article Describes Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]
thumbnail: https://thmb.techidaily.com/ebbfde368b81e7f396fe512ace44b149bef6fef394a1d6fd8cfa20e2c4a0b6c3.jpg
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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-mastering-your-mac-creating-captivating-style-videography/"><u>[New] 2024 Approved Mastering Your Mac Creating Captivating Style Videography</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/new-effortless-enchantment-make-your-mark-with-striking-templates-for-tiktok/"><u>[New] Effortless Enchantment Make Your Mark with Striking Templates for TikTok</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-aerial-precision-mavic-pro-analysis/"><u>[Updated] Unveiling Aerial Precision - Mavic Pro Analysis</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-hunt-for-windows-hello-camera/"><u>Compatibility Hunt for Windows Hello Camera</u></a></li>
<li><a href="https://techtrends.techidaily.com/download-videos-from-any-website-a-complete-guide-with-movavi/"><u>Download Videos From Any Website: A Complete Guide with Movavi</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-the-powerhouse-that-is-the-asus-zephyrus-g14-an-elite-gamers-dream/"><u>Exploring the Powerhouse That Is the Asus Zephyrus G14 - An Elite Gamer’s Dream</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211406665-fixing-the-crimson-display-issue-overcoming-the-notorious-red-screen-glitch/"><u>Fixing The Crimson Display Issue - Overcoming the Notorious Red Screen Glitch</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-update-errors-version-1607-what-you-need-to-know/"><u>Fixing Windows 11 Update Errors (Version 1607) – What You Need to Know</u></a></li>
<li><a href="https://common-error.techidaily.com/follicular-carcinoma-while-less-common-than-papillary-still-accounts-for-a-significant-percentage-of-all-thyroid-cancers/"><u>Follicular Carcinoma, While Less Common than Papillary, Still Accounts for a Significant Percentage of All Thyroid Cancers.</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Oppo Find X7 Ultra? | Dr.fone</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-2023-fb-live-stream-mp4-conversion-tool/"><u>In 2024, 2023 FB Live Stream MP4 Conversion Tool</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mast-hopping-lingo-key-pirate-words-for-authenticity/"><u>Mast-Hopping Lingo: Key Pirate Words for Authenticity</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-usb-devices-not-working-on-latest-windows-operating-systems/"><u>Resolving Issues with USB Devices Not Working on Latest Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/search-for-light-control-tool-in-windows/"><u>Search for Light Control Tool in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reducing-high-cpu-consumption-from-windows-audio-device-isolation-discrepancy/"><u>Step-by-Step Guide: Reducing High CPU Consumption From Windows Audio Device Isolation Discrepancy</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/strategies-for-managing-and-reducing-android-phone-temperature/"><u>Strategies for Managing and Reducing Android Phone Temperature</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-broken-key-on-your-keyboard-a-step-by-step-guide/"><u>Troubleshooting a Broken '@' Key on Your Keyboard - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-error-0x800f081f-in-microsoft-net-framework-35-installation-process/"><u>Troubleshooting Guide for Error 0X800F081F in Microsoft .NET Framework 3.5 Installation Process</u></a></li>
<li><a href="https://win-updates.techidaily.com/xbox-e360-drive-revival-tips-securely-backup-and-retrieve-your-lost-data/"><u>Xbox E360 Drive Revival Tips: Securely Backup & Retrieve Your Lost Data</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

