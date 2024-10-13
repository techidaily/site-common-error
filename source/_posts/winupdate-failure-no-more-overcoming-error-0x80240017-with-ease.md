---
title: WinUpdate Failure No More! Overcoming Error 0X80240017 with Ease
date: 2024-10-07T01:44:04.859Z
updated: 2024-10-13T00:34:07.421Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes WinUpdate Failure No More! Overcoming Error 0X80240017 with Ease
excerpt: This Article Describes WinUpdate Failure No More! Overcoming Error 0X80240017 with Ease
thumbnail: https://thmb.techidaily.com/f57a9586a5db5cbabd97e9f5c59c1d3f3c5f4750932e683ace8971b27daaa651.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

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
<a href="https://wigfever.sjv.io/c/5597632/2014849/22899" target="_top" id="2014849">
  <img src="//a.impactradius-go.com/display-ad/22899-2014849" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014849/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134498/18498" target="_top" id="2134498">
  <img src="//a.impactradius-go.com/display-ad/18498-2134498" border="0" alt="https://techidaily.com" width="720" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134498/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885932/19272" target="_top" id="1885932">
  <img src="//a.impactradius-go.com/display-ad/19272-1885932" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885932/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137204/26400" target="_top" id="2137204">
  <img src="//a.impactradius-go.com/display-ad/26400-2137204" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137204/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://homestyler.sjv.io/c/5597632/1943647/22993" target="_top" id="1943647">
  <img src="//a.impactradius-go.com/display-ad/22993-1943647" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://homestyler.sjv.io/i/5597632/1943647/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-turn-off-chatter-secrets-for-muting-users-on-gomeet-for-2024/"><u>[New] Turn Off Chatter Secrets for Muting Users on GoMeet for 2024</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-high-speed-video-snapshots-avoid-technical-hurdles/"><u>[Updated] High-Speed Video Snapshots - Avoid Technical Hurdles</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-in-2024-transforming-facebook-watchlists-implementing-autoplay-for-youtube-content/"><u>[Updated] In 2024, Transforming Facebook Watchlists Implementing Autoplay for YouTube Content</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-invisible-pointers-heres-how-you-can-restore-it-on-windows/"><u>Dealing with Invisible Pointers? Here's How You Can Restore It on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-overcoming-minecraft-wont-open-in-windows-problems/"><u>Expert Advice for Overcoming 'Minecraft Won't Open in Windows' Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-resolving-xbox-one-headset-connectivity-issues/"><u>Expert Advice: Resolving Xbox One Headset Connectivity Issues</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/gain-massive-audience-on-youtube-in-minutes-2-ways-for-2024/"><u>Gain Massive Audience on YouTube in Minutes (2 Ways) for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-11-best-location-changers-for-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>In 2024, 11 Best Location Changers for Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-8-best-apps-for-screen-mirroring-tecno-pop-8-pc-drfone-by-drfone-android/"><u>In 2024, 8 Best Apps for Screen Mirroring Tecno Pop 8 PC | Dr.fone</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-your-samsung-galaxy-xcover-7-screen-to-pc-with-chromecast-drfone-by-drfone-android/"><u>In 2024, How to Mirror Your Samsung Galaxy XCover 7 Screen to PC with Chromecast | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-samsung-galaxy-a14-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Samsung Galaxy A14 5G | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-lowering-sound-gradually-a-logic-pro-method/"><u>In 2024, Lowering Sound Gradually A Logic Pro Method</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-fixing-critical-installation-failure-error-code-1603/"><u>Solved: Fixing Critical Installation Failure (Error Code 1603)</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-printer-problems-why-you-cant-print-without-the-right-driver/"><u>Solving Printer Problems: Why You Can't Print Without the Right Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fix-a-broken-dvd-or-cd-reader-on-windows-computers/"><u>Step-by-Step Guide to Fix a Broken DVD or CD Reader on Windows Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-touchpad-solutions-for-nonfunctional-scroll-buttons/"><u>Troubleshooting Windows 11 Touchpad: Solutions for Nonfunctional Scroll Buttons</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209826247-windows-11-hangs-and-cant-turn-off-here-are-five-effective-solutions/"><u>Windows 11 Hangs and Can't Turn Off? Here Are Five Effective Solutions</u></a></li>
</ul></div>

