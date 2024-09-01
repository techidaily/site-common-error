---
title: Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully
date: 2024-08-31T17:40:48.412Z
updated: 2024-09-01T17:40:48.412Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully
excerpt: This Article Describes Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully
thumbnail: https://thmb.techidaily.com/ac1dc93632b498eb9e341774978ceeb78bceacaece80212cfc98f386a6cd1281.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075461/7443" target="_top" id="2075461"><img src="//a.impactradius-go.com/display-ad/7443-2075461" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075461/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
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
  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42570605&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/usbXcopy/Nero_USB_x_copy_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://article-knowledge.techidaily.com/new-in-2024-futures-finest-the-leading-photo-frame-tools-24/"><u>[New] In 2024, Future's Finest  The Leading Photo Frame Tools '24</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-mastering-video-reversal-on-ios-devices/"><u>[New] Mastering Video Reversal on iOS Devices</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-teleport-into-virtuality-top-10-mobile-vr-headsets-reviewed/"><u>[New] Teleport Into Virtuality  Top 10 Mobile VR Headsets Reviewed</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-in-2024-beginning-to-connect-a-comprehensive-facebook-setup-walkthrough/"><u>[Updated] In 2024, Beginning to Connect  A Comprehensive Facebook Setup Walkthrough</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/1716070125025-updated-in-2024-essential-mac-screen-recorders-top-10-free-list/"><u>[Updated] In 2024, Essential Mac Screen Recorders – Top 10 FREE List!</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-editors-guide-to-flawless-frame-acceleration/"><u>2024 Approved  The Editor's Guide to Flawless Frame Acceleration</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-woes-no-more-a-step-by-step-fix-for-pairing-problems-on-windows-11-insider-tips/"><u>Bluetooth Woes No More: A Step-by-Step Fix for Pairing Problems on Windows 11 - Insider Tips</u></a></li>
