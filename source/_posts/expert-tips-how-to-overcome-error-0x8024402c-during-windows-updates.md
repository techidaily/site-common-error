---
title: "Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
date: 2025-02-24T05:37:43.643Z
updated: 2025-03-02T11:10:15.825Z
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
<li><a href="https://fox-links.techidaily.com/new-2024-approved-upconversion-unveiled-sdr-to-hdri-a-complete-guide/"><u>[New] 2024 Approved Upconversion Unveiled SDR to HDRI - A Complete Guide</u></a></li>
<li><a href="https://fox-access.techidaily.com/updated-in-2024-top-streaming-technology-for-live-events/"><u>[Updated] In 2024, Top Streaming Technology for Live Events</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/cheap-microphones-for-youtubers-on-a-budget/"><u>Cheap Microphones for Youtubers on a Budget</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209250416-guide-to-fixing-lost-bluetooth-connectivity-in-windows-11-steps-for-swift-resolution/"><u>Guide to Fixing Lost Bluetooth Connectivity in Windows 11: Steps for Swift Resolution!</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-life360-shows-wrong-location-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>How to Fix Life360 Shows Wrong Location On Honor 90 GT? | Dr.fone</u></a></li>
<li><a href="https://article-files.techidaily.com/in-2024-color-theory-and-how-to-use-it/"><u>In 2024, Color Theory And How To Use It</u></a></li>
<li><a href="https://common-error.techidaily.com/in-depth-guide-to-rejuvenate-an-unresponsive-playstation-move-controller/"><u>In-Depth Guide to Rejuvenate an Unresponsive PlayStation Move Controller</u></a></li>
<li><a href="https://win-updates.techidaily.com/restaurar-a-unidade-do-sistema-com-backup-efetivo-usando-uefi/"><u>Restaurar a Unidade Do Sistema Com Backup Efetivo Usando UEFI</u></a></li>
<li><a href="https://common-error.techidaily.com/tech-tragedy-device-lifespan-ended/"><u>Tech Tragedy: Device Lifespan Ended</u></a></li>
<li><a href="https://common-error.techidaily.com/the-complete-walkthrough-resolving-your-windows-1er-bluetooth-pairing-glitches/"><u>The Complete Walkthrough: Resolving Your Windows 1Er Bluetooth Pairing Glitches</u></a></li>
</ul></div>

