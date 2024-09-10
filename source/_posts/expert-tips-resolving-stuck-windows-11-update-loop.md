---
title: "Expert Tips: Resolving Stuck Windows 11 Update Loop"
date: 2024-09-09T08:55:01.066Z
updated: 2024-09-10T08:55:01.066Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Tips: Resolving Stuck Windows 11 Update Loop"
excerpt: "This Article Describes Expert Tips: Resolving Stuck Windows 11 Update Loop"
thumbnail: https://thmb.techidaily.com/39eb12846caac832ee1b1d85070e2dd4cb557f02287ca2d451303bdd76b5dd20.jpg
---

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135416/19272" target="_top" id="2135416">
  <img src="//a.impactradius-go.com/display-ad/19272-2135416" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135416/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137212/26400" target="_top" id="2137212">
  <img src="//a.impactradius-go.com/display-ad/26400-2137212" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137212/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

<!-- affiliate ads begin -->
<span id="1982459">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982459.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982459">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982459.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982459%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982459/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/net-framework-35-setup-error-code-0x800f081f-a-step-by-step-correction-guide/"><u>.NET Framework 3.5 Setup Error Code 0X800F081F - A Step-by-Step Correction Guide</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-easy-technique-storing-tweet-videos-and-images-on-cellphone/"><u>[New] 2024 Approved  Easy Technique  Storing Tweet Videos and Images on Cellphone</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-enablingdisabling-multitasking-in-safari-devices/"><u>[New] 2024 Approved  Enabling/Disabling Multitasking in Safari Devices</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-charting-the-course-of-youtube-success-through-social-blade-analysis/"><u>[New] In 2024, Charting the Course of YouTube Success Through Social Blade Analysis</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-expert-advice-on-flawless-ipad-screen-captures/"><u>[Updated] Expert Advice on Flawless iPad Screen Captures</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-in-2024-advanced-audio-capture-a-comprehensive-look-at-whatsapp-call-recording/"><u>[Updated] In 2024, Advanced Audio Capture  A Comprehensive Look at WhatsApp Call Recording</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-how-to-get-a-faster-live-streaming-on-periscope/"><u>2024 Approved  How to Get a Faster Live Streaming on Periscope</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-keep-your-spotify-experience-recommendation-free/"><u>2024 Approved  Keep Your Spotify Experience Recommendation-Free</u></a></li>
<li><a href="https://android-frp.techidaily.com/addrom-bypass-an-android-tool-to-unlock-frp-lock-screen-for-your-lava-blaze-pro-5g-by-drfone-android/"><u>AddROM Bypass An Android Tool to Unlock FRP Lock Screen For your Lava Blaze Pro 5G</u></a></li>
<li><a href="https://common-error.techidaily.com/audio-woes-in-win-11-ends-steps-taken/"><u>Audio Woes in Win 11 Ends: Steps Taken</u></a></li>
<li><a href="https://common-error.techidaily.com/chromecast-wont-pair-discover-quick-solutions-for-better-connectivity/"><u>Chromecast Won't Pair? Discover Quick Solutions for Better Connectivity!</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fix-guide-for-persistent-crash-problems-in-oddworld-soulstorm-on-desktop-computers/"><u>Comprehensive Fix Guide for Persistent Crash Problems in Oddworld: Soulstorm on Desktop Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-the-windows-sound-driver-high-resource-utilization-problem/"><u>Diagnosing and Fixing the Window's Sound Driver High Resource Utilization Problem</u></a></li>
<li><a href="https://tech-revival.techidaily.com/efficient-ways-to-archive-and-retrieve-your-chatgpt-interactions-whenever-needed/"><u>Efficient Ways to Archive and Retrieve Your ChatGPT Interactions Whenever Needed</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-navigating-past-error-code-0x800f0922-on-your-windows-11-system/"><u>Effortless Fixes for Navigating Past Error Code 0X800F0922 on Your Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208009912-endless-cursor-flicker-heres-what-you-can-do-to-fix-it/"><u>Endless Cursor Flicker? Here's What You Can Do To Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/enhance-your-gaming-experience-resolve-rdr2-out-of-memory-errors-instantly/"><u>Enhance Your Gaming Experience: Resolve RDR2 Out of Memory Errors Instantly</u></a></li>
<li><a href="https://common-error.techidaily.com/ensuring-ftdi-integrity-the-crucial-role-of-compatible-hardware-components-and-drivers/"><u>Ensuring FTDI Integrity: The Crucial Role of Compatible Hardware Components and Drivers</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exceptional-endurance-a-moto-g-power-assessment-stellar-battery-performance-meets-style/"><u>Exceptional Endurance: A Moto G Power Assessment - Stellar Battery Performance Meets Style</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-correcting-corrupted-file-issues-in-latest-windows-operating-systems/"><u>Expert Advice: Correcting Corrupted File Issues in Latest Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-windows-11-sound-settings-issue-how-to-restore-volume-functionality/"><u>Fix Windows 11 Sound Settings Issue: How to Restore Volume Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-frozen-windows-11-issues-during-initial-load-step-by-step-guide/"><u>Fixing Frozen Windows 11 Issues During Initial Load - Step by Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-32-bit-application-faces-critical-error-print-driver-host-not-responding/"><u>Fixing the Issue: 32-Bit Application Faces Critical Error - Print Driver Host Not Responding</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-persistent-100-stall-in-windows-updates-solution/"><u>Fixing the Persistent 100%% Stall in Windows Updates - SOLUTION</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-unfixable-solutions-for-the-persistent-0x80072efd-error-on-windows-11/"><u>Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-errors-with-remote-procedure-call-servers-in-windows-environments/"><u>Guide to Fixing Errors with Remote Procedure Call Servers in Windows Environments</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-detect-and-stop-mspy-from-spying-on-your-asus-rog-phone-7-drfone-by-drfone-virtual-android/"><u>How to Detect and Stop mSpy from Spying on Your Asus ROG Phone 7 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-windows-camera-error-code-0xa00f4292/"><u>How to Resolve the Windows Camera Error (Code 0Xa00f4292)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-resolve-the-critical-fatal-error-code-1603-in-software-setup/"><u>How to Successfully Resolve the Critical Fatal Error (Code 1603) in Software Setup</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-complete-tutorial-to-use-vpna-to-fake-gps-location-on-motorola-moto-g14-drfone-by-drfone-virtual-android/"><u>In 2024, Complete Tutorial to Use VPNa to Fake GPS Location On Motorola Moto G14 | Dr.fone</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-transform-your-recording-experience-moving-past-fbx-methods/"><u>In 2024, Transform Your Recording Experience  Moving Past FBX Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-numeric-key-malfunction-heres-how-you-fixed-it/"><u>Keyboard Numeric Key Malfunction? Here's How You Fixed It!</u></a></li>
<li><a href="https://fox-http.techidaily.com/maximizing-your-gameplay-overcoming-fps-drops-in-resident-evil-village-on-pc/"><u>Maximizing Your Gameplay: Overcoming Fps Drops in Resident Evil Village on PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/mts/"><u>MTSファイルの編集手順：フリーソフトウェアを使ってダウングレードなし</u></a></li>
<li><a href="https://ai-live-streaming.techidaily.com/new-in-2024-a-guide-on-starting-private-live-streams-on-youtube/"><u>New In 2024, A Guide on Starting Private Live Streams on YouTube</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/new-simplify-avi-video-editing-16-top-avi-cutters-for-trimming-and-cutting-cross-platform-compatibility-for-2024/"><u>New Simplify AVI Video Editing 16 Top AVI Cutters for Trimming and Cutting Cross-Platform Compatibility for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-connection-issues-with-audiovideo-hardware-in-windows-tips-and-tricks/"><u>Overcoming Connection Issues with Audio/Video Hardware in Windows - Tips and Tricks</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/prime-mp4-fb-file-shifter/"><u>Prime MP4-FB File Shifter</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-resolution-for-non-functioning-airdrop-effortless-solutions-explained/"><u>Quick Resolution for Non-Functioning AirDrop: Effortless Solutions Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-to-rdr2-memory-errors-boost-your-page-file-size-now/"><u>Quick Solutions to RDR2 Memory Errors: Boost Your Page File Size Now</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210412360-resolve-unknown-usb-device-issues-in-windows-n-with-these-easy-steps/"><u>Resolve 'Unknown USB Device' Issues in Windows N with These Easy Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-solutions-for-stability-in-total-war-rome-remastered/"><u>Resolved Solutions for Stability in Total War: Rome Remastered</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-lengthy-shutdown-delays-in-windows-10-systems/"><u>Resolving the Lengthy Shutdown Delays in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-system-lags-high-usage-of-ntoskrnlexe/"><u>Solving System Lags: High Usage of Ntoskrnl.exe</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-error-0x8024200d-and-ensure-smooth-windows-update-functionality/"><u>Step-by-Step Solution to Overcome Error 0X8024200d and Ensure Smooth Windows Update Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-windows-driver-power-state-errors/"><u>Step-by-Step Solutions for Windows Driver Power State Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-restore-your-dell-speaker-functionality/"><u>Step-by-Step Tips to Restore Your Dell Speaker Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-for-windows-update-error-0x80240017-solved/"><u>Step-by-Step Troubleshooting for Windows Update Error 0X80240017 [Solved]</u></a></li>
<li><a href="https://howto.techidaily.com/tecno-spark-go-2023-not-receiving-texts-10-hassle-free-solutions-here-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Tecno Spark Go (2023) Not Receiving Texts? 10 Hassle-Free Solutions Here | Dr.fone</u></a></li>
<li><a href="https://buynow-info.techidaily.com/1722467005450-top-free-and-paid-substitutes-for-microsoft-office/"><u>Top Free & Paid Substitutes for Microsoft Office</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/top-rated-television-streaming-services-expert-picks/"><u>Top Rated Television Streaming Services - Expert Picks</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-fixing-a-non-functional-corsair-hs50-headset-microphone/"><u>Troubleshooting Steps for Fixing a Non-Functional Corsair HS50 Headset Microphone</u></a></li>
<li><a href="https://techtrends.techidaily.com/turn-off-the-autoplay-feature-for-a-better-apple-music-experience/"><u>Turn Off the Autoplay Feature for a Better Apple Music Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/twitch-error-4000-demystified-quick-fixes-to-get-your-stream-running-smoothly-again/"><u>Twitch Error 4000 Demystified: Quick Fixes to Get Your Stream Running Smoothly Again</u></a></li>
<li><a href="https://tech-haven.techidaily.com/twitscam-alert-metasig-comes-alive/"><u>TwitScam Alert: Metasig Comes Alive</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-frustrating-twitch-error-code-4000/"><u>Ultimate Guide: Resolving the Frustrating Twitch Error Code 4000</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-gameplay-upgrades-a-guide-to-achieving-smoother-faster-games/"><u>Windows 11 Gameplay Upgrades: A Guide to Achieving Smoother, Faster Games</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-strategy-instructing-windows-to-recognize-suitable-printer-drivers/"><u>Winning Strategy: Instructing Windows to Recognize Suitable Printer Drivers</u></a></li>
</ul></div>
