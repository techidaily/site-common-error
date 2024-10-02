---
title: Overcoming the Hurdle of Windows 11 Installation Error 80240020 - A Comprehensive Fix
date: 2024-09-30T17:43:49.020Z
updated: 2024-10-01T17:37:21.960Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming the Hurdle of Windows 11 Installation Error 80240020 - A Comprehensive Fix
excerpt: This Article Describes Overcoming the Hurdle of Windows 11 Installation Error 80240020 - A Comprehensive Fix
thumbnail: https://thmb.techidaily.com/ccf2cd6688a4adcaeda8d922b0b91ea561ec3cf2936a8b4a71d20d4455d103fb.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111982/7443" target="_top" id="2111982">
  <img src="//a.impactradius-go.com/display-ad/7443-2111982" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111982/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959759/19272" target="_top" id="1959759">
  <img src="//a.impactradius-go.com/display-ad/19272-1959759" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959759/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2123750/7443" target="_top" id="2123750">
  <img src="//a.impactradius-go.com/display-ad/7443-2123750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123750/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/solved-minecraft-wont-launch-in-windows/"><u>[SOLVED] Minecraft Won’t Launch in Windows</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-2024-approved-2023-how-to-share-twitter-videos-on-whatsapp/"><u>[Updated] 2024 Approved 2023 | How to Share Twitter Videos on WhatsApp?</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-convenient-viewing-setting-up-youtube-on-large-tv-panels/"><u>[Updated] 2024 Approved Convenient Viewing Setting Up YouTube on Large TV Panels</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-inside-the-new-windows-11-innovations/"><u>[Updated] In 2024, Inside the New Windows 11 Innovations</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211671450-airpods-wont-pair-with-windows-11-master-the-fixes-you-need/"><u>AirPods Won't Pair with Windows 11? Master the Fixes You Need</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-setup-successfully-resolved-ensure-smooth-integration-in-games/"><u>BattlEye Setup Successfully Resolved – Ensure Smooth Integration in Games</u></a></li>
<li><a href="https://network-issues.techidaily.com/direct-fix-for-aspect-ratio-skew-on-pcs/"><u>Direct Fix for Aspect Ratio Skew on PCs</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/essential-handbook-for-j-alphabets-and-symbols/"><u>Essential Handbook for J-Alphabets and Symbols</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-cyclic-redundancy-check-failures-in-your-system/"><u>How to Resolve Cyclic Redundancy Check Failures in Your System</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-a-complete-guide-to-oem-unlocking-on-realme-gt-3-by-drfone-android/"><u>In 2024, A Complete Guide To OEM Unlocking on Realme GT 3</u></a></li>
<li><a href="https://fox-blue.techidaily.com/in-2024-understanding-the-upside-to-asmrs-sensory-experience/"><u>In 2024, Understanding the Upside to ASMR's Sensory Experience</u></a></li>
<li><a href="https://fix-guide.techidaily.com/in-2024-why-your-whatsapp-location-is-not-updating-and-how-to-fix-on-honor-magic-5-drfone-by-drfone-virtual-android/"><u>In 2024, Why Your WhatsApp Location is Not Updating and How to Fix On Honor Magic 5 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-trick-to-eliminate-constant-usb-not-detected-pop-ups-for-good/"><u>Master the Trick to Eliminate Constant 'USB Not Detected' Pop-Ups for Good!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-errors-a-comprehensive-step-by-step-fix-for-lenovos-broken-fingerprint-access/"><u>Overcoming Errors: A Comprehensive Step-by-Step Fix for Lenovo's Broken Fingerprint Access</u></a></li>
<li><a href="https://program-issues.techidaily.com/solve-the-problem-unstuck-and-get-your-windows-pressentational-bar-working-again/"><u>Solve the Problem: Unstuck and Get Your Windows Pressentational Bar Working Again</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-effective-tips-for-resolving-windows-11s-black-display-problem/"><u>Solving the Dilemma: Effective Tips for Resolving Windows 11'S Black Display Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-fix-for-windows-n-error-in-updating-or-refreshing-your-computer/"><u>Successful Fix for Windows N Error in Updating or Refreshing Your Computer</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-10-subtitle-converters-no-cost-for-srt-files/"><u>Top 10 Subtitle Converters, No Cost for SRT Files</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-shutdowns-in-windows-10/"><u>Unexpected Shutdowns in Windows 10</u></a></li>
</ul></div>

