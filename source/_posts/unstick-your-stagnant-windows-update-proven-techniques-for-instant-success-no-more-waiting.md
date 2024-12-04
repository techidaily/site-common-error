---
title: "Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)"
date: 2024-11-27T22:22:16.660Z
updated: 2024-12-04T07:16:18.233Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)"
excerpt: "This Article Describes Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)"
thumbnail: https://thmb.techidaily.com/33c08cf35f6b5e5c15d53520e124508a521ab9ce21cadff2a0841b9ab0ad5414.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JAkb8Bv3AU4?si=2rHwnZYTzTLieKgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3hS27nZVi9Y?si=_Zqj_l4a4XkPqT2S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DxUX4R6Cf7c?si=prHevNQJivSkIfUt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://article-helps.techidaily.com/new-in-2024-the-composers-craft-crossfade-in-logic-pro-x/"><u>[New] In 2024, The Composer's Craft - Crossfade in Logic Pro X</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/tepwise-revelation-of-concealed-youtube-archives-for-2024/"><u>[New] Stepwise Revelation of Concealed YouTube Archives for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-implement-shutter-speed-blurring-in-psx/"><u>[Updated] In 2024, Implement Shutter Speed Blurring in PSX</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-recording-skype-calls-quick-guide-for-windows-and-mac-users/"><u>[Updated] Recording Skype Calls - Quick Guide for Windows and Mac Users</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-correcting-failed-directx-renderer-creation/"><u>Effective Solutions for Correcting Failed DirectX Renderer Creation</u></a></li>
<li><a href="https://common-error.techidaily.com/exploring-the-purpose-of-msdia80dll-file-should-you-keep-or-delete/"><u>Exploring the Purpose of msdia80.dll File - Should You Keep or Delete?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-acquire-safekey-permissions-for-altering-data-files/"><u>How to Acquire SafeKey Permissions for Altering Data Files</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-send-and-fake-live-location-on-facebook-messenger-of-your-realme-12-5g-drfone-by-drfone-virtual-android/"><u>How to Send and Fake Live Location on Facebook Messenger Of your Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-cutting-edge-tools-for-digital-video-capture/"><u>In 2024, Cutting-Edge Tools for Digital Video Capture</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-bypass-android-lock-screen-using-emergency-call-on-samsung-galaxy-a14-4g-by-drfone-android/"><u>In 2024, How to Bypass Android Lock Screen Using Emergency Call On Samsung Galaxy A14 4G?</u></a></li>
<li><a href="https://games-able.techidaily.com/ios-interactivity-choosing-apple-arcade-as-a-key-player/"><u>IOS Interactivity: Choosing Apple Arcade as a Key Player</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209542700-resolve-0xa00f4292-windows-camera-issue-with-easy-troubleshooting-steps/"><u>Resolve 0xA00F4292 Windows Camera Issue with Easy Troubleshooting Steps!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-deadly-glitches-in-battlefield-v-a-step-by-step-guide/"><u>Resolving Deadly Glitches in Battlefield V: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-fixing-windows-stop-error-0xc00-grove-e9-effectively/"><u>Step-by-Step Solutions: Fixing Windows Stop Error 0Xc00 Grove E9 Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-how-to-troubleshoot-and-repair-your-sony-playstation-4-microphone-issues/"><u>Ultimate Guide: How to Troubleshoot and Repair Your Sony PlayStation 4 Microphone Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-the-unavailable-desktop-path-in-windows-system-profile/"><u>Understanding and Fixing the Unavailable Desktop Path in Windows System Profile</u></a></li>
<li><a href="https://win11.techidaily.com/unveiling-the-secrets-of-wintoys-a-must-have-for-windows-users/"><u>Unveiling the Secrets of 'WinToys': A Must-Have for Windows Users</u></a></li>
</ul></div>

