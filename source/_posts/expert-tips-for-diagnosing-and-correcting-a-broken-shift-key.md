---
title: Expert Tips for Diagnosing and Correcting a Broken Shift Key
date: 2024-09-04T20:24:51.143Z
updated: 2024-09-05T20:24:51.143Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips for Diagnosing and Correcting a Broken Shift Key
excerpt: This Article Describes Expert Tips for Diagnosing and Correcting a Broken Shift Key
thumbnail: https://thmb.techidaily.com/4a9b602cddaa14e95b4c74e25b7d2e53d393546d813f68c2847153dd0769193c.jpg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1972684/19272" target="_top" id="1972684">
  <img src="//a.impactradius-go.com/display-ad/19272-1972684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1972684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123740/7443" target="_top" id="2123740">
  <img src="//a.impactradius-go.com/display-ad/7443-2123740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
<!-- affiliate ads begin -->
<span id="1938136">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938136.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938136">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938136.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938136%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938136/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.
<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Restart your computer to see if the error has gone.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012406/19272" target="_top" id="2012406">
  <img src="//a.impactradius-go.com/display-ad/19272-2012406" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012406/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

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
<li><a href="https://youtube-web.techidaily.com/ed-in-2024-unveiling-the-secrets-of-mobile-monetization-on-youtube-for-creators/"><u>[Updated] In 2024, Unveiling the Secrets of Mobile Monetization on YouTube for Creators</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-laugh-out-loud-and-weepy-instagrams-best-meme-communities-for-2024/"><u>[Updated] Laugh Out Loud & Weepy  Instagram's Best Meme Communities for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/2024-approved-clash-of-shadows-and-lightning-black-vs-silver/"><u>2024 Approved  Clash of Shadows and Lightning  BLACK vs SILVER</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-screencast-insights-101-key-concepts-for-video-creators/"><u>2024 Approved  Screencast Insights 101  Key Concepts for Video Creators</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-top-iphone-hacks-for-capturing-stunning-skyline-shots/"><u>2024 Approved  Top iPhone Hacks for Capturing Stunning Skyline Shots</u></a></li>
<li><a href="https://common-error.techidaily.com/conquering-error-code-0x80070643-effective-solutions-for-windows-updateinstallation-failures/"><u>Conquering Error Code 0X80070643: Effective Solutions for Windows Update/Installation Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-steps-for-unresponsive-usb-hdmi-interface-cable/"><u>DIY Repair Steps for Unresponsive USB HDMI Interface Cable</u></a></li>
<li><a href="https://common-error.techidaily.com/effortlessly-overcome-csgo-crashing-issues-with-these-proven-fixes/"><u>Effortlessly Overcome CS:GO Crashing Issues with These Proven Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/error-message-volume-damaged-0x80071ac3-troubleshooting-steps-for-recovery/"><u>Error Message: Volume Damaged (0X80071AC3) - Troubleshooting Steps for Recovery</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-solution-for-overcoming-errors-disrupting-your-applications-functionality/"><u>Expert Solution for Overcoming Errors Disrupting Your Application’s Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-repairing-there-was-a-problem-boot-failures-on-your-windows-eighteen-machine/"><u>Expert Tips for Repairing ‘There Was a Problem’ Boot Failures on Your Windows Eighteen Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-failed-to-update-warframe-issue-a-comprehensive-guide/"><u>Fixing the 'Failed to Update Warframe' Issue – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-correcting-device-not-detected-in-windows-operating-systems-understanding-error-code-24/"><u>Guide to Correcting 'Device Not Detected' In Windows Operating Systems: Understanding Error Code 24</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-failed-windows-10-version-1903-updates-successfully/"><u>How to Fix Failed Windows 10 Version 1903 Updates Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-updates-stalled-on-99-or-100-solved/"><u>How to Fix Windows Updates Stalled on 99 or 100%% - Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-tackle-windows-update-error-0x80070002-for-smooth-operations/"><u>How to Successfully Tackle Windows Update Error 0X80070002 for Smooth Operations</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-non-charging-devices-in-windows-7-and-10-systems/"><u>How to Troubleshoot Non-Charging Devices in Windows 7 and 10 Systems</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-3-ways-to-change-location-on-facebook-marketplace-for-meizu-21-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Ways to Change Location on Facebook Marketplace for Meizu 21 Pro | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-show-wi-fi-password-on-vivo-y02t-by-drfone-android/"><u>In 2024, How to Show Wi-Fi Password on Vivo Y02T</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-learn-to-flip-videos-a-guide-for-instagram-users/"><u>In 2024, Learn to Flip Videos  A Guide for Instagram Users</u></a></li>
<li><a href="https://common-error.techidaily.com/include-key-search-terms-ensure-that-high-value-keywords-eg-microsoft-compatibility-telemetry-high-disk-usage-are-prominent-in-your-title-to-improve-visibil27/"><u>Include Key Search Terms: Ensure that High-Value Keywords (E.g., Microsoft Compatibility Telemetry, High Disk Usage) Are Prominent in Your Title to Improve Visibility and Relevance for Those Searching on Related Topics</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-audio-adjustments-overcoming-windows-10s-volume-control-problems/"><u>Mastering Audio Adjustments - Overcoming Windows 10'S Volume Control Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-audio-enhancements-expert-advice-for-clearer-sounds/"><u>Mastering Windows Audio Enhancements – Expert Advice for Clearer Sounds</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-system-recovery-how-sfc-and-dism-restore-windows-10-stability/"><u>Navigating System Recovery: How SFC and DISM Restore Windows 10 Stability</u></a></li>
<li><a href="https://common-error.techidaily.com/optimize-your-pcs-graphics-power-on-windows-11-top-5-strategies-to-tackle-dwms-heavy-gpu-demand/"><u>Optimize Your PC's Graphics Power on Windows 11: Top 5 Strategies to Tackle DWM's Heavy GPU Demand</u></a></li>
<li><a href="https://common-error.techidaily.com/preventing-unprompted-restartboot-issues-essential-fixes-for-windows-operating-systems/"><u>Preventing Unprompted Restart/Boot Issues: Essential Fixes for Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-to-audio-output-troubleshooting-in-windows-11-systems/"><u>Quick Solutions to Audio Output Troubleshooting in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-your-windows-stores-cached-data-a-guide/"><u>Resolving Issues with Your Windows Store's Cached Data – A Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-computers-freeze-frame-repairing-a-laptops-unresponsive-input-device/"><u>Revive Your Computer’s Freeze-Frame: Repairing a Laptop's Unresponsive Input Device</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-dealing-with-a-hanging-google-chrome-window/"><u>Solution Guide: Dealing with a Hanging Google Chrome Window</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-dell-camera-problems-quickly-for-windows-users/"><u>Solve Dell Camera Problems Quickly for Windows Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-windows-11-touch-screen-problem-with-these-5-strategies/"><u>Solve Your Windows 11 Touch Screen Problem with These 5 Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-making-invisible-networks-appear-on-windows-11s-wi-fi-list/"><u>Solved: Making Invisible Networks Appear on Windows 11'S Wi-Fi List</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-fix-steam-cannot-write-to-disc-error-swiftly/"><u>Step-by-Step Tips to Fix Steam Cannot Write to Disc Error Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-overcoming-the-windows-10-couldnt-be-installed-error-code-eb80240020-challenge-a-comprehensive-guide/"><u>Successfully Overcoming the 'Windows 10 Couldn't Be Installed (Error Code Eb80240020)' Challenge – A Comprehensive Guide</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/the-best-android-sim-unlock-code-generators-unlock-your-vivo-y56-5g-phone-hassle-free-by-drfone-android/"><u>The Best Android SIM Unlock Code Generators Unlock Your Vivo Y56 5G Phone Hassle-Free</u></a></li>
<li><a href="https://extra-information.techidaily.com/the-convert-kings-playbook-youtube-to-mp4mpeg-edition/"><u>The Convert King's Playbook  YouTube to MP4/MPEG Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/top-8-solutions-overcome-the-persistent-windows-10-update-error-0x800f0922/"><u>Top 8 Solutions: Overcome the Persistent Windows 10 Update Error 0X800F0922</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-correcting-the-unrecoverable-error-1603-during-program-install/"><u>Troubleshooting Guide: Correcting the Unrecoverable Error 1603 During Program Install</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210138834-troubleshooting-guide-fixing-minecraft-lan-connection-issues-quick-solutions/"><u>Troubleshooting Guide: Fixing 'Minecraft LAN Connection Issues' - Quick Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-freezing-issues-during-windows-10-launch/"><u>Troubleshooting Guide: Fixing Freezing Issues During Windows 10 Launch</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/websites-boosted-with-cookiebot-technology/"><u>Websites Boosted with Cookiebot Technology</u></a></li>
<li><a href="https://common-error.techidaily.com/why-cant-i-install-the-latest-features-on-windows-1n-v1607/"><u>Why Can't I Install the Latest Features on Windows 1N V1607?</u></a></li>
</ul></div>
