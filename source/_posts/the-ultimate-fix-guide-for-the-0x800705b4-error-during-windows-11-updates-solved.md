---
title: The Ultimate Fix Guide for the 0X800705b4 Error During Windows 11 Updates [Solved]
date: 2024-09-16T16:18:11.152Z
updated: 2024-09-20T19:28:38.254Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes The Ultimate Fix Guide for the 0X800705b4 Error During Windows 11 Updates [Solved]
excerpt: This Article Describes The Ultimate Fix Guide for the 0X800705b4 Error During Windows 11 Updates [Solved]
thumbnail: https://thmb.techidaily.com/8b36213cf3c4388b8515bed526f0d42f540b1ba9bd34731fb80416cf28c2a508.jpg
---

## How to Fix the Windows Update Error Code 0X80070002: Simple Solutions

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60e09526e.png)

 If you are getting this error code**0x80070002** or**80070002** on your Windows PC/laptop, don’t worry! It’s one of the common error codes in Windows.

 This error can also display as**80070003** or**0x80070003** , and they’re actually the same problem and you can fix 0x80070003 with the solutions in this article as well.

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075482/7443" target="_top" id="2075482">
  <img src="//a.impactradius-go.com/display-ad/7443-2075482" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075482/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

#### Step 2: Delete the Software Distribution Folder

 1) Double-click the drive where your Windows is installed, generally in**C drive** .

 2) Go to folders:**Windows > SoftwareDistribution** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0174add00e1.jpg)

 3) Delete the folder named**SoftwareDistribution** .  (If you’re prompted for an administrator password or confirmation, type your password or provide confirmation.)

 If you don’t want to delete this folder, you can also rename it with**SoftwareDistributionOld** .

4) Close all the panes.

#### Step 3: Re-enable the Windows Update service

 1) On your keyboard, press the**Windows logo key** **\+ R** at the same time to invoke the Run box.

 2) Type**services.msc** , and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a017371df6a8.png)

<!-- affiliate ads begin -->
<span id="1983549">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983549.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983549">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983549.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983549%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983549/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Right-click Windows Update (if you are using Windows XP, right-click**Automatic Updates** ), and click**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2023/12/win11-Windows-update-Start-1200x690.jpg)

 4) Restart your Windows and try Windows Update again to see if it solves the problem.

---

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
<a href="https://aligracehair.sjv.io/c/5597632/1925565/19272" target="_top" id="1925565">
  <img src="//a.impactradius-go.com/display-ad/19272-1925565" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925565/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Go to   _**HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade** ._

 4) Select**OSUpgrade** key, then right-click the empty area on the right pane of Registry Editor, and click**New** , then c lick **DWORD (32-bit) Value** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7817546e624.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 5) Right-click the newly created**NewValue#1** and select**Modify** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a78180511caf.png)

 6) Change the value name to **AllowOSUpgrade** , after which you can double-click the number under Value data and enter**1** . Select **Hexadecimal** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a781900ea1c1.png)

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145079/17095" target="_top" id="2145079">
  <img src="//a.impactradius-go.com/display-ad/17095-2145079" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145079/17095" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

 3) Click the**Update** button next to a flagged device to automatically download and install the correct version of this driver (you can do this with the**FREE** version).
  
 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/03/Driver-Easy-Update-All.jpg)

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
<li><a href="https://youtube-docs.techidaily.com/024-approved-managing-who-accesses-your-youtube-videography/"><u>[New] 2024 Approved Managing Who Accesses Your YouTube Videography</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-ideal-voice-transformation-tools-for-digital-talent/"><u>[Updated] Ideal Voice Transformation Tools for Digital Talent</u></a></li>
<li><a href="https://fox-access.techidaily.com/2024-approved-prime-choice-of-low-cost-hd-action-recorders/"><u>2024 Approved Prime Choice of Low-Cost HD Action Recorders</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-steps-for-fixing-missing-media-device-drivers-on-windows/"><u>Essential Steps for Fixing Missing Media Device Drivers on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-windows-11s-night-light-feature-failure/"><u>Fixing the Issue: Windows 11'S Night Light Feature Failure</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-nokia-c210-if-i-forgot-security-code-or-password-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Nokia C210 If I Forgot Security Code or Password? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-how-can-i-catch-the-regional-pokemon-without-traveling-on-poco-c51-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Catch the Regional Pokémon without Traveling On Poco C51 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-ispoofer-is-not-working-on-apple-iphone-13-pro-max-fixed-drfone-by-drfone-virtual-ios/"><u>In 2024, iSpoofer is not working On Apple iPhone 13 Pro Max? Fixed | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210615747-nba-2k21s-green-error-solved-expert-tips-inside/"><u>NBA 2K21's Green Error Solved - Expert Tips Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210756908-overcome-the-0x80073712-error-in-windows-10-tips-and-tricks-for-a-smooth-operating-experience/"><u>Overcome the 0X80073712 Error in Windows 10: Tips and Tricks for a Smooth Operating Experience!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-power-symbol-disappearance-issue-on-windows-11-a-comprehensive-guide/"><u>Resolving the Power Symbol Disappearance Issue on Windows 11: A Comprehensive Guide</u></a></li>
<li><a href="https://extra-tips.techidaily.com/seamless-soundscapes-youtube-music-integration-tips/"><u>Seamless Soundscapes YouTube Music Integration Tips</u></a></li>
<li><a href="https://vp-tips.techidaily.com/top-3-estrategias-para-converter-filmes-em-dvd-do-formato-mkv-compativel-com-windows-e-mac/"><u>Top 3 Estratégias Para Converter Filmes Em DVD Do Formato MKV (Compatível Com Windows E Mac)</u></a></li>
</ul></div>

