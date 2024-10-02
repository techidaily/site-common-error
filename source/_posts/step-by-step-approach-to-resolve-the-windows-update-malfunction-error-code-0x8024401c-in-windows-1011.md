---
title: Step-by-Step Approach to Resolve the Windows Update Malfunction (Error Code 0X8024401C) in Windows 10/11
date: 2024-09-30T17:43:34.241Z
updated: 2024-10-01T20:49:10.075Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Approach to Resolve the Windows Update Malfunction (Error Code 0X8024401C) in Windows 10/11
excerpt: This Article Describes Step-by-Step Approach to Resolve the Windows Update Malfunction (Error Code 0X8024401C) in Windows 10/11
thumbnail: https://thmb.techidaily.com/ebbfd91fc57bf5ea9818d4e87d8cfd35544a71921ce7ca73b2986ee75e83dd45.jpg
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
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1838960/17916" target="_top" id="1838960">
  <img src="//a.impactradius-go.com/display-ad/17916-1838960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1838960/17916" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1938698/19272" target="_top" id="1938698">
  <img src="//a.impactradius-go.com/display-ad/19272-1938698" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938698/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1975836/19272" target="_top" id="1975836">
  <img src="//a.impactradius-go.com/display-ad/19272-1975836" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975836/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aidotcom.pxf.io/c/5597632/2129041/19576" target="_top" id="2129041">
  <img src="//a.impactradius-go.com/display-ad/19576-2129041" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129041/19576" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-videos.techidaily.com/updated-in-2024-8-exemplary-templates-dominate-social-media-creatives/"><u>[Updated] In 2024, 8 Exemplary Templates Dominate Social Media Creatives</u></a></li>
<li><a href="https://youtube-web.techidaily.com/approved-elevate-your-video-voyage-navigating-the-world-of-youtube-links/"><u>2024 Approved Elevate Your Video Voyage Navigating the World of YouTube Links</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/a-step-by-step-guide-to-crafting-facebook-visual-stories/"><u>A Step-by-Step Guide to Crafting Facebook Visual Stories</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/amd-graphics-relic/"><u>AMD Graphics Relic</u></a></li>
<li><a href="https://tech-haven.techidaily.com/enhancing-your-cv-written-skills-the-chatgpt-method/"><u>Enhancing Your CV' Written Skills: The ChatGPT Method</u></a></li>
<li><a href="https://common-error.techidaily.com/findings-opengl-not-advocated-by-drivers/"><u>Findings: OpenGL Not Advocated by Drivers</u></a></li>
<li><a href="https://howto.techidaily.com/fix-app-not-available-in-your-country-play-store-problem-on-motorola-edge-40-pro-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix App Not Available in Your Country Play Store Problem on Motorola Edge 40 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/fix-cant-take-screenshot-due-to-security-policy-on-oppo-find-n3-flip-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Fix Cant Take Screenshot Due to Security Policy on Oppo Find N3 Flip | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-windows-audio-device-graph-isolation-high-cpu-usage-issue/"><u>Fix Windows Audio Device Graph Isolation High CPU Usage Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fix-resolve-oculus-hardware-problems-effectively/"><u>Master the Fix: Resolve Oculus Hardware Problems Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-for-device-not-recognized-in-your-icue-system/"><u>Mastering the Fix for 'Device Not Recognized' In Your ICUE System</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/mend-iphones-facebook-video-displays/"><u>Mend iPhones' Facebook Video Displays</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211675583-mystery-of-undetected-sd-solved-here/"><u>Mystery of Undetected SD Solved Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-issue-troubleshooting-non-functional-numeric-buttons/"><u>Solved Issue: Troubleshooting Non-Functional Numeric Buttons</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-why-is-my-bluetooth-device-connected-but-not-communicating-with-windows-10/"><u>Solving the Mystery: Why Is My Bluetooth Device Connected but Not Communicating with Windows 10?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-feature-level-100-in-wwe-2k-battlegrounds-for-dx11-users/"><u>Troubleshooting 'Feature Level 10.0' In WWE 2K Battlegrounds for DX11 Users</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unveiling-the-secrets-of-powerful-titles/"><u>Unveiling the Secrets of Powerful Titles</u></a></li>
</ul></div>

