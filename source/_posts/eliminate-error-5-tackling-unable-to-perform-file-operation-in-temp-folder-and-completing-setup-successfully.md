---
title: Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully
date: 2025-01-19T17:56:34.614Z
updated: 2025-01-22T18:37:28.843Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully
excerpt: This Article Describes Eliminate Error 5 - Tackling 'Unable to Perform File Operation' In Temp Folder and Completing Setup Successfully
thumbnail: https://thmb.techidaily.com/ac1dc93632b498eb9e341774978ceeb78bceacaece80212cfc98f386a6cd1281.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/htnQWyEOCgc?si=fy86hi8_hTtbWAnw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qmQjRcnaq9g?si=jadcGtXemUAlKOTa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uV3vm805eX0?si=YSPcsFxBcJmoxLsU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/mMYEK2gtY5c?si=ytxNz_JHZkTrwb4b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oeSN3u4fO9M?si=Ua3Hzcil6u6akDgY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://win-amazing.techidaily.com/1722969424348-effortless-driver-installation-guide-for-hewlett-packard-computers/"><u>Effortless Driver Installation Guide for Hewlett-Packard Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-guide-to-navigating-windows-10s-file-explorer/"><u>Effortless Guide to Navigating Windows 10'S File Explorer</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/essential-mac-screen-recorder-alternatives-to-bandicam-for-2024/"><u>Essential Mac Screen Recorder Alternatives to Bandicam for 2024</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/exploring-technology-with-tom-in-depth-analysis-of-hardware-solutions/"><u>Exploring Technology with Tom: In-Depth Analysis of Hardware Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-correcting-class-registration-failures-on-windows-11-systems/"><u>Guide to Correcting Class Registration Failures on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-i-eliminated-skyrims-eternal-load-screens-forever-guide/"><u>How I Eliminated Skyrim's Eternal Load Screens Forever (Guide)</u></a></li>
<li><a href="https://review-topics.techidaily.com/how-to-upgrade-or-downgrade-iphone-15-plus-without-losing-anything-drfone-by-drfone-ios-system-repair-ios-system-repair/"><u>How To Upgrade or Downgrade iPhone 15 Plus Without Losing Anything? | Dr.fone</u></a></li>
<li><a href="https://extra-skills.techidaily.com/jump-into-gaming-evolution-explore-lgs-27ud68-monitor-for-2024/"><u>Jump Into Gaming Evolution Explore LG's 27UD68 Monitor for 2024</u></a></li>
<li><a href="https://extra-support.techidaily.com/revolutionizing-cinematography-with-advanced-3d-luts-for-2024/"><u>Revolutionizing Cinematography with Advanced 3D LUTs for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/simplified-steps-to-documenting-fb-chats-and-calls/"><u>Simplified Steps to Documenting FB Chats and Calls</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-broken-keys-on-a-laptop-under-windows-operating-systems/"><u>Step-by-Step Guide to Restoring Broken Keys on a Laptop Under Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/upgraded-system-how-to-enable-directx-11-on-incompatible-gpu/"><u>Upgraded System: How To Enable DirectX 11 on Incompatible GPU</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-file-explorer-scroll-bar-jumps-to-top-when-scrolling-solved/"><u>Windows 11 File Explorer - Scroll Bar Jumps to Top when Scrolling [Solved]</u></a></li>
</ul></div>

