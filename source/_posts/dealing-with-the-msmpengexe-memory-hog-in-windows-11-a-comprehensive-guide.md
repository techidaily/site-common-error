---
title: "Dealing with the MsMpEng.exe Memory Hog in Windows 11: A Comprehensive Guide"
date: 2024-09-17T16:43:18.914Z
updated: 2024-09-20T16:20:26.806Z
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
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148775/18498" target="_top" id="2148775">
  <img src="//a.impactradius-go.com/display-ad/18498-2148775" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148775/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2006955/19272" target="_top" id="2006955">
  <img src="//a.impactradius-go.com/display-ad/19272-2006955" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006955/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://discover-help.techidaily.com/1726029197553-ismvmp4/"><u>.ismv形式動画をMP4に簡単変換ガイド</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-2024-approved-imageintensifymax7-boosting-pixels-magnificently/"><u>[New] 2024 Approved ImageIntensifyMax7 Boosting Pixels Magnificently</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-the-ultimate-guide-to-the-most-reliable-mac-recorders/"><u>[Updated] In 2024, The Ultimate Guide to the Most Reliable Mac Recorders</u></a></li>
<li><a href="https://location-fake.techidaily.com/a-detailed-vpna-fake-gps-location-free-review-on-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>A Detailed VPNa Fake GPS Location Free Review On Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnose-and-correct-bluetooth-connectivity-issues-between-your-keyboard-and-pc/"><u>Diagnose & Correct Bluetooth Connectivity Issues Between Your Keyboard and PC</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-persistent-white-image-display-issues-in-your-portable-pc/"><u>Effective Solutions for Persistent White Image Display Issues in Your Portable PC</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevate-your-iphone-photography-with-advanced-hdr-methods/"><u>Elevate Your iPhone Photography with Advanced HDR Methods</u></a></li>
<li><a href="https://win-solutions.techidaily.com/getting-starfield-running-smoothly-again-fixes-for-launch-issues-on-steamxbox/"><u>Getting Starfield Running Smoothly Again - Fixes for Launch Issues on Steam/Xbox</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/how-do-you-play-mov-files-on-samsung-galaxy-s23plus-by-aiseesoft-video-converter-play-mov-on-android/"><u>How do you play .mov files on Samsung Galaxy S23+ ?</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-iphone-7-plusipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled iPhone 7 Plus/iPad Without Computer | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/perfecting-ultimate-canon-sequence-crafts-for-2024/"><u>Perfecting Ultimate Canon Sequence Crafts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/reactivating-the-photography-capability-of-your-dell-system-under-a-windows-environment/"><u>Reactivating the Photography Capability of Your Dell System Under a Windows Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-unstable-usb-connections-on-your-computer/"><u>Step-by-Step Fixes for Unstable USB Connections on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-correct-sign-in-problems-caused-by-user-profile-services-on-windows-1011/"><u>Step-by-Step Guide to Correct Sign-In Problems Caused by User Profile Services on Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-dealing-with-port-reset-failures-in-windows-11-drivers/"><u>Troubleshooting Tips: Dealing with Port Reset Failures in Windows 11 Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/white/"><u>White</u></a></li>
</ul></div>

