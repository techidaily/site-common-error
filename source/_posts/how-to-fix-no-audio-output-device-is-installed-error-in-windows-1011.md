---
title: How to Fix “No Audio Output Device Is Installed” Error in Windows 10/11
date: 2025-01-25T21:21:50.952Z
updated: 2025-01-30T02:18:38.529Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix “No Audio Output Device Is Installed” Error in Windows 10/11
excerpt: This Article Describes How to Fix “No Audio Output Device Is Installed” Error in Windows 10/11
thumbnail: https://thmb.techidaily.com/e28897e8d930e3677167fd762a9f129952956dbe6cf005a7a223376477485be0.jpg
---

## How to Fix 'Class Not Registered' Errors on Windows 11 – Solved

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/jf0JvOqiAXc?si=kHEHQGC_PhBv4xij" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 3) Then a few DCOM Configuration warning messages will pop up. Click **Yes**  for each one.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-18.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

``

``

`` 3) Open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 3: Start the Internet Explorer ETW Collector Service

``

 1) On your keyboard, press the **Windows** **logo key** ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png) +**R** key at the same time to invoke the run command.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) Type **services.msc**  in the box and press**Enter** to open**Windows Services** .

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-3.jpg)

``

``
 3) Find and right-click on **Internet** **Explorer ETW Collector Service** . Then click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/UCqHbpxQGP4?si=XGkajFHdqyoKNAFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-approaches.techidaily.com/new-quick-tips-altering-video-pace-in-instagram-stories/"><u>[New] Quick Tips Altering Video Pace in Instagram Stories</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-2024-approved-explore-free-youtube-pic-themes/"><u>[Updated] 2024 Approved Explore Free YouTube Pic Themes</u></a></li>
<li><a href="https://buynow-info.techidaily.com/comprehensive-guide-to-the-samsung-galaxy-watch-active-the-ultimate-health-and-fitness-companion/"><u>Comprehensive Guide to the Samsung Galaxy Watch Active - The Ultimate Health & Fitness Companion</u></a></li>
<li><a href="https://common-error.techidaily.com/correct-the-youtube-audio-player-bug-in-windows-11-with-these-easy-fixes/"><u>Correct the Youtube Audio Player Bug in Windows 11 with These Easy Fixes</u></a></li>
<li><a href="https://fox-http.techidaily.com/highest-quality-ai-voice-to-text-software-for-2024/"><u>Highest Quality AI Voice to Text Software for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-internet-explorer-performance-after-unexpected-crashes/"><u>How To Restore Internet Explorer Performance After Unexpected Crashes</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/in-2024-shh-9-secrets-of-simple-stock-editing/"><u>In 2024, Shh! 9 Secrets of Simple Stock Editing</u></a></li>
<li><a href="https://some-tips.techidaily.com/line-of-business-insights-overcoming-logistics-hurdles-by-mirroring-staff-knowledge/"><u>Line-of-Business Insights: Overcoming Logistics Hurdles by Mirroring Staff Knowledge</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-resolution-of-werfaultexe-issues-a-guide-with-6-proven-fixes-for-windows-users/"><u>Mastering the Resolution of werFault.exe Issues: A Guide with 6 Proven Fixes for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/optimized-wdf-implementation-minimizes-cpu-usage-spikes/"><u>Optimized WDF Implementation Minimizes CPU Usage Spikes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-the-audio-device-graph-isolation-causing-high-cpu-load-on-windows/"><u>Resolve the 'Audio Device Graph Isolation' Causing High CPU Load on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209853626-silent-streets-no-more-eliminating-sound-problems-in-forza-horizon-4-with-ease/"><u>Silent Streets No More: Eliminating Sound Problems in Forza Horizon 4 with Ease!</u></a></li>
<li><a href="https://techtrends.techidaily.com/top-rated-water-resistant-wearables-comprehensive-reviews-by-tech-experts/"><u>Top-Rated Water Resistant Wearables : Comprehensive Reviews by Tech Experts</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-the-continuous-reboot-cycle-on-windows-11/"><u>Ultimate Guide: Resolving the Continuous Reboot Cycle on Windows 11</u></a></li>
</ul></div>

