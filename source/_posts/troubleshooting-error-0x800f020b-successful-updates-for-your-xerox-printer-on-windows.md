---
title: "Troubleshooting Error 0X800F020B: Successful Updates for Your Xerox Printer on Windows"
date: 2024-08-22T19:14:35.097Z
updated: 2024-08-23T19:14:35.097Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Error 0X800F020B: Successful Updates for Your Xerox Printer on Windows"
excerpt: "This Article Describes Troubleshooting Error 0X800F020B: Successful Updates for Your Xerox Printer on Windows"
thumbnail: https://thmb.techidaily.com/e28897e8d930e3677167fd762a9f129952956dbe6cf005a7a223376477485be0.jpg
---

## Troubleshooting Made Easy: Fix Windows Error Code 0xC0000098 in Minutes

 While booting your PC, Windows gives you a BSOD with the**error code** **0xc0000098** . It can be rather frustrating not being able to use your device. You just get stuck at the blue/black screen. But don’t panic. This is a most common Windows error and it’s never hard to fix it at all…

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
## About the error 0xc0000098

> _During the start-up process, the**Boot Configuration Data** (BCD) is very essential to provide required information to load the operating system. If the Boot Configuration Data is missing or corrupted, Windows won’t be able to load operating system and gives you the error**0xc0000098** ._

![](https://images.drivereasy.com/wp-content/uploads/2019/12/0xc0000098-windows-7.jpg)

 _Error Code**0xc0000098**_  o_n Windows 7, Vista_

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4620780&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/07dd4d5a72f5740ef0f035f201951476/728__90banner.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/12/0xc0000098.jpg)

 _Error Code**0xc0000098**_  o_n Windows 10, 8, 8.1_

## Try these fixes

 Below you will get to know all possible fixes to solve your boot error 0xc0000098\. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Rebuild BCD manually](#f1)**
2. **[Try Startup Repair](#f2)**
3. **[Perform a CHKDSK](#f3)**
4. **[Run System File Checker](#f4)**
5. **[Use a Windows Reimage Tool](#fix-reimage)**
6. **[Perform a clean install of Windows](#f5)**

### Fix 1: Rebuild BCD manually

 Since this is a BSOD error, you won’t be able to access your PC normally. To repair your PC, you’ll need to use a Windows recovery drive: an installation USB media or a CD/DVD.

#### Step 1: Prepare installation media

 If you don’t have one, you need to create USB/DVD bootable media yourself. Here is how to do it:

**Note:** You can skip to Step 2 if you already have a (DVD/USB) installation media.

 1) Go to **[Windows 10 download](https://www.microsoft.com/en-us/software-download/windows10)**  page. (Or **[Windows 11](https://www.microsoft.com/software-download/windows11) ,** [Windows 8](https://www.microsoft.com/en-us/software-download/windows8ISO) ,[**Windows 7**](https://www.microsoft.com/en-us/software-download/windows7) )

![](https://images.drivereasy.com/wp-content/uploads/2020/01/download-win-10-1.jpg)

2) Download the installation media and save it on your computer.

3) Double-click the Media Creation Tool to launch the tool.

4) Select the **Create installation media (USB flash drive, DVD, or ISO file) for another PC** option.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=2337838&QTY=1&AFFILIATE=108875&CART=1"><iframe width="640" height="390" src="https://www.youtube.com/embed/rzZwphIv4RM" title="APFill - Ink and Toner Coverage Calculator" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/Create-instalaltion-media-USB-flash-driveor-CD-DVD.jpg)

 5) Select the language, edition, and architecture (64-bit or 32-bit) for the Windows system.

 6) Choose your preferred media. If you choose a USB flash drive, make sure you have a blank USB flash drive with at least 8GB of space.

 7) Follow the on-screen instructions to finish the setup.

#### Step 2: Change the boot order to USB/DVD

 Change the boot order in the BIOS setup. If you use a bootable USB drive, please put**Removable Devices** as the first boot choice. Otherwise, your PC will boot normally from your hard drive.

1) Turn on your device.

2) As soon as your computer starts booting up, press the function key to enter BIOS.

