---
title: "Error Code 24 in Windows: How to Restore Accessibility of Your Missing Devices"
date: 2024-10-29T18:00:54.805Z
updated: 2024-11-05T07:50:21.979Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 24 in Windows: How to Restore Accessibility of Your Missing Devices"
excerpt: "This Article Describes Error Code 24 in Windows: How to Restore Accessibility of Your Missing Devices"
thumbnail: https://thmb.techidaily.com/f7696c4ac1037e72f31c6b328a12ea085bd4635182093dadda40d9b14071da58.jpg
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

<!-- affiliate ads begin -->
<span id="1265663">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1265663.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/4482-1265663">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1265663.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fmartinic.evyy.net%2Fc%2F5597632%2F1265663%2F4482'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1265663/4482" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/1001446/11832" target="_top" id="1001446">
  <img src="//a.impactradius-go.com/display-ad/11832-1001446" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1001446/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148639/16836" target="_top" id="2148639">
  <img src="//a.impactradius-go.com/display-ad/16836-2148639" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148639/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2112008/7443" target="_top" id="2112008">
  <img src="//a.impactradius-go.com/display-ad/7443-2112008" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112008/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<span id="1155462">
					<video width="1024" height="576" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1155462.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/14559-1155462">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1155462.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:640px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fpropmoneyinc.pxf.io%2Fc%2F5597632%2F1155462%2F14559'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1155462/14559" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-http.techidaily.com/new-unleash-the-power-of-visuals-with-top-free-slideshow-designs/"><u>[New] Unleash the Power of Visuals with Top Free Slideshow Designs</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/2024-approved-crafting-content-that-wins-on-ig-unboxing-edition/"><u>2024 Approved Crafting Content That Wins on IG Unboxing Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/breaking-free-from-infinite-loading-on-valorant-expert-solutions-applied/"><u>Breaking Free From Infinite Loading on Valorant: Expert Solutions Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-fixing-hdmi-connectivity-issues-on-your-windows-11-pc-with-a-tv/"><u>Diagnosing and Fixing HDMI Connectivity Issues on Your Windows 11 PC with a TV</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-rdr2-memory-crashes-a-step-by-step-guide-to-upping-your-pagefile-size/"><u>Eliminate RDR2 Memory Crashes: A Step-by-Step Guide to Upping Your Pagefile Size</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/five-effective-solutions-when-your-pdfs-wont-load-on-google-chrome/"><u>Five Effective Solutions When Your PDFs Won't Load on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-self-activating-power-cycles-in-windows-11-pcs-a-step-by-step-guide/"><u>Fixing Self-Activating Power Cycles in Windows 11 PCs: A Step-by-Step Guide</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-stream-anything-from-oneplus-ace-2-to-apple-tv-drfone-by-drfone-android/"><u>How To Stream Anything From OnePlus Ace 2 to Apple TV | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-and-repair-a-black-display-in-google-chrome-browser/"><u>How to Troubleshoot and Repair a Black Display in Google Chrome Browser</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-future-proofing-in-the-metaverse-essential-device-lineup/"><u>In 2024, Future-Proofing in the Metaverse Essential Device Lineup</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/211458304--reclaiming-your-inner-child/"><u>Reclaiming Your Inner Child | Free Book</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-detection-of-possible-windows-update-db-fault-on-windows-11-systems/"><u>Resolved: Detection of Possible Windows Update DB Fault on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-missing-desktop-icons-on-windows-11/"><u>Resolved: Fixing Missing Desktop Icons on Windows 11</u></a></li>
<li><a href="https://some-approaches.techidaily.com/safe-techniques-for-eliminating-audio-interference-in-videos/"><u>Safe Techniques for Eliminating Audio Interference in Videos</u></a></li>
<li><a href="https://sound-issues.techidaily.com/solve-the-silent-problem-ensuring-your-facebook-videos-play-with-audio-on-windows-computers/"><u>Solve the Silent Problem: Ensuring Your Facebook Videos Play with Audio on Windows Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-overcoming-windows-11-screen-mirroring-problems/"><u>Troubleshooting: Overcoming Windows 11 Screen Mirroring Problems</u></a></li>
<li><a href="https://discover-able.techidaily.com/vobmjpeg/"><u>VOBファイルをMJPEG形式に自由に変換: 簡単なオンラインツール</u></a></li>
</ul></div>

