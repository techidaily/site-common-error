---
title: Resolving Stalled Windows 10 Installation for Smooth Upgrades
date: 2024-09-13T18:22:31.609Z
updated: 2024-09-20T17:20:59.021Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Stalled Windows 10 Installation for Smooth Upgrades
excerpt: This Article Describes Resolving Stalled Windows 10 Installation for Smooth Upgrades
thumbnail: https://thmb.techidaily.com/5c41e214e42161b19b3ba596b247b1528c5c85cbd29aaa92283a320b0b166cc8.jpg
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
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-unlock-premium-quality-streaming-on-the-worlds-largest-network/"><u>[New] 2024 Approved Unlock Premium Quality Streaming on the World's Largest Network</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-beat-stress-away-the-ultimate-gaming-list/"><u>[New] Beat Stress Away The Ultimate Gaming List</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-in-2024-gain-insight-into-your-contents-success-via-youtube-rankers/"><u>[New] In 2024, Gain Insight Into Your Content's Success via YouTube Rankers</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/boost-video-influence-techniques-for-exceptional-client-spotlights/"><u>Boost Video Influence Techniques for Exceptional Client Spotlights</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgotten-the-voicemail-password-of-itel-p55plus-try-these-fixes-by-drfone-android/"><u>Forgotten The Voicemail Password Of Itel P55+? Try These Fixes</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/high-quality-hd-dvd-conversion-guide-transforming-your-dvds-into-premium-wmv-files-on-windows/"><u>High-Quality HD DVD Conversion Guide: Transforming Your DVDs Into Premium WMV Files on Windows</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-expertly-curated-facebooks-1-10-plays/"><u>In 2024, Expertly Curated Facebook's #1-#10 Plays</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-legendaries-are-in-pokemon-platinum-on-xiaomi-redmi-note-12t-pro-drfone-by-drfone-virtual-android/"><u>In 2024, What Legendaries Are In Pokemon Platinum On Xiaomi Redmi Note 12T Pro? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solution-for-immediate-response-failure-overcoming-error-1053/"><u>Quick Solution for Immediate Response Failure - Overcoming Error 1053</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-of-a-compromised-microsoft-store-memory-bank/"><u>Solving the Problem of a Compromised Microsoft Store Memory Bank</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-11-usb-connectivity-issues-a-comprehensive-fix/"><u>Solving Windows 11 USB Connectivity Issues: A Comprehensive Fix</u></a></li>
<li><a href="https://discover-amazing.techidaily.com/step-by-step-instructions-for-converting-dvd-files-into-common-video-types-on-a-mac/"><u>Step-by-Step Instructions for Converting DVD Files Into Common Video Types on a Mac</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

