---
title: "Resolving the 0X80072EFD Error on Windows 10: A Step-by-Step Guide"
date: 2024-09-04T20:21:08.517Z
updated: 2024-09-05T20:21:08.517Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the 0X80072EFD Error on Windows 10: A Step-by-Step Guide"
excerpt: "This Article Describes Resolving the 0X80072EFD Error on Windows 10: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/4622c737506cba1a23868ce6098299cf82c4724d17bc893106f7883eb3c1b7e3.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://facebook-video-footage.techidaily.com/new-building-wealth-through-video-content-revenue-for-2024/"><u>[New] Building Wealth Through Video Content Revenue for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-remove-google-chrome-critical-error-scam/"><u>[Solved] How to Remove Google Chrome Critical Error SCAM</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-crafting-artful-pictures-on-android-devices/"><u>[Updated] Crafting Artful Pictures on Android Devices</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-enhance-video-magic-find-your-favorite-mobile-edit-apps/"><u>[Updated] Enhance Video Magic  Find Your Favorite Mobile Edit Apps</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-top-5-driving-and-race-replicas/"><u>[Updated] Top 5 Driving & Race Replicas</u></a></li>
<li><a href="https://android-location.techidaily.com/10-fake-gps-location-apps-on-android-of-your-tecno-phantom-v-fold-drfone-by-drfone-virtual/"><u>10 Fake GPS Location Apps on Android Of your Tecno Phantom V Fold | Dr.fone</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-changing-video-pace-on-your-instagram-feed/"><u>2024 Approved  Changing Video Pace on Your Instagram Feed</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-integrating-websites-into-your-instagram-presence/"><u>2024 Approved  Integrating Websites Into Your Instagram Presence</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-transform-your-visual-storytelling-with-clear-backdrops-in-figma/"><u>2024 Approved  Transform Your Visual Storytelling with Clear Backdrops in Figma</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-tecno-spark-20-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Tecno Spark 20 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-update-blues-fix-miracast-unsupported-by-this-device-easy-steps/"><u>Beat The Update Blues: Fix 'Miracast Unsupported by This Device' Easy Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-walkthrough-repairing-the-black-monitor-problem-for-dell-computer-users/"><u>Complete Walkthrough: Repairing the Black Monitor Problem for Dell Computer Users</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-tackle-videodxgkrnl-fatal-issues-on-windows-machines/"><u>Comprehensive Solutions to Tackle Video_Dxgkrnl Fatal Issues on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/device-driver-error-resolved-ensuring-full-compatibility-within-wow-and-windows/"><u>Device Driver Error Resolved: Ensuring Full Compatibility Within WoW & Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-tackling-error-0xc1900208-on-windows-11-updates-solved/"><u>Effective Remedies for Tackling Error 0xC1900208 on Windows 11 Updates [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-guide-to-reconnecting-your-chromecast-for-smooth-streaming/"><u>Effortless Guide to Reconnecting Your Chromecast for Smooth Streaming</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-playtime-awaits-correcting-your-origin-game-installation-problems/"><u>Error-Free Playtime Awaits: Correcting Your Origin Game Installation Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-getting-your-dell-camera-up-and-running-in-windows/"><u>Expert Tips: Getting Your Dell Camera Up and Running in Windows</u></a></li>
<li><a href="https://printer-issues.techidaily.com/five-tips-to-reignite-the-print-on-your-canon-printer-in-windows-11-os/"><u>Five Tips to Reignite the Print on Your Canon Printer in Windows 11 OS</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-dolby-home-theater-not-working-issue-in-windows-10/"><u>Fix Dolby Home Theater Not Working Issue in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-wd-my-passport-ultra-missing-from-windows-device-manager/"><u>Fixing the Issue: WD My Passport Ultra Missing From Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-mystery-how-to-stop-your-computer-from-unexpected-shutdowns/"><u>Fixing the Mystery: How to Stop Your Computer From Unexpected Shutdowns</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-silent-issue-complete-guide-on-resolving-no-audio-in-forza-horizon-4/"><u>Fixing the Silent Issue: Complete Guide on Resolving No Audio in Forza Horizon 4</u></a></li>
<li><a href="https://article-helps.techidaily.com/gaming-gains-total-earnings-for-pewdiepie/"><u>Gaming Gains  Total Earnings for PewDiePie</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-enabling-bluetooth-connectivity-in-windows-7-solutions-revealed/"><u>Guide: Enabling Bluetooth Connectivity in Windows 7 - Solutions Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-eliminate-endless-loading-times-on-skyrim-a-solution/"><u>How to Eliminate Endless Loading Times on Skyrim – A Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209798973-how-to-fix-a-stagnant-windows-update-process-resolved/"><u>How to Fix a Stagnant Windows Update Process: Resolved!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-error-code-0x80073cf9-and-successfully-use-windows-11-store-again/"><u>How to Overcome Error Code 0X80073CF9 & Successfully Use Windows 11 Store Again</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-right-click-capabilities-for-mice-on-your-windows-11-pc/"><u>How to Restore Right-Click Capabilities for Mice on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-set-up-battleye-anti-cheat-problems-solved/"><u>How To Successfully Set Up BattlEye Anti-Cheat: Problems Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-a-surface-device-thats-plugged-in-but-fails-to-charge/"><u>How To Troubleshoot: A Surface Device That's Plugged In But Fails to Charge</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-livestream-tactics-best-practices-for-cricket-viewers/"><u>In 2024, Top Livestream Tactics  Best Practices for Cricket Viewers</u></a></li>
<li><a href="https://common-error.techidaily.com/in-depth-analysis-how-mismatched-drivers-lead-to-breached-security-in-ftdi-bus-systems/"><u>In-Depth Analysis: How Mismatched Drivers Lead to Breached Security in FTDI Bus Systems</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/instant-time-stamping-techniques-for-youtube-videos-for-2024/"><u>Instant Time-Stamping Techniques for YouTube Videos for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/macx-dvd-ripper-pro-shop-securely-and-enjoy-special-offers-today/"><u>MacX DVD Ripper Pro: Shop Securely & Enjoy Special Offers Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212458133-master-the-art-of-connecting-hdmi-devices-with-a-windows-11-system-no-more-frustrations/"><u>Master the Art of Connecting HDMI Devices with a Windows 11 System: No More Frustrations</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/mastering-the-art-of-efficient-workflow-capturing-mac-screens-with-just-shortcuts/"><u>Mastering the Art of Efficient Workflow  Capturing Mac Screens with Just Shortcuts</u></a></li>
<li><a href="https://common-error.techidaily.com/new-world-overcomes-previous-easy-anti-cheat-issues-now-fully-functional/"><u>New World Overcomes Previous Easy Anti-Cheat Issues: Now Fully Functional</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcoming-errors-successfully-running-amd-radeon-software-installation/"><u>Overcoming Errors: Successfully Running AMD Radeon Software Installation</u></a></li>
<li><a href="https://sound-issues.techidaily.com/quick-solutions-for-low-sound-output-on-a-windows-10-computer/"><u>Quick Solutions for Low Sound Output on a Windows 10 Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-gaming-halt-quick-fix-for-pc-pauses/"><u>Resolve Gaming Halt: Quick Fix for PC Pauses</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-stop-the-constant-flicker-of-your-computer-cursor/"><u>Resolved: Stop the Constant Flicker of Your Computer Cursor</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/screen-recording-essentials-and-competitive-analyses-for-2024/"><u>Screen Recording Essentials and Competitive Analyses for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/simplify-your-experience-with-windows-10s-file-explorer-expert-advice/"><u>Simplify Your Experience with Windows 10'S File Explorer - Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-symbol-issues-a-step-by-step-guide/"><u>Solving '@' Symbol Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-of-windows-update-failed-understanding-and-fixing-error-code-0x80070643/"><u>Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-wacom-pen-input-on-upgraded-windows-11-systems/"><u>Step-by-Step Guide to Restoring Wacom Pen Input on Upgraded Windows 11 Systems</u></a></li>
<li><a href="https://video-capture.techidaily.com/streamline-screen-capturing-in-todays-remote-meetings-for-2024/"><u>Streamline Screen Capturing in Today’s Remote Meetings for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/streamline-win11s-performance-with-provider-host-fixes/"><u>Streamline Win11's Performance with Provider Host Fixes</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/surpassing-peers-standing-out-in-the-vimeo-staffs-choices/"><u>Surpassing Peers  Standing Out in the Vimeo Staff's Choices</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208217755-the-ultimate-fix-guide-for-overcoming-error-1068-in-windows-expert-advice-included/"><u>The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-your-unprintable-pdf-with-these-easy-fixes/"><u>Troubleshoot Your Unprintable PDF with These Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-a-non-responsive-microsoft-keyboard/"><u>Troubleshooting Guide for a Non-Responsive Microsoft Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-night-light-issues-on-windows-11-devices/"><u>Troubleshooting Guide: Night Light Issues on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolve-your-airpods-connection-issues-on-windows-11-top-strategies/"><u>Troubleshooting Guide: Resolve Your AirPods Connection Issues on Windows 11 - Top Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-the-windows-blue-screen-of-death-bsod-with-error-code-c00000e9/"><u>Troubleshooting Guide: Solving the Windows Blue Screen of Death (BSoD) with Error Code C00000e9</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/vloggers-money-saving-camera-recommendations-for-2024/"><u>Vloggers' Money-Saving Camera Recommendations for 2024</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118306/7443" target="_top" id="2118306">
  <img src="//a.impactradius-go.com/display-ad/7443-2118306" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118306/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->