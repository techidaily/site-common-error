---
title: "How to Fix the Error: Program Failure to Load Properly (Error Code 0xC000007B)"
date: 2024-12-29T05:45:44.867Z
updated: 2025-01-04T01:58:32.972Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix the Error: Program Failure to Load Properly (Error Code 0xC000007B)"
excerpt: "This Article Describes How to Fix the Error: Program Failure to Load Properly (Error Code 0xC000007B)"
thumbnail: https://thmb.techidaily.com/0c6fb3954d1e2db91c62e36b902addd3def785021471d7305b2b7e3d9392a35c.jpg
---

## How to Resolve the Persistent Windows Store Error 0X80072EE7: Proven Solutions Unveiled

If you’re greeted with **0x80072EE7** error code when opening**Windows Store** , you’re not alone.

But don’t worry, it’s not hard to fix at all…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 5 fixes for **0x80072EE7**

 All the fixes below work in**Windows 10** . You may not have to try all of them; just work from top down the list until your Windows Store runs smoothly again.

1. **[Start Windows Store service and change Windows Update startup type](https://tools.techidaily.com/drivereasy/download/)**
2. **[Run the DISM tool](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your graphics driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Change the DNS server address](https://tools.techidaily.com/drivereasy/download/)**
5. **[Register Windows Store package](https://tools.techidaily.com/drivereasy/download/)**

### Fix 1: Start Windows Store service and change Windows Update startup type

 Starting**Windows Store service** and change**Windows Update startup type** is a proven effective fix for our **0x80072ee7** in our Windows Store. To do so:

1. On your keyboard, press **the Windows logo key**   ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)  and **R**  at the same time, then copy & paste **services.msc** into the box and press   **Enter**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ef3aff37fc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Zgwn5kVI5V4?si=1j6j4OuSSndFieXU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2. Right-click on**Microsoft Store Install Service** and click**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b515a7b35011.jpg)
3. Scroll down to the bottom and double-click on**Windows Update** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51623b61cf7.jpg)
4. Select**Manual** in**Startup type** , click**Apply** \>**OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51629aa2ad6.jpg)
5. Launch your Windows Store again and see if the problem has been solved.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/epKTCSREjhI?si=Ez_hObK1FZrmEE7f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 2: Run the DISM tool

**DISM**  (**Deployment Image & Servicing Management** ) is a tool in Windows that helps us fix Windows-corruption-caused errors.  Sometimes this XXXX problem happens because of corruption and misconfigurations on our computer. If that’s the case, we’ll have to run DISM to check and fix the error.

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2. Type **the following command** and press **Enter** :  
**DISM.exe /Online /Cleanup-image /Restorehealth**  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b30abe4b92d4.jpg)  
 Wait a while for the whole process to finish.

3. Type **sfc /scannow**  and press **Enter** .
4. Restart your computer, run Windows Store again and see if it works properly this time.

---

### Fix 3: Update your graphics driver

 A corrupt/outdated/missing/wrong graphics driver is one of the common cause of this Windows store **0x80072ee7** error code. So you might have to**update your graphics driver to the latest** to make sure things won’t go worse (like snowy screens, blue screens of death) if unattended. There’re two ways you can update your device drivers — manually or automatically:

**Update your drivers manually** – You can update your device drivers manually by going to the manufacturer’s website, and searching for the most recent correct driver for the exact device. Be sure to choose only drivers that are compatible with your variant of Windows system versions.

**OR**

