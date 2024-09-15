---
title: "Fixing the Mysterious Darkness: Solutions to Chrome's Black Screen Dilemma"
date: 2024-09-12T16:01:02.587Z
updated: 2024-09-15T16:01:52.841Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Mysterious Darkness: Solutions to Chrome's Black Screen Dilemma"
excerpt: "This Article Describes Fixing the Mysterious Darkness: Solutions to Chrome's Black Screen Dilemma"
thumbnail: https://thmb.techidaily.com/061c3cb51f73174994130ac8ba7737b4e102bdd69124ffc25dc40b79dd6e4589.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

 Here are the solutions that have helped other Windows users resolve error 0x80240017\. You don’t need to try them all; just work your way down the list until everything’s working again.

1. **[Run Windows Update Troubleshooter](#F1)**
2. **[Reset Windows Update Components](#F2)**
3. **[Repair corrupted system files](#F3)**
4. **[Update available drivers](#F4)**

 Note: the screenshots below com from Windows 10, and fixes apply to Windows 11, 8 and 7.

### Fix 1: Run Windows Update Troubleshooter

 Windows Update Troubleshooter is a helpful tool built in Windows system, and you can use it to scan and fix the Windows Update error 0x80240017.

Here’s what you can do:

1. Type**Troubleshoot** in the search box on your desktop, and click**Troubleshoot** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04da616dafa.jpg)
2. Click**Troubleshoot** on the left. Click**Windows Update** \>**Run the troubleshooter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dacebef4f.jpg)
3. Windows will start detecting problems, which will take several minutes. Once done, follow the on-screen instructions to complete the process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

If the Windows Update error persists, move on to the second method.

### Fix 2: Reset Windows Update Components

 Windows Update components ensure Windows Update runs properly and the updates can be installed successfully in your computer. If there’s anything wrong during the process, you can try resetting Windows Update components and see how it works.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Copy and paste the following commands one by one in Command Prompt, and press**Enter** on your keyboard.  
**net stop wuauserv**  
**net stop cryptSvc**  
**net stop bits**  
**net stop msiserver**  
 **ren C:\\Windows\\SoftwareDistribution SoftwareDistribution.old**  
**ren C:\\Windows\\System32\\catroot2 catroot2.old**  
**net start wuauserv**  
**net start cryptSvc**  
**net start bits**  
**net start msiserver**  
**pause**  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dd3338a3f.jpg)
3. Wait for the commands to complete, and exit Command Prompt.
4. Open Windows Update and see if it works properly.

 If your issue still persists, don’t worry, There is something else to try.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135351/19272" target="_top" id="2135351">
  <img src="//a.impactradius-go.com/display-ad/19272-2135351" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135351/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  

<!-- affiliate ads begin -->
<span id="1328683">
					<video width="200" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1328683.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1328683">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1328683.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:125px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1328683%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1328683/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 4: Update available drivers

 To ensure your computer operates without problems, you should keep your devices drivers up to date. And here are two ways for you to update drivers:**manually** and**automatically** .

**Manually update your driver** – You can go to the manufacturer’s website of your devices, find the latest driver that’s compatible with your Windows operating system, and download it. Once done, open the downloaded file and follow the instruction to install it to your computer.

**Automatically update your driver** **(recommended)** – If you don’t have time or patience, you can do it automatically with[**Driver** **Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  it takes just 2 clicks (and you get full support and a**30-day money back guarantee** ):

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click**Scan Now** . Then Driver Easy will scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/06/driver-easy-scan.jpg)
3. Click the**Update** button next to the flagged device(s) to automatically download the driver (you can do that with the FREE version), then install it in your computer.  
 Or click**Update All** to automatically download and install all the correct drivers for problem drivers (you can do this with the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) , and you’ll be prompted to upgrade when your click**Update All** ).  
![](https://images.drivereasy.com/wp-content/uploads/2023/07/driver-easy-update.jpg)
4. Restart your computer to take effect.

 Open Windows Update to download and install updates and it should working now.

 So there you have it – Hope this post helps in resolving your**Windows Update error** **0x80240017** . If you have any questions or suggestions, feel free to leave a comment below.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](/tag-search/?tagId=62)

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
<li><a href="https://common-error.techidaily.com/fixed-error-orglwjgllwjglexception-pixel-format-not-accelerated/"><u>[Fixed] Error: org.lwjgl.LWJGLException: Pixel Format Not Accelerated</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-top-quality-economical-cam-recorder/"><u>[New] 2024 Approved Top Quality Economical Cam Recorder</u></a></li>
<li><a href="https://fox-info.techidaily.com/bebops-avian-evolution-strikes-again-with-parrot-2-for-2024/"><u>Bebop's Avian Evolution Strikes Again with Parrot 2 for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-solving-d3derrnotavailable-error-with-ease/"><u>Expert Advice on Solving 'D3DERR_NOTAVAILABLE' Error with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-stalled-or-halted-windows-11-update-process-guide/"><u>Fixing a Stalled or Halted Windows 11 Update Process - Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-freezing-or-crashing-windows-10-system/"><u>How to Fix a Freezing or Crashing Windows 10 System</u></a></li>
<li><a href="https://extra-resources.techidaily.com/in-2024-comprehensive-guide-to-sns-hdr-pro-and-similar-software/"><u>In 2024, Comprehensive Guide to SNS HDR Pro and Similar Software</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-full-tutorial-to-bypass-your-sony-xperia-5-v-face-lock-by-drfone-android/"><u>In 2024, Full Tutorial to Bypass Your Sony Xperia 5 V Face Lock?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-how-to-unlock-iphone-se-2022-with-imei-code-by-drfone-ios/"><u>In 2024, How to Unlock iPhone SE (2022) with IMEI Code?</u></a></li>
<li><a href="https://solve-hot.techidaily.com/latest-update-abbyy-releases-enhanced-abbyy-flexicapture-v122/"><u>Latest Update: ABBYY Releases Enhanced ABBYY FlexiCapture V12.2</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-manually-shutting-down-unresponsive-pcs-on-windows-10-solved/"><u>Mastering The Art Of Manually Shutting Down Unresponsive PCs on Windows 10 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-error-1-section-1-problem-advanced-pulse-modulation-techniques/"><u>Mastering the Fix: Error 1 # Section 1: Problem - Advanced Pulse Modulation Techniques</u></a></li>
<li><a href="https://extra-hints.techidaily.com/profound-overview-a-full-look-at-bublcam-360-technology/"><u>Profound Overview A Full Look at Bublcam 360 Technology</u></a></li>
<li><a href="https://network-issues.techidaily.com/quick-steps-to-overcome-c1900101-during-win11-setup/"><u>Quick Steps to Overcome C1900101 During Win11 Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-overcome-update-error-0xc1900208-in-windows-11/"><u>Step-by-Step Solutions to Overcome Update Error 0xC1900208 in Windows 11</u></a></li>
<li><a href="https://some-guidance.techidaily.com/the-essentials-understanding-whatsapp-calls-for-2024/"><u>The Essentials Understanding WhatsApp Calls for 2024</u></a></li>
</ul></div>

