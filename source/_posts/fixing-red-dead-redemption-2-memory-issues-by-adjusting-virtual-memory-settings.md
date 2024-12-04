---
title: Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
date: 2024-11-26T23:07:25.021Z
updated: 2024-12-04T04:25:08.045Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
excerpt: This Article Describes Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
thumbnail: https://thmb.techidaily.com/be26802ef5bb50783815300426404d3fea7e0b5a3f7f648e31ee7c5865304f02.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-masterful-text-effects-in-adobe-after-effects/"><u>[New] 2024 Approved Masterful Text Effects in Adobe After Effects</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-advanced-accessories-for-immersive-gaming-worlds/"><u>[New] In 2024, Advanced Accessories for Immersive Gaming Worlds</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-navigating-live-streams-on-youtube-and-twitch-with-ease-via-obs/"><u>2024 Approved Navigating Live Streams on YouTube & Twitch with Ease via OBS</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-handling-and-correcting-missing-d3dx9nn-dll-files-in-your-programs/"><u>Expert Tips for Handling and Correcting Missing D3dx9_nN Dll Files in Your Programs</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-bluetooth-missing-from-windows-device-manager/"><u>Fix Guide: Bluetooth Missing From Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-installation-glitches-for-origin-platform-gaming-titles/"><u>Guide to Fixing Installation Glitches for Origin Platform Gaming Titles</u></a></li>
<li><a href="https://common-error.techidaily.com/hassle-free-guide-to-correcting-windows-update-error-code-0x80070eb5/"><u>Hassle-Free Guide to Correcting Windows Update Error Code 0X80070eb5</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-configure-your-drivers-when-you-encounter-set-user-settings-to-driver-failed/"><u>How to Correctly Configure Your Drivers When You Encounter 'Set User Settings To Driver Failed'</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-update-error-code-0x8024002e-easily/"><u>How to Fix Windows Update Error Code 0X8024002E Easily!</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-asus-rog-phone-8-pro-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Asus ROG Phone 8 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-a-network-locked-vivo-t2-5g-phone-by-drfone-android/"><u>How to Unlock a Network Locked Vivo T2 5G Phone?</u></a></li>
<li><a href="https://common-error.techidaily.com/make-your-aoc-screen-function-again-in-win10-step-by-step-guide/"><u>Make Your AOC Screen Function Again in Win10: Step-by-Step Guide</u></a></li>
<li><a href="https://facebook.techidaily.com/nbafire-up-on-both-platforms-this-year/"><u>NBAFire Up on Both Platforms This Year</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-display-issues-missing-touchpad-and-hardware-buttons-functionality/"><u>Resolving Display Issues: Missing Touchpad and Hardware Buttons Functionality</u></a></li>
<li><a href="https://fake-location.techidaily.com/thinking-about-changing-your-netflix-region-without-a-vpn-on-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>Thinking About Changing Your Netflix Region Without a VPN On Tecno Camon 20? | Dr.fone</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unboxing-the-new-2024-dell-xps-14-a-game-changing-laptop-you-need-to-try/"><u>Unboxing the New 2024 Dell XPS 14: A Game-Changing Laptop You Need to Try!</u></a></li>
<li><a href="https://games-able.techidaily.com/unleash-full-power-of-docked-steam-deck-with-easy-tweaks/"><u>Unleash Full Power of Docked Steam Deck with Easy Tweaks</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-usb-success-stories-overcoming-port-reset-failed-hurdles-on-your-windows-11-machine/"><u>Unlocking USB Success Stories: Overcoming 'Port Reset Failed' Hurdles on Your Windows 11 Machine</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/why-the-affordable-apple-m3-macbook-pro-is-a-must-have-for-professionals-unveiling-its-single-compelling-feature-zdnet/"><u>Why the Affordable Apple M3 MacBook Pro Is a Must-Have for Professionals: Unveiling Its Single Compelling Feature | ZDNet</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aqeO4ed766s?si=AWtKHxP4hvQRd_lk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

