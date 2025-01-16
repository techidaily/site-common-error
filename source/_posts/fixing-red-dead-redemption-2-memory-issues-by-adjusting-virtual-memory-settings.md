---
title: Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
date: 2025-01-13T16:19:11.989Z
updated: 2025-01-16T16:28:15.742Z
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
<li><a href="https://youtube-tips.techidaily.com/uilding-a-studio-quality-setup-at-home-for-2024/"><u>[New] Building a Studio-Quality Setup at Home for 2024</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/reative-video-ends-top-6-budget-friendly-options-in-2024/"><u>[New] Creative Video Ends Top 6 Budget-Friendly Options, In 2024</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-from-concept-to-creation-crafting-youtube-video-splits/"><u>[New] In 2024, From Concept to Creation Crafting YouTube Video Splits</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-comedic-craftsmanship-the-best-short-video-ideas-to-entertain-viewers/"><u>[Updated] 2024 Approved Comedic Craftsmanship The Best Short Video Ideas to Entertain Viewers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-free-end-credits-maker-the-1-video-closers-guide-in-2024/"><u>[Updated] Free End Credits Maker - The #1 Video Closers Guide, In 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-comprehensive-guide-to-screenshot-excellence/"><u>[Updated] The Comprehensive Guide to Screenshot Excellence</u></a></li>
<li><a href="https://common-error.techidaily.com/cranking-up-the-volume-on-fun-overcoming-silent-gameplay-in-forza-horizon-4/"><u>Cranking Up the Volume on Fun: Overcoming Silent Gameplay in Forza Horizon 4</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-stop-your-csgo-from-freezing-a-step-by-step-guide/"><u>Effortless Solutions: Stop Your CSGO From Freezing - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-repairing-your-oculus-devices-technical-glitches-this-year/"><u>Expert Guide: Repairing Your Oculus Device's Technical Glitches This Year</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-endless-loop-resolving-your-windows-11-or-10-continuous-reboot-issue/"><u>Fixing the Endless Loop: Resolving Your Windows 11 or 10 Continuous Reboot Issue</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/how-to-watch-facebook-live-in-2024/"><u>How to Watch Facebook Live, In 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/ipad-air-vs-ipad-pro-showdown-why-you-might-prefer-the-affordable-option/"><u>IPad Air Vs. IPad Pro Showdown: Why You Might Prefer the Affordable Option</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/milliseconds-and-megabits-deconstructing-20mb-videos-for-2024/"><u>Milliseconds & Megabits Deconstructing 20MB Videos for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unspecified-error-0x80004005-in-outlook-a-comprehensive-troubleshooting-manual/"><u>Overcoming 'Unspecified Error' (0X8^_^0004005) in Outlook: A Comprehensive Troubleshooting Manual</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-lack-of-sound-in-windows-11-a-comprehensive-fix-for-the-no-audio-device-error/"><u>Overcoming the Lack of Sound in Windows 11: A Comprehensive Fix for the No Audio Device Error</u></a></li>
<li><a href="https://common-error.techidaily.com/screen-fades-out-unsolved-mystery/"><u>Screen Fades Out: Unsolved Mystery</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repair-tips-when-your-usb-mouse-fails-on-laptop/"><u>Troubleshooting and Repair Tips When Your USB Mouse Fails on Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-windows-10-pc-reset-errors/"><u>Troubleshooting Tips for Windows 10 PC Reset Errors</u></a></li>
<li><a href="https://win-net.techidaily.com/webpage-missing-error-message-explanation/"><u>Webpage Missing - Error Message Explanation</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

