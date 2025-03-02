---
title: "How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
date: 2025-02-28T20:03:55.344Z
updated: 2025-03-02T04:25:09.791Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
excerpt: "This Article Describes How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/cbe88b794b4a33f4b9a69a7996ceb63e4276735d9be42e403798167c8028b648.jpg
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
<li><a href="https://fox-info.techidaily.com/new-free-football-filming-and-editing-essentials-for-2024/"><u>[New] Free-Football Filming & Editing Essentials for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/assessing-the-truthfulness-of-medical-insights-from-chatgpt-a-look-at-its-trustworthiness/"><u>Assessing the Truthfulness of Medical Insights From ChatGPT: A Look at Its Trustworthiness.</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fix-for-windows-10-microsoft-store-wont-start/"><u>Comprehensive Fix for Windows 10: Microsoft Store Won't Start?</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-fixing-graphic-issues-in-modern-windows-environments-win1110/"><u>Effective Solutions for Fixing Graphic Issues in Modern Windows Environments (Win11/10)</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-your-matches-avoid-infinite-loading-in-valorant-with-these-fixes/"><u>Fast Track Your Matches: Avoid Infinite Loading in Valorant with These Fixes</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Huawei P60? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/labor-day-exclusive-score-a-great-bargain-on-apple-airtag-4-packs-with-24-off-only-available-at-walmart-tech-news/"><u>Labor Day Exclusive: Score a Great Bargain on Apple AirTag 4-Packs with 24% Off, Only Available at Walmart | Tech News</u></a></li>
<li><a href="https://win-blog.techidaily.com/seamless-steps-for-a-flawless-discord-install-experience/"><u>Seamless Steps for a Flawless Discord Install Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/the-fix-reactivating-lighting-features-on-your-corsair-keyboard/"><u>The Fix: Reactivating Lighting Features on Your Corsair Keyboard</u></a></li>
</ul></div>

