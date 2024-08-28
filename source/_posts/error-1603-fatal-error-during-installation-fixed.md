---
title: "Error 1603: Fatal Error During Installation [FIXED]"
date: 2024-08-27T13:37:43.553Z
updated: 2024-08-28T13:37:43.553Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error 1603: Fatal Error During Installation [FIXED]"
excerpt: "This Article Describes Error 1603: Fatal Error During Installation [FIXED]"
thumbnail: https://thmb.techidaily.com/6a865e452463a91a0991eeba9d7367cf47a6e9f955045ec39458749fd03f02a9.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=35038891&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.dupinout.com/wp-content/uploads/2021/12/DupInOut-New-Duplicate-Scan-Tab.png" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://modlily.sjv.io/c/5597632/1997817/17059" target="_top" id="1997817"><img src="//a.impactradius-go.com/display-ad/17059-1997817" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1997817/17059" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://twitter-videos.techidaily.com/new-in-2024-clear-your-twitter-timeline-fast-topunfollowtools-revealed/"><u>[New] In 2024, Clear Your Twitter Timeline Fast  #TopUnfollowTools Revealed</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-in-2024-conversational-courtesies-react-and-engage-on-discord-platforms/"><u>[New] In 2024, Conversational Courtesies  React and Engage on Discord Platforms</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-leveraging-innovative-features-a-guide-to-implementing-speech-inputs-in-powerpoint/"><u>[New] Leveraging Innovative Features  A Guide to Implementing Speech Inputs in PowerPoint</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-from-scripts-to-subscribers-mastering-the-production-of-engaging-educational-videos-for-youtube/"><u>[Updated] 2024 Approved  From Scripts to Subscribers  Mastering the Production of Engaging Educational Videos for YouTube</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-2024-approved-meditative-movement-youtubes-finest-yogis/"><u>[Updated] 2024 Approved  Meditative Movement  YouTube's Finest Yogis</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-directing-content-flow-uploading-imovie-films-to-youtube/"><u>[Updated] Directing Content Flow  Uploading IMovie Films to YouTube</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-best-price-to-performance-laptops-under-500-gaming-edition/"><u>2024 Approved  Best Price-to-Performance Laptops Under $500 (Gaming Edition)</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-perfecting-instagram-livestreams-with-obs-technology/"><u>2024 Approved  Perfecting Instagram Livestreams with OBS Technology</u></a></li>
<li><a href="https://common-error.techidaily.com/breeze-through-troubleshooting-fixing-the-permanent-0-on-your-windows-update/"><u>Breeze Through Troubleshooting: Fixing the Permanent 0%% on Your Windows Update</u></a></li>
<li><a href="https://fox-glue.techidaily.com/captivating-hdr-portraits-for-the-art-enthusiast-for-2024/"><u>Captivating HDR Portraits for the Art Enthusiast for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolving-missing-binkw32dll-errors-successfully/"><u>Comprehensive Guide: Resolving Missing BinkW32.dll Errors Successfully</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/enhance-visual-engagement-creating-pip-videos-on-macos-systems/"><u>Enhance Visual Engagement  Creating PIP Videos on macOS Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/enigmatic-obscurity-electronic-puzzle/"><u>Enigmatic Obscurity: Electronic Puzzle</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-resolving-connectivity-issues-with-your-bluetooth-mouse-in-windows-environment/"><u>Expert Advice: Resolving Connectivity Issues with Your Bluetooth Mouse in Windows Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-how-to-repair-binkw32dll-absence-warning/"><u>Expert Guide: How to Repair Binkw32.DLL Absence Warning</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-how-to-restore-connection-to-a-disconnected-external-hardware-on-windows/"><u>Expert Guide: How to Restore Connection to a Disconnected External Hardware on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-effortlessly-overcoming-the-crimson-screen-dilemma-on-any-system/"><u>Expert Tips: Effortlessly Overcoming the Crimson-Screen Dilemma on Any System</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/extensive-review-gecata-recording-device-analysis/"><u>Extensive Review  Gecata Recording Device Analysis</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/fixing-alienware-drivers-problems-on-windows-a-comprehensive-guide/"><u>Fixing Alienware Drivers Problems on Windows: A Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-get-back-lost-contacts-from-oppo-a79-5g-by-fonelab-android-recover-contacts/"><u>How to get back lost contacts from Oppo A79 5G.</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-deleted-realme-11-proplus-contacts-an-easy-method-explained-by-fonelab-android-recover-contacts/"><u>How to Restore Deleted Realme 11 Pro+ Contacts  An Easy Method Explained.</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-and-lower-wucltexe-cpu-impact-in-windows-11/"><u>How to Troubleshoot and Lower wuclt.exe CPU Impact in Windows 11</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-turn-off-the-screen-lock-on-my-vivo-s17e-by-drfone-android-unlock-android-unlock/"><u>How to turn off the screen lock on my Vivo S17e</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-to-fix-pokemon-go-route-not-working-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fix Pokemon Go Route Not Working On Vivo Y17s? | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-sim-unlock-huawei-nova-y91-phones-without-code-2-ways-to-remove-android-sim-lock-by-drfone-android/"><u>In 2024, Sim Unlock Huawei Nova Y91 Phones without Code 2 Ways to Remove Android Sim Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206753948-microsoft-print-to-pdf-not-working-in-windows-1011-heres-the-solution/"><u>Microsoft Print-to-PDF Not Working in Windows 10/11? Here's the Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/network-troubleshooting-mastery-overcoming-power-surges-at-network-junctions/"><u>Network Troubleshooting Mastery: Overcoming Power Surges at Network Junctions</u></a></li>
<li><a href="https://common-error.techidaily.com/retain-original-file-locations-with-every-windows-10-system-boot/"><u>Retain Original File Locations with Every Windows 10 System Boot</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-unrecognized-gpus-in-fortnite-windows/"><u>Troubleshooting and Fixing Unrecognized GPUs in Fortnite (Windows)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixtools-registration-error-in-windows-11/"><u>Troubleshooting FixTool's Registration Error in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-the-non-responsive-aoc-monitor-issue-on-windows-11/"><u>Troubleshooting Guide: Fixing the Non-Responsive AOC Monitor Issue on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211411398-troubleshooting-nier-automata-pc-game-freezing-issues-solved/"><u>Troubleshooting Nier: Automata PC Game Freezing Issues - Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-asus-webcam-display-problem-on-windows-11/"><u>Troubleshooting the ASUS Webcam Display Problem on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-to-fix-driverpowerstatefailure-errors-effectively/"><u>Troubleshooting Tips to Fix DRIVER_POWER_STATE_FAILURE Errors Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/victory-for-wow-enabling-comprehensive-3d-graphics/"><u>Victory for WoW: Enabling Comprehensive 3D Graphics</u></a></li>
<li><a href="https://fake-location.techidaily.com/which-is-the-best-fake-gps-joystick-app-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Which is the Best Fake GPS Joystick App On Realme GT 3? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-unregistered-class-in-windows-10-a-comprehensive-fix-guide/"><u>Winning the Battle Against Unregistered Class in Windows 10: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/your-2023-guide-best-applications-for-downloading-lite-facebook-videos/"><u>Your 2023 Guide  Best Applications for Downloading Lite Facebook Videos</u></a></li>
</ul></div>
