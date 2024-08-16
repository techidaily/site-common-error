---
title: "Error 1603 Decoded: Strategies for a Successful Software Installation Fix"
date: 2024-08-15T10:55:13.176Z
updated: 2024-08-16T10:55:13.176Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error 1603 Decoded: Strategies for a Successful Software Installation Fix"
excerpt: "This Article Describes Error 1603 Decoded: Strategies for a Successful Software Installation Fix"
thumbnail: https://thmb.techidaily.com/a88de5655376206e2ee17661cb9dd03b46b68bf81e7fb9a2b0bcd4cf8d7ba0d8.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2092236/16384" target="_top" id="2092236"><img src="//a.impactradius-go.com/display-ad/16384-2092236" border="0" alt="" width="1920" height="329"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2092236/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4742929&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/boxshot(2).png" border="0">Kanto Player Professional</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1892108/21290" target="_top" id="1892108"><img src="//a.impactradius-go.com/display-ad/21290-1892108" border="0" alt="" width="1080" height="1080"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1892108/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-optimize-obs-encoding-quick-solutions/"><u>[New] In 2024, Optimize OBS Encoding  Quick Solutions</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-enhanced-audio-guide-engaging-interview-topics/"><u>[Updated] 2024 Approved  Enhanced Audio Guide  Engaging Interview Topics</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-instagram-disconnect-watch-stay-ahead/"><u>[Updated] 2024 Approved  Instagram Disconnect Watch  Stay Ahead</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-engaging-audiences-perfecting-the-art-of-igtv-titles-and-summaries/"><u>[Updated] In 2024, Engaging Audiences  Perfecting the Art of IGTV Titles & Summaries</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-initiate-impactful-engagement-configuring-and-assessing-instream-ads-in-fb-for-2024/"><u>[Updated] Initiate Impactful Engagement  Configuring and Assessing Instream Ads in FB for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-innovating-human-interface-a-guide-to-hand-perception/"><u>[Updated] Innovating Human Interface  A Guide to Hand Perception</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/2024-approved-advanced-strategies-for-exceptional-color-grading-via-3d-lut-filters/"><u>2024 Approved  Advanced Strategies for Exceptional Color Grading via 3D LUT Filters</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-fast-tracked-fine-arts-edits-made-easy-with-windows-10-paint-application/"><u>2024 Approved  Fast-Tracked Fine Arts  Edits Made Easy with Windows 10 Paint Application</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-the-definitive-guide-to-android-mobas-10-winners/"><u>2024 Approved  The Definitive Guide to Android MOBAs  #10 Winners</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-and-repairing-undetected-device-errors-via-bluetooth-on-windows-11-platforms/"><u>Addressing and Repairing Undetected Device Errors via Bluetooth on Windows 11 Platforms</u></a></li>
<li><a href="https://howto.techidaily.com/android-screen-stuck-general-samsung-galaxy-a54-5g-partly-screen-unresponsive-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Screen Stuck General Samsung Galaxy A54 5G Partly Screen Unresponsive | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/aoc-monitor-connection-issues-troubleshooting-and-fixes-for-non-responsive-screen-in-windows-10/"><u>AOC Monitor Connection Issues: Troubleshooting and Fixes for Non-Responsive Screen in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/battle-tested-solutions-to-overcome-wwe-2ks-feature-level-10-error-in-dx11-environments/"><u>Battle-Tested Solutions to Overcome WWE 2K's Feature Level 10 Error in DX11 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-glitch-successfully-turn-off-your-computer-running-windows-11-now-solved/"><u>Beat the Glitch: Successfully Turn Off Your Computer Running Windows 11 – Now Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/best-practices-for-preventing-writing-mistakes-in-protected-or-non-writable-memory-regions/"><u>Best Practices for Preventing Writing Mistakes in Protected or Non-Writable Memory Regions</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-how-to-fix-pubg-mobile-building-glitches-effectively/"><u>Complete Guide: How To Fix PUBG Mobile Building Glitches Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-broken-or-corrupted-file-structures-in-windows-11/"><u>Comprehensive Fixes for Broken or Corrupted File Structures in Windows 11</u></a></li>
<li><a href="https://fox-info.techidaily.com/creating-compelling-montage-images-step-by-step-for-2024/"><u>Creating Compelling Montage Images Step by Step for 2024</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciphering-0xc0000185-error-code-tips-to-restore-your-computers-stability/"><u>Deciphering 0xC0000185 Error Code - Tips to Restore Your Computer's Stability</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-constant-pc-mouse-detachment-problems-for-smooth-usage/"><u>Diagnosing and Repairing Constant PC Mouse Detachment Problems for Smooth Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-ways-to-restore-your-laptops-microphone-functionality/"><u>Effective Ways to Restore Your Laptop's Microphone Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-effortless-solutions-to-stop-your-laptop-from-freezing-up/"><u>Expert Advice: Effortless Solutions to Stop Your Laptop From Freezing Up</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205128970-how-to-fix-lenovo-mouse-pad-issues-on-windows-11-8-and-7-solutions-included/"><u>How to Fix Lenovo Mouse Pad Issues on Windows 11, 8 & 7 - Solutions Included</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-stuck-or-non-updating-windows-10-problems-easily/"><u>How to Overcome Stuck or Non-Updating Windows 10 Problems Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211027005-how-to-prevent-auto-sleep-on-pc-or-laptop-easy-steps-inside/"><u>How to Prevent Auto-Sleep on PC or Laptop - Easy Steps Inside!</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-remove-find-my-iphone-without-apple-id-from-your-apple-iphone-13-mini-by-drfone-ios/"><u>How to Remove Find My iPhone without Apple ID From your Apple iPhone 13 mini?</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-xiaomi-13t-pro-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Xiaomi 13T Pro Phone? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changefake-your-oneplus-12-location-on-viber-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Fake Your OnePlus 12 Location on Viber | Dr.fone</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/in-2024-how-to-translate-videos-in-tamil-for-a-wider-reach/"><u>In 2024, How To Translate Videos in Tamil for a Wider Reach</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-to-use-ispoofer-on-realme-11-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to use iSpoofer on Realme 11 Pro? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-magnificent-art-of-pokemon-go-streaming-on-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, The Magnificent Art of Pokemon Go Streaming On Realme Note 50? | Dr.fone</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/in-2024-the-ultimate-video-editing-experience-for-vimeo-enthusiasts/"><u>In 2024, The Ultimate Video Editing Experience for Vimeo Enthusiasts</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/instagram-follower-deletion-identification/"><u>Instagram Follower Deletion Identification</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-mousepad-not-working-in-windows-1187-solved/"><u>Laptop Mousepad Not Working in Windows 11/8/7 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/logitech-mouse-woes-repairing-a-stuck-or-broken-scroll-wheel/"><u>Logitech Mouse Woes: Repairing a Stuck or Broken Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-for-event-id-1000-across-different-generations-of-windows-os/"><u>Mastering the Fix for Event ID 1000 Across Different Generations of Windows OS</u></a></li>
<li><a href="https://howto.techidaily.com/oppo-a2-not-connecting-to-wi-fi-12-quick-ways-to-fix-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Oppo A2 Not Connecting to Wi-Fi? 12 Quick Ways to Fix | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solution-for-missing-bluetooth-devices-on-your-windows-10-pc/"><u>Quick Solution for Missing Bluetooth Devices on Your Windows 10 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-the-bluetooth-not-found-error-in-windows-10-step-by-step-guide/"><u>Resolve the 'Bluetooth Not Found' Error in Windows 10 - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-pc-restoration-hiccups-the-ultimate-guide-for-windows-11-users/"><u>Resolve Your PC Restoration Hiccups: The Ultimate Guide for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-with-creating-directx-devices-on-your-system/"><u>Resolved: Issue with Creating DirectX Devices on Your System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-could-not-install-windows-cuhild-with-error-code-80240020/"><u>Resolving the 'Could Not Install Windows Cuhild' With Error Code 80240020</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-successfully-linking-your-bluetooth-keyboard-to-laptopdesktop/"><u>Solution Guide: Successfully Linking Your Bluetooth Keyboard to Laptop/Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-missing-device-drivers-warnings-in-windows-7-setup-guide/"><u>Troubleshooting the Missing Device Drivers Warnings in Windows 7 Setup [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/why-did-my-warframe-update-fail-common-causes-and-solutions/"><u>Why Did My Warframe Update Fail? Common Causes and Solutions</u></a></li>
</ul></div>
