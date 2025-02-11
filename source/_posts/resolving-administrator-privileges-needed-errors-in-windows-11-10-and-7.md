---
title: Resolving 'Administrator Privileges Needed' Errors in Windows 11, 10 & 7
date: 2025-02-03T17:10:04.482Z
updated: 2025-02-10T18:07:07.553Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving 'Administrator Privileges Needed' Errors in Windows 11, 10 & 7
excerpt: This Article Describes Resolving 'Administrator Privileges Needed' Errors in Windows 11, 10 & 7
thumbnail: https://thmb.techidaily.com/b57bdcbb41c7763c82190be25c28d361f666df5033d9cd0a341320bf7b8e56fa.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2Iv3DjT2Fyw?si=pR_z8ZDDVGF2MvKJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/odDOPrPjRYY?si=7QHzdUkTPNkHJiVj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 2) Type **regsvr32 ExplorerFrame.dll**  in the command prompt window and press **Enter**  to run it.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vfq0vw0Spz8?si=2EAk6hW-Gb-o33_L" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YfEPmG_O6F8?si=93ZTVtH_zjFRz5eh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-tips.techidaily.com/024-approved-aces-top-10-list-choosing-superior-capture-cards/"><u>[New] 2024 Approved Ace's Top 10 List Choosing Superior Capture Cards</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-shifting-paradigms-non-youtube-video-hosts-for-2024/"><u>[Updated] Shifting Paradigms Non-Youtube Video Hosts for 2024</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/updated-the-essential-iphones-guide-to-great-night-images-for-2024/"><u>[Updated] The Essential iPhones Guide to Great Night Images for 2024</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/boost-your-home-connectivity-a-comprehensive-review-of-the-amplifi-hd-mesh-router-array/"><u>Boost Your Home Connectivity: A Comprehensive Review of the Amplifi HD Mesh Router Array</u></a></li>
<li><a href="https://fox-triigers.techidaily.com/discovering-windows-10s-underlying-issues-with-the-powerful-tool-system-file-checker-and-its-revelations-on-tech-anomalies/"><u>Discovering Windows 10'S Underlying Issues with the Powerful Tool: System File Checker and Its Revelations on Tech Anomalies</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-screen-tearing-in-valorant-a-step-by-step-guide/"><u>Fix Screen Tearing in Valorant: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-troublesome-error-code-0x8024eb3f6-in-windows-11-updates-effortlessly/"><u>Fixing the Troublesome Error Code 0X8024eb3f6 in Windows 11 Updates Effortlessly!</u></a></li>
<li><a href="https://common-error.techidaily.com/forgotten-sd-cards-reclaim-and-repair-them/"><u>Forgotten SD Cards? Reclaim & Repair Them</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-unlock-professional-video-quality-with-top-youtube-to-webm-tools/"><u>In 2024, Unlock Professional Video Quality with Top YouTube-to-WebM Tools</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/inversion-workshop-for-2024/"><u>Inversion Workshop for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/1726030598880-mp3/"><u>MP3形式の容量削減法 - ファイルサイズを小さくし、データストレージを節約するテクニック</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203532007-quick-fix-tips-for-the-bluetooth-not-available-error-on-windows-11-computers/"><u>Quick-Fix Tips for the 'Bluetooth Not Available' Error on Windows 11 Computers.</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-ps4-connection-woes-with-this-detailed-nat-configuration-walkthrough/"><u>Resolve PS4 Connection Woes with This Detailed NAT Configuration Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-fixing-the-chrome-not-responding-issue-reload-browser/"><u>Resolve: Fixing the 'Chrome Not Responding' Issue - Reload Browser?</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-driverpowerstatefailure-problem-a-step-by-step-guide/"><u>Solving the DRIVER_POWER_STATE_FAILURE Problem: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-persistent-problem-how-to-stop-your-mouse-from-constant-disconnection/"><u>Solving the Persistent Problem: How to Stop Your Mouse From Constant Disconnection</u></a></li>
<li><a href="https://discover-great.techidaily.com/1728510318004-windows-10-11/"><u>Windows 格式化分区捡回方法：解决详解 10 到 11版本，无需付钱</u></a></li>
</ul></div>

