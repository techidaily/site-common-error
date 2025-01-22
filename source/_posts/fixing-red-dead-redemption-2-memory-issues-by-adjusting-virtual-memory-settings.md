---
title: Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
date: 2025-01-16T19:40:38.372Z
updated: 2025-01-22T17:45:08.296Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
excerpt: This Article Describes Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
thumbnail: https://thmb.techidaily.com/be26802ef5bb50783815300426404d3fea7e0b5a3f7f648e31ee7c5865304f02.jpg
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
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-discovering-the-best-vr-camera-for-adventures/"><u>[New] 2024 Approved Discovering the Best VR Camera for Adventures</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-untangling-aerial-vehicles-a-guide-to-drones-operation/"><u>[New] Untangling Aerial Vehicles A Guide to Drones' Operation</u></a></li>
<li><a href="https://program-issues.techidaily.com/all-clear-la-noires-long-awaited-debut-arrives-on-windows-and-mac-pc/"><u>All Clear: L.A. Noire's Long-Awaited Debut Arrives on Windows and Mac PC</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-numeric-key-issues-a-comprehensive-guide/"><u>Diagnosing and Repairing Numeric Key Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-poco-x5-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Poco X5 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/monitor-trouble-a-detailed-walkthrough-for-correcting-no-input-errors/"><u>Monitor Trouble? A Detailed Walkthrough for Correcting No Input Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/speed-up-your-minecraft-experience-proven-fixes-to-get-rid-of-lag/"><u>Speed Up Your Minecraft Experience: Proven Fixes to Get Rid of Lag</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/streamlining-your-itunes-video-recordings/"><u>Streamlining Your iTunes Video Recordings</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-resolving-a-black-screen-problem-on-your-dell-notebook/"><u>The Ultimate Guide to Resolving a Black Screen Problem on Your Dell Notebook</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-10-enterprise-cloud-options-for-2024/"><u>Top 10 Enterprise Cloud Options for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-undetected-hard-drives-effective-strategies-solved/"><u>Troubleshooting Undetected Hard Drives – Effective Strategies [SOLVED]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

