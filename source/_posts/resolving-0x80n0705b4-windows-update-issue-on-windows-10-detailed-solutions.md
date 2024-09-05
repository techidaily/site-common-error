---
title: Resolving 0X80n0705b4 Windows Update Issue on Windows 10 [Detailed Solutions]
date: 2024-09-04T20:22:14.606Z
updated: 2024-09-05T20:22:14.606Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving 0X80n0705b4 Windows Update Issue on Windows 10 [Detailed Solutions]
excerpt: This Article Describes Resolving 0X80n0705b4 Windows Update Issue on Windows 10 [Detailed Solutions]
thumbnail: https://thmb.techidaily.com/0afc969a260468b6e52b6a33d1ca7e6eed63bd07ec976231956f9d4e1713d1ee.jpg
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-10-youtube-storytelling-techniques-that-work/"><u>[New] 2024 Approved  10 YouTube Storytelling Techniques That Work</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-in-2024-the-complete-guide-to-setting-up-streamlabs-obs/"><u>[New] In 2024, The Complete Guide to Setting Up Streamlabs OBS</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-mouse-scroll-wheel-jumps-win-1011/"><u>[SOLVED] Mouse Scroll Wheel Jumps Win 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/bring-back-normalcy-explorers-fix/"><u>Bring Back Normalcy - Explorer's Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-persistent-error-0x8024401c-in-your-windows-10-or-11-update-process-expert-advice-and-fixes/"><u>Bypassing the Persistent Error 0X8024401C in Your Windows 10 or 11 Update Process: Expert Advice and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/conquer-windows-11-restlessness-at-night/"><u>Conquer Windows 11 Restlessness at Night</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-stuck-during-start-up-master-these-techniques-to-resolve-initializing-glitches/"><u>Destiny 2 Stuck During Start-Up? Master These Techniques to Resolve Initializing Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-why-is-my-corsair-backlit-keyboard-not-working/"><u>Diagnosing & Repairing: Why Is My Corsair Backlit Keyboard Not Working?</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204948974-diy-repair-techniques-for-malfunctioning-usb-jacks-get-started-now/"><u>DIY Repair Techniques for Malfunctioning USB Jacks – Get Started Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-reboot-renderer-following-2021-enhancements/"><u>Effective Techniques to Reboot Renderer Following 2021 Enhancements</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-overcoming-compatibility-issues-between-microsoft-wireless-display-adapter-and-windows-11/"><u>Expert Tips: Overcoming Compatibility Issues Between Microsoft Wireless Display Adapter and Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-responsive-dns-server-quick-and-simple-methods/"><u>How to Fix a Non-Responsive DNS Server: Quick and Simple Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/hydraamic-retention-time-hrt-is-the-volume-of-the-tank-divided-by-the-flow-rate-or-hrt-volume-q/"><u>Hydraamic Retention Time (HRT) Is the Volume of the Tank Divided by the Flow Rate, or HRT = Volume / Q.</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-a-step-by-step-guide-to-finding-your-apple-id-from-your-apple-iphone-14-pro-max-by-drfone-ios/"><u>In 2024, A Step-by-Step Guide to Finding Your Apple ID From Your Apple iPhone 14 Pro Max</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-premier-8k-capture-the-ultimate-camera-guide/"><u>In 2024, Premier 8K Capture  The Ultimate Camera Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-simple-and-effective-ways-to-change-your-country-on-youtube-app-of-your-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, Simple and Effective Ways to Change Your Country on YouTube App Of your Vivo Y27 4G | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-motorola-defy-2-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Motorola Defy 2? | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-look-at-the-asus-zephyrus-g14-uncompromising-performance-for-gamers/"><u>In-Depth Look at the ASUS Zephyrus G14 - Uncompromising Performance for Gamers</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/mastering-social-media-video-for-superior-fb-outcomes/"><u>Mastering Social Media Video for Superior FB Outcomes</u></a></li>
<li><a href="https://win11-tips.techidaily.com/mastering-the-art-how-to-skip-windows-11-lock/"><u>Mastering the Art: How to Skip Windows 11 Lock</u></a></li>
<li><a href="https://windows11.techidaily.com/my-top-pick-the-understated-notepad-application-for-windows-users/"><u>My Top Pick: The Understated Notepad Application for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/optimize-system-performance-solving-audio-device-memory-leak-on-windows/"><u>Optimize System Performance: Solving Audio Device Memory Leak on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/optimize-your-system-cut-down-dwm-related-gpu-strain-on-windows-computers/"><u>Optimize Your System: Cut Down DWM Related GPU Strain on Windows Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-game-crashes-in-wolfenstein-ii-resolving-write-error-for-crash-files/"><u>Overcoming Game Crashes in Wolfenstein II - Resolving Write Error for Crash Files</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-windows-7-updating-process-a-comprehensive-guide/"><u>Overcoming Issues with Windows 7 Updating Process – A Comprehensive Guide</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/raid-rebound-hardware-haven/"><u>RAID Rebound: Hardware Haven</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-quick-guide-to-fixing-error-1053-unresponsive-service-delays/"><u>Resolved Issue: Quick Guide to Fixing 'Error 1053: Unresponsive Service' Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11-boot-loop-problems-for-a-smooth-computer-shutdown/"><u>Resolving Windows 11 Boot Loop Problems for a Smooth Computer Shutdown</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-rockstar-games-red-dead-redemption-2-memory-issues-increase-pagefile-size/"><u>Solution for Rockstar Games Red Dead Redemption 2 Memory Issues – Increase Pagefile Size</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-methods-to-thaw-out-an-unresponsive-laptop-or-desktop/"><u>Solved! Methods to Thaw Out an Unresponsive Laptop or Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-when-your-steam-store-wont-load-correctly/"><u>Step-by-Step Solution: When Your Steam Store Won't Load Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-resolved-fixing-the-error-application-failed-to-launch-properly-error-code-0xc000007b/"><u>Successfully Resolved: Fixing the Error 'Application Failed to Launch Properly (Error Code 0xC000007B)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-vivo-g2-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-realme-12-proplus-5g-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Realme 12 Pro+ 5G Location | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-gpu-load-caused-by-the-desktop-window-manager-on-windows-11/"><u>Top 5 Solutions for Reducing GPU Load Caused by the Desktop Window Manager on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-unresponsive-usb-input-devices-in-windows-7/"><u>Troubleshoot and Fix Unresponsive USB Input Devices in Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-windows-11-error-code-0x800f0922-a-comprehensive-guide-to-8-essential-solutions/"><u>Troubleshoot Windows 11 Error CODE 0X800f0922: A Comprehensive Guide to 8 Essential Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-volume-error-0x80071ac3-steps-for-data-recovery/"><u>Troubleshooting Volume Error 0X80071AC3: Steps for Data Recovery</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-steelseries-arctis-5-headset-solving-mic-problems-easily/"><u>Troubleshooting Your SteelSeries Arctis 5 Headset: Solving Mic Problems Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-svchostexes-role-in-network-usage-solutions-to-optimize-your-pc/"><u>Understanding Svchost.exe's Role in Network Usage: Solutions to Optimize Your PC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030385/7443" target="_top" id="2030385">
  <img src="//a.impactradius-go.com/display-ad/7443-2030385" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030385/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->