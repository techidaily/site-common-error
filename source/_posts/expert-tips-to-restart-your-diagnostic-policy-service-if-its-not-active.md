---
title: Expert Tips to Restart Your Diagnostic Policy Service if It's Not Active
date: 2024-10-23T20:32:47.216Z
updated: 2024-10-24T17:35:49.292Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips to Restart Your Diagnostic Policy Service if It's Not Active
excerpt: This Article Describes Expert Tips to Restart Your Diagnostic Policy Service if It's Not Active
thumbnail: https://thmb.techidaily.com/ff27900c09b1e7c1dbf788a17f82a6622f15751a0bcc9355401391b0248f242f.jpg
---

## Resolving 'Diagnostics Policy Service Is Offline – Here’s What To Do

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1884021/19272" target="_top" id="1884021">
  <img src="//a.impactradius-go.com/display-ad/19272-1884021" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1884021/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136625/26400" target="_top" id="2136625">
  <img src="//a.impactradius-go.com/display-ad/26400-2136625" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136625/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://fox-friendly.techidaily.com/new-2024-approved-top-vectors-alternatives-to-the-classic-acid-pro/"><u>[New] 2024 Approved Top Vectors Alternatives to the Classic ACID Pro</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-innovative-strategies-for-youtube-ads-by-the-elite/"><u>[New] Innovative Strategies for YouTube Ads by the Elite</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-changing-frozen-moments-into-sequential-movies/"><u>[Updated] Changing Frozen Moments Into Sequential Movies</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-elevate-your-photo-game-top-5-android-photo-editors-ranked-for-2024/"><u>[Updated] Elevate Your Photo Game Top 5 Android Photo Editors Ranked for 2024</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-shoppers-quick-guide-to-choosing-top-notch-360cams/"><u>2024 Approved The Shopper’s Quick Guide to Choosing Top-Notch 360Cams</u></a></li>
<li><a href="https://win-excellent.techidaily.com/a-comprehensive-guide-restoring-your-whatsapp-messages-with-windows-11/"><u>A Comprehensive Guide: Restoring Your WhatsApp Messages with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/adjusting-windows-preferences-under-company-managed-settings-restrictions/"><u>Adjusting Windows Preferences Under Company-Managed Settings Restrictions</u></a></li>
<li><a href="https://common-error.techidaily.com/end-usb-malfunctions-learn-how-to-resolve-persistent-device-not-recognized-alerts/"><u>End USB Malfunctions! Learn How to Resolve Persistent 'Device Not Recognized' Alerts</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correctly-restart-applications-after-encountering-0xc0-growererror-code/"><u>How to Correctly Restart Applications After Encountering 0xC0 growerError Code</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-does-life360-notify-when-you-log-out-on-honor-x8b-drfone-by-drfone-virtual-android/"><u>In 2024, Does Life360 Notify When You Log Out On Honor X8b? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-netflix-location-to-get-more-country-version-on-oppo-find-x7-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Netflix Location to Get More Country Version On Oppo Find X7 Ultra | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/locked-out-of-iphone-12-pro-max-5-ways-to-get-into-a-locked-iphone-12-pro-max-by-drfone-ios/"><u>Locked Out of iPhone 12 Pro Max? 5 Ways to get into a Locked iPhone 12 Pro Max</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-rockstar-games-red-dead-redemption-2-memory-error-by-boosting-page-file/"><u>Resolve Rockstar Games' Red Dead Redemption 2 Memory Error by Boosting Page File</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-puzzling-windows-update-error-code-0x8007001f/"><u>Resolving the Puzzling Windows Update Error Code 0X8007001F</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-when-your-windows-7-cant-grab-those-newest-updates/"><u>Solution Steps for When Your Windows 7 Can't Grab Those Newest Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-chrome-cache-miss-error-errcachemiss-a-step-by-step-guide/"><u>Solving the Chrome Cache Miss Error (ERR_CACHE_MISS): A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-disappeared-desktop-icons-in-windows-10-a-step-by-step-resolution/"><u>Winning the Battle Against Disappeared Desktop Icons in Windows 10 – A Step-by-Step Resolution</u></a></li>
</ul></div>

