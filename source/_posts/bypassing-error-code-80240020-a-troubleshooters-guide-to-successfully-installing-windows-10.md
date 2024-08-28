---
title: "Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10"
date: 2024-08-27T13:40:20.485Z
updated: 2024-08-28T13:40:20.485Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10"
excerpt: "This Article Describes Bypassing Error Code 80240020: A Troubleshooter's Guide to Successfully Installing Windows 10"
thumbnail: https://thmb.techidaily.com/d009fff2d2f1ae33a60244be6a10e60fe9a4c6152d14b10a6c314e65ab841263.jpg
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
<li><a href="https://facebook-clips.techidaily.com/new-craft-immersive-experiences-sharing-your-view-in-facebook-lives-for-2024/"><u>[New] Craft Immersive Experiences  Sharing Your View in Facebook Lives for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-guide-to-pocket-friendly-discord-video-downloads-on-tech-devices/"><u>[New] Guide to Pocket-Friendly Discord Video Downloads on Tech Devices</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-direct-recording-tool-for-chrome-os/"><u>[New] In 2024, Direct Recording Tool for Chrome OS</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-boosting-watch-time-and-reducing-churn-on-youtube-the-ultimate-list-of-methods-for-2024/"><u>[Updated] Boosting Watch Time and Reducing Churn on YouTube  The Ultimate List of Methods for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-masterful-text-setups-in-adobe-after-effects/"><u>[Updated] Masterful Text Setups in Adobe After Effects</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-leading-removers-tiktok-ids-from-androidios/"><u>2024 Approved  Leading Removers  TikTok IDs From Android/iOS</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-ultimate-videographers-companion-the-ion-air-pro-3-deep-dive/"><u>2024 Approved  The Ultimate Videographer's Companion  The ION Air Pro 3 Deep Dive</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-0x800f0922-bug-easy-steps-for-successful-windows-10-update/"><u>Beat the 0X800F0922 Bug: Easy Steps for Successful Windows 10 Update</u></a></li>
<li><a href="https://fox-glue.techidaily.com/best-quadcopters-for-kids-and-playtime/"><u>Best Quadcopters for Kids & Playtime</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-fixes-for-ps4-network-errors-a-detailed-walkthrough/"><u>Complete Fixes for PS4 Network Errors: A Detailed Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-the-unspecified-error-a-detailed-walkthrough-on-overcoming-0x80004005-issues/"><u>Decoding the 'Unspecified Error' - A Detailed Walkthrough on Overcoming 0X80004005 Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/defeated-error-tackling-and-resolving-the-frozen-windows-config-screen/"><u>Defeated Error: Tackling and Resolving the Frozen Windows Config Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210984997-discords-silent-mic-no-more/"><u>Discord's Silent Mic: No More!</u></a></li>
<li><a href="https://driver-install.techidaily.com/effortlessly-enhance-printer-performance-on-pc/"><u>Effortlessly Enhance Printer Performance on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212386648-fix-blank-spots-in-device-manager-see-touchpad/"><u>Fix Blank Spots in Device Manager, See Touchpad</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-problem-of-windows-unable-to-reach-sensvc-system-event-notification-service/"><u>Fixing the Problem of Windows Unable to Reach SENSVc (System Event Notification Service)</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-tecno-pova-6-pro-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Tecno Pova 6 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-poco-x5-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Poco X5?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-11-muting-issues-a-step-by-step-guide/"><u>How to Fix Windows 11 Muting Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-forcefully-close-windows-11-when-your-computer-fails-to-turn-off/"><u>How to Forcefully Close Windows 11 When Your Computer Fails to Turn Off</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-content-servers-unreachable-on-steam-platforms/"><u>How To Overcome 'Content Servers Unreachable' On Steam Platforms</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-from-iphone-14-plus-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account From iPhone 14 Plus?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-malfunctioning-shift-key-a-step-by-step-guide/"><u>How to Repair a Malfunctioning Shift Key: A Step-by-Step Guide</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-augmented-reality-and-vr-navigating-2023s-content-on-android/"><u>In 2024, Augmented Reality & VR  Navigating 2023'S Content on Android</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-best-time-lapse-video-editing-software/"><u>In 2024, Best Time-Lapse Video Editing Software</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-honor-magic-6-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Honor Magic 6 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-samsung-galaxy-m14-4g-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Samsung Galaxy M14 4G Phone Hassle-Free</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-oneplus-nord-3-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Unova Stone Pokémon Go Evolution List and How Catch Them For OnePlus Nord 3 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-error-1053-non-responsive-service-launch-failure/"><u>Resolving Error 1053: Non-Responsive Service Launch Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-minecraft-crashes-due-to-faulty-graphics-driver-issues-in-windows-solutions/"><u>Resolving Minecraft Crashes Due to Faulty Graphics Driver Issues in Windows - Solutions</u></a></li>
<li><a href="https://win-able.techidaily.com/say-goodbye-to-game-interruptions-resolving-euro-truck-simulator-2-pc-crashes/"><u>Say Goodbye to Game Interruptions: Resolving Euro Truck Simulator 2 PC Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-microphone-problems-on-steelseries-arctis-5-for-optimal-performance/"><u>Solving Microphone Problems on SteelSeries Arctis 5 for Optimal Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-xerox-printing-update-error-0x800f020b-on-pcs-with-windows/"><u>Step-by-Step Fix for Xerox Printing Update Error 0X800f020b on PCs with Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-pc-connection-issues-with-bluetooth-input-devices/"><u>Step-by-Step Solution for PC Connection Issues with Bluetooth Input Devices</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-essential-techniques-for-youtube-image-crafting-for-2024/"><u>The Essential Techniques for YouTube Image Crafting for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-when-your-microsoft-surface-wont-charge-even-though-its-connected-step-by-step-solution/"><u>The Ultimate Fix for When Your Microsoft Surface Won't Charge Even Though It’s Connected: Step-by-Step Solution!</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-samsung-galaxy-m54-5g-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Samsung Galaxy M54 5G Reset Code | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-missing-letters-on-your-win-11-keyboard-step-by-step-solutions/"><u>Troubleshooting Missing Letters on Your Win 11 Keyboard – Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-auto-start-understanding-your-windows-10-pcs-self-booting-issue/"><u>Unexpected Auto-Start: Understanding Your Windows 10 PC's Self-Booting Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/wwe-t-kt-battlegrounds-fixing-the-dx11-v100-compatibility-issue/"><u>WWE ˈtʊ Kɪtʃ 🥊Battlegrounds: Fixing the DX11 v10.0 Compatibility Issue</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713324&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVTV1.90-300x188.jpg" border="0">OtsAV TV Webcaster</a>
<!-- affiliate ads end -->