---
title: "Step-by-Step Solution: Eliminating Windows 11 Update Failure (Error 0X8024401C)"
date: 2024-08-27T13:34:00.101Z
updated: 2024-08-28T13:34:00.101Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Solution: Eliminating Windows 11 Update Failure (Error 0X8024401C)"
excerpt: "This Article Describes Step-by-Step Solution: Eliminating Windows 11 Update Failure (Error 0X8024401C)"
thumbnail: https://thmb.techidaily.com/95b8d87ab463f7ac2adc7d19611917fbcf5034fba80cc910d2cfc1667a896a93.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://shop.dbschema.com/order/checkout.php?PRODS=19867419&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/176b22bab4e94a28619ca2433b2ef241/products/1_icon256.png" border="0">
DbSchema database designer for all databases, schema design in the team, schema deployment, interactive diagrams, documentation, data and query tools. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-leads-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://youtube-sure.techidaily.com/024-approved-amplify-youtube-visibility-crafting-effective-descriptions-and-tags/"><u>[New] 2024 Approved  Amplify YouTube Visibility  Crafting Effective Descriptions & Tags</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-2024-approved-stream-viewer-unraveler/"><u>[New] 2024 Approved  Stream Viewer Unraveler</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-best-youtube-live-streaming-software-and-hardware-you-should-know-for-2024/"><u>[New] Best YouTube Live Streaming Software and Hardware You Should Know for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-in-2024-diy-gif-creation-extracting-motion-from-youtube-videos/"><u>[New] In 2024, DIY GIF Creation  Extracting Motion From YouTube Videos</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-sync-your-storytelling-iphone-captures-words-and-pictures/"><u>[New] Sync Your Storytelling  IPhone Captures Words and Pictures</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-unsubscribing-disconnecting-desktop-discords/"><u>[New] Unsubscribing  Disconnecting Desktop Discords</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-2024-approved-streamlabs-versus-obs-the-ultimate-showdown/"><u>[Updated] 2024 Approved  Streamlabs Versus OBS  The Ultimate Showdown</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-in-depth-insights-perfecting-the-craft-of-screen-recording-on-macbooks/"><u>[Updated] In 2024, In-Depth Insights  Perfecting the Craft of Screen Recording on MacBooks</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-in-2024-ultimate-screen-snapper-unlocking-zd-softwares-potential/"><u>[Updated] In 2024, Ultimate Screen Snapper  Unlocking ZD Software's Potential</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-low-budget-camera-buys-roundup/"><u>[Updated] Low-Budget Camera Buys Roundup</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-perfecting-google-meet-ppt-sessions-on-desktoptablet-for-2024/"><u>[Updated] Perfecting Google Meet PPT Sessions on Desktop/Tablet for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-shield-yourself-online-strategies-to-hide-visual-identities/"><u>[Updated] Shield Yourself Online  Strategies to Hide Visual Identities</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-music-to-video-seamless-audio-import-for-inshot/"><u>2024 Approved  Music to Video  Seamless Audio Import for InShot</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-syncing-sounds-to-visuals-online/"><u>2024 Approved  Syncing Sounds to Visuals Online</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-lava-yuva-3-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Lava Yuva 3 | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-tecno-pova-5-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Tecno Pova 5 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/banish-your-minecraft-lag-easy-troubleshooting-steps-you-must-know/"><u>Banish Your Minecraft Lag: Easy Troubleshooting Steps You Must Know!</u></a></li>
<li><a href="https://common-error.techidaily.com/breezy-fixes-to-jumpstart-windows-updates-stalled-at-the-start-line/"><u>Breezy Fixes to Jumpstart Windows Updates Stalled at the Start Line</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-deadlock-successful-strategies-for-fixing-irreparable-directx-issues/"><u>Bypassing the Deadlock: Successful Strategies for Fixing Irreparable DirectX Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolve-windows-the-port-reset-failed-problem-of-your-usb-device/"><u>Comprehensive Guide: Resolve Windows The 'Port Reset Failed' Problem of Your USB Device</u></a></li>
<li><a href="https://common-error.techidaily.com/couldnt-switch-to-requested-monitor-resolution-solved/"><u>Couldn't Switch to Requested Monitor Resolution [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/crackle-free-audio-experience-repairing-speaker-issues-for-windows-107-users/"><u>Crackle-Free Audio Experience: Repairing Speaker Issues for Windows 10/7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0x8024402c-on-windows-updates-a-comprehensive-fix-tutorial/"><u>Error 0X8024402c on Windows Updates - A Comprehensive Fix Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-correcting-opengl-glitches-in-minecraft/"><u>Expert Tips for Correcting OpenGL Glitches in Minecraft</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-what-to-do-when-you-encounter-a-missing-d3dx939dll-error-message/"><u>Fix Guide: What to Do When You Encounter a Missing d3dx9_39.dll Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-device-cant-be-found-during-cast-error-on-windows-11-step-by-step-guide/"><u>Fixing 'Device Can't Be Found During Cast' Error on Windows 11 - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/game-setup-troubles-heres-how-origin-fixes-common-playing-hurdles/"><u>Game Setup Troubles? Here's How Origin Fixes Common Playing Hurdles</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/here-are-some-pro-tips-for-pokemon-go-pvp-battles-on-realme-narzo-n53-drfone-by-drfone-virtual-android/"><u>Here are Some Pro Tips for Pokemon Go PvP Battles On Realme Narzo N53 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-malfunctioning-wireless-mouse-in-windows-11-and-10-troubleshooting-guide/"><u>How to Fix a Malfunctioning Wireless Mouse in Windows 11 & 10: Troubleshooting Guide</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-behind-the-screencast-scenes-industry-secrets-revealed/"><u>In 2024, Behind the Screencast Scenes  Industry Secrets Revealed</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-best-practices-choosing-exceptional-cloud-services/"><u>In 2024, Best Practices  Choosing Exceptional Cloud Services</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-expert-approved-audio-editing-software-top-8-picks/"><u>In 2024, Expert-Approved Audio Editing Software Top 8 Picks</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-whatsapp-messages-on-nokia-c110-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track WhatsApp Messages on Nokia C110 Without Them Knowing? | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-swipe-for-success-the-art-of-flipping-videos-on-instagram/"><u>In 2024, Swipe for Success  The Art of Flipping Videos on Instagram</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-why-does-the-pokemon-go-battle-league-not-available-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, Why does the pokemon go battle league not available On Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/inquiring-into-the-benefit-of-verified-online-self-portraits/"><u>Inquiring Into the Benefit of Verified Online Self-Portraits</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-when-your-torrent-file-wont-start-downloading/"><u>Overcoming Issues when Your Torrent File Won’t Start Downloading</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-performance-lags-in-windows-11-a-step-by-step-guide/"><u>Overcoming Performance Lags in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/preventing-ftddi-memory-integrity-failures-by-ensuring-driver-compatibility/"><u>Preventing FTDDI Memory Integrity Failures by Ensuring Driver Compatibility</u></a></li>
<li><a href="https://games-able.techidaily.com/reign-supreme-on-twitch-with-these-7-streamer-assistants/"><u>Reign Supreme on Twitch With These 7 Streamer Assistants</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-2021s-common-browser-initialization-glitches/"><u>Resolve 2021'S Common Browser Initialization Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-compatibility-problems-how-to-correct-incorrect-sxs-configurations-in-windows-10-guide/"><u>Resolve Compatibility Problems: How to Correct Incorrect SxS Configurations in Windows 10 [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-tips-for-fixing-the-windows-configuration-is-incomplete-error/"><u>Resolved: Tips for Fixing the 'Windows Configuration Is Incomplete' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-lenovo-laptops-dead-pixels-fixes-for-unresponsive-keys/"><u>Reviving Your Lenovo Laptop's Dead Pixels: Fixes for Unresponsive Keys</u></a></li>
<li><a href="https://common-error.techidaily.com/smooth-playback-success-how-to-eliminate-kodis-constant-buffering/"><u>Smooth Playback Success: How to Eliminate Kodi's Constant Buffering</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-snapshot-eliminate-the-has-stopped-working-warning-for-32bit-print-drivers/"><u>Solution Snapshot: Eliminate the 'Has Stopped Working' Warning for 32Bit Print Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-mouse-keeps-double-clicking/"><u>Solved: Mouse Keeps Double Clicking</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-functionality-in-a-lenovo-keyboard-issue/"><u>Step-by-Step Guide to Restoring Functionality in a Lenovo Keyboard Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-the-failed-to-load-client-profile-error-caused-by-incorrect-side-by-side-settings-in-windows-10/"><u>Step-by-Step Solution for the 'Failed To Load Client Profile' Error Caused by Incorrect Side-by-Side Settings in Windows 10</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/steps-for-correcting-critical-error-code-c1900101-in-windows-11-upgrade/"><u>Steps for Correcting Critical Error Code: C1900101 in Windows 11 Upgrade</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/streamlined-capturing-top-5-mac-tools-for-effective-snipping-for-2024/"><u>Streamlined Capturing  Top 5 Mac Tools for Effective Snipping for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/system-slumber-windows-1110-wont-respond/"><u>System Slumber: Windows 11/10 Won't Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-troubleshooting-checklist-for-windows-updates-error-0x8007001f/"><u>The Ultimate Troubleshooting Checklist for Windows Updates Error 0X8007001f</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-updating-to-windows-11-v1607-heres-what-you-need-to-know/"><u>Trouble with Updating to Windows 11 v1607? Here's What You Need to Know</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-bluetooth-issues-and-getting-it-running-on-your-windows-7-pc/"><u>Troubleshooting Bluetooth Issues and Getting It Running on Your Windows 7 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204813863-troubleshooting-guide-for-total-war-rome-remastered-stability-issues-solution-found/"><u>Troubleshooting Guide for Total War Rome Remastered Stability Issues - SOLUTION FOUND</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-unpairing-and-pairing-airpods-to-your-window-laptopdesktop-2024-update/"><u>Troubleshooting Steps for Unpairing and Pairing AirPods to Your Window Laptop/Desktop - 2024 Update</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-solving-the-mystery-of-sudden-computer-shutdowns/"><u>Troubleshooting: Solving the Mystery of Sudden Computer Shutdowns</u></a></li>
<li><a href="https://some-tips.techidaily.com/unveiling-the-ultimate-iphone-selfie-sticks-8-for-2024/"><u>Unveiling the Ultimate IPhone Selfie Sticks (#8) for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208775208-usb-composite-device-cant-work-properly-with-usb-30-solved/"><u>USB Composite Device Can't Work Properly with USB 3.0 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/wheel-alignment-keep-your-wheels-properly-aligned-to-reduce-undue-stress-on-suspension-components-misalignment-can-cause-premature-wear-and-potentially-dama66/"><u>Wheel Alignment: Keep Your Wheels Properly Aligned to Reduce Undue Stress on Suspension Components. Misalignment Can Cause Premature Wear and Potentially Damage Other Parts of the Vehicle if Not Addressed Promptly</u></a></li>
<li><a href="https://common-error.techidaily.com/win11-optimization-addressing-excessive-provider-host-usage/"><u>Win11 Optimization: Addressing Excessive Provider Host Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203397428-windows-update-failure-overcome-error-8007000e-with-ease-and-speed/"><u>Windows Update Failure? Overcome Error 8007000E with Ease and Speed</u></a></li>
</ul></div>
