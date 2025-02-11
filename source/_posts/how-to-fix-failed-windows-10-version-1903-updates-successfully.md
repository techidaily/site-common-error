---
title: How to Fix Failed Windows 10 Version 1903 Updates Successfully
date: 2025-02-07T01:34:05.823Z
updated: 2025-02-11T08:00:28.248Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Failed Windows 10 Version 1903 Updates Successfully
excerpt: This Article Describes How to Fix Failed Windows 10 Version 1903 Updates Successfully
thumbnail: https://thmb.techidaily.com/aa9290eddc8ec2cc97b63ee765b598d95b8b81e9c2cca36d2d92b110af8ad1f5.jpg
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
<li><a href="https://fox-links.techidaily.com/updated-mass-movement-mastery-the-drone-top-list-for-2024/"><u>[Updated] Mass Movement Mastery The Drone Top List for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-unleash-creativity-with-top-10-phone-apps-adding-stickers-to-images/"><u>[Updated] Unleash Creativity with Top 10 Phone Apps Adding Stickers to Images</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-dive-into-iphone-photo-magic-with-surface-mirror-tips/"><u>2024 Approved Dive Into iPhone Photo Magic with Surface Mirror Tips</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-professional-rapid-thumbnail-artistry-for-valorant-games/"><u>2024 Approved Professional Rapid Thumbnail Artistry for Valorant Games</u></a></li>
<li><a href="https://fox-helps.techidaily.com/assemble-visual-media-for-queue-upgrade-for-2024/"><u>Assemble Visual Media for Queue Upgrade for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/can-i-use-itools-gpx-file-to-catch-the-rare-pokemon-on-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>Can I use iTools gpx file to catch the rare Pokemon On Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/complete-guide-for-apple-iphone-14-plus-lock-screen-by-drfone-ios/"><u>Complete Guide For Apple iPhone 14 Plus Lock Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-overcoming-windows-10-not-shutdown-errors-on-pc-solved/"><u>Effective Solutions: Overcoming Windows 10 Not Shutdown Errors on PC – SOLVED!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-microsofts-print-to-pdf-issue-on-windows-11-a-step-by-step-guide/"><u>Fixing Microsoft's Print to PDF Issue on Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-repair-what-to-do-when-your-google-chrome-stops-responding/"><u>Guide to Repair: What to Do When Your Google Chrome Stops Responding</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-honor-x50i-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on Honor X50i online without jailbreak</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-right-click-problems-on-your-windows-10-mouse/"><u>Step by Step Guide: Repairing Right-Click Problems on Your Windows 10 Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-why-does-my-windows-10-computer-power-on-spontaneously/"><u>Troubleshooting Guide: Why Does My Windows 10 Computer Power On Spontaneously?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

