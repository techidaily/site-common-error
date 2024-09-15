---
title: How to Fix Failed Windows 10 Version 1903 Updates Successfully
date: 2024-09-11T18:21:58.921Z
updated: 2024-09-15T15:16:53.835Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Failed Windows 10 Version 1903 Updates Successfully
excerpt: This Article Describes How to Fix Failed Windows 10 Version 1903 Updates Successfully
thumbnail: https://thmb.techidaily.com/aa9290eddc8ec2cc97b63ee765b598d95b8b81e9c2cca36d2d92b110af8ad1f5.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-complete-biomechanical-study-2023/"><u>[New] 2024 Approved Complete Biomechanical Study 2023</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-simplified-guide-integrating-snapchat-with-your-mac/"><u>[New] 2024 Approved Simplified Guide Integrating Snapchat with Your Mac</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-advanced-recording-strategies-for-effective-ppt-dissemination/"><u>[Updated] 2024 Approved Advanced Recording Strategies for Effective PPT Dissemination</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-vfx-artisan-suite/"><u>[Updated] VFX Artisan Suite</u></a></li>
<li><a href="https://common-error.techidaily.com/ensuring-smooth-audio-operations-on-win-1011/"><u>Ensuring Smooth Audio Operations on WIN 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-resolving-the-issue-of-nier-automata-crashing-in-windows-games/"><u>Expert Advice: Resolving the Issue of Nier: Automata Crashing in Windows Games</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-transfer-whatsapp-from-iphone-12-mini-to-other-iphone-11-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From iPhone 12 mini to other iPhone 11 devices? | Dr.fone</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/in-2024-crafting-animation-dynamic-bouncy-text-techniques/"><u>In 2024, Crafting Animation Dynamic, Bouncy Text Techniques</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-nubia-z50-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Nubia Z50 Ultra? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-troubleshooting-how-to-address-and-repair-error-code-grove/"><u>Mastering Windows Troubleshooting: How to Address and Repair Error Code Grove</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-activating-your-pcs-bluetooth-feature-on-windows-7-resolution-included/"><u>Step-by-Step Instructions: Activating Your PC's Bluetooth Feature on Windows 7 (Resolution Included)</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-pros-and-cons-of-using-a-premium-charger-a-closer-look-at-the-mophie-ac-powerstation/"><u>The Pros and Cons of Using a Premium Charger: A Closer Look at the Mophie AC Powerstation</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134237/18498" target="_top" id="2134237">
  <img src="//a.impactradius-go.com/display-ad/18498-2134237" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134237/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

