---
title: Resolving Your System's Diagnostics Policy Service Problem Today
date: 2024-08-15T11:08:23.859Z
updated: 2024-08-16T11:08:23.859Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Your System's Diagnostics Policy Service Problem Today
excerpt: This Article Describes Resolving Your System's Diagnostics Policy Service Problem Today
thumbnail: https://thmb.techidaily.com/8dc1e121faf37e853cf5b4a2c9e429100f4acf86a44ca231431cd5b1e8fdd239.jpg
---

## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1095219&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-20_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Advanced.png" border="0"></a>
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
<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398457/3022" target="_top" id="398457"><img src="//a.impactradius-go.com/display-ad/3022-398457" border="0" alt="www.sentrypc.com" width="980" height="120"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398457/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4615471&QTY=1&AFFILIATE=108875&CART=1"><img src="https://images.wondershare.com/affiliate-image/affiliate_banners_en/max_782x90.png" border="0"></a>
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

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254762&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/11_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=12653853&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bcb41ccdc4363c6848a1d760f26c28a0/products/14_videoproc-converter-ai-box.png" border="0"></a>
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)
<!-- affiliate ads begin -->
<a href="https://funwhole.sjv.io/c/5597632/1702887/17189" target="_top" id="1702887"><img src="//a.impactradius-go.com/display-ad/17189-1702887" border="0" alt="" width="1000" height="1000"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1702887/17189" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-record-videos.techidaily.com/new-2024-approved-10-key-tactics-to-amplify-your-youtube-presence-and-engagement/"><u>[New] 2024 Approved  10 Key Tactics to Amplify Your YouTube Presence and Engagement</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-accelerate-channels-youtubes-top-collaborative-growth-tips-for-2024/"><u>[New] Accelerate Channels  YouTube's Top Collaborative Growth Tips for 2024</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/new-cutting-edge-techniques-for-private-yt-content-dissemination-in-gmail/"><u>[New] Cutting-Edge Techniques for Private YT Content Dissemination in Gmail</u></a></li>
<li><a href="https://youtube-web.techidaily.com/n-2024-keywords-that-catapult-hashtag-hacks-in-gameplay-videos/"><u>[New] In 2024, Keywords that Catapult  Hashtag Hacks in Gameplay Videos</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/new-laughter-ledger-twittersphere-tales/"><u>[New] Laughter Ledger  Twittersphere Tales</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-set-a-unique-tiktok-sound-as-your-cellphone-alarm-or-ringtone/"><u>[New] Set a Unique TikTok Sound as Your Cellphone Alarm or Ringtone</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-transform-your-snap-game-with-these-top-tips-for-2024/"><u>[New] Transform Your Snap Game with These Top Tips for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-2024-approved-the-experts-guide-to-interactive-instagram-stories-polling/"><u>[Updated] 2024 Approved  The Expert's Guide to Interactive Instagram Stories Polling</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-filmmaking-made-simple-a-smartphone-guide-to-youtube-thumbnails-for-2024/"><u>[Updated] Filmmaking Made Simple  A Smartphone Guide to YouTube Thumbnails for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-the-ultimate-guide-to-trending-hashtags-on-instagram/"><u>[Updated] In 2024, The Ultimate Guide to Trending Hashtags on Instagram</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-making-waves-in-popularity-how-to-earn-vimeo-writers-picks/"><u>[Updated] Making Waves in Popularity  How to Earn Vimeo' Writers’ Picks</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-the-ultimate-guide-to-purging-youtube-videos/"><u>[Updated] The Ultimate Guide to Purging YouTube Videos</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-top-10plus-instagram-content-downloaders-reviewed-for-2024/"><u>[Updated] Top 10+ Instagram Content Downloaders Reviewed for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-revolutionizing-game-soundscapes-with-ps-console-tweaks/"><u>2024 Approved  Revolutionizing Game Soundscapes with PS Console Tweaks</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202086275-activated-safeguard-alert-enable-all-security-measures-immediately/"><u>Activated Safeguard Alert: Enable All Security Measures Immediately</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208499139-address-counterarguments-eg-some-may-argue-that-not-all-problems-require-a-solution-and-discredit-them-using-compelling-evidence/"><u>Address Counterarguments (E.g., some May Argue that Not All Problems Require a Solution) and Discredit Them Using Compelling Evidence</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-destiny-2-stuck-screen-with-these-easy-to-follow-tips/"><u>Beat Destiny 2 Stuck Screen with These Easy-to-Follow Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-the-miracast-not-supported-by-this-device-hurdle-proven-techniques/"><u>Bypass the 'Miracast Not Supported by This Device' Hurdle : Proven Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-to-eliminate-livekernelevent-error-number-144/"><u>Complete Guide to Eliminate LiveKernelEvent Error Number 144</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-dell-laptops-experiencing-a-black-display/"><u>Comprehensive Fixes for Dell Laptops Experiencing a Black Display</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-music-from-hot-40i-by-fonelab-android-recover-music/"><u>Easy steps to recover deleted music from Hot 40i</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209054213-easy-ways-to-fix-error-code-0x80070002-during-windows-system-updates-now/"><u>Easy Ways to Fix Error Code 0X80070002 During Windows System Updates - Now</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-117-unraveled-livekernelevent-troubleshooting-strategies/"><u>Error Code 117 Unraveled: LiveKernelEvent Troubleshooting Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-5-in-minecraft-diagnosis-and-repair-techniques/"><u>Error Code 5 in Minecraft: Diagnosis and Repair Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-strategies-to-overcome-the-livekernelevent-issue-code-117/"><u>Expert Strategies to Overcome the 'LiveKernelEvent' Issue Code 117</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/exploring-the-mobvoi-ticwatch-pro-4g-a-comprehensive-review-for-tech-enthusiasts/"><u>Exploring the Mobvoi Ticwatch Pro 4G: A Comprehensive Review for Tech Enthusiasts</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-fatal-installation-errors-a-step-by-step-solution-to-error-1603/"><u>Fixing Fatal Installation Errors – A Step-by-Step Solution to Error 1603</u></a></li>
<li><a href="https://common-error.techidaily.com/forza-horizon-4-players-rejoice-silent-gameplay-issue-now-fixed-with-crystal-clear-sounds/"><u>Forza Horizon 4 Players Rejoice! Silent Gameplay Issue Now Fixed with Crystal Clear Sounds</u></a></li>
<li><a href="https://common-error.techidaily.com/halo-4-unreal-engine-problem-solving-guide-fixing-the-fatal-errors-of-2024-release/"><u>Halo 4 Unreal Engine Problem-Solving Guide: Fixing the Fatal Errors of 2024 Release</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-deal-with-the-oppo-a1-5g-screen-black-but-still-works-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How To Deal With the Oppo A1 5G Screen Black But Still Works? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207579246-how-to-restore-vanished-desktop-icons-in-your-windows-10-system-solution-inside/"><u>How to Restore Vanished Desktop Icons in Your Windows 10 System - SOLUTION Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-address-and-rectify-red-screen-malfunctions/"><u>How to Successfully Address and Rectify Red Screen Malfunctions</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-iphone-x-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>In 2024, How to Unlock iPhone X When We Dont Have Apple ID or Password?</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/kootek-laptop-cooler-evaluation-an-excellent-choice-for-optimal-performance/"><u>Kootek Laptop Cooler Evaluation: An Excellent Choice for Optimal Performance</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-connectivity-configuring-network-discovery-features-on-windows-11-systems/"><u>Mastering Connectivity: Configuring Network Discovery Features on Windows 11 Systems</u></a></li>
<li><a href="https://win-howtos.techidaily.com/optimizing-visual-output-fix-unsupported-time-codes-in-your-current-monitor-setup/"><u>Optimizing Visual Output - Fix Unsupported Time Codes in Your Current Monitor Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-error-code-0x800f0831-instantly-through-windows-update-troubleshooting/"><u>Overcome Error Code 0X800f0831 Instantly Through Windows Update Troubleshooting</u></a></li>
<li><a href="https://extra-hints.techidaily.com/premium-apps-for-perfectly-altered-videos-on-ios-and-desktop/"><u>Premium Apps for Perfectly Altered Videos on iOS & Desktop</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-high-cpu-issues-with-optimal-windows-drivers-foundation-configurations/"><u>Resolving High CPU Issues with Optimal Windows Drivers Foundation Configurations</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-network-connection-issues-in-dragon-ball-fighterz-gameplay/"><u>Resolving Network Connection Issues in Dragon Ball FighterZ Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-issue-of-corrupted-or-lost-d3dcompiler47dll-on-your-pc/"><u>Resolving the Issue of Corrupted or Lost D3DCOMPILER_47.dll on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-for-correcting-system-event-notifier-connection-issues-on-windows/"><u>Solution Steps for Correcting System Event Notifier Connection Issues on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/speedy-remedies-to-enhance-your-keyboards-response-time/"><u>Speedy Remedies to Enhance Your Keyboard's Response Time</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-vanishing-mouse-cursors-under-windows-11-step-by-step-instructions/"><u>The Ultimate Fix for Vanishing Mouse Cursors Under Windows 11 - Step-by-Step Instructions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-inability-of-application-to-launch-correctly-error-0xc000007b/"><u>Troubleshooting and Fixing the Inability of Application to Launch Correctly [Error 0XC000007B]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-line-distortion-on-pc-screens/"><u>Troubleshooting and Repairing Line Distortion on PC Screens</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-stabilizing-your-gameplay-for-monster-hunter-world-on-pc/"><u>Troubleshooting Guide: Stabilizing Your Gameplay for Monster Hunter World on PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-nonfunctioning-camera-on-lenovo-computers-expert-advice/"><u>Troubleshooting the Nonfunctioning Camera on Lenovo Computers - Expert Advice</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-eliminating-windows-11s-dark-display-dilemma/"><u>Troubleshooting Tips: Eliminating Windows 11'S Dark Display Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-how-to-overcome-the-unable-to-connect-issue-error-0x80072fed-in-windows-10/"><u>Troubleshooting Tips: How to Overcome the 'Unable To Connect' Issue (Error 0X80072FED) in Windows 10</u></a></li>
</ul></div>
