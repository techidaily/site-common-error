---
title: How to Restore Your Mouse Cursor in Windows 11 [Solution]
date: 2024-12-22T17:22:42.613Z
updated: 2024-12-25T18:11:53.429Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Restore Your Mouse Cursor in Windows 11 [Solution]
excerpt: This Article Describes How to Restore Your Mouse Cursor in Windows 11 [Solution]
thumbnail: https://thmb.techidaily.com/ef126118f50b6cc91b0e402fe75cfce958a6a6e6b161357abe8bae35407eca1c.jpg
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
<li><a href="https://visual-screen-recording.techidaily.com/new-the-ultimate-guide-to-recording-gaming-with-fraps/"><u>[New] The Ultimate Guide to Recording Gaming with Fraps</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-2024-approved-seamless-browsing-try-these-7-android-adblockers/"><u>[Updated] 2024 Approved Seamless Browsing? Try These 7 Android AdBlockers</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-capturing-contentment-a-practical-guide-to-daily-vlogging/"><u>[Updated] In 2024, Capturing Contentment A Practical Guide to Daily Vlogging</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-step-by-step-guide-quick-vlog-content-ideas-for-2024/"><u>[Updated] Step-by-Step Guide Quick Vlog Content Ideas for 2024</u></a></li>
<li><a href="https://win-amazing.techidaily.com/download-and-update-pl2303-driver-for-your-windows-computer/"><u>Download & Update PL2303 Driver for Your Windows Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-fixes-for-resolving-no-picture-signal-detected-on-your-display/"><u>Easy Fixes for Resolving 'No Picture Signal Detected' On Your Display</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-getting-your-touchpad-scroll-back-in-action-a-step-by-step-fix/"><u>Guide to Getting Your Touchpad Scroll Back in Action: A Step-by-Step Fix</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-fake-gps-on-realme-v30t-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>In 2024, How To Fake GPS On Realme V30T For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/1722862707017-overcoming-stop-0x0000005c-halinitializationfailed-error-on-your-computer/"><u>Overcoming STOP 0X0000005C (HAL_INITIALIZATION_FAILED) Error on Your Computer</u></a></li>
<li><a href="https://win-able.techidaily.com/resolving-playback-issues-making-your-dolby-atmos-audio-work-in-windows-11-and-10/"><u>Resolving Playback Issues: Making Your Dolby Atmos Audio Work in Windows 11 & 10</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/smart-texting-strategies-to-save-on-mobile-data/"><u>Smart Texting Strategies to Save on Mobile Data</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-resolving-the-0x800704cf-network-error-in-windows-systems/"><u>Step-by-Step Instructions: Resolving the 0X800704CF Network Error in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-address-non-recognition-of-usb-drives-easily/"><u>Step-by-Step Tips to Address Non-Recognition of USB Drives Easily</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

