---
title: "Mastering Windows 11 Updates: Avoid Error Code 0X800F0922 Pitfalls"
date: 2024-10-18T02:24:09.980Z
updated: 2024-10-18T17:19:49.256Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Windows 11 Updates: Avoid Error Code 0X800F0922 Pitfalls"
excerpt: "This Article Describes Mastering Windows 11 Updates: Avoid Error Code 0X800F0922 Pitfalls"
thumbnail: https://thmb.techidaily.com/4b5562ff0db20c13529d0f69be32d5c21c69778a6a352420334c0743deb0bfe7.png
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
<li><a href="https://fox-direct.techidaily.com/updated-strategies-to-bypass-edgenuity-videos-with-minimal-hassle-for-2024/"><u>[Updated] Strategies to Bypass Edgenuity Videos with Minimal Hassle for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-breaking-into-design-your-strategy-for-career-success/"><u>2024 Approved Breaking Into Design Your Strategy for Career Success</u></a></li>
<li><a href="https://win11-tips.techidaily.com/beat-the-blue-screen-bane-11-tricks-for-windows-11/"><u>Beat the Blue Screen Bane: 11 Tricks for Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-optimize-your-pc-say-goodbye-to-fallout-4-lag-issues/"><u>How to Optimize Your PC: Say Goodbye to Fallout 4 Lag Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-audio-on-windows-10-overcoming-unresponsive-volume-control-challenges/"><u>Mastering Audio on Windows 10: Overcoming Unresponsive Volume Control Challenges</u></a></li>
<li><a href="https://fox-pages.techidaily.com/maximizing-durability-effective-strategies-for-increasing-hard-drive-ssd-and-usb-lifespans/"><u>Maximizing Durability: Effective Strategies for Increasing Hard Drive, SSD, and USB Lifespans</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/persuasive-films-that-hook-and-hold-audiences/"><u>Persuasive Films That Hook and Hold Audiences</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-messages-back-from-sony-xperia-10-v-by-fonelab-android-recover-messages/"><u>Simple ways to get lost messages back from Sony Xperia 10 V</u></a></li>
<li><a href="https://games-able.techidaily.com/the-freelance-gamers-compendium-unveiling-the-best-free-steam-titles/"><u>The Freelance Gamer's Compendium: Unveiling the Best Free Steam Titles</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-11-free-apps-to-check-imei-on-poco-c51-phones-by-drfone-android/"><u>Top 11 Free Apps to Check IMEI on Poco C51 Phones</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-failed-attempts-at-opening-the-steam-marketplace-step-by-step-solutions/"><u>Troubleshooting Failed Attempts at Opening the Steam Marketplace: Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212108452-troubleshooting-guide-fixing-a-non-responsive-laptop-trackpad/"><u>Troubleshooting Guide: Fixing a Non-Responsive Laptop TrackPad</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-window-11s-unstable-display-a-step-by-step-guide/"><u>Troubleshooting Window 11'S Unstable Display: A Step-by-Step Guide</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885999/19272" target="_top" id="1885999">
  <img src="//a.impactradius-go.com/display-ad/19272-1885999" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885999/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

