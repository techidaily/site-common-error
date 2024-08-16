---
title: "Initiating Windows 11 Successfully: Remedies for Persistent Freezing at Startup"
date: 2024-08-15T11:06:18.822Z
updated: 2024-08-16T11:06:18.822Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Initiating Windows 11 Successfully: Remedies for Persistent Freezing at Startup"
excerpt: "This Article Describes Initiating Windows 11 Successfully: Remedies for Persistent Freezing at Startup"
thumbnail: https://thmb.techidaily.com/9929e26ad232462fb3012e528ec110b36cc8e34a7ab835cf659d05f21b4127d5.jpg
---

## Winning Against Windows Update Challenge: Solving Error 0X802n02e Successfully

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

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
<!-- affiliate ads begin -->
<a href="https://estore.winxdvd.com/order/checkout.php?PRODS=4612444&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.winxdvd.com/affiliate/new-banner/pt-728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267"><img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087407/7443" target="_top" id="2087407"><img src="//a.impactradius-go.com/display-ad/7443-2087407" border="0" alt="" width="600" height="500"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
<!-- affiliate ads begin -->
<a href="https://atezr.pxf.io/c/5597632/2018605/18496" target="_top" id="2018605"><img src="//a.impactradius-go.com/display-ad/18496-2018605" border="0" alt="" width="798" height="807"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2018605/18496" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17729331&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner600x500.png" border="0"></a>
<!-- affiliate ads end -->
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2095385/26400" target="_top" id="2095385"><img src="//a.impactradius-go.com/display-ad/26400-2095385" border="0" alt="" width="1024" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2095385/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://common-error.techidaily.com/net-framework-35-setup-error-resolution-how-to-address-and-correct-error-0x800f081f/"><u>.NET Framework 3.5 Setup Error Resolution: How to Address and Correct Error 0X800F081F</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-2024-approved-the-ultimate-guide-to-no-cost-high-quality-srt-editors/"><u>[New] 2024 Approved  The Ultimate Guide to No-Cost, High-Quality Srt Editors</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-in-2024-an-anthology-of-admiration-highlighting-top-10-reddit-threads/"><u>[New] In 2024, An Anthology of Admiration  Highlighting Top 10 Reddit Threads</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-epic-encounters-a-selection-of-supreme-7-total-war-conflicts/"><u>[New] In 2024, Epic Encounters  A Selection of Supreme 7 Total War Conflicts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/uick-turn-artistry-professionally-crafted-valorant-game-imagery/"><u>[New] Quick-Turn Artistry  Professionally Crafted Valorant Game Imagery</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-premier-ios-platforms-for-ps2-gaming/"><u>[Updated] 2024 Approved  Premier iOS Platforms for PS2 Gaming</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-best-practices-to-avoid-missed-frames-during-video-capture/"><u>[Updated] Best Practices to Avoid Missed Frames During Video Capture</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-in-2024-syncing-your-presence-in-real-time-tiktoks/"><u>[Updated] In 2024, Syncing Your Presence in Real-Time TikToks</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-rectify-poor-sound-quality-zoom-audio-fixes/"><u>[Updated] Rectify Poor Sound Quality  Zoom Audio Fixes</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-gaming-evolved-comparing-mavic-air-and-sparks-impact/"><u>2024 Approved  Gaming Evolved  Comparing Mavic Air and Spark's Impact</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-master-stitching-gopro-content-in-extended-panorama-videos/"><u>2024 Approved  Master Stitching GoPro Content in Extended Panorama Videos</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-secrets-to-mastering-chromebook-zoom-features/"><u>2024 Approved  Secrets to Mastering Chromebook Zoom Features</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-tiktok-linking-made-simple-and-irreversible/"><u>2024 Approved  TikTok Linking Made Simple and Irreversible</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-lava-storm-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Lava Storm 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/common-issues-and-resolutions-for-the-failed-windows-11-update-version-1607/"><u>Common Issues & Resolutions for the Failed Windows 11 Update (Version 1607)</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-wont-start-here-are-solutions-to-fix-initialization-errors/"><u>Destiny 2 Won't Start? Here Are Solutions to Fix Initialization Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-resolve-right-click-issues-with-a-mouse-in-windows-10/"><u>Easy Steps to Resolve Right Click Issues with a Mouse in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/enhancing-stability-in-windows-driver-foundation-tackling-excessive-processor-load/"><u>Enhancing Stability in Windows Driver Foundation - Tackling Excessive Processor Load</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-0xc00000e9-explained-strategies-for-fixing-the-plcncachewiper-stop-error-on-windows/"><u>Error Code 0xC00000E9 Explained: Strategies for Fixing the PLCN_CACHE_WIPER Stop Error on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-solutions-for-startup-screens-vanishing-in-monster-hunter-world/"><u>Expert Solutions for Startup Screens Vanishing in Monster Hunter: World</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-crc-how-to-overcome-common-data-verification-issues/"><u>Fixing CRC - How to Overcome Common Data Verification Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-missing-d3dx939dll-errors-on-your-pc-with-easy-fixes/"><u>Fixing Missing d3dX9_39.dll Errors on Your PC with Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-red-screen-issue-a-comprehensive-solution/"><u>Fixing The 'Red Screen' Issue - A Comprehensive Solution</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-do-you-remove-restricted-mode-on-apple-iphone-13-mini-by-drfone-ios/"><u>How Do You Remove Restricted Mode on Apple iPhone 13 mini</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-setup-aborted-due-to-access-issues-in-temporary-directory-error-code-5/"><u>How to Correct 'Setup Aborted' Due to Access Issues in Temporary Directory (Error Code 5)</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-lock-apps-on-infinix-smart-8-pro-to-protect-your-individual-information-by-drfone-android/"><u>In 2024, How to Lock Apps on Infinix Smart 8 Pro to Protect Your Individual Information</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-lenovo-keyboards-steps-for-a-working-typing-experience-again/"><u>Overcoming Issues with Lenovo Keyboards: Steps for a Working Typing Experience Again</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-inoperative-usb-ports-for-a-smooth-windows-11-experience/"><u>Resolving Inoperative USB Ports for a Smooth Windows 11 Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-error-code-0x80072efd-on-your-windows-10-device-a-step-by-step-guide/"><u>Resolving the 'Error Code 0X80072EFD' On Your Windows 10 Device: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/rising-above-failed-installers-the-nvidia-story/"><u>Rising Above Failed Installers: The NVIDIA Story</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-windows-11-tips-for-successfully-launching-a-hosted-network/"><u>Solving Windows 11: Tips for Successfully Launching a Hosted Network</u></a></li>
<li><a href="https://games-able.techidaily.com/sonys-playstation-sound-streaming-technique/"><u>Sony's PlayStation Sound Streaming Technique</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-resolving-windows-error-0x80004005-the-unspecified-problem/"><u>Troubleshooting Guide for Resolving Windows Error 0X80004005: The Unspecified Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolve-access-denied-error-in-printer-driver-setup/"><u>Troubleshooting Tips: Resolve 'Access Denied' Error in Printer Driver Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-tips-for-the-notorious-livekernelevent-117-error/"><u>Ultimate Troubleshooting Tips for the Notorious LiveKernelEvent 117 Error</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209010932-xbox-one-earphones-malfunction-heres-how-to-fix-them/"><u>Xbox One Earphones Malfunction? Here's How to Fix Them</u></a></li>
</ul></div>
