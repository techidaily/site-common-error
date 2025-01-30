---
title: "How to Fix the Error: Program Failure to Load Properly (Error Code 0xC000007B)"
date: 2025-01-26T20:16:33.734Z
updated: 2025-01-30T09:26:26.263Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### Fix 1: Start Windows Store service and change Windows Update startup type

 Starting**Windows Store service** and change**Windows Update startup type** is a proven effective fix for our **0x80072ee7** in our Windows Store. To do so:

1. On your keyboard, press **the Windows logo key**   ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)  and **R**  at the same time, then copy & paste **services.msc** into the box and press   **Enter**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b4ef3aff37fc.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/SDUPd69Qfls?si=uIGZG-riskwmVZYg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2. Right-click on**Microsoft Store Install Service** and click**Start** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b515a7b35011.jpg)
3. Scroll down to the bottom and double-click on**Windows Update** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51623b61cf7.jpg)
4. Select**Manual** in**Startup type** , click**Apply** \>**OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/465CTOm8om0?si=63RxowNMCFA4fPUa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/07/img_5b51629aa2ad6.jpg)
5. Launch your Windows Store again and see if the problem has been solved.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qObsqoJB9LI?si=ppqxfXzP0UL4J6Tp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

---

### Fix 2: Run the DISM tool

**DISM**  (**Deployment Image & Servicing Management** ) is a tool in Windows that helps us fix Windows-corruption-caused errors.  Sometimes this XXXX problem happens because of corruption and misconfigurations on our computer. If that’s the case, we’ll have to run DISM to check and fix the error.

1. On your keyboard, press the   **Windows logo key ![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae0331bc08e4.png)**  and type **cmd** . Then right click on **Command Prompt**   and click **Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b28ad73ad4a9.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaWcXdTn5SE?si=QbxEkX-4a17J5RVs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xq2r4ZKM-Po?si=fA2DdEB1op-atCkz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

2. **Click Change adapter settings .**  
**![](https://images.drivereasy.com/wp-content/uploads/2018/04/img_5ae2935c0967f.jpg)**
3. Right-click on**the network adpater** (Ethernet in my case) and click **Properties** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b22081a8ea67.jpg)
4. Click **Internet Protocol Version 4 (TCP/IPv4)**  and then click **Properties** .  

![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2228b800796.jpg)
5. Click option **Use the following DNS server addreses** ,

 for **Preferred DNS server** , enter **8.8.8.8** ;

 for **Alternate DNS server** , enter **8.8.4.4.**

 Then click **OK** .  
 ![](https://images.drivereasy.com/wp-content/uploads/2018/06/img_5b2229e75f892.jpg)

 6) Restart your computer and re-launch your Windows Store to see if it works fine now.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://desktop-recording.techidaily.com/updated-the-screencast-primer-fundamental-knowledge-for-video-enthusiasts-for-2024/"><u>[Updated] The Screencast Primer Fundamental Knowledge for Video Enthusiasts for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-typhoon-h-by-yuneec-an-in-depth-analysis/"><u>2024 Approved Typhoon H by Yuneec An In-Depth Analysis</u></a></li>
<li><a href="https://fox-glue.techidaily.com/an-in-depth-look-at-movavis-video-edition-plus-for-2e24-for-2024/"><u>An In-Depth Look at Movavi's Video Edition Plus for 2E24 for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unrecognized-bluetooth-gadgets-in-windows-11/"><u>How to Fix Unrecognized Bluetooth Gadgets in Windows 11</u></a></li>
<li><a href="https://some-tips.techidaily.com/how-to-integrate-artificial-intelligence-in-software-development-key-insights-and-best-practices-zdnet/"><u>How to Integrate Artificial Intelligence in Software Development: Key Insights & Best Practices | ZDNet</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-update-or-downgrade-iphone-15-pro-max-without-losing-data-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Update or Downgrade iPhone 15 Pro Max Without Losing Data? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211785288-miracast-compatibility-issues-update-your-graphics-driver-now/"><u>Miracast Compatibility Issues? Update Your Graphics Driver Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210632451-overcoming-touchpad-glitches-making-your-windows-11-pad-responsive-again/"><u>Overcoming Touchpad Glitches: Making Your Windows 11 Pad Responsive Again</u></a></li>
<li><a href="https://review-topics.techidaily.com/possible-solutions-to-restore-deleted-music-from-motorola-edge-40-pro-by-fonelab-android-recover-music/"><u>Possible solutions to restore deleted music from Motorola Edge 40 Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-lols-persistent-sluggish-downloads/"><u>Resolved! Troubleshooting LoL's Persistent Sluggish Downloads</u></a></li>
<li><a href="https://common-error.techidaily.com/silent-partner-in-perfectly-configured-network/"><u>Silent Partner in Perfectly Configured Network</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-overcome-post-update-windows-10-booting-failures-with-these-fixes/"><u>Solved! Overcome Post-Update Windows 10 Booting Failures With These Fixes</u></a></li>
<li><a href="https://win-net.techidaily.com/solving-graphics-card-problems-in-windows-a-comprehensive-guide-by-yl-software/"><u>Solving Graphics Card Problems in Windows: A Comprehensive Guide by YL Software</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-cause-of-never-ending-launch-cycles-in-the-elder-scrolls-v-skyrim/"><u>Solving the Cause of Never-Ending Launch Cycles in The Elder Scrolls V: Skyrim</u></a></li>
<li><a href="https://some-guidance.techidaily.com/step-into-hd-color-on-windows-watch-edit-relish-videos-for-2024/"><u>Step Into HD Color on Windows Watch, Edit, Relish Videos for 2024</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/the-ultimate-list-8-ranked-android-video-tile-maker-options-freepaid/"><u>The Ultimate List #8 Ranked Android Video Tile Maker Options (Free/Paid)</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-try-when-torrents-arent-downloading-properly/"><u>What To Try When Torrents Aren't Downloading Properly</u></a></li>
</ul></div>

