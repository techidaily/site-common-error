---
title: "[Solved] Error Code 0X80073cf9 in Windows 10 Store"
date: 2024-12-10T19:07:13.608Z
updated: 2024-12-16T18:21:56.665Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes [Solved] Error Code 0X80073cf9 in Windows 10 Store
excerpt: This Article Describes [Solved] Error Code 0X80073cf9 in Windows 10 Store
thumbnail: https://thmb.techidaily.com/ee549b864de6102ff48675fa7bf1a7613a21bc32bbc71908950ecf0a34fbb345.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://fox-friendly.techidaily.com/new-navigating-the-world-of-audio-with-apods/"><u>[New] Navigating the World of Audio with APods</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-achieve-perfect-views-with-aspect-ratio-knowledge-on-youtube-for-2024/"><u>[Updated] Achieve Perfect Views with Aspect Ratio Knowledge on YOUTUBE for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-android-sound-recording-without-root-simple-guide/"><u>[Updated] In 2024, Android Sound Recording Without Root [Simple Guide]</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/updated-navigating-the-clouds-and-crowds-stream-from-dji-to-facebook/"><u>[Updated] Navigating the Clouds and Crowds Stream From DJI to Facebook</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/2024-approved-community-cinema-collector/"><u>2024 Approved Community Cinema Collector</u></a></li>
<li><a href="https://common-error.techidaily.com/bring-out-the-hidden-touchpad-showcase-it/"><u>Bring Out the Hidden Touchpad, Showcase It</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-repairing-the-missing-binkw32dll-error-on-your-computer/"><u>Comprehensive Guide: Repairing the Missing binkw32.dll Error on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-mastering-the-art-of-rebooting-your-keyboard/"><u>Easy Steps: Mastering the Art of Rebooting Your Keyboard</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/elevate-videos-with-gif-a-simple-guide-for-vimeo-creators-for-2024/"><u>Elevate Videos with GIF A Simple Guide for Vimeo Creators for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203244022-fixing-call-of-duty-wwii-error-4220-heres-your-complete-troubleshooting-solution/"><u>Fixing Call of Duty WWII Error 4220? Here's Your Complete Troubleshooting Solution!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-oneplus-11r-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On OnePlus 11R? | Dr.fone</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-free-video-editing-gems-top-picks-for-online-creators-for-2024/"><u>New Free Video Editing Gems Top Picks for Online Creators for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-astro-a40-microphone-clear-instructions-and-solutions/"><u>Revive Your Astro A40 Microphone: Clear Instructions and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-restoring-corrupted-files-in-windows-10-and-11/"><u>Step-by-Step Tutorial: Restoring Corrupted Files in Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-solution-to-overcome-livekernelevent-error-117/"><u>The Ultimate Solution to Overcome LiveKernelEvent Error 117</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-surface-pro-4-camera-issues-in-windows-10/"><u>Troubleshooting Guide: Fixing Surface Pro 4 Camera Issues in Windows 10</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210865164-9781960466075-koloda-taro-lenorman-znachenie/"><u>Колода Таро Ленорман Значение | Free Book</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

