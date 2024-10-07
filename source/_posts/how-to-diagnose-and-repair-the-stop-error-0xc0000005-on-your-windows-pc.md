---
title: How to Diagnose and Repair the STOP Error 0xC0000005 on Your Windows PC
date: 2024-10-02T22:06:23.044Z
updated: 2024-10-06T19:47:05.467Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Diagnose and Repair the STOP Error 0xC0000005 on Your Windows PC
excerpt: This Article Describes How to Diagnose and Repair the STOP Error 0xC0000005 on Your Windows PC
thumbnail: https://thmb.techidaily.com/3f659a3b4bb25cd415ed00e454404730b9869c867cd294c9e58180160b4e9b56.jpg
---

## Troubleshoot and Correct Windows Update Failure 0X80070002 Fast

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60e09526e.png)

 If you are getting this error code**0x80070002** or**80070002** on your Windows PC/laptop, don’t worry! It’s one of the common error codes in Windows.

 This error can also display as**80070003** or**0x80070003** , and they’re actually the same problem and you can fix 0x80070003 with the solutions in this article as well.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

### How to Fix Error 0x80070002?

 Here are solutions that have helped other users resolve the error 0x80070002\. You may not need to try them all; just work your way down the list until everything’s working again.

1. **[Check the Date and Time settings](#Method1)**
2. **[Delete the Software Distribution Folder](#Method2)**
3. **[Try Windows Update Troubleshooter](#Method3)**
4. [**Modify Registry Editor**](#Method5)
5. **[Bonus Tip](#b1)**

### Why does the error 0x80070002 occur?

 This error code may vary from different Windows versions. In Windows XP, you will see the error code **0x80070002** . While in Windows 10/8/7, you will see the error code **80070002** .

 This problem happens when some files in the Windows Update are missing or corrupted, even though the update is downloaded and extracted successfully, or the driver faulty issue. So you can work it through by these methods until it solves your problem.

---

## **Method 1: Check the Date and Time settings**

 This may sound unbelievable as a solution to fix 0x80070002 error code, but it does work for many Windows users. One of the major causes of the error is the incorrect time/date settings, so it’s necessary to make sure that your computer’s time synchronizes with the Internet time server.

[For Windows 7/8 users](#Windows7)

[For Windows 10/11 users](#Windows1)

 If you are using Windows 7/8:

 1) Click the**Date and Time** button at the bottom right, then click**Change date and time settings** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a01819233c7d.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135367/19272" target="_top" id="2135367">
  <img src="//a.impactradius-go.com/display-ad/19272-2135367" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135367/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) Click **Change date and time** to make sure that the date and time is correct on your Windows, then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0181cc9eb3f.jpg)

 3) Click**Change time zone** to make sure that the time zone is correct, then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0181f1e2bac.jpg)

 4) Click the**Internet Time** tab at the top, then click**Change Settings** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a018705735c3.jpg)

 5) Make sure to check the box next to**Synchronize with an Internet time server** , and click**Update now** , then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0182e74a509.jpg)

 7) Click**OK** to finish the settings.

 8) Restart your computer and try Windows Update again to see if it works.

 If you are using Windows 10, you can check the date and time setting by**Command Prompt** .

 1) Type**cmd** in the search box, and right click**Command Prompt**  to click**Run as administrator** , then click**Yes** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a018c0f66b68.png)

 2) Respectively type**time** ,**date** , and **w32tm/resync**  in the window, and press**Enter** after each command. If the time and date are incorrect after running, you can type the correct time and date in the window and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0266f185a5c.jpg)

 3) After the commands complete, restart your computer and try Windows Update again to see if it works.

---

---

## **Method 2: Modify the Windows Update installation files**

 Sometimes the error 0x80070002 occurs because the system update process fails, and the Windows Update installation files are corrupted or missing. So you can try to delete the installation files or rename the installation folder to solve the problem.

 Before we modify the files or folder, you may need to stop the Windows Update service. Otherwise the files or folder are open in programs and you can’t modify it. So follow the steps below:

#### Step 1: Disable the Windows Update service

 1) On your keyboard, press the**Windows logo key** **\+ R** at the same time to invoke the Run box.

 2) Type**services.msc** , and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a017383ddfcc.png)

 3) Double click**Windows Update** (if you are using Windows XP, double click**Automatic Updates** ).

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a780f0e4842e.jpg)

 4) Change the**Startup type** to**Automatic** . Then, make sure the Service status is set to**Stopped** . If it’s**Running** , click**Stop** then click**Apply** , and**OK** to save the changes.

