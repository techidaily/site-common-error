---
title: "Dealing with the MsMpEng.exe Memory Hog in Windows 11: A Comprehensive Guide"
date: 2024-09-23T16:31:46.127Z
updated: 2024-09-26T20:50:02.700Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Dealing with the MsMpEng.exe Memory Hog in Windows 11: A Comprehensive Guide"
excerpt: "This Article Describes Dealing with the MsMpEng.exe Memory Hog in Windows 11: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/373ffad1cf53faed0d680dfb4d0a7667079f49182ce78c94936651febf489146.jpg
---

## Fixing Error 1068 in Windows: A Comprehensive Guide - SOLUTION FOUND

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
<a href="https://aligracehair.sjv.io/c/5597632/1918719/19272" target="_top" id="1918719">
  <img src="//a.impactradius-go.com/display-ad/19272-1918719" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918719/19272" style="position:absolute;visibility:hidden;" border="0" />
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

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943750/22993" target="_top" id="1943750">
  <img src="//a.impactradius-go.com/display-ad/22993-1943750" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943750/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130874/7443" target="_top" id="2130874">
  <img src="//a.impactradius-go.com/display-ad/7443-2130874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130874/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-quick-click-quality-4-simple-steps-to-take-a-chromebook-screenshot/"><u>[New] In 2024, Quick Click Quality 4 Simple Steps to Take a Chromebook Screenshot</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-channel-charm-with-cost-free-visual-aids-for-2024/"><u>[Updated] Channel Charm with Cost-Free Visual Aids for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-budget-friendly-camera-guide-best-bargains/"><u>[Updated] In 2024, Budget-Friendly Camera Guide Best Bargains</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-harmonized-high-res-overlays-for-devices/"><u>2024 Approved Harmonized High-Res Overlays for Devices</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-navigating-facebook-live-your-2023-playbook/"><u>2024 Approved Navigating Facebook Live Your 2023 Playbook</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-error-code-0x80004005-a-comprehensive-solution-to-the-undefined-issue-in-email-clients/"><u>Dealing with 'Error Code 0X80004005': A Comprehensive Solution to the Undefined Issue in Email Clients</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-overcoming-the-absence-of-an-audio-device-on-your-windows-computer-system/"><u>Expert Tips for Overcoming the Absence of an Audio Device on Your Windows Computer System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-audio-functionality-when-windows-10-fails/"><u>Expert Tips for Restoring Audio Functionality When Windows 10 Fails</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-issues-when-the-diagnostics-policy-service-wont-start/"><u>Fixing Issues When the Diagnostics Policy Service Won't Start</u></a></li>
<li><a href="https://tech-revival.techidaily.com/generative-ai-tool-or-trap-for-disinformation/"><u>Generative AI: Tool or Trap for Disinformation?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-problematic-windows-11-update-1607-installation-failures/"><u>How to Resolve Problematic Windows 11 Update 1607 Installation Failures</u></a></li>
<li><a href="https://vp-tips.techidaily.com/in-2024-discover-top-notch-online-rhythm-analyzers-for-free/"><u>In 2024, Discover Top-Notch Online Rhythm Analyzers for Free</u></a></li>
<li><a href="https://techidaily.com/repair-video-tool-repair-all-your-damaged-video-files-of-honor-play-40c-on-windows-by-stellar-video-repair-mobile-video-repair/"><u>Repair Video Tool - Repair all your damaged video files of Honor Play 40C on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-excessive-cpu-consumption-by-windows-audio-hardware-acceleration/"><u>Resolve Excessive CPU Consumption by Windows Audio Hardware Acceleration</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-windows-10-device-connection-casting-errors-efficiently/"><u>Solving Your Windows 10 Device Connection Casting Errors Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/unblocked-horizons-wow-breaks-free-from-3d-restrictions/"><u>Unblocked Horizons: WoW Breaks Free From 3D Restrictions</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/unpacking-the-pros-and-cons-of-modest-might-and-luxury-touches-on-the-google-pixel-5/"><u>Unpacking the Pros and Cons of Modest Might and Luxury Touches on the Google Pixel 5</u></a></li>
</ul></div>

