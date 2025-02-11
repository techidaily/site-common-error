---
title: Successfully Overcoming the Windows 11 KB5003696 (0X80240034) Bug Fix Guide
date: 2025-02-05T01:31:42.161Z
updated: 2025-02-10T19:25:31.274Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Successfully Overcoming the Windows 11 KB5003696 (0X80240034) Bug Fix Guide
excerpt: This Article Describes Successfully Overcoming the Windows 11 KB5003696 (0X80240034) Bug Fix Guide
thumbnail: https://thmb.techidaily.com/468b7a50fb837089e10cec38dd44fa01aaab4078b704b313fd2f69558ac117bb.png
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
<li><a href="https://common-error.techidaily.com/fixed-unusual-windows-stop-affects-cpu-usage/"><u>[FIXED] Unusual Windows Stop Affects CPU Usage</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-maximizing-4k-imaging-top-lens-choices-for-2024/"><u>[New] Maximizing 4K Imaging Top Lens Choices for 2024</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-2024-approved-best-practices-in-finding-quality-photo-and-video-banners/"><u>[Updated] 2024 Approved Best Practices in Finding Quality Photo & Video Banners</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-craft-cartoony-snaps-master-snapchats-anime-filters-guide/"><u>[Updated] 2024 Approved Craft Cartoony Snaps Master Snapchat’s Anime Filters Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/5-proven-fixes-for-restoring-touchscreen-responsiveness-in-windows-10/"><u>5 Proven Fixes for Restoring Touchscreen Responsiveness in Windows 10</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-motorola-g54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Motorola G54 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-windows-10s-restart-loop-expert-tips-for-smooth-operation/"><u>Beat Windows 10'S Restart Loop: Expert Tips for Smooth Operation</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211291289-constraint-c-use-a-template-like-see-event-historical-event-date-event-description-this-relates-to-economic-term-as-it-exemplifies/"><u>Constraint C: Use a Template Like See Event [Historical Event Date]: [Event Description]. This Relates to '[Economic Term]' As It Exemplifies</u></a></li>
<li><a href="https://techtrends.techidaily.com/ditch-the-star-studded-tips-why-cryptocurrency-wisdom-shouldnt-come-from-celebrities/"><u>Ditch the Star-Studded Tips: Why Cryptocurrency Wisdom Shouldn't Come From Celebrities</u></a></li>
<li><a href="https://technical-tips.techidaily.com/diy-guide-creating-unforgettable-memories-with-a-home-based-karaoke-extravaganza/"><u>DIY Guide: Creating Unforgettable Memories with a Home-Based Karaoke Extravaganza</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-secure-connection-failed-error-in-mozilla-firefox/"><u>How to Fix 'Secure Connection Failed' Error in Mozilla Firefox</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-0x80070490-windows-update-error-successfully/"><u>How to Fix the 0X80070490 Windows Update Error Successfully</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-the-ultimate-showdown-twitchs-challenge-to-youtubes-market/"><u>In 2024, The Ultimate Showdown Twitch's Challenge to YouTube's Market</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-common-problems-for-seamless-minecraft-multiplayer-lan-play/"><u>Overcoming Common Problems for Seamless Minecraft Multiplayer LAN Play</u></a></li>
<li><a href="https://win-awesome.techidaily.com/regain-access-to-your-lost-wechat-messages-using-icloud-restores-on-ios-devices-a-step-by-step-guide/"><u>Regain Access to Your Lost WeChat Messages Using iCloud Restores on iOS Devices - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-printer-driver-issues-how-to-fix-cannot-find-appropriate-driver/"><u>Resolving Windows Printer Driver Issues: How to Fix 'Cannot Find Appropriate Driver'</u></a></li>
<li><a href="https://change-location.techidaily.com/the-most-useful-tips-for-pokemon-go-ultra-league-on-vivo-x90s-drfone-by-drfone-virtual-android/"><u>The Most Useful Tips for Pokemon Go Ultra League On Vivo X90S | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iOVkXoUxLf4?si=QfC18T2cb5OkiaXo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

