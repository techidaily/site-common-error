---
title: How to Correctly Solve Windows 11 Update Issue - Error 0X8024401C Explained
date: 2024-12-12T18:03:49.853Z
updated: 2024-12-16T16:05:28.752Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Correctly Solve Windows 11 Update Issue - Error 0X8024401C Explained
excerpt: This Article Describes How to Correctly Solve Windows 11 Update Issue - Error 0X8024401C Explained
thumbnail: https://thmb.techidaily.com/b8fca16a34b5411c86475482e61fa021f5aeb02943a66dd5dba0e650f0e39da1.jpg
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/iLlpdv0cz_k?si=HwTdnMmeVJXm4GPV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YwOwUI47FuU?si=NK7IEELjx7_SJSl2" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RJNYTGHVlLc?si=heERQcpMi77lqToE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://common-error.techidaily.com/defeat-the-0x800705b4-error-in-your-windows-11-update-process-with-these-proven-strategies/"><u>Defeat the 0X800705B4 Error in Your Windows 11 Update Process with These Proven Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-fixing-non-working-hp-laptop-cameras-on-windows-10-systems/"><u>Expert Advice: Fixing Non-Working HP Laptop Cameras on Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/halo-4-ue4-2024-edition-resolving-the-persistent-critical-error-and-eliminating-system-crashes/"><u>Halo 4 UE4 2024 Edition: Resolving the Persistent Critical Error and Eliminating System Crashes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-the-dx11-feature-level-100-flaw-in-wwe-2k-battlegrounds/"><u>How To Repair The 'DX11 Feature Level 10.0' Flaw in WWE 2K Battlegrounds</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-hassle-free-solutions-to-fake-location-on-find-my-friends-of-oppo-find-x6-pro-drfone-by-drfone-virtual-android/"><u>In 2024, 5 Hassle-Free Solutions to Fake Location on Find My Friends Of Oppo Find X6 Pro | Dr.fone</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/in-2024-how-to-unlock-oneplus-nord-n30-5g-phone-without-password-by-drfone-android/"><u>In 2024, How To Unlock OnePlus Nord N30 5G Phone Without Password?</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-top-15-apps-to-hack-wifi-password-on-oppo-find-x7-by-drfone-android/"><u>In 2024, Top 15 Apps To Hack WiFi Password On Oppo Find X7</u></a></li>
<li><a href="https://common-error.techidaily.com/key-stubbornness-now-overcome/"><u>Key Stubbornness, Now Overcome</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-f-key-malfunction-heres-a-simple-guide-to-fixing-it-fast/"><u>Lenovo F-Key Malfunction? Here's a Simple Guide to Fixing It Fast!</u></a></li>
<li><a href="https://buynow-info.techidaily.com/mac-loyalists-guide-to-freestyle2-blue-the-ultimate-customization-tool/"><u>Mac Loyalists' Guide to Freestyle2 Blue: The Ultimate Customization Tool</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-hack-swift-solutions-to-overcome-installation-incomplete-on-windows/"><u>Master the Hack: Swift Solutions to Overcome 'Installation Incomplete' On Windows</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-free-avi-video-rotator-software-and-apps-for-all-devices/"><u>New In 2024, Free AVI Video Rotator Software and Apps for All Devices</u></a></li>
<li><a href="https://games-able.techidaily.com/safe-space-a-kids-guide-to-ps5-security-settings/"><u>Safe Space: A Kid’s Guide to PS5 Security Settings</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/the-ultimate-itunes-guide-mastering-recordings-for-2024/"><u>The Ultimate iTunes Guide Mastering Recordings for 2024</u></a></li>
<li><a href="https://discover-hacks.techidaily.com/44ot44o844kr44or44oh44kj44os44kv44oi44oq44go44oj44ot44od44ox44oc44od44kv44k56zat44gn44gu44ov44kh44kk44or5zcm5pyf5pa55rov/"><u>ローカルディレクトリとドロップボックス間でのファイル同期方法</u></a></li>
</ul></div>

