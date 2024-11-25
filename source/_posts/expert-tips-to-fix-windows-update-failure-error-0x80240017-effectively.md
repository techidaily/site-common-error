---
title: Expert Tips to Fix Windows Update Failure (Error 0X80240017) Effectively
date: 2024-11-19T19:19:14.000Z
updated: 2024-11-24T18:43:16.422Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips to Fix Windows Update Failure (Error 0X80240017) Effectively
excerpt: This Article Describes Expert Tips to Fix Windows Update Failure (Error 0X80240017) Effectively
thumbnail: https://thmb.techidaily.com/dfad489a283b58802ec92c884b7191bbab4a284ecb771027987a79177a9a76e0.jpg
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-G7cU8dYvuI?si=JaKqRcW6qq9CDvty&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gkdZ3A1mock?si=2zeR5GtTU2VujM_w&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aa6vSdt1elM?si=qPhmO-hoWVIPBnnC&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/new-2024-approved-effortless-instagram-media-export-top-20-free-mp4-converters-online/"><u>[New] 2024 Approved Effortless Instagram Media Export Top 20 Free MP4 Converters Online</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-summer-screen-escapades-top-10-classic-kids-films/"><u>[New] Summer Screen Escapades Top 10 Classic Kid's Films</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-high-altitude-escapades-the-husqvarna-h501s-review-explored/"><u>[Updated] High Altitude Escapades - The Husqvarna H501S Review Explored</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-luxury-sedan-sj4000s-best-kept-secrets-gear-up/"><u>[Updated] Luxury Sedan SJ4000's Best-Kept Secrets Gear Up</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-styling-your-content-a-compreran-guide-to-insta-photo-watermarks-for-2024/"><u>[Updated] Styling Your Content A Compreran Guide to Insta Photo Watermarks for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-tap-into-endless-stock-imagery-through-favorite-4-youtube-vids/"><u>[Updated] Tap Into Endless Stock Imagery Through Favorite 4 Youtube Vids</u></a></li>
<li><a href="https://common-error.techidaily.com/5-easy-steps-to-eliminate-the-never-ending-reboots-of-windows-10/"><u>5 Easy Steps to Eliminate the Never-Ending Reboots of Windows 10</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ding-with-expertise-mastering-the-art-and-science-of-asmr-production/"><u>Ascending with Expertise Mastering The Art & Science of ASMR Production</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/essential-strategies-for-selecting-amazing-pexels-images/"><u>Essential Strategies for Selecting Amazing Pexels Images</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-windows-11-display-dimming-issues-resolved/"><u>Fix: Windows 11 Display Dimming Issues Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-update-issues-quick-guide-to-restart-the-service/"><u>Fixing Windows Update Issues: Quick Guide to Restart the Service</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-change-lock-screen-wallpaper-on-motorola-edge-40-by-drfone-android/"><u>How to Change Lock Screen Wallpaper on Motorola Edge 40</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-cannot-play-video-issue-with-code-22-a-step-by-step-fix/"><u>Overcome 'Cannot Play' Video Issue with Code 22# - A Step-by-Step Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-error-1053-ensuring-prompt-service-responsiveness-to-start-requests/"><u>Overcoming Error 1053: Ensuring Prompt Service Responsiveness to Start Requests</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-issues-with-windows-smartscreen-being-inaccessible-at-the-moment/"><u>Overcoming Issues with Windows SmartScreen Being Inaccessible at the Moment</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-lenovo-mouse-pad-issues-on-windows-11-8-and-7-comprehensive-fix-guide/"><u>Solving Lenovo Mouse Pad Issues on Windows 11, 8 & 7 – Comprehensive Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-unfreezing-file-explorer-in-windows-10/"><u>Step-by-Step Solutions: Unfreezing File Explorer in Windows 10</u></a></li>
<li><a href="https://tech-haven.techidaily.com/transform-your-kitchen-with-chatgpt-top-7-strategies-for-aspiring-chefs/"><u>Transform Your Kitchen with ChatGPT - Top 7 Strategies for Aspiring Chefs</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206300964-windows-11-users-say-goodbye-to-skype-video-problems-with-these-easy-fixes/"><u>Windows 11 Users, Say Goodbye to Skype Video Problems with These Easy Fixes!</u></a></li>
</ul></div>

