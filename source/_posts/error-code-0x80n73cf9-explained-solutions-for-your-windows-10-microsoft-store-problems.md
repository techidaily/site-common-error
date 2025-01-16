---
title: "Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems"
date: 2025-01-10T16:17:14.894Z
updated: 2025-01-16T16:26:18.804Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems"
excerpt: "This Article Describes Error Code 0X80n73Cf9 Explained: Solutions for Your Windows 10 Microsoft Store Problems"
thumbnail: https://thmb.techidaily.com/576613d76775eba96e07a16efe944a1e36820bdf585d7f2830fda9d8a084962a.jpg
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
<li><a href="https://facebook-record-videos.techidaily.com/new-chortle-chamber-ideas-for-7-amusing-online-sessions-for-2024/"><u>[New] Chortle Chamber Ideas for 7 Amusing Online Sessions for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-quick-mac-mastering-screen-recording-via-shortcuts/"><u>2024 Approved Quick Mac Mastering Screen Recording via Shortcuts</u></a></li>
<li><a href="https://common-error.techidaily.com/bringing-color-back-to-your-game-screenshots-addressing-and-solving-obsidian-screen-darkness/"><u>Bringing Color Back to Your Game Screenshots: Addressing and Solving Obsidian Screen Darkness</u></a></li>
<li><a href="https://facebook.techidaily.com/crafting-a-unique-visual-identity-fb-cover-pics-guide/"><u>Crafting a Unique Visual Identity: FB Cover Pics Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ive-command-center-studio-for-youtubers-for-2024/"><u>Creative Command Center Studio for YouTubers for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-and-rectifying-how-to-overcome-google-chromes-persistent-blackscreen-glitches/"><u>Decoding & Rectifying: How To Overcome Google Chrome's Persistent Blackscreen Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-ftdibus-driver-issues-to-restore-memory-data-integrity-and-system-stability/"><u>Fixing Ftdibus Driver Issues to Restore Memory Data Integrity and System Stability</u></a></li>
<li><a href="https://common-error.techidaily.com/handling-exceptions-fixing-memory-could-not-be-written-error-due-to-improper-references/"><u>Handling Exceptions: Fixing 'Memory Could Not Be Written' Error Due to Improper References</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-bypass-icloud-lock-from-iphone-6-by-drfone-ios/"><u>How to Bypass iCloud Lock from iPhone 6</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-harness-the-power-of-on-the-go-visual-adjustments/"><u>In 2024, Harness the Power of On-the-Go Visual Adjustments</u></a></li>
<li><a href="https://fox-glue.techidaily.com/the-ultimate-review-gopro-hero5-adventure-footage/"><u>The Ultimate Review GoPro Hero5 Adventure Footage</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-windows-driver-power-state-issues/"><u>Ultimate Guide: Resolving Windows Driver Power State Issues</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/understanding-the-mechanism-for-personalizing-social-media-visuals-for-2024/"><u>Understanding the Mechanism for Personalizing Social Media Visuals for 2024</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/why-is-my-monitor-black-diagnosing-and-fixing-graphics-card-problems-with-expert-advice-from-yl-software/"><u>Why Is My Monitor Black? Diagnosing and Fixing Graphics Card Problems with Expert Advice From YL Software</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MPoakxUNf9o?si=S-ppSqzHzN9VrxC7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

