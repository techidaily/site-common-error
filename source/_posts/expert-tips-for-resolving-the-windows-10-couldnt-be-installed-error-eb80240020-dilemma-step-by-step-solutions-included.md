---
title: Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included
date: 2024-09-24T21:52:18.301Z
updated: 2024-10-02T04:29:00.515Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included
excerpt: This Article Describes Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included
thumbnail: https://thmb.techidaily.com/4509b58b3a9a19b95f97977ea395ec0191792aea55bdaf18f72a70f3772092da.jpg
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
<li><a href="https://desktop-recording.techidaily.com/2024-approved-secrets-to-proficient-ipad-screening/"><u>2024 Approved Secrets to Proficient iPad Screening</u></a></li>
<li><a href="https://win-solutions.techidaily.com/cant-use-utorrent-resolve-the-problem-with-our-7-top-tips/"><u>Can't Use Utorrent? Resolve the Problem With Our 7 Top Tips</u></a></li>
<li><a href="https://fox-access.techidaily.com/crafting-professional-images-using-photoshops-powerful-luts-for-2024/"><u>Crafting Professional Images Using Photoshop's Powerful LUTs for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminating-the-perpetual-grayscale-fixing-laptop-screen-issues-once-and-for-all/"><u>Eliminating the Perpetual Grayscale: Fixing Laptop Screen Issues Once and For All</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-sign-in-issue-caused-by-failed-user-profile-services-in-windows-10-and-11/"><u>Fixing the Sign-In Issue Caused by Failed User Profile Services in Windows 10 and 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-is-this-a-bug-or-intentional-edit-on-instagram/"><u>In 2024, Is This a Bug or Intentional Edit on Instagram?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-where-is-the-best-place-to-catch-dratini-on-lava-agni-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Where Is the Best Place to Catch Dratini On Lava Agni 2 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/mastering-playlist-conversion-5-preferred-tools-for-youtube-streams-for-2024/"><u>Mastering Playlist Conversion 5 Preferred Tools for YouTube Streams for 2024</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/most-popular-firefox-screenshots-and-recorders/"><u>Most Popular Firefox Screenshots & Recorders</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-insights-addressing-playback-errors-due-to-missing-sources-in-windows-environments/"><u>Solution Insights: Addressing 'Playback Errors Due to Missing Sources' In Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-of-unclear-text-in-windows-11-tips-and-tricks-for-a-sharper-display/"><u>Solving the Issue of Unclear Text in Windows 11 – Tips & Tricks for a Sharper Display</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-the-missing-binkw32dll-error-message/"><u>Step-by-Step Fix for the Missing binkw32.dll Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-fixes-for-xbox-ones-connection-woes-with-xbox-live/"><u>The Definitive Fixes for Xbox One's Connection Woes with Xbox Live</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044582/7443" target="_top" id="2044582">
  <img src="//a.impactradius-go.com/display-ad/7443-2044582" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044582/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

