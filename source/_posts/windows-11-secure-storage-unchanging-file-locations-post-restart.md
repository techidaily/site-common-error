---
title: "Windows 11 Secure Storage: Unchanging File Locations Post Restart"
date: 2024-10-30T03:15:37.533Z
updated: 2024-11-05T06:27:28.830Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 11 Secure Storage: Unchanging File Locations Post Restart"
excerpt: "This Article Describes Windows 11 Secure Storage: Unchanging File Locations Post Restart"
thumbnail: https://thmb.techidaily.com/8cc2f26346852b595fe32553f266efaeb26b116a663fa0800cea00c3335313c9.png
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
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-unleash-your-creative-edge-with-adjustable-story-videos/"><u>[New] 2024 Approved Unleash Your Creative Edge with Adjustable Story Videos</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/n-2024-streamlined-approach-to-validate-your-yt-identity/"><u>[New] In 2024, Streamlined Approach to Validate Your YT Identity</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-top-10-high-definition-gaming-laptops-reviewed-for-2024/"><u>[New] Top 10 High-Definition Gaming Laptops Reviewed for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-in-2024-public-melodies-for-calmness/"><u>[Updated] In 2024, Public Melodies for Calmness</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-revive-freezing-mobile-videos-in-chrome-and-firefox-for-2024/"><u>[Updated] Revive Freezing Mobile Videos in Chrome and Firefox for 2024</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728484480148-windows-pciphone/"><u>如何復原已經永久移除的照片：選擇Windows PC和iPhone手機的易行指南</u></a></li>
<li><a href="https://common-error.techidaily.com/advanced-fixes-for-the-infamous-fatal-error-that-plagues-halo-4-ue4/"><u>Advanced Fixes for the Infamous Fatal Error That Plagues Halo 4 UE4</u></a></li>
<li><a href="https://common-error.techidaily.com/apex-legends-cheating-glitch-solution-overcome-with-ease/"><u>Apex Legends Cheating Glitch Solution - Overcome with Ease</u></a></li>
<li><a href="https://extra-hints.techidaily.com/compose-your-cinematic-storytelling-add-melodies-to-iphone-videos-without-cost/"><u>Compose Your Cinematic Storytelling – Add Melodies to iPhone Videos Without Cost</u></a></li>
<li><a href="https://fox-glue.techidaily.com/comprehensive-study-hero4-black-mechanics-for-2024/"><u>Comprehensive Study Hero4 Black Mechanics for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-not-working-fix-connection-errors-to-the-game-servers-here/"><u>Destiny 2 Not Working? Fix Connection Errors to the Game Servers Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-guidance-navigating-and-fixing-issues-with-file-explorer-in-windows-11/"><u>Effortless Guidance: Navigating and Fixing Issues with File Explorer in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/livekernelevent-bug-117-comprehensive-fixing-techniques-unveiled/"><u>LiveKernelEvent Bug #117 - Comprehensive Fixing Techniques Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-fixing-crc-related-data-errors-effectively/"><u>Solutions for Fixing CRC-Related Data Errors Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-symbol-a-guide-to-solving-non-functional-special-characters/"><u>Troubleshooting the '@' Symbol: A Guide to Solving Non-Functional Special Characters</u></a></li>
<li><a href="https://howto.techidaily.com/what-to-do-if-google-play-services-keeps-stopping-on-honor-x50-gt-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>What to Do if Google Play Services Keeps Stopping on Honor X50 GT | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484945/16446" target="_top" id="1484945">
  <img src="//a.impactradius-go.com/display-ad/16446-1484945" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484945/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

