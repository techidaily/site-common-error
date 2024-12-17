---
title: "Resolved: Fixing 'System Cannot Allocate Enough Memory' Error"
date: 2024-12-10T17:44:16.005Z
updated: 2024-12-17T01:46:30.961Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing 'System Cannot Allocate Enough Memory' Error"
excerpt: "This Article Describes Resolved: Fixing 'System Cannot Allocate Enough Memory' Error"
thumbnail: https://thmb.techidaily.com/02857e9a5729a034df5799d80242303ce172ee6947ee8ec278b9096d58e3459c.jpg
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
<li><a href="https://instagram-video-recordings.techidaily.com/effortless-guide-to-going-live-on-instagram/"><u>Effortless Guide to Going Live on Instagram</u></a></li>
<li><a href="https://technical-tips.techidaily.com/fix-your-computers-fm2dll-error-quickly-and-easily/"><u>Fix Your Computer's Fm2#.dll Error Quickly and Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-navigate-past-a-frozen-setting-up-windows-process-now-fixed/"><u>How to Successfully Navigate Past a Frozen 'Setting Up Windows' Process (Now Fixed)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-nubia-z50s-pro-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Nubia Z50S Pro Device SIM</u></a></li>
<li><a href="https://vp-tips.techidaily.com/iphones-a-compreenas-guide-to-storing-and-sharing-gifs/"><u>IPhones A Compreenas Guide to Storing & Sharing GIFs</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210045863-issue-resolved-keyboard-now-responding-say-goodbye-to-typos/"><u>Issue Resolved: Keyboard Now Responding - Say Goodbye to Typos</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-error-with-print-driver-host-on-32-bit-software-discontinued/"><u>Resolved: Error with Print Driver Host on 32-Bit Software Discontinued</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restore-sound-input-in-windows-eboot-ultimate-guide-to-solving-pc-microphone-problems/"><u>Restore Sound Input in Windows Eboot - Ultimate Guide to Solving PC Microphone Problems</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/screencapture-evaluation-interface-for-2024/"><u>ScreenCapture Evaluation Interface for 2024</u></a></li>
<li><a href="https://win-hot.techidaily.com/1728493454670-sd/"><u>SDカードに保存している失われたデジタル写真を回復する手順</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-unresponsive-network-adapters-on-microsoft-operating-systems-windows-11-7/"><u>Solutions for Unresponsive Network Adapters on Microsoft Operating Systems (Windows 11, 7)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tip-semaphore-timeout-limit-resolved-say-goodbye-to-error-0x80070079/"><u>Troubleshooting Tip: Semaphore Timeout Limit Resolved, Say Goodbye to Error 0X80070079</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-transition-like-a-pro-top-10-premiere-pro-plugin-essentials/"><u>Updated In 2024, Transition Like a Pro Top 10 Premiere Pro Plugin Essentials</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

