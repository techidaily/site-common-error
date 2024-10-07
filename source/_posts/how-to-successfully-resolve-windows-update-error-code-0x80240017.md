---
title: How to Successfully Resolve Windows Update Error Code 0X80240017
date: 2024-10-03T21:56:23.146Z
updated: 2024-10-06T22:50:16.866Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Resolve Windows Update Error Code 0X80240017
excerpt: This Article Describes How to Successfully Resolve Windows Update Error Code 0X80240017
thumbnail: https://thmb.techidaily.com/578092e9e17a69c476b3082e47519b7819155a500c43a741b28a10c98f28c4a5.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087390/7443" target="_top" id="2087390">
  <img src="//a.impactradius-go.com/display-ad/7443-2087390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1186864/12108" target="_top" id="1186864">
  <img src="//a.impactradius-go.com/display-ad/12108-1186864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1186864/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123731/7443" target="_top" id="2123731">
  <img src="//a.impactradius-go.com/display-ad/7443-2123731" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123731/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123730/7443" target="_top" id="2123730">
  <img src="//a.impactradius-go.com/display-ad/7443-2123730" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123730/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-the-pathway-to-captivating-audio-on-macos-via-audacity/"><u>[New] In 2024, The Pathway to Captivating Audio on MacOS via Audacity</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/2024-approved-webcam-perfection-in-live-streaming-and-recording/"><u>2024 Approved WebCam Perfection in Live-Streaming and Recording</u></a></li>
<li><a href="https://common-error.techidaily.com/bones/"><u>Bones</u></a></li>
<li><a href="https://common-error.techidaily.com/breaking-free-from-the-loop-strategies-to-resolve-infinite-load-in-valorant/"><u>Breaking Free From the Loop: Strategies to Resolve Infinite Load in Valorant</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-internet-sharing-mastering-usb-tethering-on-windows-11/"><u>Effortless Internet Sharing: Mastering USB Tethering on Windows 11</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-vivo-y78t-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Vivo Y78t | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-stuck-keyboard-buttons-on-windows-pcs-a-comprehensive-guide/"><u>Fixing Stuck Keyboard Buttons on Windows PCs: A Comprehensive Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-efficient-techniques-for-saving-online-meeting-transcripts/"><u>In 2024, Efficient Techniques for Saving Online Meeting Transcripts</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-use-google-assistant-on-your-lock-screen-of-nubia-red-magic-9-pro-phone-by-drfone-android/"><u>In 2024, How to Use Google Assistant on Your Lock Screen Of Nubia Red Magic 9 Pro Phone</u></a></li>
<li><a href="https://media-tips.techidaily.com/iphone-11-streaming-how-to-cast-ios-13s-4k-airplay-on-windows-10-and-mac-os/"><u>IPhone 11 Streaming: How to Cast IOS 13'S 4K AirPlay on Windows 10 and Mac OS</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/new-2024-approved-charting-the-best-affordable-virtual-studio-technology-enhancers-for-todays-producers/"><u>New 2024 Approved Charting the Best Affordable Virtual Studio Technology Enhancers for Todays Producers</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-exploring-the-causes-of-your-windows-10-machines-unexpected-boot-cycles/"><u>Resolved! Exploring the Causes of Your Windows 10 Machine's Unexpected Boot Cycles</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-install-failures-of-windows-10-build-1607/"><u>Resolving Install Failures of Windows 10 Build 1607</u></a></li>
<li><a href="https://hardware-help.techidaily.com/seamless-connectivity-and-quality-sound-a-comprehensive-beats-pill-bluetooth-speaker-assessment/"><u>Seamless Connectivity & Quality Sound: A Comprehensive Beats Pill Bluetooth Speaker Assessment</u></a></li>
<li><a href="https://driver-download.techidaily.com/swift-installation-guide-razer-mamba-driver-downloads-available-here/"><u>Swift Installation Guide: Razer Mamba Driver Downloads Available Here</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207539518-troubleshooting-persistent-windows-updates-issues-solved/"><u>Troubleshooting Persistent Windows Updates Issues - Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-step-by-step-for-code-224003-unplayable-video-errors-resolved/"><u>Troubleshooting Step-by-Step for Code 224003: Unplayable Video Errors Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-restoring-functionality-of-non-working-hp-laptop-webcam-on-windows-10/"><u>Troubleshooting Steps: Restoring Functionality of Non-Working HP Laptop Webcam on Windows 10</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/unleash-the-potential-of-your-web-analytics-with-cookiebot-technology/"><u>Unleash the Potential of Your Web Analytics with Cookiebot Technology</u></a></li>
</ul></div>

