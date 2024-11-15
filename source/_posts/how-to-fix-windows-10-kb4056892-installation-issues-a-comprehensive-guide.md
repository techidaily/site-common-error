---
title: "How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide"
date: 2024-11-11T18:34:37.694Z
updated: 2024-11-15T18:16:11.250Z
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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-discover-top-rated-xbox-extra-gb-drives/"><u>[New] In 2024, Discover Top-Rated Xbox Extra GB Drives</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-in-2024-setting-up-your-own-mac-based-sports-chat-space/"><u>[Updated] In 2024, Setting Up Your Own Mac-Based Sports Chat Space</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-optimizing-visuals-aspect-ratio-alteration/"><u>[Updated] Optimizing Visuals Aspect Ratio Alteration</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-top-picks-in-affordable-home-cinema-setups-with-4k/"><u>[Updated] Top Picks in Affordable Home Cinema Setups with 4K</u></a></li>
<li><a href="https://common-error.techidaily.com/definitive-guide-to-resolving-nier-automata-freezing-and-crashing-for-pc-users/"><u>Definitive Guide to Resolving NieR: Automata Freezing and Crashing for PC Users</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-tricks-to-revive-your-lenovos-unresponsive-f-key-step-by-step/"><u>Effortless Tricks to Revive Your Lenovo's Unresponsive F Key - Step by Step</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-review-the-ultimate-guide-to-choosing-the-ideal-apple-watch-display-guard-in-233/"><u>Expert Review: The Ultimate Guide to Choosing the Ideal Apple Watch Display Guard in 2^33!</u></a></li>
<li><a href="https://common-error.techidaily.com/five-effective-methods-to-repair-a-malfunctioning-touchscreen-on-windows-11/"><u>Five Effective Methods to Repair a Malfunctioning Touchscreen on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-wow-glitches-ensuring-your-hardware-drivers-are-up-to-date-and-compatible/"><u>Fixing WoW Glitches: Ensuring Your Hardware Drivers Are Up-to-Date and Compatible</u></a></li>
<li><a href="https://win-blog.techidaily.com/get-back-to-gaming-swiftly-troubleshoot-fortnite-loading-issues-today/"><u>Get Back to Gaming Swiftly: Troubleshoot Fortnite Loading Issues Today</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-usb-device-unrecognized-error-that-wont-go-away/"><u>How to Fix 'USB Device Unrecognized Error' That Won't Go Away</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-the-dragon-scale-and-evolution-enabled-pokemon-on-vivo-x100-drfone-by-drfone-virtual-android/"><u>How to get the dragon scale and evolution-enabled pokemon On Vivo X100? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-11-best-location-changers-for-tecno-camon-20-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 11 Best Location Changers for Tecno Camon 20 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-tecno-spark-20-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Tecno Spark 20 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-solution-how-to-address-a-missing-media-driver-issue-in-windows/"><u>Quick Fix Solution: How to Address a Missing Media Driver Issue in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-stalled-windows-10-installation-for-smooth-upgrades/"><u>Resolving Stalled Windows 10 Installation for Smooth Upgrades</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-wacom-pen-malfunctions-on-windows-operating-systems-1110/"><u>Solving Wacom Pen Malfunctions on Windows Operating Systems (11/10)</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/210165834-9781644621554-the-chronicles-of-the-ancient-wizards-of-avalon/"><u>The Chronicles of the Ancient Wizards of Avalon | Free Book</u></a></li>
<li><a href="https://common-error.techidaily.com/why-doesnt-my-acer-computer-hold-a-charge-solutions-inside/"><u>Why Doesn't My Acer Computer Hold a Charge? Solutions Inside!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134489/18498" target="_top" id="2134489">
  <img src="//a.impactradius-go.com/display-ad/18498-2134489" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134489/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

