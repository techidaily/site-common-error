---
title: "Quick Fixes for Resolving Constant Reboots on Windows 11: A Step-by-Step Guide"
date: 2024-09-04T20:21:57.983Z
updated: 2024-09-05T20:21:57.983Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Quick Fixes for Resolving Constant Reboots on Windows 11: A Step-by-Step Guide"
excerpt: "This Article Describes Quick Fixes for Resolving Constant Reboots on Windows 11: A Step-by-Step Guide"
thumbnail: https://thmb.techidaily.com/a0ea0929e49147a7aa2982696f1085c4ea3dc3044596db757054a8f03e6ab91e.jpg
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

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1948881/19272" target="_top" id="1948881">
  <img src="//a.impactradius-go.com/display-ad/19272-1948881" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1948881/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043662/7443" target="_top" id="2043662">
  <img src="//a.impactradius-go.com/display-ad/7443-2043662" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043662/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)
5. Right-click**Dhcp** under the Services section to select**Export** .  
<!-- affiliate ads begin -->
<span id="1531879">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1531879.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1531879">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1531879.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1531879%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1531879/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)
<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947746/11832" target="_top" id="947746">
  <img src="//a.impactradius-go.com/display-ad/11832-947746" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947746/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075462/7443" target="_top" id="2075462">
  <img src="//a.impactradius-go.com/display-ad/7443-2075462" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075462/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/new-2024-approved-journey-through-japan-best-video-games-akin-to-ghost-of-tsushima/"><u>[New] 2024 Approved  Journey Through Japan  Best Video Games Akin to Ghost of Tsushima</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-elevate-your-channels-visibility-through-proven-methods-for-2024/"><u>[New] Elevate Your Channels Visibility Through Proven Methods for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-expert-tips-streaming-youtube-and-fb-videos-seamlessly-with-apple-tv/"><u>[New] Expert Tips  Streaming YouTube & FB Videos Seamlessly with Apple TV</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-influencer-secrets-making-your-vids-hits-hard-for-2024/"><u>[New] Influencer Secrets  Making Your Vids Hits Hard for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-elevating-your-content-strategy-with-smart-igtv-hashtags-for-2024/"><u>[Updated] Elevating Your Content Strategy with Smart IGTV Hashtags for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-integrated-mobility-evaluation-study-for-2024/"><u>[Updated] Integrated Mobility Evaluation Study for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-the-ultimate-collection-of-elite-cost-free-vfx-and-editing-websites/"><u>2024 Approved  The Ultimate Collection of Elite, Cost-Free VFX & Editing Websites</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-unmatched-performance-and-price-select-top-asmr-microphone-picks/"><u>2024 Approved  Unmatched Performance & Price - Select Top ASMR Microphone Picks</u></a></li>
