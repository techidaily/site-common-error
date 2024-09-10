---
title: Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
date: 2024-09-09T09:03:48.069Z
updated: 2024-09-10T09:03:48.069Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
excerpt: This Article Describes Step-by-Step Solution for 'Power Surge' Error Code on USB Connections – Windows 11 Edition
thumbnail: https://thmb.techidaily.com/7f38f48d6c1e2e7dd4ffc2cf3530de002749e2e66d038be493fc55f20cd91a70.jpg
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123473/16836" target="_top" id="2123473">
  <img src="//a.impactradius-go.com/display-ad/16836-2123473" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123473/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115946/19272" target="_top" id="2115946">
  <img src="//a.impactradius-go.com/display-ad/19272-2115946" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115946/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<span id="1975562">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975562.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975562">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975562.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975562%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975562/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115924/19272" target="_top" id="2115924">
  <img src="//a.impactradius-go.com/display-ad/19272-2115924" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115924/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139114/17108" target="_top" id="2139114">
  <img src="//a.impactradius-go.com/display-ad/17108-2139114" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139114/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136612/26400" target="_top" id="2136612">
  <img src="//a.impactradius-go.com/display-ad/26400-2136612" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136612/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-capture-clarity-comprehensive-free-pcmac-recording-apps/"><u>[New] 2024 Approved Capture Clarity Comprehensive Free PC/Mac Recording Apps</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-2024-approved-viral-visionaries-top-meme-creators-on-social-media/"><u>[New] 2024 Approved Viral Visionaries Top Meme Creators on Social Media</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-cut-screen-claims-is-splitcam-supreme-in-2024/"><u>[New] Cut Screen Claims Is SplitCam Supreme, In 2024</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ow-cost-cameras-that-dont-compromise-quality/"><u>[New] Low-Cost Cameras That Don't Compromise Quality</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/peedy-realignment-youtube-videos-for-mac-views-for-2024/"><u>[New] Speedy Realignment YouTube Videos for MAC Views for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-pro-editor-tips-cropping-and-export-your-videos-for-instagram-success/"><u>[Updated] 2024 Approved Pro Editor Tips Cropping & Export Your Videos for Instagram Success</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-creative-setbacks-sudden-content-expulsion-for-2024/"><u>[Updated] Creative Setbacks Sudden Content Expulsion for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-from-novice-to-expert-mastering-movie-maker-in-windows-8-systems/"><u>[Updated] From Novice to Expert Mastering Movie Maker in Windows 8 Systems</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-unmatched-timers-for-weddings-top-10-choices-on-phones/"><u>[Updated] Unmatched Timers for Weddings Top 10 Choices on Phones</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-video-brand-enhancement-embedding-logoswatermarks-for-youtube-shows/"><u>[Updated] Video Brand Enhancement Embedding Logos/Watermarks for YouTube Shows</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-snicker-scribbles-humorhub/"><u>2024 Approved Snicker Scribbles HumorHub</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-the-ultimate-youtube-to-mp4-blueprint/"><u>2024 Approved The Ultimate YouTube to MP4 Blueprint</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/a-comprehensive-walkthrough-for-embedding-youtube-plays-in-web-design/"><u>A Comprehensive Walkthrough for Embedding YouTube Plays in Web Design</u></a></li>
