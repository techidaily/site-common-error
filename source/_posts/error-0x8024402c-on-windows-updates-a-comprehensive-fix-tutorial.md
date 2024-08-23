---
title: Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial
date: 2024-08-22T19:21:57.949Z
updated: 2024-08-23T19:21:57.949Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial
excerpt: This Article Describes Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial
thumbnail: https://thmb.techidaily.com/b12c1a140a3344398be10869a2b844a6fc484f74ef7b38393e9a6d380bb9dbb1.jpg
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
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-breaking-down-barriers-to-inaccessible-youtube-content/"><u>[New] In 2024, Breaking Down Barriers to Inaccessible YouTube Content</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-in-2024-experience-nba-like-a-pro-master-these-top-15-livestream-methods/"><u>[New] In 2024, Experience NBA Like a Pro - Master These Top 15 Livestream Methods</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-maximize-engagement-with-these-instagram-story-tips/"><u>[New] Maximize Engagement with These Instagram Story Tips</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-crafting-irresistible-profile-videos/"><u>[Updated] Crafting Irresistible Profile Videos</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-ultimate-guide-to-audiofreexer-extraction-for-2-point-zero-two-four/"><u>[Updated] The Ultimate Guide to AudioFreexer Extraction for 2 Point Zero Two Four</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-the-visionary-studio-guide-detailed-xreviewers-digest/"><u>2024 Approved  The Visionary Studio Guide  Detailed XReviewer's Digest</u></a></li>
<li><a href="https://common-error.techidaily.com/acer-not-charging-here-are-the-common-causes-and-fixes/"><u>Acer Not Charging? Here Are the Common Causes and Fixes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/apex-online-video-streaming-applications/"><u>Apex Online Video Streaming Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-common-setup-hurdles-in-directx-with-simple-corrections/"><u>Bypassing Common Setup Hurdles in DirectX with Simple Corrections</u></a></li>
<li><a href="https://common-error.techidaily.com/code-28-in-windows-device-manager-heres-how-to-fix-it-quickly/"><u>Code 28 in Windows Device Manager? Here's How to Fix It Quickly!</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-recovery-essential-windows-updates-fully-restored/"><u>Complete Recovery: Essential Windows Updates Fully Restored</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-walkthrough-to-scan-and-repair-stuck-hard-drivesssds-in-windows-11-systems/"><u>Comprehensive Walkthrough to Scan and Repair Stuck Hard Drives/SSDs in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/decode-your-issues-comprehensive-strategies-against-windows-error-code-31/"><u>Decode Your Issues: Comprehensive Strategies Against Windows Error Code 31</u></a></li>
<li><a href="https://common-error.techidaily.com/definitive-strategies-to-correctly-solve-windows-11s-common-error-code-0x80072efd/"><u>Definitive Strategies to Correctly Solve Windows 11'S Common Error Code 0X80072EFD</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/directly-send-snaps-from-your-phone-a-tutorial/"><u>Directly Send Snaps From Your Phone - A Tutorial</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/discovering-the-worth-in-your-subscription-to-youtube-tv/"><u>Discovering the Worth in Your Subscription to YouTube TV</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211590610-effective-strategies-to-address-twitchs-error-4/"><u>Effective Strategies to Address Twitch's Error 4#</u></a></li>
<li><a href="https://common-error.techidaily.com/effortlessly-fix-windows-10-bluetooth-disappearance-issues-in-minutes/"><u>Effortlessly Fix Windows 10 Bluetooth Disappearance Issues in Minutes!</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-setup-a-guide-to-solving-error-code-0x800f081f-in-net-framework-35-installs/"><u>Error-Free Setup: A Guide to Solving Error Code 0X800F081F in .NET Framework 3.5 Installs</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-solutions-for-fixing-werfaultexe-problems-on-your-pc/"><u>Essential Solutions for Fixing werFault.exe Problems on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-repairing-usb-not-recognized-error-instantly/"><u>Expert Advice on Repairing 'USB Not Recognized' Error Instantly</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-11s-frustrating-0x80072efd-error-step-by-step-solutions/"><u>Fixing Windows 11'S Frustrating 0X80072EFD Error: Step-by-Step Solutions</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/historic-discount-alert-grab-the-logitech-g-pro-for-just-54-best-offer-yet/"><u>Historic Discount Alert! Grab the Logitech G Pro for Just $54 – Best Offer Yet</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-frp-on-xiaomi-redmi-12-5g-by-drfone-android/"><u>How to Bypass FRP on Xiaomi Redmi 12 5G?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-serious-fatal-problems-in-black-ops-4/"><u>How to Correct Serious Fatal Problems in Black Ops 4</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-steams-inability-to-access-the-network/"><u>How to Fix Steam's Inability to Access the Network</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-unresponsive-scroll-feature-on-your-laptops-touchpad-windows-10/"><u>How to Repair Unresponsive Scroll Feature on Your Laptop's Touchpad (Windows 10)</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-non-copyrighted-meditation-sounds/"><u>In 2024, Non-Copyrighted Meditation Sounds</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-smoothing-video-borders-on-teamcollaboration-platforms/"><u>In 2024, Smoothing Video Borders on TeamCollaboration Platforms</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-ultimate-guide-how-to-bypass-swipe-screen-to-unlock-on-nokia-c22-device-by-drfone-android/"><u>In 2024, The Ultimate Guide How to Bypass Swipe Screen to Unlock on Nokia C22 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206908598-keyboard-malfunctions-resolve-non-working-keys-in-windows-10-and-11-quickly/"><u>Keyboard Malfunctions? Resolve Non-Working Keys in Windows 10 and 11 Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208731117-microsoft-wireless-display-not-working-on-windows-11-heres-how-you-can-solve-it/"><u>Microsoft Wireless Display Not Working on Windows 11? Here’s How You Can Solve It!</u></a></li>
<li><a href="https://common-error.techidaily.com/miracast-troubles-beat-the-unsupported-receiving-device-error-this-year/"><u>Miracast Troubles? Beat the 'Unsupported Receiving Device' Error This Year!</u></a></li>
<li><a href="https://common-error.techidaily.com/nba-2k21-green-mishap-explained-and-resolved-what-you-need-to-know/"><u>NBA 2K21 Green Mishap Explained and Resolved - What You Need to Know!</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/nier-gestalt-and-repliecate-troubleshooting-how-to-stop-game-crashes/"><u>NieR: Gestalt & Repliecate Troubleshooting - How to Stop Game Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-11-reset-failures-with-our-step-by-step-troubleshooting-tips/"><u>Overcome Windows 11 Reset Failures with Our Step-by-Step Troubleshooting Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-connectivity-problems-wireless-mouse-malfunction-in-windows-operating-systems/"><u>Resolving Connectivity Problems - Wireless Mouse Malfunction in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207892756-reveal-hidden-touchpad-with-simple-steps/"><u>Reveal Hidden Touchpad with Simple Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-corsair-hs50-essential-fixes-for-a-broken-microphone-issue/"><u>Revive Your Corsair HS50: Essential Fixes for a Broken Microphone Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-fix-your-pcs-update-error-code-0x8007001f-explained/"><u>Step-by-Step Tips to Fix Your PC's Update Error: Code 0X8007001f Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/tech-guide-lowering-high-disk-usage-linked-to-compatibility-telemetry-feature-on-pc-with-windows-10-operating-system/"><u>Tech Guide: Lowering High Disk Usage Linked to Compatibility Telemetry Feature on PC with Windows 10 Operating System</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-mechanics-behind-bot-success-and-their-appeal/"><u>The Mechanics Behind Bot Success and Their Appeal</u></a></li>
<li><a href="https://common-error.techidaily.com/tidy-up-resolve-explorer-crashes/"><u>Tidy Up: Resolve Explorer Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-werfaultexe-errors-on-your-pc-easily-with-these-6-strategies/"><u>Troubleshoot and Fix werFault.exe Errors on Your PC Easily with These 6 Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-failed-contact-with-your-dhcp-server-fixed/"><u>Troubleshooting Failed Contact With Your DHCP Server (Fixed)</u></a></li>
<li><a href="https://common-error.techidaily.com/update-and-fix-how-to-overcome-this-device-doesnt-support-receiving-miracast-error/"><u>Update & Fix: How to Overcome 'This Device Doesn't Support Receiving Miracast' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204525599-warframe-patch-problems-heres-how-you-can-successfully-install-updates-again/"><u>Warframe Patch Problems? Here's How You Can Successfully Install Updates Again</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://secure.textstudio.com/order/checkout.php?PRODS=35633309&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/d6eb8222c9718486bdabce8b897380f7/products/3_premium-icon.png" border="0"> Take advantage of PREMIUM features for 12 months. 
Create your texts / logos without any limitation. 
No attribution required when downloading. 
No advertising on the website. 
 TextStudio.com  PREMIUM - Yearly Membership</a>
<!-- affiliate ads end -->