---
title: Troubleshooting the 0X80240034 Glitch in Windows 11 Updates – Effective Strategies for Success
date: 2024-09-09T08:59:28.952Z
updated: 2024-09-10T08:59:28.952Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting the 0X80240034 Glitch in Windows 11 Updates – Effective Strategies for Success
excerpt: This Article Describes Troubleshooting the 0X80240034 Glitch in Windows 11 Updates – Effective Strategies for Success
thumbnail: https://thmb.techidaily.com/97d650cd0f6e07d2facd0c86f96f609a10afc326cf6eb9f144fb267795cd5a9a.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118318/7443" target="_top" id="2118318">
  <img src="//a.impactradius-go.com/display-ad/7443-2118318" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118318/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123738/7443" target="_top" id="2123738">
  <img src="//a.impactradius-go.com/display-ad/7443-2123738" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123738/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135366/19272" target="_top" id="2135366">
  <img src="//a.impactradius-go.com/display-ad/19272-2135366" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135366/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137220/26400" target="_top" id="2137220">
  <img src="//a.impactradius-go.com/display-ad/26400-2137220" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137220/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118314/7443" target="_top" id="2118314">
  <img src="//a.impactradius-go.com/display-ad/7443-2118314" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118314/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130889/7443" target="_top" id="2130889">
  <img src="//a.impactradius-go.com/display-ad/7443-2130889" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130889/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130891/7443" target="_top" id="2130891">
  <img src="//a.impactradius-go.com/display-ad/7443-2130891" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130891/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<span id="1912746">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1912746.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20231-1912746">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1912746.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmindmanager.sjv.io%2Fc%2F5597632%2F1912746%2F20231'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1912746/20231" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135358/19272" target="_top" id="2135358">
  <img src="//a.impactradius-go.com/display-ad/19272-2135358" border="0" alt="https://techidaily.com" width="336" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135358/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123733/7443" target="_top" id="2123733">
  <img src="//a.impactradius-go.com/display-ad/7443-2123733" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123733/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-demystifying-youtube-premium-membership-benefits/"><u>[New] 2024 Approved Demystifying YouTube Premium Membership Benefits</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-in-2024-unlocking-potential-in-your-photography-with-gopro-time-lapses/"><u>[New] In 2024, Unlocking Potential in Your Photography with GoPro Time-Lapses</u></a></li>
