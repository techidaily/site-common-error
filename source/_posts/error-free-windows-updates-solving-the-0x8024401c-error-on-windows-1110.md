---
title: "Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10"
date: 2024-09-13T18:08:49.004Z
updated: 2024-09-20T19:24:39.466Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10"
excerpt: "This Article Describes Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10"
thumbnail: https://thmb.techidaily.com/e2da78d08e286d9059a644d8b709c84167652f494081b2ccfa2bb5a7fc50971b.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139122/17108" target="_top" id="2139122">
  <img src="//a.impactradius-go.com/display-ad/17108-2139122" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139122/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2115932/19272" target="_top" id="2115932">
  <img src="//a.impactradius-go.com/display-ad/19272-2115932" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115932/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-duality-in-display-rotating-videos-on-instagram-one-click-at-a-time/"><u>[New] 2024 Approved Duality in Display Rotating Videos on Instagram, One Click at a Time</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-the-essential-guide-to-shopping-for-a-gopro-camera/"><u>[New] The Essential Guide to Shopping for a Gopro Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-10-freezes-on-startup-or-boot/"><u>[Solved] Windows 10 Freezes on Startup or Boot</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-windows-10-gamers-guide-to-effective-video-capture/"><u>[Updated] Windows 10 Gamers' Guide to Effective Video Capture</u></a></li>
<li><a href="https://common-error.techidaily.com/conquer-high-gpu-demands-from-windows-11s-dwm-discover-five-essential-solutions/"><u>Conquer High GPU Demands From Windows 11’S DWM - Discover Five Essential Solutions</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-update-amd-rx-480-gpu-drivers-with-simplicity/"><u>Download and Update AMD RX 480 GPU Drivers with Simplicity</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-crashes-in-nier-automata-windows-edition/"><u>How to Fix Crashes in Nier: Automata Windows Edition</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-icloud-lock-on-your-apple-iphone-13-mini-and-ipad-by-drfone-ios/"><u>How to fix iCloud lock on your Apple iPhone 13 mini and iPad</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-tailored-titles-for-your-youtube-success/"><u>In 2024, Tailored Titles for Your YouTube Success</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/in-depth-analysis-of-the-lenovo-ideapad-stunning-construction-for-essential-use/"><u>In-Depth Analysis of the Lenovo Ideapad: Stunning Construction for Essential Use</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205065502-quick-solutions-for-windows-update-problem-overcome-error-8007000e-today/"><u>Quick Solutions for Windows Update Problem - Overcome Error 8007000E Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/screen-fix-for-non-hid-interactive-response/"><u>Screen Fix for Non-HID Interactive Response</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-resolving-win10-update-error-code-0x800705b4/"><u>Step-by-Step Solutions for Resolving Win10 Update Error Code 0X800705B4</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/ultimate-guide-resolving-no-matches-found-error-on-bumble/"><u>Ultimate Guide: Resolving 'No Matches Found' Error on Bumble</u></a></li>
</ul></div>

