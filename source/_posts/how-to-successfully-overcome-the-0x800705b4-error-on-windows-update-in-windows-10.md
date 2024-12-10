---
title: How to Successfully Overcome the 0X800705B4 Error on Windows Update in Windows 10
date: 2024-12-09T18:16:36.385Z
updated: 2024-12-10T20:31:47.774Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Overcome the 0X800705B4 Error on Windows Update in Windows 10
excerpt: This Article Describes How to Successfully Overcome the 0X800705B4 Error on Windows Update in Windows 10
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
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
<li><a href="https://instagram-clips.techidaily.com/new-in-2024-reel-relationships-establishing-a-strong-social-media-presence-with-memes/"><u>[New] In 2024, Reel Relationships Establishing a Strong Social Media Presence with Memes</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-non-competitive-front-row-fun-ranking-the-top-ten/"><u>[Updated] In 2024, Non-Competitive Front Row Fun Ranking the Top Ten</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-unraveling-sharex-professional-perspectives-and-picks/"><u>2024 Approved Unraveling ShareX Professional Perspectives & Picks</u></a></li>
<li><a href="https://techidaily.com/complete-tutorial-for-htc-u23-pro-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>Complete Tutorial for HTC U23 Pro Hard Reset | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/detailed-guide-of-ispoofer-for-pogo-installation-on-asus-rog-phone-8-drfone-by-drfone-virtual-android/"><u>Detailed guide of ispoofer for pogo installation On Asus ROG Phone 8 | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/expert-component-choices-for-gamers-and-techies-advice-from-toms-hardware/"><u>Expert Component Choices for Gamers and Techies - Advice From Tom's Hardware</u></a></li>
<li><a href="https://common-error.techidaily.com/green-glitch-of-nba-2k21-its-now-a-thing-of-the-past/"><u>Green Glitch of NBA 2K21? It's Now a Thing of the Past!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-logitech-keyboard-recognition-problems-in-windows-10-systems/"><u>How to Fix Logitech Keyboard Recognition Problems in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-solutions-for-issues-in-pdf-printing/"><u>Immediate Solutions for Issues in PDF Printing</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-lock-screen-settings-how-to-enable-and-disable-on-samsung-galaxy-s23-fe-by-drfone-android/"><u>Mastering Lock Screen Settings How to Enable and Disable on Samsung Galaxy S23 FE</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-a-laptop-battery-that-wont-charge/"><u>Quick Solutions for a Laptop Battery That Won't Charge</u></a></li>
<li><a href="https://common-error.techidaily.com/top-strategies-for-handling-werfaultexe-issues-in-windows-systems/"><u>Top Strategies for Handling werfault.exe Issues in Windows Systems</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-non-timed-lock-screen-issue-in-windows/"><u>Troubleshooting Non-Timed Lock Screen Issue in Windows</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LW6wNx3XAj8?si=VaIuFIIx8MM_RhUR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

