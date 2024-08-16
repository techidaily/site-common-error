---
title: "Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11"
date: 2024-08-15T11:03:07.106Z
updated: 2024-08-16T11:03:07.106Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11"
excerpt: "This Article Describes Fixing the Unfixable: Solutions for the Persistent 0X80072EFD Error on Windows 11"
thumbnail: https://thmb.techidaily.com/f99b0547d8a95f637159e251c131a6578ae71b255445af767dc74d5fd38281e0.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://store.bitdefender.com/affiliate.php?ACCOUNT=BITLATIN&AFFILIATE=108875&PATH=http%3A%2F%2Fwww.bitdefender.com%2Fbusiness%3FAFFILIATE%3D108875%26RESOURCE%3D30%2525%2BOff%2Ball%2BGravityZone%2BProducts"><img src="https://www.bitdefender.com/content/dam/bitdefender/business/campaign/1200X628.png" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068407/7443" target="_top" id="2068407"><img src="//a.impactradius-go.com/display-ad/7443-2068407" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068407/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://checkout.abbyy.com/order/checkout.php?PRODS=39254549&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/0e5fb5c76fca16adbee503c9aff393cd/products/8_FR-Badges-NEW-FR-Standard-16-WIN-200.png" border="0"> PDF application, powered by AI-based OCR, for unified workflows with both digital and scanned documents. </a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://store.revouninstaller.com/order/checkout.php?PRODS=27889512&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4282ec8de8c9be897e7aff4aa231b1a4/728__90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-bifrost-betrayal-gods-at-war/"><u>[New] 2024 Approved  Bifrost Betrayal  Gods at War</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-precision-in-photograph-preservation-phone-to-snapchat-guide/"><u>[New] Precision in Photograph Preservation  Phone to Snapchat Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-navigate-nature-androids-animated-adventure-series-for-2024/"><u>[Updated] Navigate Nature  Android’s Animated Adventure Series for 2024</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-top-6-masterpieces-designing-mc-village-homes-for-2024/"><u>[Updated] Top 6 Masterpieces  Designing MC Village Homes for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-oppo-a38-system-crash-issue-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Oppo A38 System Crash Issue | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/clarified-response-handling-non-writable-memory-situations-in-location-x/"><u>Clarified Response: Handling Non-Writable Memory Situations in Location X</u></a></li>
<li><a href="https://common-error.techidaily.com/common-issues-and-resolutions-for-the-failed-windows-11-update-version-1607/"><u>Common Issues & Resolutions for the Failed Windows 11 Update (Version 1607)</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-wont-start-here-are-solutions-to-fix-initialization-errors/"><u>Destiny 2 Won't Start? Here Are Solutions to Fix Initialization Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/directx-error-resolved-a-comprehensive-guide-to-fixing-hardware-compatibility-issues/"><u>DirectX Error Resolved? A Comprehensive Guide to Fixing Hardware Compatibility Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-for-when-your-hp-laptops-usb-port-stops-working/"><u>DIY Fixes for When Your HP Laptop's USB Port Stops Working</u></a></li>
<li><a href="https://extra-resources.techidaily.com/elevate-online-media-selecting-the-best-5-quality-boosters/"><u>Elevate Online Media  Selecting the Best 5 Quality Boosters</u></a></li>
<li><a href="https://common-error.techidaily.com/enhancing-stability-in-windows-driver-foundation-tackling-excessive-processor-load/"><u>Enhancing Stability in Windows Driver Foundation - Tackling Excessive Processor Load</u></a></li>
<li><a href="https://win-dash.techidaily.com/find-and-install-compatible-microsoft-audio-drivers-for-windows-1087/"><u>Find & Install Compatible Microsoft Audio Drivers for Windows 10/8/7</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unavailable-windows-hello-feature-on-windows-10-devices/"><u>Fixing Unavailable Windows Hello Feature on Windows 10 Devices</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/game-capture-made-simple-top-free-tools-listing-for-2024/"><u>Game Capture Made Simple  Top Free Tools Listing for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcoming-device-not-present-errors-with-windows-operating-systems-code-24-fix/"><u>Guide to Overcoming 'Device Not Present' Errors with Windows Operating Systems (Code 24 Fix)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-change-your-sim-pin-code-on-your-honor-magic5-ultimate-phone-by-drfone-android/"><u>How To Change Your SIM PIN Code on Your Honor Magic5 Ultimate Phone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-remove-forgotten-pin-of-your-google-pixel-8-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Google Pixel 8</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-non-responsive-custom-profile-adjustments/"><u>How to Resolve Non-Responsive Custom Profile Adjustments</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-samsung-galaxy-s23-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Samsung Galaxy S23 Ultra | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-crack-open-your-marketing-potential-with-these-nine-tactics/"><u>In 2024, Crack Open Your Marketing Potential with These Nine Tactics</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-perfecting-live-footage-with-fbx-recorder/"><u>In 2024, Perfecting Live Footage with FBX Recorder</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/in-2024-practical-tips-to-store-your-favorite-instagram-reels/"><u>In 2024, Practical Tips to Store Your Favorite Instagram Reels</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-premium-commercial-cloud-vaulting-services/"><u>In 2024, Premium Commercial Cloud Vaulting Services</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-tips-and-tricks-for-apple-id-locked-issue-from-apple-iphone-12-by-drfone-ios/"><u>In 2024, Tips and Tricks for Apple ID Locked Issue From Apple iPhone 12</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlock-iphone-7-plus-with-forgotten-passcode-different-methods-you-can-try-drfone-by-drfone-ios/"><u>In 2024, Unlock iPhone 7 Plus With Forgotten Passcode Different Methods You Can Try | Dr.fone</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-youtubes-beauty-titans-whos-leading/"><u>In 2024, YouTube's Beauty Titans  Who's Leading ?</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagrams-time-travelling-method-master-reversal-of-videos/"><u>Instagram's Time-Travelling Method  Master Reversal of Videos</u></a></li>
<li><a href="https://os-tips.techidaily.com/quick-and-straightforward-techniques-for-mirroring-your-ipad-display-onto-a-pc-mac-or-television/"><u>Quick and Straightforward Techniques for Mirroring Your iPad Display Onto a PC, Mac or Television</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206300481-resolve-the-bluetooth-not-detected-on-windows-11-fast-fix-guide/"><u>Resolve the Bluetooth Not Detected on Windows 11 - Fast Fix Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-to-repairing-the-red-screen-error/"><u>Resolved: Step-by-Step Guide to Repairing the Red Screen Error</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-and-fixing-the-code-28-device-issues-on-windows/"><u>Resolved: Troubleshooting and Fixing the 'Code 28' Device Issues on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-resource-protection-error-troubleshooting-steps/"><u>Resolving 'Windows Resource Protection' Error: Troubleshooting Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-of-disabling-wireless-capability-on-electronics/"><u>Solving the Problem of Disabling Wireless Capability on Electronics</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210166882-solving-the-ps4s-notorious-ce-34878-0-glitch-steps-and-tips-inside/"><u>Solving the PS4's Notorious CE-34878-0 Glitch – Steps & Tips Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-airpods-connection-issues-on-pc-a-2024-guide/"><u>Solving Your AirPods Connection Issues on PC: A 2024 Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-windows-10s-troublesome-error-code-0x80072fed-proven-fixes-inside/"><u>Tackling Windows 10'S Troublesome Error Code 0X80072FED - Proven Fixes Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-chrome-couldnt-load-plugin-a-detailed-guide-for-windows-11/"><u>The Ultimate Fix for 'Chrome Couldn't Load Plugin': A Detailed Guide for Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-solution-for-when-windows-update-fails-to-launch/"><u>The Ultimate Solution for When Windows Update Fails to Launch</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-step-by-step-get-your-airpods-working-with-windows/"><u>Troubleshooting Step-by-Step: Get Your AirPods Working with Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolve-access-denied-error-in-printer-driver-setup/"><u>Troubleshooting Tips: Resolve 'Access Denied' Error in Printer Driver Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolving-issues-with-steam-store-connectivity/"><u>Troubleshooting Tips: Resolving Issues with Steam Store Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixing-the-lack-of-pen-and-touch-input-on-your-screen/"><u>Troubleshooting: Fixing the Lack of Pen and Touch Input on Your Screen</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-tips-for-the-notorious-livekernelevent-117-error/"><u>Ultimate Troubleshooting Tips for the Notorious LiveKernelEvent 117 Error</u></a></li>
<li><a href="https://common-error.techidaily.com/unable-to-start-the-bluetooth-stack-service-solved/"><u>Unable to Start the Bluetooth Stack Service [Solved]</u></a></li>
<li><a href="https://techidaily.com/undelete-lost-photos-from-htc-by-fonelab-android-recover-photos/"><u>Undelete lost photos from HTC .</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-the-causes-behind-a-non-starting-personal-computer/"><u>Understanding the Causes Behind a Non-Starting Personal Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-blurry-text-heres-how-to-fix-it/"><u>Windows 11 Blurry Text? Here's How to Fix It</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/yokus-island-adventure-an-in-depth-look-at-grand-quests-and-surprises/"><u>Yoku's Island Adventure: An In-Depth Look at Grand Quests and Surprises</u></a></li>
</ul></div>
