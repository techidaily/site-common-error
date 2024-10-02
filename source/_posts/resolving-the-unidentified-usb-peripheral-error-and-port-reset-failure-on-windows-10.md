---
title: Resolving the Unidentified USB Peripheral Error and Port Reset Failure on Windows 10
date: 2024-09-30T03:04:24.117Z
updated: 2024-10-01T21:32:24.587Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving the Unidentified USB Peripheral Error and Port Reset Failure on Windows 10
excerpt: This Article Describes Resolving the Unidentified USB Peripheral Error and Port Reset Failure on Windows 10
thumbnail: https://thmb.techidaily.com/98bd5c521103adb9f2f398b8ea114e1ff33040cece118b77c428c885565f6981.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-enhancing-video-appeal-mac-thumbnails-tutorial-for-2024/"><u>[New] Enhancing Video Appeal Mac Thumbnails Tutorial for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-expert-pick-mics-for-youtube-entrepreneurs-for-2024/"><u>[Updated] Expert Pick Mics for YouTube Entrepreneurs for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-your-pc-gameplay-mastering-windows-11-performance-enhancements/"><u>Boost Your PC Gameplay: Mastering Windows 11 Performance Enhancements</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-your-computer-struggles-with-memory-in-windows-11/"><u>Effective Solutions for When Your Computer Struggles with Memory in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-repairing-a-non-functional-shift-key-successful-strategies-inside/"><u>Expert Advice on Repairing a Non-Functional Shift Key: Successful Strategies Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixed-how-to-resolve-the-silent-gameplay-issue-in-forza-horizon-4/"><u>Fixed: How to Resolve the Silent Gameplay Issue in Forza Horizon 4</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-resolve-microsoft-windows-camera-error-0xa00f4292/"><u>Fixing the Issue: Resolve Microsoft Windows Camera Error 0xA00F4292</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-teredo-cannot-establish-connection-error/"><u>How to Fix 'Teredo Cannot Establish Connection' Error</u></a></li>
<li><a href="https://howto.techidaily.com/how-to-flash-dead-realme-narzo-60x-5g-safely-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Flash Dead Realme Narzo 60x 5G Safely | Dr.fone</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-audience-retention-the-key-to-a-great-youtube-conclusion/"><u>In 2024, Audience Retention The Key to a Great YouTube Conclusion</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/protecting-privacy-during-youtube-to-mp4-conversion-for-2024/"><u>Protecting Privacy During YouTube-to-MP4 Conversion for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/ujrakezelest-igenylo-202n-kapodnyas-videotervezo-puska-a-legjobb-professzionalis-keszitmenyeket-gyujtoje/"><u>Újrakezelést Igénylő 202N Kapodnyás Vídeótervező Puska: A Legjobb Professzionális Készítményeket Gyüjtöje</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-top-vignette-apps-for-mobile-devices-free-and-premium-options/"><u>Updated In 2024, Top Vignette Apps for Mobile Devices Free and Premium Options</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1868586/19272" target="_top" id="1868586">
  <img src="//a.impactradius-go.com/display-ad/19272-1868586" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1868586/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

