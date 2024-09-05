---
title: "Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020"
date: 2024-09-04T20:32:49.912Z
updated: 2024-09-05T20:32:49.912Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020"
excerpt: "This Article Describes Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020"
thumbnail: https://thmb.techidaily.com/227bd0353ed763348ef514468bae7b22e2b22e0109d88910437782328b50ad10.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-2024-approved-unlock-success-top-12-tycoon-games-to-capture-your-attention/"><u>[New] 2024 Approved  Unlock Success  Top 12 Tycoon Games to Capture Your Attention</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-pinnacle-players-list-best-google-cardboard-vr-game-titles/"><u>[New] Pinnacle Players' List  Best Google Cardboard VR Game Titles</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-quick-access-to-hidden-past-reddit-posts-and-articles/"><u>[New] Quick Access to Hidden, Past Reddit Posts and Articles</u></a></li>
<li><a href="https://some-tips.techidaily.com/updated-swift-image-adaptation-techniques-for-iphone-users/"><u>[Updated] Swift Image Adaptation Techniques for iPhone Users</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-accelerated-content-acquisition-with-funimate/"><u>2024 Approved  Accelerated Content Acquisition with Funimate</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-awesome-top-5-ios-podcast-platforms/"><u>2024 Approved  Awesome Top 5 iOS Podcast Platforms</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-key-online-repositories-for-rich-text-visualization/"><u>2024 Approved  Key Online Repositories for Rich Text Visualization</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/affordable-innovation-or-confused-concept-exploring-the-microsoft-surface-go-experience/"><u>Affordable Innovation or Confused Concept? Exploring the Microsoft Surface Go Experience</u></a></li>
<li><a href="https://discover-great.techidaily.com/connect-with-professionals-at-digiarty-elevate-your-online-presence/"><u>Connect with Professionals at Digiarty – Elevate Your Online Presence</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/connecting-nintendo-switch-to-tv-a-comprehensive-tutorial-for-gamers/"><u>Connecting Nintendo Switch to TV: A Comprehensive Tutorial for Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-solving-input-latency-problems-with-your-windows-11-keyboard/"><u>Diagnosing and Solving Input Latency Problems with Your Windows 11 Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210753236-directx-hardware-renderer-initialization-issues-solutions-uncovered/"><u>DirectX Hardware Renderer Initialization Issues - Solutions Uncovered</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-your-pc-refresh-a-step-by-step-walkthrough-for-windows-11-reboot/"><u>Fast-Track Your PC Refresh: A Step-by-Step Walkthrough for Windows 11 Reboot</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-lenovo-wifi-error-no-appropriate-driver-to-be-installed/"><u>Fix Lenovo WiFi Error: No Appropriate Driver to Be Installed</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-severe-bugs-and-errors-in-fortnite-tips-and-tricks-for-a-smooth-experience/"><u>Fixing Severe Bugs and Errors in Fortnite: Tips & Tricks for a Smooth Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-stuck-boot-loops-overcome-being-trapped-at-setting-up-windows-prepare-effortlessly/"><u>Fixing Stuck Boot Loops: Overcome Being Trapped at 'Setting Up Windows Prepare' Effortlessly</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-sim-cards-of-infinix-note-30-vip-racing-edition-without-puk-codes-by-drfone-android/"><u>In 2024, How To Unlock SIM Cards Of Infinix Note 30 VIP Racing Edition Without PUK Codes</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-online-meeting-transcriptions/"><u>In 2024, Online Meeting Transcriptions</u></a></li>
<li><a href="https://common-error.techidaily.com/instant-fix-for-electronic-gadgets-when-they-cant-find-a-charge/"><u>Instant Fix for Electronic Gadgets - When They Can't Find a Charge!</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-tech-efficiently-restore-touch-functionality-in-windows-10-with-five-proven-strategies/"><u>Master the Tech: Efficiently Restore Touch Functionality in Windows 10 with Five Proven Strategies</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/mastering-fb-buzz-creating-share-worthy-content/"><u>Mastering FB Buzz  Creating Share-Worthy Content</u></a></li>
<li><a href="https://win-able.techidaily.com/overcoming-startup-issues-with-armored-core-vi-fires-of-rubicon-on-your-system/"><u>Overcoming Startup Issues with Armored Core VI: Fires of Rubicon on Your System</u></a></li>
<li><a href="https://common-error.techidaily.com/rebooting-woes-windows-10-troubleshooting/"><u>Rebooting Woes: Windows 10 Troubleshooting</u></a></li>
<li><a href="https://common-error.techidaily.com/repairing-internal-camera-glitches-in-microsoft-windows-a-comprehensive-how-to/"><u>Repairing Internal Camera Glitches in Microsoft Windows: A Comprehensive How-To</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-unresponsive-laptop-mouse-problems-with-simple-usb-fixes/"><u>Solve Unresponsive Laptop Mouse Problems with Simple USB Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-windows-amoled-screen-issues-a-guide-with-5-proven-methods/"><u>Solve Your Windows Amoled Screen Issues: A Guide with 5 Proven Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-correcting-bad-image-glitches-in-modern-windows-os/"><u>Step-by-Step Guide: Correcting 'Bad Image' Glitches in Modern Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-reconnecting-your-media-on-a-windows-pc/"><u>Step-by-Step Solution: Reconnecting Your Media on a Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-the-service-registration-missing-problem-on-windows-11/"><u>Step-by-Step Solutions for the 'Service Registration Missing' Problem on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-resolving-windows-1011-sound-failures-dealing-with-missing-audio-devices/"><u>The Ultimate Guide to Resolving Windows 10/11 Sound Failures: Dealing with Missing Audio Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-optimize-your-file-explorer-in-windows-10-today/"><u>Troubleshoot and Optimize Your File Explorer in Windows 10 Today</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-undetected-device-issues-with-bluetooth-in-windows-11/"><u>Troubleshooting Guide: Resolving Undetected Device Issues with Bluetooth in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/why-apple-account-disabled-on-your-iphone-6-how-to-fix-by-drfone-ios/"><u>Why Apple Account Disabled On your iPhone 6? How to Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-werfaultexe-issues-on-windows-six-essential-hacks-and-tweaks-for-better-stability/"><u>Winning Against WerFault.exe Issues on Windows: Six Essential Hacks and Tweaks for Better Stability</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->