---
title: Bypassing Barriers in Upgrading to Windows 11 - Solving Error Code 80240020
date: 2024-08-15T11:05:48.836Z
updated: 2024-08-16T11:05:48.836Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Bypassing Barriers in Upgrading to Windows 11 - Solving Error Code 80240020
excerpt: This Article Describes Bypassing Barriers in Upgrading to Windows 11 - Solving Error Code 80240020
thumbnail: https://thmb.techidaily.com/ddf4423afddb9cc05befc8c29dab68251d90672059623bcb13035bb3744866c7.png
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-the-art-of-attraction-how-to-increase-video-likes-on-tiktok/"><u>[New] 2024 Approved  The Art of Attraction  How to Increase Video Likes on TikTok</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-2024-approved-utilizing-netflixs-floating-window-feature-effectively/"><u>[New] 2024 Approved  Utilizing Netflix's Floating Window Feature Effectively</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-actionable-techniques-for-efficient-media-conversion-chains/"><u>[Updated] 2024 Approved  Actionable Techniques for Efficient Media Conversion Chains</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-essential-tech-skills-record-on-hangouts/"><u>[Updated] Essential Tech Skills  Record on Hangouts</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-expert-filmmaking-skills-on-youtube-and-diverse-platforms-for-2024/"><u>[Updated] Expert Filmmaking Skills on YouTube and Diverse Platforms for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-uncomplicated-capture-efficient-screenshots-on-dell/"><u>[Updated] Uncomplicated Capture  Efficient Screenshots on Dell</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-a-year-end-curation-of-youtubes-most-compelling-stories/"><u>2024 Approved  A Year-End Curation of YouTube’s Most Compelling Stories</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-lava-blaze-2-pro-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Lava Blaze 2 Pro Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-guide-on-faking-your-location-in-mozilla-firefox-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>A Detailed Guide on Faking Your Location in Mozilla Firefox On Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-fixes-for-ps4-network-errors-a-detailed-walkthrough/"><u>Complete Fixes for PS4 Network Errors: A Detailed Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-the-unspecified-error-a-detailed-walkthrough-on-overcoming-0x80004005-issues/"><u>Decoding the 'Unspecified Error' - A Detailed Walkthrough on Overcoming 0X80004005 Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210984997-discords-silent-mic-no-more/"><u>Discord's Silent Mic: No More!</u></a></li>
<li><a href="https://common-error.techidaily.com/enduring-smooth-visuals-in-valorant-a-complete-guide-for-dealing-with-tech-glitches-and-tearing-fixes/"><u>Enduring Smooth Visuals in Valorant: A Complete Guide for Dealing with Tech Glitches and Tearing Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-11-muting-issues-a-step-by-step-guide/"><u>How to Fix Windows 11 Muting Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-forcefully-close-windows-11-when-your-computer-fails-to-turn-off/"><u>How to Forcefully Close Windows 11 When Your Computer Fails to Turn Off</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-malfunctioning-shift-key-a-step-by-step-guide/"><u>How to Repair a Malfunctioning Shift Key: A Step-by-Step Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-2-ways-to-monitor-honor-90-pro-activity-drfone-by-drfone-virtual-android/"><u>In 2024, 2 Ways to Monitor Honor 90 Pro Activity | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-3-ways-to-erase-apple-iphone-15-when-its-locked-within-seconds-drfone-by-drfone-ios/"><u>In 2024, 3 Ways to Erase Apple iPhone 15 When Its Locked Within Seconds | Dr.fone</u></a></li>
<li><a href="https://youtube-data.techidaily.com/24-how-to-buy-1-million-youtube-views-safely-from-trusted-providers/"><u>In 2024, How to Buy 1 Million YouTube Views Safely From Trusted Providers</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-to-come-up-with-the-best-pokemon-team-on-huawei-p60-drfone-by-drfone-virtual-android/"><u>In 2024, How to Come up With the Best Pokemon Team On Huawei P60? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-oppo-a56s-5g-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Oppo A56s 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-master-the-art-of-youtube-visibility-two-steps/"><u>In 2024, Master the Art of YouTube Visibility (Two Steps)</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-top-5-vivo-y78t-bypass-frp-tools-for-pc-that-actually-work-by-drfone-android/"><u>In 2024, Top 5 Vivo Y78t Bypass FRP Tools for PC That Actually Work</u></a></li>
<li><a href="https://youtube-web.techidaily.com/24-upgrade-your-online-presence-with-premium-webcam-tech/"><u>In 2024, Upgrade Your Online Presence with Premium Webcam Tech</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-oppo-find-n3-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Oppo Find N3 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-illumination-issues-solved-tips-for-macwindows-users/"><u>Keyboard Illumination Issues Solved: Tips for Mac/Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/monitor-connection-woes-step-by-step-solutions-for-video-input-troubles/"><u>Monitor Connection Woes: Step-by-Step Solutions for Video Input Troubles</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-chrome-unresponsiveness-efficient-methods-for-relaunching-your-browser/"><u>Overcome Chrome Unresponsiveness: Efficient Methods for Relaunching Your Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-high-cpu-usage-in-windows-by-fixing-the-audio-device-graph-isolation-problem/"><u>Resolve High CPU Usage in Windows by Fixing the Audio Device Graph Isolation Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-no-playable-sources-detected-errors-in-windows-gaming-a-comprehensive-guide/"><u>Resolving 'No Playable Sources Detected' Errors in Windows Gaming - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-error-1053-non-responsive-service-launch-failure/"><u>Resolving Error 1053: Non-Responsive Service Launch Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-minecraft-crashes-due-to-faulty-graphics-driver-issues-in-windows-solutions/"><u>Resolving Minecraft Crashes Due to Faulty Graphics Driver Issues in Windows - Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-remedies-to-address-frequent-system-hibernations-on-windows-and-macs/"><u>Simple Remedies to Address Frequent System Hibernations on Windows and Macs</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solution-resolving-the-steam-disk-write-error/"><u>Simple Solution: Resolving the Steam Disk Write Error</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-microphone-problems-on-steelseries-arctis-5-for-optimal-performance/"><u>Solving Microphone Problems on SteelSeries Arctis 5 for Optimal Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-disappearing-wi-fi-menu-issue-on-your-windows-11-device/"><u>Solving the Disappearing Wi-Fi Menu Issue on Your Windows 11 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-xerox-printing-update-error-0x800f020b-on-pcs-with-windows/"><u>Step-by-Step Fix for Xerox Printing Update Error 0X800f020b on PCs with Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-pc-connection-issues-with-bluetooth-input-devices/"><u>Step-by-Step Solution for PC Connection Issues with Bluetooth Input Devices</u></a></li>
<li><a href="https://windows11.techidaily.com/steps-to-resolve-active-directory-related-printer-errors-on-w11/"><u>Steps to Resolve Active Directory-Related Printer Errors on W11</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-when-your-microsoft-surface-wont-charge-even-though-its-connected-step-by-step-solution/"><u>The Ultimate Fix for When Your Microsoft Surface Won't Charge Even Though It’s Connected: Step-by-Step Solution!</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/updated-in-2024-from-forward-to-reverse-mastering-video-reversal-in-final-cut-pro/"><u>Updated In 2024, From Forward to Reverse Mastering Video Reversal in Final Cut Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/wwe-t-kt-battlegrounds-fixing-the-dx11-v100-compatibility-issue/"><u>WWE ˈtʊ Kɪtʃ 🥊Battlegrounds: Fixing the DX11 v10.0 Compatibility Issue</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->