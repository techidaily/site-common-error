---
title: "Resolving Windows 11 Installation Error: Fixing Error Code 80240020 Once and for All"
date: 2024-08-27T13:36:26.434Z
updated: 2024-08-28T13:36:26.434Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 11 Installation Error: Fixing Error Code 80240020 Once and for All"
excerpt: "This Article Describes Resolving Windows 11 Installation Error: Fixing Error Code 80240020 Once and for All"
thumbnail: https://thmb.techidaily.com/ed631fce79a85bf0cd5e756384d355b32be9ff521aba55cfa7af4917eeac790c.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://order.glarysoft.com/order/checkout.php?PRODS=35408920&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/6734fa703f6633ab896eecbdfad8953a/products/FR-200-1.png" border="0">Glarysoft File Recovery Pro - Helps to recover your lost file/data, even permanently deleted data. </a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

<!-- affiliate ads begin -->
<a href="https://store.absolute.com/order/checkout.php?PRODS=4601998&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/ef70e26a0b5da778eda3f48014d087cd/728x90_larger-shield.jpg" border="0"></a>
<!-- affiliate ads end -->
3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://zonlipartnershipprogram.pxf.io/c/5597632/1611407/17882" target="_top" id="1611407"><img src="//a.impactradius-go.com/display-ad/17882-1611407" border="0" alt="" width="300" height="485"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1611407/17882" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=33729450&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/7f687767ccf20fcea1c9dc4a5adc2326/Digisigner_banner_728_x_90_color_version.png" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://sentrypc.7eer.net/c/5597632/398453/3022" target="_top" id="398453"><img src="//a.impactradius-go.com/display-ad/3022-398453" border="0" alt="www.sentrypc.com" width="580" height="400"/></a><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/398453/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-instant-transmission-tweets-as-vids-on-whatsapp/"><u>[New] 2024 Approved  Instant Transmission  Tweets as Vids on WhatsApp</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-quick-click-compilation-top-10-fastest-phone-and-pc-apps-for-2024/"><u>[New] Quick Click Compilation  Top 10 Fastest Phone & PC Apps for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-11-wi-fi-option-not-showing-up/"><u>[SOLVED] Windows 11 Wi-Fi Option Not Showing Up</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-dynamic-duels-and-daring-deeds-top-10-gaming-highlights/"><u>[Updated] Dynamic Duels & Daring Deeds  Top 10 Gaming Highlights</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-instacaptions-for-a-global-stage-top-100-inspirational-posts/"><u>[Updated] InstaCaptions for a Global Stage  Top 100 Inspirational Posts</u></a></li>
<li><a href="https://some-guidance.techidaily.com/updated-the-spectrum-of-perfection-creating-stunning-hdrs-in-lightroom/"><u>[Updated] The Spectrum of Perfection  Creating Stunning HDRs in Lightroom</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-secure-and-save-with-these-10-top-rated-video-chat-apps-on-your-smartphone/"><u>2024 Approved  Secure and Save with These 10 Top-Rated Video Chat Apps on Your Smartphone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212439631-avoid-rough-terrain-limit-driving-over-bumpy-or-uneven-surfaces-that-could-cause-additional-stress-on-your-vehiclecuots-suspension-system/"><u>Avoid Rough Terrain: Limit Driving over Bumpy or Uneven Surfaces that Could Cause Additional Stress on Your Vehicle'cuot;s Suspension System.</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210148490-baffled-by-sd-detecting-errors-fixes-include/"><u>Baffled by SD Detecting Errors? Fixes Include!</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-your-pcs-performance-with-easy-maintenance-tips/"><u>Boost Your PC's Performance with Easy Maintenance Tips</u></a></li>
<li><a href="https://change-location.techidaily.com/catchemall-celebrate-national-pokemon-day-with-virtual-location-on-vivo-y17s-drfone-by-drfone-virtual-android/"><u>CatchEmAll Celebrate National Pokémon Day with Virtual Location On Vivo Y17s | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-solving-hardware-driver-problems-a-guide-to-completing-your-windows-7-installation-without-errors/"><u>Diagnosing and Solving Hardware Driver Problems: A Guide to Completing Your Windows 7 Installation Without Errors</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/download-and-update-the-corsair-k55-keyboard-drivers/"><u>Download and Update the Corsair K55 Keyboard Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-a-non-working-touchpad-scroll-wheel-on-windows-and-mac/"><u>Effective Fixes for a Non-Working Touchpad Scroll Wheel on Windows and Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-pvpnet-patchers-kernel-stops-functioning/"><u>Effective Fixes for When Your PvP.net Patcher's Kernel Stops Functioning</u></a></li>
<li><a href="https://facebook.techidaily.com/ending-seamless-fb-navigation-via-browser/"><u>Ending Seamless FB Navigation via Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-correcting-corruption-issues-with-system-files-on-windows-11/"><u>Expert Advice: Correcting Corruption Issues with System Files on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-to-overcoming-wacom-tablet-technical-glitches-and-errors/"><u>Expert Guide to Overcoming Wacom Tablet Technical Glitches and Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-performance-issues-decreasing-desktop-window-managers-cpu-and-gpu-consumption-on-windows-1011/"><u>Fixing Performance Issues: Decreasing Desktop Window Manager's CPU and GPU Consumption on Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-diagnose-and-cure-your-dell-laptops-black-screen-woes-full-instructional-handbook/"><u>How to Diagnose & Cure Your Dell Laptop's Black Screen Woes: Full Instructional Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-broken-right-click-feature-on-a-mouse-for-windows-10-users/"><u>How to Fix the Broken Right-Click Feature on a Mouse for Windows 10 Users</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-android-to-apple-how-to-transfer-photos-from-vivo-y56-5g-to-ipad-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Android to Apple How To Transfer Photos From Vivo Y56 5G to iPad Easily | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-top-10-airplay-apps-in-tecno-camon-30-pro-5g-for-streaming-drfone-by-drfone-android/"><u>In 2024, Top 10 AirPlay Apps in Tecno Camon 30 Pro 5G for Streaming | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/navigating-the-art-of-360-live-on-facebook-for-2024/"><u>Navigating the Art of 360 Live on Facebook for 2024</u></a></li>
<li><a href="https://buynow-info.techidaily.com/navigating-the-nook-glowlight-4-detailed-review-and-comparison/"><u>Navigating the Nook GlowLight 4 - Detailed Review and Comparison</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209764696-noisy-playstation-4-heres-how-you-can-silence-the-racket/"><u>Noisy PlayStation 4? Here's How You Can Silence the Racket!</u></a></li>
<li><a href="https://common-error.techidaily.com/repair-malfunctioning-letter-keys-a-guide-for-windows-10-and-11-keyboard-issues/"><u>Repair Malfunctioning Letter Keys: A Guide for Windows 10 and 11 Keyboard Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-your-windows-10-touchscreen-functionality-with-these-five-remedies/"><u>Restore Your Windows 10 Touchscreen Functionality with These Five Remedies</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-when-your-screen-lacks-hdcp-protection/"><u>Solution Steps When Your Screen Lacks HDCP Protection</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-unraveling-the-mystery-of-auto-start-issues-in-your-windows-11-machine/"><u>Solved: Unraveling the Mystery of Auto-Start Issues in Your Windows 11 Machine</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-rectifying-compromised-file-systems-on-windows-11/"><u>Troubleshooting and Rectifying Compromised File Systems on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-elevated-cpu-utilization-by-iastordatasvc-in-a-32-bit-windows/"><u>Troubleshooting Elevated CPU Utilization by IAStorDataSvc in a 32-Bit Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-display-hiccups-in-windows-11-system/"><u>Understanding and Fixing Display Hiccups in Windows 11 System</u></a></li>
<li><a href="https://driver-install.techidaily.com/win11driversnew-atiradeon5770/"><u>Win11DriversNew: ATIRadeon5770</u></a></li>
</ul></div>
