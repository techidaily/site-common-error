---
title: "How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
date: 2025-01-28T19:24:38.617Z
updated: 2025-01-29T17:22:22.400Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
excerpt: "This Article Describes How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/cbe88b794b4a33f4b9a69a7996ceb63e4276735d9be42e403798167c8028b648.jpg
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
<li><a href="https://youtube-docs.techidaily.com/n-2024-10-best-intro-maker-apps-for-iphone-and-android/"><u>[New] In 2024, 10 Best Intro Maker Apps for iPhone and Android</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-instagrams-vertical-vortex-sideways-media-mystery/"><u>[New] Instagram's Vertical Vortex Sideways Media Mystery</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-superior-selections-pro-webcam-stabilizers/"><u>[New] Superior Selections Pro Webcam Stabilizers</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-synchronizing-televisions-and-facebook-live-feeds/"><u>[New] Synchronizing Televisions and Facebook Live Feeds</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-in-2024-pixiz-essentials-from-stills-to-moving-images/"><u>[Updated] In 2024, Pixiz Essentials From Stills to Moving Images</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-unveiling-the-illusion-how-genuine-growth-is-stifled-by-shams/"><u>2024 Approved Unveiling the Illusion How Genuine Growth Is Stifled by Shams</u></a></li>
<li><a href="https://howto.techidaily.com/7-fixes-for-unfortunately-phone-has-stopped-on-motorola-moto-g34-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Fixes for Unfortunately, Phone Has Stopped on Motorola Moto G34 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-non-running-diagnostic-services/"><u>Effective Solutions for Non-Running Diagnostic Services</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effortless-dvd-conversion-with-winx-dvd-ripper-platinum-on-windows-11-experience-unmatched-32x-speeds-and-versatile-format-support/"><u>Effortless DVD Conversion with WinX DVD Ripper Platinum on Windows 11 – Experience Unmatched 32X Speeds and Versatile Format Support!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-address-and-mend-a-broken-logitech-mouse-scroll-wheel/"><u>How To Correctly Address and Mend a Broken Logitech Mouse Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208891226-how-we-overcame-the-windows-updates-issues-solutions-applied/"><u>How We Overcame the Windows Updates Issues – Solutions Applied!</u></a></li>
<li><a href="https://fox-direct.techidaily.com/in-2024-essential-tips-for-navigating-zoom-on-win11-systems/"><u>In 2024, Essential Tips for Navigating Zoom on Win11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-shortcuts-how-to-restore-functionality-for-shiftpluswindowspluss-in-w10w11/"><u>Mastering Windows Shortcuts: How to Restore Functionality for Shift+Windows+S in W10/W11</u></a></li>
<li><a href="https://common-error.techidaily.com/personalized-treatment-plans-based-on-genomic-profiling-are-becoming-the-standard-in-lung-cancer-care/"><u>Personalized Treatment Plans Based on Genomic Profiling Are Becoming the Standard in Lung Cancer Care</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-restoring-touchpad-scrolling-functionality/"><u>Troubleshooting Tips: Restoring Touchpad Scrolling Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-unfreeze-the-windows-10-taskbar-efficiently/"><u>Ultimate Guide: Unfreeze the Windows 10 Taskbar Efficiently</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HaM818fFKXQ?si=ZZLA4lFSHSgCpSE0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

