---
title: Effective Solutions for Resolving I/O Device Malfunctions
date: 2024-09-26T00:22:50.771Z
updated: 2024-09-26T16:10:09.794Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effective Solutions for Resolving I/O Device Malfunctions
excerpt: This Article Describes Effective Solutions for Resolving I/O Device Malfunctions
thumbnail: https://thmb.techidaily.com/a6603b4c8e64882a75258ea91034b33184d3edc319264524a7b728bfe67ef7f7.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

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

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151892/7443" target="_top" id="2151892">
  <img src="//a.impactradius-go.com/display-ad/7443-2151892" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151892/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Run the Network Diagnostics and see if it goes well.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037335/7443" target="_top" id="2037335">
  <img src="//a.impactradius-go.com/display-ad/7443-2037335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037335/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036486/19272" target="_top" id="2036486">
  <img src="//a.impactradius-go.com/display-ad/19272-2036486" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036486/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925565/19272" target="_top" id="1925565">
  <img src="//a.impactradius-go.com/display-ad/19272-1925565" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925565/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/new-unidentified-user-strategies-for-accessing-instagram-stories-on-desktopmobile-for-2024/"><u>[New] Unidentified User Strategies for Accessing Instagram Stories on Desktop/Mobile for 2024</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-in-2024-intuitive-guide-how-to-capture-on-vimeo/"><u>[Updated] In 2024, Intuitive Guide How to Capture on Vimeo</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-link-it-up-sharing-youtube-on-ig-snapshots/"><u>[Updated] Link It Up! Sharing YouTube on IG Snapshots</u></a></li>
<li><a href="https://sound-issues.techidaily.com/anthem-sound-problems-in-windows-11-troubleshooting-steps-to-recover-audio/"><u>Anthem Sound Problems in Windows 11: Troubleshooting Steps to Recover Audio</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-win-10s-update-hurdle-fixes-for-error-code-0x800f0922-in-8-steps/"><u>Beat Win 10'S Update Hurdle: Fixes for Error Code 0X800F0922 in 8 Steps</u></a></li>
<li><a href="https://solve-news.techidaily.com/descriptif-complet-comment-decoder-avec-succes-les-dvd-sur-macos-pour-une-experience-de-visionnage-privilegiee/"><u>Descriptif Complet : Comment Décoder Avec Succès Les DVD Sur macOS Pour Une Expérience De Visionnage Privilégiée</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-resolve-no-bootable-device-found-on-your-laptop-or-pc/"><u>Expert Tips to Resolve 'No Bootable Device Found' On Your Laptop or PC</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-audio-issues-a-guide-to-resolving-sound-cuts-in-your-logitech-g930-headset/"><u>Fixing Audio Issues: A Guide to Resolving Sound Cuts in Your Logitech G930 Headset</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-crash-alert-aw-snap-when-using-google-chrome/"><u>Fixing Crash Alert 'Aw, Snap!' When Using Google Chrome</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-vivo-s18e-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Vivo S18e? | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-realme-c53-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Realme C53 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-computer-keeps-freezing-issues/"><u>How To Fix Computer Keeps Freezing Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-issue-of-svchostexe-causing-high-cpu-usage-on-your-windows-10-pc-guide/"><u>How to Resolve the Issue of svchost.exe Causing High CPU Usage on Your Windows 10 PC [Guide]</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-podcasting-tech-updates-unveiled/"><u>In 2024, Podcasting Tech Updates Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-of-vanishing-mouse-pointer-in-windows-10/"><u>Resolving the Issue of Vanishing Mouse Pointer in Windows 10</u></a></li>
</ul></div>

