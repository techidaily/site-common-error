---
title: Solve Your Windows 7 PC's Faulty USB Input Devices Problem
date: 2024-10-19T20:22:53.132Z
updated: 2024-10-24T18:41:20.561Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solve Your Windows 7 PC's Faulty USB Input Devices Problem
excerpt: This Article Describes Solve Your Windows 7 PC's Faulty USB Input Devices Problem
thumbnail: https://thmb.techidaily.com/197c2ed369e4a9919f13d946f77f5157856e3dbfa0838cef669c3e3be16ac8df.jpg
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
<a href="https://unicoeye.pxf.io/c/5597632/2134497/18498" target="_top" id="2134497">
  <img src="//a.impactradius-go.com/display-ad/18498-2134497" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134497/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
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

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137216/26400" target="_top" id="2137216">
  <img src="//a.impactradius-go.com/display-ad/26400-2137216" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137216/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 3: Run the DISM utility

Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139115/17108" target="_top" id="2139115">
  <img src="//a.impactradius-go.com/display-ad/17108-2139115" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139115/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://article-tips.techidaily.com/new-2024-approved-gratitude-gift-selecting-high-quality-otus-freepaid/"><u>[New] 2024 Approved Gratitude Gift Selecting High-Quality OTUs (Free/Paid)</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-real-time-view-counter-analyzers/"><u>[New] Real-Time View Counter Analyzers</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-windows-10-wont-boot-after-update/"><u>[Solved] Windows 10 Won't Boot After Update</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-exploring-the-dynamics-of-fb-video-speeds/"><u>[Updated] Exploring the Dynamics of FB Video Speeds</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/2024-approved-bringing-rhythm-to-instagrams-visual-narratives/"><u>2024 Approved Bringing Rhythm to Instagram's Visual Narratives</u></a></li>
<li><a href="https://common-error.techidaily.com/call-of-duty-ww2-bug-code-easy-troubleshooting-steps-to-correct-errors/"><u>Call of Duty WW2 Bug Code 지표: Easy Troubleshooting Steps to Correct Errors</u></a></li>
<li><a href="https://buynow-help.techidaily.com/embracing-e-readers-with-kindle-technology/"><u>Embracing E-Readers with Kindle Technology</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-correcting-system-critical-process-failed-error-on-your-pc-0xc00000e9-explained/"><u>Expert Advice: Correcting System Critical Process Failed Error on Your PC (0XC00000E9 Explained)</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/mirror-of-society-top-100-inspiring-instagramcaptions/"><u>Mirror of Society Top 100 Inspiring #InstagramCaptions</u></a></li>
<li><a href="https://tech-hub.techidaily.com/openai-rebuts-claims-of-intellectual-deterioration-in-chatgpt/"><u>OpenAI Rebuts Claims of Intellectual Deterioration in ChatGPT</u></a></li>
<li><a href="https://common-error.techidaily.com/printer-driver-was-not-installed-access-is-denied/"><u>Printer Driver Was Not Installed: Access Is Denied</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-bluetooth-devices-that-appear-paired-but-remain-unconnected-in-windows-10/"><u>Troubleshooting Bluetooth Devices That Appear Paired But Remain Unconnected in Windows 10</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-the-latest-in-pc-building-toms-component-chronicles/"><u>Unveiling the Latest in PC Building - Tom's Component Chronicles</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-10-setup-fails-overcome-error-code-80240020-for-successful-installation/"><u>Windows 10 Setup Fails: Overcome Error Code 80240020 for Successful Installation</u></a></li>
<li><a href="https://solve-helper.techidaily.com/1726225515344-oggwmv-movavi/"><u>コンパクトな動画形式に自由自在: OGG,WMV対応のオンライン変換サービス Movavi</u></a></li>
</ul></div>

