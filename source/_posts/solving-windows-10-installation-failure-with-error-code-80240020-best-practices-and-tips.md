---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2025-01-10T16:25:39.533Z
updated: 2025-01-16T16:04:24.934Z
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
<li><a href="https://fox-http.techidaily.com/new-in-2024-unlocking-windows-10-seamless-media-importation-techniques/"><u>[New] In 2024, Unlocking Windows 10 Seamless Media Importation Techniques</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-storage-analysis-videography-on-64128gb-hardware/"><u>[Updated] In 2024, Storage Analysis Videography on 64/128GB Hardware</u></a></li>
<li><a href="https://android-frp.techidaily.com/a-quick-guide-to-oneplus-frp-bypass-instantly-by-drfone-android/"><u>A Quick Guide to OnePlus FRP Bypass Instantly</u></a></li>
<li><a href="https://common-error.techidaily.com/class-not-registered-on-windows-10-solved/"><u>Class Not Registered on Windows 10 [Solved]</u></a></li>
<li><a href="https://extra-tips.techidaily.com/framefusion-media-suite/"><u>FrameFusion Media Suite</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/gratis-konvertereen-van-m4a-naar-swf-professioneel-onlinedienst-by-movavi/"><u>Gratis Konvertereen Van M4A Naar SWF: Professioneel Onlinedienst by Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-scrolling-problems-with-your-pcs-touchpad-on-windows-10/"><u>How to Repair Scrolling Problems with Your PC's Touchpad on Windows 10</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-emerald-master-ball-cheat-on-vivo-y28-5g-drfone-by-drfone-virtual-android/"><u>How to Use Pokémon Emerald Master Ball Cheat On Vivo Y28 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-unlocking-ez-grabber-a-quick-guide-to-downloading-setting-up/"><u>In 2024, Unlocking EZ Grabber - A Quick Guide to Downloading, Setting Up</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-dark-mode-controls-fix-needed/"><u>Missing Dark Mode Controls: Fix Needed</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-addressing-and-correcting-stop-errors-in-hamachi/"><u>Quick Guide: Addressing and Correcting Stop Errors in Hamachi</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-resolving-windows-update-hanging-at-zero-percent/"><u>Quick Solutions for Resolving Window's Update Hanging at Zero Percent</u></a></li>
<li><a href="https://solve-luxury.techidaily.com/step-by-step-process-to-fix-driver-malfunctions-on-windows-systems-with-tips-from-yl-software/"><u>Step-by-Step Process to Fix Driver Malfunctions on Windows Systems with Tips From YL Software</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-how-to-securely-connect-your-airpods-to-windows-10-and-11-latest-troubleshooting-techniques/"><u>The Ultimate Fix: How to Securely Connect Your AirPods to Windows 10 and 11 (Latest Troubleshooting Techniques)</u></a></li>
<li><a href="https://fox-http.techidaily.com/tips-for-smooth-transitioning-from-zoom-to-fb-live-events/"><u>Tips for Smooth Transitioning From ZOOM to FB Live Events</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-power-surge-issues-at-the-networking-hub/"><u>Troubleshooting Guide: Resolving Power Surge Issues at the Networking Hub</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-no-speakers-solving-audio-device-installation-problems-in-windows/"><u>Troubleshooting No Speakers: Solving Audio Device Installation Problems in Windows</u></a></li>
<li><a href="https://facebook.techidaily.com/what-do-facebooks-newly-renamed-pages-really-signify/"><u>What Do Facebook's Newly Renamed Pages Really Signify?</u></a></li>
<li><a href="https://common-error.techidaily.com/wireless-woes-no-more-a-comprehensive-guide-to-sync-your-airpods-with-windows-pcs/"><u>Wireless Woes No More: A Comprehensive Guide to Sync Your AirPods with Windows PCs</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

