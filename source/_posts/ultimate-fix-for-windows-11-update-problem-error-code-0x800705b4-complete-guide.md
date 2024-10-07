---
title: Ultimate Fix for Windows 11 Update Problem (Error Code 0X800705b4) - Complete Guide
date: 2024-10-04T07:38:00.572Z
updated: 2024-10-06T18:26:58.392Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Ultimate Fix for Windows 11 Update Problem (Error Code 0X800705b4) - Complete Guide
excerpt: This Article Describes Ultimate Fix for Windows 11 Update Problem (Error Code 0X800705b4) - Complete Guide
thumbnail: https://thmb.techidaily.com/99d21901c046ee167dc651651f4c0a4a5fcaa0180bc67e42c2265df29bcc90c2.png
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094477/7443" target="_top" id="2094477">
  <img src="//a.impactradius-go.com/display-ad/7443-2094477" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094477/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2118320/7443" target="_top" id="2118320">
  <img src="//a.impactradius-go.com/display-ad/7443-2118320" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118320/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135350/19272" target="_top" id="2135350">
  <img src="//a.impactradius-go.com/display-ad/19272-2135350" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135350/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925544/19272" target="_top" id="1925544">
  <img src="//a.impactradius-go.com/display-ad/19272-1925544" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925544/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://twitter-videos.techidaily.com/new-2024-approved-tweet-town-ranking-the-trending-threads/"><u>[New] 2024 Approved Tweet Town Ranking the Trending Threads</u></a></li>
<li><a href="https://common-error.techidaily.com/banish-minecraft-lags-top-tips-and-tricks-for-optimal-performance/"><u>Banish Minecraft Lags: Top Tips & Tricks for Optimal Performance</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/capture-and-share-your-win10-gaming-life/"><u>Capture and Share Your Win10 Gaming Life</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-get-your-spacebar-working-again-in-the-latest-windows-11-update/"><u>Expert Tips to Get Your Spacebar Working Again in the Latest Windows 11 Update</u></a></li>
<li><a href="https://discord-videos.techidaily.com/exploring-the-distinctions-and-relationships-of-mpeg-4-vs-mp4-in-video-formats/"><u>Exploring the Distinctions & Relationships of MPEG-4 Vs. MP4 in Video Formats</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-implemented-overcome-your-keyboards-typewriting-malfunctions/"><u>Fix Implemented: Overcome Your Keyboard's Typewriting Malfunctions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209815930-harmonizing-display-and-timing-monitor-support-now-restored/"><u>Harmonizing Display and Timing - Monitor Support Now Restored!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-dvd-compatibility-problems-in-windows/"><u>How to Resolve DVD Compatibility Problems in Windows</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pioneering-methods-for-increased-srt-on-macoswindows/"><u>In 2024, Pioneering Methods for Increased SRT on macOS/Windows</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-the-ultimate-quest-achieving-immaculate-upconversion-from-sdr-to-hdri/"><u>In 2024, The Ultimate Quest Achieving Immaculate Upconversion From SDR to HDRI</u></a></li>
<li><a href="https://extra-information.techidaily.com/innovative-approach-stitching-gopro-sequences-in-holoscopic-clips/"><u>Innovative Approach Stitching GoPro Sequences in Holoscopic Clips</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-windows-11-maintennance-essential-techniques-with-sfc-and-dism/"><u>Mastering Windows 11 Maintennance: Essential Techniques with SFC and DISM</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-shockwave-flash-functionality-on-google-chrome-fixing-the-crash-problem/"><u>Restoring Shockwave Flash Functionality on Google Chrome – Fixing the Crash Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-of-fuzzy-font-ultimate-guide-to-sharpening-text-on-windows-10/"><u>Solving the Dilemma of Fuzzy Font: Ultimate Guide to Sharpening Text on Windows 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/startup-steps-for-stream-money-in-periscope/"><u>Startup Steps for Stream Money in Periscope</u></a></li>
<li><a href="https://fox-http.techidaily.com/the-artisans-blueprint-for-striking-image-collage-for-2024/"><u>The Artisan's Blueprint for Striking Image Collage for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/transformer-facilement-un-fichier-mpeg-en-format-3g2-avec-le-convertisseur-gratuit-de-movavi-en-ligne/"><u>Transformer Facilement Un Fichier MPEG en Format 3G2 Avec Le Convertisseur Gratuit De Movavi en Ligne</u></a></li>
</ul></div>

