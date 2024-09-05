---
title: "Fixing 'Class Unregistered' Errors in Windows 11: A Comprehensive Guide"
date: 2024-09-04T20:22:15.808Z
updated: 2024-09-05T20:22:15.808Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing 'Class Unregistered' Errors in Windows 11: A Comprehensive Guide"
excerpt: "This Article Describes Fixing 'Class Unregistered' Errors in Windows 11: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/47ffc6f56df8f55aee8393dc2516df4e9eefe4f14b61216a4ad108eecf8f871a.png
---

## Overcoming 'Class Unregistered on Windows 11' Error – Tips & Tricks Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a90d415e22e7.jpg)

 If you want to open an app or program on your Windows 10, but if fails, and you’re seeing this error saying: **Class not registered** . Reset assured, you’re not alone. Many Windows users encounter this error. More importantly, you can fix it easily by yourself.

 This error occurs on your Windows 10 mainly due to the app or the program with**unregistered DLL files** . You can probably fix it by these following solutions:

 **Try one at a time:**

1. [  Fix DCOM(Distributed Component Object Model) errors ](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 1. Fix DCOM%28Distributed Component Object Model%29 errors)
2. [ Re-register ExplorerFrame.dll file](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 2. Re-register ExplorerFrame.dll file)
3. [ Start Internet Explorer ETW Collector Service](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 3. Start Internet Explorer ETW Collector Service)
4. [ Set Windows Photo Viewer as a default image viewer ](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 4. Set Windows Photo Viewer as a default image viewer)
5. [ Disable iCloud](<https://www.drivereasy.com/knowledge/fix-class-not-registered-error-on-windows-10-solved/#Fix> 5. Disable iCloud) ``

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

``

``

`` 2) Go to **Component Services**  \> **Computers**  \> **My Computer**  on the Component Services window. Then double-click on **DCOM Config** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-17.png)

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

``

``

`` 3) Open the app again to see if it goes fine.

``

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<span id="1983553">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983553.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983553">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983553.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983553%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983553/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<span id="1993651">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993651.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993651">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993651.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993651%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993651/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)

<!-- affiliate ads begin -->
<span id="1424533">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424533.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424533">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424533.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424533%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424533/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Open the app again to see if it goes fine.

That’s it!

 Hopefully you have got your Windows 10 out of Class not registered error.

