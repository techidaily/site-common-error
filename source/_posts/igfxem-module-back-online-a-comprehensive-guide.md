---
title: "IgfxEM Module Back Online: A Comprehensive Guide"
date: 2024-09-20T17:10:59.001Z
updated: 2024-09-26T20:46:43.716Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes IgfxEM Module Back Online: A Comprehensive Guide"
excerpt: "This Article Describes IgfxEM Module Back Online: A Comprehensive Guide"
thumbnail: https://thmb.techidaily.com/2b667f6d425e137d74634d5b5e43d01ba3b3015e34fc38e54ba016f1aa0f02aa.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2037335/7443" target="_top" id="2037335">
  <img src="//a.impactradius-go.com/display-ad/7443-2037335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037335/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2111965/7443" target="_top" id="2111965">
  <img src="//a.impactradius-go.com/display-ad/7443-2111965" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111965/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087248/19272" target="_top" id="2087248">
  <img src="//a.impactradius-go.com/display-ad/19272-2087248" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087248/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2006928/19272" target="_top" id="2006928">
  <img src="//a.impactradius-go.com/display-ad/19272-2006928" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2006928/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144298/7443" target="_top" id="2144298">
  <img src="//a.impactradius-go.com/display-ad/7443-2144298" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144298/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/new-apple-vs-android-the-face-id-and-galaxy-recognition-race/"><u>[New] Apple Vs. Android The Face ID and Galaxy Recognition Race</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-expert-recommended-steadicams-for-professional-dslr-work/"><u>[Updated] Expert-Recommended Steadicams for Professional DSLR Work</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-cutting-ties-in-cyberspace-an-exit-strategy-from-discords/"><u>[Updated] In 2024, Cutting Ties in Cyberspace An Exit Strategy From Discords</u></a></li>
<li><a href="https://network-issues.techidaily.com/crystal-clear-interface-effortless-change/"><u>Crystal-Clear Interface, Effortless Change</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208069021-enhance-windows-7-launch-speed-top-solutions-to-combat-delays/"><u>Enhance Windows 7 Launch Speed: Top Solutions to Combat Delays</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-malfunctioning-microphone-on-your-laptop-step-by-step-guide/"><u>Fixing a Malfunctioning Microphone on Your Laptop - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-overcoming-errors-when-steams-vac-cant-validate-your-match/"><u>Guide: Overcoming Errors when Steam's VAC Can’t Validate Your Match</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-laptop-running-again-fast-charging-solutions/"><u>How to Get Your Laptop Running Again: Fast Charging Solutions</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-essential-steps-for-iptv-video-recording/"><u>In 2024, Essential Steps for IPTV Video Recording</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-flash-dramatization-structure/"><u>In 2024, Flash Dramatization Structure</u></a></li>
<li><a href="https://techidaily.com/is-your-xiaomi-redmi-12-working-too-slow-heres-how-you-can-hard-reset-it-drfone-by-drfone-reset-android-reset-android/"><u>Is your Xiaomi Redmi 12 working too slow? Heres how you can hard reset it | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/kickstart-creative-video-editing-with-xp-edition-for-2024/"><u>Kickstart Creative Video Editing with Xp Edition for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-error-resolution-eliminate-code-0x800f0831-with-ease-using-windows-update-features/"><u>Mastering Error Resolution: Eliminate Code 0X800^F0831 with Ease Using Windows Update Features</u></a></li>
<li><a href="https://win11-tips.techidaily.com/movavi-redigerer-oplysning-og-effektivitet-for-din-video-bearbejstningsnedskudsfrihenheder-forsvart-sikker-kob-now/"><u>Movavi Redigerer - Oplysning Og Effektivitet for Din Video Bearbejstningsnedskudsfrihenheder | Forsvart Sikker Køb Now</u></a></li>
<li><a href="https://screen-recording.techidaily.com/optimizing-obs-video-compression/"><u>Optimizing OBS Video Compression</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-msvcp140dll-integrity/"><u>Restoring MSVCP140.dll Integrity</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-intermittent-sounds-in-your-logitech-g930-wireless-earphones/"><u>Solution for Intermittent Sounds in Your Logitech G930 Wireless Earphones</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-wolfenstein-2-crash-dump-problems/"><u>Troubleshooting Guide: Fixing 'Wolfenstein 2' Crash Dump Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-issues-when-opening-geforce-experience/"><u>Troubleshooting Guide: Resolving Issues When Opening GeForce Experience</u></a></li>
</ul></div>

