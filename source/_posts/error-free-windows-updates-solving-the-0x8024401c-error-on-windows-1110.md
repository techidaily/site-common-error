---
title: "Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10"
date: 2024-09-14T16:10:27.434Z
updated: 2024-09-15T16:04:06.501Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10"
excerpt: "This Article Describes Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10"
thumbnail: https://thmb.techidaily.com/e2da78d08e286d9059a644d8b709c84167652f494081b2ccfa2bb5a7fc50971b.jpg
---

## Expert Advice on Correcting Windows Update Failure with Error Code 0X8024402C - Learn How Here

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

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123471/16836" target="_top" id="2123471">
  <img src="//a.impactradius-go.com/display-ad/16836-2123471" border="0" alt="https://techidaily.com" width="234" height="60"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123471/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2098703/14409" target="_top" id="2098703">
  <img src="//a.impactradius-go.com/display-ad/14409-2098703" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2098703/14409" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/updated-fast-lanes-migrating-iphone-media-to-a-desktop/"><u>[Updated] Fast Lanes Migrating iPhone Media to a Desktop</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-top-10-ingenious-ae-techniques-for-headline-hype/"><u>[Updated] Top 10 Ingenious AE Techniques for Headline Hype</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-windows-update-stuck-at-0-issue/"><u>Easy to Fix Windows Update Stuck at 0% Issue</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-predictive-ai-techniques-and-processes-involved/"><u>Exploring Predictive AI: Techniques and Processes Involved</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-a-comprehensive-guide-to-icloud-unlock-on-apple-iphone-7-plus-online-by-drfone-ios/"><u>In 2024, A Comprehensive Guide to iCloud Unlock On Apple iPhone 7 Plus Online</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-infinix-hot-40i-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Infinix Hot 40i</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-troubleshooting-of-persistent-windows-10-update-failures/"><u>Master the Troubleshooting of Persistent Windows 10 Update Failures</u></a></li>
<li><a href="https://extra-hints.techidaily.com/melodies-and-movie-editing-imovie-edition/"><u>Melodies & Movie Editing IMovie Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-an-unresponsive-microsoft-store-a-step-by-step-fix/"><u>Overcoming the Challenge of an Unresponsive Microsoft Store: A Step-by-Step Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-the-soundscape-solving-silent-issues-with-your-acer-pc/"><u>Revive the Soundscape: Solving Silent Issues with Your Acer PC</u></a></li>
<li><a href="https://unlock-android.techidaily.com/rootjunky-apk-to-bypass-google-frp-lock-for-infinix-note-30-vip-racing-edition-by-drfone-android/"><u>Rootjunky APK To Bypass Google FRP Lock For Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restore-keyboard-activity-on-a-dell-computer/"><u>Step-by-Step Guide to Restore Keyboard Activity on a Dell Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/successfully-resolved-windows-updates-now-working/"><u>Successfully Resolved: Windows Updates Now Working</u></a></li>
<li><a href="https://win11-tips.techidaily.com/troubleshooting-faulty-volume-shadows-in-win/"><u>Troubleshooting Faulty Volume Shadows in Win</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-what-to-do-when-your-usb-isnt-detected/"><u>Troubleshooting Guide: What to Do When Your USB Isn't Detected</u></a></li>
</ul></div>

