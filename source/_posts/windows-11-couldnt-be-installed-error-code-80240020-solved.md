---
title: Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]
date: 2024-08-22T19:25:33.232Z
updated: 2024-08-23T19:25:33.232Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]
excerpt: This Article Describes Windows 11 Couldn't Be Installed Error Code 80240020 [Solved]
thumbnail: https://thmb.techidaily.com/aa9290eddc8ec2cc97b63ee765b598d95b8b81e9c2cca36d2d92b110af8ad1f5.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-elevate-your-instagram-experience-with-screen-record-tips/"><u>[New] 2024 Approved  Elevate Your Instagram Experience with Screen Record Tips</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-efficient-transfer-of-movie-maker-videos-to-vimeo-for-2024/"><u>[New] Efficient Transfer of Movie Maker Videos to Vimeo for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-sticker-removal-strategies-for-tiktok-content/"><u>[Updated] Sticker Removal Strategies for TikTok Content</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-mixing-masterclass-for-dji-miniair-2-owners-no-cost-here/"><u>2024 Approved  Mixing Masterclass for DJI Mini/Air 2 Owners - No Cost Here</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-solo-art-of-personalized-instagram-ringtone-making/"><u>2024 Approved  The Solo Art of Personalized Instagram Ringtone Making</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/accessing-the-latest-events-streaming-facebook-live-through-roku/"><u>Accessing the Latest Events  Streaming Facebook Live Through Roku</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/best-10-emoji-makers-to-create-your-own-emojis-pconlineandroidiphone-for-2024/"><u>Best 10 Emoji Makers to Create Your Own Emojis PC/Online/Android/iPhone for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-sxs-side-by-side-configurations-resolving-compatibility-issues-in-windows-11/"><u>Correcting SxS (Side-by-Side) Configurations: Resolving Compatibility Issues in Windows 11</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/deconstructing-jargon-a-slang-dictionary-for-the-informal-age/"><u>Deconstructing Jargon: A Slang Dictionary for the Informal Age</u></a></li>
<li><a href="https://common-error.techidaily.com/dxgidll-woes-now-a-thing-of-past-in-pubg/"><u>Dxgi.dll Woes: Now a Thing of Past in PUBG</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-pc-wont-exit-windows-10-properly/"><u>Effective Fixes for When Your PC Won't Exit Windows 10 Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-inoperative-usb-slots-on-windows-11-pcs/"><u>Effective Solutions for Inoperative USB Slots on Windows 11 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-application-startup-problems-a-guide-for-built-in-admin-accounts/"><u>Fixing Application Startup Problems: A Guide for Built-In Admin Accounts</u></a></li>
<li><a href="https://driver-download.techidaily.com/get-the-latest-asus-network-driver-for-windows-pcs-free-download/"><u>Get the Latest Asus Network Driver for Windows PCs - Free Download</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-gps-location-on-motorola-g24-power-easily-and-safely-drfone-by-drfone-virtual-android/"><u>How to Change GPS Location on Motorola G24 Power Easily & Safely | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-change-location-on-tiktok-to-see-more-content-on-your-tecno-spark-10-4g-drfone-by-drfone-virtual-android/"><u>How to Change Location on TikTok to See More Content On your Tecno Spark 10 4G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-damaged-files-and-directories-that-wont-open/"><u>How to Fix Damaged Files & Directories That Won't Open</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-reset-a-zte-blade-a73-5g-phone-that-is-locked-by-drfone-android/"><u>How to Reset a ZTE Blade A73 5G Phone that is Locked?</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/how-to-setup-a-mac-studio-for-sports-content/"><u>How to Setup a Mac Studio for Sports Content</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-vivo-y78plus-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Vivo Y78+ to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-carryminatis-income-evolution-with-ajey-nagar/"><u>In 2024, CarryMinati's Income Evolution with Ajey Nagar</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-expert-insights-crafting-perfect-vimeo-closures/"><u>In 2024, Expert Insights  Crafting Perfect Vimeo Closures</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-lava-blaze-curve-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Lava Blaze Curve 5G Phones with/without a PC</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-resolving-non-functioning-lenovo-fingerprint-scanner-issues/"><u>Quick Fixes: Resolving Non-Functioning Lenovo Fingerprint Scanner Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-launch-errors-what-to-do-when-minecraft-fails-to-start-in-windows/"><u>Resolving Launch Errors: What to Do When Minecraft Fails to Start in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-missing-opencl-dynamic-library-errors/"><u>Resolving Missing OpenCL Dynamic Library Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-common-update-failed-mistakes-in-warframe-a-comprehvee-guide/"><u>Resolving the Common 'Update Failed' Mistakes in Warframe - A Comprehvee Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-non-appearance-of-wi-fi-settings-on-windows-11-devices/"><u>Resolving the Non-Appearance of Wi-Fi Settings on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-brightness-control-problem-for-a-perfect-display-setup/"><u>Resolving the Windows 11 Brightness Control Problem for a Perfect Display Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201594479-shockwave-flash-issues-in-google-chrome-follow-our-updated-solution-guide/"><u>Shockwave Flash Issues in Google Chrome? Follow Our Updated Solution Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-fixing-shockwave-flash-issues-on-google-chrome/"><u>Solution Steps: Fixing Shockwave Flash Issues on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-game-related-pc-restarts-on-various-windows-platforms-11-10-7-81-and-eight/"><u>Solving Game-Related PC Restarts on Various Windows Platforms - 11, 10, 7, 8.1 & Eight</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211260772-step-by-step-guide-to-restore-lost-devices-in-overwatch-quick-resolution-tips/"><u>Step-by-Step Guide to Restore Lost Devices in Overwatch - Quick Resolution Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-integrity-of-windows-os-file-system/"><u>Step-by-Step Guide: Restoring Integrity of Windows OS File System</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-update-error-code-0x80240034-on-windows-10-devices/"><u>Step-by-Step Solution to Overcome 'Update Error' Code 0X80240034 on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-tackling-and-overcoming-delayed-shutdowns-in-windows-10/"><u>The Ultimate Fix: Tackling and Overcoming Delayed Shutdowns in Windows 10</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-tracking-apps-to-track-samsung-galaxy-xcover-7-without-them-knowing-drfone-by-drfone-virtual-android/"><u>Top 5 Tracking Apps to Track Samsung Galaxy XCover 7 without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-common-issues-with-your-oculus-device/"><u>Troubleshooting Guide: Resolving Common Issues with Your Oculus Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-triumph-how-to-successfully-address-the-red-error-message/"><u>Troubleshooting Triumph: How to Successfully Address the Red Error Message</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/ultimate-guide-performing-a-complete-windows-10-system-restore-in-just-four-steps/"><u>Ultimate Guide: Performing a Complete Windows 10 System Restore in Just Four Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-your-pcs-persistent-freezing-problem/"><u>Ultimate Guide: Solving Your PC's Persistent Freezing Problem</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/under-budget-breeze-masters-check-out-our-review-of-upheres-c5c-and-d6sec-coolers/"><u>Under-Budget Breeze Masters? Check Out Our Review of UpHere's C5C and D6Sec Coolers!</u></a></li>
<li><a href="https://techidaily.com/what-you-need-to-know-to-improve-your-honor-play-7t-hard-reset-drfone-by-drfone-reset-android-reset-android/"><u>What You Need To Know To Improve Your Honor Play 7T Hard Reset | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/your-complete-guide-to-reset-samsung-galaxy-xcover-7-drfone-by-drfone-reset-android-reset-android/"><u>Your Complete Guide To Reset Samsung Galaxy XCover 7 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082535/7443" target="_top" id="2082535"><img src="//a.impactradius-go.com/display-ad/7443-2082535" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082535/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->