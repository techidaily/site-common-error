---
title: "Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
date: 2024-10-12T22:27:12.094Z
updated: 2024-10-19T02:56:24.121Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
excerpt: "This Article Describes Step-by-Step Solution: Addressing and Repairing the Power State Driver Error"
thumbnail: https://thmb.techidaily.com/7143579495d0f62e1a2cda12fd626d9036d87a576b32c356f772aa95549b6f82.jpg
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
<li><a href="https://vimeo-videos.techidaily.com/new-cutting-edge-editing-solutions-just-for-vimeo-for-2024/"><u>[New] Cutting-Edge Editing Solutions Just for Vimeo for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-secure-your-shots-in-the-cloud-unlimited-free-space-plus-charged-premium-solutions/"><u>[New] Secure Your Shots in the Cloud Unlimited Free Space + Charged Premium Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-this-display-does-not-support-hdcp/"><u>[SOLVED] This Display Does Not Support HDCP</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-perfected-techniques-for-streaming-from-obs-to-fb-success/"><u>2024 Approved Perfected Techniques for Streaming From OBS to FB Success</u></a></li>
<li><a href="https://article-files.techidaily.com/advanced-transitions-techniques-for-audios-for-2024/"><u>Advanced Transitions Techniques for Audios for 2024</u></a></li>
<li><a href="https://techidaily.com/all-things-you-need-to-know-about-wipe-datafactory-reset-for-xiaomi-14-drfone-by-drfone-reset-android-reset-android/"><u>All Things You Need to Know about Wipe Data/Factory Reset For Xiaomi 14 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-ways-to-restore-mic-functionality-on-your-steelseries-arctis-5-headset/"><u>Effective Ways to Restore Mic Functionality on Your SteelSeries Arctis 5 Headset</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-sim-card-on-xiaomi-13t-online-without-jailbreak-by-drfone-android/"><u>How to Unlock SIM Card on Xiaomi 13T online without jailbreak</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-cut-the-red-tape-easy-memes-via-kinemaster/"><u>In 2024, Cut the Red Tape Easy Memes via KineMaster</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-flip-the-script-on-classic-films-7-list/"><u>In 2024, Flip the Script on Classic Films, #7 List</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-bluetooth-device-recognition-in-windows-11-fixes-and-tips-for-seamless-connectivity/"><u>Mastering Bluetooth Device Recognition in Windows 11 – Fixes and Tips for Seamless Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-file-or-device-unavailable-issues-in-windows-systems/"><u>Overcoming 'File or Device Unavailable' Issues in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/triumph-over-fortnites-initial-failure/"><u>Triumph Over Fortnite's Initial Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/urgent-fix-required-enable-local-authorization-defenses-now/"><u>Urgent Fix Required: Enable Local Authorization Defenses Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-troubleshooting-steps-for-restoring-functionality-to-a-defective-bluetooth-mouse/"><u>Windows Troubleshooting: Steps for Restoring Functionality to a Defective Bluetooth Mouse</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