<li><a href="https://fake-location.techidaily.com/can-life360-track-or-see-text-messages-what-can-you-do-with-life360-on-oppo-k11-5g-drfone-by-drfone-virtual-android/"><u>Can Life360 Track Or See Text Messages? What Can You Do with Life360 On Oppo K11 5G? | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/cannot-play-mkv-files-on-motorola-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Cannot play MKV files on Motorola</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-issue-detected-monitor-ignores-active-signal-frequency/"><u>Compatibility Issue Detected - Monitor Ignores Active Signal Frequency</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-diagnosing-and-repairing-frozen-movements-in-your-laptop-mouse/"><u>Comprehensive Guide to Diagnosing & Repairing Frozen Movements in Your Laptop Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-restoring-functionality-for-dell-laptop-input-devices/"><u>Diagnosing and Restoring Functionality for Dell Laptop Input Devices</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722074951094-discover-how-to-utilize-openais-revolutionary-gpt-store-beginners-tutorial-inside/"><u>Discover How to Utilize OpenAI's Revolutionary GPT Store - Beginner's Tutorial Inside!</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/discover-the-dell-xps-13-7390-a-review-of-its-sleek-design-and-convertible-features-for-an-outstanding-ultrabook-experience/"><u>Discover the Dell XPS 13 7390: A Review of Its Sleek Design & Convertible Features for an Outstanding Ultrabook Experience</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-top-10-note-taking-solutions-dominating-202n4/"><u>Discover the Top 10 Note Taking Solutions Dominating 202N4</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-techniques-restoring-access-to-your-destiny-2-game-servers/"><u>DIY Repair Techniques: Restoring Access to Your Destiny 2 Game Servers</u></a></li>
<li><a href="https://techtrends.techidaily.com/driving-conversions-through-smart-lead-generation-the-cookiebot-difference/"><u>Driving Conversions Through Smart Lead Generation - The Cookiebot Difference</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-function-keys-fail-to-work-properly/"><u>Effective Solutions for When Function Keys Fail to Work Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-solve-no-signal-detected-monitor-glitches/"><u>Effective Techniques to Solve 'No Signal Detected' Monitor Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-clearing-up-disk-detection-failures-during-a-windows-10-system-reset/"><u>Expert Advice: Clearing Up Disk Detection Failures During a Windows 10 System Reset</u></a></li>
<li><a href="https://win-able.techidaily.com/fallout-3-wont-open-comprehensive-troubleshooting-tips-and-techniques/"><u>Fallout 3 Won't Open? Comprehensive Troubleshooting Tips & Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-troubleshooting-battery-not-recognized-error-solved-effortlessly/"><u>Fast Track Troubleshooting: 'Battery Not Recognized' Error Solved Effortlessly</u></a></li>
<li><a href="https://youtube-help.techidaily.com/fixing-non-appearing-thumbnails-in-youtube-shorts-for-2024/"><u>Fixing Non-Appearing Thumbnails in YouTube Shorts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/gameplay-might-force-a-shutdown/"><u>Gameplay Might Force a Shutdown</u></a></li>
<li><a href="https://common-error.techidaily.com/halo-4-in-unreal-engine-4-fixing-the-persistent-crash-bug-of-2024/"><u>Halo 4 in Unreal Engine 4: Fixing the Persistent Crash Bug of 2024</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-downgrade-iphone-14-plus-to-an-older-ios-system-version-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How to Downgrade iPhone 14 Plus to an Older iOS System Version? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quickly-correct-the-troublesome-windows-update-issue-error-0x80070652/"><u>How to Quickly Correct the Troublesome Windows Update Issue: Error 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-the-broken-spacebar-functionality-in-windows-10-computers/"><u>How to Repair the Broken Spacebar Functionality in Windows 10 Computers</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-how-can-we-bypass-vivo-x-fold-2-frp-by-drfone-android/"><u>In 2024, How Can We Bypass Vivo X Fold 2 FRP?</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-prioritize-these-5-facts-when-tiktoking-on-macos/"><u>In 2024, Prioritize These 5 Facts When TikToking on macOS</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/macdvd-imoviemp4-macx-dvd-converter/"><u>Mac用無料DVD保護解除ツール: IMovie互換MP4への高速変換 - MacX DVD Converter</u></a></li>
<li><a href="https://extra-support.techidaily.com/master-list-of-affordable-websites-boosting-vector-graphics-skills-for-2024/"><u>Master List of Affordable Websites Boosting Vector Graphics Skills for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-twitch-stability-in-depth-fixes-for-overcoming-error-4000/"><u>Mastering Twitch Stability: In-Depth Fixes for Overcoming Error 4000</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/momentum-in-pictures-a-curated-list-of-ig-motivation/"><u>Momentum in Pictures  A Curated List of IG Motivation</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-gameplay-interruptions-stop-your-pc-from-shutting-off-on-any-windows-version/"><u>Overcoming Gameplay Interruptions: Stop Your PC From Shutting Off on Any Windows Version!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-failed-steam-updates-a-comprehensive-guide/"><u>Overcoming the Challenge of Failed Steam Updates: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-xerox-printer-update-error-0x800f020b-step-by-step-fix-for-windows-users/"><u>Overcoming Xerox Printer Update Error 0X800f020b: Step-by-Step Fix for Windows Users</u></a></li>
<li><a href="https://facebook.techidaily.com/privacy-betrayed-key-themes-from-leaked-fb-papers/"><u>Privacy Betrayed: Key Themes From Leaked FB Papers</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-to-restore-bluetooth-functionality-on-windows-10/"><u>Quick Guide to Restore Bluetooth Functionality on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-dead-laptop-battery-fast-and-effortlessly/"><u>Revive Your Dead Laptop Battery Fast & Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-restoring-sounds-in-forza-horizon-4-the-ultimate-guide-to-fixing-audio-issues/"><u>Solved: Restoring Sounds in Forza Horizon 4 – The Ultimate Guide to Fixing Audio Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-no-audio-output-problem-on-your-pc-a-step-by-step-guide/"><u>Solving the 'No Audio Output' Problem on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-repairing-a-windows-boot-failure/"><u>Step-by-Step Solution for Repairing a Windows Boot Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-windows-system-file-missing-error-0xc00000e9/"><u>Step-by-Step Solutions for Windows System File Missing (Error 0xC00000E9)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-overcome-image-troubles-in-windows-11-and-windows-10-environments/"><u>Step-by-Step Solutions to Overcome Image Troubles in Windows 11 and Windows 10 Environments</u></a></li>
<li><a href="https://facebook.techidaily.com/the-secure-way-to-delete-your-facebook-account-android/"><u>The Secure Way to Delete Your Facebook Account (Android)</u></a></li>
<li><a href="https://common-error.techidaily.com/touchpad-troubles-reveal-and-repair-guide-awaits/"><u>Touchpad Troubles? Reveal & Repair Guide Awaits!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-windows-10-install-error-80240020-a-step-by-step-solution/"><u>Troubleshooting Guide for Windows 10 Install Error 80240020: A Step-by-Step Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-a-non-functional-wacom-pen-in-windows-11-and-10/"><u>Troubleshooting Guide: Fixing a Non-Functional Wacom Pen in Windows 11 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-the-host-for-32-bit-print-driver-error-message/"><u>Troubleshooting Guide: Fixing the 'Host for 32-Bit Print Driver' Error Message</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixing-non-functional-brightness-settings-on-windows-10/"><u>Troubleshooting: Fixing Non-Functional Brightness Settings on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-bluetooth-connection-issues-in-windows-11/"><u>Ultimate Guide: Resolving Bluetooth Connection Issues in Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/understanding-the-role-of-a-chatgpt-code-interpreter-its-significance-in-ai/"><u>Understanding the Role of a ChatGPT Code Interpreter: Its Significance in AI</u></a></li>
<li><a href="https://common-error.techidaily.com/unmute-netflix-effortless-fixes-to-bring-back-sound/"><u>Unmute Netflix: Effortless Fixes to Bring Back Sound</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205829204-urgent-fixes-how-to-get-your-laptops-charging-back-on-track/"><u>Urgent Fixes: How to Get Your Laptop's Charging Back on Track!</u></a></li>
<li><a href="https://facebook.techidaily.com/what-happens-to-your-data-if-facebook-ever-dies/"><u>What Happens to Your Data if Facebook Ever Dies?</u></a></li>
</ul></div>
