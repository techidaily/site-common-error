---
title: "Windows Updates Now Successfully Installed: Fix Guide"
date: 2024-09-19T16:23:58.378Z
updated: 2024-09-20T17:42:30.831Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows Updates Now Successfully Installed: Fix Guide"
excerpt: "This Article Describes Windows Updates Now Successfully Installed: Fix Guide"
thumbnail: https://thmb.techidaily.com/86e7c4ea92c80232a2f22ec398fe1175bda0bfa79b5ffdb49f75954366a9ab9c.jpg
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
<li><a href="https://desktop-recording.techidaily.com/2024-approved-comprehensive-guide-to-xbox-screen-recording-success/"><u>2024 Approved Comprehensive Guide to Xbox Screen Recording Success</u></a></li>
<li><a href="https://article-files.techidaily.com/accelerate-image-editing-mastery-with-pivotal-pixlr-tips/"><u>Accelerate Image Editing Mastery with Pivotal Pixlr Tips</u></a></li>
<li><a href="https://blog-min.techidaily.com/conversion-de-archivos-webm-a-3gp-gratis-en-linea-con-movavi/"><u>Conversión De Archivos WebM a 3GP Gratis en Línea Con Movavi</u></a></li>
<li><a href="https://win-solutions.techidaily.com/1723005517525-experience-the-epic-battles-of-god-of-war-fps-newly-released-for-pc-gamers/"><u>Experience the Epic Battles of God of War FPS – Newly Released for PC Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/explorer-down-restore-it-now/"><u>Explorer Down? Restore It Now!</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-ways-to-trade-pokemon-go-from-far-away-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, Ways to trade pokemon go from far away On Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-multiple-ways-how-to-remove-icloud-activation-lock-on-your-iphone-6s-plus-by-drfone-ios/"><u>New Multiple Ways How To Remove iCloud Activation Lock On your iPhone 6s Plus</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-hang-ups-in-windows-11-for-smooth-operation/"><u>Overcoming Hang-Ups in Windows 11 for Smooth Operation</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-usb-tethering-setup-on-windows-10-made-simple/"><u>Seamless USB Tethering Setup on Windows 10 Made Simple</u></a></li>
<li><a href="https://buynow-info.techidaily.com/unveiling-the-ultimate-guide-to-choosing-an-apple-airtag-a-savior-for-your-iphone/"><u>Unveiling The Ultimate Guide to Choosing an Apple AirTag: A Savior for Your iPhone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049382/7443" target="_top" id="2049382">
  <img src="//a.impactradius-go.com/display-ad/7443-2049382" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049382/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

