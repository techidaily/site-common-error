---
title: Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
date: 2024-12-19T17:33:43.886Z
updated: 2024-12-25T18:32:57.524Z
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
<li><a href="https://fox-helps.techidaily.com/new-in-2024-ultimate-gaming-experience-samsung-ue590-freesync-screen/"><u>[New] In 2024, Ultimate Gaming Experience Samsung UE590 FreeSync Screen</u></a></li>
<li><a href="https://win-tricks.techidaily.com/discover-top-proxmox-substitutes-strengthen-your-vms-safety-and-reliability/"><u>Discover Top Proxmox Substitutes: Strengthen Your VMs' Safety and Reliability</u></a></li>
<li><a href="https://fox-search.techidaily.com/exploring-the-spectrum-of-methodical-structured-teaching-mst-models/"><u>Exploring the Spectrum of Methodical Structured Teaching (MST) Models</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-failed-to-update-warframe-issue-a-comprehensive-guide/"><u>Fixing the 'Failed to Update Warframe' Issue – A Comprehensive Guide</u></a></li>
<li><a href="https://win-solutions.techidaily.com/fps-drop-problems-solved-for-resident-evil-village-on-personal-computers/"><u>FPS Drop Problems Solved for Resident Evil Village on Personal Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-updates-stalled-on-99-or-100-solved/"><u>How to Fix Windows Updates Stalled on 99 or 100% - Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-non-charging-devices-in-windows-7-and-10-systems/"><u>How to Troubleshoot Non-Charging Devices in Windows 7 and 10 Systems</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-low-end-pc-issues-in-windows-game-capture/"><u>Overcoming Low-End PC Issues in Window's Game Capture</u></a></li>
<li><a href="https://some-approaches.techidaily.com/seamless-productivity-boost-for-chromebook-users-using-updated-microsoft-office-suite-and-onedrive-syncing/"><u>Seamless Productivity Boost for Chromebook Users Using Updated Microsoft Office Suite & OneDrive Syncing</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-dealing-with-a-hanging-google-chrome-window/"><u>Solution Guide: Dealing with a Hanging Google Chrome Window</u></a></li>
<li><a href="https://games-able.techidaily.com/streaming-steam-games-androidios-devices-with-steam-link-tutorial/"><u>Streaming Steam Games: Android/iOS Devices with Steam Link Tutorial</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/209598745-9780285639485-the-lost-world-of-agharti/"><u>The Lost World of Agharti | Free Book</u></a></li>
<li><a href="https://win-howtos.techidaily.com/top-tips-and-solutions-for-fixing-a-non-responsive-ps4-microphone/"><u>Top Tips & Solutions for Fixing a Non-Responsive PS4 Microphone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-correcting-the-unrecoverable-error-1603-during-program-install/"><u>Troubleshooting Guide: Correcting the Unrecoverable Error 1603 During Program Install</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

