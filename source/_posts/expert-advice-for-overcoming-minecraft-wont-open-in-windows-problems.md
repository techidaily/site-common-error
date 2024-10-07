---
title: Expert Advice for Overcoming 'Minecraft Won't Open in Windows' Problems
date: 2024-09-30T06:26:25.389Z
updated: 2024-10-06T19:31:01.217Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Advice for Overcoming 'Minecraft Won't Open in Windows' Problems
excerpt: This Article Describes Expert Advice for Overcoming 'Minecraft Won't Open in Windows' Problems
thumbnail: https://thmb.techidaily.com/716b773a3a0bbb4238a628ab28cfde8731d3dd391169cbf818a66e733201ea5d.jpg
---

## The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included

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
<a href="https://homestyler.sjv.io/c/5597632/1943648/22993" target="_top" id="1943648">
  <img src="//a.impactradius-go.com/display-ad/22993-1943648" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886073/19272" target="_top" id="1886073">
  <img src="//a.impactradius-go.com/display-ad/19272-1886073" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886073/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100526/7443" target="_top" id="2100526">
  <img src="//a.impactradius-go.com/display-ad/7443-2100526" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100526/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-the-fundamentals-of-synchronizing-audio-and-video-in-screencasts/"><u>[New] 2024 Approved The Fundamentals of Synchronizing Audio and Video in Screencasts</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-revolutionize-your-pc-captures-with-these-top-tools/"><u>[Updated] Revolutionize Your PC Captures with These Top Tools</u></a></li>
<li><a href="https://solve-latest.techidaily.com/1-how-to-convert-mts-files-to-mp4-for-free-a-step-by-step-guide-for-windows-and-macos-users/"><u>1. How to Convert MTS Files to MP4 for Free: A Step-by-Step Guide for Windows & macOS Users</u></a></li>
<li><a href="https://howto.techidaily.com/4-solutions-to-fix-unfortunately-your-app-has-stopped-error-on-samsung-galaxy-s23-fe-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>4 Solutions to Fix Unfortunately Your App Has Stopped Error on Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/amplify-your-sound-experience-connecting-an-array-of-bluetooth-speakers-to-one-device/"><u>Amplify Your Sound Experience: Connecting an Array of Bluetooth Speakers to One Device</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-the-errcachemiss-error-in-your-google-chrome-browser/"><u>Effective Fixes for the ERR_CACHE_MISS Error in Your Google Chrome Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-resolving-io-device-malfunctions/"><u>Effective Solutions for Resolving I/O Device Malfunctions</u></a></li>
<li><a href="https://common-error.techidaily.com/efficient-fixes-for-when-you-cant-reach-your-remote-server-insider-techniques/"><u>Efficient Fixes for When You Can't Reach Your Remote Server: Insider Techniques</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-download-broadcom-wireless-network-drivers-compatible-with-windows-11-8-and-7/"><u>Free Download: Broadcom Wireless Network Drivers Compatible with Windows 11, 8 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-dolby-sound-malfunctioning-in-microsofts-latest-os/"><u>How to Fix Dolby Sound Malfunctioning in Microsoft's Latest OS</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-honor-x50-gt-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Honor X50 GT? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-hidefake-snapchat-location-on-your-realme-note-50-drfone-by-drfone-virtual-android/"><u>In 2024, How to Hide/Fake Snapchat Location on Your Realme Note 50 | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/mastering-keywords-with-oxfords-ease/"><u>Mastering Keywords with Oxford's Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-11-lockup-difficulties-techniques-to-safely-close-your-system-down/"><u>Overcoming Windows 11 Lockup Difficulties: Techniques to Safely Close Your System Down</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-solutions-for-screen-flashing-troubleshooting-on-windows-11-computers/"><u>Ultimate Solutions for Screen Flashing Troubleshooting on Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-repeated-automatic-restarts-in-computers-expert-tips-inside/"><u>Understanding & Fixing Repeated Automatic Restarts in Computers - Expert Tips Inside!</u></a></li>
</ul></div>

