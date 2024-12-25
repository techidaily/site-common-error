---
title: "Expert Tips: How to Overcome Error 0X8024402c During Windows Updates"
date: 2024-12-21T19:20:21.709Z
updated: 2024-12-25T18:11:46.808Z
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

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/3koT_-kvbks?si=sQV7FzPiz6GYITrE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K7fATC_lI7o?si=UFotPJqflDRZr-mv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MmTJlcwgyrQ?si=x3hba82M0tT57fj7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n-66V-LRK3Y?si=fNeB2pXCePeQli6E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KKFdFHaVIJg?si=x2vLw7ty3FtHX-9T" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/0Kr7Dpw0HuM?si=05wWDXdPgmC-oBBE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-blue.techidaily.com/new-smooth-shifts-audio-transition-wisdom-from-sonar-by-platinum-for-2024/"><u>[New] Smooth Shifts Audio Transition Wisdom From Sonar by Platinum for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-2024-approved-maximizing-youtube-exposure-with-ongoing-creative-commons-compliance/"><u>[Updated] 2024 Approved Maximizing YouTube Exposure with Ongoing Creative Commons Compliance</u></a></li>
<li><a href="https://common-error.techidaily.com/battleye-installation-issues-resolved-a-comprehensive-guide/"><u>BattlEye Installation Issues Resolved - A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/el-charisma-techniques-for-amplifying-youtube-visibility/"><u>Channel Charisma Techniques for Amplifying YouTube Visibility</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/convertissez-votre-fichier-ogm-en-mp4-de-gre-a-gre-sans-cout-movavi/"><u>Convertissez Votre Fichier OGM en MP4 De Gré À Gré Sans Coût - Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/dota-2-solve-error-2024-with-quick-api-adjustment-tips/"><u>Dota 2: Solve Error 2024 with Quick 'API Adjustment' Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/eclipse-effect-screen-issue/"><u>Eclipse Effect: Screen Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/execution-path-blocked/"><u>Execution Path Blocked</u></a></li>
<li><a href="https://fox-sys.techidaily.com/facebook-streaming-simplified-a-comprehensive-tutorial-for-hassle-free-online-broadcasts/"><u>Facebook Streaming Simplified: A Comprehensive Tutorial for Hassle-Free Online Broadcasts</u></a></li>
<li><a href="https://common-error.techidaily.com/fallout-4-performance-optimized-how-to-overcome-lag-issues-tips-players/"><u>Fallout 4 Performance Optimized: How to Overcome Lag Issues (Tips Players)</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-frozen-google-chrome-do-you-need-to-restart/"><u>Fixing a Frozen Google Chrome: Do You Need to Restart?</u></a></li>
<li><a href="https://fox-that.techidaily.com/how-can-i-access-iphone-pictures-that-seem-missing-despite-being-erased-discover-8-solutions/"><u>How Can I Access iPhone Pictures That Seem Missing Despite Being Erased? Discover 8 Solutions</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-oneplus-12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On OnePlus 12 | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/in-2024-uniting-communication-and-visuals-a-detailed-plan-for-slack-plus-filmora-meetings/"><u>In 2024, Uniting Communication & Visuals A Detailed Plan for Slack + Filmora Meetings</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/more-than-you-could-dream-or-imagine-final-cut-pro-x-is-a-powerful-software-one-such-hidden-feature-from-fcpx-is-jump-cuts-and-we-shall-know-more-about-fina/"><u>More than You Could Dream or Imagine, Final Cut Pro X Is a Powerful Software. One Such Hidden Feature From FCPX Is Jump Cuts, and We Shall Know More About Final Cut Pro Jump Cuts in This Article</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-microsoft-print-to-pdf-malfunction-in-windows-11-systems/"><u>Solving the Microsoft Print to PDF Malfunction in Windows 11 Systems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-ultimate-chroma-spectrum-now-crystal-clear-on-4k-for-2024/"><u>The Ultimate Chroma Spectrum, Now Crystal Clear on 4K for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-reducing-high-gpu-consumption-by-the-desktop-window-manager-on-windows-10-and-11/"><u>Top 5 Solutions for Reducing High GPU Consumption by the Desktop Window Manager on Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixes-for-non-responsive-dell-bluetooth-keyboard/"><u>Troubleshooting Guide: Fixes for Non-Responsive Dell Bluetooth Keyboard</u></a></li>
</ul></div>

