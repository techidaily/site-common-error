---
title: How to Correctly Solve Windows 11 Update Issue - Error 0X8024401C Explained
date: 2024-08-15T11:13:41.184Z
updated: 2024-08-16T11:13:41.184Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Correctly Solve Windows 11 Update Issue - Error 0X8024401C Explained
excerpt: This Article Describes How to Correctly Solve Windows 11 Update Issue - Error 0X8024401C Explained
thumbnail: https://thmb.techidaily.com/b8fca16a34b5411c86475482e61fa021f5aeb02943a66dd5dba0e650f0e39da1.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)
<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3851691&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.aiseesoft.com/avangate/30p/banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4572700&QTY=1&AFFILIATE=108875&CART=1"><img src="	https://www.tubedigger.com/wp-content/uploads/2020/08/tubedigger-software-new.png" border="0">TubeDigger - online video downloader from mostly any site</a>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/517826/4704" target="_top" id="517826"><img src="//a.impactradius-go.com/display-ad/4704-517826" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://united.elfm.net/i/5597632/517826/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)
<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=14095146&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8b6cc3ee5ec407721ce3bf5ff4c0f56b/PRO_BUY_728x90-EN.jpg" border="0"></a>
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)
<!-- affiliate ads begin -->
<a href="https://shop.emeditor.com/order/checkout.php?PRODS=4631722&QTY=1&AFFILIATE=108875&CART=1"><img src="https://www.emeditor.com/wp-content/uploads/2023/05/frontpage2-2048x588.webp" border="0">EmEditor Professional (Lifetime License, non-store app)</a>
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

Now try to install Windows Updates now.

After the fixes above, Windows Update should be good to go now.

