---
title: How to Fix Error Code 0X8024200D During Windows Updates – A Comprehensive Guide
date: 2024-09-04T20:22:00.327Z
updated: 2024-09-05T20:22:00.327Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Error Code 0X8024200D During Windows Updates – A Comprehensive Guide
excerpt: This Article Describes How to Fix Error Code 0X8024200D During Windows Updates – A Comprehensive Guide
thumbnail: https://thmb.techidaily.com/a88de5655376206e2ee17661cb9dd03b46b68bf81e7fb9a2b0bcd4cf8d7ba0d8.jpg
---

## Definitive Solutions to Error 0X802^24200D – Successfully Update Your Windows System Now

If you’re seeing an**error code 0x8024200d**  when performing a Windows update,  you’re not alone. Many Windows users are reporting it. This error code usually appears when they try to update to a new build of the Windows system. The reason behind it is that some updated files are missing or corrupted.

 The good news is you can fix it. You should be able to fix the problem quite easily using one of the solutions we’ve listed below. You may not have to try them all. Just work your way down the list until you find the one that works.

1. [**Running the Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. **[Restarting the Windows Update service](https://tools.techidaily.com/drivereasy/download/)**
3. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
4. **[Downloading updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**

## Method 1: Running the Windows Update Troubleshooter

 You can download and run**the Windows Update Troubleshooter** to automatically diagnose and resolve any issues regarding Windows Update.

**1)** Click **[here](http://aka.ms/diag%5Fwu)**  to download the Windows Update Troubleshooter.

**2)** Double-click the downloaded file (**WindowsUpdate.diagcab** ) to run the troubleshooter, and then click**Next** .

**If your current operating system is Windows 7** , you just need to wait until the troubleshooter finishes the process and shows you the process result.**If your current operating system is Windows 8 or Windows 10** , you may need to follow the steps below.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap3-1.png)

**3)** If there is a more recent version of Windows Update troubleshooter available, click to run it.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap4-2.png)

**4)** In the new version of Windows Update troubleshooter, Click **Next** . The troubleshooter will check the available updates for your machine.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap5-1.png)

**5)** Click **Apply this fix**  to start the update process in the background immediately.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap7.png)

 The troubleshooter will try to fix the issue for you. You can restart your computer and try to perform the Windows update again. If it still doesn’t work, please try the next method.

## Method 2: Restarting the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try to restart the Windows Update service to resolve this problem. Here’s how to do it:

**1)** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog, then type**services.msc** and press**Enter** to open the Services window.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap13.png)

**2)** Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap14-2.png)

**3)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open **File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.

`C:\Windows\SoftwareDistribution\DataStore`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap18-2.png)

Please paste it in the address bar.

**4)** Delete all the files in the folder **DataStore** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap20-1.png)

 When all the files are deleted, you shall see “This folder is empty”.

**5)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open**File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to open the**Download** folder.

`` `C:\Windows\SoftwareDistribution\Download`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap21-1.png)

Please paste it in the address bar.

**6)** Delete all the files in the folder**Download** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap22-3.png)

 When all the files are deleted, you shall see “This folder is empty”.

**7)** In the Services window, right-click **Windows Update**  and select**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap24-2.png)

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next method.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043597/7443" target="_top" id="2043597">
  <img src="//a.impactradius-go.com/display-ad/7443-2043597" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043597/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 3: Running System File Checker

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

**1)**  On your keyboard, press**the Windows Logo Key** and then type**cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **Ok** to run the **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap37.png)

<!-- affiliate ads begin -->
<a href="https://oneplusfr.sjv.io/c/5597632/1622438/14044" target="_top" id="1622438">
  <img src="//a.impactradius-go.com/display-ad/14044-1622438" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://oneplusfr.sjv.io/i/5597632/1622438/14044" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**2)** On your keyboard, type the command below and press **Enter** . **If your current operating system is Windows 7, please skip this step.**

DISM.exe /Online /Cleanup-image /Restorehealth

 It may take several minutes for this command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap11.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997695/19272" target="_top" id="1997695">
  <img src="//a.impactradius-go.com/display-ad/19272-1997695" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997695/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**3)** When this command operation is completed, on your keyboard, type the following command and press **Enter** .

sfc /scannow

It may take some time for the command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap12-1.png)

**4)** When this command operation is completed, close the **Command Prompt** and run **Windows Update**  again to check whether this method works or not. If you still fail to install updates for your Windows system, please try the next method.

## Method 4: Downloading updates from Microsoft Update Catalog manually

 If all the methods mentioned above still don’t work for you, you can try to download the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

**1)** On your keyboard, press**the Windows Logo Key** and type**Windows Update** , and then press**Enter** to open Windows Update.

**2)** Click **View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.

