---
title: "Fixing the Issue: Why Your DVD Isn't Working on a Windows PC"
date: 2024-10-05T07:15:17.728Z
updated: 2024-10-07T06:46:29.710Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Issue: Why Your DVD Isn't Working on a Windows PC"
excerpt: "This Article Describes Fixing the Issue: Why Your DVD Isn't Working on a Windows PC"
thumbnail: https://thmb.techidaily.com/c27c29fba053b8832f23b24095348059aefd5880debbcb1a483191d3fe3d1075.jpg
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
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-from-fuzzy-frames-to-sharpness-the-v22-journey/"><u>[Updated] In 2024, From Fuzzy Frames to Sharpness - The V2.2 Journey</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-effective-ways-to-gain-access-to-cost-free-imagery/"><u>2024 Approved Effective Ways to Gain Access to Cost-Free Imagery</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x887a0006-cracked-effective-fixes-at-your-fingertps/"><u>Error 0X887A0006 Cracked: Effective Fixes at Your Fingertps</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-a-non-responsive-steam-store-interface/"><u>Expert Tips for Fixing a Non-Responsive Steam Store Interface</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-why-does-my-minecraft-not-start-on-windows/"><u>Fixing the Issue: Why Does My Minecraft Not Start on Windows?</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-error-msresouce-and-apptext-on-w11-os/"><u>How to Fix Error: MsResouce and AppText on W11 OS</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-music-files-from-honor-100-by-fonelab-android-recover-music/"><u>How To Restore Missing Music Files from Honor 100</u></a></li>
<li><a href="https://android-unlock.techidaily.com/remove-the-lock-screen-fingerprint-of-your-samsung-galaxy-m54-5g-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Samsung Galaxy M54 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-pcs-performance-by-installing-required-media-drivers/"><u>Revive Your PC's Performance by Installing Required Media Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-obs-capture-problem-eliminate-the-annoying-black-screen-now/"><u>Troubleshooting OBS Capture Problem - Eliminate the Annoying Black Screen Now!</u></a></li>
<li><a href="https://data-recovery.techidaily.com/1720600583031-windows-stellar-data-recovery/"><u>Windows版無料データ復元ソフト - Stellar Data Recovery(ステラデータリカバリー)</u></a></li>
<li><a href="https://extra-tips.techidaily.com/your-guide-to-attracting-viewers-with-6-key-videos/"><u>Your Guide to Attracting Viewers with 6 Key Videos</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

