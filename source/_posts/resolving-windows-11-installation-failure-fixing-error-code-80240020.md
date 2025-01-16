---
title: "Resolving Windows 11 Installation Failure: Fixing Error Code 80240020"
date: 2025-01-13T16:05:37.482Z
updated: 2025-01-16T16:26:36.157Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Windows 11 Installation Failure: Fixing Error Code 80240020"
excerpt: "This Article Describes Resolving Windows 11 Installation Failure: Fixing Error Code 80240020"
thumbnail: https://thmb.techidaily.com/571b6953560c969952a7e82657ab3c73d752ed211ca4fd673ea682421459ce79.png
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vPGg53vbOsk?si=CkSEN5HFPS7vDuAa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sXLLPY11of0?si=-3YNnpnO0wbc0K_-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gMS5pm0SQlQ?si=gasOo6p2agrVlIb7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/FATJWpNYmio?si=72ugPTb3vJXz6cAM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-channel-growth-guide-top-5-video-marketing-tactics-revealed/"><u>[New] The Ultimate Channel Growth Guide Top 5 Video Marketing Tactics Revealed</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-10-best-vr-videos-on-youtube-to-have-immersive-experience-for-2024/"><u>[Updated] 10 Best VR Videos on YouTube to Have Immersive Experience for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-enhancing-your-stream-5-key-techniques-for-gamers/"><u>[Updated] Enhancing Your Stream 5 Key Techniques for Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/error-0xc000007b-strikes-again-heres-how-to-successfully-launch-your-app/"><u>Error 0Xc000007b Strikes Again? Here's How to Successfully Launch Your App!</u></a></li>
<li><a href="https://win-excellent.techidaily.com/exploring-benefits-why-should-you-consider-crypto-assets-insights-by-yl-computing/"><u>Exploring Benefits: Why Should You Consider Crypto Assets? - Insights by YL Computing</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-error-0x887a0006-instantly-effortless-fix-techniques-unveiled/"><u>Fix Error 0X887A0006 Instantly: Effortless Fix Techniques Unveiled!</u></a></li>
<li><a href="https://win-dash.techidaily.com/free-hp-deskjet-ink-advantage-3050a-drivers-windows-compatible-latest-updates-available/"><u>Free HP Deskjet Ink Advantage 3050A Drivers: Windows Compatible, Latest Updates Available</u></a></li>
<li><a href="https://some-guidance.techidaily.com/in-2024-ultrafine-a-deep-dive-into-lgs-elite-4k-display-features/"><u>In 2024, UltraFine A Deep Dive Into LG's Elite 4K Display Features</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/inside-look-at-apple-watch-series-6-refined-features-keep-it-ahead-of-competition/"><u>Inside Look at Apple Watch Series 6: Refined Features Keep It Ahead of Competition</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-windows-update-issues-getting-the-service-back-on-track/"><u>Resolved: Troubleshooting Windows Update Issues – Getting the Service Back On Track</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203366895-solve-your-bluetooth-woes-windows-11-wireless-fixes-and-tips-for-pairing-success/"><u>Solve Your Bluetooth Woes: Windows ˈ11 Wireless Fixes and Tips for Pairing Success!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-perpetually-halted-100-in-windows-update/"><u>Troubleshooting Guide: Resolving Perpetually Halted 100% in Windows Update</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-volume-is-dirty-error-0x80071ac3/"><u>Understanding and Resolving 'Volume Is Dirty' Error (0X80071AC3)</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-code-0x80070643-your-ultimate-fix-guide-for-windows-updates-and-installation-hiccups/"><u>Unraveling Code 0X80070643: Your Ultimate Fix Guide for Windows Updates and Installation Hiccups</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/upgrade-your-workflow-with-linux-mint-211-an-enhanced-and-sleeker-linux-desktop-choice/"><u>Upgrade Your Workflow with Linux Mint 21.1, an Enhanced and Sleeker Linux Desktop Choice</u></a></li>
</ul></div>

