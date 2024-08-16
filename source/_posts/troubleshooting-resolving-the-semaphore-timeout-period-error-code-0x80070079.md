---
title: "Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079"
date: 2024-08-15T11:09:39.170Z
updated: 2024-08-16T11:09:39.170Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079"
excerpt: "This Article Describes Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079"
thumbnail: https://thmb.techidaily.com/8a54b5f3957881ee85a4e67f8767270bede7bd83bce45614963bc600bb3e8241.jpg
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
  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BGeneral%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/general-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=4729507&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.nero.com/nero-com-wAssets/img/banners/2023/TIU/Nero_TuneItUp_Screen_2.webp" border="0">/a>
<!-- affiliate ads end -->
  
b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
<!-- affiliate ads begin -->
<a href="https://tinyland.pxf.io/c/5597632/1793214/19135" target="_top" id="1793214"><img src="//a.impactradius-go.com/display-ad/19135-1793214" border="0" alt="" width="900" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1793214/19135" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.pcdj.com/order/checkout.php?PRODS=4698998&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/47f4b6321e9fd8e8f7326a6adc1a7c1e/products/MacBook_Pro_lyrx-withsinger-tv.png" border="0">LYRX is an easy-to-use karaoke software with the professional features karaoke hosts need to perform with precision. LYRX is karaoke show hosting software that supports all standard karaoke file types as well as HD video formats, and it’s truly fun to use. 
LYRX Karaoke Software MAC/WINDOWS (Includes Activation For 3 Machines)</a>
<!-- affiliate ads end -->
  
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
<li><a href="https://fox-hovers.techidaily.com/new-2024-approved-assemble-and-build-your-own-google-vr-viewing-device/"><u>[New] 2024 Approved  Assemble and Build Your Own Google VR Viewing Device</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/024-approved-dive-into-the-world-of-expertise-with-youtubes-top-10-makeup-vloggers/"><u>[New] 2024 Approved  Dive Into the World of Expertise with YouTube's Top 10 Makeup Vloggers</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-adventurers-zenith-a-celebration-of-the-best-games-ever-made/"><u>[New] Adventurers' Zenith  A Celebration of the Best Games Ever Made</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-beat-the-bad-guys-top-kung-fu-action-puzzle-games/"><u>[New] In 2024, Beat the Bad Guys  Top Kung Fu Action Puzzle Games</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-diving-deep-into-lyric-video-designs-powered-by-lyric-video-maker/"><u>[New] In 2024, Diving Deep Into Lyric Video Designs, Powered by Lyric Video Maker</u></a></li>
<li><a href="https://fox-links.techidaily.com/2024-approved-revolutionary-rider-helmet-cams-top-picks-for-23/"><u>2024 Approved  Revolutionary Rider Helmet Cams - Top Picks for '23</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-complete-guide-to-adding-powerful-narrations/"><u>2024 Approved  The Complete Guide to Adding Powerful Narrations</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-top-action-capturing-software-guide/"><u>2024 Approved  Top Action-Capturing Software Guide</u></a></li>
<li><a href="https://android-location-track.techidaily.com/3-solutions-to-find-your-nokia-130-music-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>3 Solutions to Find Your Nokia 130 Music Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/accessing-network-drives-through-explorer-pane/"><u>Accessing Network Drives Through Explorer Pane</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-block-mastering-minecraft-error-code-5-solutions/"><u>Beat the Block! Mastering Minecraft Error Code 5 Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/breeze-through-blockages-repair-techniques-for-stalled-0-windows-updates/"><u>Breeze Through Blockages: Repair Techniques for Stalled 0%% Windows Updates</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/comprehensively-reviewing-the-ricoh-theta-s-system-for-2024/"><u>Comprehensively Reviewing the Ricoh Theta S System for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/cracking-down-error-1067-the-process-that-stopped-in-windows-explained-and-fixed/"><u>Cracking Down Error 1067: The Process that Stopped in Windows Explained & Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/directx-troubleshooting-successfully-addressing-unrecoverable-error-scenarios/"><u>DirectX Troubleshooting: Successfully Addressing Unrecoverable Error Scenarios</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-to-overcome-incomplete-windows-updates/"><u>Easy Solutions to Overcome Incomplete Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-troubleshooting-steps-for-repairing-your-lenovos-malfunctioning-fingerprint-scanner/"><u>Easy Troubleshooting Steps for Repairing Your Lenovo's Malfunctioning Fingerprint Scanner</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-non-responsive-lenovo-mouse-pads-in-various-windows-versions/"><u>Effective Solutions for Non-Responsive Lenovo Mouse Pads in Various Windows Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-fixes-for-the-persistent-restart-problem-in-windows-11/"><u>Effortless Fixes for the Persistent Restart Problem in Windows 11</u></a></li>
<li><a href="https://os-tips.techidaily.com/effortless-steps-to-delete-your-youtube-browsing-and-search-logs/"><u>Effortless Steps to Delete Your YouTube Browsing and Search Logs</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209900034-elaborate-on-how-solving-problems-aids-personal-growth-and-self-reliance/"><u>Elaborate on How Solving Problems Aids Personal Growth and Self-Reliance</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208725532-google-chrome-blackout-heres-how-to-restore-your-browsers-display/"><u>Google Chrome Blackout? Here's How to Restore Your Browser's Display!</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-your-lenovo-mouse-pad-functionality-across-all-windows-versions/"><u>Guide to Restoring Your Lenovo Mouse Pad Functionality Across All Windows Versions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/how-does-the-iphone-15-fare-against-water-unpacking-its-ip-rating/"><u>How Does the iPhone 15 Fare Against Water? Unpacking Its IP Rating</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-corrupted-windows-store-database-a-complete-guide/"><u>How to Fix a Corrupted Windows Store Database - A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-your-aoc-monitors-functionality-on-a-windows-11-system/"><u>How to Restore Your AOC Monitor's Functionality on a Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/identifying-and-rectifying-self-starting-behavior-on-your-windows-10-device/"><u>Identifying & Rectifying Self-Starting Behavior on Your Windows 10 Device</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-all-you-need-to-know-about-mega-greninja-for-motorola-moto-g73-5g-drfone-by-drfone-virtual-android/"><u>In 2024, All You Need To Know About Mega Greninja For Motorola Moto G73 5G | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-constructing-a-high-definition-pc-for-ultra-hd-video-production/"><u>In 2024, Constructing a High-Definition PC for Ultra-HD Video Production</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-sony-xperia-5-v-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Sony Xperia 5 V | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-to-remove-flashlight-from-iphone-xr-lock-screen-drfone-by-drfone-ios/"><u>In 2024, How To Remove Flashlight From iPhone XR Lock Screen | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-masterful-podcast-descriptions-strategies-and-case-studies/"><u>In 2024, Masterful Podcast Descriptions  Strategies and Case Studies</u></a></li>
<li><a href="https://article-posts.techidaily.com/in-2024-preserving-the-past-a-comprehensible-process-of-photograph-digitization/"><u>In 2024, Preserving the Past  A Comprehensible Process of Photograph Digitization</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-still-using-pattern-locks-with-realme-11-pro-tips-tricks-and-helpful-advice-by-drfone-android/"><u>In 2024, Still Using Pattern Locks with Realme 11 Pro? Tips, Tricks and Helpful Advice</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-tapping-into-youtubes-affiliate-income-streams/"><u>In 2024, Tapping Into YouTube's Affiliate Income Streams</u></a></li>
<li><a href="https://common-error.techidaily.com/no-more-freezing-expert-tips-for-troubleshooting-nier-automata-pc-bugs/"><u>No More Freezing: Expert Tips for Troubleshooting Nier: Automata PC Bugs</u></a></li>
<li><a href="https://win-blog.techidaily.com/overcoming-launch-problems-for-armored-core-vi-fires-of-rubicon/"><u>Overcoming Launch Problems for Armored Core VI: Fires of Rubicon</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-hp-laptops-camera-wont-work-with-windows-11/"><u>Quick Fixes for When Your HP Laptop's Camera Won't Work with Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-to-overcoming-cannot-complete-installation-on-windows/"><u>Quick Guide to Overcoming 'Cannot Complete Installation' On Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-problem-occurred-while-rebooting-error-in-windows-10/"><u>Resolving the 'Problem Occurred While Rebooting' Error in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204570284-smooth-gameplay-on-demand-no-trouble/"><u>Smooth Gameplay on Demand, No Trouble</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reviving-the-scroll-wheel-in-a-malfunctioning-logitech-mouse/"><u>Step-by-Step Guide: Reviving the Scroll Wheel in a Malfunctioning Logitech Mouse</u></a></li>
<li><a href="https://buynow-info.techidaily.com/step-by-step-guide-upgrading-your-computers-graphics-card/"><u>Step-by-Step Guide: Upgrading Your Computer's Graphics Card</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-resolve-windows-11-update-error-code-0x80e705b4/"><u>Step-by-Step Solutions to Resolve Windows 11 Update Error Code 0X80e705B4</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/streaming-tweets-on-whatsapp-a-2023-guide-for-2024/"><u>Streaming Tweets on WhatsApp  A 2023 Guide for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/super-easy-ways-to-deal-with-tecno-spark-10-4g-unresponsive-screen-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Super Easy Ways To Deal with Tecno Spark 10 4G Unresponsive Screen | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/the-role-of-msda80dll-in-your-system-do-you-need-to-retain-it/"><u>The Role of MSDA80.DLL in Your System - Do You Need to Retain It?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-resolving-disappeared-desktop-icon-issues-in-win10/"><u>Troubleshooting and Resolving Disappeared Desktop Icon Issues in Win10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-flash-content-failures-in-google-chrome-a-comprehensive-guide/"><u>Troubleshooting Flash Content Failures in Google Chrome: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-intermittent-wireless-mouse-failures-in-windows-1110/"><u>Troubleshooting Guide: Fixing Intermittent Wireless Mouse Failures in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-windows-11-update-error-code-0x80240034/"><u>Troubleshooting Guide: Resolving Windows 11 Update Error Code 0X80240034</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-cxfreeze-catastrophic-failures-with-ease/"><u>Troubleshooting Guide: Solving Cx_Freeze Catastrophic Failures with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-restoring-access-to-remotely-located-servers/"><u>Troubleshooting Tips for Restoring Access to Remotely Located Servers</u></a></li>
<li><a href="https://common-error.techidaily.com/wd-my-passport-ultra-not-showing-up-in-device-manager-solutions-to-try/"><u>WD My Passport Ultra Not Showing Up in Device Manager – Solutions to Try</u></a></li>
<li><a href="https://techtrends.techidaily.com/wireless-ps4-setup-a-comprehensive-walkthrough-on-controller-link-up/"><u>Wireless PS4 Setup: A Comprehensive Walkthrough on Controller Link-Up</u></a></li>
</ul></div>
