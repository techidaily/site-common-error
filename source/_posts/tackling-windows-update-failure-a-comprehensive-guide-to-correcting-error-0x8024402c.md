---
title: "Tackling Windows Update Failure: A Comprehensive Guide to Correcting Error 0X8024402C"
date: 2024-08-15T11:01:46.288Z
updated: 2024-08-16T11:01:46.288Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Tackling Windows Update Failure: A Comprehensive Guide to Correcting Error 0X8024402C"
excerpt: "This Article Describes Tackling Windows Update Failure: A Comprehensive Guide to Correcting Error 0X8024402C"
thumbnail: https://thmb.techidaily.com/ef2d39454969b75baf5c215d0724710d89c3d8cc82ce806ec7a058e29ddc30fe.jpg
---

## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=30901410&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_1_copy_vMixCallScreenshot1-large.jpg" border="0"> vMix Pro - Software based live production. vMix Pro includes everything in vMix 4K plus 8 channels of Replay and 8 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3546200&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.binteko.com/sites/default/files/banner01_468x60a.gif" border="0"></a>
<!-- affiliate ads end -->
## Fix 1: Reset your Windows Update components

 The Windows Update “0x8024002e” error code may occur because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this fixes your problem.

To reset these components:

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “cmd” in the Run box, then, on your keyboard, press the**Ctrl** ,**Shift** and**Enter** keys at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-884.png)

3. If prompted, click**Yes** .
4. In Command Prompt, type the following lines of command and press**Enter** on your keyboard after typing each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

5. Type these lines of command and press**Enter** after typing each in Command Prompt:

ren %systemroot%\softwaredistribution softwaredistribution.old
ren %systemroot%\system32\catroot2 catroot2.old

6. In Command Prompt, type these commands and press**Enter** after each:

net start bits
net start wuauserv
net start appidsvc
net start cryptsvc

7. Try updating your system with Windows Update, and see if the 0x8024002e error is gone.

 If it is, then you’ve solved your problem. But if not, you may need to…

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698824&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/dex3pro-screenshot-homepage.png" border="0">PCDJ DEX 3 for Windows & MAC is the total entertainment DJ software solution, offering audio, video, and karaoke mixing ability. Automatic beat-sync, smart looping, 4 decks, DJ MIDI controller support, Karaoke Streaming and much more. 
DEX 3 meets the demands of today’s versatile DJ, without compromise! 
DEX 3 (Audio, Video and Karaoke Mixing Software for Windows/MAC | 3 Activations and Free Updates)</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4550420&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/pic/f_02.jpg" border="0">PearlMountain Image Converter</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BVideo%2BConverter%2BBox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/8020c1dc-518e-3bdf-6e7b-e6d1bdf1597b.jpg" border="0"></a>
<!-- affiliate ads end -->
## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4712430&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c404a5adbf90e09631678b13b05d9d7a/products/dlnow_256.png" border="0">DLNow Video Downloader</a>
<!-- affiliate ads end -->
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4530091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.pearlmountainsoft.com/n_img/product/cit_win/banScrn.jpg" border="0">CollageIt Pro</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
<!-- affiliate ads begin -->
<a href="https://arkmc.pxf.io/c/5597632/427477/5172" target="_top" id="427477"><img src="//a.impactradius-go.com/display-ad/5172-427477" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://arkmc.pxf.io/i/5597632/427477/5172" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=38709260&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF Perpetual (2-PC)  Free upgrade. No monthly fees ever. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4728277&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/f7f07e7dab09533bc71247a5b29a7373/products/1_iDeviceMessageBox.png" border="0"></a>
<!-- affiliate ads end -->
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
 If there’s any startup item that causes the 0x8024002e error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

 Hopefully one of the fixes above helped you fix your 0x8024002e error on Windows Update. If you have any questions or suggestions, you’re more than welcome to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://youtube-blog.techidaily.com/024-approved-mastering-the-craft-of-youtubers-music-reaction-videos-essentials/"><u>[New] 2024 Approved  Mastering the Craft of Youtubers  Music Reaction Videos Essentials</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/new-effortless-tutorial-for-top-notch-yt-video-thumbnails/"><u>[New] Effortless Tutorial for Top-Notch YT Video Thumbnails</u></a></li>
