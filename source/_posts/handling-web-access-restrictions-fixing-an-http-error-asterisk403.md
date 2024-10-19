---
title: "Handling Web Access Restrictions: Fixing an HTTP Error Asterisk(403)"
date: 2024-10-12T01:22:23.329Z
updated: 2024-10-19T00:26:06.055Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Handling Web Access Restrictions: Fixing an HTTP Error Asterisk(403)"
excerpt: "This Article Describes Handling Web Access Restrictions: Fixing an HTTP Error Asterisk(403)"
thumbnail: https://thmb.techidaily.com/405adc45ebf84824c8425ce7d2ecb9e77863385d350fb3dba3386c181908ce4e.jpg
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
<li><a href="https://facebook-video-content.techidaily.com/new-in-2024-drive-success-a-comprehensive-list-of-the-best-fb-schedulers/"><u>[New] In 2024, Drive Success A Comprehensive List of the Best FB Schedulers</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-loadlibrary-failed-with-error-87-the-parameter-is-incorrect/"><u>[SOLVED] Loadlibrary Failed with Error 87: The Parameter Is Incorrect</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/5-best-websites-to-download-royalty-free-comedy-background-music/"><u>5 Best Websites to Download Royalty Free Comedy Background Music</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolving-windows-11-display-flicker-problems/"><u>Comprehensive Guide: Resolving Windows 11 Display Flicker Problems</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/creating-captivating-thumbnails-for-youtube/"><u>Creating Captivating Thumbnails for YouTube</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-guide-repairing-function-key-issues-on-a-dell-laptop/"><u>DIY Guide: Repairing Function Key Issues on a Dell Laptop</u></a></li>
<li><a href="https://win-amazing.techidaily.com/find-and-get-the-right-realtek-network-interface-controller-software-for-your-windows-710-pc/"><u>Find & Get the Right Realtek Network Interface Controller Software for Your Windows 7/10 PC</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-science-of-sensor-based-hands-monitoring/"><u>In 2024, The Science of Sensor-Based Hands Monitoring</u></a></li>
<li><a href="https://vp-tips.techidaily.com/professionelle-zu-youtube-converter-apps-zum-herunterladen-und-umwandeln-in-wav-format-finden-sie-hier/"><u>Professionelle Zu YouTube Converter Apps Zum Herunterladen Und Umwandeln in WAV Format Finden Sie Hier</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-for-logildadll-gone/"><u>Quick Fix for LogiLDA.dll Gone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-unknown-usb-hardware-issues-device-descriptor-request-fails/"><u>Resolving Unknown USB Hardware Issues: Device Descriptor Request Fails</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/vimeo-star-moment-analysis-for-2024/"><u>Vimeo Star Moment Analysis for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006933/19272" target="_top" id="2006933">
  <img src="//a.impactradius-go.com/display-ad/19272-2006933" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