**Note:** The key to access BIOS can vary from**Esc** ,**Delete** to**F2** ,**F8** ,**F12** , depending on your manufacturer and computer model.  
![](https://images.drivereasy.com/wp-content/uploads/2019/12/keyboard-bios-keys.jpg)

 3) Once in BIOS, go to the**Boot** sector and set**Removable Devices** or**CD-Rom Drive** as the first boot device.

 4) Save the changes and exit.

#### Step 3: Boot with an Installation or Repair disc or USB drive

1) Boot your PC from the bootable CD/DVD/USB.

2) In the Windows Setup menu, click**Next** .

3) Select**Repair your computer** in the lower-left corner.

4) Go to**Troubleshoot** \>**Advanced Options** \>**Command Prompt** .

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4726807&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/command-prompt.png)

 5) In Command Prompt, type the following command lines and hit Enter after each command. (There’s a space between**bootrec** and**/** .)

bootrec /scanos

bootrec /fixmbr

bootrec /fixboot

bootrec /rebuildbcd

 Type**Y** and press**Enter** if you’re prompted for permission.

 6) After you have entered the commands above, close the Command Prompt and Reboot your PC.

 The 0xc0000098 error should now be fixed as your PC begins to load. If not, try the fix below.

### Fix 2: Startup Repair

 Startup Repair is a built-in tool to diagnose and repair some common problems on Windows. You may need to run Startup Repair (even 2 or 3 times).

1) Boot your PC from your setup disk (USB/DVD/CD).

2) Select**Repair your computer** and go to**Troubleshoot** \>**Advanced Options** \>**Startup Repair** .

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/2016067/18544" target="_top" id="2016067"><img src="//a.impactradius-go.com/display-ad/18544-2016067" border="0" alt="" width="1020" height="380"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2016067/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2019/12/startup-repair.jpg)

 3) Startup Repair will begin scanning your installation for known issues and will attempt a repair if it finds any.

 4) If it fails, you can run Startup Repair again.

### Fix 3: CHKDSK

 CHKDSK, short for “check disk”, aims to check disk and verify system files for any errors.

 1) Boot your device from your installation media and go to**Command Prompt** .

 2) Type the following command line and press**Enter** .

chkdsk C: /f /r /x

* **C:** is the letter of the drive where Windows is installed, you can change it if you’ve installed it on another drive.
* **r** directs to find out the error.
* **x** symbolizes the volume that requires scanning.

3) CHKDSK will manage to fix the problems it finds.

4) Close Command Prompt and restart your device to check if the Windows system can load up again.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
### Fix 4: System File Checker

 The error 0xc0000098 can also be caused by missing or corrupt system files. System File Checker (SFC) can help you to restore the missing files and repair any problematic ones.

 1) Again go to**Command Prompt** and type the following command and hit**Enter** .

sfc /scannow /offbootdir=c:\ /offwindir=c:\windows

 This command is slightly different from_**sfc /scannow**_ because this is done with a different installation of Windows (**_/offwindir=c:\\windows_** ) on a different drive (_**/offbootdir=c**_ :).

2) Wait for the scan to finish.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
### Fix 5: Use a Windows Fortect Tool

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  Windows repair works by replacing system files automatically. It’s like a clean Windows reinstallation in one hour, without losing any programs, settings, or user data. It can fix the 0xc0000098 error code without a computer restart.

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.

 2) Open Fortect and it might take 3\~5 minutes to analyze your PC. Sit back and grab a cup of coffee. Once complete, you will be able to review the detailed scan report for free.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082526/7443" target="_top" id="2082526"><img src="//a.impactradius-go.com/display-ad/7443-2082526" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082526/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)

 3) Click**Start Repair** to restore any corrupted files. You will need to purchase a license key to do so and don’t have pressure on it, for it has a 60-day money-back guarantee.

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

 4) Enter your license key and the restoration will begin automatically. Reimage handles all.

