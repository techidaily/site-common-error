---
title: Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems
date: 2024-12-22T20:22:14.188Z
updated: 2024-12-25T17:13:21.650Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems
excerpt: This Article Describes Step-by-Step Solution to Overcome the Windows Update Failure 'Error 0X8024401C' In Windows 11/11 Systems
thumbnail: https://thmb.techidaily.com/89f58c00fabb0b3ac26622205cb1b82f67ddb2d733ca5558e5f2d4e68026f7eb.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/6X24fPKs6AE?si=YtQy-8zy7GifgfA7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fHWdQw1gRyI?si=ve9wZnPupiooLThG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LBCobAYzzcc?si=J3eSTQ3AdyxWAjGo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aoMiYpYiFZs?si=qvYvGytDD17fvSXO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Bov2KfWQ_Y?si=MnVczisgeJ-sGW2r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://extra-hints.techidaily.com/new-crafting-success-steps-to-thriving-as-a-designer/"><u>[New] Crafting Success Steps to Thriving as a Designer</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-elevate-video-quality-with-pro-tools-selection-for-2024/"><u>[New] Elevate Video Quality with Pro Tools Selection for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-unlock-the-power-of-any-video-with-these-free-online-editors/"><u>[Updated] 2024 Approved Unlock the Power of Any Video With These Free Online Editors</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-maximize-your-youtube-yields-small-channel-sponsorship-strategies-for-2024/"><u>[Updated] Maximize Your YouTube Yields Small Channel Sponsorship Strategies for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/descargue-convertidor-de-video-de-todos-los-formatos-al-formato-mov-en-linea-sin-coste-alguno-moovavi/"><u>Descargue Convertidor De Video De Todos Los Formatos Al Formato MOV En Línea Sin Coste Alguno - Moovavi</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-repairing-https-errors-and-securing-firefox-connections-effectively/"><u>Guide: Repairing HTTPS Errors and Securing Firefox Connections Effectively</u></a></li>
<li><a href="https://fox-http.techidaily.com/in-2024-complete-analysis-triangulating-life-with-samsung-vr/"><u>In 2024, Complete Analysis Triangulating Life with Samsung VR</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-through-the-best-picks-in-instagram-ringtone-and-exceptional-alerts/"><u>In 2024, Navigating Through the Best Picks in Instagram Ringtone & Exceptional Alerts</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-restoring-functionality-to-windows-keyboards-with-sticking-keys/"><u>Mastering the Art of Restoring Functionality to Windows Keyboards with Sticking Keys.</u></a></li>
<li><a href="https://common-error.techidaily.com/repaired-non-typing-functionality-of-keyboard/"><u>Repaired: Non-Typing Functionality of Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-functionality-to-your-windows-10-touch-display-with-these-simple-fixes/"><u>Restore Functionality to Your Windows 10 Touch Display with These Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210724719-surface-book-pro-n-cam-trouble-on-windows-11-solutions-inside/"><u>Surface Book (Pro N) Cam Trouble on Windows 11 - Solutions Inside!</u></a></li>
<li><a href="https://win11-tips.techidaily.com/win11-voice-control-commands-quick-guide/"><u>Win11 Voice Control Commands Quick Guide</u></a></li>
<li><a href="https://win-deluxe.techidaily.com/44k744kv44k44oq44kk44k744kv44k5oqa6kgt44gn5a6f54plusplus44gz44kl44kv44ot44o844oz5l2c5oiq5a6m5ywo44oe44ol44ol44ki44or44g4/"><u>セクタバイセクタ技術で実現するクローン作成完全マニュアルへ</u></a></li>
</ul></div>

