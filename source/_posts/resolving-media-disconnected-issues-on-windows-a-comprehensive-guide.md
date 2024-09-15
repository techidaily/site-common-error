---
title: Resolving 'Media Disconnected' Issues on Windows - A Comprehensive Guide
date: 2024-09-11T07:11:53.716Z
updated: 2024-09-15T00:34:16.990Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving 'Media Disconnected' Issues on Windows - A Comprehensive Guide
excerpt: This Article Describes Resolving 'Media Disconnected' Issues on Windows - A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/dd50570496ecd6117c25174ee2bd7c391f8d8aee122e4f4fcf28370737609fdc.jpg
---

## Resolving Unregistered Class Errors on Your Windows 10 PC - Solutions Inside

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

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130529/26400" target="_top" id="2130529">
  <img src="//a.impactradius-go.com/display-ad/26400-2130529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130529/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

``

 2) Click **System** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8-12.png)

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
<li><a href="https://vp-tips.techidaily.com/updated-2024-approved-strategies-to-alleviate-vr-motion-woes/"><u>[Updated] 2024 Approved Strategies to Alleviate VR Motion Woes</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-in-2024-the-ps3-game-viewers-guide-filming-your-playtime/"><u>[Updated] In 2024, The PS3 Game Viewer's Guide Filming Your Playtime</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-understanding-limits-to-instagram-videography/"><u>2024 Approved Understanding Limits to Instagram Videography</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-tecno-phantom-v-flip-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Tecno Phantom V Flip | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-fix-ethernet-problems-on-your-windows-11-or-windows-7-computer/"><u>How to Diagnose & Fix Ethernet Problems on Your Windows 11 or Windows 7 Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-audio-functionality-when-windows-1n-detects-no-output-device-installed/"><u>How to Restore Audio Functionality When Windows 1N Detects No Output Device Installed</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-outro-crafting-made-easy-the-best-free-guide-top-6/"><u>In 2024, Outro Crafting Made Easy - The Best Free Guide (Top 6)</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-touch-control-on-your-laptop-or-desktop-essential-repair-tips-for-windows-11-enthusiasts/"><u>Mastering Touch Control on Your Laptop or Desktop - Essential Repair Tips for Windows 11 Enthusiasts</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-excessive-noise-in-playstation-4-consoles-tips-and-tricks/"><u>Resolving Excessive Noise in PlayStation 4 Consoles - Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-function-key-malfunction-on-your-dell-pc-a-step-by-step-guide/"><u>Solving the Function-Key Malfunction on Your Dell PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/speed-up-your-keys-effective-methods-to-fix-laggy-keyboard-performance/"><u>Speed Up Your Keys: Effective Methods to Fix Laggy Keyboard Performance</u></a></li>
<li><a href="https://discover-docs.techidaily.com/step-by-step-process-of-transforming-epub-ebooks-to-plain-text-without-cost/"><u>Step-by-Step Process of Transforming EPUB eBooks to Plain Text Without Cost</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-restoring-right-click-functionality-in-windows-11-pcs/"><u>Step-by-Step Solution: Restoring Right-Click Functionality in Windows 11 PCs</u></a></li>
<li><a href="https://win-amazing.techidaily.com/step-by-step-tutorial-for-installing-new-drivers-on-asus-portable-computers/"><u>Step-by-Step Tutorial for Installing New Drivers on ASUS Portable Computers</u></a></li>
<li><a href="https://program-issues.techidaily.com/troubleshooting-guide-preventing-f1-2020-from-crashing-on-your-computer/"><u>Troubleshooting Guide: Preventing F1 2020 From Crashing on Your Computer</u></a></li>
</ul></div>

