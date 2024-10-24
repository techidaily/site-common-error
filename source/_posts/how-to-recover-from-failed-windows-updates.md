---
title: How to Recover From Failed Windows Updates
date: 2024-10-18T17:47:14.887Z
updated: 2024-10-24T22:01:05.889Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Recover From Failed Windows Updates
excerpt: This Article Describes How to Recover From Failed Windows Updates
thumbnail: https://thmb.techidaily.com/d8ea0db08299b418f8415fcdb55459d60a299aaeacab1eb2b1b6960f90e2b4a4.jpg
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126492/26400" target="_top" id="2126492">
  <img src="//a.impactradius-go.com/display-ad/26400-2126492" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126492/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094429/7443" target="_top" id="2094429">
  <img src="//a.impactradius-go.com/display-ad/7443-2094429" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094429/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880976/19272" target="_top" id="1880976">
  <img src="//a.impactradius-go.com/display-ad/19272-1880976" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880976/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<span id="1982499">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982499.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982499">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982499.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982499%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982499/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-accelerating-your-tiktok-content-made-simple/"><u>[Updated] Accelerating Your TikTok Content Made Simple</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-mastering-srt-a-complete-guide-overview/"><u>[Updated] Mastering SRT A Complete Guide Overview</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-screenflow-for-mac-full-review/"><u>[Updated] ScreenFlow for Mac Full Review</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/budding-entrepreneurs-guide-mastering-the-art-of-social-media-advertising/"><u>Budding Entrepreneurs Guide Mastering the Art of Social Media Advertising</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/crafting-next-gen-web-interfaces-the-gpt-way/"><u>Crafting Next-Gen Web Interfaces: The GPT Way</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-your-wireless-mouse-keeps-stopping-mid-operation-on-pcs-with-windows-11-or-10/"><u>Effective Solutions for When Your Wireless Mouse Keeps Stopping Mid-Operation on PCs with Windows 11 or 10</u></a></li>
<li><a href="https://common-error.techidaily.com/exe-errors-tamed-explorer-on-win1011/"><u>Exe Errors Tamed – Explorer on Win10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209021298-how-to-fix-the-irritating-cracking-sound-from-your-pcs-speakers-on-windows-operating-systems/"><u>How to Fix the Irritating Cracking Sound From Your PC's Speakers on Windows Operating Systems.</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-a-complete-manual-for-logging-and-storing-periscope-video/"><u>In 2024, A Complete Manual for Logging & Storing Periscope Video</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-unlocking-iphone-8-plus-lock-screen-3-foolproof-methods-that-actually-work-drfone-by-drfone-ios/"><u>In 2024, Unlocking iPhone 8 Plus Lock Screen 3 Foolproof Methods that Actually Work | Dr.fone</u></a></li>
<li><a href="https://win11.techidaily.com/overcoming-file-access-denial-on-windows-11/"><u>Overcoming File Access Denial on Windows 11</u></a></li>
<li><a href="https://tech-revival.techidaily.com/prompt-engineering-jobs-unveiling-the-legitimacy-and-important-points-to-think-about/"><u>Prompt Engineering Jobs: Unveiling the Legitimacy and Important Points to Think About</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-oculus-device-malfunctions-a-step-by-step-guide/"><u>Solving Oculus Device Malfunctions: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/system-resource-shortage-solutions-overcoming-service-request-failed-messages/"><u>System Resource Shortage Solutions: Overcoming 'Service Request Failed' Messages</u></a></li>
<li><a href="https://common-error.techidaily.com/top-4-fixes-for-when-your-dns-server-isnt-working-properly/"><u>Top 4 Fixes for When Your DNS Server Isn’t Working Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-restore-5-techniques-for-a-functional-touchscreen-on-windows-11/"><u>Troubleshoot and Restore: 5 Techniques for a Functional Touchscreen on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unsuccessful-hardware-transfer-in-windows-10-systems/"><u>Troubleshooting Unsuccessful Hardware Transfer in Windows 10 Systems</u></a></li>
</ul></div>

