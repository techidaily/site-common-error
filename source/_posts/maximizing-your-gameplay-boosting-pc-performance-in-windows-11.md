---
title: "Maximizing Your Gameplay: Boosting PC Performance in Windows 11"
date: 2024-12-21T19:05:52.233Z
updated: 2024-12-25T16:12:48.293Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Maximizing Your Gameplay: Boosting PC Performance in Windows 11"
excerpt: "This Article Describes Maximizing Your Gameplay: Boosting PC Performance in Windows 11"
thumbnail: https://thmb.techidaily.com/3854233be38a7a3b692f6b1c87d1917c44d3f0b5ad0376d97a1f07070c0cf22e.jpg
---

## Optimizing ntoskrnl.exe for Better Performance on PC

 If your Windows is working slowly, and when you check your Task Manager and find that the**System** item is hogging much of your CPU (or Disk in some cases) usage, you’re not alone. Many Windows users are reporting this problem. Don’t worry, it’s possible to fix.

**\*** Right-click the**System** item and click**Properties** , you’ll see a new item called**ntoskrnl.exe** .

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b0f9d613fd6.png)

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

**The Pro version of Driver Easy** comes with _full technical support_ . If you need assistance, please contact **Driver Easy’s support team** at **[support@drivereasy.com](https://bellelily.pxf.io/m5azgm) .**

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Disable Windows Search service

 A lot of users suggested that disabling Windows Search helps to reduce the CPU and Disk usage caused by ntoskrnl.exe. To see if this does the trick for you as well:

1. On your keyboard, press the **Windows key** and**X** at the same time, then click **Computer management** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/computer-management.png)
2. Expand**Services and Applications** and click**Services** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YpnYKIrpgZQ?si=94zicAHp1CH-0oso" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://www.drivereasy.com/wp-content/uploads/2016/09/services-and-applications.jpg)
3. Double-click**Windows Search** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/windwos-search-6101.jpg)
4. In the**General** tab, click **Stop** .  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/stop-button.jpg)
5. Wait for the service to stop, then press**OK** to save the change and exit.  
![](https://www.drivereasy.com/wp-content/uploads/2016/09/ok-to-save-the-change-6104.jpg)

## Method 2: Check incompatible programs

 Some users say that this only happens when they use certain programs. Especially when they have antivirus software running in the background. The antivirus software might have some conflicts with certain programs. The next time you encounter this situation, try to pay extra attention to see if you can find the program that is messing with your system. If such a program can be located, try reinstallingit or uninstalling it completely.

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

### 3.2\. Run dism.exe

 1) On your keyboard, press the**Windows** logo key and**R** at the same time. Type**cmd** and press**Ctrl+Shift+Enter** to run Command Prompt as administrator.

![](https://images.drivereasy.com/wp-content/uploads/2019/12/cmd-1.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/w7c5EHp-GDw?si=UTw7lZR0wTmRjp8W" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S0b9szh8vEk?si=NlGzpJ6MN_SJNk5A" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 4: Disable Runtime Broker

 Normally, the runtime broker process should only use a very low CPU resource, but if things go wrong, it could take up to 100% CPU and disk usage, making your Windows run slowly and buggy. In this case, you can try to disable it to see if it helps. To do so:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here: [How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the **Windows** key and the **R** key together. Type **regedit** and hit **Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location: `HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Services\TimeBroker`  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/yr0yS_Ywrjs?si=QxzYiX1KmUaExmlo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://fox-access.techidaily.com/updated-effortless-video-magic-the-no-cost-guide/"><u>[Updated] Effortless Video Magic The No-Cost Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-expertise-in-edits-selecting-premier-video-tools-for-2024/"><u>[Updated] Expertise in Edits Selecting Premier Video Tools for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-navigate-the-nuances-of-zooms-broadcast-technology-for-youtube-pros/"><u>[Updated] Navigate the Nuances of Zoom's Broadcast Technology for YouTube Pros</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-realme-12-pro-5g-drfone-by-drfone-virtual-android/"><u>15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Realme 12 Pro 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/approved-step-by-step-guide-to-adding-your-own-video-images/"><u>2024 Approved Step-by-Step Guide to Adding Your Own Video Images</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206559286-african-americans/"><u>African Americans:</u></a></li>
<li><a href="https://tech-haven.techidaily.com/chatgpt-and-user-persona-development-a-guide-to-superior-results/"><u>ChatGPT and User Persona Development: A Guide to Superior Results</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-resolve-the-there-was-an-issue-error-when-restoring-windows-10/"><u>How to Successfully Resolve the 'There Was an Issue' Error When Restoring Windows 10</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-4-ways-to-transfer-music-from-google-pixel-7a-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 4 Ways to Transfer Music from Google Pixel 7a to iPhone | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/issue-resolved-how-to-repair-broken-numeric-keys-on-a-computer-keyboard/"><u>Issue Resolved: How to Repair Broken Numeric Keys on a Computer Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-no-device-found-challenge-with-icue-drivers/"><u>Overcoming the 'No Device Found' Challenge with iCUE Drivers</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-delayed-keyboard-responses-easy-solutions-inside/"><u>Resolving Delayed Keyboard Responses: Easy Solutions Inside!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/solving-the-helldivers-ii-missing-msvcr110dll-file-issue/"><u>Solving the Helldivers II Missing MSVCR110.dll File Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-repair-your-steelseries-arctis-cued-headphones-microphone-step-by-step-solutions/"><u>Troubleshoot & Repair Your SteelSeries Arctis Cued Headphones Microphone – Step by Step Solutions</u></a></li>
</ul></div>

