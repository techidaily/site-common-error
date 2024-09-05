---
title: "How to Fix Error 0X8024002E on Your Windows PC: A Complete Troubleshooting Manual"
date: 2024-09-04T20:21:31.911Z
updated: 2024-09-05T20:21:31.911Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix Error 0X8024002E on Your Windows PC: A Complete Troubleshooting Manual"
excerpt: "This Article Describes How to Fix Error 0X8024002E on Your Windows PC: A Complete Troubleshooting Manual"
thumbnail: https://thmb.techidaily.com/0ee1c1c5a9be407cbf065c21cefa3d097b024c8bd5c0bbace26a3b7cf94a12be.jpg
---

## Tackling Windows Troubles? Here's How You Can Resolve Error 0X8024402C on Your PC

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1915870/19272" target="_top" id="1915870">
  <img src="//a.impactradius-go.com/display-ad/19272-1915870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1915870/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<span id="1983472">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983472.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983472">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983472.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983472%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983472/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<span id="1975555">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975555.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975555">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975555.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975555%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975555/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052063/7443" target="_top" id="2052063">
  <img src="//a.impactradius-go.com/display-ad/7443-2052063" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052063/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

<!-- affiliate ads begin -->
<span id="2135471">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/2135471.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18498-2135471">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/2135471.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Funicoeye.pxf.io%2Fc%2F5597632%2F2135471%2F18498'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/2135471/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-direct.techidaily.com/new-in-2024-accelerated-aesthetics-rapid-revamping-of-images-on-windows-photo-editor/"><u>[New] In 2024, Accelerated Aesthetics  Rapid Revamping of Images on Windows Photo Editor</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/n-2024-the-professionals-path-expert-strategies-for-360-youtube-live-broadcasting/"><u>[New] In 2024, The Professional's Path  Expert Strategies for 360° Youtube Live Broadcasting</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-simple-method-setting-up-snapchat-for-mac-users-for-2024/"><u>[New] Simple Method  Setting up Snapchat for Mac Users for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-2024-approved-a-compre-written-by-dr-john-smith-phd-in-environmental-science/"><u>[Updated] 2024 Approved  A Compre Written By  Dr. John Smith, PhD in Environmental Science</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-direct-music-upload-top-tools-for-turning-spotify-into-youtube-listings/"><u>[Updated] 2024 Approved  Direct Music Upload  Top Tools for Turning Spotify Into YouTube Listings</u></a></li>
<li><a href="https://extra-hints.techidaily.com/updated-advanced-3d-design-for-stylish-text-creations/"><u>[Updated] Advanced 3D Design for Stylish Text Creations</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/2024-approved-7-top-free-instagram-video-clips-tools-for-daily-entertainment/"><u>2024 Approved  7 Top Free Instagram Video Clips Tools for Daily Entertainment</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-the-fixed-windows-11-update-error-code-0x8024401c/"><u>Comprehensive Fixes for the 'Fixed' Windows 11 Update Error (Code 0X8024401c)</u></a></li>
<li><a href="https://common-error.techidaily.com/conclusion-opengl-unsupported-by-drivers/"><u>Conclusion: OpenGL Unsupported By Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/conquer-the-challenge-of-error-0x887a0006-speedy-solutions-unveiled-for-hassle-free-fixes/"><u>Conquer the Challenge of Error 0X887A0006: Speedy Solutions Unveiled for Hassle-Free Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/conquered-crisis-effective-solutions-to-the-infamous-red-screen-problem/"><u>Conquered Crisis: Effective Solutions to the Infamous Red Screen Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnostic-report-overcoming-the-challenges-with-an-inoperative-igfx-unit/"><u>Diagnostic Report: Overcoming the Challenges with an Inoperative iGFX Unit</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-steps-to-overcome-windows-10s-vanishing-bluetooth-problem-get-connected-again/"><u>Easy Steps to Overcome Windows 10'S Vanishing Bluetooth Problem - Get Connected Again</u></a></li>
<li><a href="https://fox-glue.techidaily.com/exploring-beyond-the-screen-with-vr/"><u>Exploring Beyond the Screen with VR</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-frozen-windows-10-taskbar-best-practices-and-techniques-that-work/"><u>Fixing a Frozen Windows 10 Taskbar: Best Practices and Techniques That Work</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-http-403-forbidden-error-expert-strategies-and-best-practices/"><u>Fixing HTTP 403 Forbidden Error: Expert Strategies and Best Practices</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-common-hamachi-disconnection-problems/"><u>Fixing The Common Hamachi Disconnection Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-logitech-g930-microphone-sound-hole-issue-a-step-by-step-guide/"><u>Fixing the Logitech G930 Microphone Sound Hole Issue: A Step-by-Step Guide</u></a></li>
<li><a href="https://activate-lock.techidaily.com/how-to-fix-iphone-12-could-not-be-activatedreached-issue-by-drfone-ios/"><u>How To Fix iPhone 12 Could Not Be Activated/Reached Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209385132-how-to-fix-livekernelevent-141-hardware-error-2024/"><u>How to Fix LiveKernelEvent 141 Hardware Error – 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/how-to-play-mkv-videos-in-itunes-convert-them-for-free-into-mp4-or-mov/"><u>How to Play MKV Videos in iTunes - Convert Them for Free Into MP4 or MOV!</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-fixes-for-when-your-dns-server-is-down-no-stress-required/"><u>Immediate Fixes for When Your DNS Server Is Down - No Stress Required!</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-protecting-your-privacy-how-to-remove-apple-id-from-iphone-7-by-drfone-ios/"><u>In 2024, Protecting Your Privacy How To Remove Apple ID From iPhone 7</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-transforming-your-spotify-list-into-a-youtube-music-collection/"><u>In 2024, Transforming Your Spotify List Into a YouTube Music Collection</u></a></li>
<li><a href="https://hardware-help.techidaily.com/latest-updates-installing-and-upgrading-the-logitech-c920-webcam-driver-on-windows-11-10-and-8/"><u>Latest Updates: Installing and Upgrading the Logitech C920 Webcam Driver on Windows 11, 10 & 8</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/master-the-archive-navigating-social-media-live-recordings-for-2024/"><u>Master the Archive  Navigating Social Media Live Recordings for 2024</u></a></li>
<li><a href="https://fox-http.techidaily.com/mastering-the-art-of-selecting-top-online-vhs-image-adjustments-for-2024/"><u>Mastering the Art of Selecting Top Online VHS Image Adjustments for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-connection-ready-to-use-fixes-for-your-airpods-and-windows-pcs/"><u>Mastering the Connection: Ready-to-Use Fixes for Your AirPods and Windows PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/msvcr71dll-was-not-found-solved/"><u>MSVCR71.dll Was Not Found [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-frequent-device-disconnection-a-comprehensive-approach-to-troubleshooting-usb-connectivity/"><u>Overcoming Frequent Device Disconnection: A Comprehensive Approach to Troubleshooting USB Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-left-vs-right-click-discrepancy-solutions-for-windows-11-users/"><u>Overcoming the Left Vs. Right Click Discrepancy: Solutions for Windows 11 Users</u></a></li>
<li><a href="https://extra-support.techidaily.com/premium-software-solutions-for-visual-storytelling-from-pictures-for-2024/"><u>Premium Software Solutions for Visual Storytelling From Pictures for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/questioning-authority-has-openai-relinquished-supervision-over-chatgpt/"><u>Questioning Authority: Has OpenAI Relinquished Supervision Over ChatGPT?</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-the-failed-network-start-up-problem-in-dragon-ball-fighterz/"><u>Quick Fixes for the Failed Network Start-Up Problem in Dragon Ball FighterZ</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-failed-to-connect-issue-in-overwatch-a-step-by-step-guide/"><u>Resolving the 'Failed to Connect' Issue in Overwatch: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-corsair-keyboard-expert-tips-to-overcome-non-functionality-issues/"><u>Revive Your Corsair Keyboard: Expert Tips to Overcome Non-Functionality Issues</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/trimming-tips-select-the-top-5-url-shrinkers-for-youtube-for-2024/"><u>Trimming Tips  Select the Top 5 URL Shrinkers for YouTube for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-addressing-second-monitor-not-detected-on-windows-7-fixed/"><u>Troubleshooting Guide: Addressing 'Second Monitor Not Detected' On Windows 7 [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-how-to-fix-typing-incorrect-characters-on-your-keyboard/"><u>Troubleshooting: How to Fix Typing Incorrect Characters on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-fixes-for-call-of-duty-wwii-error-4220-step-by-step-guide/"><u>Ultimate Fixes for Call of Duty: WWII Error 4220 - Step by Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/unwanted-system-stops-on-windows-10/"><u>Unwanted System Stops on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-wont-exit-airplane-mode-heres-how-you-can-fix-it/"><u>Windows 11 Won't Exit Airplane Mode? Here's How You Can Fix It!</u></a></li>
</ul></div>
