---
title: "Resolved: How to Fix the Notorious Windows 10 Blue Screen Dilemma"
date: 2024-12-14T20:38:21.839Z
updated: 2024-12-16T18:09:28.135Z
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XS1nQCe95LU?si=A2dhdFkSAI61_nKA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**3)** Open the program you’ve just downloaded. Then click**Update Now**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a002e5ecc61b.jpg)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UoBCgLTmznE?si=MXXiGsd2qpd_DrzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

**4)** Follow the instructions to download and install the latest update.**5)** When the process finishes, your operating system will be updated to the latest version, and the update failed issue will be fixed.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Jfq2Wx1Bcs?si=YQrYpTy0g4aV5QaO" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Method 2: Reset the Windows Update components

You may fail to install the 1607 update because the**Windows Update components**on your computer are corrupted. These components include the services and temporary files required by or related to Windows Update. You can try resetting these components and see if this can fix your problem. To reset the Windows Update components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/gSKkJrJ57EA?si=WDOmInPE9EgQa_tB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/HtM7d4dpN1I?si=2vN_xgVGD4eYGORu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-boxes.techidaily.com/updated-digital-therapeutics-and-patient-engagement/"><u>[Updated] Digital Therapeutics and Patient Engagement</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-stand-alone-hold-tight-camera-stability-techniques/"><u>[Updated] Stand Alone, Hold Tight Camera Stability Techniques</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-artisans-guide-to-aesthetic-photographic-adjustments/"><u>2024 Approved The Artisan's Guide to Aesthetic Photographic Adjustments</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202561962-combat-the-disappearing-cursor-problem-on-your-windows-11-touchpad-today/"><u>Combat the Disappearing Cursor Problem on Your Windows 11 Touchpad Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-solution-to-overcome-the-pitch-black-display-problem-in-monster-hunter-game/"><u>Complete Solution To Overcome The Pitch-Black Display Problem In Monster Hunter Game</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-refresh-options-for-microsofts-latest-operating-system-windows-11/"><u>Effortless Refresh Options for Microsoft's Latest Operating System, Windows 11</u></a></li>
<li><a href="https://win11.techidaily.com/elevate-your-package-control-a-windows-11-and-wingetuser-experience/"><u>Elevate Your Package Control: A Windows 11 & WingetUser Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/enable-digital-writing-tools-fix-pen-not-detected-or-touch-unresponsive-screen-problems/"><u>Enable Digital Writing Tools: Fix 'Pen Not Detected' Or 'Touch Unresponsive' Screen Problems</u></a></li>
<li><a href="https://android-transfer.techidaily.com/how-to-transfer-photos-from-motorola-edge-40-pro-to-new-android-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How to Transfer Photos from Motorola Edge 40 Pro to New Android? | Dr.fone</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-6-ways-to-transfer-contacts-from-vivo-y17s-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 6 Ways To Transfer Contacts From Vivo Y17s to iPhone | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-delays-in-launching-windows-7-top-tips-and-tricks/"><u>Resolving Delays in Launching Windows 7 - Top Tips & Tricks</u></a></li>
<li><a href="https://techidaily.com/simple-ways-to-get-lost-files-back-from-samsung-galaxy-f34-5g-by-fonelab-android-recover-data/"><u>Simple ways to get lost files back from Samsung Galaxy F34 5G</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/unlocking-the-potential-of-your-ppt-with-professional-recording/"><u>Unlocking the Potential of Your PPT with Professional Recording</u></a></li>
<li><a href="https://solve-lab.techidaily.com/wie-erneuern-sie-daten-auf-einer-alten-festplatte-ihres-toshiba-laptops-wieder/"><u>Wie Erneuern Sie Daten Auf Einer Alten Festplatte Ihres Toshiba Laptops Wieder?</u></a></li>
<li><a href="https://common-error.techidaily.com/wolfenstein-ii-stealth-assassin-addressing-crash-dump-writing-challenges/"><u>Wolfenstein II: Stealth Assassin - Addressing Crash Dump Writing Challenges</u></a></li>
</ul></div>

