---
title: Step-by-Step Solution for Corrupting Windows 10 Update Error 0Xc1900208
date: 2024-12-11T21:03:52.365Z
updated: 2024-12-17T01:40:58.740Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for Corrupting Windows 10 Update Error 0Xc1900208
excerpt: This Article Describes Step-by-Step Solution for Corrupting Windows 10 Update Error 0Xc1900208
thumbnail: https://thmb.techidaily.com/a01c874bf96001212de2ae31da3cf8c01bb85a8c094ea57055633d7f6bda8cb6.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://common-error.techidaily.com/bypassing-glitches-a-guide-to-correcting-windows-11-touchscreen-malfunctions-in-5-ways/"><u>Bypassing Glitches: A Guide to Correcting Windows 11 Touchscreen Malfunctions in 5 Ways</u></a></li>
<li><a href="https://win11.techidaily.com/enabling-or-disabling-data-tracking-on-wi-fi-connection-in-windows-11/"><u>Enabling or Disabling Data Tracking on Wi-Fi Connection in Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/enhance-your-online-presence-with-manycam-top-tier-video-effects-and-fake-cam-solutions/"><u>Enhance Your Online Presence with ManyCam - Top-Tier Video Effects & Fake Cam Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-corrective-measures-for-when-your-laptop-keys-dont-work/"><u>Expert Advice: Corrective Measures for When Your Laptop Keys Don’t Work</u></a></li>
<li><a href="https://tech-haven.techidaily.com/exploring-superior-functionalities-chatgpt-on-pc-beats-website-experience/"><u>Exploring Superior Functionalities: ChatGPT on PC Beats Website Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-with-your-aoc-display-screen-in-compatibility-mode-for-windows-11/"><u>Fixing Issues with Your AOC Display Screen in Compatibility Mode for Windows 11</u></a></li>
<li><a href="https://change-location.techidaily.com/home-button-not-working-on-vivo-v30-here-are-real-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Home Button Not Working on Vivo V30? Here Are Real Fixes | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/leverage-vimeo-for-wider-viewership-for-2024/"><u>Leverage Vimeo for Wider Viewership for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-resolving-lenovo-mouse-pad-problems-across-multiple-windows-environments-xpvista/"><u>Mastering the Fix: Resolving Lenovo Mouse Pad Problems Across Multiple Windows Environments (XP/Vista)</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/melody-matrix-tips-and-tricks-for-social-media-sounds-for-2024/"><u>Melody Matrix Tips and Tricks for Social Media Sounds for 2024</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-mastering-avi-file-editing-easy-ways-to-trim-cut-and-split-videos-2023-update-for-2024/"><u>New Mastering AVI File Editing Easy Ways to Trim, Cut, and Split Videos (2023 Update) for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/optimizing-vimeo-playback-speed-for-2024/"><u>Optimizing Vimeo Playback Speed for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-10s-freezing-hurdle-during-initial-boot-sequence/"><u>Overcoming Windows 10'S Freezing Hurdle During Initial Boot Sequence</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-steps-to-resolve-lag-issues-in-hearthstone/"><u>Simple Steps to Resolve Lag Issues in Hearthstone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solving-audio-not-playing-issues-for-windows-operating-systems-step-by-step-guide/"><u>Solving 'Audio Not Playing' Issues for Windows Operating Systems: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-11-update-error-code-0x800f0922-top-8-methods/"><u>Solving Windows 11 Update Error CODE 0X800f0922: Top 8 Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooted-voltage-spike-on-switch-entry/"><u>Troubleshooted: Voltage Spike on Switch Entry</u></a></li>
<li><a href="https://fox-access.techidaily.com/unveiling-the-most-innovative-metaverse-visors-and-wearables-for-2024/"><u>Unveiling the Most Innovative Metaverse Visors & Wearables for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-update-failed-to-install-solved/"><u>Windows 11 Update Failed to Install [SOLVED]</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

