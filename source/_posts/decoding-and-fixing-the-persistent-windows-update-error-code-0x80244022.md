---
title: "Decoding and Fixing the Persistent Windows Update Error Code: 0X802#44022"
date: 2024-10-29T16:04:55.547Z
updated: 2024-10-30T16:42:55.805Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Decoding and Fixing the Persistent Windows Update Error Code: 0X802#44022"
excerpt: "This Article Describes Decoding and Fixing the Persistent Windows Update Error Code: 0X802#44022"
thumbnail: https://thmb.techidaily.com/d9d28999ab80c3fe303824be9f1e02b9cc335e9a7ef77a5fdd8ceeee3dcb3523.jpg
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
<li><a href="https://extra-support.techidaily.com/new-step-by-step-obtaining-no-cost-photo-frames/"><u>[New] Step-by-Step Obtaining No-Cost Photo Frames</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/best-hashtags-for-youtube-to-get-your-views-to-6-figures-for-2024/"><u>Best Hashtags for YouTube to Get Your Views to 6 Figures for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/cost-effective-charm-how-the-motorola-one-mimics-an-iphone-at-a-bargain-price/"><u>Cost-Effective Charm: How the Motorola One Mimics an iPhone at a Bargain Price</u></a></li>
<li><a href="https://fox-http.techidaily.com/creating-a-unique-identity-in-the-flood-of-live-streams/"><u>Creating a Unique Identity in the Flood of Live Streams</u></a></li>
<li><a href="https://hardware-help.techidaily.com/efficiently-update-your-brother-mfc-l2740dw-printer-with-new-windows-drivers/"><u>Efficiently Update Your Brother MFC-L2740DW Printer with New Windows Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208810863-errtoomanyredirects-fixed-fast-solutions/"><u>ERR_TOO_MANY_REDIRECTS Fixed: Fast Solutions</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/in-2024-irecorder-insights-for-tech-enthusiasts/"><u>In 2024, IRecorder Insights for Tech Enthusiasts</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/skypes-sound-solution-purifying-your-talks-for-2024/"><u>Skype's Sound Solution Purifying Your Talks for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/speeding-up-your-lol-downloads-effective-solutions-and-tips/"><u>Speeding Up Your LoL Downloads - Effective Solutions and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-unsuccessful-attempts-to-access-a-distant-server/"><u>Troubleshooting and Solving Unsuccessful Attempts to Access a Distant Server</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-your-ps4-controller-sync-problems/"><u>Ultimate Guide: Resolving Your PS4 Controller Sync Problems</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-2024-approved-free-to-create-top-14-watermark-free-video-editing-software-and-beyond/"><u>Updated 2024 Approved Free to Create Top 14 Watermark-Free Video Editing Software and Beyond</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484909/16446" target="_top" id="1484909">
  <img src="//a.impactradius-go.com/display-ad/16446-1484909" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484909/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

