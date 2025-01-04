---
title: "Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions"
date: 2024-12-28T18:35:53.192Z
updated: 2025-01-03T17:12:32.151Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions"
excerpt: "This Article Describes Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions"
thumbnail: https://thmb.techidaily.com/a9441716968b4b370228db8f919eac0889d914a97cb067222fedd44de8e1315f.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://facebook-record-videos.techidaily.com/new-best-video-apps-review-youtube-iphones-and-androids-for-2024/"><u>[New] Best Video Apps Review YouTube iPhones & Androids for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-the-ultimate-camera-selection-for-youtube-filmmakers/"><u>[New] In 2024, The Ultimate Camera Selection for YouTube Filmmakers</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-from-meta-to-omni-a-new-age-digital-odyssey-guide/"><u>[Updated] From Meta to Omni A New Age Digital Odyssey Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/device-unveiled-revolutionary-speed-boost-achieved/"><u>Device Unveiled: Revolutionary Speed Boost Achieved!</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-malfunctioning-usb-inputoutput-on-modern-windows-systems/"><u>Diagnosing and Repairing Malfunctioning USB Input/Output on Modern Windows Systems</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/fb-ad-forecast-2024-essentials-you-cant-ignore/"><u>FB Ad Forecast 2024 Essentials You Can't Ignore</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-fix-login-errors-caused-by-a-faulty-user-profile-service-on-windows/"><u>How to Correctly Fix Login Errors Caused by a Faulty User Profile Service on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-charging-windows-11-laptop-even-when-its-plugged-in-expert-tips-and-solutions/"><u>How to Fix a Non-Charging Windows 11 Laptop Even When It's Plugged In - Expert Tips & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-night-light-functionality-on-your-pc-running-windows-10-or-11/"><u>How to Restore Night Light Functionality on Your PC Running Windows 10 or 11</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-bypassing-common-drone-mistakes-with-this-essential-checklist/"><u>In 2024, Bypassing Common Drone Mistakes with This Essential Checklist</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-how-to-mass-download-tiktok-videos/"><u>In 2024, How To Mass Download TikTok Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/photo-perfection-erasing-with-ease-in-photoshop-for-2024/"><u>Photo Perfection Erasing with Ease in Photoshop for 2024</u></a></li>
<li><a href="https://techidaily.com/this-is-how-you-can-recover-deleted-pictures-from-motorola-moto-g24-by-fonelab-android-recover-pictures/"><u>This is how you can recover deleted pictures from Motorola Moto G24.</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unresponsive-function-keys-a-comprehensive-guide/"><u>Troubleshooting Unresponsive Function Keys: A Comprehensive Guide</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/1725286037701-winxdvd/"><u>WinXDVD 용인 기술 사전 학습: 코스를 안내하는 우수한 모듈화 팩</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

