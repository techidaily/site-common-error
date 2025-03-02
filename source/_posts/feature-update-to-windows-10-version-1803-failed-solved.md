---
title: Feature Update to Windows 10 Version 1803 Failed [SOLVED]
date: 2025-02-26T06:33:02.618Z
updated: 2025-03-02T02:37:47.548Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Feature Update to Windows 10 Version 1803 Failed [SOLVED]
excerpt: This Article Describes Feature Update to Windows 10 Version 1803 Failed [SOLVED]
thumbnail: https://thmb.techidaily.com/4dbb96e84abbbc08787367a1af5777cd4560a19b1ed332d7a4f64409037b9669.jpg
---

## Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It

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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-windows-10-basic-guide-to-audio-recording/"><u>[New] 2024 Approved Windows 10 Basic Guide to Audio Recording</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-in-2024-effortless-iphone-screen-recording-techniques-unveiled/"><u>[Updated] In 2024, Effortless iPhone Screen Recording Techniques Unveiled</u></a></li>
<li><a href="https://extra-hints.techidaily.com/apples-m1-pro-versus-the-powerhouse-m1-max-what-to-note-in-2024/"><u>Apple's M1 Pro Versus the Powerhouse M1 Max - What to Note, In 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-restoring-functionality-for-dell-laptop-input-devices/"><u>Diagnosing and Restoring Functionality for Dell Laptop Input Devices</u></a></li>
<li><a href="https://tech-revival.techidaily.com/evaluating-third-party-tools-for-chatgpts-safety/"><u>Evaluating Third-Party Tools for ChatGPT's Safety</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-clearing-up-disk-detection-failures-during-a-windows-10-system-reset/"><u>Expert Advice: Clearing Up Disk Detection Failures During a Windows 10 System Reset</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-iphone-passcode-again-unlock-iphone-14-pro-max-without-passcode-now-drfone-by-drfone-ios/"><u>Forgot iPhone Passcode Again? Unlock iPhone 14 Pro Max Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quickly-correct-the-troublesome-windows-update-issue-error-0x80070652/"><u>How to Quickly Correct the Troublesome Windows Update Issue: Error 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-the-broken-spacebar-functionality-in-windows-10-computers/"><u>How to Repair the Broken Spacebar Functionality in Windows 10 Computers</u></a></li>
<li><a href="https://android-unlock.techidaily.com/mastering-android-device-manager-the-ultimate-guide-to-unlocking-your-sony-xperia-1-v-device-by-drfone-android/"><u>Mastering Android Device Manager The Ultimate Guide to Unlocking Your Sony Xperia 1 V Device</u></a></li>
<li><a href="https://ai-voice.techidaily.com/new-2024-approved-best-5-tiktok-voice-generators-you-should-try/"><u>New 2024 Approved Best 5 TikTok Voice Generators You Should Try</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-gameplay-interruptions-stop-your-pc-from-shutting-off-on-any-windows-version/"><u>Overcoming Gameplay Interruptions: Stop Your PC From Shutting Off on Any Windows Version!</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-no-audio-output-problem-on-your-pc-a-step-by-step-guide/"><u>Solving the 'No Audio Output' Problem on Your PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/unlocking-iphone-6-lock-screen-3-foolproof-methods-that-actually-work-by-drfone-ios/"><u>Unlocking iPhone 6 Lock Screen 3 Foolproof Methods that Actually Work</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/upgrading-from-macos-monterey-to-ventura-is-the-new-version-worth-it/"><u>Upgrading From macOS Monterey to Ventura: Is the New Version Worth It?</u></a></li>
</ul></div>

