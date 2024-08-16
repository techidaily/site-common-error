---
title: Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems
date: 2024-08-15T11:06:11.156Z
updated: 2024-08-16T11:06:11.156Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems
excerpt: This Article Describes Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems
thumbnail: https://thmb.techidaily.com/89f58c00fabb0b3ac26622205cb1b82f67ddb2d733ca5558e5f2d4e68026f7eb.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2087389/7443" target="_top" id="2087389"><img src="//a.impactradius-go.com/display-ad/7443-2087389" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087389/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

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

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4531356&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8fdd149fcaa7058caccc9c4ad5b0d89a/products/tss-box.JPG" border="0">The Tube Sites Submitter is a fast and efficient tool for anyone who needs to upload videos quickly, easily and automatically to hundreds of tube sites in mere minutes . </a>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)
<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DBanner%2B728x90"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/2e76fe6a-3010-1b37-7846-f34ff9c6b4ca.png" border="0"></a>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)
<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)
<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2086436/19576" target="_top" id="2086436"><img src="//a.impactradius-go.com/display-ad/19576-2086436" border="0" alt="" width="1500" height="400"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2086436/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)
<!-- affiliate ads begin -->
<a href="https://tokenmetrics.sjv.io/c/5597632/1864921/20702" target="_top" id="1864921"><img src="//a.impactradius-go.com/display-ad/20702-1864921" border="0" alt="" width="1251" height="1042"/></a>
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

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4718730&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/ce9a6fb2becc2d235e62b125e9260102/products/copy_vMixCallScreenshot1-large.jpg" border="0">vMix HD - Software based live production. vMix HD includes everything in vMix Basic HD plus 1000 inputs, Video List, 4 Overlay Channels, and 1 vMix Call 
This bundle includes Studio 200 for vMix from Virtualsetworks, HTTP Matrix 1.0 automation scheduler, and 4 introductory training videos from the Udemy vMix Basic to Amazing course. </a>
<!-- affiliate ads end -->

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
<li><a href="https://facebook-video-content.techidaily.com/new-elevate-engagement-10-effective-facebook-video-tips-for-2024/"><u>[New] Elevate Engagement  10 Effective Facebook Video Tips for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-how-to-download-vimeo-videos-withwithout-software-100-useful-for-2024/"><u>[New] How to Download Vimeo Videos With/Without Software [100%% Useful] for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-audio-enabled-mac-video-recorder/"><u>[New] In 2024, Audio-Enabled Mac Video Recorder</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-unveiling-the-secrets-of-superior-tunefab-recordings-for-2024/"><u>[New] Unveiling the Secrets of Superior Tunefab Recordings for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-core-dll-not-present-on-windows-pc/"><u>[Resolved] Core DLL Not Present on Windows PC</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-in-2024-ensure-video-perfection-before-sharing-on-instagram/"><u>[Updated] In 2024, Ensure Video Perfection Before Sharing on Instagram</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-preparing-to-engage-in-googles-video-meetings/"><u>[Updated] Preparing to Engage in Google's Video Meetings</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-exploring-youtube-channels-for-easier-access-to-fb-videos-on-apple-tv/"><u>2024 Approved  Exploring YouTube Channels for Easier Access to FB Videos on Apple TV</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveil-the-power-leveraging-windows-11-and-zoom-maximum/"><u>2024 Approved  Unveil the Power  Leveraging Windows 11 and Zoom Maximum</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/all-about-factory-reset-what-is-it-and-what-it-does-to-your-poco-f5-pro-5g-drfone-by-drfone-reset-android-reset-android/"><u>All About Factory Reset, What Is It and What It Does to Your Poco F5 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/detecting-undetected-second-monitor-win1011/"><u>Detecting Undetected Second Monitor (Win10/11)</u></a></li>
<li><a href="https://common-error.techidaily.com/dll-concern-msvcr120-not-present-in-win/"><u>DLL Concern: MSVCR120 Not Present in Win</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-your-wireless-mouse-keeps-stopping-mid-operation-on-pcs-with-windows-11-or-10/"><u>Effective Solutions for When Your Wireless Mouse Keeps Stopping Mid-Operation on PCs with Windows 11 or 10</u></a></li>
<li><a href="https://common-error.techidaily.com/error-solved-how-to-fix-pixel-format-not-accelerated-in-lwjgl-applications/"><u>Error Solved: How to Fix 'Pixel Format Not Accelerated' In LWJGL Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/exe-errors-tamed-explorer-on-win1011/"><u>Exe Errors Tamed – Explorer on Win10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-disappearing-bluetooth-icon-tips-for-windows-11-users/"><u>Fixing a Disappearing Bluetooth Icon – Tips for Windows 11 Users</u></a></li>
<li><a href="https://some-techniques.techidaily.com/from-audio-clips-to-written-content-harnessing-ms-words-transcription-features-for-2024/"><u>From Audio Clips to Written Content  Harnessing MS Word's Transcription Features for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209021298-how-to-fix-the-irritating-cracking-sound-from-your-pcs-speakers-on-windows-operating-systems/"><u>How to Fix the Irritating Cracking Sound From Your PC's Speakers on Windows Operating Systems.</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-screen-mirroring-infinix-smart-8-plus-drfone-by-drfone-android/"><u>How to Screen Mirroring Infinix Smart 8 Plus? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-windows-11-display-from-flickering-solutions-and-tips/"><u>How to Stop Windows 11 Display From Flickering: Solutions and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-swiftly-rectify-dll-absence-in-games/"><u>How to Swiftly Rectify DLL Absence in Games</u></a></li>
<li><a href="https://techidaily.com/how-to-transfer-data-from-apple-iphone-x-to-other-iphone-12-pro-max-devices-drfone-by-drfone-transfer-data-from-ios-transfer-data-from-ios/"><u>How To Transfer Data From Apple iPhone X To Other iPhone 12 Pro Max devices? | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-mastering-profit-on-beauty-channels/"><u>In 2024, Mastering Profit on Beauty Channels</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://tech-revival.techidaily.com/mastering-gpt-3-a-step-by-step-guide-for-openais-sandbox/"><u>Mastering GPT-3: A Step-by-Step Guide for OpenAI's Sandbox</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-over-amplified-sounds-causes-fixes-and-prevention-techniques/"><u>PS4 Over-Amplified Sounds: Causes, Fixes, and Prevention Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-remedies-to-address-missing-bluetooth-on-your-windows-11-system/"><u>Quick Remedies to Address Missing Bluetooth on Your Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-oculus-device-malfunctions-a-step-by-step-guide/"><u>Solving Oculus Device Malfunctions: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-correcting-broken-service-registeries-on-windows-(theme)10(theme)/"><u>Step-by-Step Guide: Correcting Broken Service Registeries on Windows <Theme>10</Theme></u></a></li>
<li><a href="https://common-error.techidaily.com/system-resource-shortage-solutions-overcoming-service-request-failed-messages/"><u>System Resource Shortage Solutions: Overcoming 'Service Request Failed' Messages</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/top-10-airplay-apps-in-honor-x50i-for-streaming-drfone-by-drfone-android/"><u>Top 10 AirPlay Apps in Honor X50i for Streaming | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-4-fixes-for-when-your-dns-server-isnt-working-properly/"><u>Top 4 Fixes for When Your DNS Server Isn’t Working Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/top-strategies-to-prevent-frequent-crashes-and-stops-in-pc-performance/"><u>Top Strategies to Prevent Frequent Crashes and Stops in PC Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-restore-5-techniques-for-a-functional-touchscreen-on-windows-11/"><u>Troubleshoot and Restore: 5 Techniques for a Functional Touchscreen on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-what-to-do-when-your-laptop-mouse-freezes/"><u>Troubleshooting Tips: What to Do When Your Laptop Mouse Freezes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unsuccessful-hardware-transfer-in-windows-10-systems/"><u>Troubleshooting Unsuccessful Hardware Transfer in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-bluetooth-features-in-windows-11-and-10-a-complete-walkthrough/"><u>Unlocking Bluetooth Features in Windows 11 & 10: A Complete Walkthrough</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-are-location-permissions-life360-on-vivo-g2-drfone-by-drfone-virtual-android/"><u>What are Location Permissions Life360 On Vivo G2? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/why-is-my-computers-built-in-security-not-responding-fix-windows-smartscreen-gaps/"><u>Why Is My Computer's Built-In Security Not Responding? Fix Windows SmartScreen Gaps</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-explorer-down-fix-now/"><u>Windows Explorer Down – Fix Now!</u></a></li>
</ul></div>
