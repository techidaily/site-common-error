---
title: "Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079"
date: 2024-09-09T08:50:19.815Z
updated: 2024-09-10T08:50:19.815Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079"
excerpt: "This Article Describes Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079"
thumbnail: https://thmb.techidaily.com/24b4a5d68fd5e6bea75410f8f6c4c82cdd5bcbea33115cb8218e3e0a99c10ef2.jpg
---

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123508/26400" target="_top" id="2123508">
  <img src="//a.impactradius-go.com/display-ad/26400-2123508" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123508/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115950/19272" target="_top" id="2115950">
  <img src="//a.impactradius-go.com/display-ad/19272-2115950" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115950/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139108/17108" target="_top" id="2139108">
  <img src="//a.impactradius-go.com/display-ad/17108-2139108" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139108/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137378/7443" target="_top" id="2137378">
  <img src="//a.impactradius-go.com/display-ad/7443-2137378" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137378/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5)  

When it finish rebooting, run System Restore again.  
  
<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135316/14409" target="_top" id="2135316">
  <img src="//a.impactradius-go.com/display-ad/14409-2135316" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135316/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115928/19272" target="_top" id="2115928">
  <img src="//a.impactradius-go.com/display-ad/19272-2115928" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-fb-tunes-unlimited-playlist/"><u>[New] 2024 Approved FB Tunes Unlimited Playlist</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-2024-approved-optimal-viewing-verticalhorizontal-in-fb-videos/"><u>[New] 2024 Approved Optimal Viewing - Vertical/Horizontal in FB Videos?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-ultimate-razer-webcam-analysis/"><u>[New] 2024 Approved Ultimate Razer Webcam Analysis</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-making-waves-in-popularity-how-to-earn-vimeo-writers-picks/"><u>[New] In 2024, Making Waves in Popularity How to Earn Vimeo' Writers’ Picks</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/astering-media-with-top-5-photo-and-video-apps-on-iosandroid-devices/"><u>[New] Mastering Media with Top 5 Photo & Video Apps on iOS/Android Devices</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/new-playlist-on-a-page-embedding-yt-videos-online/"><u>[New] Playlist on a Page Embedding YT Videos Online</u></a></li>
