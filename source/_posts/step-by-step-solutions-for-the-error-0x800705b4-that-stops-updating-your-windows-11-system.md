---
title: Step-by-Step Solutions for the 'Error 0X800705B4' That Stops Updating Your Windows 11 System
date: 2024-08-27T13:43:49.900Z
updated: 2024-08-28T13:43:49.900Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for the 'Error 0X800705B4' That Stops Updating Your Windows 11 System
excerpt: This Article Describes Step-by-Step Solutions for the 'Error 0X800705B4' That Stops Updating Your Windows 11 System
thumbnail: https://thmb.techidaily.com/502b1cdc938497dc65859bd4dea7388cbc83b5388aae8627911832c708fd7626.jpg
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
<li><a href="https://article-knowledge.techidaily.com/new-comparing-metaverse-to-multiplemetasa-highlighting-their-variance-for-2024/"><u>[New] Comparing Metaverse to MultipleMetasa  Highlighting Their Variance for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-create-captivating-yt-thumbnails-fast/"><u>[New] Create Captivating YT Thumbnails Fast!</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-in-2024-final-steps-for-irreversible-tiktok-un-signup/"><u>[New] In 2024, Final Steps for Irreversible TikTok Un-Signup</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-motivation-on-playlist-the-leading-workout-song-picks/"><u>[New] Motivation on Playlist  The Leading Workout Song Picks</u></a></li>
<li><a href="https://extra-hints.techidaily.com/new-twitch-vs-youtube-an-in-depth-comparative-analysis/"><u>[New] Twitch Vs. YouTube  An In-Depth Comparative Analysis</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-2024-approved-steady-and-true-keeping-it-all-together-in-your-youtube-shoots/"><u>[Updated] 2024 Approved  Steady and True  Keeping It All Together in Your YouTube Shoots</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-the-definitive-guide-to-the-top-9-mic-recording-apps-in-23/"><u>[Updated] 2024 Approved  The Definitive Guide to the Top 9 Mic Recording Apps in '23</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-2024-approved-the-new-dawn-of-creativity-spotlight-on-six-visionary-nftos/"><u>[Updated] 2024 Approved  The New Dawn of Creativity  Spotlight on Six Visionary NFTOs</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-brighter-days-with-five-winter-themed-backgrounds-for-2024/"><u>[Updated] Brighter Days with Five Winter-Themed Backgrounds for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-capture-android-the-ultimate-recorder-at-no-cost-for-2024/"><u>[Updated] Capture Android  The Ultimate Recorder at No Cost for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-easy-to-follow-steps-for-adding-vimeo-clips-to-ppts-for-2024/"><u>[Updated] Easy-to-Follow Steps for Adding Vimeo Clips to PPTs for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-elevating-positivity-in-a-constructive-space-for-2024/"><u>[Updated] Elevating Positivity in a Constructive Space for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-in-2024-discover-the-top-free-tools-for-youtube-image-downloads/"><u>[Updated] In 2024, Discover the Top Free Tools for YouTube Image Downloads</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-immediate-pause-screen-capture-steps/"><u>[Updated] In 2024, Immediate Pause Screen Capture Steps</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-podcasts-on-windows-select-best-8/"><u>[Updated] Mastering Podcasts on Windows - Select Best 8</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-top-essential-fluid-dynamics-gaming-experiences/"><u>[Updated] Top Essential Fluid Dynamics Gaming Experiences</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/1099-launch-of-snapdragon-x-windows-copilotplus-pcs-by-acer-dell-hp-and-lenovo-featuring-multi-day-battery-life/"><u>$1,099: Launch of Snapdragon X Windows Copilot+ PCs by Acer, Dell, HP, and Lenovo Featuring 'Multi-Day Battery Life'</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-aural-aesthetics-in-whatsapp-statues/"><u>2024 Approved  Aural Aesthetics in WhatsApp Statues</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-comprehensive-list-best-10-terraria-mods/"><u>2024 Approved  Comprehensive List  Best 10 Terraria Mods</u></a></li>
<li><a href="https://article-helps.techidaily.com/2024-approved-crafting-engaging-narration-for-your-video-projects/"><u>2024 Approved  Crafting Engaging Narration for Your Video Projects</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-safeguarding-your-listening-pleasure-with-3-steps/"><u>2024 Approved  Safeguarding Your Listening Pleasure with 3 Steps</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-easy-ways-to-copy-contacts-from-nokia-c32-to-iphone-14-and-15-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Easy Ways to Copy Contacts from Nokia C32 to iPhone 14 and 15 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/activate-secure-windows-scripting-navigating-execution-policies/"><u>Activate Secure Windows Scripting: Navigating Execution Policies</u></a></li>
<li><a href="https://common-error.techidaily.com/bring-back-the-keys-tablet-saved/"><u>Bring Back The Keys! Tablet Saved</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/broadcast-battle-which-platform-wins/"><u>Broadcast Battle  Which Platform Wins?</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-the-hassle-of-error-8007000e-on-your-pc/"><u>Bypassing the Hassle of Error 8007000E on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-dealing-with-network-cable-unplugged-errors-in-windows-10-and-hemenet-a-technical-troubleshooting-resource/"><u>Comprehensive Solutions for Dealing with 'Network Cable Unplugged' Errors in Windows 10 & Hemenet: A Technical Troubleshooting Resource</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-fixes-for-lost-desktop-icons-in-windows-11-top-solutions-revealed/"><u>Easy Fixes for Lost Desktop Icons in Windows 11 - Top Solutions Revealed</u></a></li>
<li><a href="https://fox-access.techidaily.com/elevating-visual-communication-top-10-tools-for-vector-artists/"><u>Elevating Visual Communication  Top 10 Tools for Vector Artists</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminating-the-perpetual-grayscale-fixing-laptop-screen-issues-once-and-for-all/"><u>Eliminating the Perpetual Grayscale: Fixing Laptop Screen Issues Once and For All</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/enable-quiet-youtube-bgplay-for-iphone-and-android/"><u>Enable Quiet YouTube BGPlay for iPhone & Android</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211817073-error-0x8024200d-windows-update-failure-solved/"><u>Error 0X8024200d - Windows Update Failure [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-resolving-continuous-usb-recognition-errors-effectively/"><u>Expert Advice for Resolving Continuous USB Recognition Errors Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212325473-expert-tips-for-resolving-persistent-keyboard-typos-learn-effective-techniques-now/"><u>Expert Tips for Resolving Persistent Keyboard Typos - Learn Effective Techniques Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-reactivate-and-optimize-intel-rapid-storage-in-windows-11-environments/"><u>Expert Tips to Reactivate and Optimize Intel Rapid Storage in Windows 11 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-sign-in-issue-caused-by-failed-user-profile-services-in-windows-10-and-11/"><u>Fixing the Sign-In Issue Caused by Failed User Profile Services in Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/from-shadows-to-light-world-of-warcrafts-full-spectrum-3d-achievement/"><u>From Shadows to Light: World of Warcraft's Full-Spectrum 3D Achievement</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-the-fn-buttons-back-on-track-asus-laptop-repair-guide/"><u>Getting the Fn Buttons Back On Track: ASUS Laptop Repair Guide</u></a></li>
<li><a href="https://change-location.techidaily.com/honor-magic-5-camera-not-working-unexpected-error-fix-it-now-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Honor Magic 5 Camera Not Working Unexpected Error? Fix It Now | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-the-no-sound-devices-found-error-in-windows-11-with-ease/"><u>How to Correct the No Sound Devices Found Error in Windows 11 with Ease</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/how-to-remove-background-noise-from-skype-video-calls/"><u>How to Remove Background Noise From Skype Video Calls</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-watch-hulu-outside-us-on-vivo-s17t-drfone-by-drfone-virtual-android/"><u>How to Watch Hulu Outside US On Vivo S17t | Dr.fone</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/in-2024-here-are-some-of-the-best-pokemon-discord-servers-to-join-on-apple-iphone-11-pro-max-drfone-by-drfone-virtual-ios/"><u>In 2024, Here are Some of the Best Pokemon Discord Servers to Join On Apple iPhone 11 Pro Max | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-vivo-s17e-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Vivo S17e? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-changeadd-location-filters-on-snapchat-for-your-lava-blaze-curve-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change/Add Location Filters on Snapchat For your Lava Blaze Curve 5G | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/initiate-seamless-gaming-streams-mastering-obs-recording/"><u>Initiate Seamless Gaming Streams  Mastering OBS Recording</u></a></li>
<li><a href="https://some-techniques.techidaily.com/innovative-guide-transforming-social-media-sounds-into-mobile-alerts-for-2024/"><u>Innovative Guide  Transforming Social Media Sounds Into Mobile Alerts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207645731-keyboard-stutter-on-windows-10-heres-how-you-can-fix-it/"><u>Keyboard Stutter on Windows 10? Here’s How You Can Fix It!</u></a></li>
<li><a href="https://common-error.techidaily.com/optimized-system-configuration-overcomes-previous-resource-limitations-in-services/"><u>Optimized System Configuration Overcomes Previous Resource Limitations in Services</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-windows-10-casting-hurdles-solutions-to-device-unavailable-for-cast/"><u>Overcome Windows 10 Casting Hurdles: Solutions to 'Device Unavailable for Cast'</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/cle-community-standards-on-youtube-for-2024/"><u>Pinnacle Community Standards on YouTube for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-windows-10s-delayed-shutdown-bug-get-started/"><u>Quick Fixes for Windows 10'S Delayed Shutdown Bug - Get Started</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-when-your-bluetooth-mouse-stops-working-on-windows-computers/"><u>Quick Solutions for When Your Bluetooth Mouse Stops Working on Windows Computers</u></a></li>
<li><a href="https://howto.techidaily.com/reasons-for-meizu-21-pro-stuck-on-startup-screen-and-ways-to-fix-them-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Reasons for Meizu 21 Pro Stuck on Startup Screen and Ways To Fix Them | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212456673-resolve-your-overwatch-audio-glitches-instantly/"><u>Resolve Your Overwatch Audio Glitches Instantly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-initialization-error-in-rendering-engine-enhanced-version-2021/"><u>Resolved: Initialization Error in Rendering Engine (Enhanced Version, 2021)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-this-device-is-absent-issues-across-windows-11-8-and-7-platforms/"><u>Resolving 'This Device Is Absent' Issues Across Windows 11, 8 & 7 Platforms</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-high-cpu-usage-by-windows-11s-runtime-broker-a-comprehensive-guide/"><u>Resolving High CPU Usage by Windows 11'S Runtime Broker: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-insights-addressing-playback-errors-due-to-missing-sources-in-windows-environments/"><u>Solution Insights: Addressing 'Playback Errors Due to Missing Sources' In Windows Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205909632-solve-the-windows-11-will-not-shut-down-issue-proven-methods-inside/"><u>Solve the 'Windows 11 Will Not Shut Down' Issue - Proven Methods Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-fatal-error-code-1603-in-installations-a-comprehensive-guide-to-recovery/"><u>Solving Fatal Error Code 1603 in Installations - A Comprehensive Guide to Recovery</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-of-unclear-text-in-windows-11-tips-and-tricks-for-a-sharper-display/"><u>Solving the Issue of Unclear Text in Windows 11 – Tips & Tricks for a Sharper Display</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-of-undetected-devices-a-comprehensive-guide-to-mend-your-bluetooth-on-windows-11/"><u>Solving the Mystery of Undetected Devices - A Comprehensive Guide to Mend Your Bluetooth on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-unexpected-autostart-issues-on-your-windows-11-machine/"><u>Solving Unexpected Autostart Issues on Your Windows 11 Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-the-missing-binkw32dll-error-message/"><u>Step-by-Step Fix for the Missing binkw32.dll Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-resolve-failed-feature-updates-on-windows-11-version/"><u>Step-by-Step Guide to Resolve Failed Feature Updates on Windows 11 Version</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-fixes-for-xbox-ones-connection-woes-with-xbox-live/"><u>The Definitive Fixes for Xbox One's Connection Woes with Xbox Live</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-troubleshooting-manual-for-dealing-with-black-screens-on-your-dell-computer/"><u>The Ultimate Troubleshooting Manual for Dealing with Black Screens on Your Dell Computer</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-huawei-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Huawei</u></a></li>
<li><a href="https://common-error.techidaily.com/touchpad-not-working-fixed/"><u>Touchpad Not Working [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/trim-high-cpu-usage-in-win11-via-wmi-enhancements/"><u>Trim High CPU Usage in Win11 via WMI Enhancements</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204854376-trouble-with-netflix-discover-why-its-not-streaming-and-how-to-fix-it/"><u>Trouble with Netflix? Discover Why It's Not Streaming and How to Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-fn-keys-in-dell-computers-easy-fixes-you-can-do-now/"><u>Troubleshooting Non-Responsive Fn Keys in Dell Computers - Easy Fixes You Can Do Now</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-port-reset-failures-on-usb-devices-in-windows-11-tips-and-solutions/"><u>Troubleshooting Port Reset Failures on USB Devices in Windows 11 – Tips & Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-resolve-d3d-error-not-available/"><u>Troubleshooting Steps to Resolve D3D Error 'Not Available'</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-fake-gps-location-pro-and-is-it-good-on-vivo-y200e-5g-drfone-by-drfone-virtual-android/"><u>What is Fake GPS Location Pro and Is It Good On Vivo Y200e 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-update-stuck-or-frozen-how-do-i-fix-it/"><u>Windows 11 Update Stuck or Frozen - How Do I Fix It?</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17727588&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/Affiliates_300x250px_valentinesday.png" border="0"></a>
<!-- affiliate ads end -->