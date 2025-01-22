---
title: How to Fix The RPC Server Is Unavailable Error in Windows
date: 2025-01-18T16:19:26.916Z
updated: 2025-01-22T19:28:35.336Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gOyLy8DeizY?si=GkAmK0hChZw6_2tW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 1: Fix DCOM(**Distributed Component Object Model)** errors

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LlVkEwpjKKo?si=hXi-mchMaJvbnIzM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` 2) Type **dcomcnfg**  and press Enter to open **Component Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-19.png)

``

``

`` 2) Go to **Component Services**  \> **Computers**  \> **My Computer**  on the Component Services window. Then double-click on **DCOM Config** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vFQCEZiYA08?si=xjIu5IAy77RlHWii" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

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
<li><a href="https://youtube-help.techidaily.com/new-simplify-your-youtube-presence-with-flawless-shorts-thumbnails/"><u>[New] Simplify Your YouTube Presence with Flawless Shorts Thumbnails</u></a></li>
<li><a href="https://extra-resources.techidaily.com/updated-cartoonhub-complete-guide-and-assessment-2024/"><u>[Updated] CartoonHub Complete Guide & Assessment 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-innovative-approaches-to-modify-user-numbers-in-tiktok/"><u>2024 Approved Innovative Approaches to Modify User Numbers in TikTok</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/approved-leverage-seo-power-secrets-of-effective-youtube-backlink-building/"><u>2024 Approved Leverage SEO Power Secrets of Effective YouTube Backlink Building</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-streamlining-movie-color-correction-through-luts-application/"><u>2024 Approved Streamlining Movie Color Correction Through Luts Application</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-initialization-errors-for-windows-10-system-settings/"><u>Diagnosing and Repairing Initialization Errors for Windows 10 System Settings</u></a></li>
<li><a href="https://android-frp.techidaily.com/easy-guide-to-motorola-edge-40-frp-bypass-with-best-methods-by-drfone-android/"><u>Easy Guide to Motorola Edge 40 FRP Bypass With Best Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-windows-update-error-0x80070652/"><u>Easy to Fix Windows Update Error 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-critical-issue-0x8024200d-during-windows-update-process-complete/"><u>Effective Fixes for Critical Issue 0X8024200d During Windows Update Process [COMPLETE]</u></a></li>
<li><a href="https://facebook.techidaily.com/how-to-approach-minor-user-behavior-on-web-platforms/"><u>How to Approach Minor User Behavior on Web Platforms</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fake-gps-on-motorola-moto-g34-5g-for-mobile-legends-drfone-by-drfone-virtual-android/"><u>How To Fake GPS On Motorola Moto G34 5G For Mobile Legends? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-device-not-detected-problem-fixing-error-code-24-on-windows-os/"><u>How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-obstacles-a-fixed-nvidia-error/"><u>Overcoming Obstacles: A Fixed NVIDIA Error</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-endless-windows-update-progress-at-100/"><u>Resolved: Troubleshooting Endless Windows Update Progress at 100%</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-folder-navigation-in-windows-10-easy-tips-for-using-file-explorer/"><u>Seamless Folder Navigation in Windows 10 - Easy Tips for Using File Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-steam-api-dll-errors/"><u>Solutions for Steam API DLL Errors</u></a></li>
<li><a href="https://extra-support.techidaily.com/the-samsung-galaxy-a20-unveiled-staying-competitive-in-the-budget-android-market/"><u>The Samsung Galaxy A20 Unveiled: Staying Competitive in the Budget Android Market</u></a></li>
<li><a href="https://win11-tips.techidaily.com/the-ultimate-guide-to-stopping-unwanted-disk-filling/"><u>The Ultimate Guide to Stopping Unwanted Disk Filling</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-complete-battleye-installation-now-running-smoothly/"><u>Troubleshooting Complete: BattlEye Installation Now Running Smoothly</u></a></li>
</ul></div>