### Fix 6: Perform a clean install of Windows

 If neither of the fixes above did the trick, then you need to do a clean reinstall of Windows to fix your issues and return your PC to a cleaner state.

 1) Boot from your installation media and select**Next** .

 2) Select**Install now** \> check the**I accept** box >**Next** \> select**Custom: Install Windows only (advanced)** .

 3) If multiple disks are displayed, you’ll only need to delete all partitions from the disk where you want to install Windows.

 3) Highlight each drive/partition in the list and select**Delete** . When the Windows Setup notification appears, select**OK** .

 4) Do this for every drive in the list except the one that says**Unallocated Space** . When you’re finished, only**Drive 0 Unallocated Space** should remain.

 5) Select**Next** .

 6) The Windows setup screen requests you choose your language/keyboard layout, remove the external storage drive from your device, and select**OK** . This will restart your device.

 7) Your device should be working properly now.

#### Pro tip: Update the essential drivers

 If the new setup fails to add some essential drivers correctly after a clean installation, such as for the network adapter and graphics card, you’ll need to update the driver whether through**Windows Update** or**Device Manager** .

##### 1\. Check for updates

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296855&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2023/recode/Nero_Recode_Screen_2.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/Windows-update.jpg)

 Type**Check for updates** in the Search box and press**Enter** .

##### 2\. Device Manager

![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-driver.jpg)

 In Device Manager, right-click your device and select**Update Driver** then choose search automatically.

##### 3\. Download from the manufacturer’s website

 Although Windows does a pretty good job detecting and installing most device drivers automatically, it can’t always update all of your drivers because of the OEM (Original equipment manufacturer) restrictions. In that case, you need to go to the manufacturer’s website for new drivers and install it manually.

##### 4\. Update all of your drivers automatically (Recommended)

 If you don’t have the time, patience or computer skills to update these drivers manually, you can**do it automatically** with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 **All the drivers in Driver Easy come straight from the manufacturer.**

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

<!-- affiliate ads begin -->
<a href="https://shop.manycam.com/order/checkout.php?PRODS=17728032&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8230bea7d54bcdf99cdfe85cb07313d5/mcaffbanner920x120.png" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2020/01/scan-now.png)

 3) Click**Update All** to automatically download and install the correct version of all essential and peripheral drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click_Update All_ . You get**full support** and a no-questions-asked**30-day money back guarantee** .)