<li><a href="https://common-error.techidaily.com/repaired-comprehensive-tips-to-correct-the-pervasive-red-screen-of-death-problem/"><u>[REPAIRED] Comprehensive Tips to Correct the Pervasive 'Red Screen of Death' Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-forza-horizon-4-no-sound-problem/"><u>[SOLVED] Forza Horizon 4 No Sound Problem</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-2024-approved-discover-top-screen-capture-apps-for-windowsmacos/"><u>[Updated] 2024 Approved Discover Top Screen Capture Apps for Windows/macOS</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-master-your-path-to-success-with-youtubes-keywords-guide/"><u>[Updated] 2024 Approved Master Your Path to Success with YouTube's Keywords Guide</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-time-saving-strategies-mastering-video-playback-speed/"><u>[Updated] In 2024, Time-Saving Strategies Mastering Video Playback Speed</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-linux-windows-and-mac-10-budget-video-player-options-for-2024/"><u>[Updated] Linux, Windows & Mac 10 Budget Video Player Options for 2024</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-quick-react-guide-efficiently-answering-discord-messages/"><u>[Updated] Quick-React Guide Efficiently Answering Discord Messages</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-step-towards-stunning-visuals-using-video-enhancer-22/"><u>[Updated] Step Towards Stunning Visuals - Using Video Enhancer 2.2</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-vlc-capture-a-comprehensive-recording-tutorial/"><u>[Updated] VLC Capture A Comprehensive Recording Tutorial</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-5-quick-hacks-to-sharpen-your-indie-filmmaking-skills/"><u>2024 Approved 5 Quick Hacks to Sharpen Your Indie Filmmaking Skills</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-efficient-reliable-and-free-your-ultimate-guide-to-videodownloading-pins/"><u>2024 Approved Efficient, Reliable & Free! Your Ultimate Guide to Videodownloading Pins</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/2024-approved-keeping-up-with-aspect-ratios-for-twitter-content/"><u>2024 Approved Keeping Up with Aspect Ratios for Twitter Content</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mobile-recorder-iphones-future-call-log/"><u>2024 Approved Mobile Recorder IPhone's Future Call Log</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-oneplus-nord-ce-3-5g-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On OnePlus Nord CE 3 5G | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On Honor X8b | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/ai-showcase-surpassing-a-venerable-standard/"><u>AI Showcase: Surpassing a Venerable Standard</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-trouble-connecting-your-keyboard-to-your-pc-made-simple/"><u>Bluetooth Trouble? Connecting Your Keyboard to Your PC Made Simple</u></a></li>
<li><a href="https://vp-tips.techidaily.com/brillianttoons-in-depth-review-2024-guide/"><u>BrilliantToons In-Depth Review 2024 Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/directx-initialization-problem-solved-successful-device-creation-tips/"><u>DirectX Initialization Problem Solved: Successful Device Creation Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-for-malfunctioning-windows-keyboards-dealing-with-persistent-keys/"><u>DIY Fixes for Malfunctioning Windows Keyboards: Dealing with Persistent Keys</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-your-system-cant-reach-the-remote-server/"><u>Effective Solutions for When Your System Can't Reach the Remote Server</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/enhanced-site-performance-through-cookiebot-integration-a-game-changing-approach-to-analytics-and-retargeting/"><u>Enhanced Site Performance Through Cookiebot Integration: A Game-Changing Approach to Analytics and Retargeting</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-resolving-the-missing-directx-component-d3derr/"><u>Expert Advice for Resolving The Missing DirectX Component (D3DERR)</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-insights-diagnosing-and-repairing-the-black-screen-phenomenon-on-your-dell-pc/"><u>Expert Insights: Diagnosing and Repairing the Black Screen Phenomenon on Your Dell PC</u></a></li>
<li><a href="https://common-error.techidaily.com/five-effective-methods-to-repair-your-windows-11-touchscreen-issues/"><u>Five Effective Methods to Repair Your Windows 11 Touchscreen Issues</u></a></li>
<li><a href="https://howto.techidaily.com/fix-the-error-of-unfortunately-the-processcomandroidphone-has-stopped-on-tecno-spark-10-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix the Error of Unfortunately the Process.com.android.phone Has Stopped on Tecno Spark 10 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-out-of-a-pinch-unlocking-windows-10-from-continuous-airplane-mode/"><u>Getting Out of a Pinch: Unlocking Windows 10 From Continuous Airplane Mode</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/head-to-head-review-sonys-ps5-slim-versus-full-sized-console-battle/"><u>Head-to-Head Review: Sony's PS5 Slim Versus Full-Sized Console Battle</u></a></li>
<li><a href="https://common-error.techidaily.com/identifying-and-fixing-high-traffic-caused-by-svchostexe-netsvcs-in-windows-systems/"><u>Identifying & Fixing High Traffic Caused by Svchost.exe NETSVCS in Windows Systems</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/in-2024-5-tutorials-on-how-to-transfer-photos-from-apple-iphone-13-to-new-iphone-drfone-by-drfone-transfer-from-ios/"><u>In 2024, 5 Tutorials on How to Transfer Photos From Apple iPhone 13 to New iPhone | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-cast-oppo-reno-10-5g-screen-to-pc-using-wifi-drfone-by-drfone-android/"><u>In 2024, How to Cast Oppo Reno 10 5G Screen to PC Using WiFi | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-tecno-spark-10-5g-phone-without-any-data-loss-by-drfone-android/"><u>In 2024, How to Unlock Tecno Spark 10 5G Phone without Any Data Loss</u></a></li>
<li><a href="https://common-error.techidaily.com/locating-and-fixing-the-necessary-driver-your-pc-requires-for-media-devices/"><u>Locating and Fixing the Necessary Driver Your PC Requires For Media Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-monitor-errors-a-deep-dive-into-unsupported-input-categories/"><u>Navigating Monitor Errors: A Deep Dive Into Unsupported Input Categories</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-incompatibility-hurdles-with-easy-driver-update-techniques-on-windows-systems-solved/"><u>Overcome Incompatibility Hurdles with Easy Driver Update Techniques on Windows Systems (Solved)</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-persistent-update-issue-fixing-error-code-0x8024401c-in-windows-10-and-11-systems/"><u>Overcoming the Persistent Update Issue: Fixing Error Code 0X8024401c in Windows 10 and 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolving-dns-server-not-available-issues/"><u>Quick Solutions: Resolving 'DNS Server Not Available' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-window-10-shutdown-lags-with-ease/"><u>Resolve Your Window 10 Shutdown Lags with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-a-non-functional-corsair-keyboard/"><u>Resolved: Troubleshooting a Non-Functional Corsair Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-ensuring-your-hardware-drivers-work-seamlessly-with-windows-update-solved/"><u>Resolved! Ensuring Your Hardware Drivers Work Seamlessly With Windows Update (Solved)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-apex-legends-cheating-issues-the-simple-fix-youve-been-waiting-for/"><u>Resolving Apex Legends Cheating Issues: The Simple Fix You've Been Waiting For!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-installation-issue-fixing-error-code-80240020/"><u>Resolving Windows 10 Installation Issue: Fixing Error Code 80240020</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-update-error-0x8024401c-a-step-by-step-fix-for-windows-11-users/"><u>Resolving Windows Update Error 0X8024401c: A Step-by-Step Fix for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-escaping-the-endless-loop-of-windows-configuration-preparation/"><u>Solution Guide: Escaping the Endless Loop of Windows Configuration Preparation</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-function-keys-problem-a-guide-on-restoring-fn-key-functionality-in-dell-computers/"><u>Solving the Function Keys Problem: A Guide on Restoring 'FN' Key Functionality in Dell Computers</u></a></li>
<li><a href="https://win-dash.techidaily.com/solving-the-mystery-why-arent-my-bluetooth-gadgets-detected-by-pcs-device-manager-and-what-to-do-about-it/"><u>Solving the Mystery: Why Aren't My Bluetooth Gadgets Detected by PC's Device Manager and What to Do About It?</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-usb-functionality-on-your-pc-with-windows-1011/"><u>Step-by-Step Guide: Restoring USB Functionality on Your PC with Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-when-your-laptops-mic-stops-working/"><u>Step-by-Step Solution for When Your Laptop's Mic Stops Working</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/tage-der-woche-deutsche-sprachreise-antreten/"><u>Tage Der Woche: Deutsche Sprachreise Antreten</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-essential-checklist-purging-backdrops-with-affinity-photo/"><u>The Essential Checklist Purging Backdrops with Affinity Photo</u></a></li>
<li><a href="https://hardware-reviews.techidaily.com/transform-your-android-lockscreen-into-an-iphone-inspired-display/"><u>Transform Your Android Lockscreen Into an iPhone-Inspired Display</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-text-copier-in-windows-11/"><u>Trouble with Text Copier in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-charging-issues-when-plugged-into-windows-pcs-version-7-or-10/"><u>Troubleshooting Non-Charging Issues When Plugged Into Windows PCs (Version 7 or 10)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-steam-updates-a-step-by-step-guide/"><u>Troubleshooting Your Steam Updates: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-resolving-windows-10-failure-to-shut-down-problems-in-under-5-steps/"><u>Troubleshooting: Resolving Windows 10 Failure to Shut Down Problems in Under 5 Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-solving-the-problem-of-error-code-31-in-windows-os/"><u>Understanding and Solving the Problem of Error Code ☢️31 in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-absence-of-screen-brightness-control/"><u>Unexpected Absence of Screen Brightness Control</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/unlock-opportunities-through-english-mastery/"><u>Unlock Opportunities Through English Mastery</u></a></li>
<li><a href="https://common-error.techidaily.com/why-is-my-pc-running-windows-11-turning-on-without-command/"><u>Why Is My PC Running Windows 11 Turning on without Command?</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207707840-windows-10-touchscreen-issues-fix-it-in-just-five-ways/"><u>Windows 10 Touchscreen Issues? Fix It in Just Five Ways!</u></a></li>
</ul></div>
