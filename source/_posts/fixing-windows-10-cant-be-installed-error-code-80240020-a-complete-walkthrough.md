---
title: "Fixing 'Windows 10 Can't Be Installed' Error Code 80240020: A Complete Walkthrough"
date: 2024-08-22T19:13:05.992Z
updated: 2024-08-23T19:13:05.992Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing 'Windows 10 Can't Be Installed' Error Code 80240020: A Complete Walkthrough"
excerpt: "This Article Describes Fixing 'Windows 10 Can't Be Installed' Error Code 80240020: A Complete Walkthrough"
thumbnail: https://thmb.techidaily.com/ab4dd483e1f79e38d09cf8e4fff380926562633e9bf3ddc744f9f9ddbc0ddf17.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://vapordna.pxf.io/c/5597632/1496243/17238" target="_top" id="1496243"><img src="//a.impactradius-go.com/display-ad/17238-1496243" border="0" alt="" width="1000" height="1221"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1496243/17238" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068425/7443" target="_top" id="2068425"><img src="//a.impactradius-go.com/display-ad/7443-2068425" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068425/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4709458&QTY=1&AFFILIATE=108875&CART=1"><img src="https://3d-kstudio.com/wp-content/uploads/2014/02/Project-Manager-3D-Models-4-800x800.jpg" border="0">Project Manager - Asset Browser for 3Ds Max</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://engwe.pxf.io/c/5597632/2093504/25579" target="_top" id="2093504"><img src="//a.impactradius-go.com/display-ad/25579-2093504" border="0" alt="" width="1200" height="1200"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2093504/25579" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-reddit-experts-briefly-meet-at-snapchat/"><u>[New] In 2024, Reddit Experts Briefly Meet at Snapchat</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-seamless-obs-zoom-connection-step-by-step/"><u>[Updated] Seamless OBS-Zoom Connection  Step-by-Step</u></a></li>
<li><a href="https://location-fake.techidaily.com/11-best-location-changers-for-oppo-a18-drfone-by-drfone-virtual-android/"><u>11 Best Location Changers for Oppo A18 | Dr.fone</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-illuminating-the-future-luminances-influence-on-hdr/"><u>2024 Approved  Illuminating the Future  Luminance’s Influence on HDR</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-insiders-list-google-pixel-tone-sources/"><u>2024 Approved  Insider's List  Google Pixel Tone Sources</u></a></li>
<li><a href="https://unlock-android.techidaily.com/7-ways-to-unlock-a-locked-xiaomi-redmi-note-13-pro-5g-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked Xiaomi Redmi Note 13 Pro 5G Phone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ace-note-taking-in-any-setting-using-advanced-chatgpt-tools/"><u>Ace Note-Taking in Any Setting Using Advanced ChatGPT Tools</u></a></li>
<li><a href="https://fox-helps.techidaily.com/choosing-top-8-free-ai-powered-srt-translators/"><u>Choosing Top 8 Free, AI-Powered SRT Translators</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-enabling-bluetooth-connectivity-in-windows-11-and-10-systems/"><u>Comprehensive Guide: Enabling Bluetooth Connectivity in Windows 11 & 10 Systems</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/conquer-new-heights-the-definitive-guide-to-the-dji-mavic-3s-sky-high-imaging-capabilities/"><u>Conquer New Heights: The Definitive Guide to the DJI Mavic 3'S Sky-High Imaging Capabilities</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-the-windows-unable-to-find-media-mistake-for-gamers/"><u>Correcting the 'Windows Unable to Find Media' Mistake for Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/critical-deficit-microsoft-runtime-layer-1/"><u>Critical Deficit: Microsoft Runtime Layer 1</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-correct-apex-legends-anti-cheat-alerts-and-continue-playing-seamlessly/"><u>Easy Steps to Correct 'Apex Legends' Anti-Cheat Alerts and Continue Playing Seamlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-werfaultexe-application-error/"><u>Easy to Fix WerFault.exe Application Error</u></a></li>
<li><a href="https://fox-access.techidaily.com/elevating-listeners-a-comprehensive-guide-to-podcast-seo/"><u>Elevating Listeners  A Comprehensive Guide to Podcast SEO</u></a></li>
<li><a href="https://common-error.techidaily.com/enhance-your-streaming-experience-eliminate-kodis-buffering-frustration-effortlessly/"><u>Enhance Your Streaming Experience: Eliminate Kodi's Buffering Frustration Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-10-failed-to-enumerate-objects-error-step-by-step-solutions/"><u>Fixing Windows 10 'Failed to Enumerate Objects' Error: Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210072423-get-your-lenovo-mouse-pad-working-again-on-any-version-of-windows-comprehensive-fixes/"><u>Get Your Lenovo Mouse Pad Working Again on Any Version of Windows - Comprehensive Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-incompatible-drivers-can-compromise-the-integrity-of-your-ftdi-synchronous-data-transmission/"><u>How Incompatible Drivers Can Compromise the Integrity of Your FTDI Synchronous Data Transmission</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-system-error-e-xtracted-from-an-ssd-windows-11-7-and-8/"><u>How to Fix 'System Error E Xtracted From an SSD? [Windows 11, 7 & 8]</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-error-code-0x8000ffff-step-by-step-troubleshooting-guide/"><u>How to Fix Windows Error Code 0X8000FFFF – Step-by-Step Troubleshooting Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-atandt-apple-iphone-15-with-3-methods-by-drfone-ios/"><u>In 2024, How to Unlock AT&T Apple iPhone 15 with 3 Methods</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-master-the-art-of-video-with-these-html5-platforms/"><u>In 2024, Master the Art of Video with These HTML5 Platforms</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-non-youtube-havens-for-unparalleled-video-streaming/"><u>In 2024, Non-Youtube Havens for Unparalleled Video Streaming</u></a></li>
<li><a href="https://extra-skills.techidaily.com/leading-the-way-in-iphonecomputer-video-format-conversion-for-2024/"><u>Leading the Way in iPhone/Computer Video Format Conversion for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-google-chrome-stalling-is-it-time-for-a-fresh-start/"><u>Overcome Google Chrome Stalling: Is It Time for a Fresh Start?</u></a></li>
<li><a href="https://common-error.techidaily.com/renderer-boot-sequence-issue-corrected-for-enhanced-stability-new-fixes-applied/"><u>Renderer Boot Sequence Issue Corrected for Enhanced Stability - New Fixes Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-directx-graphics-driver-initialization-issue/"><u>Resolved: DirectX Graphics Driver Initialization Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-failed-connection-to-windows-system-event-notification-service/"><u>Resolved: Troubleshooting Failed Connection to Windows System Event Notification Service</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-non-functioning-fn-key-problems-on-your-computer/"><u>Resolving Non-Functioning Fn Key Problems on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-crash-in-32-bit-applications-print-driver-host/"><u>Resolving the Crash in 32-Bit Applications' Print Driver Host</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-functionality-to-your-windows-10-touchscreen-a-guide-to-5-key-strategies/"><u>Restoring Functionality to Your Windows 10 Touchscreen – A Guide to 5 Key Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-repair-unresponsive-fn-keys-on-your-pc-or-laptop/"><u>Step-by-Step Guide to Repair Unresponsive Fn Keys on Your PC or Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-nonfunctional-symbol-in-emails-and-text-messages/"><u>Step-by-Step Guide: Repairing Nonfunctional '@' Symbol in Emails and Text Messages</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-tackling-windows-update-error-0x80240017-successfully/"><u>Step-by-Step Solutions for Tackling Windows Update Error 0X80240017 Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-eradicating-errcachemiss-error-in-your-chrome-experience/"><u>Step-by-Step Tutorial: Eradicating ERR_CACHE_MISS Error in Your Chrome Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-resolving-minecraft-peer-to-peer-network-issues-for-seamless-play/"><u>Step-by-Step Tutorial: Resolving Minecraft Peer-to-Peer Network Issues for Seamless Play</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-the-0x80240017-dilemma-proven-fixes-to-revive-your-windows-updates-successfully/"><u>Tackling the 0X80240017 Dilemma - Proven Fixes to Revive Your Windows Updates Successfully</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/the-ultimate-guide-to-the-sub-100-tp-link-archer-c80-router-speeds-and-features-unveiled/"><u>The Ultimate Guide to the Sub-$100 TP-Link Archer C80 Router – Speeds and Features Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211516047-troubleshooting-crackling-audio-on-your-pc-with-windows-11-and-7-solved/"><u>Troubleshooting Crackling Audio on Your PC with Windows 11 & 7 - Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-errors-during-game-installation-on-origin/"><u>Troubleshooting Errors During Game Installation on Origin</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-call-of-duty-world-war-ii-overcoming-error-4220/"><u>Troubleshooting Guide for Call of Duty World War II - Overcoming Error 4220</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-no-audio-output-device-installed-issue-on-windows-11/"><u>Troubleshooting Guide: Resolving 'No Audio Output Device Installed' Issue on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-dolby-atmos-and-truehd-playback-problems-on-windows-11/"><u>Troubleshooting Guide: Resolving Dolby Atmos & TrueHD Playback Problems on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-microsoft-surface-pro-4s-non-responsive-touch-display-complete-solution/"><u>Troubleshooting Microsoft Surface Pro 4'S Non-Responsive Touch Display - Complete Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-techniques-overcoming-recurring-device-hang-ups/"><u>Troubleshooting Techniques: Overcoming Recurring Device Hang-Ups</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-repairing-a-non-functional-logitech-mouse-scroll-wheel/"><u>Troubleshooting Tips: Repairing a Non-Functional Logitech Mouse Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/wake-up-woes-pc-puzzled-on-win1110/"><u>Wake-Up Woes: PC Puzzled on Win11/10</u></a></li>
</ul></div>
