---
title: Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643
date: 2024-09-04T20:22:02.231Z
updated: 2024-09-05T20:22:02.231Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643
excerpt: This Article Describes Solving the Mystery of 'Windows Update Failed' - Understanding and Fixing Error Code 0X80070643
thumbnail: https://thmb.techidaily.com/7989d193b701c6c4112afd659656de357f20d61f1ee9fa4b40235e3cbfd62f11.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-taking-screenshots-on-chromebook-4-methods/"><u>[New] 2024 Approved  Taking Screenshots on Chromebook [4 Methods]</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-explore-exceptional-economically-priced-asmr-gear/"><u>[New] Explore Exceptional, Economically-Priced ASMR Gear</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-key-screen-snapping-programs-for-content-sharing/"><u>[New] Key Screen-Snapping Programs for Content Sharing</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-superior-text-tools-and-after-effects/"><u>[New] Superior Text Tools & After Effects</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-master-the-art-of-backup-phones-camera-roll-upload-to-social-apps/"><u>[Updated] 2024 Approved  Master the Art of Backup  Phone's Camera Roll Upload to Social Apps</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-best-camera-for-videos-mirrorless-vs-dslr-showdown/"><u>[Updated] In 2024, Best Camera for Videos  Mirrorless Vs. DSLR Showdown</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-harnessing-the-hype-how-to-hike-your-youtube-horde/"><u>2024 Approved  Harnessing the Hype  How to Hike Your Youtube Horde</u></a></li>
<li><a href="https://howto.techidaily.com/app-wont-open-on-your-realme-gt-5-pro-here-are-all-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>App Wont Open on Your Realme GT 5 Pro? Here Are All Fixes | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-resolving-missing-binkw32dll-errors-successfully/"><u>Comprehensive Guide: Resolving Missing BinkW32.dll Errors Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-disabled-shortcut-keys-on-your-laptopdesktop-pc/"><u>Dealing with Disabled Shortcut Keys on Your Laptop/Desktop PC</u></a></li>
<li><a href="https://common-error.techidaily.com/decode-and-defeat-the-windows-10-0x80072efd-error-easily/"><u>Decode and Defeat the Windows 10 0X80072EFD Error Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-call-of-duty-wwii-error-code-4220-expert-tips-and-tricks/"><u>Diagnosing and Repairing Call of Duty WWII Error Code 4220: Expert Tips & Tricks</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/easy-steps-on-how-to-create-a-new-apple-id-account-on-apple-iphone-8-drfone-by-drfone-ios/"><u>Easy Steps on How To Create a New Apple ID Account On Apple iPhone 8 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/error-1603-decoded-strategies-for-a-successful-software-installation-fix/"><u>Error 1603 Decoded: Strategies for a Successful Software Installation Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-how-to-restore-connection-to-a-disconnected-external-hardware-on-windows/"><u>Expert Guide: How to Restore Connection to a Disconnected External Hardware on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-handling-directory-does-not-exist-errors-successfully/"><u>Expert Tips for Handling 'Directory Does Not Exist' Errors Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-effortlessly-overcoming-the-crimson-screen-dilemma-on-any-system/"><u>Expert Tips: Effortlessly Overcoming the Crimson-Screen Dilemma on Any System</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-restoring-your-pcs-built-in-camera-functionality-on-windows-systems/"><u>Expert Tips: Restoring Your PC's Built-In Camera Functionality on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-volume-icon-missing-on-windows-10-with-pictures/"><u>Fix Volume Icon Missing on Windows 10 [with Pictures]</u></a></li>
<li><a href="https://common-error.techidaily.com/get-back-in-the-game-solving-common-issues-with-minecrafts-lan-setup/"><u>Get Back in the Game: Solving Common Issues with Minecraft's LAN Setup</u></a></li>
<li><a href="https://techidaily.com/how-to-downgrade-apple-iphone-xs-max-to-the-previous-ios-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade Apple iPhone XS Max to the Previous iOS Version? | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-quickly-solve-the-d3d-graphics-error-errgfxd3dinit-in-your-gta-v-gameplay-experience/"><u>How to Quickly Solve the D3D Graphics Error (ERR_GFX_D3D_INIT) in Your GTA V Gameplay Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-audio-problems-in-windows-107-fix-crackling-sounds/"><u>How to Troubleshoot Audio Problems in Windows 10/7 – Fix Crackling Sounds</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/hp-laptop-tips-for-perfect-screen-recordings/"><u>HP Laptop Tips for Perfect Screen Recordings</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-tecno-camon-20-pro-5g-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from Tecno Camon 20 Pro 5G Phones with/without a PC</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-14-plus-with-a-mask-on-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 14 Plus with a Mask On</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-looking-for-a-location-changer-on-motorola-edge-40-neo-look-no-further-drfone-by-drfone-virtual-android/"><u>In 2024, Looking For A Location Changer On Motorola Edge 40 Neo? Look No Further | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-personalizing-your-android-a-step-by-step-guide-to-ringtone-and-sound-settings/"><u>In 2024, Personalizing Your Android  A Step-by-Step Guide to Ringtone & Sound Settings</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-preeminent-6-networks-driving-biz-innovation/"><u>In 2024, Preeminent 6 Networks Driving Biz Innovation</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-the-top-5-android-apps-that-use-fingerprint-sensor-to-lock-your-apps-on-realme-c55-by-drfone-android/"><u>In 2024, The Top 5 Android Apps That Use Fingerprint Sensor to Lock Your Apps On Realme C55</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-things-you-should-know-when-unlocking-total-wireless-of-iphone-6s-plus-by-drfone-ios/"><u>In 2024, Things You Should Know When Unlocking Total Wireless Of iPhone 6s Plus</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-top-10-strategies-for-accessing-nfl-games-online/"><u>In 2024, Top 10 Strategies for Accessing NFL Games Online</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-your-screens-brightness-blues-fixes-for-windows-10-problems/"><u>Overcome Your Screen’s Brightness Blues: Fixes for Windows 10 Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-keeps-showing-up-hurdle-solving-constant-usb-device-errors/"><u>Overcoming the 'Keeps Showing Up' Hurdle: Solving Constant USB Device Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-windows-11-touchscreen-problems-quickly-using-this-5-part-strategy/"><u>Resolve Windows 11 Touchscreen Problems Quickly Using This 5-Part Strategy</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-copy-paste-problems-in-windows-11-a-comprehensive-guide/"><u>Resolving Copy-Paste Problems in Windows 11 – A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10s-bluetooth-pairing-woes-expert-advice-and-strategies/"><u>Resolving Windows 10'S Bluetooth Pairing Woes: Expert Advice and Strategies</u></a></li>
<li><a href="https://fix-guide.techidaily.com/simple-solutions-to-fix-android-systemui-has-stopped-error-for-huawei-p60-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Simple Solutions to Fix Android SystemUI Has Stopped Error For Huawei P60 | Dr.fone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/snapchats-money-making-opportunities-exposed-for-2024/"><u>Snapchat's Money-Making Opportunities Exposed for 2024</u></a></li>
<li><a href="https://win-forum.techidaily.com/social-media-powerhouses-unveiled-exploring-facebook-twitter-instagram-and-youtube-dynamics/"><u>Social Media Powerhouses Unveiled: Exploring Facebook, Twitter, Instagram and Youtube Dynamics</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-overcome-the-preparing-to-configure-windows-hurdle-easily/"><u>Solution Found! Overcome the 'Preparing to Configure Windows' Hurdle Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-windows-11-sound-problems-mastering-the-volume-settings-restoration/"><u>Solve Your Windows 11 Sound Problems - Mastering the Volume Settings Restoration</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/solving-issues-with-unresponsive-optical-drives-a-step-by-step-guide/"><u>Solving Issues with Unresponsive Optical Drives: A Step-by-Step Guide</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/sparkle-on-screen-ideal-tools-for-online-videos-for-2024/"><u>Sparkle on Screen  Ideal Tools for Online Videos for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fixing-lack-of-sound-device-detection-in-windows-11/"><u>Step-by-Step Guide: Fixing Lack of Sound Device Detection in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/the-step-by-step-process-to-correct-failed-to-finish-writing-in-steam/"><u>The Step-by-Step Process to Correct 'Failed To Finish Writing' In Steam</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-easytime-timer-solutions-at-zero-cost-for-2024/"><u>Top EasyTime Timer Solutions at Zero Cost for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixtools-registration-error-in-windows-11/"><u>Troubleshooting FixTool's Registration Error in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-dll-runtime-140-not-found-issue/"><u>Troubleshooting Guide for 'DLL Runtime 140 Not Found' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-night-light-doesnt-work-on-windows-10-and-11-systems/"><u>Troubleshooting: Night Light Doesn't Work on Windows 10 and 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-crc-cyclical-data-integrity-issues/"><u>Understanding and Resolving CRC Cyclical Data Integrity Issues</u></a></li>
<li><a href="https://tech-haven.techidaily.com/unlocking-the-full-potential-of-chatgpt-for-a-better-lifestyle/"><u>Unlocking the Full Potential of ChatGPT for a Better Lifestyle</u></a></li>
<li><a href="https://common-error.techidaily.com/victory-for-wow-enabling-comprehensive-3d-graphics/"><u>Victory for WoW: Enabling Comprehensive 3D Graphics</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-bluetooth-problems-a-step-by-step-guide-to-detecting-devices-easily/"><u>Windows 10 Bluetooth Problems? A Step-by-Step Guide to Detecting Devices Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-continuous-automatic-repairs-in-windows-11-top-fixes/"><u>Winning the Battle Against Continuous Automatic Repairs in Windows #11: Top Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/xbox-ones-joystick-pc-compatibility-triumph/"><u>Xbox One's Joystick: PC Compatibility Triumph</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902324/19272" target="_top" id="1902324">
  <img src="//a.impactradius-go.com/display-ad/19272-1902324" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902324/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->