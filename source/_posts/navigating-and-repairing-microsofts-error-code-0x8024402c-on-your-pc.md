---
title: Navigating and Repairing Microsoft's Error Code 0X8024402c on Your PC
date: 2024-10-05T18:19:04.148Z
updated: 2024-10-13T04:36:08.013Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Navigating and Repairing Microsoft's Error Code 0X8024402c on Your PC
excerpt: This Article Describes Navigating and Repairing Microsoft's Error Code 0X8024402c on Your PC
thumbnail: https://thmb.techidaily.com/a1aef9ac34b30a9b89c44b4090cc093f70a661d81b3d63d1adb081d4443463d3.jpg
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-elevate-your-shots-vloggers-guide-to-the-9-finest-camera-gadgets/"><u>[New] 2024 Approved Elevate Your Shots Vlogger's Guide to the 9 Finest Camera Gadgets</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-technical-insights-for-superior-ppt-recording-quality/"><u>[New] Technical Insights for Superior PPT Recording Quality</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-honoring-creativity-ultimate-otu-collection/"><u>[Updated] Honoring Creativity Ultimate OTU Collection</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-switching-on-windows-11s-adaptive-hdr-option/"><u>2024 Approved Switching On Windows 11'S Adaptive HDR Option</u></a></li>
<li><a href="https://extra-resources.techidaily.com/assemble-visual-media-for-queue-upgrade/"><u>Assemble Visual Media for Queue Upgrade</u></a></li>
<li><a href="https://program-issues.techidaily.com/boost-your-gaming-experience-fixing-the-division-2-frame-rate-issues/"><u>Boost Your Gaming Experience: Fixing The Division 2 Frame Rate Issues</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-do-nokia-c110-screen-sharing-drfone-by-drfone-android/"><u>How To Do Nokia C110 Screen Sharing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-windows-11-update-error-code-0x80240034/"><u>How To Fix The Windows 11 Update Error Code: 0X80240034</u></a></li>
<li><a href="https://fox-zaraz.techidaily.com/is-your-google-drive-vulnerable-to-ransomware-insights-from-malwarefox/"><u>Is Your Google Drive Vulnerable to Ransomware: Insights From MalwareFox</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-10-unable-to-install-problem-with-code-80240020-guide/"><u>Overcoming Window's 10 Unable to Install Problem with Code #80240020 [Guide]</u></a></li>
<li><a href="https://facebook.techidaily.com/tech-based-resetting-facebooks-response-to-user-data-breaches/"><u>Tech-Based Resetting - Facebook's Response to User Data Breaches</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-methods-to-repair-a-malfunctioning-touchscreen-on-windows-11/"><u>Top 5 Methods to Repair a Malfunctioning Touchscreen on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-function-keys-on-your-keyboard/"><u>Troubleshooting Non-Responsive Function Keys on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-correcting-the-rpc-service-failure-on-windows-computers/"><u>Troubleshooting Tips for Correcting the RPC Service Failure on Windows Computers</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082542/7443" target="_top" id="2082542">
  <img src="//a.impactradius-go.com/display-ad/7443-2082542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

