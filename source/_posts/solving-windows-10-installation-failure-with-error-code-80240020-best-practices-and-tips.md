---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-12-05T18:36:10.259Z
updated: 2024-12-10T17:48:54.061Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
excerpt: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
thumbnail: https://thmb.techidaily.com/c616a530c3b86047af7fee8d712f3caf3cb46a3e47132cccfb907573c9519566.jpg
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
<li><a href="https://article-files.techidaily.com/new-in-2024-maximize-your-hd-vids-experience-the-ultimate-android-apps-list/"><u>[New] In 2024, Maximize Your Hd Vids Experience The Ultimate Android Apps List</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-settle-down-with-our-best-10-chill-titles/"><u>[Updated] Settle Down with Our Best 10 Chill Titles</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-infuse-rhythms-into-your-whatsapp-story/"><u>2024 Approved Infuse Rhythms Into Your WhatsApp Story</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-bugs-masterful-techniques-to-get-oddworld-soulstorm-running-on-windows-and-mac/"><u>Beat the Bugs! Masterful Techniques to Get Oddworld: Soulstorm Running on Windows and Mac</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/best-software-to-fix-and-repair-corrupt-mp4movavi-video-files-of-x9b-by-stellar-video-repair-mobile-video-repair/"><u>Best software to Fix and Repair Corrupt MP4,MOV,AVI video files of X9b</u></a></li>
<li><a href="https://win-community.techidaily.com/discovering-covert-surveillance-a-step-by-step-guide-to-detecting-undercover-spyware-on-your-android-device/"><u>Discovering Covert Surveillance: A Step-by-Step Guide to Detecting Undercover Spyware on Your Android Device</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-solutions-for-video-input-not-connected-error-on-your-display-device/"><u>Expert Solutions for Video Input Not Connected Error on Your Display Device</u></a></li>
<li><a href="https://common-error.techidaily.com/from-troubled-to-triumphant-the-end-of-easy-anti-cheat-problems-in-new-world-release/"><u>From Troubled to Triumphant: The End of Easy Anti-Cheat Problems in New World Release</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-msmpengexe-high-cpu-usage-on-windows-11-a-comprehensive-guide/"><u>How to Fix MsMpEng.exe High CPU Usage on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-persistent-pairing-problems-with-bluetooth-on-your-windows-10-device/"><u>How to Fix Persistent Pairing Problems with Bluetooth on Your Windows 10 Device</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-ios-meets-classic-play-best-ps2-game-emulators-reviewed/"><u>In 2024, IOS Meets Classic Play Best PS2 Game Emulators Reviewed</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/professional-guide-expertise-in-vimeo-video-logging-for-2024/"><u>Professional Guide Expertise in Vimeo Video Logging for 2024</u></a></li>
<li><a href="https://sound-issues.techidaily.com/restoring-your-windows-7-audio-a-comprehensive-fix-for-nonfunctional-headphones/"><u>Restoring Your Windows 7 Audio: A Comprehensive Fix for Nonfunctional Headphones</u></a></li>
<li><a href="https://common-error.techidaily.com/speeding-up-your-computer-simple-cleanup-techniques-for-better-speed/"><u>Speeding Up Your Computer: Simple Cleanup Techniques for Better Speed</u></a></li>
<li><a href="https://fox-sys.techidaily.com/step-by-step-guide-to-downloading-training-content-from-lynda-and-linkedin-learning/"><u>Step-by-Step Guide to Downloading Training Content From Lynda & LinkedIn Learning</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-for-enabling-bluetooth-connectivity-in-windows-1110/"><u>Step-by-Step Tutorial for Enabling Bluetooth Connectivity in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-fatal-dxgkrnl-bug-in-windows-multimedia-playback/"><u>Troubleshooting the Fatal Dxgkrnl Bug in Windows Multimedia Playback</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