<li><a href="https://youtube-web.techidaily.com/ed-effortless-mp3-conversion-from-youtube-for-mac-users-for-2024/"><u>[Updated] Effortless MP3 Conversion From YouTube for Mac Users for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-rhythm-and-reel-adding-music-to-ig-feeds/"><u>[Updated] In 2024, Rhythm and Reel  Adding Music to IG Feeds</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-mastering-viral-fame-boosting-your-videos-popularity-on-youtube/"><u>[Updated] Mastering Viral Fame  Boosting Your Video's Popularity on YouTube</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-crypto-artistry-unleashed-the-best-generators-transforming-images/"><u>2024 Approved  Crypto Artistry Unleashed  The Best Generators Transforming Images</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-the-subtle-art-of-easing-audio-intensity-garageband/"><u>2024 Approved  The Subtle Art of Easing Audio Intensity (Garageband)</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/5-ways-to-reset-xiaomi-redmi-note-13-5g-without-volume-buttons-drfone-by-drfone-reset-android-reset-android/"><u>5 Ways to Reset Xiaomi Redmi Note 13 5G Without Volume Buttons | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-ue4s-halo-4-2024-fatal-crash-a-step-by-step-fix-manual/"><u>Bypassing UE4's Halo 4 2024 Fatal Crash - A Step-by-Step Fix Manual</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/convenient-methods-for-macbook-pros-video-recording/"><u>Convenient Methods for MacBook Pro's Video Recording</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/convert-live-facebook-videos-to-mp3s-on-the-fly-for-2024/"><u>Convert Live Facebook Videos to MP3s on the Fly for 2024</u></a></li>
<li><a href="https://tech-haven.techidaily.com/effective-strategies-leveraging-chatgpt-in-online-team-collaborations/"><u>Effective Strategies: Leveraging ChatGPT in Online Team Collaborations</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-overcoming-obstacles-during-a-windows-software-installation/"><u>Expert Advice: Overcoming Obstacles During a Windows Software Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-modifying-windows-settings-under-corporate-governance/"><u>Expert Guide: Modifying Windows Settings Under Corporate Governance</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-getting-your-wireless-mouse-working-smoothly-again-on-windows-11-or-10/"><u>Expert Tips for Getting Your Wireless Mouse Working Smoothly Again on Windows 11 or 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210270675-fixing-kodi-malfunctions-effective-tips-and-tricks-unveiled/"><u>Fixing Kodi Malfunctions: Effective Tips & Tricks Unveiled!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204948165-fortnite-troubleshooting-launch-success/"><u>Fortnite Troubleshooting: Launch Success!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-your-windows-10-microphone-expert-troubleshooting-tips/"><u>How to Restore Your Windows 10 Microphone: Expert Troubleshooting Tips</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-spy-on-text-messages-from-computer-and-realme-c51-drfone-by-drfone-virtual-android/"><u>How to Spy on Text Messages from Computer & Realme C51 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/icue-fixes-at-hand-tackling-the-device-not-detected-problem-easily/"><u>ICUE Fixes at Hand: Tackling the 'Device Not Detected' Problem Easily</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-3-facts-you-need-to-know-about-screen-mirroring-lenovo-thinkphone-drfone-by-drfone-android/"><u>In 2024, 3 Facts You Need to Know about Screen Mirroring Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-can-you-unlock-iphone-13-pro-after-forgetting-the-passcode-drfone-by-drfone-ios/"><u>In 2024, Can You Unlock iPhone 13 Pro After Forgetting the Passcode? | Dr.fone</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-enhance-your-medias-exposure-on-the-platform/"><u>In 2024, Enhance Your Media's Exposure on the Platform</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-remove-or-bypass-knox-enrollment-service-on-infinix-note-30-vip-racing-edition-by-drfone-android/"><u>In 2024, How To Remove or Bypass Knox Enrollment Service On Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-vivo-y55s-5g-2023-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Vivo Y55s 5G (2023) to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-the-directors-eye-15-essential-camera-shots-explained/"><u>In 2024, The Director's Eye  15 Essential Camera Shots Explained</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/non-twitter-video-tweeting-hacks-for-the-modern-user/"><u>Non-Twitter Video Tweeting Hacks for the Modern User</u></a></li>
<li><a href="https://common-error.techidaily.com/offscreen-window-woes-discover-effective-ways-to-restore-them/"><u>Offscreen Window Woes? Discover Effective Ways to Restore Them</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-startup-struggles-break-free-from-constant-restarts-in-windows-1110/"><u>Overcome Startup Struggles: Break Free From Constant Restarts in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-your-battleye-setup-woes-effective-solutions-for-smooth-functionality/"><u>Overcome Your BattlEye Setup Woes – Effective Solutions for Smooth Functionality</u></a></li>
<li><a href="https://fix-guide.techidaily.com/play-store-stuck-on-downloading-of-tecno-spark-10c-7-ways-to-resolve-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Play Store Stuck on Downloading Of Tecno Spark 10C? 7 Ways to Resolve | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-unable-to-reach-file-location-in-windows-error-quickly/"><u>Resolving 'Unable to Reach File Location in Windows' Error Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-stuck-keys-on-your-windows-pc-comprehensive-fixes-inside/"><u>Reviving Stuck Keys on Your Windows PC - Comprehensive Fixes Inside</u></a></li>
<li><a href="https://fox-blue.techidaily.com/showcasing-design-brilliance-best-10-text-setups-in-ae/"><u>Showcasing Design Brilliance  Best 10 Text Setups in AE</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-enabling-night-mode-when-windows-10s-night-light-is-unresponsive/"><u>Solution Steps for Enabling Night Mode when Windows 10'S Night Light Is Unresponsive</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-clearing-and-solving-errcachemiss-errors-in-chrome/"><u>Step-by-Step Guide: Clearing and Solving ERR_CACHE_MISS Errors in Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-repair-tips-correcting-windows-1110-error-code-0x80ebase-f/"><u>Step-by-Step Repair Tips: Correcting Windows 11/10 Error Code 0X80ebase F</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-restore-functionality-of-your-left-click-mouse/"><u>Step-by-Step Solutions to Restore Functionality of Your Left Click Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-how-to-stop-halo-4-ue4-from-crashing-permanently-year-2024-strategies/"><u>The Ultimate Fix: How to Stop Halo 4 UE4 From Crashing Permanently - Year 2024 Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-your-devices-unwanted-power-naps-with-easy-tips/"><u>Troubleshoot Your Device's Unwanted Power Naps with Easy Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-logitech-g930-steps-for-addressing-volume-interruptions/"><u>Troubleshooting Logitech G930: Steps for Addressing Volume Interruptions</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-making-your-lenovo-mouse-pad-work-again-on-pcs-with-windows-1187-operating-systems/"><u>Ultimate Guide: Making Your Lenovo Mouse Pad Work Again on PCs with Windows 11/8/7 Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-the-power-of-file-explorer-on-windows-10-a-beginners-guide/"><u>Unlocking the Power of File Explorer on Windows 10: A Beginner's Guide</u></a></li>
<li><a href="https://games-able.techidaily.com/what-makes-steam-different-from-gog-game-sellers/"><u>What Makes Steam Different From GOG Game Sellers?</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-printer-problems-a-detailed-guide-to-resolve-xerox-update-error-0x800f020b-in-windows/"><u>Winning Against Printer Problems: A Detailed Guide to Resolve Xerox Update Error 0X800f020b in Windows</u></a></li>
</ul></div>
