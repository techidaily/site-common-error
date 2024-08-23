---
title: Solutions for Fixing CRC-Related Data Errors Effectively
date: 2024-08-22T19:12:57.556Z
updated: 2024-08-23T19:12:57.556Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solutions for Fixing CRC-Related Data Errors Effectively
excerpt: This Article Describes Solutions for Fixing CRC-Related Data Errors Effectively
thumbnail: https://thmb.techidaily.com/98b85ce6d797323413c6bf7e018c1d8e6594fdbbf15afde0abd2d98dfde1d7e0.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=22741618&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.diskpart.com/resource/images/index/dp-index-img-banner-people@2x.png" border="0">Easy and Safe Partition Software & Hard Disk Manager</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://natural-cycles.sjv.io/c/5597632/2072199/17885" target="_top" id="2072199"><img src="//a.impactradius-go.com/display-ad/17885-2072199" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2072199/17885" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37540879&QTY=1&AFFILIATE=108875&CART=1"><img src="https://paperscan.orpalis.com/img/content/You_prefer_to_use.png" border="0">PaperScan Professional： PaperScan Scanner Software is a powerful TWAIN & WIA scanning application centered on one idea: making document acquisition an unparalleled easy task for anyone.</a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://mushroom-supplies.sjv.io/c/5597632/1692242/18134" target="_top" id="1692242"><img src="//a.impactradius-go.com/display-ad/18134-1692242" border="0" alt="" width="834" height="592"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1692242/18134" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://digital-screen-recording.techidaily.com/new-harnessing-power-at-no-cost-guide-to-hosting-and-participating-in-gmeet/"><u>[New] Harnessing Power at No Cost  Guide to Hosting & Participating in GMeet</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-complete-breakdown-enhancing-your-experience-with-advanced-mobizen-techniques/"><u>[New] In 2024, Complete Breakdown  Enhancing Your Experience with Advanced Mobizen Techniques</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-unlocking-the-power-of-thumbnails-creating-visual-appeal-for-youtube-content/"><u>[New] In 2024, Unlocking the Power of Thumbnails  Creating Visual Appeal for YouTube Content</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-obs-vs-shadowplay-which-recording-tool-takes-the-prize-in-2024/"><u>[New] OBS Vs ShadowPlay  Which Recording Tool Takes the Prize, In 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-lifetime-favorites-reddits-highly-endorsed-top-10/"><u>[Updated] Lifetime Favorites  Reddit's Highly-Endorsed Top 10</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-skyrocketing-popularity-on-igtv-with-powerful-targeted-hash-tags/"><u>[Updated] Skyrocketing Popularity on IGTV with Powerful, Targeted Hash Tags</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-the-echo-of-past-interactions-unraveling-your-facebook-history/"><u>[Updated] The Echo of Past Interactions  Unraveling Your Facebook History</u></a></li>
<li><a href="https://common-error.techidaily.com/access-denied-on-your-computer-install-the-necessary-printer-drivers-first/"><u>Access Denied on Your Computer? Install the Necessary Printer Drivers First</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-for-mending-missing-audio-dll-files/"><u>Easy Steps for Mending Missing Audio DLL Files</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-battling-screen-flicker-in-windows-10-environment/"><u>Effective Solutions for Battling Screen Flicker in Windows 10 Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208629437-event-id-1000-explained-for-windows-users-7810-finding-solutions-easily/"><u>Event ID 1000 Explained for Windows Users (7/8/10): Finding Solutions Easily!</u></a></li>
<li><a href="https://win-howtos.techidaily.com/1723202021194-expert-advice-on-correcting-windows-update-failure-with-error-code-0x8024402c-learn-how-here/"><u>Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-that-hush-restoring-functional-speakers-in-your-acer-computer/"><u>Fix That Hush: Restoring Functional Speakers in Your Acer Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-total-war-rome-remastered-game-crashes-solutions-inside/"><u>Fixing Total War Rome Remastered Game Crashes: Solutions Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-a-deficiency-in-xinput13dll/"><u>How to Address a Deficiency in XINPUT1_3.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-hosted-network-not-starting-issue-in-windows-11-solutions-proven-effective/"><u>How to Fix 'Hosted Network Not Starting' Issue in Windows 11 - Solutions Proven Effective</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-msvcp140dll-is-missing-the-right-way/"><u>How to Fix 'MSVCP140.dll Is Missing' The Right Way</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-windows-11-running-smoothly-after-update-hiccups/"><u>How to Get Your Windows 11 Running Smoothly After Update Hiccups</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-unavailable-desktop-error-on-system-profile-folder/"><u>How to Overcome Unavailable Desktop Error on System Profile Folder</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-windows-update-problems-a-comprehve-guide/"><u>How to Overcome Windows Update Problems - A Comprehve Guide</u></a></li>
<li><a href="https://techidaily.com/how-to-perform-hard-reset-on-huawei-p60-drfone-by-drfone-reset-android-reset-android/"><u>How to Perform Hard Reset on Huawei P60? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-couldnt-load-plugin-errors-on-chrome-in-windows-11/"><u>How to Resolve 'Couldn't Load Plugin' Errors on Chrome in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-excessive-cpu-drain-caused-by-windows-audio-device-isolation/"><u>How to Resolve Excessive CPU Drain Caused by Windows Audio Device Isolation</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-address-unregistered-class-errors-in-windows-11-systems/"><u>How To Successfully Address Unregistered Class Errors in Windows 11 Systems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-honor-80-pro-straight-screen-edition-to-laptop-without-usb-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Honor 80 Pro Straight Screen Edition to Laptop Without USB | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-use-google-assistant-on-your-lock-screen-of-realme-gt-neo-5-se-phone-by-drfone-android/"><u>How to Use Google Assistant on Your Lock Screen Of Realme GT Neo 5 SE Phone</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-knowledge-keepers-premier-10-tools-to-record-teaching-sessions/"><u>In 2024, Knowledge Keepers  Premier 10 Tools to Record Teaching Sessions</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-sim-unlock-code-generators-unlock-your-honor-100-pro-phone-hassle-free-by-drfone-android/"><u>In 2024, The Best Android SIM Unlock Code Generators Unlock Your Honor 100 Pro Phone Hassle-Free</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211684915-keyboard-issues-fix-inactive-letters-on-your-win-10-or-win-11-system-today/"><u>Keyboard Issues? Fix Inactive Letters on Your Win 10 or Win 11 System Today!</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-solve-fcpx-plugin-issues-troubleshooting-guide-for-2024/"><u>New Solve FCPX Plugin Issues Troubleshooting Guide for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-miracast-issues-with-graphics-driver-now-compatible/"><u>Resolved Miracast Issues with Graphics Driver - Now Compatible</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/resolved-overcome-stuttering-glitches-in-fallout-76/"><u>Resolved: Overcome Stuttering Glitches in Fallout 76</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-to-overcome-preparing-to-configure-windows-issue/"><u>Resolved: Step-by-Step Guide to Overcome 'Preparing to Configure Windows' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-version-1607-update-failure-during-setup/"><u>Resolving Windows 10 Version 1_607 Update Failure During Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/simplify-your-experience-using-windows-10-file-explorer-features/"><u>Simplify Your Experience Using Windows 10 File Explorer Features</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-aoc-usb-monitor-malfunction-errors-in-windows-11-step-by-step-guide/"><u>Solving AOC USB Monitor Malfunction Errors in Windows 11 - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-enable-wwe-2k-battlegrounds-with-directx-11-feature-level-100/"><u>Solving the Issue: Enable WWE 2K Battlegrounds with DirectX 11, Feature Level 10.0</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-get-your-dell-usb-connections-working-perfectly-again/"><u>Step-by-Step Guide to Get Your Dell USB Connections Working Perfectly Again</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-tackling-svchostexes-heavy-cpu-load-on-windows-11-systems/"><u>Step-by-Step Solutions for Tackling svchost.exe's Heavy CPU Load on Windows 11 Systems</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-essential-guide-to-win10s-video-grabbing-software/"><u>The Essential Guide to Win10's Video Grabbing Software</u></a></li>
<li><a href="https://common-error.techidaily.com/top-tips-for-fixing-audio-services-unresponsive-issues-in-windows-11/"><u>Top Tips for Fixing 'Audio Services Unresponsive' Issues in Windows 11</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-ranked-gaming-systems-in-22024/"><u>Top-Ranked Gaming Systems in 2#2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-class-registration-issues-in-windows-10-solution-steps/"><u>Troubleshooting Class Registration Issues in Windows 10 - Solution Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-restore-functionality-on-a-malfunctioning-dell-keyboardmouse/"><u>Troubleshooting Guide: How To Restore Functionality on a Malfunctioning Dell Keyboard/Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-resolving-the-semaphore-timeout-period-error-code-0x80070079/"><u>Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/unova-stone-pokemon-go-evolution-list-and-how-catch-them-for-nubia-red-magic-8s-pro-drfone-by-drfone-virtual-android/"><u>Unova Stone Pokémon Go Evolution List and How Catch Them For Nubia Red Magic 8S Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/windowslinux-users-beware-how-to-tackle-unwarranted-high-cpu-usage-from-shell-infrastructures/"><u>Windows/Linux Users Beware – How to Tackle Unwarranted High CPU Usage From Shell Infrastructures!</u></a></li>
</ul></div>