![](https://images.drivereasy.com/wp-content/uploads/2021/12/2021-12-10_11-51-40-1.jpg)

#### Step 2: Delete the Software Distribution Folder

 1) Double-click the drive where your Windows is installed, generally in**C drive** .

 2) Go to folders:**Windows > SoftwareDistribution** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0174add00e1.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484950/16446" target="_top" id="1484950">
  <img src="//a.impactradius-go.com/display-ad/16446-1484950" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484950/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Delete the folder named**SoftwareDistribution** .  (If you’re prompted for an administrator password or confirmation, type your password or provide confirmation.)

 If you don’t want to delete this folder, you can also rename it with**SoftwareDistributionOld** .

4) Close all the panes.

#### Step 3: Re-enable the Windows Update service

 1) On your keyboard, press the**Windows logo key** **\+ R** at the same time to invoke the Run box.

 2) Type**services.msc** , and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a017371df6a8.png)

 3) Right-click Windows Update (if you are using Windows XP, right-click**Automatic Updates** ), and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2023/12/win11-Windows-update-Start-1200x690.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082532/7443" target="_top" id="2082532">
  <img src="//a.impactradius-go.com/display-ad/7443-2082532" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082532/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Restart your Windows and try Windows Update again to see if it solves the problem.

---

<!-- affiliate ads begin -->
<a href="https://aidotcom.pxf.io/c/5597632/2129042/19576" target="_top" id="2129042">
  <img src="//a.impactradius-go.com/display-ad/19576-2129042" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aidotcom.pxf.io/i/5597632/2129042/19576" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Method 3: Try Windows Update Troubleshooter**

 The Windows Update Troubleshooter is always a method to consider when you have any problems running Windows Update.

 1) Download the troubleshooter from[**Microsoft**](https://support.microsoft.com/en-ph/help/4027322/windows-windows-update-troubleshooter) .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0177a875597.png)

 2) Run the downloaded file.

 3) Click**Windows Update** , and click**Next** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0175eea504b.png)

 4) Then it will run and try to fix the problem. After completing, restart your computer and try Windows Update again to see if it works.

---

## **Method 4: Modify Registry Editor**

 If you see the error when installing the Windows upgrade: Something happened 0x80070002, you can try this method to solve the issue.

 Before going on, you may need to make sure that you select **English (United States)** in the Language setting. And please run Windows Media Creation Tool as administrator. Right-click it and select Run as administrator option. Then follow the instructions:

 1) Press the**Windows logo key** **\+ R** at the same time on your keyboard.

 2) Type **regedit** and press**Enter** . You may need to provide the administrative right to open, click**Yes** to confirm.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7816a3da385.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/947750/11832" target="_top" id="947750">
  <img src="//a.impactradius-go.com/display-ad/11832-947750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/947750/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Go to   _**HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade** ._

 4) Select**OSUpgrade** key, then right-click the empty area on the right pane of Registry Editor, and click**New** , then c lick **DWORD (32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7817546e624.png)

 5) Right-click the newly created**NewValue#1** and select**Modify** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a78180511caf.png)

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/2106655/12108" target="_top" id="2106655">
  <img src="//a.impactradius-go.com/display-ad/12108-2106655" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/2106655/12108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 6) Change the value name to **AllowOSUpgrade** , after which you can double-click the number under Value data and enter**1** . Select **Hexadecimal** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a781900ea1c1.png)

7) Restart your computer and try again to see if it works.

---

## **Bonus Tip: Update device drivers**

 Updating your device drivers is so important that you should verify the device drivers are all up to date. By doing so, it can resolve many hardware issues and bring the best possible experience for you.

**Option 1 – Manually** : You can first uninstall your device drivers in Device Manager, and go to the official website to download the correct drivers matched with your Windows OS. That may require time and computer skills.

**Option 2 – Automatically (Recommended)** : If you don’t have the time or skills to update the drivers manually, you can do it automatically with[**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 With Driver Easy, you don’t need to figure out the Operating System, and you don’t need to worry about making mistakes while processing. That will tremendously save you time and patience.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version, it takes just 2 clicks (and you get full support and a**30-day money-back guarantee** ):

 1) [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Scan-Needed.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Click the**Update** button next to a flagged device to automatically download and install the correct version of this driver (you can do this with the**FREE** version).
  
 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Update-All.jpg)

