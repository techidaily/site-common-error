---
title: Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside
date: 2024-10-20T21:37:13.630Z
updated: 2024-10-24T21:49:38.633Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside
excerpt: This Article Describes Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside
thumbnail: https://thmb.techidaily.com/91715213b833560df5357cf6515828851bc7618f2025585b01b64f73f1ad8f14.jpg
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
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. **Double-click** WLAN AutoConfig.

5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148650/16836" target="_top" id="2148650">
  <img src="//a.impactradius-go.com/display-ad/16836-2148650" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148650/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135417/19272" target="_top" id="2135417">
  <img src="//a.impactradius-go.com/display-ad/19272-2135417" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135417/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1880940/19272" target="_top" id="1880940">
  <img src="//a.impactradius-go.com/display-ad/19272-1880940" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880940/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  

 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-blog.techidaily.com/ditmaster-app-for-2024/"><u>[New] EditMaster App for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevate-your-presence-the-best-5-practices-for-max-viewers-for-2024/"><u>[New] Elevate Your Presence The Best 5 Practices for Max Viewers for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-decoding-second-count-in-20mb-video-files/"><u>[New] In 2024, Decoding Second Count in 20MB Video Files</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-the-ultimate-guide-to-adjusting-to-new-facebook-ranking-criteria-for-2024/"><u>[New] The Ultimate Guide to Adjusting to New Facebook Ranking Criteria for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-step-up-your-photo-game-basic-snapseed-skills-guide/"><u>[Updated] Step Up Your Photo Game Basic Snapseed Skills Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/code-blocking-mechanism-engaged/"><u>Code Blocking Mechanism Engaged</u></a></li>
<li><a href="https://win-howtos.techidaily.com/converti-i-tuoi-file-avi-in-mp3-senza-costi-guida-di-conversione-online-gratuita-con-movavi/"><u>Converti I Tuoi File AVI in MP3 Senza Costi: Guida Di Conversione Online Gratuita Con Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/cursor-blues-discover-simple-solutions-to-end-the-annoying-blinking/"><u>Cursor Blues? Discover Simple Solutions to End the Annoying Blinking.</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207914319-how-to-fix-windows-updates-stalled-on-99-or-100-solved/"><u>How to Fix Windows Updates Stalled on 99 or 100% - Solved</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-transfer-contacts-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Contacts from Samsung Galaxy XCover 6 Pro Tactical Edition to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/in-2024-fast-forward-your-videos-a-beginners-guide-to-time-lapse-software/"><u>In 2024, Fast Forward Your Videos A Beginners Guide to Time Lapse Software</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-is-fake-gps-location-spoofer-a-good-choice-on-nokia-130-music-drfone-by-drfone-virtual-android/"><u>In 2024, Is Fake GPS Location Spoofer a Good Choice On Nokia 130 Music? | Dr.fone</u></a></li>
<li><a href="https://win11-tips.techidaily.com/intel-unison-calling-made-simple-in-windows-11-environment/"><u>Intel Unison Calling Made Simple in Windows 11 Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-non-functioning-overwatch-voice-communication/"><u>Quick Fixes for Non-Functioning Overwatch Voice Communication</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-fixes-for-turned-off-wireless-networks-now-solved/"><u>Simple Fixes for Turned-Off Wireless Networks - Now Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-for-a-non-functional-hp-laptop-mouse-pad-quick-fixes/"><u>Solution for a Non-Functional HP Laptop Mouse Pad – Quick Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/sticky-keyboard-issues-in-windows-heres-how-you-can-get-them-working-smoothly-again/"><u>Sticky Keyboard Issues in Windows? Here's How You Can Get Them Working Smoothly Again</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-overcoming-the-windows-11-kb5003696-0x80240034-bug-fix-guide/"><u>Successfully Overcoming the Windows 11 KB5003696 (0X80240034) Bug Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-resolving-steam-store-not-loading-issue/"><u>Troubleshooting Tips for Resolving 'Steam Store Not Loading' Issue</u></a></li>
</ul></div>

