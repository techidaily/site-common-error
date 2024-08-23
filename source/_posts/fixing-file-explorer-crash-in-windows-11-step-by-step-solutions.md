---
title: Fixing File Explorer Crash in Windows 11 – Step-by-Step Solutions
date: 2024-08-22T19:21:28.247Z
updated: 2024-08-23T19:21:28.247Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing File Explorer Crash in Windows 11 – Step-by-Step Solutions
excerpt: This Article Describes Fixing File Explorer Crash in Windows 11 – Step-by-Step Solutions
thumbnail: https://thmb.techidaily.com/06768f0764e3fd16593ec6ab66fe93ff9404677c09f36129dabffcc95362a115.jpg
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
<li><a href="https://screen-video-capture.techidaily.com/new-deciphering-bandicams-latest-2023-capabilities-for-2024/"><u>[New] Deciphering Bandicam's Latest 2023 Capabilities for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-ideal-marketplace-for-customized-box-masterpieces-for-2024/"><u>[New] Ideal Marketplace For Customized Box Masterpieces for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-accelerating-or-slowing-down-youtube-videos-playback/"><u>[New] In 2024, Accelerating or Slowing Down YouTube Videos Playback</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-easy-guide-to-screenshots-and-recordings-with-macos/"><u>[New] In 2024, Easy Guide to Screenshots & Recordings with macOS</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/new-in-2024-expert-evaluation-best-action-capture-systems/"><u>[New] In 2024, Expert Evaluation  Best Action Capture Systems</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/new-seamless-transfer-of-tiktok-content-to-your-facebook-page-for-2024/"><u>[New] Seamless Transfer of TikTok Content to Your Facebook Page for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-the-ultimate-amazon-prime-series-most-liked-and-watched-on-twitter-for-2024/"><u>[New] The Ultimate Amazon Prime Series  Most Liked & Watched on Twitter for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-when-your-mouse-cursor-goes-missing-in-windows-win-10-a-step-by-step-solution/"><u>[Troubleshooting] When Your Mouse Cursor Goes Missing in Windows (Win) [10]: A Step-by-Step Solution.</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-gain-on-ig-unveiling-high-payoff-content-strategies/"><u>[Updated] 2024 Approved  Gain on IG  Unveiling High-Payoff Content Strategies</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-design-strategies-for-top-tier-valorant-thumbnails-on-social-media/"><u>[Updated] Design Strategies for Top-Tier Valorant Thumbnails on Social Media</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-sonic-and-the-hedgehog-switch-edition-top-10/"><u>[Updated] In 2024, Sonic and the Hedgehog  Switch Edition (Top 10)</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-in-2024-the-art-of-color-grading-employing-luts-from-cg-central/"><u>[Updated] In 2024, The Art of Color Grading  Employing LUTs From CG Central</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/10-pro-tips-for-effortless-android-recording-for-2024/"><u>10 Pro Tips for Effortless Android Recording for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-high-quality-action-captured-by-the-ion-pro-3-camera/"><u>2024 Approved  High-Quality Action Captured by the ION Pro 3 Camera</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-the-clearer-picture-remove-borders-and-boost-recording-quality/"><u>2024 Approved  The Clearer Picture  Remove Borders and Boost Recording Quality</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ovative-workout-challenges-for-dynamic-viewers/"><u>9 Innovative Workout Challenges for Dynamic Viewers</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/amplify-your-wifi-game-with-netgears-advanced-nighthawk-x6s-extender/"><u>Amplify Your WiFi Game with Netgear's Advanced Nighthawk X6S Extender</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-0x80072efd-blues-easy-repairs-for-windows-10-users/"><u>Beat the 0X80072EFD Blues: Easy Repairs for Windows 10 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-blues-beat-windows-11s-pairing-problems-with-these-expert-solutions/"><u>Bluetooth Blues? Beat Windows 11'S Pairing Problems with These Expert Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-keyboard-issues-heres-how-you-can-get-it-working-again/"><u>Corsair Keyboard Issues? Here's How You Can Get It Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/directory-corruption-solved-effective-strategies-for-file-repair/"><u>Directory Corruption Solved: Effective Strategies for File Repair</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/dive-into-french-novels-best-list-for-beginning-readers/"><u>Dive Into French Novels: Best List for Beginning Readers</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-navigation-and-troubleshooting-for-windows-10s-file-explorer/"><u>Effortless Navigation and Troubleshooting for Windows 10'S File Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-0x80072f8f-on-windows-1110-top-solutions-to-restore-your-pcs-functionality/"><u>Error Code 0X80072F8F on Windows 11/10: Top Solutions to Restore Your PC's Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/fec-codes-like-reed-solomon-can-correct-detected-errors-without-retransmission/"><u>FEC Codes Like Reed-Solomon Can Correct Detected Errors without Retransmission.</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-lenovo-mouse-pad-problems-on-windows-1187-effective-solutions-and-workarounds/"><u>Fix Your Lenovo Mouse Pad Problems on Windows 11/8/7 - Effective Solutions and Workarounds</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-resolved-problem-windows-error-code-1067-premature-process-end/"><u>Fixing the Issue: Resolved Problem - Windows Error Code 1#067: Premature Process End</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-persistent-device-error-code-28-on-your-windows-machine-step-by-step-tutorial/"><u>Fixing the Persistent Device Error Code 28 on Your Windows Machine – Step-by-Step Tutorial</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/high-fidelity-mp4-streamer-to-facebook/"><u>High-Fidelity MP4 Streamer to Facebook</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-fix-a-malfunctioning-mic-on-your-computer-system/"><u>How To Diagnose and Fix a Malfunctioning Mic on Your Computer System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-and-troubleshoot-the-persistent-windows-update-issue-error-0x802c4022/"><u>How to Fix and Troubleshoot the Persistent Windows Update Issue (Error 0X802C4022)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-brightness-controls-on-a-non-responsive-windows-10-display/"><u>How to Restore Brightness Controls on a Non-Responsive Windows 10 Display</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-silence-your-ps4s-overheating-problem-a-step-by-step-guide/"><u>How to Silence Your PS4's Overheating Problem – A Step-by-Step Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-3-ways-to-unlock-iphone-7-without-passcode-or-face-id-by-drfone-ios/"><u>In 2024, 3 Ways to Unlock iPhone 7 without Passcode or Face ID</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-building-your-screencasting-skills-from-the-ground-up/"><u>In 2024, Building Your Screencasting Skills From the Ground Up</u></a></li>
<li><a href="https://video-capture.techidaily.com/in-2024-efficient-movie-file-management-in-windows-11-six-approaches/"><u>In 2024, Efficient Movie File Management in Windows 11  Six Approaches</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-lock-apps-on-samsung-galaxy-a34-5g-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Samsung Galaxy A34 5G to Protect Your Individual Information</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-wondering-the-best-alternative-to-hola-on-vivo-y27-4g-here-is-the-answer-drfone-by-drfone-virtual-android/"><u>In 2024, Wondering the Best Alternative to Hola On Vivo Y27 4G? Here Is the Answer | Dr.fone</u></a></li>
<li><a href="https://fix-guide.techidaily.com/my-videos-arent-playing-on-honor-90-lite-what-can-i-do-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>My Videos Arent Playing on Honor 90 Lite – What Can I Do? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-dysfunctional-function-keys-a-step-by-step-guide/"><u>Overcoming the Challenge of Dysfunctional Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-unresponsive-file-explorer-effective-fixes-for-windows-10-users-solved/"><u>Overcoming Unresponsive File Explorer: Effective Fixes for Windows 10 Users [Solved]</u></a></li>
<li><a href="https://extra-resources.techidaily.com/petite-plot-puzzle-piece/"><u>Petite Plot Puzzle Piece</u></a></li>
<li><a href="https://extra-support.techidaily.com/precision-practices-for-perfecting-figmas-background-removal-for-2024/"><u>Precision Practices for Perfecting Figma's Background Removal for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-device-unprepared-message-a-step-by-step-guide/"><u>Resolving the 'Device Unprepared' Message: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-0x80t70541-update-issue-successfully/"><u>Resolving the Windows 11 0X80t70541 Update Issue Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11-scrolling-woes-tips-and-techniques-for-a-smooth-touchpad-experience/"><u>Resolving Windows 11 Scrolling Woes: Tips and Techniques for a Smooth Touchpad Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-your-windows-11-copy-and-paste-malfunction-easily/"><u>Resolving Your Windows 11 'Copy & Paste' Malfunction Easily</u></a></li>
<li><a href="https://extra-skills.techidaily.com/restore-pristine-photos-easily-discover-top-10-online-enhancers-for-2024/"><u>Restore Pristine Photos Easily  Discover Top 10 Online Enhancers for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/simplify-installing-latest-lexmark-printer-driver/"><u>Simplify Installing Latest Lexmark Printer Driver</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/step-by-step-how-to-conduct-real-time-calls-via-whatsapp-on-pc-for-2024/"><u>Step by Step  How to Conduct Real-Time Calls via WhatsApp on PC for 2024</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/step-by-step-guide-mastering-the-art-of-splitting-your-screen-on-macbook-air/"><u>Step-by-Step Guide: Mastering the Art of Splitting Your Screen on MacBook Air</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-your-laptops-touchpad-from-activating-tips-for-windows-10-users/"><u>Stop Your Laptop's Touchpad From Activating: Tips for Windows 10 Users</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-developers-guide-to-chatgpt-in-vs-code/"><u>The Developer's Guide to ChatGPT in VS Code</u></a></li>
<li><a href="https://common-error.techidaily.com/top-strategies-to-overcome-wow-performance-drops-and-enjoy-uninterrupted-gaming/"><u>Top Strategies to Overcome Wow Performance Drops & Enjoy Uninterrupted Gaming</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-screen-stuttering-and-flickering-problems-on-windows-11-devices/"><u>Troubleshooting Screen Stuttering and Flickering Problems on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/uncover-hidden-network-adapters-solving-windows-11s-wi-fi-dilemma/"><u>Uncover Hidden Network Adapters: Solving Windows 11'S Wi-Fi Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-xinput13dll-and-troubleshooting-its-absence/"><u>Understanding XINPUT1_3.dll & Troubleshooting Its Absence</u></a></li>
<li><a href="https://common-error.techidaily.com/unlit-display-random-outage/"><u>Unlit Display: Random Outage</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-the-beginning-of-windows-11-where-and-how-to-find-the-start-button/"><u>Unlocking the Beginning of Windows 11: Where and How to Find the Start Button</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/updated-which-video-editor-reigns-supreme-final-cut-pro-vs-lumafusion-review/"><u>Updated Which Video Editor Reigns Supreme? Final Cut Pro vs LumaFusion Review</u></a></li>
<li><a href="https://common-error.techidaily.com/valorant-players-rejoice-learn-the-proven-methods-to-resolve-unwanted-screen-tearing-instantly/"><u>Valorant Players Rejoice! Learn the Proven Methods to Resolve Unwanted Screen Tearing Instantly</u></a></li>
<li><a href="https://common-error.techidaily.com/valorant-teardown-ultimate-solutions-for-smooth-gameplay/"><u>Valorant Teardown: Ultimate Solutions for Smooth Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/win11-pcs-restart-at-odd-hours/"><u>Win11 PCs Restart at Odd Hours</u></a></li>
<li><a href="https://common-error.techidaily.com/xinput13dll-explained-essentiality-and-recovery-steps/"><u>XINPUT1_3.dll Explained: Essentiality and Recovery Steps</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->