---
title: Troubleshooting Steps for Overcoming Black Screens During OBS Captures
date: 2024-11-01T16:26:56.121Z
updated: 2024-11-04T20:08:10.302Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Overcoming Black Screens During OBS Captures
excerpt: This Article Describes Troubleshooting Steps for Overcoming Black Screens During OBS Captures
thumbnail: https://thmb.techidaily.com/443fa3d21137649dff0319f1c3c3070702e32a7b2f673e094959a8fdb4cdbd5b.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

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
<a href="https://aligracehair.sjv.io/c/5597632/1902278/19272" target="_top" id="1902278">
  <img src="//a.impactradius-go.com/display-ad/19272-1902278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902278/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151860/7443" target="_top" id="2151860">
  <img src="//a.impactradius-go.com/display-ad/7443-2151860" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151860/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1934258/19272" target="_top" id="1934258">
  <img src="//a.impactradius-go.com/display-ad/19272-1934258" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1934258/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135375/19272" target="_top" id="2135375">
  <img src="//a.impactradius-go.com/display-ad/19272-2135375" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135375/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-memory-map-maker/"><u>[Updated] 2024 Approved Memory Map Maker</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-in-2024-unmasking-imagerys-origins-a-complete-guide-to-reverse-picture-searching-in-instagram/"><u>[Updated] In 2024, Unmasking Imagery's Origins A Complete Guide to Reverse Picture Searching in Instagram</u></a></li>
<li><a href="https://extra-support.techidaily.com/updated-masterful-date-trackers-for-android-and-ios-wedding-planners/"><u>[Updated] Masterful Date-Trackers for Android and iOS Wedding Planners</u></a></li>
<li><a href="https://driver-error.techidaily.com/boost-hat-performance-update-to-win11-driver/"><u>Boost HAT Performance: Update to Win11 Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-for-fixing-detached-media-devices-on-your-window-computer/"><u>Comprehensive Solutions for Fixing Detached Media Devices on Your Window Computer</u></a></li>
<li><a href="https://win11.techidaily.com/comprehensively-manage-app-packages-with-winget-on-win11/"><u>Comprehensively Manage App Packages with Winget on Win11</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/conversational-cognition-comparison-analyzing-gpt-vs-bingbots-capabilities/"><u>Conversational Cognition Comparison: Analyzing GPT Vs. BingBot's Capabilities</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-freezing-windows-10-system-expert-tips-and-solutions/"><u>How to Fix a Freezing Windows 10 System: Expert Tips and Solutions</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-restore-missing-photos-files-from-infinix-zero-30-5g-by-fonelab-android-recover-photos/"><u>How To Restore Missing Photos Files from Infinix Zero 30 5G.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-nokia-c12-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For Nokia C12 Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://games-able.techidaily.com/navigating-the-premier-vod-extractors-for-streamers-5/"><u>Navigating the Premier VOD Extractors for Streamers #5</u></a></li>
<li><a href="https://common-error.techidaily.com/pwm-alters-pulse-width-while-maintaining-constant-amplitude-and-frequency/"><u>PWM Alters Pulse Width While Maintaining Constant Amplitude and Frequency.</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-restore-corrupt-file-containers-in-windows-11/"><u>Step-by-Step Tutorial: Restore Corrupt File Containers in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/visual-settings-puzzlingly-absent-from-win-1011/"><u>Visual Settings Puzzlingly Absent From Win 10/11</u></a></li>
</ul></div>

