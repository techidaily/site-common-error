---
title: Expert Tips for Resolving Installation and Update Complications on Steam Gaming Services
date: 2024-08-15T10:57:28.161Z
updated: 2024-08-16T10:57:28.161Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips for Resolving Installation and Update Complications on Steam Gaming Services
excerpt: This Article Describes Expert Tips for Resolving Installation and Update Complications on Steam Gaming Services
thumbnail: https://thmb.techidaily.com/8c77eb31aaf68af03a18e4ba7fcc0097815c2ee3fb471579a2b65c14ccd90d40.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://lightailing.sjv.io/c/5597632/1725213/17190" target="_top" id="1725213"><img src="//a.impactradius-go.com/display-ad/17190-1725213" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1725213/17190" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4665597&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pcclean.io/wp-content/uploads/2018/03/winutilities-box-130521.png" border="0">WinUtilities Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-crafting-compelling-stories-the-art-of-instagram-video-editing/"><u>[New] Crafting Compelling Stories  The Art of Instagram Video Editing</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-dji-flying-tech-experiment-with-color-luts-at-no-extra-charge/"><u>[New] DJI Flying Tech  Experiment with Color LUTs at No Extra Charge</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-2023-how-to-fix-live-video-interrupted-on-facebook-in-2024/"><u>[Updated] 2023 | How to Fix Live Video Interrupted on Facebook, In 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-explore-the-leading-youtube-to-webm-video-conversion-tools/"><u>[Updated] 2024 Approved  Explore the Leading YouTube-to-WebM Video Conversion Tools</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-how-to-play-facebook-videos-on-tv-for-2024/"><u>[Updated] How To Play Facebook Videos on TV for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-flavorful-friends-top-gastronomy-guides-online/"><u>2024 Approved  Flavorful Friends  Top Gastronomy Guides Online</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mirthful-user-sign-up-saga/"><u>2024 Approved  Mirthful User Sign-Up Saga</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/castrecorder-analysis/"><u>CastRecorder Analysis</u></a></li>
<li><a href="https://extra-information.techidaily.com/chilling-celebrations-beijings-winter-sports-spectacle-for-2024/"><u>Chilling Celebrations  Beijing's Winter Sports Spectacle for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/code-blocked-process-halted/"><u>Code Blocked: Process Halted</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-troubleshooting-for-windows-update-error-understanding-and-solving-0x800f0831/"><u>Effortless Troubleshooting for Windows Update Error: Understanding and Solving 0X800F0831</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-dealing-with-unstable-system-bootups-stemming-from-driver-power-issues-in-windows-computers/"><u>Expert Advice on Dealing with Unstable System Bootups Stemming From Driver Power Issues in Windows Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tricks-to-start-your-intel-rst-service-again-overcoming-windows-10-setbacks/"><u>Expert Tricks to Start Your Intel RST Service Again – Overcoming Windows 10 Setbacks</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-speaker-distortion-issues-on-windows-11-and-7-a-comprehensive-guide/"><u>Fixing Speaker Distortion Issues on Windows 11 & 7 – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-stalled-steam-update-problem-a-comprehensive-guide/"><u>Fixing the Stalled Steam Update Problem: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-the-cache-miss-problem-errcachemiss-error-on-chrome/"><u>Guide to Fixing the 'Cache Miss' Problem – ERR_CACHE_MISS Error on Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-fixing-lost-or-disappearing-bluetooth-devices-on-windows-10-easily/"><u>Guide: Fixing Lost or Disappearing Bluetooth Devices on Windows 10 Easily</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-tecno-spark-10c-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Tecno Spark 10C | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209911636-how-to-do-a-clean-install-of-windows-10-quickly-and-easily/"><u>How to Do a Clean Install of Windows 10, Quickly and Easily</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-newest-amd-radeon-r9-series-drivers-on-your-pc-with-windows-os/"><u>How to Get the Newest AMD Radeon R9 Series Drivers on Your PC with Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-windows-update-error-0x800f08/"><u>How to Resolve Windows Update Error 0X800f08</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-functionality-to-your-broken-backspace-key-on-a-pc-or-mac/"><u>How to Restore Functionality to Your Broken Backspace Key on a PC or Mac</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-wiped-call-history-on-xiaomi-14-by-fonelab-android-recover-call-logs/"><u>How to restore wiped call history on Xiaomi 14?</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-everything-you-need-to-know-about-unlocked-apple-iphone-15-by-drfone-ios/"><u>In 2024, Everything You Need To Know About Unlocked Apple iPhone 15</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-do-you-get-sun-stone-evolutions-in-pokemon-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How Do You Get Sun Stone Evolutions in Pokémon For Meizu 21 Pro? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-reset-a-oneplus-12r-phone-that-is-locked-by-drfone-android/"><u>In 2024, How to Reset a OnePlus 12R Phone that is Locked?</u></a></li>
<li><a href="https://extra-hints.techidaily.com/master-the-art-of-video-editing-complimentary-top-pp-tools/"><u>Master the Art of Video Editing  Complimentary, Top PP Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-volume-control-overcoming-the-soundless-challenge-in-forza-horizon-4/"><u>Mastering Volume Control: Overcoming the Soundless Challenge in Forza Horizon 4</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-trustee-rights-requesting-access-from-trustedinstaller-to-modify-files/"><u>Navigating Trustee Rights: Requesting Access From TrustedInstaller to Modify Files</u></a></li>
<li><a href="https://extra-resources.techidaily.com/os-bridging-virtualmix-pro/"><u>OS-Bridging VirtualMix Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-resolving-windows-error-651/"><u>Quick Solutions for Resolving Windows Error 651</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-update-unavailable-issue-step-by-step-fix-guide/"><u>Resolving 'Windows Update Unavailable' Issue: Step-by-Step Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-wireless-display-adapter-not-connecting-problems-on-your-pc-with-windows-10/"><u>Resolving 'Wireless Display Adapter Not Connecting' Problems on Your PC with Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/restart-your-computer/"><u>Restart Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-the-speakers-expert-guide-to-enabling-audio-on-an-acer-notebook/"><u>Reviving the Speakers: Expert Guide to Enabling Audio on an Acer Notebook</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-noisy-audio-in-windows-operating-systems-10-and-7/"><u>Solution for Noisy Audio in Windows Operating Systems (10 and 7)</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-minecraft-not-opening-in-windows-operating-system/"><u>Solution Steps for Minecraft Not Opening in Windows Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-failed-to-login-through-user-profile-service/"><u>Step-by-Step Fix for 'Failed to Login Through User Profile Service'</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-when-your-lenovo-mouse-pad-fails-on-windows-windows-11-8-and-7/"><u>Step-by-Step Fixes for When Your Lenovo Mouse Pad Fails on Windows [Windows 11, 8 & 7]</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-instructions-for-syncing-your-xbox-one-controller-when-connected-to-a-pc-or-console/"><u>Step-by-Step Instructions for Syncing Your Xbox One Controller When Connected to a PC or Console</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/the-best-boxing-streaming-websites-for-the-latest-match-coverage-for-2024/"><u>The Best Boxing Streaming Websites for the Latest Match Coverage for 2024</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/the-samsung-galaxy-watch-active-deconstructed-is-it-truly-a-health-enthusiasts-dream/"><u>The Samsung Galaxy Watch Active Deconstructed – Is It Truly a Health Enthusiast's Dream?</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/the-ultimate-language-map-of-vietnamese-expressions/"><u>The Ultimate Language Map of Vietnamese Expressions</u></a></li>
<li><a href="https://techidaily.com/top-8-iphone-se-2022-smsmessagetext-recovery-software-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>Top 8 iPhone SE (2022) SMS/Message/Text Recovery Software | Stellar</u></a></li>
<li><a href="https://tech-hub.techidaily.com/transformative-gaming-journeys-leveraging-chatgpt-for-engaging-and-interactive-roleplay/"><u>Transformative Gaming Journeys: Leveraging ChatGPT for Engaging and Interactive Roleplay</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-restore-five-tips-for-solving-touchscreen-issues-in-windows-10/"><u>Troubleshoot and Restore: Five Tips for Solving Touchscreen Issues in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-missing-bluetooth-devices-in-windows-11-without-hassle/"><u>Troubleshoot Missing Bluetooth Devices in Windows 11 Without Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-nonfunctional-dell-wireless-keypad-solutions-inside/"><u>Troubleshooting a Nonfunctional Dell Wireless Keypad – Solutions Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-nonfunctional-usb-mouse-on-your-pc-top-solutions/"><u>Troubleshooting a Nonfunctional USB Mouse on Your PC: Top Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixes-for-geforce-experience-not-starting-correctly/"><u>Troubleshooting Tips: Fixes for GeForce Experience Not Starting Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-restoring-integrity-of-windows-11-system-components/"><u>Troubleshooting Tips: Restoring Integrity of Windows 11 System Components</u></a></li>
<li><a href="https://activate-lock.techidaily.com/ultimate-guide-from-apple-iphone-7-plus-icloud-activation-lock-bypass-by-drfone-ios/"><u>Ultimate Guide from Apple iPhone 7 Plus iCloud Activation Lock Bypass</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-memory-management-issues-in-windows-11-devices/"><u>Understanding and Fixing Memory Management Issues in Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/upgrade-your-screen-update-required-incompatible-display-timeout-settings/"><u>Upgrade Your Screen: Update Required - Incompatible Display Timeout Settings</u></a></li>
</ul></div>
