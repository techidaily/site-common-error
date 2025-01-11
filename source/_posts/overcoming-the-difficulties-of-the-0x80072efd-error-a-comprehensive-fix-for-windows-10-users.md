---
title: "Overcoming the Difficulties of the 0X80072EFD Error: A Comprehensive Fix for Windows 10 Users"
date: 2025-01-06T16:38:32.572Z
updated: 2025-01-10T21:23:49.029Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Overcoming the Difficulties of the 0X80072EFD Error: A Comprehensive Fix for Windows 10 Users"
excerpt: "This Article Describes Overcoming the Difficulties of the 0X80072EFD Error: A Comprehensive Fix for Windows 10 Users"
thumbnail: https://thmb.techidaily.com/c74a6f4cbc3131991d1108cc0cd3851c9f4624d9f7132bc54e3318b3d6ad9b70.jpg
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
<li><a href="https://extra-guidance.techidaily.com/new-master-your-subtitles-with-top-10-free-converter-websites/"><u>[New] Master Your Subtitles with Top 10 Free Converter Websites</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-harmonizing-photos-with-musical-scores-for-2024/"><u>[Updated] Harmonizing Photos With Musical Scores for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-premiere-samsung-gear-vr-playlist/"><u>2024 Approved Premiere Samsung Gear VR Playlist</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-check-required-a-graphics-processor-with-directx-11-support-is-mandatory/"><u>Compatibility Check Required: A Graphics Processor with DirectX 11 Support Is Mandatory</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/gpt-intelligence-unscathed-adopted-by-openai/"><u>GPT Intelligence Unscathed: Adopted by OpenAI</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-use-snapchat-location-spoofer-to-protect-your-privacy-on-oppo-find-x7-drfone-by-drfone-virtual-android/"><u>How to use Snapchat Location Spoofer to Protect Your Privacy On Oppo Find X7? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/lose-not-the-tracking-of-your-sd-cards/"><u>Lose Not the Tracking of Your SD Cards!</u></a></li>
<li><a href="https://common-error.techidaily.com/navigate-with-ease-expert-tips-for-optimizing-file-explorer-in-windows-11/"><u>Navigate with Ease: Expert Tips for Optimizing File Explorer in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/random-reboots-on-windows-11-os/"><u>Random Reboots on Windows 11 OS</u></a></li>
<li><a href="https://common-error.techidaily.com/temporarily-unable-to-access-heres-how-to-restore-functionality-to-windows-smartscreen-filter/"><u>Temporarily Unable To Access? Here's How to Restore Functionality to Windows SmartScreen Filter</u></a></li>
<li><a href="https://extra-hints.techidaily.com/the-blueprint-of-writing-appealing-vlog-storylines/"><u>The Blueprint of Writing Appealing Vlog Storylines</u></a></li>
<li><a href="https://blog-min.techidaily.com/traspasando-fronteras-de-dvd-con-windows-como-hacer-que-tu-pelicula-sea-compatible-con-cualquier-reproductor-mediante-conversion-de-regiones-en-windows-1187156/"><u>Traspasando Fronteras De DVD Con Windows: Cómo Hacer Que Tu Película Sea Compatible Con Cualquier Reproductor Mediante Conversión De Regiones en Windows 11/8/7</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-from-zero-to-hero-mastering-xml-files-in-fcpx/"><u>Updated From Zero to Hero Mastering XML Files in FCPX</u></a></li>
<li><a href="https://win-exceptional.techidaily.com/why-does-my-system-keep-crashing-expert-tips-on-preventing-computer-freezes-by-yl-software/"><u>Why Does My System Keep Crashing? Expert Tips on Preventing Computer Freezes by YL Software</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-audio-troubles-how-to-repair-your-microphone/"><u>Windows 11 Audio Troubles: How to Repair Your Microphone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jnITUsxMz5s?si=ohwRVH6eWhVnC6Xf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

