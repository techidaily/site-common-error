---
title: How To Correctly Address the Windows Update Error with Code 0X80070490 [SOLUTION]
date: 2024-09-04T20:22:00.485Z
updated: 2024-09-05T20:22:00.485Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How To Correctly Address the Windows Update Error with Code 0X80070490 [SOLUTION]
excerpt: This Article Describes How To Correctly Address the Windows Update Error with Code 0X80070490 [SOLUTION]
thumbnail: https://thmb.techidaily.com/1cd4d8b30d4bc3438d0d666b54184cb335ed999f5f531a542c9f720844c66d4d.jpg
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

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2044586/7443" target="_top" id="2044586">
  <img src="//a.impactradius-go.com/display-ad/7443-2044586" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2044586/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2049370/7443" target="_top" id="2049370">
  <img src="//a.impactradius-go.com/display-ad/7443-2049370" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049370/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2082527/7443" target="_top" id="2082527">
  <img src="//a.impactradius-go.com/display-ad/7443-2082527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528703/16446" target="_top" id="1528703">
  <img src="//a.impactradius-go.com/display-ad/16446-1528703" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528703/16446" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094415/7443" target="_top" id="2094415">
  <img src="//a.impactradius-go.com/display-ad/7443-2094415" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094415/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-channel-expansion-through-smart-youtube-link-building-methods/"><u>[New] In 2024, Channel Expansion Through Smart YouTube Link-Building Methods</u></a></li>
