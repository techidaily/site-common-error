---
title: Scrolling Gains for the Modern PC
date: 2024-09-25T00:23:20.611Z
updated: 2024-10-01T19:05:33.408Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Scrolling Gains for the Modern PC
excerpt: This Article Describes Scrolling Gains for the Modern PC
thumbnail: https://thmb.techidaily.com/9b8cd7a1defe234b7c5e19ea975a65111eb68a7f947172e793fdb9bfe98621fe.jpg
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
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-the-ins-and-outs-of-earning-from-youtube/"><u>[Updated] 2024 Approved The Ins and Outs of Earning From YouTube</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-conceptualization-to-production-writing-engaging-documentary-stories/"><u>[Updated] From Conceptualization to Production Writing Engaging Documentary Stories</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-instagram-success-starts-with-these-strategies/"><u>2024 Approved Instagram Success Starts with These Strategies</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-top-8-best-tripods-for-4k-camera/"><u>2024 Approved Top 8 Best Tripods for 4K Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-trouble-connecting-your-keyboard-to-your-pc-made-simple/"><u>Bluetooth Trouble? Connecting Your Keyboard to Your PC Made Simple</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/boost-engagement-sharing-streams-from-twitch-on-fb/"><u>Boost Engagement Sharing Streams From Twitch on FB</u></a></li>
<li><a href="https://common-error.techidaily.com/directx-initialization-problem-solved-successful-device-creation-tips/"><u>DirectX Initialization Problem Solved: Successful Device Creation Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-resolving-the-missing-directx-component-d3derr/"><u>Expert Advice for Resolving The Missing DirectX Component (D3DERR)</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-out-of-a-pinch-unlocking-windows-10-from-continuous-airplane-mode/"><u>Getting Out of a Pinch: Unlocking Windows 10 From Continuous Airplane Mode</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-realme-gt-5-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Realme GT 5 Device</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/rapid-routes-transferring-ios-photos-and-videos/"><u>Rapid Routes Transferring iOS Photos & Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-ensuring-your-hardware-drivers-work-seamlessly-with-windows-update-solved/"><u>Resolved! Ensuring Your Hardware Drivers Work Seamlessly With Windows Update (Solved)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-installation-issue-fixing-error-code-80240020/"><u>Resolving Windows 10 Installation Issue: Fixing Error Code 80240020</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-steam-updates-a-step-by-step-guide/"><u>Troubleshooting Your Steam Updates: A Step-by-Step Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/unlock-hidden-potential-boost-productivity-essential-multitasking-tips-for-podcast-lovers-for-2024/"><u>Unlock Hidden Potential, Boost Productivity Essential Multitasking Tips for Podcast Lovers for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880960/19272" target="_top" id="1880960">
  <img src="//a.impactradius-go.com/display-ad/19272-1880960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880960/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

