---
title: KB4056892 Windows 10 Update Won’t Install [SOLVED]
date: 2025-01-23T23:10:19.267Z
updated: 2025-01-29T21:56:46.031Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes KB4056892 Windows 10 Update Won’t Install [SOLVED]
excerpt: This Article Describes KB4056892 Windows 10 Update Won’t Install [SOLVED]
thumbnail: https://thmb.techidaily.com/2a75585c706bda1c98b7ca78005e810cc4fa04565ec0bfaa1522a3466ddc9fcb.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/updated-beef-up-your-cgi-with-these-8-online-repositories-of-free-green-screens-and-clips-for-2024/"><u>[Updated] Beef up Your CGI with These 8 Online Repositories of FREE Green Screens and Clips for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-grasping-the-heart-of-narrative-design/"><u>[Updated] Grasping the Heart of Narrative Design</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-engaging-subjects-for-consistent-vlogging/"><u>[Updated] In 2024, Engaging Subjects for Consistent Vlogging</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-for-unfreezing-your-windows-tskbr-in-windows-10/"><u>Effective Techniques for Unfreezing Your Windows ˈtɑːskbɑːr in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-fallout-4-performance-slumps-expert-tips-and-tricks/"><u>Fixing Fallout 4 Performance Slumps - Expert Tips & Tricks</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-learn-to-capture-on-ipad-like-a-pro-effortlessly/"><u>In 2024, Learn To Capture on iPad Like a Pro - Effortlessly</u></a></li>
<li><a href="https://fox-helps.techidaily.com/innovative-methods-to-subtly-soften-audible-output-via-lumafusion/"><u>Innovative Methods to Subtly Soften Audible Output via Lumafusion</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-and-simple-solutions-stop-your-csgo-game-from-crashing-now/"><u>Quick and Simple Solutions: Stop Your CSGO Game From Crashing Now!</u></a></li>
<li><a href="https://data-wizards.techidaily.com/solving-emptying-macs-trash-problem/"><u>Solving Emptying Mac's Trash Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-restoring-a-failed-graphics-card-driver-system/"><u>Step-by-Step Solution for Restoring a Failed Graphics Card Driver System</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-ranking-smart-irrigation-controllers-of-2022-exploring-options-from-rachio-to-rainmachine-the-ultimate-comparison/"><u>Top-Ranking Smart Irrigation Controllers of 2022: Exploring Options From Rachio to RainMachine - The Ultimate Comparison</u></a></li>
<li><a href="https://facebook.techidaily.com/virtual-voyagers-discovering-false-profiles/"><u>Virtual Voyagers: Discovering False Profiles</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=LvxQhsEJoymsM2iZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