<li><a href="https://fox-access.techidaily.com/new-in-2024-how-to-activatedeactivate-pip-in-ios-web-experience/"><u>[New] In 2024, How to Activate/Deactivate PIP in iOS Web Experience</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-rhythm-discoveries-at-your-fingertips-free-online/"><u>[New] Rhythm Discoveries at Your Fingertips (Free, Online)</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-fast-tracking-views-on-vimeo-for-2024/"><u>[Updated] Fast-Tracking Views on Vimeo for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-innovators-designing-online-marvel-experiences/"><u>[Updated] Innovators Designing Online Marvel Experiences</u></a></li>
<li><a href="https://buynow-info.techidaily.com/2023s-premier-game-lineup-for-the-portable-powerhouse-steam-deck/"><u>2023'S Premier Game Lineup for the Portable Powerhouse: Steam Deck</u></a></li>
<li><a href="https://howto.techidaily.com/9-quick-fixes-to-unfortunately-touchwiz-has-stopped-of-tecno-pop-8-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Quick Fixes to Unfortunately TouchWiz has stopped Of Tecno Pop 8 | Dr.fone</u></a></li>
<li><a href="https://activate-lock.techidaily.com/a-comprehensive-guide-to-icloud-unlock-from-apple-iphone-11-online-by-drfone-ios/"><u>A Comprehensive Guide to iCloud Unlock From Apple iPhone 11 Online</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-winodw-11s-frustrating-0x80072efd-bug-proven-remedies-inside/"><u>Beat Winodw 11'S Frustrating 0X80072EFD Bug: Proven Remedies Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-hs50-microphone-issue-solutions-and-tips-for-users/"><u>Corsair HS50 Microphone Issue: Solutions and Tips for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-a-stubborn-geforce-experience-application-that-refuses-to-start/"><u>Dealing with a Stubborn GeForce Experience Application That Refuses to Start</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-guide-restoring-functionality-of-non-working-webcam-on-a-lenovo-laptop/"><u>DIY Guide: Restoring Functionality of Non-Working Webcam on a Lenovo Laptop</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-hearthstone-lagging/"><u>Easy To Fix Hearthstone Lagging</u></a></li>
<li><a href="https://common-error.techidaily.com/efficiently-tackle-wudfhostexe-high-resource-drain-on-windows-11-devices/"><u>Efficiently Tackle wudfhost.exe High Resource Drain on Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/endgame-achievement-overcoming-pubgs-dxgidll-challenge/"><u>Endgame Achievement - Overcoming PUBG's Dxgi.dll Challenge</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-it-tips-for-resolving-issues-with-a-broken-hdmi-connector-through-usb-ports/"><u>Fix It! Tips for Resolving Issues with a Broken HDMI Connector Through USB Ports</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-how-to-successfully-cast-media-from-your-pc-to-another-device-in-windows-10/"><u>Fixing the Issue: How to Successfully Cast Media From Your PC to Another Device in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-problem-of-non-responsive-bluetooth-keyboard-in-pc-connectivity/"><u>Fixing the Problem of Non-Responsive Bluetooth Keyboard in PC Connectivity</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-google-frp-lock-from-xiaomi-redmi-a2plus-devices-by-drfone-android/"><u>How to Bypass Google FRP Lock from Xiaomi Redmi A2+ Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-d3dcompiler47dll-error-comprehensive-guide/"><u>How to Fix D3DCOMPILER_47.dll Error - Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-stopped-audio-service-in-windows-7/"><u>How to Fix the Stopped Audio Service in Windows 7</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-omni-vmix-universal-controller/"><u>In 2024, Omni-VMix Universal Controller</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-learn-how-to-create-animated-titles-and-text-in-the-filmora-video-editor-this-is-a-simple-step-by-step-tutorial-for-any-skill-level/"><u>New Learn How to Create Animated Titles and Text in the Filmora Video Editor. This Is a Simple Step-by-Step Tutorial for Any Skill Level</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-connection-hurdles-effective-methods-to-connect-your-airpods-to-windows-11-a-2024-update/"><u>Overcoming Connection Hurdles: Effective Methods to Connect Your AirPods to Windows 11 - A 2024 Update</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-missing-battery-indicator-on-windows-10-with-these-simple-fixes/"><u>Resolve Your Missing Battery Indicator on Windows 10 with These Simple Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-icue-hardware-recognition-errors-step-by-step-guide/"><u>Resolving iCUE Hardware Recognition Errors: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-network-access-how-to-correctly-address-ethernet-malfunctions-on-windows-versions-11-7/"><u>Restoring Network Access: How to Correctly Address Ethernet Malfunctions on Windows Versions (11, 7)</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-overcoming-the-0xaddressed-memory-write-error/"><u>Solution: Overcoming the 0xAddressed Memory Write Error</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fixing-the-internet-explorer-has-stopped-working-issue/"><u>Step-by-Step Guide to Fixing the 'Internet Explorer Has Stopped Working' Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-nonfunctional-at-sign-keyboard-problems/"><u>Step-by-Step Solution for Nonfunctional 'At Sign' Keyboard Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-improve-scanner-printer-conversation-epson/"><u>Steps to Improve Scanner-Printer Conversation (Epson)</u></a></li>
<li><a href="https://common-error.techidaily.com/streamlining-corporate-compliance-with-admin-managed-windows-environment-settings/"><u>Streamlining Corporate Compliance with Admin-Managed Windows Environment Settings</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/for-youtube-thumbnail-size-aspect-ratio-included-for-2024/"><u>Tips for YouTube Thumbnail Size [Aspect Ratio Included] for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-to-successfully-shut-down-a-non-responsive-windows-10-machine-problem-solved/"><u>Tips to Successfully Shut Down a Non-Responsive Windows 10 Machine [PROBLEM SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/total-war-enthusiasts-rejoice-uncrash-your-rome-remastered-experience-here/"><u>Total War Enthusiasts Rejoice: Uncrash Your Rome Remastered Experience Here</u></a></li>
<li><a href="https://common-error.techidaily.com/troubled-by-cs-go-keep-freezing-or-crashing-heres-how-to-fix-it-quickly/"><u>Troubled by CS: GO Keep Freezing or Crashing? Here's How to Fix It Quickly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-repair-windows-groove-with-these-5-solutions-for-a-malfunctioning-touchscreen/"><u>Troubleshoot and Repair Windows Groove with These 5 Solutions for a Malfunctioning Touchscreen</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-excessive-cpu-consumption-caused-by-windows-audio-device-graph-issue/"><u>Troubleshooting and Repairing Excessive CPU Consumption Caused by Windows' Audio Device Graph Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-errors-when-playing-media-files-on-windows/"><u>Troubleshooting Errors When Playing Media Files on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-fixing-xerox-software-updates-failure-error-0x800f020b-in-windows/"><u>Troubleshooting Guide for Fixing Xerox Software Updates Failure (Error 0X800f020b) in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-previously-unresponsive-custom-settings-are-now-working-perfectly/"><u>Troubleshooting Guide: Previously Unresponsive Custom Settings Are Now Working Perfectly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-persistent-bad-image-problems-on-windows-operating-systems/"><u>Troubleshooting Persistent Bad Image Problems on Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-stuck-keyboard-arrows-effective-solutions-and-tips/"><u>Troubleshooting Stuck Keyboard Arrows: Effective Solutions & Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-causes-behind-invalid-directory-names-in-web-hosting/"><u>Troubleshooting: The Causes Behind Invalid Directory Names in Web Hosting</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-fixes-for-windows-10-error-understanding-and-solving-code-80240020/"><u>Ultimate Fixes for Windows 10 Error: Understanding and Solving Code 80240020</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-how-to-thaw-a-frozen-windows-10-taskbar-efficiently/"><u>Ultimate Guide: How to Thaw a Frozen Windows 10 Taskbar Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/unveiling-the-solution-overcoming-total-war-romes-remastered-persistent-crashes/"><u>Unveiling the Solution: Overcoming Total War: Rome's Remastered Persistent Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-update-failed-successful-strategies-for-resolving-error-0x80240034/"><u>Windows 10 Update Failed? Successful Strategies for Resolving Error 0X80240034</u></a></li>
<li><a href="https://common-error.techidaily.com/zap-freezes-quickly-enjoy-flawless-games/"><u>Zap Freezes Quickly - Enjoy Flawless Games</u></a></li>
</ul></div>
