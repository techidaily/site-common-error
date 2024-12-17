---
title: Fixing File Explorer Crash in Windows 11 – Step-by-Step Solutions
date: 2024-12-09T20:38:51.049Z
updated: 2024-12-16T17:37:32.409Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing File Explorer Crash in Windows 11 – Step-by-Step Solutions
excerpt: This Article Describes Fixing File Explorer Crash in Windows 11 – Step-by-Step Solutions
thumbnail: https://thmb.techidaily.com/06768f0764e3fd16593ec6ab66fe93ff9404677c09f36129dabffcc95362a115.jpg
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
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-fiverr-cover-content-proportions/"><u>[New] 2024 Approved Fiverr Cover Content Proportions</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-vidma-screen-recorder-review-and-alternatives/"><u>[New] In 2024, Vidma Screen Recorder | Review and Alternatives</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-sky-high-cloud-stashing-solutions-on-android/"><u>[Updated] Sky-High Cloud Stashing Solutions on Android</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-viral-ventures-valuation-the-revenue-of-a-rising-star/"><u>2024 Approved Viral Ventures Valuation The Revenue of a Rising Star</u></a></li>
<li><a href="https://extra-information.techidaily.com/comprehensive-data-restoration-tool-complete-software-suite-for-every-type-of-file-retrieval/"><u>Comprehensive Data Restoration Tool: Complete Software Suite for Every Type of File Retrieval</u></a></li>
<li><a href="https://common-error.techidaily.com/ensuring-successful-system-tasks-with-admin-access-in-windows-11-10-and-nversions/"><u>Ensuring Successful System Tasks with Admin Access in Windows 11, 10 & Nversions</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-on-restoring-functionality-to-a-broken-corsair-keyboard/"><u>Expert Tips on Restoring Functionality to a Broken Corsair Keyboard</u></a></li>
<li><a href="https://howto.techidaily.com/google-play-services-wont-update-12-fixes-are-here-on-oppo-f25-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Google Play Services Wont Update? 12 Fixes are Here on Oppo F25 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-any-samsung-galaxy-f54-5g-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Samsung Galaxy F54 5G Phone Password Using Emergency Call</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-art-of-reviving-a-dead-steelseries-x70-optical-mouse-nub-in-depth-restoration-guide-for-windows-users/"><u>Master the Art of Reviving a Dead SteelSeries X70 Optical Mouse Nub: In-Depth Restoration Guide for Windows Users</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/no-more-scrolling-find-your-filmora-promo-code-now-for-2024/"><u>No More Scrolling Find Your Filmora Promo Code Now for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-system-file-specified-not-found-errors-a-comprehve-solutions-guide/"><u>Overcoming System 'File Specified Not Found' Errors: A Comprehve Solutions Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/the-biggest-risk-for-stock-markets-now-is-that-central-banks-are-forced-to-tighten-policy-sooner-than-expected-which-could-spark-higher-borrowing-costs-and-45/"><u>The Biggest Risk for Stock Markets Now Is that Central Banks Are Forced to Tighten Policy Sooner than Expected, Which Could Spark Higher Borrowing Costs and Make Equities Less Attractive.</u></a></li>
<li><a href="https://common-error.techidaily.com/unlock-stylus-and-touch-capabilities-for-non-reactive-displays/"><u>Unlock Stylus & Touch Capabilities for Non-Reactive Displays</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-and-intel-storage-solutions-getting-rst-services-up-and-running-again/"><u>Windows 11 and Intel Storage Solutions: Getting RST Services Up & Running Again</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

