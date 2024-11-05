---
title: Error 80240020 on Your PC? Here's How to Successfully Install Windows 10!
date: 2024-10-30T16:44:52.619Z
updated: 2024-11-05T07:15:06.246Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10!
excerpt: This Article Describes Error 80240020 on Your PC? Here's How to Successfully Install Windows 10!
thumbnail: https://thmb.techidaily.com/f946d84f254099655a6b886de29d65e5f587fa0ecc62cec124a4f1eb3cdbb6d6.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://youtube-web.techidaily.com/ed-deconstructing-the-revenue-stream-of-tseries-in-youtube-economy-for-2024/"><u>[Updated] Deconstructing the Revenue Stream of TSeries in YouTube Economy for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-instantaneous-windows-photo-explorer/"><u>[Updated] Instantaneous Windows Photo Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/anaplastic-carcinoma-is-a-rare-but-highly-aggressive-form-of-thyroid-cancer-that-often-has-a-poor-prognosis/"><u>Anaplastic Carcinoma Is a Rare but Highly Aggressive Form of Thyroid Cancer that Often Has a Poor Prognosis</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-the-headache-of-error-0x887a0006-your-definitive-guide-to-a-smooth-update-process/"><u>Bypass the Headache of Error 0X887A0006 - Your Definitive Guide to a Smooth Update Process</u></a></li>
<li><a href="https://tech-hub.techidaily.com/crafting-believable-characters-in-ux-with-chatgpt-assistance/"><u>Crafting Believable Characters in UX with ChatGPT Assistance</u></a></li>
<li><a href="https://common-error.techidaily.com/file-explorer-not-responding-in-windows-11-solved/"><u>File Explorer Not Responding in Windows 11 [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-print-to-pdf-feature-for-windows-users-of-both-windows-10-and-11-solutions-uncovered/"><u>Fixing the 'Print to PDF' Feature for Windows Users of Both Windows 10 & 11 - Solutions Uncovered!</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-the-persistent-windows-update-issue-error-0x80240017/"><u>Guide to Fixing the Persistent Windows Update Issue (Error 0X80240017)</u></a></li>
<li><a href="https://tech-hub.techidaily.com/navigating-chatai-for-auto-tailoring-techniques/"><u>Navigating ChatAI for Auto Tailoring Techniques</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/the-beginners-handbook-to-igtv-mastery-for-2024/"><u>The Beginner's Handbook to IGTV Mastery for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/tune-tastic-transfers-find-your-favorite-youtube-songs-with-top-6-free-android-apps-for-2024/"><u>Tune-Tastic Transfers Find Your Favorite Youtube Songs with Top 6 Free Android Apps for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972665/19272" target="_top" id="1972665">
  <img src="//a.impactradius-go.com/display-ad/19272-1972665" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972665/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