<li><a href="https://common-error.techidaily.com/bug-fixed-now-running-smoothly-32bit-apps-print-driver-issues-addressed/"><u>Bug Fixed: Now Running Smoothly - 32Bit Apps Print Driver Issues Addressed</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-overcome-the-persistent-windows-10-update-error-code-0x800705b4-explained/"><u>Effective Strategies to Overcome the Persistent Windows 10 Update Error: Code 0X800705b4 Explained</u></a></li>
<li><a href="https://win11-tips.techidaily.com/efficiently-detect-pcs-network-settings-in-windows-ps/"><u>Efficiently Detect PC's Network Settings in Windows PS</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-when-your-steam-content-servers-cant-be-reached/"><u>Expert Tips for When Your Steam Content Servers Can't Be Reached</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-overcome-error-code-ce-3478-on-playstation-4-systems/"><u>Expert Tips to Overcome Error Code CE-3478 on PlayStation 4 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/exploring-the-phenomenon-of-automatic-boot-in-windows-10-systems/"><u>Exploring the Phenomenon of Automatic Boot in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-notorious-aw-snap-glitch-on-your-chrome-browser/"><u>Fixing the Notorious Aw, Snap! Glitch on Your Chrome Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-shockwave-flash-problem-with-google-chrome/"><u>Fixing the Shockwave Flash Problem with Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207828919-getting-windows-update-running-again-heres-how-you-fix-it/"><u>Getting Windows Update Running Again? Here’s How You Fix It!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-seamlessly-enable-usb-tethering-in-windows-11-a-step-by-step-guide/"><u>How to Seamlessly Enable USB Tethering in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-your-laptop-from-turning-off-without-warning-tips-for-a-smooth-run/"><u>How to Stop Your Laptop From Turning Off Without Warning – Tips for a Smooth Run</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-card-on-oneplus-ace-2v-online-without-jailbreak-by-drfone-android/"><u>In 2024, How to Unlock SIM Card on OnePlus Ace 2V online without jailbreak</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-unmask-phony-followers-a-speedy-cost-free-approach-for-instagram/"><u>In 2024, Unmask Phony Followers A Speedy, Cost-Free Approach for Instagram</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-system-performance-by-controlling-svchostexe-netsvcs-network-activity-expert-solutions/"><u>Optimizing System Performance by Controlling Svchost.exe (NETsvcs) Network Activity: Expert Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-activating-bluetooth-on-windows-7-operating-system/"><u>Quick Fix: Activating Bluetooth on Windows 7 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-the-missing-bluetooth-error-in-windows-11-with-simple-solutions/"><u>Resolve the 'Missing Bluetooth' Error in Windows 11 with Simple Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-persistent-delay-on-windows-10-keyboards/"><u>Resolved: Fixing Persistent Delay on Windows 10 Keyboards</u></a></li>
<li><a href="https://vp-tips.techidaily.com/review-unveiling-the-capabilities-of-belkin-boostcharge-pro-qi2-wireless-kickstand-a-comprehensive-look-at-its-5k-battery-performance/"><u>Review: Unveiling the Capabilities of Belkin BoostCharge Pro (Qi2 Wireless, Kickstand) – A Comprehensive Look at Its 5K Battery Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-resolving-silent-streams-on-netflix/"><u>Simple Solutions: Resolving Silent Streams on Netflix</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-non-responsive-audio-levels-on-windows-10-devices/"><u>Solution Steps for Non-Responsive Audio Levels on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-how-to-resolve-vac-could-not-confirm-your-gaming-activity/"><u>Solution: How to Resolve 'VAC Could Not Confirm Your Gaming Activity'</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-poor-sync-between-epson-printer-and-scanner/"><u>Solving Poor Sync Between Epson Printer and Scanner</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-fixing-the-code-0xc0000098-issue-in-windows/"><u>Step-by-Step Solutions for Fixing the 'Code 0xC0000098' Issue in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-address-intel-serial-io-driver-configuration-warning-for-unsupported-hardware-or-operating-system/"><u>Steps to Address Intel Serial IO Driver Configuration Warning for Unsupported Hardware or Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/the-comprehensive-solution-for-resolving-steams-error-code-80-problems/"><u>The Comprehensive Solution for Resolving Steam's Error Code 80 Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-disconnected-amd-premium-sound-devices/"><u>Troubleshooting Guide for Disconnected AMD Premium Sound Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-your-icue-system-cant-detect-devices/"><u>Troubleshooting Tips for When Your ICUE System Can’t Detect Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-fixes-for-the-troublesome-windows-update-failed-code-0x80244022-explained/"><u>Unraveling Fixes for the Troublesome 'Windows Update Failed' - Code 0X80244022 Explained</u></a></li>
<li><a href="https://change-location.techidaily.com/why-is-ipogo-not-working-on-vivo-y27s-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Vivo Y27s? Fixed | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/win10-computers-restart-unpredictably/"><u>Win10 Computers Restart Unpredictably</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-(connector)-10-deactivating-touchpad-with-an-external-mouse-attached/"><u>Windows <Connector> 10: Deactivating Touchpad with an External Mouse Attached</u></a></li>
</ul></div>