<li><a href="https://some-guidance.techidaily.com/new-unravel-the-mysteries-of-color-grading-with-cs6cc-luts/"><u>[New] Unravel the Mysteries of Color Grading with CS6/CC LUTs</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-ps4-controller-wont-charge/"><u>[SOLVED] PS4 Controller Won’t Charge</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-a-compreenas-guide-to-choosing-ideal-lenses-for-filmmaking-for-2024/"><u>[Updated] A Compreenas Guide to Choosing Ideal Lenses for Filmmaking for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-in-2024-elevate-your-vimeo-watch-time/"><u>[Updated] In 2024, Elevate Your Vimeo Watch Time</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-virtual-experiences-simplified-insights/"><u>2024 Approved Unveiling Virtual Experiences Simplified Insights</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-google-chromes-black-display-anomaly-effective-solutions-herein/"><u>Addressing Google Chrome's Black Display Anomaly - Effective Solutions Herein</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-high-cpu-load-due-to-iastordatasvc-on-32-bit-windows-10-operating-system-solution-provided/"><u>Addressing High CPU Load Due to IAStorDataSvc on 32-Bit Windows 10 Operating System [Solution Provided]</u></a></li>
<li><a href="https://win-blog.techidaily.com/boost-your-gaming-experience-how-to-tackle-blurry-graphics-issues-in-cod-warzone-on-pc/"><u>Boost Your Gaming Experience: How to Tackle Blurry Graphics Issues in COD: Warzone on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207691717-cracking-the-code-to-successfully-register-classes-on-windows-10-detailed-fixes-revealed/"><u>Cracking the Code to Successfully Register Classes on Windows 10 - Detailed Fixes Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnose-and-repair-ps4-dualshock-not-charging-issues-easily/"><u>Diagnose and Repair PS4 Dualshock Not Charging Issues Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-getting-minecraft-back-running-on-windows-after-launch-problems/"><u>Expert Advice: Getting Minecraft Back Running on Windows After Launch Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-explanation-overcoming-writing-errors-to-assigned-memory-space-x/"><u>Fix Explanation: Overcoming Writing Errors to Assigned Memory Space X</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-windows-11-sign-in-errors-with-easy-solutions-for-the-failed-user-profile-service/"><u>Fix Your Windows 11 Sign-In Errors with Easy Solutions for the Failed User Profile Service</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-faulty-driver-issues-fast-a-comprehensive-tutorial/"><u>Fixing Faulty Driver Issues Fast: A Comprehensive Tutorial</u></a></li>
<li><a href="https://howto.techidaily.com/fixing-persistent-pandora-crashes-on-realme-c67-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fixing Persistent Pandora Crashes on Realme C67 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-input-devices-back-online-a-step-by-step-guide-to-fix-usb-mouse-and-keyboard-issues-on-windows-7-systems/"><u>Getting Your Input Devices Back Online: A Step-by-Step Guide to Fix USB Mouse & Keyboard Issues on Windows 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-non-responsive-google-chrome-browser-reload-and-troubleshooting-tips/"><u>How to Fix a Non-Responsive Google Chrome Browser: Reload and Troubleshooting Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-issues-with-unsuccessful-torrent-downloads/"><u>How to Fix Issues with Unsuccessful Torrent Downloads</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-optimize-your-pc-lower-dwm-gpu-load-on-windows-10-and-11/"><u>How to Optimize Your PC: Lower DWM GPU Load on Windows 10 & 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-a-previously-synced-google-account-from-your-tecno-pova-5-pro-by-drfone-android/"><u>How to Remove a Previously Synced Google Account from Your Tecno Pova 5 Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-non-responsive-bluetooth-mouse-on-pc-a-step-by-step-guide/"><u>How to Repair a Non-Responsive Bluetooth Mouse on PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/incompatible-ftdi-device-drivers-trigger-memory-corruption-alerts/"><u>Incompatible FTDI Device Drivers Trigger Memory Corruption Alerts</u></a></li>
<li><a href="https://hardware-help.techidaily.com/install-ricoh-printer-software-on-windows-step-by-step-tutorials/"><u>Install Ricoh Printer Software on Windows: Step-by-Step Tutorials</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-halo-4-ue4-fix-your-critical-system-failures-for-uninterrupted-playtime/"><u>Mastering Halo 4 UE4: Fix Your Critical System Failures for Uninterrupted Playtime</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-unfreezing-process-effective-ways-to-revive-your-windows-10-taskbar/"><u>Mastering the Unfreezing Process: Effective Ways to Revive Your Windows 10 Taskbar</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-2024-approved-google-plays-top-charts-trending-android-apps/"><u>New 2024 Approved Google Plays Top Charts Trending Android Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/no-more-pdf-print-troubles-effective-remedies-for-immediate-relief/"><u>No More PDF Print Troubles - Effective Remedies for Immediate Relief</u></a></li>
<li><a href="https://common-error.techidaily.com/noise-free-viewing-effective-methods-for-restoring-sound-on-netflix/"><u>Noise-Free Viewing: Effective Methods for Restoring Sound on Netflix</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-dealing-with-the-parameter-is-incorrect-alert/"><u>Quick Fixes for Dealing with the Parameter Is Incorrect Alert</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-why-arent-my-keyboard-numbers-working-and-how-to-fix-them/"><u>Quick Guide: Why Aren't My Keyboard Numbers Working? And How To Fix Them</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-common-causes-and-fixes-for-unresponsive-lenovo-keyboards/"><u>Resolved! Common Causes and Fixes for Unresponsive Lenovo Keyboards</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-blue-screen-a-step-by-step-guide-to-correcting-system-error-code-c00000e9/"><u>Resolving the Blue Screen: A Step-by-Step Guide to Correcting System Error Code C00000e9</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-a-dead-microphone-in-windows-10-best-practices-for-users/"><u>Reviving a Dead Microphone in Windows 10: Best Practices for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/revolutionary-guide-to-eliminating-minecraft-performance-lags/"><u>Revolutionary Guide to Eliminating Minecraft Performance Lags</u></a></li>
<li><a href="https://common-error.techidaily.com/side-by-side-configuration-is-incorrect-error-in-windows-11-fixed/"><u>Side by Side Configuration Is Incorrect Error in Windows 11 [FIXED]</u></a></li>
<li><a href="https://win-solutions.techidaily.com/step-by-step-guide-flushing-the-update-cache-in-windows-1110/"><u>Step-by-Step Guide: Flushing the Update Cache in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/the-definitive-solution-ensuring-seamless-airpods-integration-with-windows-11/"><u>The Definitive Solution : Ensuring Seamless AirPods Integration with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-persistent-computer-hibernation-issues-with-easy-solutions/"><u>Troubleshoot Persistent Computer Hibernation Issues with Easy Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-failed-to-initialize-renderer-issues-in-browsers/"><u>Troubleshooting Guide: Fixing 'Failed to Initialize Renderer' Issues in Browsers</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-notorious-red-screen-of-error-in-your-device/"><u>Ultimate Guide: Resolving the Notorious 'Red Screen of Error' In Your Device</u></a></li>
<li><a href="https://fox-that.techidaily.com/ultimate-solutions-for-resolving-ghost-touch-issues-on-your-iphone-a-step-by-step-guide/"><u>Ultimate Solutions for Resolving Ghost Touch Issues on Your iPhone - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-upgrade-witness-your-devices-accelerated-performance-now/"><u>Ultimate Upgrade: Witness Your Device's Accelerated Performance Now</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpectedly-turned-off-computers-diagnosis-and-repair-techniques/"><u>Unexpectedly Turned Off Computers: Diagnosis and Repair Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/unreal-engine-hangs-in-balance-with-d3d-status/"><u>Unreal Engine Hangs in Balance with D3D Status</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210118723-vcruntime140dll-missing-program-cant-start-on-windows-10-solved/"><u>VCRUNTIME140.dll Missing, Program Can't Start on Windows 10 [Solved]</u></a></li>
</ul></div>