<!-- affiliate ads begin -->
<a href="https://review-au.sjv.io/c/5597632/2135315/14409" target="_top" id="2135315">
  <img src="//a.impactradius-go.com/display-ad/14409-2135315" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://review-au.sjv.io/i/5597632/2135315/14409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) After updating, restart your computer and try the Windows Update again.

---

 These are the most common and helpful methods to**fix 0x80070002 error code in Windows Update** . Which method helps solve your problem? If your problem persists, feel free to comment below and we will see what more we can do to help.

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
<li><a href="https://screen-sharing-recording.techidaily.com/new-camera-glitches-ended-by-obs-fix-for-2024/"><u>[New] Camera Glitches Ended by OBS Fix for 2024</u></a></li>
<li><a href="https://app-tips.techidaily.com/best-free-and-premium-high-speed-camera-applications-for-both-iphone-and-android-users/"><u>Best Free and Premium High-Speed Camera Applications for Both iPhone and Android Users</u></a></li>
<li><a href="https://common-error.techidaily.com/black-screen-no-more-a-guide-to-troubleshooting-your-obs-setup/"><u>Black Screen No More: A Guide to Troubleshooting Your OBS Setup</u></a></li>
<li><a href="https://activate-lock.techidaily.com/bypass-icloud-activation-lock-with-imei-code-on-your-iphone-se-2020-by-drfone-ios/"><u>Bypass iCloud Activation Lock with IMEI Code On your iPhone SE (2020)</u></a></li>
<li><a href="https://common-error.techidaily.com/fortnite-resolved-how-to-get-your-old-graphics-card-working-on-a-windows-pc/"><u>Fortnite Resolved: How to Get Your Old Graphics Card Working on a Windows PC</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/head-to-head-comparison-the-features-and-performance-of-apple-watch-series-9-vs-fitbit-charge-n/"><u>Head-to-Head Comparison: The Features and Performance of Apple Watch Series 9 Vs. Fitbit Charge N</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-error-code-2024-related-to-dota-2s-changing-apis-swiftly/"><u>How to Fix Error Code 2024 Related to Dota 2'S Changing APIs Swiftly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-best-anti-tracker-software-for-tecno-camon-20-drfone-by-drfone-virtual-android/"><u>In 2024, Best Anti Tracker Software For Tecno Camon 20 | Dr.fone</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-free-filmora-13-editor-download-for-windows-and-mac/"><u>In 2024, Free Filmora 13 Editor Download For Windows and Mac</u></a></li>
<li><a href="https://twitter-clips.techidaily.com/in-2024-giggle-gazette-twitters-top-threads/"><u>In 2024, Giggle Gazette Twitter’s Top Threads</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-detect-and-remove-spyware-on-realme-narzo-60-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Detect and Remove Spyware on Realme Narzo 60 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://win-hot.techidaily.com/introducing-the-cutting-edge-apowerrescue-software-experience-exceptional-new-functionality-today/"><u>Introducing the Cutting-Edge ApowerRescue Software - Experience Exceptional New Functionality Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-thawing-your-pc-from-freezing-up/"><u>Step-by-Step Guide: Thawing Your PC From Freezing Up</u></a></li>
<li><a href="https://buynow-info.techidaily.com/step-by-step-instructions-enjoying-the-2024-olympic-gymnastics-competitions-online/"><u>Step-by-Step Instructions: Enjoying the 2024 Olympic Gymnastics Competitions Online</u></a></li>
<li><a href="https://common-error.techidaily.com/streamline-your-files-essential-techniques-for-using-file-explorer-in-widows-11/"><u>Streamline Your Files: Essential Techniques for Using File Explorer In Widows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205625785-total-war-rome-remastered-crash-issues-simple-solutions-uncovered/"><u>Total War: Rome Remastered Crash Issues - Simple Solutions Uncovered</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-wireless-mouse-that-inconsistently-fails-in-windows-11-and-10/"><u>Troubleshooting a Wireless Mouse That Inconsistently Fails in Windows 11 and 10</u></a></li>
<li><a href="https://common-error.techidaily.com/valorant-launch-stuck-on-infinite-load-heres-how-to-fix-it/"><u>Valorant Launch Stuck on Infinite Load? Here's How to Fix It</u></a></li>
<li><a href="https://common-error.techidaily.com/why-is-my-system-restore-not-working-on-windows-10-understanding-the-causes-and-solutions/"><u>Why Is My System Restore Not Working on Windows 10? Understanding the Causes and Solutions</u></a></li>
</ul></div>

