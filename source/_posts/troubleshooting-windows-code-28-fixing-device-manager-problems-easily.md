---
title: "Troubleshooting Windows Code 28: Fixing Device Manager Problems Easily"
date: 2024-10-07T01:22:32.295Z
updated: 2024-10-13T00:47:13.650Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Windows Code 28: Fixing Device Manager Problems Easily"
excerpt: "This Article Describes Troubleshooting Windows Code 28: Fixing Device Manager Problems Easily"
thumbnail: https://thmb.techidaily.com/f6b900a7e2a78e7ffb6b0f28d526eebcba1c857a70cbdea2eddb16d9a4a9539b.png
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

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)

<!-- affiliate ads begin -->
<span id="1542129">
					<video width="864" height="1152" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1542129.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1542129">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1542129.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1542129%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1542129/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036467/19272" target="_top" id="2036467">
  <img src="//a.impactradius-go.com/display-ad/19272-2036467" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036467/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148649/16836" target="_top" id="2148649">
  <img src="//a.impactradius-go.com/display-ad/16836-2148649" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148649/16836" style="position:absolute;visibility:hidden;" border="0" />
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
5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/863035/11832" target="_top" id="863035">
  <img src="//a.impactradius-go.com/display-ad/11832-863035" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/863035/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-web.techidaily.com/ed-discover-how-to-design-dynamic-youtube-music-playlists/"><u>[Updated] Discover How to Design Dynamic YouTube Music Playlists</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-inside-the-evolved-sony-bdp-s6700-world/"><u>2024 Approved Inside the Evolved Sony BDP-S6700 World</u></a></li>
<li><a href="https://howto.techidaily.com/6-solutions-to-fix-error-505-in-google-play-store-on-xiaomi-14-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>6 Solutions to Fix Error 505 in Google Play Store on Xiaomi 14 Ultra | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/7-ways-to-lock-apps-on-iphone-13-pro-and-ipad-securely-drfone-by-drfone-ios/"><u>7 Ways to Lock Apps on iPhone 13 Pro and iPad Securely | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-resolving-windows-update-paused-at-completion-stage/"><u>Effective Solutions for Resolving Windows Update Paused at Completion Stage</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-guide-to-speed-up-your-unresponsive-keyboard/"><u>Effortless Guide to Speed Up Your Unresponsive Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-repair-csgo-crashes-fast-and-simple/"><u>Effortless Solutions: Repair CSGO Crashes Fast and Simple</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-broken-webcam-on-lenovo-devices-comprehensive-solutions-for-users/"><u>Fixing a Broken Webcam on Lenovo Devices: Comprehensive Solutions for Users</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-undo-macos-sierras-os-x-transition/"><u>In 2024, How to Undo MacOS Sierra's OS X Transition</u></a></li>
<li><a href="https://fox-tls.techidaily.com/logiciels-de-sauvegarde-incrementielle-leaders-en-telechargement-gratuits-pour-windows-11/"><u>Logiciels De Sauvegarde Incrémentielle Leaders en Téléchargement Gratuits Pour Windows 11</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-and-rectifying-workspace-errors-in-office-software/"><u>Navigating and Rectifying Workspace Errors in Office Software</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-msmpengexe-reducing-high-cpu-usage-on-windows-11-solved/"><u>Optimizing MsMpEng.exe: Reducing High CPU Usage on Windows 11 - Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-obstacles-in-nvidia-system-installation/"><u>Overcoming Obstacles in NVIDIA System Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-the-blue-light-filter-in-windows-10-and-11/"><u>Resolving Issues with the Blue Light Filter in Windows 10 & 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/selecting-the-ultimate-gear-for-stellar-4k-production-for-2024/"><u>Selecting the Ultimate Gear for Stellar 4K Production for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-halting-error-in-32-bit-applications-print-driver-revived/"><u>Solution Found: Halting Error in 32-Bit Application's Print Driver Revived!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unbelievable-offer-top-notch-black-nylon-filament-for-3d-printing-at-a-steal-just-16kg/"><u>Unbelievable Offer: Top-Notch Black Nylon Filament for 3D Printing at a Steal – Just $16/Kg</u></a></li>
</ul></div>

