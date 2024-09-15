---
title: "Critical System Failure: Devices at End"
date: 2024-09-08T23:48:40.190Z
updated: 2024-09-14T19:03:43.913Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Critical System Failure: Devices at End"
excerpt: "This Article Describes Critical System Failure: Devices at End"
thumbnail: https://thmb.techidaily.com/07877b725aebcc26ce626860ff1aa31b598ca62f4a725eae923eeb25fe929021.jpg
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
<li><a href="https://facebook-clips.techidaily.com/new-the-art-of-audio-integration-in-online-journals-for-2024/"><u>[New] The Art of Audio Integration in Online Journals for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-essential-toolkit-how-to-use-obs-for-youtube-and-twitch-streaming/"><u>[Updated] The Essential Toolkit How to Use OBS for YouTube & Twitch Streaming</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/3-ways-to-track-apple-iphone-6s-without-them-knowing-drfone-by-drfone-virtual-ios/"><u>3 Ways to Track Apple iPhone 6s without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211076397-ce-34878-0-glitch-on-ps4-heres-how-you-can-easily-solve-it/"><u>CE-34878-0 Glitch on PS4? Here's How You Can Easily Solve It</u></a></li>
<li><a href="https://tech-haven.techidaily.com/coding-assistants-face-off-github-copilot-vs-chatgpt/"><u>Coding Assistants Face Off: GitHub Copilot VS. ChatGPT</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-windows-connectivity-issues-with-the-event-notifications-service/"><u>How to Repair Windows Connectivity Issues with the Event Notifications Service</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-explore-better-than-sharex-a-guide/"><u>In 2024, Explore Better Than ShareX - A Guide</u></a></li>
<li><a href="https://some-tips.techidaily.com/in-2024-upgrading-your-mp4s-integrating-premium-srt-sound/"><u>In 2024, Upgrading Your MP4s Integrating Premium SRT Sound</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-resolving-code-0xc1900208-during-your-windows-11-installation-fixed/"><u>Mastering the Fix: Resolving Code 0Xc1900208 During Your Windows 11 Installation [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-icue-when-your-computer-doesnt-recognize-hardware/"><u>Solution Steps for ICUE When Your Computer Doesn't Recognize Hardware</u></a></li>
<li><a href="https://common-error.techidaily.com/stay-on-top-of-your-battle-royale-essential-tips-to-avoid-unexpected-game-shutdowns/"><u>Stay on Top of Your Battle Royale: Essential Tips to Avoid Unexpected Game Shutdowns</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-resolving-the-diagnostic-policy-service-not-active-error/"><u>Successfully Resolving the 'Diagnostic Policy Service Not Active' Error</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/what-to-do-if-the-facebook-message-shows-its-you-in-this-video-in-2024/"><u>What To Do If the Facebook Message Shows It’s You in This Video, In 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

