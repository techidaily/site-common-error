---
title: Troubleshooting and Repairing Fatal Errors in Videos on Windows Devices (Dxgkrnl)
date: 2024-10-07T23:06:21.970Z
updated: 2024-10-12T18:35:29.580Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Repairing Fatal Errors in Videos on Windows Devices (Dxgkrnl)
excerpt: This Article Describes Troubleshooting and Repairing Fatal Errors in Videos on Windows Devices (Dxgkrnl)
thumbnail: https://thmb.techidaily.com/f0f1add4f06bedd9b4441c0d9e38e221d87204ef26ea2cde0e10ae3ca9b9c9f6.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

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
<a href="https://aligracehair.sjv.io/c/5597632/2087262/19272" target="_top" id="2087262">
  <img src="//a.impactradius-go.com/display-ad/19272-2087262" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087262/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2080333/19272" target="_top" id="2080333">
  <img src="//a.impactradius-go.com/display-ad/19272-2080333" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2080333/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-epic-encounters-topping-10-royale-battles/"><u>[Updated] 2024 Approved Epic Encounters Topping 10 Royale Battles</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-toolwiz-app-unveiled-a-critical-examination-of-its-functionality/"><u>[Updated] Toolwiz App Unveiled A Critical Examination of Its Functionality</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-ultimate-guide-to-scrolling-through-engaging-youtube-remarks/"><u>2024 Approved The Ultimate Guide to Scrolling Through Engaging YouTube Remarks</u></a></li>
<li><a href="https://common-error.techidaily.com/adjusting-windows-preferences-under-company-managed-settings-restrictions/"><u>Adjusting Windows Preferences Under Company-Managed Settings Restrictions</u></a></li>
<li><a href="https://fox-helps.techidaily.com/easy-steps-for-srt-files-into-xml-ssa-ttml-for-2024/"><u>Easy Steps for SRT Files Into XML, SSA, TTML for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/end-usb-malfunctions-learn-how-to-resolve-persistent-device-not-recognized-alerts/"><u>End USB Malfunctions! Learn How to Resolve Persistent 'Device Not Recognized' Alerts</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-restart-applications-after-encountering-0xc0-growererror-code/"><u>How to Correctly Restart Applications After Encountering 0xC0 growerError Code</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-cannot-reset-pc-issue-on-windows-10-solution-included/"><u>How to Overcome the Cannot Reset PC Issue on Windows 10 (Solution Included)</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/mastering-script-structuring-for-2024/"><u>Mastering Script Structuring for 2024</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/navigating-twitters-aspect-ratio-policies/"><u>Navigating Twitter's Aspect Ratio Policies</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/1721435409647-reinvigorate-your-iphones-mindfulness-with-these-fixes-to-try/"><u>Reinvigorate Your iPhone's Mindfulness with These Fixes to Try!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-rockstar-games-red-dead-redemption-2-memory-error-by-boosting-page-file/"><u>Resolve Rockstar Games' Red Dead Redemption 2 Memory Error by Boosting Page File</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-puzzling-windows-update-error-code-0x8007001f/"><u>Resolving the Puzzling Windows Update Error Code 0X8007001F</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-when-your-windows-7-cant-grab-those-newest-updates/"><u>Solution Steps for When Your Windows 7 Can't Grab Those Newest Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-chrome-cache-miss-error-errcachemiss-a-step-by-step-guide/"><u>Solving the Chrome Cache Miss Error (ERR_CACHE_MISS): A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/the-way-to-get-back-lost-videos-from-honor-play-8t-by-fonelab-android-recover-video/"><u>The way to get back lost videos from Honor Play 8T</u></a></li>
<li><a href="https://blog-min.techidaily.com/top-free-video-player-supporting-h265-hevc-and-uhd-the-ultimate-choice-for-windows-10-and-mac-in-2020/"><u>Top Free Video Player Supporting H.265 HEVC & UHD: The Ultimate Choice for Windows 10 & Mac in 2020</u></a></li>
<li><a href="https://some-guidance.techidaily.com/transcribe-speaking-to-writing-free-of-charge-for-2024/"><u>Transcribe Speaking to Writing Free of Charge for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-disappeared-desktop-icons-in-windows-10-a-step-by-step-resolution/"><u>Winning the Battle Against Disappeared Desktop Icons in Windows 10 – A Step-by-Step Resolution</u></a></li>
</ul></div>

