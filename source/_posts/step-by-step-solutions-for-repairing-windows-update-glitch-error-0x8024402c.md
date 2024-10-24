---
title: Step-by-Step Solutions for Repairing Windows Update Glitch (Error 0X8024402c)
date: 2024-10-23T20:58:17.718Z
updated: 2024-10-24T22:43:00.681Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Repairing Windows Update Glitch (Error 0X8024402c)
excerpt: This Article Describes Step-by-Step Solutions for Repairing Windows Update Glitch (Error 0X8024402c)
thumbnail: https://thmb.techidaily.com/5bb08ab6d34a1fb0acace4e8322f42ab6cac411cdc94c053d0ad8ae749b9c794.jpg
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

<!-- affiliate ads begin -->
<span id="1834906">
					<video width="864" height="864" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1834906.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16836-1834906">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1834906.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2F25home.pxf.io%2Fc%2F5597632%2F1834906%2F16836'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1834906/16836" style="position:absolute;visibility:hidden;" border="0" />
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

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135364/19272" target="_top" id="2135364">
  <img src="//a.impactradius-go.com/display-ad/19272-2135364" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135364/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<span id="1983573">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983573.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983573">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983573.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983573%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983573/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://united.elfm.net/c/5597632/2139557/4704" target="_top" id="2139557">
  <img src="//a.impactradius-go.com/display-ad/4704-2139557" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://united.elfm.net/i/5597632/2139557/4704" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2016129/19272" target="_top" id="2016129">
  <img src="//a.impactradius-go.com/display-ad/19272-2016129" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2016129/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/updated-avoiding-common-pitfalls-with-zoom-recording-methods-for-2024/"><u>[Updated] Avoiding Common Pitfalls with Zoom Recording Methods for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/a-decade-in-review-top-8-free-online-srt-translators/"><u>A Decade in Review Top 8 Free Online SRT Translators</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-disabled-shortcut-keys-on-your-laptopdesktop-pc/"><u>Dealing with Disabled Shortcut Keys on Your Laptop/Desktop PC</u></a></li>
<li><a href="https://common-error.techidaily.com/decode-and-defeat-the-windows-10-0x80072efd-error-easily/"><u>Decode and Defeat the Windows 10 0X80072EFD Error Easily</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/elite-callers-on-windows-top-8-sorted-for-2024/"><u>Elite Callers on Windows Top 8 Sorted for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-volume-icon-missing-on-windows-10-with-pictures/"><u>Fix Volume Icon Missing on Windows 10 [with Pictures]</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-your-itel-a70-location-on-twitter-drfone-by-drfone-virtual-android/"><u>How to Change your Itel A70 Location on Twitter | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-on-infinix-hot-40-pro-drfone-by-drfone-virtual-android/"><u>How to Fake Snapchat Location on Infinix Hot 40 Pro | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-2-ways-to-transfer-text-messages-from-nubia-red-magic-8s-pro-to-iphone-1514131211x8-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 2 Ways to Transfer Text Messages from Nubia Red Magic 8S Pro to iPhone 15/14/13/12/11/X/8/ | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-keeps-showing-up-hurdle-solving-constant-usb-device-errors/"><u>Overcoming the 'Keeps Showing Up' Hurdle: Solving Constant USB Device Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/the-step-by-step-process-to-correct-failed-to-finish-writing-in-steam/"><u>The Step-by-Step Process to Correct 'Failed To Finish Writing' In Steam</u></a></li>
<li><a href="https://technical-tips.techidaily.com/troubleshooting-the-d3d9dll-not-detected-error-in-windows-systems/"><u>Troubleshooting the d3d9.dll Not Detected Error in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-continuous-automatic-repairs-in-windows-11-top-fixes/"><u>Winning the Battle Against Continuous Automatic Repairs in Windows #11: Top Fixes</u></a></li>
</ul></div>

