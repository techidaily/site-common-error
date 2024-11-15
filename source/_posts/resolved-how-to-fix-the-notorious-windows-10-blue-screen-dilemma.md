---
title: "Resolved: How to Fix the Notorious Windows 10 Blue Screen Dilemma"
date: 2024-11-08T16:47:42.404Z
updated: 2024-11-15T16:19:06.942Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolved: How to Fix the Notorious Windows 10 Blue Screen Dilemma"
excerpt: "This Article Describes Resolved: How to Fix the Notorious Windows 10 Blue Screen Dilemma"
thumbnail: https://thmb.techidaily.com/ff65255da837891834ddbec118debc41ab0f1d1e57de67c2dd583540d5810764.jpg
---

## Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<a href="https://smilemakers.pxf.io/c/5597632/2123899/26106" target="_top" id="2123899">
  <img src="//a.impactradius-go.com/display-ad/26106-2123899" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://smilemakers.pxf.io/i/5597632/2123899/26106" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087484/7443" target="_top" id="2087484">
  <img src="//a.impactradius-go.com/display-ad/7443-2087484" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087484/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082533/7443" target="_top" id="2082533">
  <img src="//a.impactradius-go.com/display-ad/7443-2082533" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082533/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2148772/18498" target="_top" id="2148772">
  <img src="//a.impactradius-go.com/display-ad/18498-2148772" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148772/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-ultimate-panoramic-camera-scrutiny/"><u>[New] 2024 Approved Ultimate Panoramic Camera Scrutiny</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-the-essentials-of-instagram-filters-for-picture-perfection-for-2024/"><u>[New] The Essentials of Instagram Filters for Picture Perfection for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-affordable-high-performance-game-mice-and-keyboards-for-gamers-for-2024/"><u>[Updated] Affordable High-Performance Game Mice and Keyboards for Gamers for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-deciding-on-a-personal-social-media-platform-tiktok-or-youtubes-shorts-in-2024/"><u>[Updated] Deciding on a Personal Social Media Platform TikTok or YouTubes' Shorts, In 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-mastering-the-game-discover-these-top-12-pc-clickers/"><u>[Updated] In 2024, Mastering the Game Discover These Top 12 PC Clickers</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210351826-comprehensive-troubleshoot-for-windows-11s-persistent-0xc190n0028-upgrade-hurdle-solutions-included/"><u>Comprehensive Troubleshoot for Windows 11'S Persistent 0xC190n0028 Upgrade Hurdle - Solutions Included</u></a></li>
<li><a href="https://blog-min.techidaily.com/convertir-videos-qt-a-wmv-gratuitement-en-ligne-le-guide-detaille-de-movavi/"><u>Convertir Vidéos QT À WMV Gratuitement En Ligne - Le Guide Détaillé De Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-fixes-for-common-windows-problems-addressing-the-entry-point-not-found-error/"><u>DIY Fixes for Common Windows Problems: Addressing the Entry Point Not Found Error</u></a></li>
<li><a href="https://common-error.techidaily.com/exploring-ways-to-fix-windows-10-a-guide-to-using-sfc-and-dism-tools/"><u>Exploring Ways to Fix Windows 10: A Guide to Using SFC & DISM Tools</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-mastering-windows-11-photos-incorporating-filters-and-tunes/"><u>In 2024, Mastering Windows 11 Photos Incorporating Filters & Tunes</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/navigating-song-rights-on-social-media/"><u>Navigating Song Rights on Social Media</u></a></li>
<li><a href="https://discover-guides.techidaily.com/tecnicas-faciles-de-rotacion-en-videos-mp4-a-angulos-rectos-sin-reducir-la-calidad-visual-guia-detallada-para-90-180-y-270-grados/"><u>Técnicas Fáciles De Rotación en Videos MP4 a Ángulos Rectos Sin Reducir La Calidad Visual - Guía Detallada Para 90, 180 Y 270 Grados</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-nonfunctional-dell-webcams-in-windows-a-step-by-step-guide/"><u>Troubleshoot Nonfunctional Dell Webcams in Windows: A Step-by-Step Guide</u></a></li>
</ul></div>

