---
title: Trouble with Updating to Windows 11 v1607? Here's What You Need to Know
date: 2024-12-13T22:18:55.925Z
updated: 2024-12-16T17:59:36.301Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Trouble with Updating to Windows 11 v1607? Here's What You Need to Know
excerpt: This Article Describes Trouble with Updating to Windows 11 v1607? Here's What You Need to Know
thumbnail: https://thmb.techidaily.com/2ca46c2a129dc1360b713c04a30f75e3e36c2cb0f971400d44a0a7430d69515d.jpg
---

## Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/d-COuhPT5mk?si=wLZU6jkkAdJuAn6h" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/grbt-5VvbuI?si=qnoirlmljslpqcQj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

**2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)**Still in Command Prompt, type these commands and press Enter after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Run Windows Update and check to see if your computer can install the 1607 update.

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1KKovVi9epE?si=EF7KA7b4KsEpWA-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GBWcw6rXIdg?si=Tlue44bW-bPA4tH9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 4: Temporarily disable your antivirus software

Sometimes your system can’t install new updates due to the interference from your**antivirus software**. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.**IMPORTANT:**Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-low-cost-high-performance-great-smartphones-for-gamers/"><u>[New] Low-Cost, High Performance Great Smartphones for Gamers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-2024-approved-action-camera-faceoff-whos-winning-in-gopro-vs-yi-4k-battle/"><u>[Updated] 2024 Approved Action Camera Faceoff Who's Winning in GoPro Vs. Yi 4K Battle?</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/updated-in-2024-the-hot-list-viral-video-threads-for-the-week/"><u>[Updated] In 2024, The Hot List Viral Video Threads for the Week</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-in-2024-ultimate-tutorial-for-3d-lut-creators/"><u>[Updated] In 2024, Ultimate Tutorial for 3D LUT Creators</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-make-your-own-meme-now/"><u>[Updated] Make Your Own Meme Now</u></a></li>
<li><a href="https://win-brilliant.techidaily.com/1728495484648-windows-1011/"><u>学习如何轻松地在Windows 10/11中备份和复制三种方法的用户设置文件</u></a></li>
<li><a href="https://common-error.techidaily.com/curbing-msmpengexe-cpu-hog-effective-techniques-to-enhance-system-efficiency-in-windows-11-solved/"><u>Curbing MsMpEng.exe CPU Hog: Effective Techniques to Enhance System Efficiency in Windows 11 [SOLVED]</u></a></li>
<li><a href="https://technical-tips.techidaily.com/discover-the-secrets-of-enjoying-netflix-at-zero-price-heres-how/"><u>Discover the Secrets of Enjoying Netflix at Zero Price - Here's How!</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/epic-encounters-a-selection-of-supreme-7-total-war-conflicts-for-2024/"><u>Epic Encounters A Selection of Supreme 7 Total War Conflicts for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-windows-updates-solving-the-0x8024401c-error-on-windows-1110/"><u>Error-Free Windows Updates: Solving the 0X8024401c Error on Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-non-responsive-volume-buttons-in-windows-10/"><u>Expert Tips for Fixing Non-Responsive Volume Buttons in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-corrupted-windows-store-caches-effective-strategies-and-solutions/"><u>Fix Corrupted Windows Store Caches: Effective Strategies and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204423354-fix-lol-pvpnet-patcher-kernel-has-stopped-working-easily/"><u>Fix LOL “PvP.net Patcher Kernel Has Stopped Working” Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-wwe-2k-battlegrounds-and-enable-dx11-feature-level-100-without-issues/"><u>How to Fix WWE 2K Battlegrounds and Enable DX11, Feature Level 10.0 without Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-incompatible-timing-settings-on-your-computers-display/"><u>How to Resolve Incompatible Timing Settings on Your Computer's Display</u></a></li>
<li><a href="https://common-error.techidaily.com/mastery-in-minutes-repair-techniques-for-remote-server-not-reachable-error/"><u>Mastery in Minutes: Repair Techniques for 'Remote Server Not Reachable' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-your-system-integrity-solutions-for-repairing-broken-files-in-windows-11/"><u>Restore Your System Integrity: Solutions for Repairing Broken Files in Windows 11</u></a></li>
<li><a href="https://win-amazing.techidaily.com/unlocking-the-free-qualcomm-atheros-ar938x-driver-download-painless-process/"><u>Unlocking the Free Qualcomm Atheros AR938X Driver Download - Painless Process!</u></a></li>
<li><a href="https://some-tips.techidaily.com/1726223490741-pgm-movavi/"><u>무료 온라인 PGM 교체를 위한 Movavi의 도우미 방법</u></a></li>
</ul></div>

