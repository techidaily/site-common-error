---
title: Mastering Quick Fixes for Windows 11 and #ErrorCode 0X80072F8f
date: 2024-09-09T01:56:21.913Z
updated: 2024-09-15T02:20:46.368Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Mastering Quick Fixes for Windows 11 and #ErrorCode 0X80072F8f
excerpt: This Article Describes Mastering Quick Fixes for Windows 11 and #ErrorCode 0X80072F8f
thumbnail: https://thmb.techidaily.com/abd95b31cf1a96dd50fea72e4fad17faec8b6807eeb04dedcab0ba4e1aebe611.jpg
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

## Fix 4: Set Windows Photo Viewer as a default image viewer

 Note: If Class not registered error occur when you open the photo app, try to set Windows Photo Viewer as a default image viewer to fix the error.

 1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/02/win-key-3.png)**  \+ **I**  key at the same time to open the Windows**Setting** window.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123470/16836" target="_top" id="2123470">
  <img src="//a.impactradius-go.com/display-ad/16836-2123470" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123470/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-jumpstart-with-vrecorder-easy-installation-walkthrough/"><u>[New] Jumpstart with VRecorder Easy Installation Walkthrough</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-bridging-social-media-posting-tweets-on-fb/"><u>[Updated] In 2024, Bridging Social Media Posting Tweets on FB</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-unleash-creative-fb-ad-videos-access-free-video-tools-now-for-2024/"><u>[Updated] Unleash Creative FB Ad Videos - Access FREE Video Tools Now for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-understanding-the-mechanics-of-vsdc-vs-leading-alternatives/"><u>2024 Approved Understanding the Mechanics of VSDC vs Leading Alternatives</u></a></li>
<li><a href="https://tech-hub.techidaily.com/avoiding-the-traps-how-students-can-ethically-leverage-cheatgpt-for-academic-success/"><u>Avoiding the Traps: How Students Can Ethically Leverage CheatGPT for Academic Success</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-advance-explored-in-metasig-space/"><u>ChatGPT Advance Explored in Metasig Space</u></a></li>
<li><a href="https://common-error.techidaily.com/ensured-interoperability-with-updated-htc-tactile-screens/"><u>Ensured Interoperability with Updated HTC Tactile Screens</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-realme-c55-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Realme C55 | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/fixing-the-mystery-of-not-found-in-windows-pc/"><u>Fixing the Mystery of 'Not Found' In Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-resource-protection-could-not-complete-task-on-pcs/"><u>How to Repair 'Resource Protection Could Not Complete Task' On PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-solve-when-your-steelseries-arctis-mic-isnt-functioning-correctly/"><u>How To Solve When Your SteelSeries Arctis ([Mic]) Isn't Functioning Correctly</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209785652-troubleshooting-non-functional-usb-ports-on-windows-10-and-11/"><u>Troubleshooting Non-Functional USB Ports on Windows 10 & 11</u></a></li>
</ul></div>
