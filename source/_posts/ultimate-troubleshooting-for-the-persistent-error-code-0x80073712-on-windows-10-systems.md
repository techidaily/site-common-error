---
title: Ultimate Troubleshooting for the Persistent Error Code 0X80073712 on Windows 10 Systems
date: 2024-10-24T17:09:05.465Z
updated: 2024-10-30T17:11:43.394Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Ultimate Troubleshooting for the Persistent Error Code 0X80073712 on Windows 10 Systems
excerpt: This Article Describes Ultimate Troubleshooting for the Persistent Error Code 0X80073712 on Windows 10 Systems
thumbnail: https://thmb.techidaily.com/e2a22d0e1eb69e31073b9f86edc15bd17dc9ed7433f25f15297fff8ea322d744.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

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
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902273/19272" target="_top" id="1902273">
  <img src="//a.impactradius-go.com/display-ad/19272-1902273" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902273/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657399/16446" target="_top" id="1657399">
  <img src="//a.impactradius-go.com/display-ad/16446-1657399" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1657399/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105882/7443" target="_top" id="2105882">
  <img src="//a.impactradius-go.com/display-ad/7443-2105882" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105882/7443" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049391/7443" target="_top" id="2049391">
  <img src="//a.impactradius-go.com/display-ad/7443-2049391" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049391/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-swift-tip-extracting-and-storing-twitter-video-on-phone/"><u>[New] 2024 Approved Swift Tip Extracting and Storing Twitter Video on Phone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-dive-into-todays-top-8-viral-video-phenomena/"><u>[New] Dive Into Today’s Top 8 Viral Video Phenomena</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-ultimate-ps4-recording-in-obs-a-detailed-walkthrough/"><u>[New] In 2024, Ultimate PS4 Recording in OBS - A Detailed Walkthrough</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-unleash-music-from-the-cloud-youtube-downloader-tips/"><u>[New] In 2024, Unleash Music From the Cloud YouTube Downloader Tips</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-propel-your-social-impact-with-strategic-facebook-video-ads/"><u>[Updated] Propel Your Social Impact with Strategic Facebook Video Ads</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-which-is-superior-for-screen-recording-obs-studio-or-fraps-in-2024/"><u>[Updated] Which Is Superior for Screen Recording – OBS Studio or Fraps, In 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-lenovo-mouse-pad-malfunctioning-on-windows-1187-step-by-step-guide/"><u>Fix: Lenovo Mouse Pad Malfunctioning on Windows 11/8/7 – Step-by-Step Guide</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/guide-facile-installer-le-logiciel-libdvdcss-dans-handbrake-sous-macoswindows-11-pour-ajouter-des-commentaires-au-video-dvd/"><u>Guide Facile: Installer Le Logiciel Libdvdcss Dans Handbrake Sous macOS/Windows 11 Pour Ajouter Des Commentaires Au Vidéo-DVD</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-unfortunately-contacts-has-stopped-error-on-samsung-galaxy-a54-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Unfortunately, Contacts Has Stopped Error on Samsung Galaxy A54 5G | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-the-elite-compilation-9-online-mic-recorders-ranked/"><u>In 2024, The Elite Compilation 9 Online Mic Recorders Ranked</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-for-the-troublesome-livekernelevent-117-error/"><u>Mastering the Fix for the Troublesome LiveKernelEvent 117 Error</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-battery-woes-discover-how-to-get-your-controller-charging-again/"><u>PS4 Battery Woes? Discover How to Get Your Controller Charging Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-error-writing-failed-to-0x-referenced-memory-location-understanding-fixes/"><u>Resolved Error: Writing Failed to 0X Referenced Memory Location - Understanding Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-extended-semaphore-connection-timed-out-error-error-code-0x80070079/"><u>Resolved: Extended Semaphore Connection Timed Out Error (Error Code 0X80070079)</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-fix-for-windows-11-installation-failure-resolving-error-code-80240020/"><u>Successful Fix for Windows 11 Installation Failure: Resolving Error Code 80240020</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-restoring-visible-bluetooth-devices-in-your-computers-device-manager/"><u>Troubleshooting Steps for Restoring Visible Bluetooth Devices in Your Computer's Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/uncover-how-to-bring-back-gone-desktop-icons-in-windows-10-with-these-steps/"><u>Uncover How to Bring Back Gone Desktop Icons in Windows 10 with These Steps</u></a></li>
</ul></div>

