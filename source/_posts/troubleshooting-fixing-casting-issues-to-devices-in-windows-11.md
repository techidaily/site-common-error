---
title: "Troubleshooting: Fixing Casting Issues to Devices in Windows 11"
date: 2024-10-22T18:22:31.038Z
updated: 2024-10-24T16:21:28.009Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Fixing Casting Issues to Devices in Windows 11"
excerpt: "This Article Describes Troubleshooting: Fixing Casting Issues to Devices in Windows 11"
thumbnail: https://thmb.techidaily.com/6a82b15c3b5908dade20c57e5528354889aa2d43fb699583edd3d2db4662000a.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1896510/19272" target="_top" id="1896510">
  <img src="//a.impactradius-go.com/display-ad/19272-1896510" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896510/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

---

### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  
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
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

taskkill /F /IM explorer.exe  
cd /d %userprofile%\AppData\Local  
attrib –h IconCache.db  
del IconCache.db  
start explorer.exe
3. Check if it helps restore your desktop icons. If not, try Tip 4, below.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144283/7443" target="_top" id="2144283">
  <img src="//a.impactradius-go.com/display-ad/7443-2144283" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144283/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Tip 4: Perform a system restore

If your desktop icons still don’t show up, you can perform a system restore to return your system to a date when the icons appeared normally on the desktop. Here’s how to perform a system restore to help fix your “desktop icons disappeared in Windows 10” issue:

1. Type **recovery** in the Windows search box, then press **Enter**.
2. At Recovery, click **Open System Restore**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a2728a7e.jpg)
3. Select **Choose a different restore point**, and click **Next**.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047361/19272" target="_top" id="2047361">
  <img src="//a.impactradius-go.com/display-ad/19272-2047361" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047361/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.
6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

### Tip 5: Reset your computer

If the steps above didn’t work for you. Resetting your computer is worth a try. It fixed the desktop icon issue for some users.

1. Click the **Start** button > the **Settings** icon.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b790f639.jpg)
2. Click **Update & security** \> **Recovery**.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082536/7443" target="_top" id="2082536">
  <img src="//a.impactradius-go.com/display-ad/7443-2082536" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082536/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://some-tips.techidaily.com/new-the-ultimate-gear-for-tempo-tinkering-in-stories/"><u>[New] The Ultimate Gear for Tempo Tinkering in Stories</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-expert-tips-for-seamless-integration-of-pip-in-microsoft-edge/"><u>[Updated] Expert Tips for Seamless Integration of PIP in Microsoft Edge</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-free-guide-perfecting-your-youtube-audio-to-text-conversion/"><u>[Updated] In 2024, Free Guide Perfecting Your YouTube Audio-to-Text Conversion</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-safariblocks-fixes-and-tips-to-open-webpages-effortlessly/"><u>Bypassing Safariblocks: Fixes and Tips to Open Webpages Effortlessly</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/tial-youtube-seo-techniques-for-enhanced-video-rankings-for-2024/"><u>Essential YouTube SEO Techniques for Enhanced Video Rankings for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209100579-fixed-windows-resource-protection-could-not-start-the-repair-service-sfc-error/"><u>Fixed: Windows Resource Protection Could Not Start the Repair Service — Sfc Error</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-solving-video-playback-sounds-addressing-microsofts-soundrenderer-fault-on-windows-10-youtube-fixes/"><u>Guide to Solving Video Playback Sounds: Addressing Microsoft's SoundRenderer Fault on Windows 10 - YouTube Fixes</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-fake-the-location-to-get-around-the-mlb-blackouts-on-xiaomi-13-ultra-drfone-by-drfone-virtual-android/"><u>In 2024, Fake the Location to Get Around the MLB Blackouts on Xiaomi 13 Ultra | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-google-pixel-8-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Google Pixel 8 | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/iphoneai/"><u>IPhone写真をAIがぼかす！無料アプリなし、画像編集手順｜フル/パーツ/バックグラウンドぼかし</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-installation-issue-fixing-error-code-80240020-once-and-for-all/"><u>Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All</u></a></li>
<li><a href="https://win-howtos.techidaily.com/step-by-step-solutions-for-fixing-ethernet-networking-errors-on-windows-11-and-windows-7/"><u>Step-by-Step Solutions for Fixing Ethernet Networking Errors on Windows 11 and Windows 7</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/step-by-step-solutions-for-watching-4k-videos-on-pcs-and-macs-without-glitches/"><u>Step-by-Step Solutions for Watching 4K Videos on PCs and Macs without Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/top-8-solutions-for-resolving-windows-11-update-error-0x800f0922/"><u>Top 8 Solutions for Resolving Windows 11 Update Error: 0X800F0922</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-desktop-is-unavailable-message-in-windows-config/"><u>Troubleshooting Tips for 'Desktop Is Unavailable' Message in Windows Config</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-the-secrets-to-clearing-filefolder-access-blockades-in-windows-environments/"><u>Unlocking the Secrets to Clearing File/Folder Access Blockades in Windows Environments</u></a></li>
</ul></div>
