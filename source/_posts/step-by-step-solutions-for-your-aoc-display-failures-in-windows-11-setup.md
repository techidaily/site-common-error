---
title: Step-by-Step Solutions for Your AOC Display Failures in Windows 11 Setup
date: 2024-08-27T13:37:11.146Z
updated: 2024-08-28T13:37:11.146Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Your AOC Display Failures in Windows 11 Setup
excerpt: This Article Describes Step-by-Step Solutions for Your AOC Display Failures in Windows 11 Setup
thumbnail: https://thmb.techidaily.com/7b61f24c759b4bb707c98e4d5ba6ea429d7484a4ebc98b905ced6f7c4d8a2b63.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://imp.i110150.net/c/5597632/924299/11305" target="_top" id="924299"><img src="//a.impactradius-go.com/display-ad/11305-924299" border="0" alt="" width="520" height="100"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2090698/16836" target="_top" id="2090698"><img src="//a.impactradius-go.com/display-ad/16836-2090698" border="0" alt="" width="720" height="300"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
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
<li><a href="https://common-error.techidaily.com/fixed-this-device-is-not-present-code-24-windows-10-8-or-7/"><u>[Fixed] This Device Is Not Present (Code 24) - Windows 10, 8 or 7</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/new-2024-approved-maximize-marketing-magic-ranking-of-8-facebook-friendly-apps/"><u>[New] 2024 Approved  Maximize Marketing Magic  Ranking of 8 Facebook-Friendly Apps</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-2024-approved-ultimate-low-cost-smart-home-devices-for-gaming/"><u>[New] 2024 Approved  Ultimate Low-Cost Smart Home Devices for Gaming</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-ultimate-spots-for-discovering-rich-gold-text-effects/"><u>[New] In 2024, Ultimate Spots for Discovering Rich, Gold Text Effects</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-professional-grade-8-filters-for-live-feeds-for-2024/"><u>[New] Professional-Grade 8 Filters for Live Feeds for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/pubg-no-more-misfires-dxgidll-secured/"><u>[PUBG] No More Misfires - Dxgi.dll Secured</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-captivating-cycles-on-ig-perfecting-the-boomerang-effect/"><u>[Updated] 2024 Approved  Captivating Cycles on IG  Perfecting the Boomerang Effect</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-professional-streams-from-obs-to-insta/"><u>[Updated] 2024 Approved  Professional Streams From OBS to Insta</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-effortless-android-screenshot-and-screen-record-for-2024/"><u>[Updated] Effortless Android Screenshot & Screen Record for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-expert-insights-crafting-perfect-vimeo-closures/"><u>[Updated] Expert Insights  Crafting Perfect Vimeo Closures</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-best-in-class-textify-your-vlogs/"><u>[Updated] In 2024, Best in Class  Textify Your Vlogs</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-in-2024-strategies-and-costs-promoting-videos-effectively/"><u>[Updated] In 2024, Strategies and Costs  Promoting Videos Effectively</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-snap-in-hours-stars-quick-hit-video-winners-for-2024/"><u>[Updated] Snap-in-Hours Stars  Quick Hit Video Winners for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-e-education-video-logging/"><u>2024 Approved  E-Education Video Logging</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-leading-the-way-in-personal-trail-tracking-drone-innovation/"><u>2024 Approved  Leading the Way in Personal Trail-Tracking Drone Innovation</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-masterful-voice-changes-without-cost-explore-these-options/"><u>2024 Approved  Masterful Voice Changes Without Cost - Explore These Options</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/7-ways-to-unlock-a-locked-oneplus-11-5g-phone-by-drfone-android/"><u>7 Ways to Unlock a Locked OnePlus 11 5G Phone</u></a></li>
<li><a href="https://common-error.techidaily.com/banish-the-shadows-expert-tips-to-restore-your-game-after-monster-hunter-worlds-startup-screens-are-swallowed-by-darkness/"><u>Banish the Shadows: Expert Tips to Restore Your Game After Monster Hunter: World's Startup Screens Are Swallowed by Darkness</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210596431-dells-usb-port-problem-discover-proven-strategies-to-get-it-working-again/"><u>Dell's USB Port Problem? Discover Proven Strategies to Get It Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-the-remote-procedure-call-failed-message-on-windows-systems/"><u>Diagnosing and Repairing the 'Remote Procedure Call Failed' Message on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-mend-corrupted-files-in-windows-11-using-system-file-check-sfc-and-deployment-image-servicing-dism/"><u>Effective Strategies to Mend Corrupted Files in Windows 11 Using System File Check (SFC) & Deployment Image Servicing (DISM)</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-efficiency-after-resolving-inadequate-system-resources-warning/"><u>Enhanced Efficiency After Resolving Inadequate System Resources Warning</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-fixing-windows-communication-issue-with-the-event-notification-system/"><u>Expert Advice: Fixing Windows Communication Issue with the Event Notification System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-eliminating-cod-wwii-error-4220-the-ultimate-fix-checklist/"><u>Expert Tips for Eliminating COD WWII Error 4220 - The Ultimate Fix Checklist</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unresponsive-laptop-keys-on-windows-solutions-for-win10-8-and-7/"><u>Fixing Unresponsive Laptop Keys on Windows: Solutions for Win10, 8 & 7</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/from-zero-to-hero-youtube-tech-required/"><u>From Zero to Hero  YouTube Tech Required</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-13-pro-without-losing-any-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone 13 Pro without Losing Any Data? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-nier-automata-crashes-in-pc-game-detailed-guide/"><u>How to Fix Nier: Automata Crashes in PC Game – Detailed Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-process-abruptly-ended-error-code-1067-on-your-pc/"><u>How To Overcome 'The Process Abruptly Ended' Error Code 1067 on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-not-charging-problem-for-connected-gadgets-on-your-windows-computer-versions-7-10/"><u>How to Resolve Not Charging Problem for Connected Gadgets on Your Windows Computer (Versions 7, 10)</u></a></li>
<li><a href="https://common-error.techidaily.com/illuminating-the-screen-expert-fixes-for-obs-capturing-blackout-issues/"><u>Illuminating the Screen: Expert Fixes for OBS Capturing Blackout Issues</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-3-ways-to-fake-gps-without-root-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Fake GPS Without Root On Oppo Find X6 | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-innovative-ideas-to-make-money-from-your-snapchat-community/"><u>In 2024, Innovative Ideas to Make Money From Your Snapchat Community</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-inside-windows-10-a-snapshot-of-its-transformation/"><u>In 2024, Inside Windows 10  A Snapshot of Its Transformation</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-livestream-launchpad-duel-go-with-xsplit-or-opt-for-obs/"><u>In 2024, Livestream Launchpad Duel  Go with XSplit or Opt for OBS?</u></a></li>
<li><a href="https://hardware-help.techidaily.com/inside-toms-computer-gear-comprehensive-hardware-analysis/"><u>Inside Tom's Computer Gear: Comprehensive Hardware Analysis</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/ipad-video-editing-software-the-best-of-the-best/"><u>IPad Video Editing Software The Best of the Best</u></a></li>
<li><a href="https://common-error.techidaily.com/lonicera-fragrantissima-sweet-breath-of-spring-or-fragrant-honeysuckle-native-to-china-it-is-known-for-its-intensely-fragrant-winter-blooms-even-when-the-pl131/"><u>Lonicera Fragrantissima (Sweet Breath of Spring or Fragrant Honeysuckle): Native to China, It Is Known for Its Intensely Fragrant Winter Blooms, Even when the Plant Appears Dormant.</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-ranking-the-best-video-editing-apps-with-music-for-android-and-ios-devices-for-2024/"><u>New Ranking the Best Video Editing Apps with Music for Android and iOS Devices for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-cache-miss-errors-errcachemiss-in-google-chrome-easily/"><u>Overcoming Cache Miss Errors (ERR_CACHE_MISS) in Google Chrome Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-broken-function-keys-on-your-asus-portable-computer/"><u>Overcoming Issues with Broken Function Keys on Your ASUS Portable Computer</u></a></li>
<li><a href="https://howto.techidaily.com/play-store-stuck-on-downloading-of-vivo-s17t-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Vivo S17t? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-unresponsive-keyboard-on-your-hp-laptop-solved/"><u>Quick Fixes for Unresponsive Keyboard on Your HP Laptop - Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-stuck-huion-pen-problems-in-a-flash-5-essential-troubleshooting-steps/"><u>Resolve Your Stuck Huion Pen Problems in a Flash: 5 Essential Troubleshooting Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-error-messages-in-kodi-a-comprehensive-guide-to-smooth-streaming/"><u>Resolving Error Messages in Kodi - A Comprehensive Guide to Smooth Streaming</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-steams-absent-file-permissions-issue/"><u>Resolving Steam's Absent File Permissions Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/say-goodbye-to-kodi-pause-a-guide-on-correcting-stream-stutter/"><u>Say Goodbye to Kodi Pause: A Guide on Correcting Stream Stutter</u></a></li>
<li><a href="https://extra-tips.techidaily.com/sdr-vs-hdr-choosing-the-best-for-professional-outputs/"><u>SDR vs HDR  Choosing the Best for Professional Outputs</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-pubg-fixing-missing-building-assets-issue/"><u>Solved: PUBG - Fixing Missing Building Assets Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-lenovo-mousepad-issues-on-windows-11-8-and-7-a-comprehensive-fix-guide/"><u>Solving Lenovo Mousepad Issues on Windows 11, 8 & 7: A Comprehensive Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-of-a-nonfunctional-hp-laptop-camera-in-windows-11-tips-and-solutions/"><u>Solving the Problem of a Nonfunctional HP Laptop Camera in Windows 11 – Tips and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-repairing-a-dead-microphone-on-skype-calls/"><u>Step-by-Step Guide to Repairing a Dead Microphone on Skype Calls</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-resolution-overcoming-the-battleye-installation-hurdle/"><u>Successful Resolution: Overcoming the BattlEye Installation Hurdle</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-restoring-charge-on-a-plugged-in-yet-unresponsive-surface-device/"><u>The Ultimate Guide To Restoring Charge On A Plugged In, Yet Unresponsive Surface Device</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208863446-thyroid-lymphoma-while-uncommon-can-be-more-prevalent-in-individuals-with-a-history-of-autoimmune-thyroiditis-like-hashimotos-disease/"><u>Thyroid Lymphoma, While Uncommon, Can Be More Prevalent in Individuals with a History of Autoimmune Thyroiditis Like Hashimoto's Disease.</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-a-non-responsive-logitech-keyboard-under-windows-11-what-to-do/"><u>Trouble with a Non-Responsive Logitech Keyboard Under Windows 11: What to Do?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-corrupted-files-on-a-windows-11-operating-system/"><u>Troubleshooting and Fixing Corrupted Files on a Windows 11 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-high-wudfhostexe-cpu-consumption-on-windows-10-pcs/"><u>Troubleshooting and Fixing High wudfhost.exe CPU Consumption on Windows 10 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-solving-windows-pcs-nonfunctional-built-in-camera/"><u>Troubleshooting Steps: Solving Windows PC's Nonfunctional Built-In Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-touchscreen-issues-5-effective-solutions/"><u>Troubleshooting Windows 11 Touchscreen Issues - 5 Effective Solutions</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-how-to-get-your-dell-camera-back-to-work-on-a-windows-pc/"><u>Troubleshooting: How to Get Your Dell Camera Back to Work on a Windows PC</u></a></li>
<li><a href="https://some-approaches.techidaily.com/unlocking-windows-high-dynamic-range-potential-for-2024/"><u>Unlocking Windows' High Dynamic Range Potential for 2024</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-motorola-g54-5g-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Motorola G54 5G Phones</u></a></li>
</ul></div>
