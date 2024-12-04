---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-11-29T00:15:23.955Z
updated: 2024-12-04T01:52:35.701Z
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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-top-7-essential-metaverse-tech-for-your-arsenal/"><u>[New] 2024 Approved Top 7 Essential Metaverse Tech for Your Arsenal</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-effortlessly-replay-videos-on-iphone-for-2024/"><u>[New] Effortlessly Replay Videos on iPhone for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-proven-approaches-to-amass-elite-copyright-free-imagery/"><u>[Updated] Proven Approaches to Amass Elite, Copyright-Free Imagery</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/79592734-2024-approved-dive-into-design-get-a-complimentary-set-of-50-banner-pieces/"><u>2024 Approved Dive Into Design Get a Complimentary Set of 50 Banner Pieces</u></a></li>
<li><a href="https://common-error.techidaily.com/best-fixes-for-audio-services-not-responding-windows-11/"><u>Best Fixes for Audio Services Not Responding Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/conquer-display-disturbances-resolve-surface-pro-screen-jitters-and-flashes/"><u>Conquer Display Disturbances: Resolve Surface Pro Screen Jitters and Flashes</u></a></li>
<li><a href="https://common-error.techidaily.com/critical-windows-update-features-now-fixed-and-operational/"><u>Critical Windows Update Features Now Fixed and Operational</u></a></li>
<li><a href="https://extra-hints.techidaily.com/elite-android-podcast-services/"><u>Elite Android Podcast Services</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-gaming-experience-with-fixed-xbox-one-console/"><u>Enhanced Gaming Experience with Fixed Xbox One Console</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11-sound-settings-how-to-restore-volume-control/"><u>Fixing Windows 11 Sound Settings: How To Restore Volume Control</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207374264-persistent-mouse-disconnection-woes-heres-how-to-keep-your-cursor-steady/"><u>Persistent Mouse Disconnection Woes? Here's How to Keep Your Cursor Steady</u></a></li>
<li><a href="https://program-issues.techidaily.com/seamless-gameplay-awaits-tackle-and-prevent-halo-infinites-pc-freezes-using-our-7-step-method/"><u>Seamless Gameplay Awaits: Tackle and Prevent Halo Infinite's PC Freezes Using Our 7-Step Method</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-the-problem-of-automatic-mouse-shifting/"><u>Tackling the Problem of Automatic Mouse Shifting</u></a></li>
<li><a href="https://common-error.techidaily.com/the-simplest-way-to-correct-the-windows-update-failure-error-0x80070652/"><u>The Simplest Way to Correct the Windows Update Failure (Error 0X80070652)</u></a></li>
<li><a href="https://win-solutions.techidaily.com/understanding-the-user-agreement-rules-and-regulations-for-the-movavicom-site/"><u>Understanding the User Agreement: Rules & Regulations for the MOVAVI.COM Site</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/4qA2pGQ5qmw?si=1mAA9WTi2Z5F7n6s" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

