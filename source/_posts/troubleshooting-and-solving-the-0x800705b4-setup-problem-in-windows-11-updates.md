---
title: Troubleshooting and Solving the 0X800705b4 Setup Problem in Windows 11 Updates
date: 2024-10-05T07:13:57.275Z
updated: 2024-10-06T19:01:29.959Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Solving the 0X800705b4 Setup Problem in Windows 11 Updates
excerpt: This Article Describes Troubleshooting and Solving the 0X800705b4 Setup Problem in Windows 11 Updates
thumbnail: https://thmb.techidaily.com/3e8a6c48903de348edfc32de01dc40c1bc954d345539201fb129df4e83ad3d30.jpg
---

## Troubleshooting Missing Desktop Icons on Windows 11 – Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these tips

You don’t have to try them all; just work your way down the list until you find the one that works for you.

1. [**Enable Show desktop icons**](#t1)
2. [**Check your desktop icon settings**](#t2)
3. [**Rebuild icon cache**](#t4)
4. [**Perform a system restore**](#t5)
5. [**Reset your computer**](#t6)
6. [**Bonus tip**](#t7)

### Tip 1: Enable Show desktop icons

Make sure you have enabled the “Show desktop icon” feature on Windows 10:

1. Right-click your desktop, click **View**, and check **Show desktop icons**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf52ca259fe4.jpg)
2. Check to see if your desktop icons are back. If not, try Tip 2, below.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037338/7443" target="_top" id="2037338">
  <img src="//a.impactradius-go.com/display-ad/7443-2037338" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037338/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1918684/19272" target="_top" id="1918684">
  <img src="//a.impactradius-go.com/display-ad/19272-1918684" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1918684/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135368/19272" target="_top" id="2135368">
  <img src="//a.impactradius-go.com/display-ad/19272-2135368" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135368/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

---

### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

taskkill /F /IM explorer.exe  
cd /d %userprofile%\AppData\Local  
attrib –h IconCache.db  
del IconCache.db  
start explorer.exe
3. Check if it helps restore your desktop icons. If not, try Tip 4, below.

---

### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

### Bonus tip

A missing or outdated graphics driver may also stop items from appearing properly on PC. You should make sure your graphics card driver is up to date. There are two ways to update your graphics driver: **manually** and **automatically**.

**Update your graphics driver manually** — You can update your driver manually by going to the hardware manufacturer’s website, and searching for the latest driver for your graphics card. But if you take this approach, be sure to choose the driver that’s compatible with the exact model number of your hardware, and your version of Windows.

OR

**Update your graphics driver automatically** — If you don’t have the time, patience, or computer skills to update your driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. Driver Easy handles it all.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.
2. Run Driver Easy and click **Scan Now**. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)
3. Click **Update** next to any flagged devices to automatically download the correct version of their drivers, then you can install them manually. Or click **Update All** to automatically download and install them all automatically. (This requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All. You get full support and a 30-day money-back guarantee.)  
![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

---

Hopefully, this can help you out.

If you have any other suggestions, please feel free to leave a comment below.

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
<li><a href="https://discord-videos.techidaily.com/new-masterminds-of-memorable-discord-symbols-revealed/"><u>[New] Masterminds of Memorable Discord Symbols Revealed</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-quick-corrections-for-iphone-shot-blur-issues/"><u>[Updated] 2024 Approved Quick Corrections for iPhone Shot Blur Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-reviving-the-keyboard-of-your-malfunctioning-dell-device/"><u>DIY Fixes: Reviving the Keyboard of Your Malfunctioning Dell Device</u></a></li>
<li><a href="https://fox-info.techidaily.com/essence-of-virtual-story-delivery/"><u>Essence of Virtual Story Delivery</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/gratuit-online-converting-nef-bilders-naar-bmp-formaat-movavi/"><u>Gratuit Online: Converting NEF Bilders Naar BMP Formaat - Movavi</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/half-price-geforce-now-offer-exclusive-temporary-discounts-unveiled/"><u>Half-Price GeForce Now Offer: Exclusive Temporary Discounts Unveiled!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-the-remote-procedure-call-service-not-responding-error-in-windows-systems/"><u>How to Repair the Remote Procedure Call Service Not Responding Error in Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-remedies-restore-functionality-to-faulty-logitech-keyboards/"><u>Immediate Remedies: Restore Functionality to Faulty Logitech Keyboards</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-tecno-spark-20-pro-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>In 2024, Tecno Spark 20 Pro ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
<li><a href="https://common-error.techidaily.com/initiating-windows-11-successfully-remedies-for-persistent-freezing-at-startup/"><u>Initiating Windows 11 Successfully: Remedies for Persistent Freezing at Startup</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-malfunction-learn-how-to-stop-incorrect-letter-inputs/"><u>Keyboard Malfunction? Learn How to Stop Incorrect Letter Inputs</u></a></li>
<li><a href="https://discord-videos.techidaily.com/mastering-video-format-transformation-the-ultimate-tutorial-for-lrv-to-mp4-conversion/"><u>Mastering Video Format Transformation: The Ultimate Tutorial for LRV to MP4 Conversion</u></a></li>
<li><a href="https://media-tips.techidaily.com/mastering-wma-your-complete-resource-for-insights-and-necessities/"><u>Mastering WMA: Your Complete Resource for Insights and Necessities</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-tips-to-speed-up-boot-time-for-windows-7-users/"><u>Quick Tips to Speed Up Boot Time for Windows 7 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-excessive-cpu-consumption-in-windows-sound-device-graph/"><u>Resolve Excessive CPU Consumption in Windows Sound Device Graph</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-your-non-responsive-wacom-graphics-tablet/"><u>Troubleshooting Guide: Fixing Your Non-Responsive Wacom Graphics Tablet</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-make-it-loop-10-best-free-online-video-looping-platforms-for-2024/"><u>Updated Make It Loop 10 Best Free Online Video Looping Platforms for 2024</u></a></li>
</ul></div>

