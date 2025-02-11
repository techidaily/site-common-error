---
title: "Resolved: Optimizing WDF Performance & Reducing System CPU Usage"
date: 2025-02-04T19:00:06.176Z
updated: 2025-02-10T18:02:07.683Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: Optimizing WDF Performance & Reducing System CPU Usage"
excerpt: "This Article Describes Resolved: Optimizing WDF Performance & Reducing System CPU Usage"
thumbnail: https://thmb.techidaily.com/69a1f779573ffb1d9703aa1f0c2a82407b77bc35052e19faef90f3eeabcd3dc4.jpg
---

## Optimizing ntoskrnl.exe for Better Performance on PC

 If your Windows is working slowly, and when you check your Task Manager and find that the**System** item is hogging much of your CPU (or Disk in some cases) usage, you’re not alone. Many Windows users are reporting this problem. Don’t worry, it’s possible to fix.

**\*** Right-click the**System** item and click**Properties** , you’ll see a new item called**ntoskrnl.exe** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b0f9d613fd6.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ME5-sAQJVE4?si=ZfcvJSnhQevWtjI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## What is ntoskrnl.exe?

 Ntoskrnl.exe, short for**Windows NT operating system kernel** , is a fundamental part of the system. Usually, when you see the uncommon usage of high CPU or memory, you should shut down the possible programs that are causing the problem.

 If this happens a lot, you should see if there is something wrong with certain application settings or files in your system.

## How do I fix it?

 Here are 4 methods for you to try. You may not have to try them all; just work your way down until you find the one that works for you.

* **[Method 1: Disable Windows Search Service](#a)**
* **[Method 2: Check Incompatible Programs](#b)**
* **[Method 3: Run SFC and DISM](#c)**
* **[Method 4: Disable Runtime Broker](#d)** [](#d)

 It is always suggested that you keep your device drivers updated to eliminate the possibility of such problems.

 Driver Easy is a tool that detects, downloads, and updates drivers (if you go Pro). You can use it to fix any driver problems. If you go to Pro, you can even update all drivers with just one click. If the high system CPU usage problem is caused by drivers, you can use Driver Easy to fix it quickly.

 You can update your drivers automatically with either the [**7 days free trial**](https://tools.techidaily.com/drivereasy/download/) or the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) of Driver Easy. It takes just 2 clicks, and you get full support and a 30-day money-back guarantee with the Pro version:

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the **Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://www.drivereasy.com/wp-content/uploads/2020/10/6_0_scan-now.jpg)
3. Click the**Activate & Update** button next to the flagged device to automatically download and install the correct version of this driver.  

 Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (You’ll need the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  for this – when you select Update All, you’ll get a prompt to upgrade. If you’re not prepared to purchase the Pro version yet, Driver Easy provides a 7-day trial at no cost, granting access to all Pro features like fast downloads and easy installation. No charges will occur until after your 7-day trial period ends.)  
![](https://www.drivereasy.com/wp-content/uploads/2021/05/NVIDIA-GeForce-RTX-3090-Ti-3.jpg)
4. After updating, restart your computer to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

## Method 1: Disable Windows Search service

 A lot of users suggested that disabling Windows Search helps to reduce the CPU and Disk usage caused by ntoskrnl.exe. To see if this does the trick for you as well:

1. On your keyboard, press the **Windows key** and**X** at the same time, then click **Computer management** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/computer-management.png)
2. Expand**Services and Applications** and click**Services** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/wNhKhWc0wLc?si=1XLYV0sXV52Xc0lu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2016/09/services-and-applications.jpg)
3. Double-click**Windows Search** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/windwos-search-6101.jpg)
4. In the**General** tab, click **Stop** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2016/09/stop-button.jpg)
5. Wait for the service to stop, then press**OK** to save the change and exit.  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/ok-to-save-the-change-6104.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/eMEJvwMM0vk?si=EQF_jo_4u9v5iJ_C" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 2: Check incompatible programs

 Some users say that this only happens when they use certain programs. Especially when they have antivirus software running in the background. The antivirus software might have some conflicts with certain programs. The next time you encounter this situation, try to pay extra attention to see if you can find the program that is messing with your system. If such a program can be located, try reinstallingit or uninstalling it completely.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 3: Run SFC and DISM

 Corrupted system files may cause high CPU and disk usage with ntoskrnl.exe, but luckily, there are two built-in tools that can help to identify and repair such bad system files. The whole process could take some time, and we suggest you don’t run any other programs when doing the test. To run these tools:

### 3.1\. Scan corrupt files with System File Checker

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** at the same time to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following command and hit**Enter** .

sfc /scannow

 3) System File Checker will then scan all system files and repair any corrupted or missing ones it detected. This may take 3-5 minutes.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/scan-now.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3.2\. Run dism.exe

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

 Click**Yes** when prompted for permission to make changes to your device.

 2) In the Command Prompt window, copy and paste the following commands and hit**Enter** after each line:

