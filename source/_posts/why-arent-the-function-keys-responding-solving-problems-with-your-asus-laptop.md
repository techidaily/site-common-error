---
title: Why Aren't the Function Keys Responding? Solving Problems with Your Asus Laptop
date: 2025-02-25T10:52:42.094Z
updated: 2025-03-01T21:25:28.676Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Why Aren't the Function Keys Responding? Solving Problems with Your Asus Laptop
excerpt: This Article Describes Why Aren't the Function Keys Responding? Solving Problems with Your Asus Laptop
thumbnail: https://thmb.techidaily.com/b6c1c170b3fb34192b1990649e9c8685733790cb7484ba703ce124bf47249cb0.jpg
---

## Resolving Problems During Feature Update Rollout for Windows 11, v1607 Edition

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-visualcut-content-checker/"><u>[New] 2024 Approved VisualCut Content Checker</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-direct-pathway-streamlined-capturing-techniques-dell-for-2024/"><u>[Updated] Direct Pathway Streamlined Capturing Techniques (Dell) for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-mastering-digital-conversion-old-photos-to-video/"><u>[Updated] Mastering Digital Conversion Old Photos to Video</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/ed-optimize-your-online-presence-youtube-to-dailymotion-video-migration-for-2024/"><u>[Updated] Optimize Your Online Presence YouTube to Dailymotion Video Migration for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ifunny-meme-journey-downloading-made-easy/"><u>2024 Approved The iFunny Meme Journey Downloading Made Easy</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-issue-detected-monitor-ignores-active-signal-frequency/"><u>Compatibility Issue Detected - Monitor Ignores Active Signal Frequency</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-repair-techniques-restoring-access-to-your-destiny-2-game-servers/"><u>DIY Repair Techniques: Restoring Access to Your Destiny 2 Game Servers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-when-function-keys-fail-to-work-properly/"><u>Effective Solutions for When Function Keys Fail to Work Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-solve-no-signal-detected-monitor-glitches/"><u>Effective Techniques to Solve 'No Signal Detected' Monitor Glitches</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/tial-tags-to-amplify-your-youtube-gaming-channel/"><u>Essential Tags to Amplify Your YouTube Gaming Channel</u></a></li>
<li><a href="https://common-error.techidaily.com/fast-track-troubleshooting-battery-not-recognized-error-solved-effortlessly/"><u>Fast Track Troubleshooting: 'Battery Not Recognized' Error Solved Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/halo-4-in-unreal-engine-4-fixing-the-persistent-crash-bug-of-2024/"><u>Halo 4 in Unreal Engine 4: Fixing the Persistent Crash Bug of 2024</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-complete-fixes-to-solve-iphone-15-pro-randomly-asking-for-apple-id-password-drfone-by-drfone-ios/"><u>In 2024, Complete Fixes To Solve iPhone 15 Pro Randomly Asking for Apple ID Password | Dr.fone</u></a></li>
<li><a href="https://win-answers.techidaily.com/lost-ark-freezes-and-fails-on-windows-how-to-fix-game-stability-issues/"><u>Lost Ark Freezes & Fails on Windows: How to Fix Game Stability Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-to-restore-bluetooth-functionality-on-windows-10/"><u>Quick Guide to Restore Bluetooth Functionality on Windows 10</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/transforming-playtime-how-fitbits-new-ace-lte-shapes-up-as-the-kid-friendly-google-pixel-watch-2-alternative-that-gamifies-fitness/"><u>Transforming Playtime: How Fitbit's New Ace LTE Shapes Up as the Kid-Friendly Google Pixel Watch 2 Alternative That Gamifies Fitness</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixing-non-functional-brightness-settings-on-windows-10/"><u>Troubleshooting: Fixing Non-Functional Brightness Settings on Windows 10</u></a></li>
</ul></div>

