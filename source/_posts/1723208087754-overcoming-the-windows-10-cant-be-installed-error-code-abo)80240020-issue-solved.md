---
title: Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved
date: 2024-10-29T04:35:24.777Z
updated: 2024-11-05T06:05:34.082Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved
excerpt: This Article Describes Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved
thumbnail: https://thmb.techidaily.com/20681dc3787d86713afd2395e0942d0819f5bca12434956d1fe5521df7d6718e.jpg
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
<li><a href="https://facebook-clips.techidaily.com/new-from-your-vantage-point-to-the-worlds-sharing-immersive-photos-online-for-2024/"><u>[New] From Your Vantage Point to the World's Sharing Immersive Photos Online for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/acknowledgment-series-free-vs-paid-template-choices/"><u>Acknowledgment Series Free vs Paid Template Choices</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-twitch-troubles-effective-fixes-for-overcoming-error-4000/"><u>Beat Twitch Troubles: Effective Fixes for Overcoming Error #4000</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-resolve-the-missing-entry-point-warning-in-windows/"><u>Easy Steps to Resolve the Missing Entry Point Warning in Windows</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/effective-strategies-overcoming-no-recording-problem-in-windows-10-game-bar-top-7-fixes-explored/"><u>Effective Strategies: Overcoming 'No Recording' Problem in Windows 10 Game Bar, Top 7 Fixes Explored</u></a></li>
<li><a href="https://extra-tips.techidaily.com/faces-of-technology-analyzing-face-detection-in-phones/"><u>Faces of Technology Analyzing Face Detection in Phones</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-3-things-you-must-know-about-fake-snapchat-location-on-infinix-smart-8-plus-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Things You Must Know about Fake Snapchat Location On Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-itel-p55plus-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Itel P55+ Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://common-error.techidaily.com/pubg-wont-start-comprehensive-repair-steps-a-step-by-step-guide/"><u>PUBG Won't Start? Comprehensive Repair Steps : A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-understanding-cyclic-redundancy-check-and-correcting-data-mistakes/"><u>Resolved: Understanding Cyclic Redundancy Check and Correcting Data Mistakes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-of-a-missing-bluetooth-symbol-in-windows-10/"><u>Resolving the Issue of a Missing Bluetooth Symbol in Windows 10</u></a></li>
<li><a href="https://fox-that.techidaily.com/reviving-access-a-guide-to-restoring-active-icloud-settings-in-ios-devices/"><u>Reviving Access: A Guide to Restoring Active iCloud Settings in iOS Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-tips-for-fixing-windows-error-code-31/"><u>Step-by-Step Troubleshooting Tips for Fixing Windows Error Code 31</u></a></li>
<li><a href="https://win-remarkable.techidaily.com/trasforma-rapidamente-i-tuoi-scatti-da-cr2-a-jpg-con-movavi/"><u>Trasforma Rapidamente I Tuoi Scatti Da CR2 a JPG Con Movavi</u></a></li>
<li><a href="https://win-webster.techidaily.com/1728486938019-windows-1110/"><u>Windows 11/10における画像ファイルのバックアップと同期手順</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

