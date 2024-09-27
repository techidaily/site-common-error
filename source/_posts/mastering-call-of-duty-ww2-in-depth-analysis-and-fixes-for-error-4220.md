---
title: "Mastering Call of Duty WW2: In-Depth Analysis and Fixes for Error 4220"
date: 2024-09-25T00:29:07.443Z
updated: 2024-09-26T17:04:15.894Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Call of Duty WW2: In-Depth Analysis and Fixes for Error 4220"
excerpt: "This Article Describes Mastering Call of Duty WW2: In-Depth Analysis and Fixes for Error 4220"
thumbnail: https://thmb.techidaily.com/0d605cbff29d9fac95ea636e3f1dc6722b73dcac2e7b43e02dacf71b94afcc8e.jpg
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
<li><a href="https://fox-glue.techidaily.com/new-quick-start-guide-easy-steps-for-effective-video-calling-on-zoom-for-2024/"><u>[New] Quick Start Guide Easy Steps for Effective Video Calling on Zoom for 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-free-templates-for-dynamic-youtube-channel-closures-for-2024/"><u>[Updated] Free Templates for Dynamic YouTube Channel Closures for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-how-to-leverage-phantoms-retrograde-footage-tech-for-2024/"><u>[Updated] How to Leverage Phantom’s Retrograde Footage Tech for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/discover-the-most-beloved-disney-masterpieces-your-definitive-list-and-official-ways-to-watchdownload/"><u>Discover the Most Beloved Disney Masterpieces: Your Definitive List and Official Ways to Watch/Download</u></a></li>
<li><a href="https://some-guidance.techidaily.com/discover-the-ultimate-selection-of-no-cost-tools-for-apples-macos-users/"><u>Discover the Ultimate Selection of No-Cost Tools for Apple's macOS Users</u></a></li>
<li><a href="https://screen-capture.techidaily.com/easy-steps-to-personalize-google-meet-on-laptops-and-mobile-devices-for-2024/"><u>Easy Steps to Personalize Google Meet on Laptops & Mobile Devices for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-getting-your-touchpad-scroll-back-in-action-a-step-by-step-fix/"><u>Guide to Getting Your Touchpad Scroll Back in Action: A Step-by-Step Fix</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlock-vivo-y100a-phone-password-without-factory-reset-full-guide-here-by-drfone-android/"><u>In 2024, Unlock Vivo Y100A Phone Password Without Factory Reset Full Guide Here</u></a></li>
<li><a href="https://common-error.techidaily.com/managing-system-resources-on-windows-10/"><u>Managing System Resources on Windows 10</u></a></li>
<li><a href="https://buynow-help.techidaily.com/1723038338914-review-the-insignia-ns-43df710na19-affordable-smart-streaming-box-with-ultra-hd-and-alexa-support/"><u>Review: The Insignia NS-43DF710NA19 - Affordable Smart Streaming Box With Ultra HD and Alexa Support!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-resolving-the-0x800704cf-network-error-in-windows-systems/"><u>Step-by-Step Instructions: Resolving the 0X800704CF Network Error in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-address-non-recognition-of-usb-drives-easily/"><u>Step-by-Step Tips to Address Non-Recognition of USB Drives Easily</u></a></li>
<li><a href="https://blog-min.techidaily.com/strategie-seo-amelioree-comment-optimiser-la-taille-des-fichiers-mp4-avec-efficacite-et-preservation-de-la-qualite-image/"><u>Stratégie SEO Améliorée : Comment Optimiser La Taille Des Fichiers MP4 Avec Efficacité Et Préservation De La Qualité Image</u></a></li>
<li><a href="https://common-error.techidaily.com/top-6-solutions-to-resolve-werfaultexe-crashes-in-windows-os/"><u>Top 6 Solutions to Resolve werFault.exe Crashes in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-pc-reboots-in-windows-11/"><u>Unexpected PC Reboots in Windows 11</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://bluetties.sjv.io/c/5597632/2141688/17094" target="_top" id="2141688">
  <img src="//a.impactradius-go.com/display-ad/17094-2141688" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluetties.sjv.io/i/5597632/2141688/17094" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

