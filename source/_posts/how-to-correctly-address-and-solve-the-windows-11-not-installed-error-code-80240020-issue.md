---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2024-12-23T16:03:58.326Z
updated: 2024-12-25T20:07:43.273Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
excerpt: This Article Describes How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
thumbnail: https://thmb.techidaily.com/995d8276c073ea6830ba619ba4614fd047fc0375a4d1ae8bef82547a42248f63.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/UJJbj1vbzs8?si=X3zd8thLJKprfuEa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/c17xsnbinCQ?si=xHKslFgC3QbxY4qW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/RCYs8keh-Vs?si=uDC28-9yh-k6HLj4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-techniques.techidaily.com/new-fasttrackpodcastlive-your-straightforward-guide-to-livestreaming-success/"><u>[New] FastTrackPodcastLive Your Straightforward Guide to Livestreaming Success</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-understanding-the-shift-navigating-posting-in-an-algorithm-world/"><u>[New] Understanding the Shift Navigating Posting in an Algorithm World</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-beginner-friendly-steps-to-record-your-mac-display/"><u>[Updated] 2024 Approved Beginner-Friendly Steps to Record Your Mac Display</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-ultimate-phone-and-camera-mounts-precision-focus-tracking/"><u>2024 Approved Ultimate Phone & Camera Mounts Precision Focus Tracking</u></a></li>
<li><a href="https://common-error.techidaily.com/eclipse-of-vision-screen-phenomenon/"><u>Eclipse of Vision: Screen Phenomenon</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211280401-how-to-fix-hosted-network-cant-be-started-error-in-windows-11-solved/"><u>How to Fix 'Hosted Network Can't Be Started' Error in Windows 11 - Solved</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-play-avchd-mts-files-on-samsung-by-aiseesoft-video-converter-play-mts-on-android/"><u>How to play AVCHD MTS files on Samsung ?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-minecraft-game-stalling-overcome-error-code-amartz/"><u>How to Repair Minecraft Game Stalling - Overcome Error Code Amartz</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/how-to-restart-your-ps4-after-safe-mode-activation-a-comprehensive-guide/"><u>How to Restart Your PS4 After Safe Mode Activation – A Comprehensive Guide</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-capture-crop-and-color-correct-with-this-lists-top-5-android-apps/"><u>In 2024, Capture, Crop, and Color-Correct with This List's Top 5 Android Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-microsoft-outlooks-mysterious-error-your-step-by-step-guide-for-solving-unspecified-error-0x8004005/"><u>Overcoming Microsoft Outlook's Mysterious Error: Your Step-by-Step Guide for Solving Unspecified Error 0X800#4005</u></a></li>
<li><a href="https://win11.techidaily.com/strategies-for-effective-household-budget-planning-using-microsoft-excel/"><u>Strategies for Effective Household Budget Planning Using Microsoft Excel</u></a></li>
<li><a href="https://solve-helper.techidaily.com/top-intelligent-document-management-suite-revolutionizes-with-advanced-intelligence-features/"><u>Top Intelligent Document Management Suite Revolutionizes with Advanced Intelligence Features</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-common-opengl-issues-in-minecraft/"><u>Ultimate Guide: Solving Common OpenGL Issues in Minecraft</u></a></li>
</ul></div>

