---
title: "Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
date: 2025-01-01T18:39:30.097Z
updated: 2025-01-03T21:21:28.734Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
excerpt: "This Article Describes Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
thumbnail: https://thmb.techidaily.com/063f04ddcc12d7ad0c40343a71ed623fbddb1ebfb8c3b581a5d414d7d362a54b.jpg
---

## Overcome the Windows Update Error (0X8024402c) with Ease - Detailed Solutions Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Jng92DT1n_Y?si=EdMRoNAFi0Q6mP7G" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/8dH3yHH9IX8?si=geiW5KbIljSFT9pz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9ECz3oZ8NrQ?si=86vkwkDJo9HQXpzt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-2024-approved-dynamic-interactions-key-to-enhancing-page-visibility/"><u>[New] 2024 Approved Dynamic Interactions Key to Enhancing Page Visibility</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-2024-approved-adobe-audition-tutorial-managing-sound-curves/"><u>[Updated] 2024 Approved Adobe Audition Tutorial Managing Sound Curves</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-securely-save-fb-high-definition/"><u>[Updated] Securely Save FB High Definition</u></a></li>
<li><a href="https://fox-http.techidaily.com/detailed-synopsis-gopro-silver-hero4-model-review-for-2024/"><u>Detailed Synopsis GoPro Silver Hero4 Model Review for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-solutions-for-fixing-unspecified-module-errors-on-pcmac/"><u>Easy Solutions for Fixing Unspecified Module Errors on PC/Mac</u></a></li>
<li><a href="https://fake-location.techidaily.com/fixing-foneazy-mockgo-not-working-on-oppo-reno-10-5g-drfone-by-drfone-virtual-android/"><u>Fixing Foneazy MockGo Not Working On Oppo Reno 10 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-error-code-31-in-windows/"><u>How to Fix Error Code 31 in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-media-disconnected-in-windows/"><u>How to Fix Media Disconnected in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-cast-functionality-on-your-windows-10-computer-expert-fixes/"><u>How to Restore Cast Functionality on Your Windows 10 Computer - Expert Fixes</u></a></li>
<li><a href="https://iphone-transfer.techidaily.com/how-to-transfer-data-from-apple-iphone-15-to-zte-phones-drfone-by-drfone-transfer-from-ios/"><u>How to Transfer Data from Apple iPhone 15 to ZTE Phones | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/maximize-your-chatgpt-experience-discover-the-pluses/"><u>Maximize Your ChatGPT Experience - Discover the Pluses</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-the-common-installation-incomplete-on-windows/"><u>Quick Solutions for the Common 'Installation Incomplete on Windows'</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-troubleshoot-your-non-functional-steelseries-arctis-er-audio-device/"><u>Solved! How to Troubleshoot Your Non-Functional SteelSeries Arctis Er Audio Device</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-persistent-boot-problems-on-your-windows-11-system/"><u>Troubleshooting Persistent Boot Problems on Your Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-error-code-0xc1900208-on-your-windows-10-system-resolved/"><u>Troubleshooting Tips for Fixing Error Code 0xC1900208 on Your Windows 10 System [RESOLVED]</u></a></li>
<li><a href="https://win-blog.techidaily.com/ultimate-guide-to-preventing-constant-failures-in-nox-player-for-pc-users/"><u>Ultimate Guide to Preventing Constant Failures in Nox Player for PC Users</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-unleash-the-power-of-slow-mo-top-video-editing-software-revealed/"><u>Updated 2024 Approved Unleash the Power of Slow Mo Top Video Editing Software Revealed</u></a></li>
</ul></div>

