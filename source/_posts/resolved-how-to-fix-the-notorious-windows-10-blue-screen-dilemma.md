---
title: "Resolved: How to Fix the Notorious Windows 10 Blue Screen Dilemma"
date: 2024-12-21T17:29:41.554Z
updated: 2024-12-25T20:34:36.701Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002c98764a3.jpg)

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XA_wP7rS9ww?si=LarMG3sEHAhSoL6q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/LI9nKlbhnw8?si=uUXFVbuEqXtFHHv0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/AQn0MYjIfyI?si=rIdjT-qMRpjpJXXa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Nyp7-xVwqHA?si=XCuZbpKLFIdrGQQh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

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
<li><a href="https://fox-glue.techidaily.com/new-capturing-impactful-voice-top-tips-for-podcasting-interviews-on-idevices-for-2024/"><u>[New] Capturing Impactful Voice Top Tips for Podcasting Interviews on iDevices for 2024</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ommanding-the-screen-top-10-women-gamers-yt/"><u>[New] Commanding the Screen Top 10 Women Gamers YT</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-in-2024-cutting-edge-gear-for-aspiring-youtube-stars/"><u>[Updated] In 2024, Cutting-Edge Gear for Aspiring YouTube Stars</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-year-in-review-top-5-camera-tips-filmmakers-for-2024/"><u>[Updated] Year in Review Top 5 Camera Tips Filmmakers for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/2024-approved-mastering-the-art-of-finding-pixel-tone-sites/"><u>2024 Approved Mastering the Art of Finding Pixel Tone Sites</u></a></li>
<li><a href="https://common-error.techidaily.com/boost-typing-responsiveness-practical-tips-for-addressing-delayed-keyboard-feedback/"><u>Boost Typing Responsiveness: Practical Tips for Addressing Delayed Keyboard Feedback</u></a></li>
<li><a href="https://article-helps.techidaily.com/building-an-empire-in-smm-a-step-by-step-guide-for-success-for-2024/"><u>Building an Empire in SMM A Step-by-Step Guide for Success for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-addressing-and-correcting-ethernet-issues-in-windows-operating-systems-version-10-and-7/"><u>Expert Advice: Addressing & Correcting Ethernet Issues in Windows Operating Systems (Version 10 & 7)</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-unresponsive-task-manager-running-again-quick-solutions/"><u>Get Your Unresponsive Task Manager Running Again: Quick Solutions</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-fix-locked-apple-id-on-iphone-se-2020-by-drfone-ios/"><u>How to Fix Locked Apple ID on iPhone SE (2020)</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-3-effective-methods-to-fake-gps-location-on-android-for-your-infinix-smart-8-plus-drfone-by-drfone-virtual/"><u>In 2024, 3 Effective Methods to Fake GPS location on Android For your Infinix Smart 8 Plus | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-vcruntime140-dll-on-windows-11-quick-resolution-steps-for-programs-to-run-perfectly/"><u>Missing VCRUNTIME140 DLL on Windows 11: Quick Resolution Steps for Programs to Run Perfectly</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-the-fn-key-on-your-lenovo-laptop-stops-working/"><u>Quick Fixes for When the Fn Key on Your Lenovo Laptop Stops Working</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-the-stuck-or-non-functioning-spacebar-problem-in-windows-10-systems/"><u>Solve the Stuck or Non-Functioning Spacebar Problem in Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-ps4-connectivity-effective-nat-type-solutions/"><u>Troubleshooting PS4 Connectivity: Effective NAT Type Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-software-conflicts-resolving-missing-class-problems/"><u>Windows 11 Software Conflicts: Resolving Missing Class Problems</u></a></li>
<li><a href="https://discover-helper.techidaily.com/winx-mediatrans-iphoneipadmv/"><u>WinX MediaTrans™: 最適合iPhone、iPad上移動照片及MV管理解決方案</u></a></li>
</ul></div>

