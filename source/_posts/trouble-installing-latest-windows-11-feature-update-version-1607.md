---
title: Trouble Installing Latest Windows 11 Feature Update (Version 1607)
date: 2024-10-11T02:25:34.405Z
updated: 2024-10-13T02:41:13.161Z
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100541/7443" target="_top" id="2100541">
  <img src="//a.impactradius-go.com/display-ad/7443-2100541" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100541/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136621/26400" target="_top" id="2136621">
  <img src="//a.impactradius-go.com/display-ad/26400-2136621" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136621/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135363/19272" target="_top" id="2135363">
  <img src="//a.impactradius-go.com/display-ad/19272-2135363" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135363/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/new-in-2024-the-ultimate-guide-to-restoring-windows-photo-viewer-on-win-11/"><u>[New] In 2024, The Ultimate Guide to Restoring Windows Photo Viewer on Win 11</u></a></li>
<li><a href="https://extra-tips.techidaily.com/updated-capturing-panoramic-shots-iphone-guide/"><u>[Updated] Capturing Panoramic Shots IPhone Guide</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/updated-comparing-youtube-and-dailymotion-notable-contrasts/"><u>[Updated] Comparing YouTube and Dailymotion Notable Contrasts</u></a></li>
<li><a href="https://buynow-reviews.techidaily.com/best-online-coding-courses/"><u>Best Online Coding Courses</u></a></li>
<li><a href="https://common-error.techidaily.com/dealing-with-lagging-chrome-a-guide-to-refresh-and-continue-browsing-seamlessly/"><u>Dealing with Lagging Chrome: A Guide to Refresh & Continue Browsing Seamlessly</u></a></li>
<li><a href="https://win-dash.techidaily.com/effortless-way-to-get-the-newest-graphics-card-software-for-your-amd-rx-580-driver-downloads-and-updates/"><u>Effortless Way to Get the Newest Graphics Card Software for Your AMD RX 580: Driver Downloads and Updates</u></a></li>
<li><a href="https://driver-download.techidaily.com/fast-download-usb-to-rs232-interface-driver/"><u>Fast Download: USB to RS232 Interface Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/graphics-driver-compatibility-essential-fixes-for-enabling-miracast-functionality/"><u>Graphics Driver Compatibility: Essential Fixes for Enabling Miracast Functionality</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-transform-your-digital-works-into-blockchain-treasures-with-these-tools/"><u>In 2024, Transform Your Digital Works Into Blockchain Treasures with These Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/ps4-connection-woes-follow-this-step-by-step-fixers-guide-for-nat-types/"><u>PS4 Connection Woes? Follow This Step by Step Fixer's Guide for NAT Types!</u></a></li>
<li><a href="https://common-error.techidaily.com/reinstall-lost-media-device-drivers-step-by-step-guide-to-fix-common-issues/"><u>Reinstall Lost Media Device Drivers - Step-by-Step Guide to Fix Common Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-gain-admin-privileges-needed-for-successful-operations-on-windows-11-10-and-7/"><u>Solution: Gain Admin Privileges Needed for Successful Operations on Windows 11, 10 & 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-corsair-keyboards-that-wont-illuminate-properly/"><u>Troubleshooting Tips for Corsair Keyboards That Won't Illuminate Properly</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/ultimate-guide-to-get-the-meltan-box-pokemon-go-for-poco-c50-drfone-by-drfone-virtual-android/"><u>Ultimate guide to get the meltan box pokemon go For Poco C50 | Dr.fone</u></a></li>
<li><a href="https://games-able.techidaily.com/why-xbox-series-s-ignores-traditional-game-formats/"><u>Why Xbox Series S Ignores Traditional Game Formats</u></a></li>
</ul></div>

