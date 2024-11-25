---
title: Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
date: 2024-11-19T17:33:39.654Z
updated: 2024-11-25T00:55:37.756Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
excerpt: This Article Describes Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
thumbnail: https://thmb.techidaily.com/b024a84a41e25a10e99a735d71f0138708aa747c63be7c3be4720f86eba5080f.jpg
---

## Microsoft Compatibility Telemetry Eating Up Too Much Disk Space on Windows 10 – Solutions and Fixes Available Now

Does this look familiar?

![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b61598e9c1bf.jpg)

 If the Microsoft Compatibility Telemetry process has recently started causing very high disk or high CPU usage on your Windows 10 system, it could be very frustrating. But there’s no need to panic – it’s usually easy to fix. You’ll learn 3 easy methods to troubleshoot the Microsoft Compatibility Telemetry high disk or high CPU problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Try these fixes

 **Method 1:[ Using Group Policy Editor ](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 1. Using Group Policy Editor) Method 2:[ Using Registry Editor](<https://www.drivereasy.com/knowledge/windows-10-microsoft-compatibility-telemetry-high-disk-usage-solved/#Way> 2. Using Registry Editor)**
 **Method 3:[Updating your device drivers](https://tools.techidaily.com/drivereasy/download/)**

### Method 1: Using Group Policy Editor

1) On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) Type **gpedit.msc**  and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279bde5ee8d.png)

**Note:**  If you cannot find gpedit.msc on your Windows 10,[here is the method to got it.](https://tools.techidaily.com/drivereasy/download/)
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``
 3) Go to **Computer Configuration** \> **Administrative** **Templates** \>**Windows Components** \> **Data Collection and Preview Builds** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279c6c18122.png)

`
` `
` `
` `
` `
`

 4) Double-click**Allow Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279cc82eec5.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XVsiIO7hWOc?si=UvWnqxaI_yHwEr74&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` ```` ``

 5) Select **Disabled** , then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a279d1cdc304.jpg)

 6) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.  
`
` `
` `
` `
` `
` `
` `
` `
` `
` `
` `` `
` `
` `
` `
` `
` `
` `
` `
` `
`

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/slm2NjVPNtk?si=9ow6g1ucmf0TnT4T&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

### Method 3: Update your device drivers

 If, after trying the above, the issue still exists or your PC is still running slow, it’s time to update your device drivers.

 There are two ways you can get the right drivers for all your devices:  
 manually or automatically.

**Manual driver update** – You can update your drivers manually by going to the manufacturer’s website for your devices, and searching for the most recent correct driver for each. Be sure to choose only drivers that are compatible with your variant of Windows 10.

**Automatic driver update** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  Driver Easy will automatically recognize your system and find the correct drivers for your devices, and your variant of Windows 10, and it will download and install them correctly :

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae696a52856.jpg)

 3) Click the **Update**  button next toany flagged driver to automatically download the correct version of that driver, then you can manually install it (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  which comes with full support and a 30-day money back guarantee. You’ll be prompted to upgrade when you click Update All.)

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ae6a0c3f690.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6Wfzj6YNDM?si=WRZQD9zCdQ1_tW1b&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

4) Reboot your Windows 10 PC.

5) On your keyboard, press the **Ctrl**  +**Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

 **Note:** If you can’t find gpedit.msc on your Windows 10 computer, here’s how you can get it: 1\. Download gpedit.msc(Group Policy Editor) from Internet  
 2\. When it’s done, Go to C:\\Windows\\SysWOW64, and copy the followings:  
 folders: GroupPolicy  
 GroupPolicyUsers  
 gpedit.msc(console document)  
 3\. Paste them in the following locations:  
 C:\\Windows\\System  
 C:\\Windows\\System32

 Hopefully this article could help you fix the problem. Feel free to comment below with your own experiences.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://facebook-videos.techidaily.com/updated-becoming-a-live-broadcast-pro-the-essential-guide-to-wirecast-and-fb-for-2024/"><u>[Updated] Becoming a Live Broadcast Pro The Essential Guide to Wirecast and FB for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-from-ordinary-to-outstanding-making-effortless-slow-motion-videos-in-android/"><u>[Updated] From Ordinary to Outstanding Making Effortless Slow-Motion Videos in Android</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-instagram-desktop-tips-for-effortless-video-posts/"><u>[Updated] Instagram Desktop Tips for Effortless Video Posts</u></a></li>
<li><a href="https://screen-capture.techidaily.com/2024-approved-demystifying-the-advanced-features-in-vlc/"><u>2024 Approved Demystifying the Advanced Features in VLC</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/approved-proven-techniques-for-crafting-impactful-youtube-video-content/"><u>2024 Approved Proven Techniques for Crafting Impactful YouTube Video Content</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-fixes-for-no-compatible-graphics-device-found-error-in-civilization-vi/"><u>Easy Fixes for 'No Compatible Graphics Device Found' Error in Civilization VI</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205981424-error-8007000e-on-windows-updates-ace-the-solution-in-no-time-with-this-guide/"><u>Error 8007000E on Windows Updates? Ace The Solution in No Time With This Guide!</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-how-to-fix-power-overload-at-your-devices-connection-point/"><u>Expert Tips: How to Fix Power Overload at Your Device's Connection Point</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-and-fix-module-not-found-errors-on-windows-or-mac/"><u>How to Address and Fix 'Module Not Found' Errors on Windows or Mac</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-old-music-from-your-oppo-by-fonelab-android-recover-music/"><u>How to recover old music from your Oppo</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/in-2024-maximize-your-media-influence-with-10-effortless-steps/"><u>In 2024, Maximize Your Media Influence with 10 Effortless Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/netflix-no-more-blackouts-troubleshooting-steps-for-perfect-picture-quality/"><u>Netflix No More Blackouts: Troubleshooting Steps for Perfect Picture Quality</u></a></li>
<li><a href="https://fox-direct.techidaily.com/rekindle-ambition-top-10-motivational-moments-for-2024/"><u>Rekindle Ambition Top 10 Motivational Moments for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-issue-when-your-lenovo-keyboard-fails-to-respond/"><u>Solving the Issue When Your Lenovo Keyboard Fails to Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-rdr2-out-of-memory-errors-in-their-tracks-by-adjusting-the-windows-page-file/"><u>Stop RDR2 Out of Memory Errors in Their Tracks by Adjusting the Windows Page File</u></a></li>
<li><a href="https://vp-tips.techidaily.com/the-last-word-on-tech-in-depth-analysis-of-the-google-pixel-8a-smartphone-are-we-witnessing-its-conclusion/"><u>The Last Word on Tech: In-Depth Analysis of the Google Pixel 8A Smartphone - Are We Witnessing Its Conclusion?</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-fight-against-airpods-connectivity-glitches-on-windows-new-strategies/"><u>Winning the Fight Against AirPods Connectivity Glitches on Windows - New Strategies</u></a></li>
</ul></div>