<li><a href="https://common-error.techidaily.com/a-step-by-step-guide-restoring-your-steam-files-privileges/"><u>A Step-by-Step Guide: Restoring Your Steam Files’ Privileges</u></a></li>
<li><a href="https://win-forum.techidaily.com/complete-walkthrough-for-installing-and-using-revo-uninstaller-pro-on-mobile-devices/"><u>Complete Walkthrough for Installing and Using Revo Uninstaller Pro on Mobile Devices</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/convert-any-video-format-with-macx-hd-converter-pro-windows-10-top-rated-software-for-iphoneipadandroid-media-editing-and-slideshow-creation/"><u>Convert Any Video Format with MacX HD Converter Pro Windows 10 - Top Rated Software for iPhone/iPad/Android Media Editing and Slideshow Creation</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-and-solving-the-windows-10-teal-screen-mystery-for-good/"><u>Decoding and Solving the Windows 10 Teal Screen Mystery for Good</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-when-your-computer-wont-recognize-your-usb-drive/"><u>Effortless Fixes for When Your Computer Won't Recognize Your USB Drive</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/enhance-communication-skills-in-german-via-netflix/"><u>Enhance Communication Skills in German Via Netflix</u></a></li>
<li><a href="https://common-error.techidaily.com/explorerexe-error-solved-and-secured/"><u>Explorer.exe Error: Solved & Secured</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-permanent-windows-10-update-freeze-at-99-percent/"><u>Fixing the Permanent Windows 10 Update Freeze at 99 Percent</u></a></li>
<li><a href="https://howto.techidaily.com/gmail-not-working-on-motorola-moto-e13-7-common-problems-and-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Gmail Not Working on Motorola Moto E13 7 Common Problems & Fixes | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/how-to-easily-hard-reset-my-tecno-camon-20-premier-5g-drfone-by-drfone-reset-android-reset-android/"><u>How to Easily Hard reset my Tecno Camon 20 Premier 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208441396-how-to-overcome-failed-update-issues-in-your-favorite-mmo-warframe/"><u>How to Overcome Failed Update Issues in Your Favorite MMO, Warframe!</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-messages-from-your-google-pixel-8-by-fonelab-android-recover-messages/"><u>How to recover old messages from your Google Pixel 8</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-overwatch-server-connection-error-quickly-and-easily/"><u>How to Resolve the Overwatch Server Connection Error Quickly and Easily</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-14-to-others-ios-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone 14 To Others ios devices? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-any-itel-a60-phone-password-using-emergency-call-by-drfone-android/"><u>How To Unlock Any Itel A60 Phone Password Using Emergency Call</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-location-on-tiktok-to-see-more-content-on-your-nokia-c210-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Location on TikTok to See More Content On your Nokia C210 | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-sharefake-location-on-whatsapp-for-vivo-g2-drfone-by-drfone-virtual-android/"><u>In 2024, How to Share/Fake Location on WhatsApp for Vivo G2 | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-poco-m6-pro-4g-pin-codepattern-lockpassword-by-drfone-android/"><u>In 2024, How to Unlock Poco M6 Pro 4G PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-still-using-pattern-locks-with-motorola-moto-g-stylus-5g-2023-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Motorola Moto G Stylus 5G (2023)? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-the-comprehensive-manual-for-effective-morphvox-voice-changes/"><u>In 2024, The Comprehensive Manual for Effective MorphVOX Voice Changes</u></a></li>
<li><a href="https://common-error.techidaily.com/integrating-windows-hello-with-appropriate-camera/"><u>Integrating Windows Hello With Appropriate Camera</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/new-free-video-stabilizer-roundup-the-best-options/"><u>New Free Video Stabilizer Roundup The Best Options</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-stop-your-mouse-from-wandering-solo/"><u>Quick Solutions: Stop Your Mouse From Wandering Solo</u></a></li>
<li><a href="https://common-error.techidaily.com/reset-or-refresh-a-beginners-guide-to-reviving-windows-10/"><u>Reset or Refresh - A Beginner's Guide to Reviving Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-no-supported-devices-detected-fixes-and-tips-for-windows-7-setup/"><u>Resolve 'No Supported Devices Detected': Fixes & Tips for Windows 7 Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-chromes-mystery-a-guide-to-overcoming-complete-screen-darkness/"><u>Resolve Chrome's Mystery: A Guide to Overcoming Complete Screen Darkness</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209897455-resolve-your-windows-10-bluetooth-disappearance-troubles-with-simple-fixes/"><u>Resolve Your Windows 10 Bluetooth Disappearance Troubles with Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-a-comprehensive-guide-on-overcoming-the-red-screen-error/"><u>Resolved: A Comprehensive Guide on Overcoming the Red Screen Error</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-error-message-applicationexe-has-stopped-now-fixed/"><u>Resolved: Error Message 'Application.exe Has Stopped' Now Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-wacom-tablet-driver-issues-in-windows-11/"><u>Resolved: Fixing Wacom Tablet Driver Issues in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-initialization-issue-with-renderer-updated-solution-2021/"><u>Resolved: Initialization Issue with Renderer (Updated Solution, 2021)</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-to-logildadll-missing-error/"><u>Solution to LogiLDA.dll Missing Error</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-hp-laptops-webcam-issues-on-windows-10-a-step-by-step-guide/"><u>Solving Your HP Laptop's Webcam Issues on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-restoring-webcam-functionality-on-hp-devices-with-windows-11/"><u>Step-by-Step Solution: Restoring Webcam Functionality on HP Devices with Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-essence-of-effortless-live-broadcasts-with-one-device-use-for-2024/"><u>The Essence of Effortless Live Broadcasts with One-Device Use for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-essential-blueprint-for-melding-linktree-into-tiktok-profiles-for-2024/"><u>The Essential Blueprint for Melding Linktree Into TikTok Profiles for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/the-final-countdown-over-fortnite-launched/"><u>The Final Countdown Over - Fortnite Launched</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203614301-trouble-with-camera-on-windows-overcome-error-0xa00f4292-here/"><u>Trouble with Camera on Windows? Overcome Error 0xA00F4292 Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-persistent-restarting-in-windows-11-with-simple-solutions/"><u>Troubleshoot Persistent Restarting in Windows 11 with Simple Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-red-dead-redemption-ii-memory-full-error-with-easy-pagefile-increase-tips/"><u>Troubleshoot Red Dead Redemption II 'Memory Full' Error with Easy Pagefile Increase Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-the-0x80070490-error-on-your-windows-system/"><u>Troubleshooting and Solving the 0X80070490 Error on Your Windows System</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-pubg-network-delays-and-errors-for-improved-online-play-experience/"><u>Troubleshooting PUBG Network Delays and Errors for Improved Online Play Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-how-to-fix-incorrectly-pressed-keys-while-typing/"><u>Troubleshooting: How to Fix Incorrectly Pressed Keys While Typing</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-the-error-dealing-with-non-compatible-entries-on-visual-outputs/"><u>Understanding the Error: Dealing with Non-Compatible Entries on Visual Outputs</u></a></li>
<li><a href="https://unlock-android.techidaily.com/unlocking-made-easy-the-best-10-apps-for-unlocking-your-google-pixel-7a-device-by-drfone-android/"><u>Unlocking Made Easy The Best 10 Apps for Unlocking Your Google Pixel 7a Device</u></a></li>
<li><a href="https://common-error.techidaily.com/what-should-i-do-when-windows-10-hangs/"><u>What Should I Do when Windows 10 Hangs?</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/where-is-the-best-place-to-catch-dratini-on-oppo-a1x-5g-drfone-by-drfone-virtual-android/"><u>Where Is the Best Place to Catch Dratini On Oppo A1x 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-10-freeze-tips-and-fixes-for-update-woes/"><u>Winning Against Windows 10 Freeze: Tips and Fixes for Update Woes</u></a></li>
</ul></div>
