---
title: Trouble Installing Latest Windows 11 Feature Update (Version 1607)
date: 2024-09-14T16:06:31.286Z
updated: 2024-09-15T16:03:19.930Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Trouble Installing Latest Windows 11 Feature Update (Version 1607)
excerpt: This Article Describes Trouble Installing Latest Windows 11 Feature Update (Version 1607)
thumbnail: https://thmb.techidaily.com/213b932fcd2c7374497ebb4064c054acfe0cd4d0bb51ae2c7e5af1c110e1b3ef.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

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

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2130530/26400" target="_top" id="2130530">
  <img src="//a.impactradius-go.com/display-ad/26400-2130530" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2130530/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-recordings.techidaily.com/updated-untangling-insta-vids-selfies-validity-questioned-for-2024/"><u>[Updated] Untangling Insta Vids Selfies' Validity Questioned for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/digital-dialogue-preservation-guide/"><u>Digital Dialogue Preservation Guide</u></a></li>
<li><a href="https://win-dash.techidaily.com/download-hp-universal-printer-drivers-for-windows-systems/"><u>Download HP Universal Printer Drivers for Windows Systems</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/effortless-screen-recording-on-modern-pcs-for-2024/"><u>Effortless Screen Recording on Modern PCs for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-tips-to-rectify-typing-issues-on-your-pc-for-windows-11-7-and-8/"><u>Essential Tips to Rectify Typing Issues on Your PC - For Windows 11, 7, and 8</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-tecno-spark-20-proplus-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Tecno Spark 20 Pro+ Phone with Broken Screen</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/24-charting-social-media-trends-with-data-graphics/"><u>In 2024, Charting Social Media Trends with Data Graphics</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-proven-steps-to-convert-webp-to-high-quality-jpeg/"><u>In 2024, Proven Steps to Convert WebP to High-Quality JPEG</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-why-wont-my-pc-exit-windows-10-properly/"><u>Solution Guide: Why Won't My PC Exit Windows 10 Properly?</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-essentials-of-claude-ai-and-its-value-for-enhanced-digital-solutions/"><u>The Essentials of Claude AI and Its Value for Enhanced Digital Solutions</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/king-history-with-youtube-student-edition-top-10/"><u>Unpacking History with YouTube – Student Edition (Top 10)</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-right-click-not-working-top-diagnostic-steps-to-restore-your-mouse/"><u>Windows 11 Right-Click Not Working – Top Diagnostic Steps to Restore Your Mouse</u></a></li>
</ul></div>
