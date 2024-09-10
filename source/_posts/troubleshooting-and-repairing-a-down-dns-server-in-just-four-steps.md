---
title: Troubleshooting and Repairing a Down DNS Server in Just Four Steps
date: 2024-09-09T09:03:07.887Z
updated: 2024-09-10T09:03:07.887Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Repairing a Down DNS Server in Just Four Steps
excerpt: This Article Describes Troubleshooting and Repairing a Down DNS Server in Just Four Steps
thumbnail: https://thmb.techidaily.com/f13aeea6c73457fbc5bbd1b6bff4a0c00a428af0a90b0cd758e49ef9cfc3066d.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
<!-- affiliate ads begin -->
<a href="https://bluettiit.sjv.io/c/5597632/2114267/17093" target="_top" id="2114267">
  <img src="//a.impactradius-go.com/display-ad/17093-2114267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettiit.sjv.io/i/5597632/2114267/17093" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120862/26400?prodsku=Saturn" target="_top" id="2120862">
  <img src="//a.impactradius-go.com/display-ad/26400-2120862" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120862/26400?prodsku=Saturn" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135370/19272" target="_top" id="2135370">
  <img src="//a.impactradius-go.com/display-ad/19272-2135370" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135370/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137219/26400" target="_top" id="2137219">
  <img src="//a.impactradius-go.com/display-ad/26400-2137219" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137219/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118318/7443" target="_top" id="2118318">
  <img src="//a.impactradius-go.com/display-ad/7443-2118318" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://tiktok-video-files.techidaily.com/new-2024-approved-conquer-tiktok-with-proficient-voiceovers/"><u>[New] 2024 Approved Conquer TikTok with Proficient Voiceovers</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/024-approved-maximizing-impact-with-youtube-micro-videos/"><u>[New] 2024 Approved Maximizing Impact with YouTube Micro Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-restoring-clear-vision-fixing-iphone-lens-out-of-focus/"><u>[New] 2024 Approved Restoring Clear Vision Fixing iPhone Lens Out-of-Focus</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ros-picks-best-microphones-for-asmr-recording-for-2024/"><u>[New] Pros' Picks Best Microphones for ASMR Recording for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-when-your-mouse-cursor-goes-missing-in-windows-win-10-a-step-by-step-solution/"><u>[Troubleshooting] When Your Mouse Cursor Goes Missing in Windows (Win) [10]: A Step-by-Step Solution.</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-twitter-marketing-101-step-by-step-guide/"><u>[Updated] In 2024, Twitter Marketing 101 Step-by-Step Guide</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-wechat-photo-frame-specifications/"><u>2024 Approved WeChat Photo Frame Specifications</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-0x80072efd-blues-easy-repairs-for-windows-10-users/"><u>Beat the 0X80072EFD Blues: Easy Repairs for Windows 10 Users</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-apple-iphone-14-plus-drfone-by-drfone-virtual-ios/"><u>Best 10 Mock Location Apps Worth Trying On Apple iPhone 14 Plus | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209874334-bluetooth-connection-problems-in-windows-10-heres-how-to-fix-them/"><u>Bluetooth Connection Problems in Windows 10? Here's How to Fix Them!</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-windows-10-stalls-top-tips-for-quick-recovery/"><u>Dealing with Windows 10 Stalls - Top Tips for Quick Recovery</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-aoc-computer-screens-not-working-properly-with-the-latest-windows-operating-system/"><u>Diagnosing and Repairing AOC Computer Screens Not Working Properly with the Latest Windows Operating System</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-the-latest-logitech-t630-software-for-windows-operating-systems-7810/"><u>Download the Latest Logitech T630 Software for Windows Operating Systems (7/8/10)</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-oppo-a78-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Oppo A78 Phone? | Dr.fone</u></a></li>
