---
title: Expert Tips for Resolving Installation and Update Complications on Steam Gaming Services
date: 2024-12-27T17:28:07.590Z
updated: 2025-01-03T20:22:34.931Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips for Resolving Installation and Update Complications on Steam Gaming Services
excerpt: This Article Describes Expert Tips for Resolving Installation and Update Complications on Steam Gaming Services
thumbnail: https://thmb.techidaily.com/8c77eb31aaf68af03a18e4ba7fcc0097815c2ee3fb471579a2b65c14ccd90d40.jpg
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
<li><a href="https://common-error.techidaily.com/resolution-unlocking-pc-performance-eliminating-shell-induced-high-cpu-load-on-modern-oses/"><u>(Resolution) Unlocking PC Performance: Eliminating Shell-Induced High CPU Load on Modern OSes</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/udience-connection-mastering-the-art-of-viewpoint-based-youtube-reaction-vids-2-pov-method/"><u>[New] Audience Connection – Mastering the Art of Viewpoint-Based YouTube Reaction Vids (2 POV Method)</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-techniques-to-decrease-film-duration-on-macos-for-insta/"><u>[New] Techniques to Decrease Film Duration on macOS for Insta</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-on-the-spot-screen-savers-facebook-edition/"><u>[Updated] 2024 Approved On-the-Spot Screen Savers - Facebook Edition</u></a></li>
<li><a href="https://blog-min.techidaily.com/capture-decran-et-enregistreur-de-bureau-le-meilleur-pour-chrome-guide-top-des-extensions/"><u>Capture D'Écran Et Enregistreur De Bureau Le Meilleur Pour Chrome : Guide TOP Des Extensions</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-erratic-flickering-screens-in-windows-10-operating-system/"><u>Effective Fixes for Erratic Flickering Screens in Windows 10 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-strategies-to-repair-the-missing-msvcr110dll-error-on-your-pc-in-depth-guide/"><u>Expert Strategies to Repair the Missing msvcr110.dll Error on Your PC [In-Depth Guide]</u></a></li>
<li><a href="https://some-approaches.techidaily.com/flac-to-mp3aac-free-online-conversion-with-movavi-transcoder/"><u>FLAC to MP3/AAC Free Online Conversion with Movavi Transcoder</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-factory-unlock-your-telstra-apple-iphone-xs-by-drfone-ios/"><u>How To Factory Unlock Your Telstra Apple iPhone XS</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-online-visionaries-subscriber-play-button-triumphs/"><u>In 2024, Online Visionaries Subscriber, Play Button Triumphs</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/merge-videos-without-logos-best-7-software-options/"><u>Merge Videos Without Logos Best 7 Software Options</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-windows-11-continuous-restart-problem-with-simple-steps/"><u>Solve Your Windows 11 Continuous Restart Problem with Simple Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-addressing-microsofts-windows-10-update-to-may-2019-build-1903-setbacks/"><u>Step-by-Step Solutions for Addressing Microsoft's Windows 10 Update to May 2019 (Build 1903) Setbacks</u></a></li>
<li><a href="https://common-error.techidaily.com/the-key-to-unlocking-trustedinstaller-rights-how-to-modify-system-files-successfully/"><u>The Key to Unlocking TrustedInstaller Rights: How to Modify System Files Successfully</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aYH0B2HqcIM?si=3fkoG85L6hAeB4ok" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

