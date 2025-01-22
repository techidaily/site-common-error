---
title: "Coding Stalled: Command Refused"
date: 2025-01-17T18:48:19.643Z
updated: 2025-01-22T16:19:46.279Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Coding Stalled: Command Refused"
excerpt: "This Article Describes Coding Stalled: Command Refused"
thumbnail: https://thmb.techidaily.com/96d460ad778074a93b63a308714d13a6fb98bd643d60a66bb372b318524a5b70.jpg
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
<li><a href="https://youtube-blog.techidaily.com/024-approved-navigating-online-content-the-merits-of-youtubes-ad-free-alternative/"><u>[New] 2024 Approved Navigating Online Content The Merits of YouTube's Ad-Free Alternative</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-in-2024-youtube-alternative-free-conversion-of-fb-videos-to-mp4-format-hd-quality/"><u>[New] In 2024, YouTube Alternative Free Conversion of FB Videos to MP4 Format (HD Quality)</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-meme-mastery-money-making-the-financial-figures-of-a-video-virtuoso-for-2024/"><u>[Updated] Meme Mastery Money-Making The Financial Figures of a Video Virtuoso for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solution-eliminate-unwanted-cursor-blind-spots-for-a-smoother-experience/"><u>Effective Solution: Eliminate Unwanted Cursor Blind Spots for a Smoother Experience</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/edisable-comments-a-youtube-instructional-for-2024/"><u>Enable/Disable Comments A YouTube Instructional for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/exploring-the-dual-capabilities-of-fitbit-versa-2-your-guide-to-health-monitoring-and-smartwatch-integration/"><u>Exploring the Dual Capabilities of Fitbit Versa 2 – Your Guide to Health Monitoring and Smartwatch Integration</u></a></li>
<li><a href="https://sound-issues.techidaily.com/get-your-windows-11-audio-back-a-step-by-step-fix-for-broken-speakers/"><u>Get Your Windows 11 Audio Back: A Step-by-Step Fix for Broken Speakers</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-failed-status-on-your-latest-warframe-game-upgrade/"><u>How to Fix 'Failed' Status on Your Latest Warframe Game Upgrade</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-a-step-by-step-guide-to-getting-the-most-out-of-your-mobizen-experience/"><u>In 2024, A Step-by-Step Guide to Getting the Most Out of Your Mobizen Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-troubles-learn-to-resolve-inactive-letter-buttons-on-win-1011-systems/"><u>Keyboard Troubles? Learn to Resolve Inactive Letter Buttons on Win 10/11 Systems</u></a></li>
<li><a href="https://youtube-help.techidaily.com/making-money-with-videos-strategies-for-the-aspiring-vlogger-for-2024/"><u>Making Money with Videos Strategies for the Aspiring Vlogger for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolve-the-windows-update-error-code-0x80070652/"><u>Quick Solutions: Resolve the Window's Update Error Code 0X80070652</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/top-ranking-desktop-speaker-that-outshines-logitech-and-pioneer-unveiled-on-zdnet/"><u>Top-Ranking Desktop Speaker That Outshines Logitech & Pioneer Unveiled on ZDNet</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-shadowplay-setup-failures-on-nvidia-gpus/"><u>Troubleshooting Tips for Fixing ShadowPlay Setup Failures on Nvidia GPUs</u></a></li>
<li><a href="https://common-error.techidaily.com/yac553-yamahaaturbosound-ii-sound-module-based-on-the-ymf794cymu794c-dsp-plus-midi-synthesader-plus-codec-and-256-mb-of-spiram-for-sample-storage-instead-of18/"><u>YAC553 - Yamaha'aturboSound II Sound Module Based on the YMF794C/YMU794C (DSP + MIDI Synthesader + Codec) and 256 MB of SPIRAM for Sample Storage Instead of ROM. It Also Includes a Second Audio Input Connector</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

