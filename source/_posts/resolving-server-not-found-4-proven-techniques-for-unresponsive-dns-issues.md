---
title: "Resolving 'Server Not Found': 4 Proven Techniques for Unresponsive DNS Issues"
date: 2024-09-29T21:00:16.562Z
updated: 2024-10-02T04:21:37.159Z
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

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139118/17108" target="_top" id="2139118">
  <img src="//a.impactradius-go.com/display-ad/17108-2139118" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139118/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997722/19272" target="_top" id="1997722">
  <img src="//a.impactradius-go.com/display-ad/19272-1997722" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997722/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2094479/7443" target="_top" id="2094479">
  <img src="//a.impactradius-go.com/display-ad/7443-2094479" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094479/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135399/19272" target="_top" id="2135399">
  <img src="//a.impactradius-go.com/display-ad/19272-2135399" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135399/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/new-icy-innovations-on-ice-olympic-edition/"><u>[New] Icy Innovations on Ice - Olympic Edition</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-brand-awakening-on-reddit-7-easy-steps-to-market-mastery/"><u>[Updated] Brand Awakening on Reddit 7 Easy Steps to Market Mastery</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-capture-save-and-share-mastering-playstation-4-recordings/"><u>[Updated] In 2024, Capture, Save & Share Mastering PlayStation 4 Recordings</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-churning-charts-todays-1-backdrop-music-for-youtube-shorts/"><u>[Updated] In 2024, Churning Charts Today's #1 Backdrop Music for YouTube Shorts</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-unlock-the-power-of-persuasion-perfecting-your-shorts-visual-hook-for-2024/"><u>[Updated] Unlock the Power of Persuasion Perfecting Your Shorts' Visual Hook for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-heaviest-heroes-in-the-air-drone-power-list/"><u>2024 Approved Heaviest Heroes in the Air Drone Power List</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-the-skys-boldest-workhorses-top-10-drones/"><u>2024 Approved The Sky's Boldest Workhorses - Top 10 Drones</u></a></li>
<li><a href="https://blog-min.techidaily.com/windows-11-dvd-shrink-dvd/"><u>對於 Windows 11 用户而言，如何在當前系統不支持 DVD Shrink時進行 DVD 資料庫備份？</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/brief-basslines-and-rhythms-video-soundscapes-for-2024/"><u>Brief Basslines & Rhythms Video Soundscapes for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-to-fix-the-windows-update-failed-with-code-0x8024002e/"><u>Effective Solutions to Fix the 'Windows Update Failed with Code 0X8024002E'</u></a></li>
<li><a href="https://common-error.techidaily.com/from-broken-to-secure-fixing-problematic-windows-update-processes/"><u>From Broken to Secure: Fixing Problematic Windows Update Processes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-undetected-bluetooth-gadgets-in-windows-10/"><u>How to Resolve Undetected Bluetooth Gadgets in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-windows-entry-point-missing-error-fix/"><u>Step-by-Step Solution for Windows 'Entry Point Missing' Error Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-lenovo-mouse-pad-in-windows-operating-systems/"><u>Troubleshooting Non-Responsive Lenovo Mouse Pad in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-troubleshooting-for-valorant-how-to-stop-screen-tearing-once-and-for-all/"><u>Ultimate Troubleshooting for Valorant: How To Stop Screen Tearing Once and For All</u></a></li>
</ul></div>

