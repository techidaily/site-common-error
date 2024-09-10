---
title: "Critical System Failure: Devices at End"
date: 2024-09-09T09:00:08.167Z
updated: 2024-09-10T09:00:08.167Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Critical System Failure: Devices at End"
excerpt: "This Article Describes Critical System Failure: Devices at End"
thumbnail: https://thmb.techidaily.com/07877b725aebcc26ce626860ff1aa31b598ca62f4a725eae923eeb25fe929021.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2128843/7443" target="_top" id="2128843">
  <img src="//a.impactradius-go.com/display-ad/7443-2128843" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2128843/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123479/16836" target="_top" id="2123479">
  <img src="//a.impactradius-go.com/display-ad/16836-2123479" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123479/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115921/19272" target="_top" id="2115921">
  <img src="//a.impactradius-go.com/display-ad/19272-2115921" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115921/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://common-error.techidaily.com/fixed-windows-11-start-menu-not-working/"><u>[FIXED] Windows 11 Start Menu Not Working</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-archive-hunt-accessing-yesteryears-facebook-stories/"><u>[New] 2024 Approved Archive Hunt Accessing Yesteryear's Facebook Stories</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-hp-laptop-tutorial-easy-webcam-video-recording-steps/"><u>[New] 2024 Approved HP Laptop Tutorial Easy Webcam Video Recording Steps</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/024-approved-mic-selection-made-easy-optimal-picks-for-vloggers-educators-and-more/"><u>[New] 2024 Approved Mic Selection Made Easy Optimal Picks for Vloggers, Educators & More</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-standout-methods-for-fb-ad-visualization/"><u>[New] Standout Methods for FB Ad Visualization</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-device-not-migrated-on-windows-11/"><u>[Solved] Device Not Migrated on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-steam-content-servers-unreachable/"><u>[Solved] Steam Content Servers Unreachable</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-top-5-platforms-for-active-engagement-outside-of-twitter/"><u>[Updated] 2024 Approved Top 5 Platforms For Active Engagement Outside of Twitter</u></a></li>