[](https://tools.techidaily.com/drivereasy/download/)

[](https://tools.techidaily.com/drivereasy/download/) [](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-data.techidaily.com/024-approved-unlock-audience-favorites-3-powerful-tales/"><u>[New] 2024 Approved  Unlock Audience Favorites  3 Powerful Tales</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-gratitude-freepaid-video-outro-template-gallery/"><u>[New] Gratitude  Free/Paid Video Outro Template Gallery</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/nsightful-rank-trackers-unlock-your-videos-potential/"><u>[New] Insightful Rank Trackers - Unlock Your Video's Potential</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-exploring-profit-sharing-in-youtube-short-creation/"><u>[Updated] 2024 Approved  Exploring Profit Sharing in YouTube Short Creation</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/updated-club-anthems-expertly-curated-dj-vids-downloads/"><u>[Updated] Club Anthems  Expertly Curated DJ Vids Downloads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-nine-powerful-microphone-capture-options-decoded/"><u>[Updated] In 2024, Nine Powerful Microphone Capture Options Decoded</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-unravel-the-secrets-of-crafting-engaging-snapchat-boomerangs-for-2024/"><u>[Updated] Unravel the Secrets of Crafting Engaging Snapchat Boomerangs for 2024</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-frugal-cloud-cradle-for-copious-file-collection/"><u>2024 Approved  Frugal Cloud Cradle for Copious File Collection</u></a></li>
<li><a href="https://fox-http.techidaily.com/2024-approved-funimate-unlocking-the-secrets-of-easy-downloads/"><u>2024 Approved  Funimate  Unlocking the Secrets of Easy Downloads</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-video-freelancers-talent-agreement-form/"><u>2024 Approved  Video Freelancers  Talent Agreement Form</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-virtuverse-video-vault/"><u>2024 Approved  VirtuVerse Video Vault</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-stuck-on-configuration-quick-tips-for-a-smooth-windows-installation/"><u>Bypass 'Stuck on Configuration' - Quick Tips for a Smooth Windows Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-troubleshooting-cyclic-redundancy-check-failures/"><u>Comprehensive Guide to Troubleshooting Cyclic Redundancy Check Failures</u></a></li>
<li><a href="https://tech-hub.techidaily.com/enhance-your-hr-routine-with-these-5-innovative-chatgpt-solutions/"><u>Enhance Your HR Routine with These 5 Innovative ChatGPT Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-successfully-completing-your-pending-windows-11-update-issues-addressed/"><u>Expert Tips: Successfully Completing Your Pending Windows 11 Update [ISSUES ADDRESSED]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-non-functional-webcam-on-your-lenovo-laptop-easily/"><u>Fixing a Non-Functional Webcam on Your Lenovo Laptop Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-logitech-g930-headset-audio-issue-steps-and-tips/"><u>Fixing the Logitech G930 Headset Audio Issue: Steps and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/graphics-driver-update-enables-miracast-functionality/"><u>Graphics Driver Update Enables Miracast Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-excessive-msmpengexe-cpu-consumption-in-windows-11-computers/"><u>How to Fix Excessive MsMpEng.exe CPU Consumption in Windows 11 Computers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-fix-iphone-12-pro-max-passcode-not-working-by-drfone-ios/"><u>How to Fix iPhone 12 Pro Max Passcode not Working?</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-whatsapp-from-apple-iphone-6-plus-to-other-iphone-14-pro-devices-drfone-by-drfone-transfer-whatsapp-from-ios-transfer-whatsapp-from-ios/"><u>How To Transfer WhatsApp From Apple iPhone 6 Plus to other iPhone 14 Pro devices? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-and-fix-error-0x800f0922-during-windows-10-update/"><u>How to Troubleshoot and Fix Error 0X800F0922 During Windows 10 Update</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-11-best-location-changers-for-apple-iphone-15-plus-drfone-by-drfone-virtual-ios/"><u>In 2024, 11 Best Location Changers for Apple iPhone 15 Plus | Dr.fone</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-motorola-razr-40withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Motorola Razr 40with/without a PC</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-snapchat-secrets-lowering-playback-rate-for-better-views/"><u>In 2024, Snapchat Secrets  Lowering Playback Rate for Better Views</u></a></li>
<li><a href="https://common-error.techidaily.com/in-depth-manual-how-to-restore-display-colors-and-eliminate-black-screens-on-dell-computers/"><u>In-Depth Manual: How to Restore Display Colors and Eliminate Black Screens on Dell Computers</u></a></li>
<li><a href="https://android-frp.techidaily.com/latest-guide-how-to-bypass-asus-frp-without-computer-by-drfone-android/"><u>Latest Guide How To Bypass Asus FRP Without Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/master-obs-troubleshooting-eradicating-black-screens-in-live-gaming-broadcasts/"><u>Master OBS Troubleshooting: Eradicating Black Screens in Live Gaming Broadcasts</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-the-stuck-boot-screen-repairing-your-pc-when-it-freezes-on-windows-setup/"><u>Overcome the Stuck Boot Screen: Repairing Your PC When It Freezes on Windows Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-persistent-slowdowns-the-complete-guide-for-stuck-valorant-loading-screens/"><u>Overcoming Persistent Slowdowns: The Complete Guide for Stuck Valorant Loading Screens</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-windows-update-error-code-0x80070002-a-step-by-step-guide/"><u>Quick Fixes for Windows Update Error Code 0X80070002: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205020648-quick-solutions-when-your-hp-laptops-keys-stop-functioning-correctly/"><u>Quick Solutions When Your HP Laptop's Keys Stop Functioning Correctly!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-minecrafts-error-code-5-a-step-by-step-guide/"><u>Resolving Minecraft's Error Code ^5: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-persistent-windows-update-error-code-0x802n401c-on-windows-10-and-11/"><u>Resolving the Persistent Windows Update Error Code 0X802n401C on Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-successfully-restoring-your-keyboard-settings/"><u>Step-by-Step Guide: Successfully Restoring Your Keyboard Settings</u></a></li>
<li><a href="https://facebook.techidaily.com/the-comprehensive-guide-to-group-recognition-in-social-media/"><u>The Comprehensive Guide to Group Recognition in Social Media</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-troubleshooting-guide-to-restore-symbol-functionality-in-apps-and-websites/"><u>The Ultimate Troubleshooting Guide to Restore @ Symbol Functionality in Apps and Websites</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-damaged-files-in-windows-11/"><u>Troubleshooting and Repairing Damaged Files in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-error-internet-explorer-has-stopped-working-problem/"><u>Troubleshooting the 'Error: Internet Explorer Has Stopped Working' Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-issue-fixing-right-click-functionality-on-a-mouse-with-windows-11/"><u>Troubleshooting the Issue: Fixing Right-Click Functionality on a Mouse with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-realtek-network-controllers-fail-to-show-up/"><u>Troubleshooting Tips for When Realtek Network Controllers Fail to Show Up</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210484870-troubleshooting-your-battleye-installation-woes-now-fixed/"><u>Troubleshooting Your BattlEye Installation Woes - Now Fixed</u></a></li>
<li><a href="https://tech-hub.techidaily.com/turing-test-or-its-successors-discovering-current-ai-evaluation-methods/"><u>Turing Test or Its Successors? Discovering Current AI Evaluation Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/update-your-tech-resolving-failed-to-initialize-renderer-with-latest-2021-fixes/"><u>Update Your Tech: Resolving 'Failed to Initialize Renderer' With Latest 2021 Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-7-installation-issue-overcoming-the-no-device-drivers-present-hurdle-successfully/"><u>Windows 7 Installation Issue: Overcoming the 'No Device Drivers Present' Hurdle Successfully</u></a></li>
</ul></div>
