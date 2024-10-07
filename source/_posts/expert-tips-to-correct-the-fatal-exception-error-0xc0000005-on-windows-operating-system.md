---
title: Expert Tips to Correct the Fatal Exception Error (0xC0000005) on Windows Operating System
date: 2024-09-29T20:10:51.327Z
updated: 2024-10-07T11:41:35.533Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips to Correct the Fatal Exception Error (0xC0000005) on Windows Operating System
excerpt: This Article Describes Expert Tips to Correct the Fatal Exception Error (0xC0000005) on Windows Operating System
thumbnail: https://thmb.techidaily.com/b92970fb02a09749baa6f2838ddd89dd174bd2bb3f33370dc3c96100a7eda776.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  
## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  
b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  
Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  
3)  

Type the following commands and hit **Enter** to run them one by one:  
**• cd C:\\Program Files**
**• takeown /f WindowsApps /r /d Y**
 **• icacls WindowsApps /grant “%USERDOMAIN%\\%USERNAME%”:(F) /t**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
4)  

Follows the a) & b) of Step 1 to open**System Configuration**Window.  
This time uncheck **Safe boot** to reboot your Windows 10.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/5-1.jpg)
  
5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484910/16446" target="_top" id="1484910">
  <img src="//a.impactradius-go.com/display-ad/16446-1484910" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484910/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123511/26400" target="_top" id="2123511">
  <img src="//a.impactradius-go.com/display-ad/26400-2123511" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123511/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2005196/22899" target="_top" id="2005196">
  <img src="//a.impactradius-go.com/display-ad/22899-2005196" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2005196/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

2)  

Type the following commands and hit **Enter**  to run them one by one:  
**• cd C:\\Program Files**
**• attrib WindowsApps -h**
 **• rename WindowsApps WindowsApps.old**
  
3)

Reboot your Windows 10, then run System Restore again.  
  
That’s it!

* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://common-error.techidaily.com/fixed-this-device-is-not-present-code-24-windows-10-8-or-7/"><u>[Fixed] This Device Is Not Present (Code 24) - Windows 10, 8 or 7</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-engaging-with-your-audience-through-twitter-promos-for-2024/"><u>[Updated] Engaging With Your Audience Through Twitter Promos for 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/5-easy-ways-to-change-location-on-youtube-tv-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>5 Easy Ways to Change Location on YouTube TV On Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://location-fake.techidaily.com/8-solutions-to-fix-find-my-friends-location-not-available-on-zte-nubia-flip-5g-drfone-by-drfone-virtual-android/"><u>8 Solutions to Fix Find My Friends Location Not Available On ZTE Nubia Flip 5G | Dr.fone</u></a></li>
<li><a href="https://video-capture.techidaily.com/comprehensive-tutorial-adding-timer-functionality-to-obs/"><u>Comprehensive Tutorial Adding Timer Functionality to OBS</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-overcoming-severe-cxcrystalize-issues-smoothly/"><u>Expert Advice on Overcoming Severe Cx_Crystalize Issues Smoothly</u></a></li>
<li><a href="https://techidaily.com/guide-on-how-to-erase-apple-iphone-12-pro-max-devices-entirely-drfone-by-drfone-ios-full-data-eraser-ios-full-data-eraser/"><u>Guide on How To Erase Apple iPhone 12 Pro Max Devices Entirely | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-locked-iphone-15-password-learn-the-best-methods-to-unlock-drfone-by-drfone-ios/"><u>In 2024, Forgot Locked iPhone 15 Password? Learn the Best Methods To Unlock | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-system-performance-tackling-high-wudfhostexe-cpu-usage-in-windows-11/"><u>Optimizing System Performance: Tackling High WUDFHost.exe CPU Usage in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/problem-ejecting-usb-mass-storage-device-easy-fixes/"><u>Problem Ejecting USB Mass Storage Device (EASY FIXES)</u></a></li>
<li><a href="https://win11.techidaily.com/resolving-faulty-troubleshooting-tools-in-windows-1011/"><u>Resolving Faulty Troubleshooting Tools in Windows 10/11</u></a></li>
<li><a href="https://video-content-creator.techidaily.com/stream-your-favorite-anime-elsewhere-top-7-options-beyond-crunchyroll/"><u>Stream Your Favorite Anime Elsewhere: Top 7 Options Beyond Crunchyroll</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-for-successfully-handling-loadlibrary-failure-due-to-the-parameter-is-incorrect-error-code-erronous/"><u>Tips for Successfully Handling LoadLibrary Failure Due to 'The Parameter Is Incorrect' Error (Code Erronous)</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-a-non-responsive-logitech-keyboard-under-windows-11-what-to-do/"><u>Trouble with a Non-Responsive Logitech Keyboard Under Windows 11: What to Do?</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-corrupted-files-on-a-windows-11-operating-system/"><u>Troubleshooting and Fixing Corrupted Files on a Windows 11 Operating System</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/unlock-your-poco-m6-pro-4gs-potential-the-top-20-lock-screen-apps-you-need-to-try-by-drfone-android/"><u>Unlock Your Poco M6 Pro 4Gs Potential The Top 20 Lock Screen Apps You Need to Try</u></a></li>
</ul></div>