<li><a href="https://media-tips.techidaily.com/easy-steps-changing-mpg-files-into-mp4-format-on-your-mac/"><u>Easy Steps: Changing MPG Files Into MP4 Format on Your Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-google-hangouts-microphone-not-working/"><u>Easy to Fix Google Hangouts Microphone Not Working</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-a-quick-and-responsive-keyboard-experience/"><u>Effortless Fixes for a Quick and Responsive Keyboard Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-remedies-for-rapidly-restoring-power-when-your-device-says-no-charge/"><u>Effortless Remedies for Rapidly Restoring Power When Your Device Says 'No Charge'</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209210125-error-code-0x800f081f-on-your-mind-solving-the-dotnet-35-install-problems/"><u>Error Code 0X800F081F on Your Mind? Solving the DotNet 3.5 Install Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-successfully-addressing-windows-loadlibrary-failure-with-error-1114/"><u>Expert Tips for Successfully Addressing Windows 'LoadLibrary' Failure with Error 1114</u></a></li>
<li><a href="https://common-error.techidaily.com/fec-codes-like-reed-solomon-can-correct-detected-errors-without-retransmission/"><u>FEC Codes Like Reed-Solomon Can Correct Detected Errors without Retransmission.</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-when-your-dell-camcorder-wont-function-with-windows-pc/"><u>Fixes for When Your Dell Camcorder Won't Function with Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-resolved-problem-windows-error-code-1067-premature-process-end/"><u>Fixing the Issue: Resolved Problem - Windows Error Code 1#067: Premature Process End</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-persistent-device-error-code-28-on-your-windows-machine-step-by-step-tutorial/"><u>Fixing the Persistent Device Error Code 28 on Your Windows Machine – Step-by-Step Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-past-errors-a-step-by-step-fix-for-a-non-responsive-microsoft-store/"><u>Getting Past Errors: A Step-by-Step Fix for a Non-Responsive Microsoft Store</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-and-regaining-your-steam-files-that-went-missing/"><u>Guide to Fixing and Regaining Your Steam Files That Went MISSING</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/harmony-in-transit-relocating-your-loved-songs-for-2024/"><u>Harmony in Transit Relocating Your Loved Songs for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/high-quality-video-capture-for-tech-enthusiasts/"><u>High-Quality Video Capture for Tech Enthusiasts</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-fix-a-malfunctioning-mic-on-your-computer-system/"><u>How To Diagnose and Fix a Malfunctioning Mic on Your Computer System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-hub-port-power-spike-problem-successfully/"><u>How to Fix a Hub Port Power Spike Problem Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-rid-of-game-lags-in-pubg-expert-tips-and-tricks-uncovered/"><u>How to Get Rid of Game Lags in PUBG? Expert Tips & Tricks Uncovered!</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-apple-iphone-15-pro-max-data-from-ios-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How to Recover Apple iPhone 15 Pro Max Data From iOS iTunes Backup? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-sharefake-gps-on-uber-for-motorola-edgeplus-2023-drfone-by-drfone-virtual-android/"><u>How to share/fake gps on Uber for Motorola Edge+ (2023) | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/in-2024-6-ways-to-change-spotify-location-on-your-samsung-galaxy-a05s-drfone-by-drfone-virtual-android/"><u>In 2024, 6 Ways to Change Spotify Location On Your Samsung Galaxy A05s | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-9-best-phone-monitoring-apps-for-honor-70-lite-5g-drfone-by-drfone-virtual-android/"><u>In 2024, 9 Best Phone Monitoring Apps for Honor 70 Lite 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-12-prominent-motorola-fingerprint-not-working-solutions-by-drfone-android/"><u>In 2024, Top 12 Prominent Motorola Fingerprint Not Working Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-audio-settings-restoring-volume-in-windows-11-made-easy/"><u>Mastering Audio Settings: Restoring Volume in Windows 11 Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-your-airpods-windows-11-connectivity-challenges-the-latest-fixes/"><u>Overcome Your AirPods-Windows 11 Connectivity Challenges - The Latest Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-dysfunctional-function-keys-a-step-by-step-guide/"><u>Overcoming the Challenge of Dysfunctional Function Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/cting-your-presence-mastery-of-title-and-tag-use-on-youtube-for-2024/"><u>Perfecting Your Presence Mastery of Title and Tag Use on YouTube for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-guide-resolving-directx-9-device-failure-on-your-pc/"><u>Quick Fix Guide: Resolving DirectX 9 Device Failure on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-tips-for-speeding-up-your-pcs-initial-launch-sequence/"><u>Quick Tips for Speeding Up Your PC's Initial Launch Sequence</u></a></li>
<li><a href="https://buynow-info.techidaily.com/revolutionizing-mobile-experiences-in-depth-analysis-of-motorola-one-5g-aces-remarkable-speed-and-power-efficiency/"><u>Revolutionizing Mobile Experiences: In-Depth Analysis of Motorola One 5G Ace's Remarkable Speed and Power Efficiency</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-guide-to-resolving-the-persistent-update-service-failed-issue-error-0x80070652/"><u>Simple Guide to Resolving the Persistent 'Update Service Failed' Issue – Error 0X80070652</u></a></li>
<li><a href="https://extra-information.techidaily.com/snappy-picture-assemblies-a-brisk-guide-to-google-collages/"><u>Snappy Picture Assemblies A Brisk Guide to Google Collages</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-vanishing-cursor-issue-in-windows-11-a-step-by-step-guide/"><u>Solving the Vanishing Cursor Issue in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-an-unsecured-network-wire-in-windows/"><u>Step-by-Step Guide: Repairing an Unsecured Network Wire in Windows</u></a></li>
<li><a href="https://tech-haven.techidaily.com/stepwise-construction-of-a-web-app-powered-by-chatgpt/"><u>Stepwise Construction of a Web App Powered by ChatGPT</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-secret-to-success-with-filmora-top-10-editing-traits/"><u>The Secret to Success with Filmora Top 10 Editing Traits</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-airpods-pairing-problems-on-microsofts-latest-os-comprehensive-tips/"><u>Troubleshooting AirPods Pairing Problems on Microsoft's Latest OS - Comprehensive Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-correcting-insufficient-resource-alerts-in-systems/"><u>Troubleshooting and Correcting Insufficient Resource Alerts in Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-destiny-twos-server-accessibility-trouble/"><u>Troubleshooting and Solving Destiny ˈTwo's Server Accessibility Trouble</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-screen-stuttering-and-flickering-problems-on-windows-11-devices/"><u>Troubleshooting Screen Stuttering and Flickering Problems on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-ethernet-connection-problems-in-windows-10-and-7/"><u>Troubleshooting Steps: Resolving Ethernet Connection Problems in Windows 10 and 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-svchostexe-reducing-cpu-load-on-your-windows-11-pc-guide/"><u>Troubleshooting Svchost.exe: Reducing CPU Load on Your Windows 11 PC [Guide]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-10-combatting-high-disk-usage-from-microsoft-compatibility-telemetry/"><u>Troubleshooting Windows 10: Combatting High Disk Usage From Microsoft Compatibility Telemetry</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-erratic-wireless-mouse-problem-in-windows-11-and-10-a-comprehensive-guide/"><u>Troubleshooting Your Erratic Wireless Mouse Problem in Windows 11 and 10: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/unavailable-real-time-monitor-display-doesnt-recognize-present-input-delays/"><u>Unavailable: Real-Time Monitor Display Doesn't Recognize Present Input Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-xinput13dll-and-troubleshooting-its-absence/"><u>Understanding XINPUT1_3.dll & Troubleshooting Its Absence</u></a></li>
<li><a href="https://common-error.techidaily.com/unlit-display-random-outage/"><u>Unlit Display: Random Outage</u></a></li>
<li><a href="https://media-tips.techidaily.com/vpn-friendly-smart-tv-sticks-which-ones-can-be-used/"><u>VPN-Friendly Smart TV Sticks: Which Ones Can Be Used?</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/webcam-experience-pioneering-high-definition-video-capture-for-2024/"><u>WebCam Experience Pioneering High-Definition Video Capture for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-nokia-105-classic-drfone-by-drfone-virtual-android/"><u>Why Your WhatsApp Location is Not Updating and How to Fix On Nokia 105 Classic | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-volume-control-not-working-solved/"><u>Windows 11 Volume Control Not Working [SOLVED]</u></a></li>
</ul></div>
