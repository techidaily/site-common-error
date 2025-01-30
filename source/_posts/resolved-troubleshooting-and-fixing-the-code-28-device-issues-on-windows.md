---
title: "Resolved: Troubleshooting and Fixing the 'Code 28' Device Issues on Windows"
date: 2025-01-23T18:37:39.304Z
updated: 2025-01-29T23:52:23.026Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Troubleshooting and Fixing the 'Code 28' Device Issues on Windows"
excerpt: "This Article Describes Resolved: Troubleshooting and Fixing the 'Code 28' Device Issues on Windows"
thumbnail: https://thmb.techidaily.com/b926e430c3910450366f0c5eac6f2faf425580bfe11541a9628c11209d7640f5.jpg
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
<li><a href="https://fox-glue.techidaily.com/new-the-ultimate-bundles-for-yi-4k-videographers-for-2024/"><u>[New] The Ultimate Bundles for YI 4K Videographers for 2024</u></a></li>
<li><a href="https://win-bytes.techidaily.com/1-resolve-roblox-error-code-288-instantly-step-by-step-guide/"><u>1. Resolve Roblox Error Code 288 Instantly: Step-by-Step Guide</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-cinematic-capture-top-picks-from-video-experts/"><u>2024 Approved Cinematic Capture Top Picks From Video Experts</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-hs50-microphone-malfunction-common-issues-and-effective-fixes/"><u>Corsair HS50 Microphone Malfunction: Common Issues & Effective Fixes</u></a></li>
<li><a href="https://article-helps.techidaily.com/discovering-the-metaverses-hidden-joys/"><u>Discovering the Metaverse's Hidden Joys</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-the-errcachemiss-error-in-your-google-chrome-browser/"><u>Effective Fixes for the ERR_CACHE_MISS Error in Your Google Chrome Browser</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/engaging-recorders-within-huawei-mate-and-p-series-for-video-capture/"><u>Engaging Recorders Within Huawei Mate and P-Series for Video Capture</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/how-to-completely-remove-files-and-folders-expert-algorithm-guide/"><u>How to Completely Remove Files & Folders: Expert Algorithm Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-dolby-sound-malfunctioning-in-microsofts-latest-os/"><u>How to Fix Dolby Sound Malfunctioning in Microsoft's Latest OS</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-there-was-an-error-resetting-your-pc-in-widows-10/"><u>How to Resolve 'There Was an Error Resetting Your PC' In Widows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-11-lockup-difficulties-techniques-to-safely-close-your-system-down/"><u>Overcoming Windows 11 Lockup Difficulties: Techniques to Safely Close Your System Down</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-google-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Google</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restoring-sound-to-your-conexant-smartaudio-hd-device-under-windows-11/"><u>Restoring Sound to Your Conexant SmartAudio HD Device Under Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-solutions-for-screen-flashing-troubleshooting-on-windows-11-computers/"><u>Ultimate Solutions for Screen Flashing Troubleshooting on Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-repeated-automatic-restarts-in-computers-expert-tips-inside/"><u>Understanding & Fixing Repeated Automatic Restarts in Computers - Expert Tips Inside!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

