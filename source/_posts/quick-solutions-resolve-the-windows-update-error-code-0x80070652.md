---
title: "Quick Solutions: Resolve the Window's Update Error Code 0X80070652"
date: 2025-01-14T16:08:50.476Z
updated: 2025-01-16T16:16:18.062Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Quick Solutions: Resolve the Window's Update Error Code 0X80070652"
excerpt: "This Article Describes Quick Solutions: Resolve the Window's Update Error Code 0X80070652"
thumbnail: https://thmb.techidaily.com/61f98fc4d9e1af032d9fc6896b875fde870b9cc610ca573f8ea2783fc3752f47.jpg
---

## Resolving the Troublesome 0X80240017 Windows Update Issue: Proven Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04d8761fcdb.jpg)

 The**0x80240017** error is a common Windows Update error which happens when you’re downloading or installing your Windows updates and indicates the Windows update failed. It’s generally caused by system files corruption or driver issues. But don’t worry. You can try the solutions below to fix this problem easily.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RAnyQ0uj9Yg?si=Es4_ulcdM_-LuDcq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/tkpBmccvJ_Q?si=J7ellPL1G1l8Axi_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/12/img_5c04dae7e3360.png)
4. Restart your computer and try Windows Update again to see if it works.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/W5aJC8okA8s?si=L2rnYAp-gmGlLQSf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
![](https://images.drivereasy.com/wp-content/uploads/2022/01/fortect-2.jpg)
4. Once done, you’ll see a detailed report of all the issues on your PC. To fix them automatically, click**START REPAIR** . This requires you to purchase the full version. But don’t worry. If Fortect doesn’t solve the issue, you can request a refund within 60 days.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VlwHTQQMs?si=BXYwD1pKiaTuev4y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/it8VkxDUdAc?si=ef6VZWR7kW4P9ikh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-digital-divas-top-ten-gamers-on-youtube/"><u>[New] 2024 Approved Digital Divas Top Ten Gamers on YouTube</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-seamless-streaming-tackle-instagram-video-woes/"><u>[New] 2024 Approved Seamless Streaming Tackle Instagram Video Woes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-break-bot-patterns-enhance-organic-video-reach-for-2024/"><u>[New] Break Bot Patterns, Enhance Organic Video Reach for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/new-future-of-techno-gaming-revenue-for-2024/"><u>[New] Future of Techno-Gaming Revenue for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-global-gala-of-greatest-video-views/"><u>[Updated] 2024 Approved Global Gala of Greatest Video Views</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-superior-streaming-with-integrated-local-channels-future-edition/"><u>[Updated] Superior Streaming with Integrated Local Channels, Future Edition</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/a-step-by-step-guide-on-using-adb-and-fastboot-to-remove-frp-lock-from-your-vivo-y78plus-t1-edition-by-drfone-android/"><u>A Step-by-Step Guide on Using ADB and Fastboot to Remove FRP Lock from your Vivo Y78+ (T1) Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-keyboard-failure-heres-what-you-need-to-know-to-get-it-working-again/"><u>Corsair Keyboard Failure? Here's What You Need to Know to Get It Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-players-with-sims-aturated-and-her-sister-isabella-was-an-active-child-who-loved-to-play-soccer/"><u>Effective Solutions for Players with Sims Aturated, and Her Sister Isabella Was an Active Child Who Loved to Play Soccer</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-secure-connections-on-firefox-platforms/"><u>Expert Tips for Restoring Secure Connections on Firefox Platforms</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-guide-overcome-the-issue-of-set-user-settings-to-driver-failed/"><u>Fix Guide: Overcome the Issue of 'Set User Settings To Driver Failed'</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-vanished-desktop-icons-on-windows-10-a-complete-guide/"><u>Fixing Vanished Desktop Icons on Windows 10: A Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/ftdi-memory-corruption-issue-how-incorrect-drivers-can-compromise-data-integrity/"><u>FTDI Memory Corruption Issue - How Incorrect Drivers Can Compromise Data Integrity</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206903020-hp-laptop-keyboard-woes-heres-how-to-get-your-keys-working-again-in-no-time/"><u>HP Laptop Keyboard Woes? Here's How to Get Your Keys Working Again in No Time!</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-transfer-data-from-realme-narzo-n55-to-blackberry-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Transfer Data from Realme Narzo N55 to BlackBerry | Dr.fone</u></a></li>
<li><a href="https://win-forum.techidaily.com/navigating-the-giants-of-digital-engagement-facebook-twitter-instagram-and-youtube/"><u>Navigating the Giants of Digital Engagement: Facebook, Twitter, Instagram & Youtube</u></a></li>
<li><a href="https://win-howtos.techidaily.com/overcoming-google-chromes-not-responding-glitches-expert-fix-guide/"><u>Overcoming Google Chrome's 'Not Responding' Glitches – Expert Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-windows-7s-troublesome-update-downloads-expert-tips-and-tricks/"><u>Overcoming Windows 7'S Troublesome Update Downloads: Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/verdict-drivers-refrain-from-supporting-opengl/"><u>Verdict: Drivers Refrain From Supporting OpenGL</u></a></li>
</ul></div>

