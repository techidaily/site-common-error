---
title: "Resolved: Fixing 'System Cannot Allocate Enough Memory' Error"
date: 2024-08-15T11:13:48.294Z
updated: 2024-08-16T11:13:48.294Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Fixing 'System Cannot Allocate Enough Memory' Error"
excerpt: "This Article Describes Resolved: Fixing 'System Cannot Allocate Enough Memory' Error"
thumbnail: https://thmb.techidaily.com/02857e9a5729a034df5799d80242303ce172ee6947ee8ec278b9096d58e3459c.jpg
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-direct-download-and-mp3-creation-for-streaming-video-files/"><u>[New] 2024 Approved  Direct Download & MP3 Creation for Streaming Video Files</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-effortless-integration-of-xbox-and-facebook-streams/"><u>[New] 2024 Approved  Effortless Integration of Xbox and Facebook Streams</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-crafting-cinema-scores-in-imovie/"><u>[Updated] Crafting Cinema Scores in iMovie</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-how-does-the-law-apply-to-video-sharing-on-facebook-for-2024/"><u>[Updated] How Does the Law Apply to Video Sharing on Facebook for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-youtubes-payment-cycle-a-detailed-look/"><u>[Updated] YouTube’s Payment Cycle  A Detailed Look</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-xiaomi-redmi-13c-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Xiaomi Redmi 13C | Dr.fone</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/2024-approved-3-strategies-for-tiktok-livestreaming-from-desktop/"><u>2024 Approved  3 Strategies for TikTok Livestreaming From Desktop</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/2024-approved-game-on-compile-your-collection-of-the-top-12-pc-clickers/"><u>2024 Approved  Game On  Compile Your Collection of the Top 12 PC Clickers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-meizu-21-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Meizu 21 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/achieve-seamless-xbox-one-operation-on-computer/"><u>Achieve Seamless Xbox One Operation on Computer</u></a></li>
<li><a href="https://tech-revival.techidaily.com/chatgpt-and-its-impact-on-writers-job-prospects-5challenges/"><u>ChatGPT & Its Impact on Writers' Job Prospects - #5Challenges</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-headset-mic-wont-work-heres-how-to-restore-your-hs50-audio-output/"><u>Corsair Headset Mic Won't Work? Here's How to Restore Your HS50 Audio Output</u></a></li>
<li><a href="https://common-error.techidaily.com/defeating-pubgs-launch-error-a-step-by-step-tutorial/"><u>Defeating PUBG's Launch Error : A Step-by-Step Tutorial</u></a></li>
<li><a href="https://technical-tips.techidaily.com/diy-tutorial-getting-rid-of-microsoft-copilot-in-windows-11-what-you-need-to-know/"><u>DIY Tutorial: Getting Rid of Microsoft Copilot in Windows 11 – What You Need to Know</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-galaxy-a54-5g-support-avchd-video-by-aiseesoft-video-converter-play-mts-on-android/"><u>Does Galaxy A54 5G support AVCHD video?</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-windows-media-player-server-failure-messages-on-pcs/"><u>Effective Solutions for Windows Media Player Server Failure Messages on PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-overcome-the-0x80072efd-failure-message-on-windows-10-machines/"><u>Effective Solutions to Overcome the 0X80072EFD Failure Message on Windows 10 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-communication-restored-tackling-the-crc-error-effectively/"><u>Error-Free Communication Restored: Tackling the CRC Error Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-addressing-the-missing-devices-warning-in-icue/"><u>Expert Guide: Addressing the Missing Devices Warning in ICUE</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-oppo-reno-11-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Oppo Reno 11 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-battleye-installation-errors-a-comprehensive-tutorial/"><u>Fixes for BattlEye Installation Errors: A Comprehensive Tutorial</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/grandest-picture-tweaker-suite-for-2024/"><u>Grandest Picture Tweaker Suite for 2024</u></a></li>
<li><a href="https://network-issues.techidaily.com/how-to-fix-youtube-green-screen-issues/"><u>How To Fix YouTube Green Screen Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-a-disrupted-vpn-session-with-hamachi-errors/"><u>How to Overcome a Disrupted VPN Session with Hamachi Errors?</u></a></li>
<li><a href="https://common-error.techidaily.com/hp-keyboard-malfunctions-5-easy-steps-to-restore-functionality/"><u>HP Keyboard Malfunctions? 5 Easy Steps to Restore Functionality</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-apple-iphone-xs-drfone-by-drfone-virtual-ios/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Apple iPhone XS | Dr.fone</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-pokemon-go-error-12-failed-to-detect-location-on-oppo-reno-11-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Pokemon Go Error 12 Failed to Detect Location On Oppo Reno 11 5G? | Dr.fone</u></a></li>
<li><a href="https://win-dash.techidaily.com/installing-or-updating-your-brother-hl-l2300d-printer-driver-made-easy/"><u>Installing or Updating Your Brother HL-L2300D Printer Driver Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/login-blues-overcoming-keyboard-errors-during-boot-process/"><u>Login Blues: Overcoming Keyboard Errors During Boot Process</u></a></li>
<li><a href="https://common-error.techidaily.com/nba-2k21-eco-friendly-bug-fixes-and-updates/"><u>NBA 2K21 Eco-Friendly Bug Fixes and Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-remedy-for-lidadll-problem/"><u>Quick Remedy for Lida.dll Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-strategies-for-overcoming-error-0x887a0006/"><u>Quick-Fix Strategies for Overcoming Error 0X887A0006</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-minecraft-game-failures-due-to-faulty-video-card-software-for-windows-users/"><u>Resolve Minecraft Game Failures Due to Faulty Video Card Software for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/runtime-rejection-in-effect/"><u>Runtime Rejection in Effect</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-dns-server-not-responding-discover-4-easy-fixes-to-restore-connectivity/"><u>Solve 'DNS Server Not Responding': Discover 4 Easy Fixes to Restore Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-msmpengexe-high-cpu-usage-on-windows-10-a-comprehensive-guide/"><u>Solve MsMpEng.exe High CPU Usage on Windows 10: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-audio-output-missing-issue-on-windows-10-and-11/"><u>Solving the 'Audio Output Missing' Issue on Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-unknown-usb-device-error-with-port-reset-issues-in-windows-10/"><u>Solving the 'Unknown USB Device' Error with Port Reset Issues in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/the-great-link-up-laptops-and-headphones-converse-again/"><u>The Great Link-Up: Laptops and Headphones Converse Again</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-to-reduce-msmpengexes-heavy-resource-consumption-in-windows-11-solution-found/"><u>Tips to Reduce MsMpEng.exe's Heavy Resource Consumption in Windows 11 (SOLUTION FOUND)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-non-functional-brightness-settings-on-windows-10-devices/"><u>Troubleshooting Guide for Non-Functional Brightness Settings on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-geforce-experience-unable-to-access-user-configurations/"><u>Troubleshooting Guide: 'GeForce Experience Unable to Access User Configurations'</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-persistent-white-error-screen-in-windows-11/"><u>Troubleshooting Persistent White Error Screen in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-80240020-error-during-windows-10-setup-solutions-revealed/"><u>Troubleshooting the 80240020 Error During Windows 10 Setup - Solutions Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-unresponsive-touchpad-windows-10-solutions/"><u>Troubleshooting the Unresponsive Touchpad: Windows 10 Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-your-dell-wireless-keyboard-stops-responding/"><u>Troubleshooting Tips for When Your Dell Wireless Keyboard Stops Responding</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-success-expert-advice-for-tackling-and-repairing-error-1603-on-your-device/"><u>Unlocking Success: Expert Advice for Tackling and Repairing Error 1603 on Your Device</u></a></li>
<li><a href="https://common-error.techidaily.com/warframe-update-not-working-heres-how-you-can-successfully-retry-the-process/"><u>Warframe Update Not Working? Here's How You Can Successfully Retry the Process</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-and-missing-cursor-mystery-solved-tips-and-fixes/"><u>Windows 10 and Missing Cursor Mystery Solved – Tips & Fixes!</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-1011-and-acer-keyboard-reconnectivity-restored/"><u>Windows 10/11 & Acer: Keyboard Reconnectivity Restored</u></a></li>
<li><a href="https://common-error.techidaily.com/wwe-2k-battlegrounds-troubleshooting-fixing-dx11-feature-level-100-error/"><u>WWE 2K Battlegrounds Troubleshooting - Fixing DX11 Feature Level 10.0 Error</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://otszone.ots7.com/order/checkout.php?PRODS=4713321&QTY=1&AFFILIATE=108875&CART=1"><img src="https://green.ots7.com/screenshots/OtsAV/OtsAVDJ1.90-300x188.jpg" border="0">OtsAV DJ Pro</a>
<!-- affiliate ads end -->