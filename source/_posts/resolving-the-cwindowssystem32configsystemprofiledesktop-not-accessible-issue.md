---
title: "Resolving the 'C:\\Windows\\System32\\Config\\SystemProfile\\Desktop Not Accessible' Issue"
date: 2025-02-09T06:10:38.159Z
updated: 2025-02-11T08:45:35.928Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving the 'C:\\Windows\\System32\\Config\\SystemProfile\\Desktop Not Accessible' Issue"
excerpt: "This Article Describes Resolving the 'C:\\Windows\\System32\\Config\\SystemProfile\\Desktop Not Accessible' Issue"
thumbnail: https://thmb.techidaily.com/cdf09465082716a317b2f16f4ef99338eb56d0b864c0910b3b97914866d756b0.jpg
---

## Troubleshooting Missing Desktop Icons on Windows 11 – Solved

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf526e8ebcab-1024x552.jpg)

If your desktop icons somehow disappear on your Windows 10 computer, don’t worry, you can try the tips below to fix the issue. Quickly and easily.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RvR5PNhspKE?si=uJcMYK9v-_Xq7fAg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

### Tip 2: Check your desktop icon settings

1. Right-click your desktop and click **Personalize**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf531bcea206.jpg)
2. Click **Themes** \> **Desktop icon settings**.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53220a4552.jpg)
3. Select the icons you want to show on desktop, then click **OK**.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53279e9206.jpg)
4. Check if your “desktop icons missing” problem is resolved. If not, try Tip 3, below.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

### Tip 3: Rebuild icon cache

You can also try these steps to rebuild the icon cache:

1. Run **Command Prompt** as administrator.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53d32cc341.jpg)
2. Copy-paste the following commands one at a time and press **Enter** after each command.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c-BHGGIC0zE?si=FzUQKZa-bx8OlKuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
3. In the **Reset this PC** area, click the **Get started** button. Then follow the on-screen instructions to reset your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf53b9dab56d.jpg)

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/jjGL9wFdlbo?si=Vb1JgZqRXNc03UGG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2022/02/de-update-all-rtx-3080.jpg)  
If you need assistance, please contact Driver Easy’s support team at **<support@drivereasy.com>**.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/vEYkX2NJgZw?si=IaHqlqJcYipwUOht" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-videos.techidaily.com/2024-approved-engage-your-audience-launching-instagram-lives/"><u>2024 Approved Engage Your Audience Launching Instagram Lives</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/acclaimed-ideas-top-tone-creators-for-apple-phones-for-2024/"><u>Acclaimed Ideas Top Tone Creators for Apple Phones for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-solutions-eradicating-the-windows-error-code-entry-point-not-present/"><u>DIY Solutions: Eradicating the Windows Error Code - Entry Point Not Present</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-resolved-halo-4-ue4-critical-bug-leading-to-system-failure/"><u>Fixing the [Resolved]: Halo 4 UE4 Critical Bug Leading to System Failure</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/framing-character-arcs-on-screen-for-2024/"><u>Framing Character Arcs on Screen for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-reactivating-the-night-light-option-in-windows-operating-systems-10-and-11/"><u>Guide to Reactivating the Night Light Option in Windows Operating Systems - 10 & 11</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-a1x-5g-phone-without-any-data-loss-by-drfone-android/"><u>How to Unlock Oppo A1x 5G Phone without Any Data Loss</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/in-2024-how-to-translate-youtube-videos-to-english-subtitles/"><u>In 2024, How to Translate YouTube Videos to English Subtitles</u></a></li>
<li><a href="https://extra-information.techidaily.com/maximizing-views-on-tiktok-unboxing-content/"><u>Maximizing Views on TikTok Unboxing Content</u></a></li>
<li><a href="https://common-error.techidaily.com/noise-troubleshooting-a-comprehensive-guide-to-fixing-forza-horizon-4s-muted-gameplay/"><u>Noise Troubleshooting: A Comprehensive Guide to Fixing Forza Horizon 4'S Muted Gameplay</u></a></li>
<li><a href="https://solve-howtos.techidaily.com/professionelle-losungen-fur-die-rettung-von-daten-auf-einem-gespaltenen-datentrager/"><u>Professionelle Lösungen Für Die Rettung Von Daten Auf Einem Gespaltenen Datenträger</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-the-media-unresponsive-problem-in-windows-a-step-by-step-guide/"><u>Solve the 'Media Unresponsive' Problem in Windows - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/system-seizure-irreparable-device-error/"><u>System Seizure: Irreparable Device Error</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/the-ultimate-solution-for-secure-and-systematic-deletion-on-macs-unveiling-the-power-of-stellar-file-eraser-standard-with-automated-cleanup-features/"><u>The Ultimate Solution for Secure & Systematic Deletion on Macs - Unveiling the Power of Stellar File Eraser Standard with Automated Cleanup Features</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-address-missing-d3dx939dll-file/"><u>Troubleshooting Guide: How to Address Missing d3dx9_39.dll File</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-oculus-device-malfunctions-a-step-by-step-guide/"><u>Troubleshooting Oculus Device Malfunctions: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-reactivating-your-windows-update-functionality-efficiently/"><u>Troubleshooting Tips: Reactivating Your Windows Update Functionality Efficiently</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-creality-ender-v3-a-budget-friendly-open-source-additive-manufacturing-marvel/"><u>Unveiling the Creality Ender 지오 V3: A Budget-Friendly Open Source Additive Manufacturing Marvel</u></a></li>
<li><a href="https://technical-tips.techidaily.com/what-is-pope-francis-stance-on-utilizing-email-for-papal-communications/"><u>What Is Pope Francis' Stance on Utilizing Email for Papal Communications?</u></a></li>
</ul></div>

