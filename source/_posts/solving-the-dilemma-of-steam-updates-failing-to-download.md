---
title: Solving the Dilemma of Steam Updates Failing to Download
date: 2024-09-25T16:06:38.399Z
updated: 2024-09-26T21:29:32.901Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Solving the Dilemma of Steam Updates Failing to Download
excerpt: This Article Describes Solving the Dilemma of Steam Updates Failing to Download
thumbnail: https://thmb.techidaily.com/270945824bfc208da598210ea9d10172c37fe105e9954ed76f47e6f487357fc6.jpg
---

## Winning the Battle Against Failing Windows Updates - Now Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fddb113ec0.png)

Window Update is an important component of your Windows system. It helps you install updates on your system. Windows Update is designed to keep your Windows up to date and healthy and it usually does. But unfortunately, in many cases, it fails to do so and instead become the source of multiple annoying problems. Many Windows users have reported that they have got this or that kind of issues with their Windows Update. They have been told that Windows Update “failed to install” certain updates or these updates’ “installation failed”. They’ve got an error popping up with a code and an associated message, which stops them from installing updates. Or they couldn’t download or install the updates with no clear message but get stuck in the update process. No matter how these issues look like, it stops you from installing the updates on your Windows. You can’t fix your system security vulnerabilities, fix bugs, and enjoy new system features without those updates. This can be extremely frustrating. But don’t panic. All Windows Update issues can be fixed. You can fix them by trying the methods below. You don’t have to try them all; just work your way down the list until you find the one that really works for you.**Methods that fix your Windows Update issues:**

1. [**Run Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. [**Restart Windows Update related services**](https://tools.techidaily.com/drivereasy/download/)
3. [**Manually download and install updates**](https://tools.techidaily.com/drivereasy/download/)
4. [**Run DISM and System File Checker**](https://tools.techidaily.com/drivereasy/download/)
5. [**Disable your antivirus**](https://tools.techidaily.com/drivereasy/download/)
6. [**Update your drivers**](https://tools.techidaily.com/drivereasy/download/)
7. [**Restore your Windows**](https://tools.techidaily.com/drivereasy/download/)

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Method 1: Run Windows Update Troubleshooter

Windows Update Troubleshooter is a tool released by Microsoft that can help you troubleshoot issues with your Windows Update. You can run it to check your Windows Update when it fails to work properly. To do so:**1)**Download **[Windows Update Troubleshooter](https://aka.ms/diag%5Fwu)** (the program is from a Microsoft site and it’s verified and safe).**2)** Run the tool you’ve just downloaded and follow the on-screen instructions to complete the troubleshooting process.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c046d056cc.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2118311/7443" target="_top" id="2118311">
  <img src="//a.impactradius-go.com/display-ad/7443-2118311" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2118311/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

##  Method 2: Reset the Windows Update related components

Your Windows Update may fail to update your Windows because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this can fix your problem. To reset these components:**1)**Click the**Start**button in the lower left corner of your screen, then type “_**cmd**_“. In the list of results, right-click**Command Prompt**and select**Run as administrator**.![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a012175c9a76.png) **2)** In Command Prompt, type the following lines of command and press**Enter**on your keyboard after typing each:

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

* _**net stop bits**_
* _**net stop wuauserv**_
* _**net stop appidsvc**_
* _**net stop cryptsvc**_
(These commands will stop the services that Windows Update requires to download and install updates.)**3)** Type these lines of command and press**Enter** after typing each in Command Prompt:
* _**Ren %systemroot%\\SoftwareDistribution SoftwareDistribution.old**_
* _**Ren %systemroot%\\system32\\catroot2 catroot2.old**_
(This will rename the_SoftwareDistribution_and_catroot2_folder, which are used by Windows Update to store data and temporary files. Your system will detect that these folders are missing, and then it’ll create new ones. The purpose of this is to make the system use the new_SoftwareDistribution_and _catroot2_folders so that Windows Update can avoid issues from the old ones.)**4)** In Command Prompt, type these commands and press**Enter**after each to restart the services you closed just now:
* _**net start bits**_
* _**net start wuauserv**_
* _**net start appidsvc**_
* _**net start cryptsvc**_
**5)**Check your Windows Update to see if it works fine.

## Method 3: Manually download and install updates

If Windows Update can’t help you download certain system updates, you can try doing so on your own. Microsoft has put all its system updates online, and you can download these updates and install them on your computer without the help of Windows Update. To manually download and install updates:**1)**Click the**Start**button in the lower left corner of your screen. Then type “_**information**_“. In the list of results, click**System Information**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c0faa09e19.png)

