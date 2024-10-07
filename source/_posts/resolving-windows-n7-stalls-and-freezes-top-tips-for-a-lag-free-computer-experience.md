---
title: Resolving Windows N7 Stalls and Freezes - Top Tips for a Lag-Free Computer Experience
date: 2024-10-06T06:34:05.687Z
updated: 2024-10-07T07:27:55.706Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Windows N7 Stalls and Freezes - Top Tips for a Lag-Free Computer Experience
excerpt: This Article Describes Resolving Windows N7 Stalls and Freezes - Top Tips for a Lag-Free Computer Experience
thumbnail: https://thmb.techidaily.com/545eb30532b146292d910492a3de0882f942d02de7b5ef10d79d0e3f377f7561.jpg
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-snapback-success-the-secrets-to-loops-on-instagram-for-2024/"><u>[New] Snapback Success The Secrets to Loops on Instagram for 2024</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-in-2024-photography-editing-tips-for-creating-stunning-photos/"><u>[Updated] In 2024, Photography Editing Tips for Creating Stunning Photos</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-quick-guide-activatingdeactivating-picture-in-picture-pip-for-youtube/"><u>[Updated] Quick Guide Activating/Deactivating Picture In Picture (PIP) for YouTube</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-poco-m6-pro-5g-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Poco M6 Pro 5G to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-and-continue-your-adventure-when-stuck-at-the-loading-screen-of-red-dead-redemption-2/"><u>How to Fix and Continue Your Adventure When Stuck at the Loading Screen of Red Dead Redemption 2</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-a-comprehensive-guide-to-mastering-ipogo-for-pokemon-go-on-apple-iphone-6s-drfone-by-drfone-virtual-ios/"><u>In 2024, A Comprehensive Guide to Mastering iPogo for Pokémon GO On Apple iPhone 6s | Dr.fone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-laughlines-drawing-chuckles-online/"><u>In 2024, LaughLines Drawing Chuckles Online</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-a-corrupted-windows-store-cache/"><u>Resolved: Fixing a Corrupted Windows Store Cache</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-incompatible-device-drivers-on-windows-operating-systems/"><u>Resolved: Incompatible Device Drivers on Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-system-error-5-across-windows-11-7-and-8-comprehensive-guide/"><u>Resolving 'System Error 5' Across Windows 11, 7, and 8 - Comprehensive Guide</u></a></li>
<li><a href="https://app-tips.techidaily.com/rising-popularity-of-ops-transforming-it-landscapes-and-introducing-fresh-challenges-insights-from-tech-giants/"><u>Rising Popularity of 'Ops': Transforming IT Landscapes and Introducing Fresh Challenges - Insights From Tech Giants</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-the-dxgi-device-freeze-error-with-straightforward-remedies/"><u>Tackling the DXGI Device Freeze Error with Straightforward Remedies</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202175401-trouble-with-your-huion-pen-heres-how-to-repair-it-fast/"><u>Trouble with Your Huion Pen? Here's How to Repair It Fast</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-non-functional-microsoft-print-to-pdf-feature-in-latest-windows-os/"><u>Troubleshooting Steps for Non-Functional Microsoft Print to PDF Feature in Latest Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-keyboard-response-slowdown-heres-how-to-address-it-effectively/"><u>Windows 11 Keyboard Response Slowdown? Here's How to Address It Effectively!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

