---
title: "Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
date: 2025-01-19T20:38:23.380Z
updated: 2025-01-22T18:11:38.206Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
excerpt: "This Article Describes Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
thumbnail: https://thmb.techidaily.com/063f04ddcc12d7ad0c40343a71ed623fbddb1ebfb8c3b581a5d414d7d362a54b.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qNrOsjUdRz0?si=xGzhmNmtgxNTsRxN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6kzbT13ds3M?si=hBInu0Or-cX2ANJF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UcplMvRBulA?si=iBonbwDS1v7RAlHK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0OxkndZbIA4?si=TWJlkTbYKsVag8-q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-clips.techidaily.com/new-2024-approved-deciphering-fb-video-dimensions-for-perfect-sharing/"><u>[New] 2024 Approved Deciphering FB Video Dimensions for Perfect Sharing</u></a></li>
<li><a href="https://fox-blue.techidaily.com/new-2024-approved-sdr-upgrade-manual-unveiling-the-secrets-of-hdr-transformation/"><u>[New] 2024 Approved SDR Upgrade Manual Unveiling the Secrets of HDR Transformation</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-digital-video-capturing-demystified-systematic-guide-for-2024/"><u>[Updated] Digital Video Capturing Demystified Systematic Guide for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/design-thinking-for-content-creators-crafting-impactful-facebook-reels/"><u>Design Thinking for Content Creators Crafting Impactful Facebook Reels</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-solving-d3derrnotavailable-error-with-ease/"><u>Expert Advice on Solving 'D3DERR_NOTAVAILABLE' Error with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-stalled-or-halted-windows-11-update-process-guide/"><u>Fixing a Stalled or Halted Windows 11 Update Process - Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/forgot-locked-iphone-12-pro-max-password-learn-the-best-methods-to-unlock-by-drfone-ios/"><u>Forgot Locked iPhone 12 Pro Max Password? Learn the Best Methods To Unlock</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-freezing-or-crashing-windows-10-system/"><u>How to Fix a Freezing or Crashing Windows 10 System</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-google-play-location-on-realme-c51-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Google Play Location On Realme C51 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-manually-shutting-down-unresponsive-pcs-on-windows-10-solved/"><u>Mastering The Art Of Manually Shutting Down Unresponsive PCs on Windows 10 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-error-1-section-1-problem-advanced-pulse-modulation-techniques/"><u>Mastering the Fix: Error 1 # Section 1: Problem - Advanced Pulse Modulation Techniques</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/maximizing-your-home-network-potential-a-complete-netgear-nighthawk-ax8-wi-fi/"><u>Maximizing Your Home Network Potential: A Complete Netgear Nighthawk AX8 Wi-Fi</u></a></li>
<li><a href="https://common-error.techidaily.com/reveal-your-touchpad-master-device-management-solutions/"><u>Reveal Your Touchpad: Master Device Management Solutions!</u></a></li>
<li><a href="https://sound-issues.techidaily.com/skype-audio-not-working-heres-how-you-can-fix-it-easily/"><u>Skype Audio Not Working? Here’s How You Can Fix It Easily</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/speedy-pc-file-examination-guide-for-2024/"><u>Speedy PC File Examination Guide for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-critical-issues-fixing-irreparable-directx-error-messages/"><u>Tackling Critical Issues: Fixing Irreparable DirectX Error Messages</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-error-code-0x800f0922-in-windows-10-top-fixes-you-need-to-know/"><u>Winning Against Error Code 0X800F0922 in Windows 10 - Top Fixes You Need to Know!</u></a></li>
</ul></div>

