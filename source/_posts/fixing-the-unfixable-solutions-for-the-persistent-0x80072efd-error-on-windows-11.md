---
title: "Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11"
date: 2025-01-09T17:03:02.890Z
updated: 2025-01-10T22:46:04.065Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11"
excerpt: "This Article Describes Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11"
thumbnail: https://thmb.techidaily.com/f99b0547d8a95f637159e251c131a6578ae71b255445af767dc74d5fd38281e0.jpg
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-streaming-beyond-streamlabs-a-comparative-study/"><u>[New] 2024 Approved Streaming Beyond StreamLabs A Comparative Study</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-taking-screenshot-on-windows-1087/"><u>[Updated] 2024 Approved Taking Screenshot on Windows 10/8/7</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-virtual-skirmishes-of-legends-top-7-total-war-battles/"><u>[Updated] 2024 Approved Virtual Skirmishes of Legends – Top 7 Total War Battles</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-silent-learners-guide-to-bypassing-edgenuity-videos-effortlessly/"><u>2024 Approved The Silent Learner's Guide to Bypassing Edgenuity Videos Effortlessly</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210867990-9780811749688-big-book-of-new-jersey-ghost-stories/"><u>Big Book of New Jersey Ghost Stories | Free Book</u></a></li>
<li><a href="https://win-rankings.techidaily.com/easy-steps-to-modify-pdf-files-using-google-drive-or-google-docs/"><u>Easy Steps to Modify PDF Files Using Google Drive or Google Docs</u></a></li>
<li><a href="https://common-error.techidaily.com/efficient-wmi-host-management-for-windows-11-upgrades/"><u>Efficient WMI Host Management for Windows 11 Upgrades</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-resolving-task-manager-not-responding-problems-successfully/"><u>Expert Advice: Resolving Task Manager Not Responding Problems Successfully</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-fix-oem-unlock-missing-on-xiaomi-redmi-k70-pro-by-drfone-android/"><u>How To Fix OEM Unlock Missing on Xiaomi Redmi K70 Pro?</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-sign-a-pdf-v17-document-with-digital-signature-app-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>How to sign a PDF v1.7 document with digital signature app</u></a></li>
<li><a href="https://common-error.techidaily.com/kodi-playback-troubles-heres-how-you-can-overcome-buffering-issues/"><u>Kodi Playback Troubles? Here's How You Can Overcome Buffering Issues!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-windows-update-issues-understanding-and-fixing-error-code-0x800705b4-on-windows-11/"><u>Resolve Windows Update Issues: Understanding and Fixing Error Code 0X800705b4 on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-handling-windows-error-1067-the-termination-issue-explained/"><u>Successfully Handling Windows Error 1067: The Termination Issue Explained</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/top-9-essential-factors-to-evaluate-when-purchasing-your-first-dashcam/"><u>Top 9 Essential Factors to Evaluate When Purchasing Your First Dashcam</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qbuund2HKOQ?si=NaGHqIrx8hSL7gWV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

