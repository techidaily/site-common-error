---
title: How to Fix The RPC Server Is Unavailable Error in Windows
date: 2024-11-18T02:51:43.231Z
updated: 2024-11-24T21:54:56.301Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JNxZ4Z6BVCg?si=522oz1OPSQDhNYWT&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/TJCye_oCTTw?si=6bVyBphcSgSFdyuq&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/On0Jw2oMZf0?si=Pm-FJoEt8XWmtMbr&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-http.techidaily.com/new-2024-approved-all-about-triller-diverging-from-standard-tiktok-experience/"><u>[New] 2024 Approved All About Triller Diverging From Standard TikTok Experience</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-elevate-your-social-impact-with-these-hashtags/"><u>[New] 2024 Approved Elevate Your Social Impact with These Hashtags</u></a></li>
<li><a href="https://article-helps.techidaily.com/new-2024-approved-precision-editing-in-photopea-sculpting-cleaner-visual-space/"><u>[New] 2024 Approved Precision Editing in Photopea Sculpting Cleaner Visual Space</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/new-in-2024-troubleshooting-excessive-obs-bitrate/"><u>[New] In 2024, Troubleshooting Excessive OBS Bitrate</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-expert-advice-on-youtube-short-pitfalls/"><u>[Updated] Expert Advice on YouTube Short Pitfalls</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-best-of-the-best-ultimate-list-of-gopro-casings/"><u>[Updated] In 2024, Best of the Best Ultimate List of GoPro Casings</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-top-20-youtube-friendly-facebook-video-editors-for-2024/"><u>[Updated] Top 20 YouTube-Friendly Facebook Video Editors for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/address-the-no-speakers-problem-fixes-for-windows-11-sound-issues/"><u>Address the No Speakers Problem - Fixes for Windows 11 Sound Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/age-of-empires-3-startup-errors-overcoming-initialization-failure-effortlessly/"><u>Age of Empires 3 Startup Errors: Overcoming Initialization Failure Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-non-updating-windows-11-systems/"><u>Effective Fixes for Non-Updating Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-overwatch-voice-communication-problems-quickly-and-effectively/"><u>Fix Overwatch Voice Communication Problems Quickly and Effectively</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/hitachis-ultra-hd-mastery-premium-4k-smart-tvs-powered-by-built-in-roku-streaming-features/"><u>Hitachi's Ultra HD Mastery: Premium 4K Smart TVs Powered by Built-In Roku Streaming Features</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-a-device-management-error-28-code-in-your-windows-system/"><u>How to Overcome a Device Management 'Error 28' Code in Your Windows System</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-your-bluetooth-connectivity-problems-in-windows-10-ultimate-fixes/"><u>How to Resolve Your Bluetooth Connectivity Problems in Windows 10 - Ultimate Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-unresponsive-devices-hooked-up-to-mainframe-resolution-achieved/"><u>Overcoming Issues with Unresponsive Devices Hooked Up to Mainframe [Resolution Achieved]</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-device-cast-errors-in-windows-11-expert-advice-and-fixes/"><u>Resolving Device Cast Errors in Windows 11: Expert Advice & Fixes</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/by-step-save-youtube-sounds-directly-for-2024/"><u>Step-by-Step Save YouTube Sounds Directly for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/top-credit-cards-perfect-for-beginner-spenders-expert-reviews/"><u>Top Credit Cards Perfect for Beginner Spenders | Expert Reviews</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-the-mystery-of-the-windows-error-code-0xc00000e9/"><u>Ultimate Guide: Solving the Mystery of the Windows Error Code 0xC00000E9</u></a></li>
</ul></div>

