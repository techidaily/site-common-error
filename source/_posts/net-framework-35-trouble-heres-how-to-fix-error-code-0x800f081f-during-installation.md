---
title: .NET Framework 3.5 Trouble? Here's How to Fix Error Code 0X800F081F During Installation
date: 2024-09-14T16:00:12.380Z
updated: 2024-09-15T16:00:29.182Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes .NET Framework 3.5 Trouble? Here's How to Fix Error Code 0X800F081F During Installation
excerpt: This Article Describes .NET Framework 3.5 Trouble? Here's How to Fix Error Code 0X800F081F During Installation
thumbnail: https://thmb.techidaily.com/dc8c23798056f26fbb4ba042d36186a35f13e6ccd93d9efde90962c264b99c13.jpg
---

## WinUpdate Trouble? Here's How to Fix Error 0X80240017 for Good

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

### Fix 3: Repair corrupted system files

 Missing or corrupted system files can also trigger the Windows Update error 0x80240017\. To detect and fix them, you may need to perform an in-depth PC scan.

#### Option 1 – Automatically (recommended)

**[Fortect](https://tools.techidaily.com/drivereasy/download/)**  is a powerful Windows repair and optimization tool. It can detect a variety of hardware or security issues, and replace damaged files on your computer with correct and updated Windows files and components. It’s much like a fresh reinstallation of Windows, but keeps your programs, user data and settings as they are.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Fortect.
2. Open Fortect and click**Yes** to run a free scan of your PC.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-1.jpg)
3. Fortect will scan your computer thoroughly. This may take a few minutes.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135355/19272" target="_top" id="2135355">
  <img src="//a.impactradius-go.com/display-ad/19272-2135355" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135355/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-3.jpg)

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014848/22899" target="_top" id="2014848">
  <img src="//a.impactradius-go.com/display-ad/22899-2014848" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014848/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

#### Option 2 – Manually

 System File Checker (SFC) is a Windows built-in tool to identify and repair corrupted system files. But note that checking and restoring system files in this way might take some time and computer skills, and you may risk your personal data.

1. Type**cmd** in the search box on your desktop, right click on**Command Prompt** and select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04db671de3d.jpg)
2. Type the following command and press**Enter** .  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04ddb7ef0b3.jpg)
3. Once the process is 100% complete, exit Command Prompt and restart your computer.

 Try to update Windows again and see if it fixes your error 0x80240017\. Still no luck? There’s one more thing to try.

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115933/19272" target="_top" id="2115933">
  <img src="//a.impactradius-go.com/display-ad/19272-2115933" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115933/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://extra-support.techidaily.com/new-step-by-step-guide-to-ace-11-essential-color-correction-tutorials/"><u>[New] Step-by-Step Guide to Ace 11 Essential Color Correction Tutorials</u></a></li>
<li><a href="https://win-able.techidaily.com/cyberpunk-2077-overcome-freezing-issue-optimization-success/"><u>Cyberpunk 2077 Overcome Freezing Issue - Optimization Success!</u></a></li>
<li><a href="https://common-error.techidaily.com/ease-windows-wmi-process-demands/"><u>Ease Windows WMi Process Demands</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-slow-download-problem-in-league-of-legends-once-and-for-all/"><u>Fixing the Slow Download Problem in League of Legends Once and For All</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-failed-update-on-your-windows-amoled-version-1803-explained/"><u>How to Fix a Failed Update on Your Windows Amoled - Version 1803 Explained</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-managing-excessive-tiktoks-mastering-edits-and-deletions/"><u>In 2024, Managing Excessive TikToks Mastering Edits & Deletions</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-the-ultimate-guide-to-self-supported-youtube-earnings-strategies/"><u>In 2024, The Ultimate Guide to Self-Supported YouTube Earnings Strategies</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-top-notch-solutions-for-disabled-apple-id-from-iphone-13-pro-making-it-possible-by-drfone-ios/"><u>In 2024, Top-Notch Solutions for Disabled Apple ID From iPhone 13 Pro Making It Possible</u></a></li>
<li><a href="https://fox-helps.techidaily.com/in-2024-virtual-decoration-google-vs-alternative-ar-tools/"><u>In 2024, Virtual Decoration Google Vs. Alternative AR Tools</u></a></li>
<li><a href="https://unlock-android.techidaily.com/remove-the-lock-screen-fingerprint-of-your-xiaomi-redmi-note-12t-pro-by-drfone-android/"><u>Remove the Lock Screen Fingerprint Of Your Xiaomi Redmi Note 12T Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-valorants-perpetual-launch-loop-issue/"><u>Resolving Valorant's Perpetual Launch Loop Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-cannot-be-installed-error-80240020-step-by-step-solutions/"><u>Resolving Windows 10 Cannot Be Installed: Error 80240020 – Step-by-Step Solutions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/reviving-your-reliable-tiktok-videos/"><u>Reviving Your Reliable TikTok Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-a-bluetooth-keyboard-that-refuses-to-sync-with-your-personal-computer/"><u>Step-by-Step Solutions for a Bluetooth Keyboard That Refuses to Sync with Your Personal Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-a-down-dns-server-in-just-four-steps/"><u>Troubleshooting and Repairing a Down DNS Server in Just Four Steps</u></a></li>
</ul></div>