**3)** Follow the instructions below to view your system type:

**i.** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Enter** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap40.png)

**ii.**  Type the command line**systeminfo** and press**Enter** to view your system type.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap31-2.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2030373/7443" target="_top" id="2030373">
  <img src="//a.impactradius-go.com/display-ad/7443-2030373" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2030373/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 “**X64-based PC** ” indicates that your Windows OS is 64-bit; “**X86-based PC** ” means that your Windows OS is 32-bit.

**4)** Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

**5)**  Type the update number that you want to download. In this example, type KB 3006137 and then click **Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap42.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915830/19272" target="_top" id="1915830">
  <img src="//a.impactradius-go.com/display-ad/19272-1915830" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915830/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**6)** In the list of search results, select the right update for your operating system and click **Download** .

 If your Windows OS is 64-bit, you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap26-1.png)

**7)** In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap27.png)

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**8)** Double-click the downloaded file and follow the on-screen instructions to install the update.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-mastering-instagram-video-dimensions-for-peak-performance/"><u>[New] In 2024, Mastering Instagram Video Dimensions for Peak Performance</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-navigating-phones-and-samsung-gear-vr-interaction/"><u>[New] Navigating Phones & Samsung Gear VR Interaction</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unveil-the-secrets-of-adventure-with-these-vids/"><u>[New] Unveil the Secrets of Adventure with These Vids</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-list-of-recent-unfollowers-in-instagram/"><u>[Updated] 2024 Approved  List of Recent Unfollowers in Instagram</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-become-an-expert-tutorial-for-making-gifs-into-desirable-whatsapp-and-telegram-stickers/"><u>[Updated] Become an Expert  Tutorial for Making GIFs Into Desirable WhatsApp & Telegram Stickers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-quick-step-by-step-guide-for-youtube-audio-in-imovie/"><u>[Updated] Quick Step-by-Step Guide for YouTube Audio in iMovie</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-viral-ventures-from-likes-to-lore-in-the-facebook-landscape/"><u>[Updated] Viral Ventures  From Likes to Lore in the Facebook Landscape</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-visual-producer-studio-for-2024/"><u>[Updated] Visual Producer Studio for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/2024-approved-15-exceptional-homes-from-the-virtual-world-of-minecraft/"><u>2024 Approved  15 Exceptional Homes From the Virtual World of Minecraft</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/3-methods-to-mirror-xiaomi-civi-3-disney-100th-anniversary-edition-to-roku-drfone-by-drfone-android/"><u>3 Methods to Mirror Xiaomi Civi 3 Disney 100th Anniversary Edition to Roku | Dr.fone</u></a></li>
<li><a href="https://win-amazing.techidaily.com/bcm20702a0-windows-drivers-installed-in-a-flash-get-the-latest-version-now/"><u>BCM20702A0 Windows Drivers Installed in a Flash – Get the Latest Version Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-sxs-side-by-side-configurations-resolving-compatibility-issues-in-windows-11/"><u>Correcting SxS (Side-by-Side) Configurations: Resolving Compatibility Issues in Windows 11</u></a></li>
<li><a href="https://win-blog.techidaily.com/crash-free-gaming-optimizing-your-pc-to-enhance-forza-horizon-4-play-experience/"><u>Crash-Free Gaming: Optimizing Your PC to Enhance Forza Horizon 4 Play Experience</u></a></li>
<li><a href="https://sound-issues.techidaily.com/diagnosing-and-repairing-nonfunctional-headphone-setups-in-windows-7-systems/"><u>Diagnosing and Repairing Nonfunctional Headphone Setups in Windows 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/dxgidll-woes-now-a-thing-of-past-in-pubg/"><u>Dxgi.dll Woes: Now a Thing of Past in PUBG</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-inoperative-usb-slots-on-windows-11-pcs/"><u>Effective Solutions for Inoperative USB Slots on Windows 11 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-why-teredo-qualification-fails-and-how-to-fix-it/"><u>Expert Guide: Why Teredo Qualification Fails and How to Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-application-startup-problems-a-guide-for-built-in-admin-accounts/"><u>Fixing Application Startup Problems: A Guide for Built-In Admin Accounts</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-sound-hiccups-heres-how-to-address-the-cut-out-issue-with-your-logitech-g930/"><u>Fixing Sound Hiccups? Here's How to Address the Cut-Out Issue with Your Logitech G930</u></a></li>
<li><a href="https://win-dash.techidaily.com/get-your-asus-atk0110-acpi-drivers-instantly-free-downloads-available-now/"><u>Get Your ASUS ATK0110 Acpi Drivers Instantly - Free Downloads Available Now</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-of-the-best-pokemon-discord-servers-to-join-on-infinix-note-30-pro-drfone-by-drfone-virtual-android/"><u>Here are Some of the Best Pokemon Discord Servers to Join On Infinix Note 30 Pro | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/honor-100-pro-bootloop-problem-how-to-fix-it-without-data-loss-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Honor 100 Pro Bootloop Problem, How to Fix it Without Data Loss | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-damaged-files-and-directories-that-wont-open/"><u>How to Fix Damaged Files & Directories That Won't Open</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-bypass-activation-lock-on-apple-iphone-15-pro-4-easy-ways-by-drfone-ios/"><u>In 2024, Bypass Activation Lock On Apple iPhone 15 Pro - 4 Easy Ways</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-clocking-down-the-big-day-10-best-mobile-apps-revealed/"><u>In 2024, Clocking Down the Big Day  10 Best Mobile Apps Revealed</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-from-novice-to-expert-mastering-movie-maker-in-windows-8-systems/"><u>In 2024, From Novice to Expert  Mastering Movie Maker in Windows 8 Systems</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-unlock-iphone-11-pro-without-swiping-up-6-ways-drfone-by-drfone-ios/"><u>In 2024, How To Unlock iPhone 11 Pro Without Swiping Up? 6 Ways | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-methods-to-change-gps-location-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>In 2024, Methods to Change GPS Location On Vivo V27 Pro | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/inverted-screen-changing-video-ordering-for-2024/"><u>Inverted Screen  Changing Video Ordering for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-tecno-phantom-v-foldfrp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Tecno Phantom V FoldFRP Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-silence-no-more-effortless-solutions-to-restore-sounds/"><u>Netflix Silence No More: Effortless Solutions to Restore Sounds</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-geforce-experience-not-opening-an-easy-fix/"><u>Overcoming Issues with GeForce Experience Not Opening: An Easy Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-resolving-non-functioning-lenovo-fingerprint-scanner-issues/"><u>Quick Fixes: Resolving Non-Functioning Lenovo Fingerprint Scanner Issues</u></a></li>
<li><a href="https://screen-capture.techidaily.com/realms-united-identifying-the-7-best-strategy-rivals-for-2024/"><u>Realms United  Identifying the 7 Best Strategy Rivals for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-guide-turning-off-a-non-responsive-windows-11-system/"><u>Resolved Guide: Turning Off a Non-Responsive Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-launch-errors-what-to-do-when-minecraft-fails-to-start-in-windows/"><u>Resolving Launch Errors: What to Do When Minecraft Fails to Start in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-missing-opencl-dynamic-library-errors/"><u>Resolving Missing OpenCL Dynamic Library Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-common-update-failed-mistakes-in-warframe-a-comprehvee-guide/"><u>Resolving the Common 'Update Failed' Mistakes in Warframe - A Comprehvee Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-non-appearance-of-wi-fi-settings-on-windows-11-devices/"><u>Resolving the Non-Appearance of Wi-Fi Settings on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-windows-11-brightness-control-problem-for-a-perfect-display-setup/"><u>Resolving the Windows 11 Brightness Control Problem for a Perfect Display Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201594479-shockwave-flash-issues-in-google-chrome-follow-our-updated-solution-guide/"><u>Shockwave Flash Issues in Google Chrome? Follow Our Updated Solution Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-fixing-shockwave-flash-issues-on-google-chrome/"><u>Solution Steps: Fixing Shockwave Flash Issues on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-networking-issue-code-0x80n0704cf-explained-and-resolved/"><u>Solving Windows Networking Issue: Code 0X80n0704CF Explained and Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201318600-steelseries-arctis-5-audio-trouble-heres-how-to-fix-the-mic-problem-permanently/"><u>SteelSeries Arctis 5 Audio Trouble? Here's How to Fix the Mic Problem Permanently!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-integrity-of-windows-os-file-system/"><u>Step-by-Step Guide: Restoring Integrity of Windows OS File System</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-update-error-code-0x80240034-on-windows-10-devices/"><u>Step-by-Step Solution to Overcome 'Update Error' Code 0X80240034 on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-tackling-and-overcoming-delayed-shutdowns-in-windows-10/"><u>The Ultimate Fix: Tackling and Overcoming Delayed Shutdowns in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-common-issues-with-your-oculus-device/"><u>Troubleshooting Guide: Resolving Common Issues with Your Oculus Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-triumph-how-to-successfully-address-the-red-error-message/"><u>Troubleshooting Triumph: How to Successfully Address the Red Error Message</u></a></li>
<li><a href="https://driver-download.techidaily.com/ultimate-guide-installing-updated-creative-audigy-card-drivers-in-windows-ebox/"><u>Ultimate Guide: Installing Updated Creative Audigy Card Drivers in Windows Ebox</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-your-pcs-persistent-freezing-problem/"><u>Ultimate Guide: Solving Your PC's Persistent Freezing Problem</u></a></li>
</ul></div>
