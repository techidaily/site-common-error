---
title: "Resolving 'Server Not Found': 4 Proven Techniques for Unresponsive DNS Issues"
date: 2024-09-30T03:19:58.252Z
updated: 2024-10-06T23:46:23.617Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving 'Server Not Found': 4 Proven Techniques for Unresponsive DNS Issues"
excerpt: "This Article Describes Resolving 'Server Not Found': 4 Proven Techniques for Unresponsive DNS Issues"
thumbnail: https://thmb.techidaily.com/015ca8337481fa9d7a46737ec3890e681969035749527955b33fb723b973c5c1.jpg
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

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<span id="1983475">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983475.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983475">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983475.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983475%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983475/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082520/7443" target="_top" id="2082520">
  <img src="//a.impactradius-go.com/display-ad/7443-2082520" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082520/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043638/7443" target="_top" id="2043638">
  <img src="//a.impactradius-go.com/display-ad/7443-2043638" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043638/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-helps.techidaily.com/new-reimagine-virtual-engagements-with-customized-video-filters-in-zoom-for-2024/"><u>[New] Reimagine Virtual Engagements with Customized Video Filters in Zoom for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-setup-made-simple-installing-vrecorder-for-2024/"><u>[New] Setup Made Simple Installing VRecorder for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-showcasing-design-brilliance-best-10-text-setups-in-ae/"><u>[New] Showcasing Design Brilliance Best 10 Text Setups in AE</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/androids-finest-moba-battles-compilation-10-edition/"><u>Android's Finest MOBA Battles Compilation (#10 Edition)</u></a></li>
<li><a href="https://common-error.techidaily.com/brighten-your-display-fix-blurry-screen-on-windows-10-with-these-simple-tweaks/"><u>Brighten Your Display: Fix Blurry Screen on Windows 10 with These Simple Tweaks</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-best-no-entry-price-voice-transformation-for-valorant-gamers/"><u>In 2024, Best No-Entry Price Voice Transformation for Valorant Gamers</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-samsung-galaxy-xcover-6-pro-tactical-edition-to-any-ios-devices-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Samsung Galaxy XCover 6 Pro Tactical Edition to Any iOS Devices | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/1719579855799-mondlys-lifetime-plan-zero-price/"><u>Mondly's Lifetime Plan: Zero Price!</u></a></li>
<li><a href="https://common-error.techidaily.com/quickly-restore-bluetooth-functionality-on-your-windows-11-pc-easy-methods-inside/"><u>Quickly Restore Bluetooth Functionality on Your Windows 11 PC: Easy Methods Inside!</u></a></li>
<li><a href="https://windows11.techidaily.com/resolve-your-black-screen-woes-with-simple-tricks-for-win11/"><u>Resolve Your Black Screen Woes with Simple Tricks for Win11</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-cannot-access-device-pathfile-in-windows-fix-guide/"><u>Solving 'Cannot Access Device Path/File' In Windows - Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-repairing-common-werfaultexe-windows-issues-with-minimal-hassle/"><u>Step-by-Step Guide: Repairing Common werFault.exe Windows Issues with Minimal Hassle</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-repair-tips-for-a-broken-fingerprint-reader-on-lenovo-devices/"><u>Step-by-Step Repair Tips for a Broken Fingerprint Reader on Lenovo Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/stuck-on-a-pdf-not-printing-heres-how-you-can-solve-the-problem-fast/"><u>Stuck on a PDF Not Printing? Here's How You Can Solve the Problem Fast</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-a-malfunctioning-torrent-download/"><u>Troubleshooting Steps for a Malfunctioning Torrent Download</u></a></li>
<li><a href="https://common-error.techidaily.com/usb-connection-issues-beat-device-descriptor-request-failed-with-our-expert-tips/"><u>USB Connection Issues? Beat 'Device Descriptor Request Failed' With Our Expert Tips!</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/visionmaster-vs-screencapturer-for-2024/"><u>VisionMaster vs ScreenCapturer for 2024</u></a></li>
</ul></div>

