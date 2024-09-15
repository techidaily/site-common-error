---
title: Step-by-Step Guide to Correcting Windows Update Failure (Error 0X80070002)
date: 2024-09-11T13:09:16.811Z
updated: 2024-09-14T19:05:00.080Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Guide to Correcting Windows Update Failure (Error 0X80070002)
excerpt: This Article Describes Step-by-Step Guide to Correcting Windows Update Failure (Error 0X80070002)
thumbnail: https://thmb.techidaily.com/4526e24333ba977c51600360964ccfdbc4ba0f9b4255ce54480ebe44b63f8c8e.jpg
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130885/7443" target="_top" id="2130885">
  <img src="//a.impactradius-go.com/display-ad/7443-2130885" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130885/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

<!-- affiliate ads begin -->
<span id="1743243">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1743243.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/19272-1743243">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1743243.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Faligracehair.sjv.io%2Fc%2F5597632%2F1743243%2F19272'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1743243/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137201/26400" target="_top" id="2137201">
  <img src="//a.impactradius-go.com/display-ad/26400-2137201" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137201/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://some-knowledge.techidaily.com/new-extensive-breakdown-what-the-google-podcast-app-means-for-you/"><u>[New] Extensive Breakdown What the Google Podcast App Means for You</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-navigating-echo-reduction-techniques-in-audacity-for-2024/"><u>[New] Navigating Echo Reduction Techniques in Audacity for 2024</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/esolving-the-disappearance-of-shorts-thumbnails-for-2024/"><u>[New] Resolving the Disappearance of Shorts Thumbnails for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-telehealth-advancements-with-vr-integrations/"><u>[New] Telehealth Advancements with VR Integrations</u></a></li>
<li><a href="https://iphone-location.techidaily.com/5-ways-change-your-home-address-in-googleapple-map-on-apple-iphone-15-plusipad-drfone-by-drfone-virtual-ios/"><u>5 Ways Change Your Home Address in Google/Apple Map on Apple iPhone 15 Plus/iPad | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/excel-mastery-through-artificayerly-crafted-chatgpt-solutions/"><u>Excel Mastery Through Artificayerly-Crafted ChatGPT Solutions</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/google-pixels-latest-rumors-expected-price-tag-probable-release-date-and-specs-overview/"><u>Google Pixel's Latest Rumors: Expected Price Tag, Probable Release Date & Specs Overview</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-cannot-create-directx-graphics-device-error-solutions-included/"><u>How to Fix the 'Cannot Create DirectX Graphics Device' Error - Solutions Included</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-hidefake-snapchat-location-on-your-tecno-pova-5-drfone-by-drfone-virtual-android/"><u>How to Hide/Fake Snapchat Location on Your Tecno Pova 5 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-physxloaderdll-not-found-error-when-starting-games/"><u>Resolving the 'physxloader.dll Not Found' Error When Starting Games</u></a></li>
<li><a href="https://common-error.techidaily.com/success-story-fixing-the-persistent-unrecoverable-directx-error-issue/"><u>Success Story: Fixing the Persistent Unrecoverable DirectX Error Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-missing-printer-or-scanner-driver-in-windows-a-step-by-step-guide/"><u>Troubleshooting a Missing Printer or Scanner Driver in Windows: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/unstoppable-exe-how-to-handle-application-stopped-working-mishaps/"><u>Unstoppable Exe: How to Handle Application Stopped Working Mishaps</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/updated-simplify-your-workflow-gopro-quik-video-editing-made-easy-on-macbook-for-2024/"><u>Updated Simplify Your Workflow GoPro Quik Video Editing Made Easy on MacBook for 2024</u></a></li>
</ul></div>

