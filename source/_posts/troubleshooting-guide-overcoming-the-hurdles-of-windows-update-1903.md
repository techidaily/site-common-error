---
title: "Troubleshooting Guide: Overcoming the Hurdles of Windows Update 1903"
date: 2024-09-22T16:24:57.276Z
updated: 2024-09-26T18:12:41.097Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Overcoming the Hurdles of Windows Update 1903"
excerpt: "This Article Describes Troubleshooting Guide: Overcoming the Hurdles of Windows Update 1903"
thumbnail: https://thmb.techidaily.com/d70a53087560a098bb105b6da250ee7a060b663d95025554525e6d2ddaef6a7e.jpg
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

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037350/7443" target="_top" id="2037350">
  <img src="//a.impactradius-go.com/display-ad/7443-2037350" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037350/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<span id="1977028">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1977028.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1977028">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1977028.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1977028%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1977028/22993" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2094477/7443" target="_top" id="2094477">
  <img src="//a.impactradius-go.com/display-ad/7443-2094477" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094477/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a34c35bc.jpg)
4. Check the box beside **Show more restore points**. You should see a list of ‘restore points’. These are like backups of your computer, as it was at that particular date and time. Think back to a date when your desktop icons showed up, and **select a restore point** from that date or slightly earlier (but no later).  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53a4d84f3c.jpg)
5. Click **Next** \> **Finish**.
6. Check to see if your desktop icons are now restored on Windows 10\. If not, try Tip 5, below.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1902294/19272" target="_top" id="1902294">
  <img src="//a.impactradius-go.com/display-ad/19272-1902294" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902294/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-in-2024-fading-techniques-for-aural-balance/"><u>[New] In 2024, Fading Techniques for Aural Balance</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-5-must-try-websites-for-cost-free-effects/"><u>[Updated] 2024 Approved 5 Must-Try Websites for Cost-Free Effects</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-funny-facades-top-quality-free-meme-files/"><u>[Updated] Funny Facades Top-Quality, FREE Meme Files</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-growth-hacking-for-youtube-stars-maximizing-fans-for-2024/"><u>[Updated] Growth Hacking for YouTube Stars Maximizing Fans for 2024</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-premier-funny-photo-tool/"><u>[Updated] Premier Funny Photo Tool</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-from-obscurity-to-the-top-the-seo-playbook-for-podcasters/"><u>2024 Approved From Obscurity to the Top The SEO Playbook for Podcasters</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-platform-faceoff-twitchs-challenge-to-youtube/"><u>2024 Approved The Platform Faceoff Twitch's Challenge to YouTube</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202561962-combat-the-disappearing-cursor-problem-on-your-windows-11-touchpad-today/"><u>Combat the Disappearing Cursor Problem on Your Windows 11 Touchpad Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-your-surface-pro-4-stylus-not-working-dilemma/"><u>Effective Fixes for Your Surface Pro 4 Stylus Not Working Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-80240020-in-windows-10-installation-troubleshooting-steps-and-fixes/"><u>Error Code 80240020 in Windows 10 Installation: Troubleshooting Steps & Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-resolving-problems-with-malfunctioning-laptop-usb-input-devices/"><u>Expert Advice: Resolving Problems with Malfunctioning Laptop USB Input Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210596795-how-to-fix-and-restore-bluetooth-functionality-on-your-windows-10-laptopdesktop-efficiently/"><u>How to Fix and Restore Bluetooth Functionality on Your Windows 10 Laptop/Desktop Efficiently</u></a></li>
<li><a href="https://screen-capture.techidaily.com/in-2024-swift-systems-simplified-screen-capture-procedures-dell/"><u>In 2024, Swift Systems Simplified Screen Capture Procedures (Dell)</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-delays-in-launching-windows-7-top-tips-and-tricks/"><u>Resolving Delays in Launching Windows 7 - Top Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-eliminate-persistent-buffering-on-your-kodi-device/"><u>Solution Found: Eliminate Persistent Buffering on Your Kodi Device</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-preventing-issues-with-the-successful-implementation-of-battleye-anti-cheat/"><u>Solved: Preventing Issues with the Successful Implementation of BattlEye Anti-Cheat</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/the-ultimate-guide-to-mobile-snapchat-recording/"><u>The Ultimate Guide to Mobile Snapchat Recording</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-dxgkrnl-fatal-errors-in-windows/"><u>Ultimate Guide: Resolving DXGKRNL Fatal Errors in Windows</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/win-11-strategies-to-successfully-save-mov-files-for-2024/"><u>Win 11 Strategies to Successfully Save .mov Files for 2024</u></a></li>
</ul></div>
