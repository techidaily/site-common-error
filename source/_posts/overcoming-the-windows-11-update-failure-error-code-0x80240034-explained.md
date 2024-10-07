---
title: "Overcoming the Windows 11 Update Failure: Error Code 0X80240034 Explained"
date: 2024-10-02T21:11:32.381Z
updated: 2024-10-07T06:07:56.391Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming the Windows 11 Update Failure: Error Code 0X80240034 Explained"
excerpt: "This Article Describes Overcoming the Windows 11 Update Failure: Error Code 0X80240034 Explained"
thumbnail: https://thmb.techidaily.com/3da10c18ed5eb1d81fc33e9b77c3f37bbadf618042f3295c06f9d5e5b10aa5c0.jpg
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
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-enhance-gameplay-memories-win10-recording-methods/"><u>[Updated] 2024 Approved Enhance Gameplay Memories Win10 Recording Methods</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-compact-content-leading-5-services-to-compress-video-urls/"><u>[Updated] Compact Content Leading 5 Services to Compress Video URLs</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-5-upgrades-to-shine-your-digital-clips/"><u>[Updated] In 2024, 5 Upgrades to Shine Your Digital Clips</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-essential-guide-to-html5s-most-acclaimed-tools/"><u>2024 Approved The Essential Guide to HTML5's Most Acclaimed Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/deciding-on-apples-m1-laptops-air-or-pro-advantages/"><u>Deciding on Apple's M1 Laptops Air or Pro Advantages</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-the-blackout-a-guide-to-restoring-visibility-in-windows-11/"><u>Decoding the Blackout: A Guide to Restoring Visibility in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-missing-device-issue-error-24-on-windows-operating-systems/"><u>Fixing the Missing Device Issue (Error 24) on Windows Operating Systems</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-unlocking-the-secrets-to-instagram-post-replicas/"><u>In 2024, Unlocking the Secrets to Instagram Post Replicas</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/no-need-for-worry-get-your-beloved-tv-show-episodes-on-dvd/"><u>No Need for Worry: Get Your Beloved TV Show Episodes on DVD!</u></a></li>
<li><a href="https://common-error.techidaily.com/run-disabled-process-stopped-suddenly/"><u>Run Disabled: Process Stopped Suddenly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unresponsive-xbox-one-controllers-a-step-by-step-guide/"><u>Troubleshooting Unresponsive Xbox One Controllers: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-windows-update-error-code-0x8024402c-successfully/"><u>Ultimate Guide: Resolving Windows Update Error Code 0X8024402c Successfully</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-nokia-c12-pro-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Nokia C12 Pro Phones</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135393/19272" target="_top" id="2135393">
  <img src="//a.impactradius-go.com/display-ad/19272-2135393" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135393/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

