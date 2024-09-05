---
title: 5 Effective Remedies When Your DNS Server Fails to Respond
date: 2024-09-04T20:23:29.345Z
updated: 2024-09-05T20:23:29.345Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes 5 Effective Remedies When Your DNS Server Fails to Respond
excerpt: This Article Describes 5 Effective Remedies When Your DNS Server Fails to Respond
thumbnail: https://thmb.techidaily.com/d37006e5965cff133da2576b0b3455692491cf1f8c58029bf90db9237f948dc9.jpg
---

## Master the Fix for 'Class Not Registered' Problem in Windows 11 - Effective Solutions Await

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
<span id="1976998">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1976998.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1976998">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1976998.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1976998%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1976998/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

<!-- affiliate ads begin -->
<span id="1936838">
					<video width="374" height="48" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1936838.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18409-1936838">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1936838.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:234px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcoinrule.sjv.io%2Fc%2F5597632%2F1936838%2F18409'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1936838/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130875/7443" target="_top" id="2130875">
  <img src="//a.impactradius-go.com/display-ad/7443-2130875" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130875/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105860/7443" target="_top" id="2105860">
  <img src="//a.impactradius-go.com/display-ad/7443-2105860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``

`` 3) Click **Default apps**  on the left pane. Then on the right pane, scroll down to click **Reset**  under the **Reset to the Microsoft recommended defaults**  section.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7-11.png)

``

``

