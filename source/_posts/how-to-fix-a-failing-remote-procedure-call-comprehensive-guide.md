---
title: How to Fix a Failing Remote Procedure Call - Comprehensive Guide
date: 2025-01-20T17:29:54.910Z
updated: 2025-01-22T20:01:37.132Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix a Failing Remote Procedure Call - Comprehensive Guide
excerpt: This Article Describes How to Fix a Failing Remote Procedure Call - Comprehensive Guide
thumbnail: https://thmb.techidaily.com/1015d95938322524d6bc75ebe9eaf3943bcb8d4c985b42fd4426ba3493876a07.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://extra-information.techidaily.com/new-2023-guide-to-affordable-laptop-dvd-players/"><u>[New] 2023 Guide to Affordable Laptop DVD Players</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-alt-tab-not-working/"><u>[Solved] Alt Tab Not Working</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-high-quality-recording-discovering-the-best-5-slow-video-cameras/"><u>[Updated] High-Quality Recording Discovering the Best 5 Slow Video Cameras</u></a></li>
<li><a href="https://blog-min.techidaily.com/apples-pursuit-of-healthy-digital-habits-why-vision-pro-doesnt-align/"><u>Apple's Pursuit of Healthy Digital Habits: Why Vision Pro Doesn't Align</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-intermittent-screen-lock-ups-in-computers/"><u>Diagnosing and Repairing Intermittent Screen Lock-Ups in Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-resolve-windows-file-corruption-issues-ws-10-and-11-edition/"><u>Effective Strategies to Resolve Windows File Corruption Issues - WS 10 & 11 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-updating-made-simple-overcoming-windows-0x80070652-mishap-with-ease/"><u>Error-Free Updating Made Simple: Overcoming Windows 0X80070652 Mishap with Ease</u></a></li>
<li><a href="https://some-skills.techidaily.com/evolving-smartphone-intelligence-how-oneplus-is-integrating-advanced-ai-capabilities/"><u>Evolving Smartphone Intelligence: How OnePlus Is Integrating Advanced AI Capabilities</u></a></li>
<li><a href="https://tech-haven.techidaily.com/from-beginner-to-expert-in-using-chatgpt-best-practices-and-tips/"><u>From Beginner to Expert in Using ChatGPT: Best Practices and Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-identify-malfunctioning-your-drivers-with-windows-device-manager-in-windows-7-by-drivereasy-guide/"><u>How to identify malfunctioning your drivers with Windows Device Manager in Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-video-not-detected-problem-on-your-screen-a-detailed-walkthrough/"><u>How to Resolve the 'Video Not Detected' Problem on Your Screen - A Detailed Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fix-handling-and-repairing-hamachi-errors-effectively/"><u>Master the Fix: Handling and Repairing Hamachi Errors Effectively</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210877269-9781612833156-out-of-body-experiences/"><u>Out of Body Experiences | Free Book</u></a></li>
<li><a href="https://some-tips.techidaily.com/preserve-the-fresh-look-of-your-iphone-13-the-must-have-accessories-you-need-to-know-about/"><u>Preserve the Fresh Look of Your iPhone 13: The Must-Have Accessories You Need to Know About</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-high-disk-consumption-of-microsoft-compatibility-telemetry-on-windows-10/"><u>Troubleshooting and Fixing High Disk Consumption of Microsoft Compatibility Telemetry on Windows 10</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LeKJBWb6Jhk?si=AnViizAPiIT1YCRA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

