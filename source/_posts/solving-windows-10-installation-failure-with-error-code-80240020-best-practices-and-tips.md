---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-11-20T00:32:11.745Z
updated: 2024-11-24T17:38:20.927Z
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
<li><a href="https://extra-support.techidaily.com/new-pixelated-personae-effective-face-covering-tactics/"><u>[New] Pixelated Personae Effective Face Covering Tactics</u></a></li>
<li><a href="https://article-files.techidaily.com/new-revolutionizing-patient-outreach-with-fb-ads-for-2024/"><u>[New] Revolutionizing Patient Outreach with FB Ads for 2024</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/avchd-on-samsung-galaxy-s24-ultra-convert-mts-for-samsung-galaxy-s24-ultra-by-aiseesoft-video-converter-play-mts-on-android/"><u>AVCHD on Samsung Galaxy S24 Ultra-convert MTS for Samsung Galaxy S24 Ultra</u></a></li>
<li><a href="https://common-error.techidaily.com/beating-the-blues-of-windows-updates-overcoming-error-code-0x80240n17/"><u>Beating the Blues of Windows Updates: Overcoming Error Code 0X80240n17</u></a></li>
<li><a href="https://common-error.techidaily.com/detecting-missing-dll-msvcr120-error/"><u>Detecting Missing DLL: MSVCR120 Error</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-overcoming-windows-10-error-0x80070541-during-updates/"><u>Effective Solutions for Overcoming Windows 10 Error 0X80070541 During Updates</u></a></li>
<li><a href="https://tech-revival.techidaily.com/effortless-guide-top-imovie-mp4-converter-picks-and-smooth-transfer-tips/"><u>Effortless Guide: Top iMovie MP4 Converter Picks & Smooth Transfer Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-fixes-for-your-windows-10-a-guide-to-sfc-and-dism-tools/"><u>Essential Fixes for Your Windows 10: A Guide to SFC and DISM Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/fixation-techniques-overcoming-the-configuring-windows-hurdle/"><u>Fixation Techniques: Overcoming the 'Configuring Windows' Hurdle</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-xiaomi-14-ultra-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Xiaomi 14 Ultra? | Dr.fone</u></a></li>
<li><a href="https://technical-tips.techidaily.com/how-to-send-and-receive-faxes-for-free-the-top-7-options/"><u>How to Send and Receive Faxes for Free: The Top 7 Options</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-pros-and-cons-of-using-the-lenovo-tab-p11-pro-our-detailed-review/"><u>The Pros and Cons of Using the Lenovo Tab P11 Pro - Our Detailed Review</u></a></li>
<li><a href="https://common-error.techidaily.com/why-doesnt-my-laptop-touchpad-scroll-properly-on-windows-10-solutions-inside/"><u>Why Doesn't My Laptop Touchpad Scroll Properly on Windows 10? Solutions Inside!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