dism.exe /online /cleanup-image /scanhealth

dism.exe /online /cleanup-image /restorehealth

2) When the process finishes:

* If the DISM tool gives you errors, you can always try this command line. This will take up to 2 hours.

dism /online /cleanup-image /startcomponentcleanup

* If you get **Error: 0x800F081F** , reboot your computer, then open Command Prompt as administrator again (step 1) and run this command line instead:

Dism.exe /Online /Cleanup-Image /AnalyzeComponentStore

 When these tests are done, see if the ntoskrnl.exe high CPU or disk usage problem remains. If the problem still persists, please move on to the next fix.

## Method 4: Disable Runtime Broker

 Normally, the runtime broker process should only use a very low CPU resource, but if things go wrong, it could take up to 100% CPU and disk usage, making your Windows run slowly and buggy. In this case, you can try to disable it to see if it helps. To do so:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here: [How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the **Windows** key and the **R** key together. Type **regedit** and hit **Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\TimeBroker`  

![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker.png)
4. On the right side, double-click**Start** , and change its value to**4** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/runtime-broker-4.png)
5. Restart your computer for the changes to take effect.

See if the ntoskrnl.exe high CPU or disk usage problem remains.

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
<li><a href="https://youtube-tips.techidaily.com/hort-film-producer-yt-for-2024/"><u>[New] Short Film Producer YT for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-2024-approved-step-into-the-world-of-manga-and-anime-with-a-tap-on-snapchat/"><u>[Updated] 2024 Approved Step Into the World of Manga & Anime with a Tap on Snapchat</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-top-recommended-asmrists-for-nighttime-calmness/"><u>[Updated] Top Recommended ASMRists for Nighttime Calmness</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-best-route-generator-apps-you-should-try-on-huawei-nova-y71-drfone-by-drfone-virtual-android/"><u>5 Best Route Generator Apps You Should Try On Huawei Nova Y71 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/automating-youtube-playback-in-social-networks-a-focus-on-facebook-for-2024/"><u>Automating Youtube Playback in Social Networks A Focus on Facebook for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/combat-network-troubles-fix-a-stalled-dns-server-in-4-steps/"><u>Combat Network Troubles: Fix a Stalled DNS Server in 4 Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-windows-update-tips-for-solving-error-0x80n001f-successfully/"><u>Error-Free Windows Update! Tips for Solving Error 0X80n001f Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-complete-the-windows-10-update-process-for-version-1803-issues-resolved/"><u>How to Successfully Complete the Windows 10 Update Process for Version 1803 (Issues Resolved)</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-htc-u23-pro-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>How to Track HTC U23 Pro Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-5-ways-to-track-apple-iphone-15-pro-max-without-app-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Ways to Track Apple iPhone 15 Pro Max without App | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/in-2024-how-to-teleport-your-gps-location-on-nokia-c300-drfone-by-drfone-virtual-android/"><u>In 2024, How To Teleport Your GPS Location On Nokia C300? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-microphone-problems-in-the-steelseries-arctis-series-a-step-by-step-guide/"><u>Resolving Microphone Problems in the SteelSeries Arctis Series: A Step-by-Step Guide</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-guide-to-repairing-sound-on-your-toshiba-laptop-computer/"><u>Step-by-Step Guide to Repairing Sound on Your Toshiba Laptop Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-overcome-the-windows-11-update-error-code-0x800705b4-tutorial/"><u>Step-by-Step Solution to Overcome the Windows 11 Update Error: Code 0X800705B4 [Tutorial]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-solving-speaker-distortions-in-windows-operating-systems-w11w7/"><u>Troubleshooting and Solving Speaker Distortions in Windows Operating Systems [W11/W7]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-missing-files-in-systems-tips-and-techniques/"><u>Troubleshooting Missing Files in Systems - Tips and Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-youtube-sound-problems-on-windows-10-a-step-by-step-guide/"><u>Troubleshooting YouTube Sound Problems on Windows 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/1723808313778-troubleshooting-pc-starts-without-screen-output-solved/"><u>Troubleshooting: PC Starts without Screen Output – Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/wired-into-solutions-pc-and-headphones-reconcile-issues/"><u>Wired Into Solutions: PC & Headphones Reconcile Issues</u></a></li>
</ul></div>