<li><a href="https://extra-information.techidaily.com/updated-a-step-by-step-guide-to-mastering-morphvox-modifications/"><u>[Updated] A Step-by-Step Guide to Mastering MorphVOX Modifications</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-in-2024-silent-spectators-manual-mastering-the-art-of-private-instagram-story-watching-pcandroidios/"><u>[Updated] In 2024, Silent Spectator's Manual Mastering the Art of Private Instagram Story Watching [PC/Android/iOS]</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-learn-to-redefine-your-instagram-sound-with-ease/"><u>[Updated] Learn to Redefine Your Instagram Sound with Ease</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-tips-for-overcoming-obs-screen-blackout/"><u>[Updated] Tips for Overcoming OBS Screen Blackout</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-elevating-your-igtv-visuals-cover-photos-update/"><u>2024 Approved Elevating Your IGTV Visuals Cover Photos Update</u></a></li>
<li><a href="https://fox-info.techidaily.com/2024-approved-mastery-in-making-advanced-tiktok-editing-techniques/"><u>2024 Approved Mastery in Making Advanced TikTok Editing Techniques</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-navigating-apples-content-downloading-with-ease/"><u>2024 Approved Navigating Apple's Content Downloading with Ease</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-obsudio-screen-recorder-analysis-your-best-choices-explored/"><u>2024 Approved Obsudio Screen Recorder Analysis Your Best Choices Explored</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-reality-redefined-exploring-virtualitys-kin-vr-ar-and-mr/"><u>2024 Approved Reality Redefined Exploring Virtuality’s Kin - VR, AR, & MR</u></a></li>
<li><a href="https://common-error.techidaily.com/asus-laptop-issue-resolved-enabling-and-repairing-function-keys-that-wont-work-anymore/"><u>ASUS Laptop Issue Resolved: Enabling and Repairing Function Keys That Won't Work Anymore</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-installation-issues-resolved-a-comprehensive-guide/"><u>BattlEye Installation Issues Resolved - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-buffs-expert-hacks-for-fast-tracking-league-of-legends-game-setup/"><u>Bypass Buffs: Expert Hacks for Fast-Tracking League of Legends Game Setup</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/championed-by-artists-the-top-6-nft-maker-tools/"><u>Championed by Artists The Top 6 NFT Maker Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/dota-2-solve-error-2024-with-quick-api-adjustment-tips/"><u>Dota 2: Solve Error 2024 with Quick 'API Adjustment' Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-fixes-for-undetected-bluetooth-gadgets-on-your-windows-11-pc/"><u>Easy Fixes for Undetected Bluetooth Gadgets on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-resolving-your-netflix-audio-problems-in-a-jiffy/"><u>Easy Solutions: Resolving Your Netflix Audio Problems in a Jiffy</u></a></li>
<li><a href="https://common-error.techidaily.com/eclipse-effect-screen-issue/"><u>Eclipse Effect: Screen Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-remove-unwanted-vertical-or-horizontal-lines-appearing-on-screen/"><u>Effective Techniques to Remove Unwanted Vertical or Horizontal Lines Appearing On Screen</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/enhance-ideas-a-compilation-of-top-5-ai-writers/"><u>Enhance Ideas: A Compilation of Top 5 AI Writers</u></a></li>
<li><a href="https://common-error.techidaily.com/execution-path-blocked/"><u>Execution Path Blocked</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-fixing-a-stuck-or-failed-windows-feature-update-to-version-1903/"><u>Expert Advice on Fixing a Stuck or Failed Windows Feature Update to Version 1903</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/expert-tips-and-fixes-for-overcoming-fatal-pnp-detected-error-messages-in-windows-11/"><u>Expert Tips and Fixes for Overcoming Fatal 'PNP Detected' Error Messages in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/fallout-4-performance-optimized-how-to-overcome-lag-issues-tips-players/"><u>Fallout 4 Performance Optimized: How to Overcome Lag Issues (Tips Players)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208830902-fix-windows-update-error-code-0x80070002-step-by-step-guide/"><u>Fix Windows Update Error Code 0X80070002 - Step-by-Step Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-frozen-google-chrome-do-you-need-to-restart/"><u>Fixing a Frozen Google Chrome: Do You Need to Restart?</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-non-functional-dell-webcam-on-windows-step-by-step-guide/"><u>Fixing a Non-Functional Dell Webcam on Windows: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-non-compatible-hardware-drivers-for-a-smoother-world-of-warcraft-experience/"><u>Fixing Non-Compatible Hardware Drivers for a Smoother World of Warcraft Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-endless-reboot-cycle-tips-for-pcs-stuck-at-startup/"><u>Fixing the Endless Reboot Cycle: Tips for PCs Stuck at Startup</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-can-honor-magic-v2mirror-share-to-pc-drfone-by-drfone-android/"><u>How Can Honor Magic V2Mirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211467650-how-to-get-your-astro-a40s-mic-up-and-running-again/"><u>How To Get Your Astro A40's Mic Up and Running Again</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/in-2024-10-youtube-music-rippers-for-android-and-ios/"><u>In 2024, 10 YouTube Music Rippers for Android and iOS</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-apple-id-locked-or-disabled-on-apple-iphone-se-2022-7-mehtods-you-cant-miss-by-drfone-ios/"><u>In 2024, Apple ID Locked or Disabled On Apple iPhone SE (2022)? 7 Mehtods You Cant-Miss</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-delete-icloud-account-from-iphone-7-plus-without-password-by-drfone-ios/"><u>In 2024, How to Delete iCloud Account From iPhone 7 Plus without Password?</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-the-insider-guide-elevating-your-instagram-imagery/"><u>In 2024, The Insider Guide Elevating Your Instagram Imagery</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-winning-scenarios-prime-video-recording-software-for-windows/"><u>In 2024, Winning Scenarios Prime Video Recording Software for Windows</u></a></li>
<li><a href="https://fox-info.techidaily.com/instabeats-intellectual-property-overview-for-2024/"><u>InstaBeats Intellectual Property Overview for 2024</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-oppo-a78-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Oppo A78 – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/navigating-the-landscape-of-automated-moderation-in-digital-dialogues/"><u>Navigating the Landscape of Automated Moderation in Digital Dialogues</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-fading-audio-in-adobe-rush-for-2024/"><u>New Fading Audio in Adobe Rush for 2024</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-in-2024-create-cartoons-like-a-pro-top-10-tools-for-beginners/"><u>New In 2024, Create Cartoons Like a Pro Top 10 Tools for Beginners</u></a></li>
<li><a href="https://win-howtos.techidaily.com/obs-game-capturing-woes-fix-that-perplexing-black-screen-issue-today/"><u>OBS Game Capturing Woes? Fix That Perplexing Black Screen Issue Today</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-how-to-resolve-undetected-battery-problems/"><u>Quick Troubleshooting: How to Resolve Undetected Battery Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-warframe-update-issues-fixed/"><u>Resolving 'Warframe Update' Issues: Fixed</u></a></li>
<li><a href="https://win-answers.techidaily.com/resolving-the-new-world-connection-issue-step-by-step-guide/"><u>Resolving the 'New World Connection Issue': Step-by-Step Guide</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/reviving-retro-tech-the-impressive-similarities-of-8bitdos-latest-mechanical-keyboard-to-the-iconic-ibm-model-m/"><u>Reviving Retro Tech: The Impressive Similarities of 8BitDo's Latest Mechanical Keyboard to the Iconic IBM Model M</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/shopback-up-specialists-judgment/"><u>ShopBack Up Specialists' Judgment</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-failed-to-initialize-network-problem-in-dragon-ball-fighterz-expert-guide/"><u>Solving the 'Failed to Initialize Network' Problem in Dragon Ball FighterZ - Expert Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-microsoft-print-to-pdf-malfunction-in-windows-11-systems/"><u>Solving the Microsoft Print to PDF Malfunction in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-correcting-error-0xc000007b-for-successful-program-launches/"><u>Step-by-Step Guide: Correcting Error 0xC000007B for Successful Program Launches</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-guide-restoring-your-lost-untitled-microsoft-office-documents/"><u>Step-by-Step Guide: Restoring Your Lost, Untitled Microsoft Office Documents</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-connecting-your-microsoft-dock-with-windows-10-resolved/"><u>Step-by-Step Solution for Connecting Your Microsoft Dock with Windows 10 [Resolved]</u></a></li>
<li><a href="https://win-solutions.techidaily.com/step-by-step-solution-to-stop-infinite-loads-in-anthem-game/"><u>Step-by-Step Solution to Stop Infinite Loads in Anthem Game</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-high-gpu-consumption-by-the-desktop-window-manager-on-windows-10-and-11/"><u>Top 5 Solutions for Reducing High GPU Consumption by the Desktop Window Manager on Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/top-solutions-to-resolve-the-werfaultexe-crashing-issue-in-windows-systems/"><u>Top Solutions to Resolve the werFault.exe Crashing Issue in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solutions-for-windows-resource-protection-failures/"><u>Troubleshooting and Solutions for Windows Resource Protection Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-0x800f020b-successful-updates-for-your-xerox-printer-on-windows/"><u>Troubleshooting Error 0X800F020B: Successful Updates for Your Xerox Printer on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixes-for-non-responsive-dell-bluetooth-keyboard/"><u>Troubleshooting Guide: Fixes for Non-Responsive Dell Bluetooth Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-get-dell-webcam-operational-on-windows-systems/"><u>Troubleshooting Guide: How to Get Dell Webcam Operational on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-a-non-responsive-razer-keyboard/"><u>Troubleshooting Steps for a Non-Responsive Razer Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-windows-11-problem-found-during-system-reset-complete-solution-walkthrough/"><u>Troubleshooting the Windows 11 Problem Found During System Reset - Complete Solution Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixing-malfunctioning-function-keyboard-buttons/"><u>Troubleshooting Tips: Fixing Malfunctioning Function Keyboard Buttons</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/understanding-what-makes-asmr-videos-special/"><u>Understanding What Makes ASMR Videos Special</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-honor-x50i-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Honor X50i Users</u></a></li>
<li><a href="https://apple-account.techidaily.com/why-apple-account-disabled-on-your-apple-iphone-14-plus-how-to-fix-by-drfone-ios/"><u>Why Apple Account Disabled On your Apple iPhone 14 Plus? How to Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209267175-windows-10-screen-saver-troubles-here-are-the-fixes/"><u>Windows 10 Screen Saver Troubles? Here Are the Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-mastered-achieving-restful-sleep/"><u>Windows 11 Mastered: Achieving Restful Sleep</u></a></li>
</ul></div>