![](https://images.drivereasy.com/wp-content/uploads/2020/01/update-all-your-drivers.jpg)

 Note: You can do it for free if you like, but it’s partly manual.

 If you need assistance or have any questions, please contact Driver Easy’s support team at [**support@drivereasy.com**](https://vapordna.pxf.io/vnbxna) .

 Good to go? Hopefully, one of the fixes above did the trick for you. Feel free to leave us a comment if you have further questions or suggestions.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://snapchat-videos.techidaily.com/new-effortlessly-merge-your-memories-photos-from-iphone-to-snapchat-for-2024/"><u>[New] Effortlessly Merge Your Memories  Photos From iPhone to Snapchat for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-maximizing-clarity-fb-messages-full-recording-process-for-2024/"><u>[New] Maximizing Clarity  FB Messages Full Recording Process for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-guiding-you-through-youtubes-view-limitations/"><u>[Updated] Guiding You Through YouTube's View Limitations</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-emoji-magic-for-enhanced-discord-statues/"><u>[Updated] In 2024, Emoji Magic for Enhanced Discord Statues</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-looms-labyrinth-navigating-screen-record-art-for-2024/"><u>[Updated] Loom's Labyrinth  Navigating Screen Record Art for 2024</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-leading-brands-for-budget-friendly-high-definition-projectors/"><u>2024 Approved  Leading Brands for Budget-Friendly, High-Definition Projectors</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-organize-your-fb-content-access-to-free-downloaders-online/"><u>2024 Approved  Organize Your FB Content  Access to Free Downloaders Online</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-hunt-for-windows-hello-camera/"><u>Compatibility Hunt for Windows Hello Camera</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211406665-fixing-the-crimson-display-issue-overcoming-the-notorious-red-screen-glitch/"><u>Fixing The Crimson Display Issue - Overcoming the Notorious Red Screen Glitch</u></a></li>
<li><a href="https://common-error.techidaily.com/follicular-carcinoma-while-less-common-than-papillary-still-accounts-for-a-significant-percentage-of-all-thyroid-cancers/"><u>Follicular Carcinoma, While Less Common than Papillary, Still Accounts for a Significant Percentage of All Thyroid Cancers.</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-repairing-inoperative-scrolling-features-of-a-touchpad-in-windows-11/"><u>Guide to Repairing Inoperative Scrolling Features of a Touchpad in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-correct-call-of-duty-world-at-war-error-code-4220-instantly-step-by-step-guide/"><u>How to Correct Call of Duty: World at War Error Code 4220 Instantly - Step by Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-not-present-device-issue-on-windows-pc-error-code-e-24/"><u>How to Fix the ‘Not Present’ Device Issue on Windows PC (Error Code E-24)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206258902-how-to-securely-eliminate-critical-error-scams-in-google-chrome-expert-tips-inside/"><u>How to Securely Eliminate Critical Error SCAMs in Google Chrome – Expert Tips Inside!</u></a></li>
<li><a href="https://fox-access.techidaily.com/in-2024-comprehensive-techniques-to-master-telegram-web-interface/"><u>In 2024, Comprehensive Techniques to Master Telegram Web Interface</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-how-does-the-stardust-trade-cost-in-pokemon-go-on-lava-blaze-2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How does the stardust trade cost In pokemon go On Lava Blaze 2 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-epson-scanner-connectivity-problems/"><u>Overcoming Epson Scanner Connectivity Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/recover-missing-taskbar-icon-shortcuts-in-windows-10-with-these-proven-tips/"><u>Recover Missing Taskbar Icon Shortcuts in Windows 10 With These Proven Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-pcs-silent-mode-addressing-lack-of-sound-in-windows-os/"><u>Resolve Your PC's Silent Mode: Addressing Lack of Sound in Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-steams-missing-files-and-restore-full-access/"><u>Resolved: How to Fix Steam's Missing Files and Restore Full Access</u></a></li>
<li><a href="https://common-error.techidaily.com/search-for-light-control-tool-in-windows/"><u>Search for Light Control Tool in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-dilemma-of-malfunctioning-usb-input-devices-in-windows-7-systems/"><u>Solving the Dilemma of Malfunctioning USB Input Devices in Windows 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-of-forced-reboots-instead-of-properly-closing-on-windows-11-systems/"><u>Solving the Problem of Forced Reboots Instead of Properly Closing on Windows 11 Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/soundscapes-synopsis-a-guide-to-visual-tunes/"><u>Soundscapes Synopsis  A Guide to Visual Tunes</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-fixing-0x800f0831-with-windows-update-features/"><u>Step-by-Step Guide: Fixing 0X800F0831 with Windows Update Features</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-reducing-high-cpu-consumption-from-windows-audio-device-isolation-discrepancy/"><u>Step-by-Step Guide: Reducing High CPU Consumption From Windows Audio Device Isolation Discrepancy</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202390863-third-monitor-not-detected-heres-the-real-fix/"><u>Third Monitor Not Detected? Here’s the Real Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-broken-key-on-your-keyboard-a-step-by-step-guide/"><u>Troubleshooting a Broken '@' Key on Your Keyboard - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211249748-troubleshooting-the-wi-fi-has-been-turned-off-error-solutions-proven-effective/"><u>Troubleshooting the 'Wi-Fi Has Been Turned Off' Error: Solutions Proven Effective!</u></a></li>
<li><a href="https://extra-resources.techidaily.com/unlocking-ps-simple-grading-techniques-for-perfection/"><u>Unlocking PS  Simple Grading Techniques for Perfection</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/upgraded-airflow-efficiency-discover-the-strength-of-thermaltakes-latest-br)/"><u>Upgraded Airflow Efficiency: Discover the Strength of Thermaltake's Latest ^Br></u></a></li>
<li><a href="https://win-howtos.techidaily.com/windows-groovy-guide-resolve-registry-error-while-opening-pictures/"><u>Windows Groovy Guide: Resolve 'Registry Error' While Opening Pictures</u></a></li>
</ul></div>
