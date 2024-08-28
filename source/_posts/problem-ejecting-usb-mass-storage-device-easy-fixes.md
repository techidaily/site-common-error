---
title: Problem Ejecting USB Mass Storage Device (EASY FIXES)
date: 2024-08-27T13:33:15.083Z
updated: 2024-08-28T13:33:15.083Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Problem Ejecting USB Mass Storage Device (EASY FIXES)
excerpt: This Article Describes Problem Ejecting USB Mass Storage Device (EASY FIXES)
thumbnail: https://thmb.techidaily.com/0994f11e3b98aa050445b83a923c27f3f286a1f5302c7ff78d5008912b4d02f9.jpg
---

## Resolving Your System's Diagnostics Policy Service Problem Today

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://ursime.pxf.io/c/5597632/2048972/16384" target="_top" id="2048972"><img src="//a.impactradius-go.com/display-ad/16384-2048972" border="0" alt="" width="1200" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2048972/16384" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453719/17020" target="_top" id="1453719"><img src="//a.impactradius-go.com/display-ad/17020-1453719" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453719/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4699091&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/bccefcc1b1eee9eca3ae4f5c1a281482/products/1_jutoh-logo-1200x1600.jpg" border="0">Jutoh Plus -  Jutoh is an ebook creator for Epub, Kindle and more. It's fast, runs on Windows, Mac, and Linux, comes with a cover design editor, and allows book variations to be created with alternate text, style sheets and cover designs. Jutoh Plus adds scripting so you can automate ebook import and creation operations. It also allows customisation of ebook HTML via templates and source code documents; and you can create Windows CHM and wxWidgets HTB help files. </a>
<!-- affiliate ads end -->
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

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484"><img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-is-it-allowable-to-distribute-videos-via-social-networks/"><u>[Updated] 2024 Approved  Is It Allowable to Distribute Videos via Social Networks?</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-revolutionizing-color-with-the-precision-of-4k-blade-cameras/"><u>2024 Approved  Revolutionizing Color with the Precision of 4K Blade Cameras</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-freezing-during-windows-11-updates-best-fixes-and-techniques/"><u>Addressing Freezing During Windows 11 Updates: Best Fixes & Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/common-issues-with-the-windows-1903-upgrade-process-fixes-included/"><u>Common Issues with the Windows 1903 Upgrade Process - Fixes Included</u></a></li>
<li><a href="https://common-error.techidaily.com/correcting-the-missing-sound-driver-issue-in-windows-11-tips-and-tricks/"><u>Correcting the Missing Sound Driver Issue in Windows 11 - Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-keyboard-darkness-issue-a-step-by-step-illumination-restoration-method/"><u>Corsair Keyboard Darkness Issue? A Step-by-Step Illumination Restoration Method</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-netflix-accessibility-is-it-a-service-interruption-or-something-else/"><u>Diagnosing & Fixing Netflix Accessibility: Is It a Service Interruption or Something Else?</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-a-non-functional-mic-on-your-samsung-playstation-4-console/"><u>Expert Tips for Fixing a Non-Functional Mic on Your Samsung PlayStation 4 Console</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-torrent-download-errors-effective-strategies-for-users/"><u>Fixing Torrent Download Errors: Effective Strategies for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/frozen-function-computer-wont-leave-win1110-snooze/"><u>Frozen Function: Computer Won't Leave Win11/10 Snooze</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-do-i-stop-someone-from-tracking-my-tecno-camon-30-pro-5g-drfone-by-drfone-virtual-android/"><u>How Do I Stop Someone From Tracking My Tecno Camon 30 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-factory-reset-ipad-or-apple-iphone-13-mini-without-icloud-password-or-apple-id-by-drfone-ios/"><u>How to Factory Reset iPad or Apple iPhone 13 mini without iCloud Password or Apple ID?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-common-wacom-tablet-connectivity-problems/"><u>How to Fix Common Wacom Tablet Connectivity Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-cannot-install-updates-message-error-0x8007001f-explained/"><u>How To Overcome The 'Cannot Install Updates' Message - Error 0X8007001F Explained!</u></a></li>
<li><a href="https://common-error.techidaily.com/identifying-group-managed-settings-within-your-windows-configuration/"><u>Identifying Group-Managed Settings Within Your Windows Configuration</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-remove-a-previously-synced-google-account-from-your-vivo-y78-5g-by-drfone-android/"><u>In 2024, How to Remove a Previously Synced Google Account from Your Vivo Y78 5G</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-contacts-from-oppo-find-n3-to-other-android-devices-using-bluetooth-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Contacts from Oppo Find N3 to Other Android Devices Using Bluetooth? | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-xiaomi-mix-fold-3-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Xiaomi Mix Fold 3 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/insufficient-disk-space-resolving-not-enough-storage-error-messages/"><u>Insufficient Disk Space: Resolving 'Not Enough Storage' Error Messages</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-bluetooth-compatibility-expert-tips-for-seamless-connections-on-windows-n-in-the-new-year/"><u>Mastering Bluetooth Compatibility: Expert Tips for Seamless Connections on Windows N in the New Year</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-windows-10-for-reliable-clipboard-use/"><u>Optimizing Windows 10 for Reliable Clipboard Use</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-steam-server-accessibility-issues/"><u>Resolved: Fixing Steam Server Accessibility Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-unsupported-hdcp-format-on-your-screen-setup/"><u>Resolving Unsupported HDCP Format on Your Screen Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-a-malfunctioning-huion-pen-5-swift-repair-strategies-for-artists/"><u>Reviving A Malfunctioning Huion Pen: 5 Swift Repair Strategies for Artists</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-fixes-for-when-your-computer-wont-read-your-usb-flash-drive/"><u>Simple Fixes for When Your Computer Won't Read Your USB Flash Drive</u></a></li>
<li><a href="https://technical-tips.techidaily.com/simplified-processes-to-detach-applications-from-your-macintosh-system/"><u>Simplified Processes to Detach Applications From Your Macintosh System</u></a></li>
<li><a href="https://common-error.techidaily.com/skype-microphone-not-working-follow-these-steps-for-a-quick-and-easy-resolution/"><u>Skype Microphone Not Working? Follow These Steps for a Quick and Easy Resolution!</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/soundtrack-your-youtube-videos-7-free-audio-selections/"><u>Soundtrack Your YouTube Videos  7 Free Audio Selections</u></a></li>
<li><a href="https://common-error.techidaily.com/streamline-fixing-missing-dll-on-pc-games/"><u>Streamline Fixing Missing DLL on PC Games</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-5-car-locator-apps-for-realme-12-5g-drfone-by-drfone-virtual-android/"><u>Top 5 Car Locator Apps for Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-solutions-how-to-fix-a-freezing-windows-11-system/"><u>Top Solutions: How to Fix a Freezing Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/troubled-update-process-on-windows-10-version-1607/"><u>Troubled Update Process on Windows 10 (Version 1607)</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-service-failed-to-start-issue-for-user-profiles-in-windows-10-and-11/"><u>Troubleshooting the 'Service Failed to Start' Issue for User Profiles in Windows 10 & 11</u></a></li>
<li><a href="https://common-error.techidaily.com/unblock-stuck-window-updates-on-older-operating-systems-the-ultimate-guide-to-better-user-experience-in-year-of-our-lord-two-thousand-and-twenty-four-for-wi84/"><u>Unblock Stuck Window Updates On Older Operating Systems - The Ultimate Guide to Better User Experience In Year Of Our Lord Two Thousand And Twenty Four for Windows Users Edition of Win7! (Step by Step Guide Along with Helpful Tips and Expert Advice.)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203892941-why-isnt-my-microsoft-surface-pro-4-touch-screen-responding-solve-the-problem-here/"><u>Why Isn’t My Microsoft Surface Pro 4 Touch Screen Responding? Solve the Problem Here!</u></a></li>
</ul></div>