**2)**In the System Information window, check**System Type**. Its value is usually **x64-based** or **x86-based**(or sometimes**ARM64-based**).

 This is an important piece of information and you should note it down. It will be useful when you are looking for the updates that match your Windows later.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7c104b5d2ee.jpg)

**3)** On Windows Update, note down the system updates that failed to install. (You may need to get the information from the update history.)

 Note down the codes of these updates that start with “**KB** “.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fafbba7758.png)

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb0182b995.png)

**4)**Go to **[Microsoft Update Catalog](https://www.catalog.update.microsoft.com/home.aspx)** . Then search for the updates you have failed to install.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb3a1da130.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135410/19272" target="_top" id="2135410">
  <img src="//a.impactradius-go.com/display-ad/19272-2135410" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135410/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**5)** In the search results, find the update that matches your**operating system**and**system type**(_x86-,_ _x64- or ARM64-based_). Then click**Download**next to the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb49473bae.jpg)

**6)** Click the link on the new window to download the update.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fb79898ae2.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2047411/19272" target="_top" id="2047411">
  <img src="//a.impactradius-go.com/display-ad/19272-2047411" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2047411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**7)**Open the file you’ve just downloaded and follow the on-screen instructions to install the update.

## Method 4: Run DISM and System File Checker

It’s also possible that your Windows Update can’t work because of the corrupted files on your operating system. Windows has two built-in tools called**SFC (System File Checker)**and**DISM (Deployment Imaging and Servicing Management)**that scan your computer and fix various issues on it. To run these tools:**1)** Click the**Start**button in the lower corner of your screen. Then type “_**cmd**_“. Right-click**Command Prompt**in the list of results and select**Run as administrator**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbd72bc9a4.png)

**2)** In Command Prompt, to run System File Checker, type “_**sfc /scannow**_” and press**Enter**on your keyboard.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbe8bbd499.png)

**3)**To run DISM, type “_**dism /online /cleanup-image /restorehealth**_“. and press**Enter**.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fbeb602fef.png)

**4)**Wait for the process to complete, then restart your computer. After that, check to see if your Windows Update recovers.

## Method 5: Disable your antivirus

Sometimes your system can’t install new updates due to the interference from your antivirus software. You can temporarily disable your antivirus and check if the problem persists. (Consult your antivirus program documentation for instructions on disabling it.) If this resolves the problem, contact the vendor of your antivirus software and ask them for advice, or install a different solution.

**IMPORTANT:** Be extra careful about what sites you visit, what emails you open and what files you download when your antivirus is disabled.

##  Method 6: Update your drivers

You may get issues with your Windows Update if you are using wrong or out-of-date device drivers. You should regularly check your device drivers and keep them up to date so as to prevent your computer from many annoying issues. But you may not have the time or patience to check and update your drivers manually. If you want to have this done easily and automatically, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)** .**Driver Easy**will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing. You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 steps (and you get full support and a 30-day money back guarantee): **1) [Download](https://tools.techidaily.com/drivereasy/download/)** and install Driver Easy.**2)**Run Driver Easy and click the**Scan Now**button. Driver Easy will then scan your computer and detect any problem drivers.![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713a84159a4.png) **3)** Click the **Update** button next to each driver to automatically download and install the correct version of this driver (you can do this with the FREE version). Or click **Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)** – you’ll be prompted to upgrade when you click Update All).![](https://images.drivereasy.com/wp-content/uploads/2018/01/img_5a713ba9d0320.jpg)

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Method 7: Restore your Windows

Perhaps the issues with your Windows come from some changes you’ve made to your system. You can perform a system restore. This will restore your system from a restore point (you need to have one that has been created before your Windows Update issue occurs) undo those changes made. To do so:**1)**Click the **Start**button in the lower corner of your screen. Then type “_**restore**_“. In the list of results, click “**Create a restore point**“. The System Properties dialog will appear.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc666d51a9.png)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**2)** Click**System Restore**. The System Restore wizard will pop up.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc6fa8971e.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2130871/7443" target="_top" id="2130871">
  <img src="//a.impactradius-go.com/display-ad/7443-2130871" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130871/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**3)** Follow the on-screen instructions to choose a system restore point and restore your Windows.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7fc712671f3.png)

