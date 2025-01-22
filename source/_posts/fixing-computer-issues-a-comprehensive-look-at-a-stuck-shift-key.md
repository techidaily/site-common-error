---
title: "Fixing Computer Issues: A Comprehensive Look at a Stuck Shift Key"
date: 2025-01-18T16:11:47.390Z
updated: 2025-01-22T20:41:46.593Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Computer Issues: A Comprehensive Look at a Stuck Shift Key"
excerpt: "This Article Describes Fixing Computer Issues: A Comprehensive Look at a Stuck Shift Key"
thumbnail: https://thmb.techidaily.com/95080ee1192e9ec99602ccecb30de670936b2e86c3bafe48586480f26bd563d2.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-0Ww1YIIUe4?si=cQ-Gkh9UCJABuPZU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iPCr_bxZjMQ?si=ubOsoq5umPEXL9xL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-quick-start-recording-audio-on-windows-11/"><u>[New] In 2024, Quick Start Recording Audio on Windows 11</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-in-2024-tweeting-visual-stories-from-vids-to-interactive-gifs/"><u>[Updated] In 2024, Tweeting Visual Stories From Vids to Interactive GIFs</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-integrated-guide-for-mobile-and-pc-session-records/"><u>[Updated] Integrated Guide for Mobile & PC Session Records</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-navigating-complex-editing-a-practical-guide-for-youtube-video-creators-on-pc-for-2024/"><u>[Updated] Navigating Complex Editing A Practical Guide for YouTube Video Creators on PC for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/2024-approved-expertly-curated-green-screen-gear-list/"><u>2024 Approved Expertly Curated Green Screen Gear List</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-text-artistry-in-ae-our-top-10-recommendations/"><u>2024 Approved Text Artistry in AE Our Top 10 Recommendations</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-step-by-step-instructions-to-fix-a-blank-screen-on-your-monitor/"><u>Expert Advice: Step-by-Step Instructions to Fix a Blank Screen on Your Monitor</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-oppo-reno-9a-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Oppo Reno 9A 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-excessive-cpu-usage-from-iastordatasvc-service-on-windows-10-32-bit-resolved/"><u>How to Fix Excessive CPU Usage From IAStorDataSvc Service on Windows 10 (32 Bit) [Resolved]</u></a></li>
<li><a href="https://program-issues.techidaily.com/resolving-your-issue-with-crossbow-error-code-in-minecraft/"><u>Resolving Your Issue with Crossbow Error Code in Minecraft</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-malfunctioning-keyboard-backlights-on-pcmac-systems/"><u>Step-by-Step Solution for Malfunctioning Keyboard Backlights on PC/Mac Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-tell-if-netflix-isnt-working-and-solutions/"><u>Troubleshooting Guide: How to Tell If Netflix Isn't Working and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-your-disconnected-printer-resolving-error-code-30-successfully/"><u>Troubleshooting Your Disconnected Printer: Resolving Error Code -30 Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/winkernel-power-failure-error-41-fixed/"><u>WinKernel Power Failure: Error #41 Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/wwe-2k-battlegrounds-correcting-the-direct-x-version-10-error-for-optimal-performance/"><u>WWE 2K Battlegrounds: Correcting the Direct X Version 10 Error for Optimal Performance</u></a></li>
</ul></div>

