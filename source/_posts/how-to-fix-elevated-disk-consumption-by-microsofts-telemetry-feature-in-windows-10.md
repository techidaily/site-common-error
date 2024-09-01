---
title: How to Fix Elevated Disk Consumption by Microsoft's Telemetry Feature in Windows 10
date: 2024-08-31T17:42:14.269Z
updated: 2024-09-01T17:42:14.269Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Elevated Disk Consumption by Microsoft's Telemetry Feature in Windows 10
excerpt: This Article Describes How to Fix Elevated Disk Consumption by Microsoft's Telemetry Feature in Windows 10
thumbnail: https://thmb.techidaily.com/3376b29faa2d3197bcfcb2a2edc1961849ab5554465668491f874fa276d36a0e.jpg
---

## Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It

<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_59ffe5a36e9e9.png)

 Windows has rolled out a new Anniversary Update,**version 1607** , to its Windows 10 operating system, offering many new features. However, many Windows 10 users are getting trouble when they install this update — their operating system tries repeatedly to upgrade to this version but keeps failing. When they check the update history in Windows Update, they see one or more items that say “ _**Feature update to Windows 10, version 1607 Failed to install on …**_  “.

You will be very annoyed when you get this update error. Your Windows Update keeps installing the 1607 feature update but can’t stop failing, which is quite troublesome. Also, this prevents you from enjoying the new version of Windows 10 and its new features. What’s more, it can occupy a lot of system resources and slow down your computer. But don’t worry. This issue can be fixed. You still can install the version 1607 update on your computer. The following are the methods that have helped many Windows 10 users to resolves this problem. You can give them a try: Method 1:[**Install the update with Windows 10 Update Assistant**](https://tools.techidaily.com/drivereasy/download/)Method 2:[**Reset the Windows Update components**](https://tools.techidaily.com/drivereasy/download/)Method 3:[**Run the DISM utility**](https://tools.techidaily.com/drivereasy/download/)Method 4:[**Temporarily disable your antivirus software**](https://tools.techidaily.com/drivereasy/download/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068411/7443" target="_top" id="2068411"><img src="//a.impactradius-go.com/display-ad/7443-2068411" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 1: Install the update with Windows 10 Update Assistant

Microsoft has released an update installation tool named**Windows 10 Update Assistant**for Windows 10 users. It can help you update your Windows 10 to the latest version. If you get stuck in installing the 1607 update, you can try updating your system with this tool instead of Windows Update. To download and run Windows 10 Update Assistant:**1)**Go to the[**Microsoft software download website**](https://www.microsoft.com/en-us/software-download/windows10).**2)** Click the**Update Now**button. This will download Windows 10 Update Assistant.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3DSysTools%2BGmail%2BBackup"><img src="https://www.systoolsgroup.com/box/gmail-backup.png" border="0"></a>
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1657397/16446" target="_top" id="1657397"><img src="//a.impactradius-go.com/display-ad/16446-1657397" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657397/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
## Method 3: Run the DISM utility

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620778&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
Your system may fail to install the 1607 update because something corrupts your Windows image, which is necessary for the important system features like Windows Update. You can try running the**DISM**(Deployment Image Servicing and Management) utility to repair your Windows image. To run DISM:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type “_**DISM.exe /Online /Cleanup-image /Restorehealth**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0150723fc23.png)

**3)** Wait for the utility to complete repairing your Windows image. Then restart your computer and check to see if this fixes your update problem.

