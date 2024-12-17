---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-12-10T21:55:58.733Z
updated: 2024-12-16T23:57:27.897Z
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
<li><a href="https://some-skills.techidaily.com/updated-utilizing-slug-lines-for-better-content-structure/"><u>[Updated] Utilizing Slug Lines for Better Content Structure</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-a-step-by-step-pathway-to-adding-sound-in-adobe-premiere/"><u>2024 Approved A Step-by-Step Pathway to Adding Sound in Adobe Premiere</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-reversing-live-action-on-twitch-a-comprehensive-guide/"><u>2024 Approved Reversing Live Action on Twitch A Comprehensive Guide</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/capture-creativity-ios-and-android-writing-apps-roundup/"><u>Capture Creativity IOS & Android Writing Apps Roundup</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/cultivate-inner-peace-and-physical-strength-with-these-channels-for-2024/"><u>Cultivate Inner Peace & Physical Strength with These Channels for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-device-not-found-failed-description-lookup-on-your-usb-device-a-comprehhemed-solution/"><u>How to Fix 'Device Not Found: Failed Description Lookup' On Your USB Device – A Comprehhemed Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208522423-hp-laptop-keyboard-malfunction-solved-discover-simple-repair-techniques-now/"><u>HP Laptop Keyboard Malfunction Solved? Discover Simple Repair Techniques Now</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-gmail-password-on-nubia-red-magic-9-pro-devices-by-drfone-android/"><u>In 2024, How to Reset Gmail Password on Nubia Red Magic 9 Pro Devices</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/maximize-comfort-and-minimize-fatigue-with-the-ergodriven-topo-the-ideal-standing-desk-mat-reviewed/"><u>Maximize Comfort and Minimize Fatigue with the Ergodriven Topo - The Ideal Standing Desk Mat Reviewed</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-tips-for-non-printable-pdf-files/"><u>Quick Troubleshooting Tips for Non-Printable PDF Files</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-win10-upgrade-stuck-on-99-proven-solutions-that-work/"><u>Resolve Win10 Upgrade Stuck on 99%: Proven Solutions That Work</u></a></li>
<li><a href="https://common-error.techidaily.com/swift-methods-to-restore-lenovos-keyboard-function-fn-buttons/"><u>Swift Methods to Restore Lenovo's Keyboard Function (Fn) Buttons</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-windows-107-ethernet-connectivity-problems/"><u>Ultimate Guide: Resolving Windows 10/7 Ethernet Connectivity Problems</u></a></li>
<li><a href="https://some-approaches.techidaily.com/ultra-fast-authorized-winx-dvd-ripper-pro-convert-your-dvds-to-high-quality-mp4-and-hevc-in-record-time/"><u>Ultra-Fast [AUTHORIZED] WinX DVD Ripper Pro: Convert Your DVDs to High-Quality MP4 & HEVC in Record Time!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