4) Open the app again to see if it goes fine.

 Note: If you’ve installed iCloud on your Windows 10, you can try the fix below if all the fixes above don’t help.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135361/19272" target="_top" id="2135361">
  <img src="//a.impactradius-go.com/display-ad/19272-2135361" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 5: Disable iCloud

 Some users reported that to disable iCloud in Task Manager fix the error for them. So make sure to try to disable icloud if you install one on Windows 10.

 1) Press**Shift** +**Ctrl** +**Esc** keys at the same time to open**Task Manager** .

 2) On Task Manager window, tap on the **Startup** pane. Then find and right-click on **iCloud Services** . Click **Disable** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10-7.png)

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
<li><a href="https://snapchat-videos.techidaily.com/new-2024-approved-from-ordinary-to-outstanding-a-guide-to-snapchat-edits/"><u>[New] 2024 Approved  From Ordinary to Outstanding  A Guide to Snapchat Edits</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/024-approved-html-techniques-for-youtube-playlist-web-insertion/"><u>[New] 2024 Approved  HTML Techniques for YouTube Playlist Web Insertion</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-essential-techniques-for-convenient-iphone-screen-recording/"><u>[New] In 2024, Essential Techniques for Convenient Iphone Screen Recording</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/updated-craft-the-perfect-picture-on-android-with-these-5-best-apps/"><u>[Updated] Craft the Perfect Picture on Android with These 5 Best Apps</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-from-snapchat-to-social-upload-videos-on-twit/"><u>[Updated] From Snapchat to Social  Upload Videos on Twit</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-navigating-lenses-for-professional-videography/"><u>[Updated] Navigating Lenses for Professional Videography</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-ppt-visualization-leveraging-webcam-tech-for-2024/"><u>[Updated] PPT Visualization  Leveraging Webcam Tech for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tutorial-on-stopping-automatic-youtube-video-prefaces/"><u>[Updated] Tutorial on Stopping Automatic YouTube Video Prefaces</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1725285483067-mp4-mp3/"><u>如何免費地改變 MP4 到 MP3：這六大可靠的步驟指南</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/e-a-profitable-channel-with-ytp2024-mastery/"><u>Become a Profitable Channel with YTP2024 Mastery</u></a></li>
<li><a href="https://common-error.techidaily.com/bug-fixed-now-running-smoothly-32bit-apps-print-driver-issues-addressed/"><u>Bug Fixed: Now Running Smoothly - 32Bit Apps Print Driver Issues Addressed</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-overcome-the-persistent-windows-10-update-error-code-0x800705b4-explained/"><u>Effective Strategies to Overcome the Persistent Windows 10 Update Error: Code 0X800705b4 Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-when-your-steam-content-servers-cant-be-reached/"><u>Expert Tips for When Your Steam Content Servers Can't Be Reached</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-overcome-error-code-ce-3478-on-playstation-4-systems/"><u>Expert Tips to Overcome Error Code CE-3478 on PlayStation 4 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-restart-copypaste-feature-effectively-on-windows-11-machines/"><u>Expert Tips: Restart Copy/Paste Feature Effectively on Windows 11 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/exploring-the-phenomenon-of-automatic-boot-in-windows-10-systems/"><u>Exploring the Phenomenon of Automatic Boot in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-notorious-aw-snap-glitch-on-your-chrome-browser/"><u>Fixing the Notorious Aw, Snap! Glitch on Your Chrome Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-shockwave-flash-problem-with-google-chrome/"><u>Fixing the Shockwave Flash Problem with Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207828919-getting-windows-update-running-again-heres-how-you-fix-it/"><u>Getting Windows Update Running Again? Here’s How You Fix It!</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-nokia-g310-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Nokia G310 Phone | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-realme-gt-neo-5-se-location-on-skout-drfone-by-drfone-virtual-android/"><u>How to Change Realme GT Neo 5 SE Location on Skout | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-seamlessly-enable-usb-tethering-in-windows-11-a-step-by-step-guide/"><u>How to Seamlessly Enable USB Tethering in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-your-laptop-from-turning-off-without-warning-tips-for-a-smooth-run/"><u>How to Stop Your Laptop From Turning Off Without Warning – Tips for a Smooth Run</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-frugal-flight-assemblies-budget-friendly-drones-ranking/"><u>In 2024, Frugal Flight Assemblies  Budget-Friendly Drones Ranking</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-after-switching-from-vivo-t2-5g-to-latest-samsung-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data After Switching From Vivo T2 5G to Latest Samsung | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-music-from-lava-blaze-2-to-ipod-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Music from Lava Blaze 2 to iPod | Dr.fone</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-amazon-echo-show-10-gen-3-analysis-enhanced-mobility-feature/"><u>In-Depth Amazon Echo Show 10 (Gen 3) Analysis: Enhanced Mobility Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/microsoft-print-to-pdf-not-working-heres-how-to-fix-it-in-windows-10-and-11/"><u>Microsoft Print-to-PDF Not Working? Here's How to Fix It in Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-system-performance-by-controlling-svchostexe-netsvcs-network-activity-expert-solutions/"><u>Optimizing System Performance by Controlling Svchost.exe (NETsvcs) Network Activity: Expert Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-activating-bluetooth-on-windows-7-operating-system/"><u>Quick Fix: Activating Bluetooth on Windows 7 Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-resolving-silent-streams-on-netflix/"><u>Simple Solutions: Resolving Silent Streams on Netflix</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-non-responsive-audio-levels-on-windows-10-devices/"><u>Solution Steps for Non-Responsive Audio Levels on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-how-to-resolve-vac-could-not-confirm-your-gaming-activity/"><u>Solution: How to Resolve 'VAC Could Not Confirm Your Gaming Activity'</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-fixing-the-code-0xc0000098-issue-in-windows/"><u>Step-by-Step Solutions for Fixing the 'Code 0xC0000098' Issue in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-address-intel-serial-io-driver-configuration-warning-for-unsupported-hardware-or-operating-system/"><u>Steps to Address Intel Serial IO Driver Configuration Warning for Unsupported Hardware or Operating System</u></a></li>
<li><a href="https://common-error.techidaily.com/the-comprehensive-solution-for-resolving-steams-error-code-80-problems/"><u>The Comprehensive Solution for Resolving Steam's Error Code 80 Problems</u></a></li>
<li><a href="https://some-skills.techidaily.com/transformative-notetaking-the-mematic-way-for-2024/"><u>Transformative Notetaking  The Mematic Way for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-my-mc-lan-connection-issues/"><u>Troubleshooting Guide: Fixing My MC LAN Connection Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-persistent-usb-connection-issues/"><u>Troubleshooting Guide: Resolving Persistent USB Connection Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-windows-error-code-31/"><u>Troubleshooting Guide: Resolving Windows Error Code 31</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-fixes-for-the-troublesome-windows-update-failed-code-0x80244022-explained/"><u>Unraveling Fixes for the Troublesome 'Windows Update Failed' - Code 0X80244022 Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/win10-computers-restart-unpredictably/"><u>Win10 Computers Restart Unpredictably</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-(connector)-10-deactivating-touchpad-with-an-external-mouse-attached/"><u>Windows <Connector> 10: Deactivating Touchpad with an External Mouse Attached</u></a></li>
</ul></div>
