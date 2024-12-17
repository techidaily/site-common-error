---
title: How to Fix 'Failed to Enumerate Objects' Error During Windows 11 Installation – A Comprehensive Guide
date: 2024-12-15T16:27:14.340Z
updated: 2024-12-16T19:35:15.474Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix 'Failed to Enumerate Objects' Error During Windows 11 Installation – A Comprehensive Guide
excerpt: This Article Describes How to Fix 'Failed to Enumerate Objects' Error During Windows 11 Installation – A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/66f3cf36e141a02ee3ef4f8fc90997bfb9adc390279a16b539b7e76e0dc798e2.jpg
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

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

``

``

`` 4) Reboot your Windows 10 and open the app again to see if it goes fine.

``

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 2: Re-register the ExplorerFrame.dll file

``

`
` ``

 1) Press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  +**X** key together, then click**Command Prompt(Admin)** .

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`` Click **Yes**  when prompted by User Account Control.

``

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-17.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6nvb0775GOM?si=peBB_Mo_4zcZFuci" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://youtube-web.techidaily.com/024-approved-techniques-to-improve-video-visibility-on-youtube-platform/"><u>[New] 2024 Approved Techniques to Improve Video Visibility on YouTube Platform</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-effortless-playlist-pivot-the-top-5-spotify-to-youtube-tools-for-2024/"><u>[Updated] Effortless Playlist Pivot The Top 5 Spotify-to-YouTube Tools for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/data-error-resolution-understanding-cyclic-redundancy-check-fixes/"><u>Data Error Resolution: Understanding Cyclic Redundancy Check Fixes</u></a></li>
<li><a href="https://facebook.techidaily.com/decrypting-the-codex-to-oversee-metas-account-central-hub/"><u>Decrypting the Codex to Oversee Meta’s Account Central Hub</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-for-the-d3derr-not-available-problem-in-windows-computers/"><u>Easy Solutions for the 'D3DERR Not Available' Problem in Windows Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/end-of-the-road-for-error-5-has-occurred-quick-fixes-on-modern-and-legacy-windows-os/"><u>End of the Road for 'Error 5 Has Occurred': Quick Fixes on Modern and Legacy Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-and-solutions-overcoming-issues-during-steam-game-installation-or-updates/"><u>Fixes and Solutions: Overcoming Issues During Steam Game Installation or Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-endless-wait-resolve-bethesdas-skyrim-unlimited-load-times/"><u>Fixing the Endless Wait: Resolve Bethesda's Skyrim Unlimited Load Times</u></a></li>
<li><a href="https://article-posts.techidaily.com/gratuitous-green-backdrops-available-for-2024/"><u>Gratuitous Green Backdrops Available for 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-gionee-f3-pro-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Gionee F3 Pro Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-infinix-smart-8-hd-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Infinix Smart 8 HD to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-fix-auto-lock-greyed-out-on-apple-iphone-12-pro-max-drfone-by-drfone-ios/"><u>In 2024, How To Fix Auto Lock Greyed Out on Apple iPhone 12 Pro Max | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/movie-magic-for-video-editing-enthusiasts-for-2024/"><u>Movie Magic for Video Editing Enthusiasts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-file-explorer-unresponsiveness-on-windows-11-with-easy-fixes/"><u>Overcoming File Explorer Unresponsiveness on Windows 11 with Easy Fixes</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/hythm-revivers-guide-to-distorted-beats/"><u>The Rhythm Reviver's Guide to Distorted Beats</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unavailable-desktop-issue-within-windows-system-profile-configuration/"><u>Troubleshooting Unavailable Desktop Issue Within Windows System Profile Configuration</u></a></li>
</ul></div>

