---
title: "Guide: Correcting the Missing Audio Device Installation Error on Your Windows 11 PC"
date: 2024-09-25T16:07:47.122Z
updated: 2024-09-26T22:08:15.593Z
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
<li><a href="https://youtube-data.techidaily.com/024-approved-youtube-revenue-streams-cross-device-studio-strategies/"><u>[New] 2024 Approved YouTube Revenue Streams Cross-Device Studio Strategies</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-discreetly-discovering-instagram-stories-online-pc-android-iphone-methods/"><u>[Updated] Discreetly Discovering Instagram Stories Online - PC, Android, iPhone Methods</u></a></li>
<li><a href="https://win-dash.techidaily.com/1722967704950-bluetooth-connection-woes-fresh-drivers-for-improved-control/"><u>Bluetooth Connection Woes? Fresh Drivers for Improved Control.</u></a></li>
<li><a href="https://win-marvelous.techidaily.com/create-interactive-digital-magaznies-from-pdfs-using-our-no-cost-pdf-flipsheet-maker/"><u>Create Interactive Digital Magaznies From PDFs Using Our No-Cost PDF Flipsheet Maker</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/digital-collection-mastery-extracting-twitters-animated-tweets-for-2024/"><u>Digital Collection Mastery Extracting Twitter's Animated Tweets for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204141485-fixing-the-print-to-pdf-feature-for-windows-users-of-both-windows-10-and-11-solutions-uncovered/"><u>Fixing the 'Print to PDF' Feature for Windows Users of Both Windows 10 & 11 - Solutions Uncovered</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-use-life360-on-windows-pc-for-google-pixel-8-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Use Life360 on Windows PC For Google Pixel 8 Pro? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201917753-medullary-carcinoma-originates-from-parafollicular-c-cells-and-can-be-associated-with-genetic-syndromes-like-multiple-endocrine-neoplasia-type-2-men2/"><u>Medullary Carcinoma Originates From Parafollicular C Cells and Can Be Associated with Genetic Syndromes Like Multiple Endocrine Neoplasia Type 2 (MEN2).</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-lenovo-security-hurdles-fixing-a-failing-fingerprint-scanner/"><u>Overcoming Lenovo Security Hurdles: Fixing a Failing Fingerprint Scanner</u></a></li>
<li><a href="https://windows11.techidaily.com/quick-guide-to-photoshopping-out-image-borders/"><u>Quick Guide to Photoshopping Out Image Borders</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-valorant-perpetual-load-how-to-fix-endless-startup-issues/"><u>Resolve 'Valorant' Perpetual Load: How to Fix Endless Startup Issues</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148644/16836" target="_top" id="2148644">
  <img src="//a.impactradius-go.com/display-ad/16836-2148644" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148644/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