* [Windows Update](/tag-search/?tagId=62)


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
<li><a href="https://facebook-video-share.techidaily.com/new-direct-to-youtube-stepwise-process-of-mobile-and-desktop-video-posting-for-2024/"><u>[New] Direct to YouTube  Stepwise Process of Mobile & Desktop Video Posting for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-explorations-reward-6-innovative-minecraft-residences/"><u>[New] In 2024, Exploration's Reward  6 Innovative Minecraft Residences</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/updated-break-free-from-linearity-mastering-jump-cut-transitions/"><u>[Updated] Break Free From Linearity  Mastering Jump Cut Transitions</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-expertly-convert-videos-on-your-device-with-the-most-trusted-apps-8-for-2024/"><u>[Updated] Expertly Convert Videos on Your Device with the Most Trusted Apps #8 for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-exploring-user-experiences-triller-and-tiktok-compared-max-156-chars/"><u>[Updated] Exploring User Experiences  Triller & TikTok Compared (Max 156 Chars)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-vimeos-global-distribution-guide/"><u>[Updated] Vimeo's Global Distribution Guide</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-elite-nintendo-switch-battle-selection-max-156/"><u>2024 Approved  Elite Nintendo Switch Battle Selection (Max 156)</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-luminances-hdr-accuracy-assessment/"><u>2024 Approved  Luminance's HDR Accuracy Assessment</u></a></li>
<li><a href="https://howto.techidaily.com/8-quick-fixes-unfortunately-snapchat-has-stopped-on-honor-80-pro-straight-screen-edition-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Quick Fixes Unfortunately, Snapchat has Stopped on Honor 80 Pro Straight Screen Edition | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-cast-errors-and-enable-smooth-streaming-from-pc-to-tv-on-windows-11/"><u>Bypass Cast Errors and Enable Smooth Streaming From PC to TV on Windows 11</u></a></li>
<li><a href="https://fox-direct.techidaily.com/crafting-captivating-photo-based-video-content-using-pixizs-features/"><u>Crafting Captivating Photo-Based Video Content Using Pixiz's Features</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-continuous-halt-issues-in-computers-a-users-handbook/"><u>Diagnosing & Repairing Continuous Halt Issues in Computers – A User's Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207376954-diagnosing-the-disconnected-systems-event-notification-service-in-windows-fixed/"><u>Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed</u></a></li>
<li><a href="https://win11-tips.techidaily.com/enabling-managed-users-and-groups-in-win1110-homes/"><u>Enabling Managed Users and Groups in Win11/10 Homes</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/exploring-the-features-of-garmin-venu-the-fitness-companion-for-every-moment/"><u>Exploring the Features of Garmin Venu - The Fitness Companion for Every Moment</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-mute-condition-solving-windows-eboard-sound-problems/"><u>Fix Your Mute Condition: Solving Windows Eboard Sound Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-crash-problems-in-total-war-rome-remastered-troubleshooting-guide/"><u>Fixing Crash Problems in Total War: Rome Remastered - Troubleshooting Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-cannot-reach-system-event-notification-services-error-message/"><u>How to Fix Windows Cannot Reach System Event Notification Services Error Message</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-achieving-visual-precision-with-the-right-4k-display-selection/"><u>In 2024, Achieving Visual Precision with the Right 4K Display Selection</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-guide-to-mirror-your-honor-x50iplus-to-other-android-devices-drfone-by-drfone-android/"><u>In 2024, Guide to Mirror Your Honor X50i+ to Other Android devices | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-jokejigsaw-compiler/"><u>In 2024, JokeJigsaw Compiler</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-marketing-edge-with-video-based-client-advocacy/"><u>In 2024, Marketing Edge with Video-Based Client Advocacy</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-stand-out-in-the-crowd-top-15-innovative-snapchat-posts/"><u>In 2024, Stand Out in the Crowd  Top 15 Innovative Snapchat Posts</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-thinking-about-changing-your-netflix-region-without-a-vpn-on-vivo-y02t-drfone-by-drfone-virtual-android/"><u>In 2024, Thinking About Changing Your Netflix Region Without a VPN On Vivo Y02T? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-missing-bluetooth-feature-problems-in-windows-10-with-easy-fixes/"><u>Overcome Missing Bluetooth Feature Problems in Windows 10 with Easy Fixes!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-launch-darkness-errors-in-monster-hunter-world-gameplay/"><u>Overcoming Launch Darkness Errors in Monster Hunter World Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-resolving-winsvr-server-role-failed-smb-signing-requirements-error-x0x800706b7/"><u>Quick Solutions for Resolving WinSvr Server Role Failed: SMB Signing Requirements Error - X0x800706B7</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/secrets-to-profitability-earning-with-youtube-shorts-explored/"><u>Secrets to Profitability  Earning with YouTube Shorts Explored</u></a></li>
<li><a href="https://common-error.techidaily.com/speed-up-your-pc-by-reviving-corrupted-hardware-drivers-easily/"><u>Speed Up Your PC by Reviving Corrupted Hardware Drivers Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/steam-connection-problems-solved-restored-game-server-access/"><u>Steam Connection Problems Solved – Restored Game Server Access</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-minecraft-loading-on-your-windows-machine-heres-the-solution-fixed/"><u>Trouble with Minecraft Loading on Your Windows Machine? Here's the Solution! [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-activating-dx11-and-feature-level-ebitron-in-wwe-2k-battlegrounds/"><u>Troubleshooting Tips for Activating DX11 and Feature Level Ebitron in WWE 2K Battlegrounds</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-resolved-issue-with-teredo-tunneling-protocol/"><u>Troubleshooting: Resolved Issue with Teredo Tunneling Protocol</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-error-0x80004005-unspecified-issue-explained/"><u>Understanding and Resolving Error 0X80004005: Unspecified Issue Explained</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-windows-error-0x80nffff-causes-solutions-and-prevention-tips/"><u>Understanding Windows Error 0X80nFFFF – Causes, Solutions, and Prevention Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-reducing-system-overheads/"><u>Windows 10: Reducing System Overheads</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-tutorial-deactivate-touchpad-when-connected-to-a-mouse/"><u>Windows 11 Tutorial: Deactivate Touchpad When Connected to a Mouse</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209969299-xbox-one-connection-woes-heres-how-to-get-your-controllers-working-perfectly-again/"><u>Xbox One Connection Woes? Here’s How to Get Your Controllers Working Perfectly Again!</u></a></li>
</ul></div>