**Update your drivers automatically** – If you don’t have the time, patience or computer skills to update your drivers manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .  You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either **[the FREE](https://tools.techidaily.com/drivereasy/download/)**  or **[the Pro version](https://tools.techidaily.com/drivereasy/download/)**   of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b46ffcde1143.jpg)
3. You can upgrade to **[the Pro version](https://tools.techidaily.com/drivereasy/download/)**  and click **Update All** to automatically download and install the correct version of **ALL**  the drivers that are missing or out of date on your system.  

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b472528c2b06.jpg) You can also click **Update** to do it for free if you like, but it’s partly manual.
4. Restart your computer and hope everything goes off without a hitch on your computer.

 If the problem still lingers on after trying Driver Easy, feel free to contact our support team at **<support@drivereasy.com>** . Be sure to attach **the URL of this article** for more expedient and efficient guidance. ?

---

### Fix 4: Change the DNS server address

 Another possible cause for this issue is  the unstable network connection or the misconfiguration of DNS servers settings. So we might have to change the DNS server address to see if it gets fixed:

1. On your keyboard, press   **the Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)** and **R**  at the same time. Then copy & paste **control /name Microsoft.NetworkAndSharingCenter** into the box and click   **OK**  .  
**![](https://images.drivereasy.com/wp-content/uploads/2018/05/img_5af921398c56a.png)**

2. **Click Change adapter settings .**  
**![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae2935c0967f.jpg)**
3. Right-click on**the network adpater** (Ethernet in my case) and click **Properties** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b22081a8ea67.jpg)
4. Click **Internet Protocol Version 4 (TCP/IPv4)**  and then click **Properties** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2228b800796.jpg)
5. Click option **Use the following DNS server addreses** ,

 for **Preferred DNS server** , enter **8.8.8.8** ;

 for **Alternate DNS server** , enter **8.8.4.4.**

 Then click **OK** .  
 ![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2229e75f892.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/nWu29cqFjZA?si=TNZyCbPq68PQ0JIb" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 6) Restart your computer and re-launch your Windows Store to see if it works fine now.

---

### **Fix 5: Register Windows Store package**

 Fix 5 is about registering Windows Store package. This can help fix many issues(not opening, hanging, error codes etc) on Windows Store. To do this:

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

2. Copy & paste**the following command** into the window and press**Enter** .  
**PowerShell -ExecutionPolicy Unrestricted -Command “& {$manifest = (Get-AppxPackage Microsoft.WindowsStore).InstallLocation + ‘\AppxManifest.xml’ ; Add-AppxPackage -DisableDevelopmentMode -Register $manifest}”**
3. Once it finishes, close the command prompt window.
4. Restart your computer, open Windows Store again and see if the error code has been fixed.

---

 That’s it – top 5 tips for fixing the 0x80072ee7 Windows Store problem on your Windows 10 computer. Hope this helps and feel free to comment below if you have any further questions or thoughts. 🙂

* [Windows store](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://article-helps.techidaily.com/updated-2024-approved-turning-social-media-sounds-into-functional-phone-alarms/"><u>[Updated] 2024 Approved Turning Social Media Sounds Into Functional Phone Alarms</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-mastering-video-production-xstudio-deep-dive/"><u>[Updated] Mastering Video Production XStudio Deep Dive</u></a></li>
<li><a href="https://article-helps.techidaily.com/updated-revealing-veiled-youtube-reviewers-opinions-for-2024/"><u>[Updated] Revealing Veiled YouTube Reviewers' Opinions for 2024</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-the-art-of-background-elimination-in-graphic-designs-for-2024/"><u>[Updated] The Art of Background Elimination in Graphic Designs for 2024</u></a></li>
<li><a href="https://fox-links.techidaily.com/updated-the-mechanism-behind-imovie-trim/"><u>[Updated] The Mechanism Behind iMovie Trim</u></a></li>
<li><a href="https://common-error.techidaily.com/curbing-msmpengexe-cpu-hog-effective-techniques-to-enhance-system-efficiency-in-windows-11-solved/"><u>Curbing MsMpEng.exe CPU Hog: Effective Techniques to Enhance System Efficiency in Windows 11 [SOLVED]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-how-an-apple-employee-found-unexpected-joy-using-the-innovative-vision-pro-a-must-read-article/"><u>Discover How an Apple Employee Found Unexpected Joy Using the Innovative Vision Pro - A Must-Read Article!</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-non-responsive-volume-buttons-in-windows-10/"><u>Expert Tips for Fixing Non-Responsive Volume Buttons in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-corrupted-windows-store-caches-effective-strategies-and-solutions/"><u>Fix Corrupted Windows Store Caches: Effective Strategies and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204423354-fix-lol-pvpnet-patcher-kernel-has-stopped-working-easily/"><u>Fix LOL “PvP.net Patcher Kernel Has Stopped Working” Easily</u></a></li>
<li><a href="https://techidaily.com/hard-resetting-an-nokia-c22-device-made-easy-drfone-by-drfone-reset-android-reset-android/"><u>Hard Resetting an Nokia C22 Device Made Easy | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-wwe-2k-battlegrounds-and-enable-dx11-feature-level-100-without-issues/"><u>How to Fix WWE 2K Battlegrounds and Enable DX11, Feature Level 10.0 without Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-incompatible-timing-settings-on-your-computers-display/"><u>How to Resolve Incompatible Timing Settings on Your Computer's Display</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-all-must-knows-to-use-fake-gps-go-location-spoofer-on-nubia-z50s-pro-drfone-by-drfone-virtual-android/"><u>In 2024, All Must-Knows to Use Fake GPS GO Location Spoofer On Nubia Z50S Pro | Dr.fone</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-innovative-approaches-to-save-whatsapp-voice-calls/"><u>In 2024, Innovative Approaches to Save WhatsApp Voice Calls</u></a></li>
<li><a href="https://common-error.techidaily.com/mastery-in-minutes-repair-techniques-for-remote-server-not-reachable-error/"><u>Mastery in Minutes: Repair Techniques for 'Remote Server Not Reachable' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-your-system-integrity-solutions-for-repairing-broken-files-in-windows-11/"><u>Restore Your System Integrity: Solutions for Repairing Broken Files in Windows 11</u></a></li>
</ul></div>