<!-- affiliate ads begin -->
<a href="https://propmoneyinc.pxf.io/c/5597632/1803116/14559" target="_top" id="1803116"><img src="//a.impactradius-go.com/display-ad/14559-1803116" border="0" alt="" width="859" height="859"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1803116/14559" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-advanced-tactics-preserving-the-integrity-of-whatsapp-talks/"><u>[Updated] In 2024, Advanced Tactics  Preserving the Integrity of WhatsApp Talks</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-in-the-front-row-ranked-no-8-image-synthesis-app/"><u>2024 Approved  In the Front Row  Ranked No. 8 Image Synthesis App</u></a></li>
<li><a href="https://fox-direct.techidaily.com/2024-approved-luminous-techniques-for-web-based-cinema/"><u>2024 Approved  Luminous Techniques for Web-Based Cinema</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-essential-guide-to-photo-backdrop-removal-in-picsart/"><u>2024 Approved  The Essential Guide to Photo Backdrop Removal in Picsart</u></a></li>
<li><a href="https://android-location.techidaily.com/9-best-free-android-monitoring-apps-to-monitor-phone-remotely-for-your-xiaomi-redmi-note-12-pro-4g-drfone-by-drfone-virtual/"><u>9 Best Free Android Monitoring Apps to Monitor Phone Remotely For your Xiaomi Redmi Note 12 Pro 4G | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/acpi-device-fix-handle-error-id-venint33a0/"><u>Acpi Device Fix: Handle Error ID VEN_INT33A0</u></a></li>
<li><a href="https://common-error.techidaily.com/backspace-failure-diagnosing-the-problems-and-correcting-them-effectively/"><u>Backspace Failure: Diagnosing the Problems and Correcting Them Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-blizzards-wow-lags-tips-for-a-smooth-gaming-experience/"><u>Beat Blizzard's WoW Lags: Tips for a Smooth Gaming Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206476731-computer-freezes-at-startup-heres-what-you-need-to-know/"><u>Computer Freezes at Startup? Here's What You Need to Know</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/deciding-on-phone-upgrades-how-often-is-too-often/"><u>Deciding on Phone Upgrades: How Often Is Too Often?</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209281098-desktop-icon-vanishing-act-on-windows-11-heres-how-to-get-them-back/"><u>Desktop Icon Vanishing Act on Windows 11? Here's How to Get Them Back!</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/efficient-ways-to-audit-your-cellular-data-usage/"><u>Efficient Ways to Audit Your Cellular Data Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/eradicating-input-lag-for-a-smoother-experience-with-windows-11-computers/"><u>Eradicating Input Lag for a Smoother Experience with Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-solutions-for-fixing-werfaultexe-errors-in-windows/"><u>Essential Solutions for Fixing werfault.exe Errors in Windows</u></a></li>
<li><a href="https://buynow-info.techidaily.com/evaluating-googles-advanced-wifi-offering-a-user-friendly-and-efficient-mesh-network-for-broadband-environments/"><u>Evaluating Google's Advanced Wifi Offering: A User-Friendly and Efficient Mesh Network for Broadband Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-plugged-in-but-not-charging-issue-on-windows-710-pcs/"><u>Fix 'Plugged In but Not Charging' Issue on Windows 7/10 PCs</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-this-platform-is-not-supported-while-installing-intel-serial-io-driver/"><u>Fix This Platform Is Not Supported. While Installing Intel Serial IO Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-pc-writes-on-kernel32/"><u>Fix Your PC' Writes on Kernel32</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/forgot-locked-iphone-se-2020-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>Forgot Locked iPhone SE (2020) Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-miracast-streaming-despite-errors-a-step-by-step-guide/"><u>How to Enable Miracast Streaming Despite Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-wireless-mouse-that-stops-working-sporadically-on-computers-running-windows-1110/"><u>How to Fix a Wireless Mouse That Stops Working Sporadically on Computers Running Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-d3derrnotavailable-troubleshooting-steps-inside/"><u>How to Overcome 'D3DERR_NOTAVAILABLE': Troubleshooting Steps Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-error-0x8024401c-during-updates-on-windows-11/"><u>How To Overcome The Error 0X8024401C During Updates On Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-a-non-responsive-spacebar-on-microsofts-latest-os-windows-11/"><u>How to Repair a Non-Responsive Spacebar on Microsoft's Latest OS, Windows 11</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-p55-phone-with-broken-screen-by-drfone-android/"><u>How to Unlock Itel P55 Phone with Broken Screen</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/in-2024-entry-into-the-world-of-google-meet-webinars/"><u>In 2024, Entry Into the World of Google Meet Webinars</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/24-instant-inspiration-the-easy-guide-to-building-custom-youtube-music-mixes-webapp/"><u>In 2024, Instant Inspiration  The Easy Guide to Building Custom YouTube Music Mixes (Web/App)</u></a></li>
<li><a href="https://fox-helps.techidaily.com/laying-the-groundwork-for-av1-understanding-for-2024/"><u>Laying The Groundwork for AV1 Understanding for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-technique-efficiently-restarting-your-malfunctioning-keyboard/"><u>Master the Technique: Efficiently Restarting Your Malfunctioning Keyboard</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/mastering-photo-8-restoration-with-stellar-repair-on-windows-systems/"><u>Mastering Photo 8 Restoration with Stellar Repair on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-light-adjustment-feature-on-windows-surprise/"><u>Missing Light Adjustment Feature on Windows Surprise</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/navigating-technology-choices-expert-advice-from-toms-tech-hub/"><u>Navigating Technology Choices - Expert Advice From Tom's Tech Hub</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-select-proper-boot-device-glitch-on-your-pc-effective-fixes-unveiled/"><u>Overcome 'Select Proper Boot Device' Glitch on Your PC: Effective Fixes Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solution-for-unseen-bluetooth-option-in-computer-device-manager/"><u>Quick Solution for Unseen Bluetooth Option in Computer Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-guide-to-keep-your-computer-awake-and-alert/"><u>Quick Troubleshooting Guide to Keep Your Computer Awake and Alert</u></a></li>
<li><a href="https://techidaily.com/samsung-data-retrieval-tool-restore-lost-data-from-samsung-galaxy-a15-5g-by-fonelab-android-recover-data/"><u>Samsung Data Retrieval tool – restore lost data from Samsung Galaxy A15 5G</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/screencasting-simplified-compreehd-step-by-step-guide/"><u>Screencasting Simplified  Compreehd, Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/shift-key-malfunction-diagnosis-and-effective-remedies-fixed/"><u>Shift Key Malfunction: Diagnosis and Effective Remedies [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-lenovo-keyboard-malfunction-issues-and-resolutions/"><u>Solved! Lenovo Keyboard Malfunction Issues and Resolutions</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-airpods-connection-issues-on-windows-1011-top-tips-for-2-cufflinks/"><u>Solving the AirPods Connection Issues on Windows 10/11: Top Tips for 2 Cufflinks</u></a></li>
<li><a href="https://common-error.techidaily.com/steelseries-arctis-solved-comprehensive-guide-to-repairing-a-dead-mic/"><u>SteelSeries Arctis ([SOLVED]): Comprehensive Guide to Repairing a Dead Mic</u></a></li>
<li><a href="https://common-error.techidaily.com/touchpad-lag-or-no-response-heres-how-you-can-resolve-it/"><u>Touchpad Lag or No Response? Here's How You Can Resolve It</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-dealing-with-semaphore-timeout-expiration-error-code-0x80070079/"><u>Troubleshooting Guide: Dealing with Semaphore Timeout Expiration (Error Code 0X80070079)</u></a></li>
<li><a href="https://common-error.techidaily.com/user-friendly-steps-to-fix-the-notorious-http-503-service-interruption-issue/"><u>User-Friendly Steps to Fix the Notorious HTTP 503 Service Interruption Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209305785-windows-10-blurry-text-heres-how-to-fix-it/"><u>Windows 10 Blurry Text? Here's How to Fix It</u></a></li>
</ul></div>
