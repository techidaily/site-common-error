---
title: Fixing the Non-Responsive Service Delay - Understanding and Correcting Error 1053
date: 2024-10-22T21:55:48.742Z
updated: 2024-10-24T20:38:34.979Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing the Non-Responsive Service Delay - Understanding and Correcting Error 1053
excerpt: This Article Describes Fixing the Non-Responsive Service Delay - Understanding and Correcting Error 1053
thumbnail: https://thmb.techidaily.com/924b42c675af7e54d265aac523b5dbe2839bad9cc4e31e018921bfcd577d0db7.jpg
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
<li><a href="https://instagram-clips.techidaily.com/updated-flip-the-script-crafting-unique-and-shareable-memes-on-social-platforms-for-2024/"><u>[Updated] Flip the Script Crafting Unique and Shareable Memes on Social Platforms for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-how-to-convert-youtube-to-mp3-in-3-ways-safe/"><u>[Updated] In 2024, How to Convert YouTube to MP3 in 3 Ways [Safe]</u></a></li>
<li><a href="https://win-howtos.techidaily.com/effortless-steps-for-a-clean-setup-of-windows-11-operating-system/"><u>Effortless Steps for a Clean Setup of Windows 11 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/end-the-annoyance-steps-to-cease-relentless-cursor-blindness/"><u>End the Annoyance: Steps to Cease Relentless Cursor Blindness</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-solutions-for-fixing-the-dota-2-error-changerenderingapi-error-202c/"><u>Fast Solutions for Fixing the Dota 2 Error - ChangeRenderingAPI (Error 202C)</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-device-path-not-found-issue-on-windows-complete-guide/"><u>Fixing the 'Device Path Not Found' Issue on Windows - Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-of-elevated-disk-use-by-compatibility-telemetry-in-windows-11-systems/"><u>Fixing the Issue of Elevated Disk Use by Compatibility Telemetry in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-easily-resolve-the-werfaultexe-blue-screen-of-death-errors/"><u>How to Easily Resolve the werFault.exe Blue Screen of Death Errors</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-oneplus-nord-n30-5g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, OnePlus Nord N30 5G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-the-complete-guide-to-oppo-a38-frp-bypass-everything-you-need-to-know-by-drfone-android/"><u>In 2024, The Complete Guide to Oppo A38 FRP Bypass Everything You Need to Know</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-samsung-galaxy-f15-5g-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Samsung Galaxy F15 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211335088-microsoft-surface-pro-4-touchscreen-malfunction-heres-how-to-get-it-working-again/"><u>Microsoft Surface Pro 4 Touchscreen Malfunction? Here's How to Get It Working Again!</u></a></li>
<li><a href="https://fox-blue.techidaily.com/mouthwatering-movies-how-to-make-your-food-videography-shine/"><u>Mouthwatering Movies How to Make Your Food Videography Shine</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-missing-dll-issue-for-steam-apps/"><u>Resolving Missing Dll Issue for Steam Apps</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-guide-addressing-the-coredll-missing-mistake/"><u>Step-by-Step Guide: Addressing the Core.dll Missing Mistake</u></a></li>
<li><a href="https://video-creation-software.techidaily.com/updated-2024-approved-mac-users-install-lumafusion-or-find-equivalent-video-editors/"><u>Updated 2024 Approved Mac Users Install Lumafusion or Find Equivalent Video Editors</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-users-heres-how-you-can-get-your-spacebar-working-again/"><u>Windows 10 Users! Here's How You Can Get Your Spacebar Working Again</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144288/7443" target="_top" id="2144288">
  <img src="//a.impactradius-go.com/display-ad/7443-2144288" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144288/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

