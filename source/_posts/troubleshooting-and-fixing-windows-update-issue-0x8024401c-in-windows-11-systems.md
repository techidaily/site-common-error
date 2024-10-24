---
title: Troubleshooting and Fixing Windows Update Issue 0X8024401c in Windows 11 Systems
date: 2024-10-20T18:27:35.714Z
updated: 2024-10-24T22:17:25.091Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Windows Update Issue 0X8024401c in Windows 11 Systems
excerpt: This Article Describes Troubleshooting and Fixing Windows Update Issue 0X8024401c in Windows 11 Systems
thumbnail: https://thmb.techidaily.com/6befd60c173a5cd8b8d9dfcf598dea7f7e1558ad2a50419820d4a5c540b52039.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/2012429/19272" target="_top" id="2012429">
  <img src="//a.impactradius-go.com/display-ad/19272-2012429" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012429/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://ephamedtechinc.pxf.io/c/5597632/2123509/26400" target="_top" id="2123509">
  <img src="//a.impactradius-go.com/display-ad/26400-2123509" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2123509/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137206/26400" target="_top" id="2137206">
  <img src="//a.impactradius-go.com/display-ad/26400-2137206" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137206/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2141684/17092" target="_top" id="2141684">
  <img src="//a.impactradius-go.com/display-ad/17092-2141684" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://bluettide.pxf.io/i/5597632/2141684/17092" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-achieve-clear-and-smooth-video-outputs-with-these-logitech-camera-insights/"><u>[New] 2024 Approved Achieve Clear & Smooth Video Outputs with These Logitech Camera Insights</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-understanding-and-controlling-safaris-pip-feature/"><u>[Updated] 2024 Approved Understanding and Controlling Safari's PIP Feature</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-how-to-shave-seconds-off-your-youtube-video-submission/"><u>[Updated] How to Shave Seconds Off Your YouTube Video Submission</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/az-screen-recorder-review-series-for-2024/"><u>AZ Screen Recorder Review Series for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/efficient-resource-management-for-windows-11-addressing-msmpengexe-cpu-spikes-resolved/"><u>Efficient Resource Management for Windows 11: Addressing MsMpEng.exe CPU Spikes [RESOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-connection-woes-with-your-ps4-gamepad-practical-methods-and-strategies/"><u>Fixing Connection Woes with Your PS4 Gamepad: Practical Methods & Strategies</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-remove-or-bypass-knox-enrollment-service-on-oneplus-ace-2-pro-by-drfone-android/"><u>How To Remove or Bypass Knox Enrollment Service On OnePlus Ace 2 Pro</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/new-2024-approved-revealed-the-5-superior-mac-compatible-audio-mixers/"><u>New 2024 Approved Revealed The 5 Superior Mac-Compatible Audio Mixers</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fix-tips-navigate-past-windows-error-code-0x887a0006-effortlessly/"><u>Quick-Fix Tips: Navigate Past Windows Error Code 0X887A0006 Effortlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/silent-no-more-effective-techniques-to-resolve-netflix-audio-issues/"><u>Silent No More: Effective Techniques to Resolve Netflix Audio Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-device-drivers-not-found-error-in-windows-7/"><u>Step-by-Step Solution for 'Device Drivers Not Found' Error in Windows 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-complete-solutions-for-the-0x800705b4-problem-during-a-windows-10-upgrade/"><u>Troubleshooting Complete Solutions for the 0X800705b4 Problem During a Windows 10 Upgrade</u></a></li>
<li><a href="https://win-lab.techidaily.com/trp-mp4-online-movavi/"><u>TRP MP4 영상을 쉽게 오늘 무료로 Online 전환: Movavi</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-your-pcs-persistent-freezing-problem/"><u>Ultimate Guide: Resolving Your PC's Persistent Freezing Problem</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/vivo-y27-4g-adb-format-tool-for-pc-vs-other-unlocking-tools-which-one-is-the-best-by-drfone-android/"><u>Vivo Y27 4G ADB Format Tool for PC vs. Other Unlocking Tools Which One is the Best?</u></a></li>
</ul></div>

