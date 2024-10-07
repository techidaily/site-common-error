---
title: Resolving the Unidentified USB Peripheral Error and Port Reset Failure on Windows 10
date: 2024-10-03T06:22:47.768Z
updated: 2024-10-07T11:01:40.211Z
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
<li><a href="https://extra-information.techidaily.com/updated-beyond-entertainment-vrs-utility/"><u>[Updated] Beyond Entertainment VR's Utility</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-adobes-quest-for-giggles-and-grins/"><u>[Updated] In 2024, Adobe's Quest for Giggles and Grins</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-master-thumbnail-design-for-mac-users-youtube-edition-for-2024/"><u>[Updated] Master Thumbnail Design for Mac Users - YouTube Edition for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-smooth-windows-11-upgrade-process-and-avoiding-stucks/"><u>Expert Tips for Smooth Windows 11 Upgrade Process & Avoiding Stucks</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-network-up-to-speed-download-the-latest-linksys-ae1200-driver-today/"><u>Get Your Network Up To Speed: Download the Latest Linksys AE1200 Driver Today!</u></a></li>
<li><a href="https://dvd-bd.techidaily.com/guia-practica-como-minimizar-la-extension-de-videos-grandes-antes-de-publicarlos-en-facebook/"><u>Guía Práctica: Cómo Minimizar La Extensión De Vídeos Grandes Antes De Publicarlos en Facebook</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-samsung-galaxy-a34-5g-to-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Samsung Galaxy A34 5G To Phone | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-diy-tips-getting-started-with-voice-over-filming/"><u>In 2024, DIY Tips Getting Started with Voice Over Filming</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-top-live-broadcast-tech-for-industry-experts/"><u>In 2024, Top Live Broadcast Tech for Industry Experts</u></a></li>
<li><a href="https://common-error.techidaily.com/instant-repair-for-missing-lidadll/"><u>Instant Repair for Missing Lida.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-no-volume-easy-fixes-to-get-your-sounds-back/"><u>Netflix No Volume? Easy Fixes to Get Your Sounds Back</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-the-windows-update-failure-error-0x8024401c-in-windows-1111-systems/"><u>Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-overwatchs-voice-chat-issues-swiftly/"><u>Troubleshoot and Fix Overwatch's Voice Chat Issues Swiftly</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135372/19272" target="_top" id="2135372">
  <img src="//a.impactradius-go.com/display-ad/19272-2135372" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135372/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

