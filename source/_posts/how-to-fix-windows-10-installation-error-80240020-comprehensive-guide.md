---
title: How to Fix Windows 10 Installation Error 802^40020 - Comprehensive Guide
date: 2024-09-30T07:29:19.218Z
updated: 2024-10-06T17:48:10.232Z
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
<li><a href="https://extra-resources.techidaily.com/a-step-by-step-approach-to-pinpointing-stellar-photos-on-pexels-for-2024/"><u>A Step-by-Step Approach to Pinpointing Stellar Photos on Pexels for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/best-pokemons-for-pvp-matches-in-pokemon-go-for-xiaomi-redmi-note-13-pro-5g-drfone-by-drfone-virtual-android/"><u>Best Pokemons for PVP Matches in Pokemon Go For Xiaomi Redmi Note 13 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://buynow-help.techidaily.com/free-protection-excellence-leading-antivirus-solutions-without-the-price-tag/"><u>Free Protection Excellence: Leading Antivirus Solutions Without the Price Tag</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208101350-how-to-tackle-excessive-cpu-consumption-by-runtime-broker-on-your-windows-11-pc-solutions-included/"><u>How to Tackle Excessive CPU Consumption by Runtime Broker on Your Windows 11 PC – Solutions Included</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-comparing-the-most-popular-linux-snapshots-tools/"><u>In 2024, Comparing the Most Popular Linux Snapshots Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-shutdown-procedures-troubleshooting-tips-for-a-smooth-exit-in-windows-11-devices/"><u>Mastering Shutdown Procedures: Troubleshooting Tips for a Smooth Exit in Windows 11 Devices</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-prompt-engineering-in-ai-learning/"><u>Navigating Prompt Engineering in AI Learning</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-error-loading-player-issue-with-unavailable-content-on-windows-systems/"><u>Resolving the ‘Error Loading Player’ Issue with Unavailable Content on Windows Systems</u></a></li>
<li><a href="https://program-issues.techidaily.com/solve-your-wow-lag-woes-fast-simple-solutions-for-smooth-gaming/"><u>Solve Your WoW Lag Woes Fast - Simple Solutions for Smooth Gaming</u></a></li>
<li><a href="https://win-answers.techidaily.com/speeding-up-utorrent-effective-strategies-to-improve-transfer-rates/"><u>Speeding Up uTorrent: Effective Strategies to Improve Transfer Rates</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-tips-for-fixing-windows-11-update-error-0xc1900208/"><u>Ultimate Troubleshooting Tips for Fixing Windows 11 Update Error 0Xc1900208</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