**4)** Wait for the restore process to complete and then check to see if your Windows Update gets back to normal.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
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
<li><a href="https://video-capture.techidaily.com/new-videography-made-simple-efficient-recording-and-editing-in-adobe-connect-for-2024/"><u>[New] Videography Made Simple Efficient Recording & Editing in Adobe Connect for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-optimal-room-decorations-for-livestreams/"><u>2024 Approved Optimal Room Decorations for Livestreams</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-the-vcruntime140dll-not-located-problem-in-your-pc-expert-advice/"><u>Bypass the VCRUNTIME140.dll Not Located Problem in Your PC - Expert Advice</u></a></li>
<li><a href="https://howto.techidaily.com/calls-on-lava-agni-2-5g-go-straight-to-voicemail-12-fixes-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Calls on Lava Agni 2 5G Go Straight to Voicemail? 12 Fixes | Dr.fone</u></a></li>
<li><a href="https://driver-download.techidaily.com/complete-guide-installing-the-newest-hp-laserjet-pro-mfp-m127fn-driver-for-smooth-printing/"><u>Complete Guide: Installing the Newest HP LaserJet Pro MFP M127FN Driver for Smooth Printing</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-crackling-speakers-on-your-pc-solutions-for-windows-10-and-11/"><u>Fixing Crackling Speakers on Your PC - Solutions for Windows 10 and 11</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/generate-amazing-flash-flipbooks-for-zero-cost-a-guide-to-using-text-to-flipbook-converter-tools/"><u>Generate Amazing Flash Flipbooks for Zero Cost: A Guide to Using Text-to-FlipBook Converter Tools!</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On ZTE Nubia Flip 5G? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/how-to-fix-starting-issues-with-fall-guys-comprehensive-solutions/"><u>How to Fix Starting Issues with Fall Guys – Comprehensive Solutions</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-inside-the-world-of-adobe-cloud-storing-strategies-and-alternative-spaces-reviewed/"><u>In 2024, Inside The World of Adobe Cloud Storing Strategies and Alternative Spaces Reviewed</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-step-by-step-mastery-how-to-design-your-vr-alter-egos-efficiently/"><u>In 2024, Step-by-Step Mastery How to Design Your VR Alter Egos Efficiently</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-why-steam-game-servers-might-be-inaccessible/"><u>Resolving Issues: Why Steam Game Servers Might Be Inaccessible</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-bluetooth-missing-dilemma-on-your-windows-10-device-today/"><u>Solving the 'Bluetooth Missing' Dilemma on Your Windows 10 Device Today</u></a></li>
<li><a href="https://common-error.techidaily.com/system-restore-error-0x80070091-on-windows-10-solved/"><u>System Restore Error 0X80070091 on Windows 10 [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-a-non-responsive-mouse-on-your-pc/"><u>Ultimate Guide: Resolving a Non-Responsive Mouse on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-resolving-freezing-glitches-on-windows-11-during-boot-sequence/"><u>Understanding and Resolving Freezing Glitches on Windows 11 During Boot Sequence</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-keyboard-responsiveness-issue-how-to-fix-it/"><u>Windows 11 Keyboard Responsiveness Issue - How to Fix It</u></a></li>
</ul></div>
