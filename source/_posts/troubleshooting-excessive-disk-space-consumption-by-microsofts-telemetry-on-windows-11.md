---
title: Troubleshooting Excessive Disk Space Consumption by Microsoft's Telemetry on Windows 11
date: 2024-08-27T13:49:52.943Z
updated: 2024-08-28T13:49:52.943Z
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
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
### Method 2: Using Registry Editor

 1)On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a1bafc786d58.png)**  and **R** at the same time to invoke a **Run** command.

2) T ype**regedit**  in the box and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a22807d2e.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=36506229&QTY=1&AFFILIATE=108875&CART=1"><video width="100%" height="" class="rounded-t-md shadow-lg relative z-20" controls="" autoplay="" loop="" muted="" playsinline="" webkit-playinginline="">
<source type="video/mp4" src="https://aidaform.com/images/videos/aidaform-welcome-site.mp4"><source type="video/webm" src="https://aidaform.com/images/videos/aidaform-welcome-site.webm"></video></a>
<!-- affiliate ads end -->
 3) Click **YES**  when prompted by User Account Control.

 4) Go to **HKEY\_LOCAL\_MACHINE** \> **SOFTWARE** \>**Policies** \>**Microsoft** \>**Windows** \>**DataCollection.**

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a4ede532e.jpg)

<!-- affiliate ads begin -->
<a href="https://bluettieu.pxf.io/c/5597632/2042323/17091" target="_top" id="2042323"><img src="//a.impactradius-go.com/display-ad/17091-2042323" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="3840" height="1600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042323/17091" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 5) Double-click**Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a53baa7f6.png)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4537546&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/7_copy_2_2_hdpro.png" border="0">HD Video Converter Factory Pro</a>
<!-- affiliate ads end -->
**NOTE:** If you can’t find Allow Telemetry, create it manually: Right-click on DataCollection and choose**New** \>**DWORD (32-bit) Value** . Then name the new value **Allow** **Telemetry** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9-2.png)

 6) Set**Value date** to **0** (zero) and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/12/img_5a27a576ca320.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=3922934&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/4b0a0290ad7df100b77e86839989a75e/products/ripperpro.png" border="0">WonderFox DVD Ripper Pro</a>
<!-- affiliate ads end -->
 7) On your keyboard, press **Ctrl**  \+ **Shift**  \+ **Esc**  keys (at the same time) to open your Task Manager, check to see if Microsoft Compatibility Telemetry takes up a normal disk usage.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
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


