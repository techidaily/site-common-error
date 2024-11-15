---
title: How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS
date: 2024-11-12T16:49:58.062Z
updated: 2024-11-15T18:17:26.958Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS
excerpt: This Article Describes How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS
thumbnail: https://thmb.techidaily.com/e6c7c0aea059b2b9594111c92d9d243c60708ba7355f3daa30e8aeaa265b4225.jpg
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136617/26400" target="_top" id="2136617">
  <img src="//a.impactradius-go.com/display-ad/26400-2136617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136617/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134224/18498" target="_top" id="2134224">
  <img src="//a.impactradius-go.com/display-ad/18498-2134224" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134224/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134246/18498" target="_top" id="2134246">
  <img src="//a.impactradius-go.com/display-ad/18498-2134246" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134246/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-docs.techidaily.com/024-approved-proven-ways-to-create-engaging-intros-on-iphones-and-android/"><u>[New] 2024 Approved Proven Ways to Create Engaging Intros on iPhones & Android</u></a></li>
<li><a href="https://article-files.techidaily.com/new-in-2024-are-vloggers-compensated-for-product-critiques/"><u>[New] In 2024, Are Vloggers Compensated for Product Critiques?</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-mp4-capture-and-analysis-toolkit/"><u>[New] MP4 Capture & Analysis Toolkit</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-common-issues-with-youtube-shorts-thumbnails-for-2024/"><u>[Updated] Common Issues with YouTube Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-exclusive-8-video-download-utilities-guide-for-2024/"><u>[Updated] Exclusive 8 Video Download Utilities Guide for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-voice-transformation-top-7-innovative-mobile-apps-for-2024/"><u>[Updated] Voice Transformation Top 7 Innovative Mobile Apps for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solution-to-overcome-error-0x80070426-in-windows-11-environments/"><u>Comprehensive Solution to Overcome Error 0X80070426 in Windows 11 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-restoring-functionality-to-a-broken-lenovo-keyboard/"><u>Diagnosing and Restoring Functionality to a Broken Lenovo Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-rdr2-out-of-memory-error-quickly-by-boosting-your-pagefile/"><u>Fix 'RDR2 - Out Of Memory' Error Quickly by Boosting Your Pagefile</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-a-non-responsive-dns-quick-and-effective-4-strategies/"><u>Fix a Non-Responsive DNS: Quick & Effective 4 Strategies</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/fix-lenovo-easy-camera-not-working-issue-on-windows-11/"><u>Fix Lenovo Easy Camera Not Working Issue on Windows 11</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-troubleshoot-and-repair-the-configuration-failure-on-windows-11/"><u>How to Troubleshoot and Repair the Configuration Failure on Windows 11</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-maximizing-color-correction-advanced-techniques-for-lut-applications/"><u>In 2024, Maximizing Color Correction Advanced Techniques for LUT Applications</u></a></li>
<li><a href="https://common-error.techidaily.com/master-cheats-gone-wrong-deactivate-the-nba-2k21-emerald-hack-now/"><u>Master Cheats Gone Wrong? Deactivate the NBA 2K21 Emerald Hack Now</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-your-fortnite-experience-overcoming-windows-unsupported-graphics-cards/"><u>Optimizing Your Fortnite Experience: Overcoming Windows-Unsupported Graphics Cards</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-no-audio-output-device-found-issue-on-windows-1011/"><u>Solving the 'No Audio Output Device Found' Issue on Windows 10/11</u></a></li>
<li><a href="https://app-tips.techidaily.com/transforming-work-how-ai-agents-mark-a-new-era-of-innovation-and-permanent-shifts-in-employment-landscape/"><u>Transforming Work: How AI Agents Mark a New Era of Innovation and Permanent Shifts in Employment Landscape</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-dealing-with-the-persistent-windows-camera-error-0xa00f4292/"><u>Troubleshooting Tips for Dealing with the Persistent Windows Camera Error 0xA00F4292</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-resolving-windows-n-11-media-streaming-problems-cast-not-working/"><u>Ultimate Guide to Resolving Windows N 11 Media Streaming Problems (Cast Not Working)</u></a></li>
</ul></div>

