---
title: Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial
date: 2024-12-14T01:06:46.093Z
updated: 2024-12-16T17:22:07.736Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial
excerpt: This Article Describes Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial
thumbnail: https://thmb.techidaily.com/b12c1a140a3344398be10869a2b844a6fc484f74ef7b38393e9a6d380bb9dbb1.jpg
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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-evaluating-on-demand-media-podcast-or-youtube/"><u>[New] 2024 Approved Evaluating On-Demand Media Podcast or YouTube?</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-free-lut-heaven-the-10-finest-and-accessible-resources-for-2024/"><u>[New] Free LUT Heaven The 10 Finest and Accessible Resources for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-switch-showdown-top-10-arcade-combat-classics/"><u>[New] Switch Showdown Top 10 Arcade Combat Classics</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-the-ultimate-guide-to-fb-video-calls-best-practices-for-2024/"><u>[Updated] The Ultimate Guide to FB Video Calls Best Practices for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-transform-voice-with-cloud-services-top-5-online-chromebook-audio-editors/"><u>[Updated] Transform Voice with Cloud Services Top 5 Online Chromebook Audio Editors</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-leading-caller-id-changers-with-enchanting-options/"><u>2024 Approved Leading Caller ID Changers with Enchanting Options</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210436458-arrow-key-malfunctions-heres-how-to-restore-functionality-on-your-keyboard/"><u>Arrow Key Malfunctions? Here's How to Restore Functionality on Your Keyboard</u></a></li>
<li><a href="https://extra-hints.techidaily.com/closer-look-techniques-for-minecraft-exploration-for-2024/"><u>Closer Look Techniques for Minecraft Exploration for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-techniques-making-your-laptops-touchpad-work-again/"><u>DIY Repair Techniques: Making Your Laptop's Touchpad Work Again</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-to-restore-lenovo-mouse-functionality-in-windows-os/"><u>Effective Remedies to Restore Lenovo Mouse Functionality in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202423799-effective-solutions-for-players-with-sims-aturated-and-her-sister-isabella-was-an-active-child-who-loved-to-play-soccer/"><u>Effective Solutions for Players with Sims Aturated, and Her Sister Isabella Was an Active Child Who Loved to Play Soccer.</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-how-to-resolve-a-non-functional-mac-mouse/"><u>Fixing Issues: How to Resolve a Non-Functional Mac Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-dell-bluetooth-keyboard-issues-a-step-by-step-guide/"><u>Fixing Your Dell Bluetooth Keyboard Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-cutting-edge-design-top-5-3d-intro-makers/"><u>In 2024, Cutting-Edge Design Top 5 3D Intro Makers</u></a></li>
<li><a href="https://games-able.techidaily.com/innovate-your-gaming-sphere-with-the-steam-workshop-method/"><u>Innovate Your Gaming Sphere with the Steam Workshop Method</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-strategies-to-tackle-the-windows-update-at-zero-percent-conundrum/"><u>Seamless Strategies to Tackle the Windows Update at Zero Percent Conundrum</u></a></li>
<li><a href="https://common-error.techidaily.com/securing-authorization-altering-files-with-trustedinstallers-approval/"><u>Securing Authorization: Altering Files with TrustedInstaller's Approval</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

