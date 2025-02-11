---
title: How to Fix The RPC Server Is Unavailable Error in Windows
date: 2025-02-04T20:04:49.245Z
updated: 2025-02-10T18:30:21.467Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_1g4U13PBk0?si=xJLJtlc4hKBTBH8M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Open the app again to see if it goes fine.

``

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/j5gTm5KxtQ0?si=onF1rBS2nEM5nLGg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-capture.techidaily.com/new-2024-approved-the-comprehensible-guide-to-wincams-bests/"><u>[New] 2024 Approved The Comprehensible Guide to WinCams' Bests</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-economical-videography-for-extreme-sports-enthusiasts/"><u>[New] Economical Videography for Extreme Sports Enthusiasts</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-mastering-canva-10-best-practices-unveiled/"><u>[New] In 2024, Mastering Canva 10 Best Practices Unveiled</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-chromium-device-live-screen-recorder/"><u>[Updated] In 2024, Chromium Device Live Screen Recorder</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-in-2024-mastery-over-mobile-and-desktop-recording-team-discussions/"><u>[Updated] In 2024, Mastery Over Mobile & Desktop Recording Team Discussions</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-avoid-lag-and-enhance-engagement-mastering-xboxs-zooming-features/"><u>2024 Approved Avoid Lag & Enhance Engagement Mastering Xbox's Zooming Features</u></a></li>
<li><a href="https://some-tips.techidaily.com/2024-approved-the-power-of-persuasion-exploring-6-video-genres/"><u>2024 Approved The Power of Persuasion Exploring 6 Video Genres</u></a></li>
<li><a href="https://extra-tips.techidaily.com/best-webcams-for-zoom/"><u>Best Webcams for Zoom</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204366949-fix-windows-11s-bluetooth-connection-problems-with-these-simple-steps/"><u>Fix Windows 11'S Bluetooth Connection Problems with These Simple Steps!</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-apply-spiral-depth-enhancement-to-images-psx/"><u>In 2024, Apply Spiral Depth Enhancement to Images PSX</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-trackpad-malfunctions-in-windows-operating-systems-a-comprehensive-fix-for-win1087/"><u>Laptop TrackPad Malfunctions in Windows Operating Systems: A Comprehensive Fix for Win10/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-for-typing-issues-how-to-reinitialize-your-keyboard-settings/"><u>Quick Fix for Typing Issues: How to Reinitialize Your Keyboard Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-hosted-network-couldnt-be-started-errors-on-windows-10-computers/"><u>Resolving 'Hosted Network Couldn't Be Started' Errors on Windows 10 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-troubleshooting-overcoming-black-ops-n-death-glitches/"><u>Step-by-Step Troubleshooting: Overcoming Black Ops N' Death Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-step-by-step-correcting-error-e80240020-for-successful-windows-10-setup/"><u>Troubleshooting Step-by-Step: Correcting Error E80240020 for Successful Windows 10 Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/unreals-future-tethered-to-d3d-device-availability/"><u>Unreal's Future Tethered to D3D Device Availability</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-invisible-mouse-buttons-in-windows-10-solutions/"><u>Winning the Battle Against Invisible Mouse Buttons in Windows 10 [Solutions]</u></a></li>
</ul></div>

