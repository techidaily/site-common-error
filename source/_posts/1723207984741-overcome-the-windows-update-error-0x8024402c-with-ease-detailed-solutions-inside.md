---
title: Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside
date: 2024-10-26T16:58:23.332Z
updated: 2024-10-30T17:09:17.584Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside
excerpt: This Article Describes Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside
thumbnail: https://thmb.techidaily.com/f61e0cf06b5f94c52331e7280bfea34d0fc7a11feee31daa0334519a989e1892.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2111968/7443" target="_top" id="2111968">
  <img src="//a.impactradius-go.com/display-ad/7443-2111968" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111968/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://appsumo.8odi.net/c/5597632/2094479/7443" target="_top" id="2094479">
  <img src="//a.impactradius-go.com/display-ad/7443-2094479" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094479/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137975/21526" target="_top" id="2137975">
  <img src="//a.impactradius-go.com/display-ad/21526-2137975" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137975/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Now try to install Windows Updates now.

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934288/19272" target="_top" id="1934288">
  <img src="//a.impactradius-go.com/display-ad/19272-1934288" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934288/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-storing-success-top-strategies-for-mov-and-mov-files-in-windows/"><u>[New] 2024 Approved Storing Success Top Strategies for Mov and .mov Files in Windows</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-comprehensive-guide-to-captioning-for-enhanced-video-impact-for-2024/"><u>[Updated] Comprehensive Guide to Captioning for Enhanced Video Impact for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-grab-free-video-profile-backgrounds/"><u>[Updated] In 2024, Grab Free Video Profile Backgrounds</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/crafting-vivid-instagram-profile-previews-for-2024/"><u>Crafting Vivid Instagram Profile Previews for 2024</u></a></li>
<li><a href="https://discover-dash.techidaily.com/1725287099055-dvddvd/"><u>DVDリッピングができない原因から始まり、究極の裏技とダイナミックDVDコピーソフトを紹介！</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-lower-dwms-impact-on-your-pcs-graphics-resources-in-windows-nkite/"><u>Effective Techniques to Lower DWM's Impact on Your PC's Graphics Resources in Windows Nkite</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-restoring-connectivity-between-your-aoc-monitor-and-windows-10-computer/"><u>Expert Advice: Restoring Connectivity Between Your AOC Monitor and Windows 10 Computer</u></a></li>
<li><a href="https://win-net.techidaily.com/guide-to-setting-up-dynamic-output-for-e-book-titles-in-web-design-with-flipbuilder-tips-on-keywords-and-script-integration/"><u>Guide to Setting Up Dynamic Output for E-Book Titles in Web Design with FlipBuilder: Tips on Keywords & Script Integration</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-serious-glitches-and-error-messages-in-black-ops-4/"><u>How to Resolve Serious Glitches and Error Messages in Black Ops 4</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-youtube-premium-subscription-everything-you-need-to-know/"><u>In 2024, YouTube Premium Subscription - Everything You Need to Know</u></a></li>
<li><a href="https://driver-download.techidaily.com/mastery-of-asus-pce-ac56-wifi-driver-setup-for-windows-users-overcoming-compatibility-hurdles/"><u>Mastery of ASUS PCE-AC56 WiFi Driver Setup for Windows Users: Overcoming Compatibility Hurdles</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-challenges-in-configuring-a-functional-d3d-graphics-device/"><u>Overcoming Challenges in Configuring a Functional D3D Graphics Device</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-a-non-functional-keyboard-during-system-boot/"><u>Resolved: Troubleshooting a Non-Functional Keyboard During System Boot</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-easily-resolving-detected-no-power-source/"><u>Troubleshooting Tips: Easily Resolving 'Detected No Power Source'</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/unified-video-ventures-selecting-an-mcn-for-2024/"><u>Unified Video Ventures Selecting an MCN for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/why-isnt-my-hdmi-converter-working-with-usb-solutions-inside/"><u>Why Isn't My HDMI Converter Working with USB? Solutions Inside</u></a></li>
</ul></div>

