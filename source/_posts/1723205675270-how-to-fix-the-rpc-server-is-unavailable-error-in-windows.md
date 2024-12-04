---
title: How to Fix The RPC Server Is Unavailable Error in Windows
date: 2024-11-29T06:32:06.816Z
updated: 2024-12-04T03:54:38.068Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix The RPC Server Is Unavailable Error in Windows
excerpt: This Article Describes How to Fix The RPC Server Is Unavailable Error in Windows
thumbnail: https://thmb.techidaily.com/d1f3ab1e0f303254b5da0d1c46b4cd5df7801fb77b72cd0a87c2f6333bdfc5bd.jpg
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

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/QPAKth3O_5c?si=M69YSY0Mk_gsdU0Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/May-pLCUkEA?si=PGlcFZAlsp3S3beI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-speedy-engagement-the-how-to-for-video-speed-in-stories/"><u>[New] In 2024, Speedy Engagement The How-To for Video Speed in Stories</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/new-stylish-shots-top-trending-instagram-filters-for-2024/"><u>[New] Stylish Shots Top Trending Instagram Filters for 2024</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-tiny-feature-plot-outline/"><u>[New] Tiny Feature Plot Outline</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-how-to-combat-sync-issues-between-cameras-and-obs/"><u>[Updated] How to Combat Sync Issues Between Cameras and OBS</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solution-for-dealing-with-failed-attempts-at-accessing-a-remote-server/"><u>Comprehensive Solution for Dealing With Failed Attempts at Accessing a Remote Server</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-strategies-to-overcome-recurring-freezing-errors-on-windows-or-mac-systems/"><u>Comprehensive Strategies to Overcome Recurring Freezing Errors on Windows or Mac Systems</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/earths-richest-digital-content-wizard-for-2024/"><u>Earth's Richest Digital Content Wizard for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-repairing-error-0x802n4401c-that-hampers-update-process-on-windows-10-and-11-machines/"><u>Expert Advice for Repairing Error 0X802n4401C That Hampers Update Process on Windows 10 & 11 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-repairing-a-broken-internet-explorer-connection/"><u>Expert Tips for Repairing a Broken Internet Explorer Connection</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-fix-the-system-call-failed-error-on-windows-10-and-11/"><u>How to Fix the “System Call Failed” Error on Windows 10 & 11</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-elevate-videography-the-right-aspect-ratio-knowledge/"><u>In 2024, Elevate Videography The Right Aspect Ratio Knowledge</u></a></li>
<li><a href="https://win-solutions.techidaily.com/mastering-steamvr-overcoming-the-challenge-of-error-3-to-ensure-a-seamless-vr-experience/"><u>Mastering SteamVR: Overcoming the Challenge of Error 3 to Ensure a Seamless VR Experience.</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-the-non-working-print-screen-button-on-pcs-with-windows-10-or-11/"><u>Step-by-Step Solutions for the Non-Working Print Screen Button on PCs with Windows 10 or 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-making-bluetooth-appear-in-your-computers-device-manager/"><u>Troubleshooting Tips for Making Bluetooth Appear in Your Computer's Device Manager</u></a></li>
<li><a href="https://extra-resources.techidaily.com/vlc-player-insider-top-10-underrated-functions/"><u>VLC Player Insider Top 10 Underrated Functions</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-11-keyboard-lag-effective-fixes-revealed/"><u>Winning Against Window's 11 Keyboard Lag - Effective Fixes Revealed</u></a></li>
</ul></div>

