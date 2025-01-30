---
title: "Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079"
date: 2025-01-28T17:05:40.909Z
updated: 2025-01-30T08:25:19.215Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079"
excerpt: "This Article Describes Troubleshooting Guide: Resolving the 'Semaphore Timed Out' Error Code 0X80070079"
thumbnail: https://thmb.techidaily.com/24b4a5d68fd5e6bea75410f8f6c4c82cdd5bcbea33115cb8218e3e0a99c10ef2.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/o-sRtqHdEYY?si=NMTMQVxJsUaoguqh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/ZLb1ViO4WR8?si=g_aiHGNCd7eAvmDM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/uzb-0C0xUYA?si=F4MPhdVqyVgx7_8X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/3UyJuZYzjt0?si=W87GeyzVKVORAk7S" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  
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
<li><a href="https://fox-hovers.techidaily.com/new-comprehensive-motion-dynamics-synopsis-for-2024/"><u>[New] Comprehensive Motion Dynamics Synopsis for 2024</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-2024-approved-game-testers-and-beta-gamers-online/"><u>[Updated] 2024 Approved Game Testers & Beta Gamers Online</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-tips-for-optimizing-facebooks-auto-play-videos/"><u>[Updated] Tips for Optimizing Facebook's Auto-Play Videos</u></a></li>
<li><a href="https://some-tips.techidaily.com/envisioning-tomorrow-how-apples-innovative-robotic-aide-could-transform-homes/"><u>Envisioning Tomorrow: How Apple's Innovative Robotic Aide Could Transform Homes</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-get-and-use-pokemon-go-promo-codes-on-vivo-v30-drfone-by-drfone-virtual-android/"><u>How to Get and Use Pokemon Go Promo Codes On Vivo V30 | Dr.fone</u></a></li>
<li><a href="https://sound-issues.techidaily.com/how-to-resolve-crackling-noise-problems-in-your-cyberpunk-2077-audio-setup/"><u>How to Resolve Crackling Noise Problems in Your Cyberpunk 2077 Audio Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/how-we-overcame-the-windows-updates-issues-solutions-applied/"><u>How We Overcame the Windows Updates Issues – Solutions Applied</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-pcs-function-keys-a-step-by-step-guide-for-quick-fixes/"><u>Reviving Your PC’s Function Keys: A Step-by-Step Guide for Quick Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-a-non-responsive-shift-key-on-your-computer/"><u>Troubleshoot & Fix a Non-Responsive Shift Key on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-how-to-switch-on-bluetooth-for-windows-7-devices/"><u>Troubleshooting and Fixing: How to Switch On Bluetooth for Windows 7 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206850703-windows-11-usb-port-problems-heres-how-you-can-fix-them-easily/"><u>Windows 11 USB Port Problems? Here's How You Can Fix Them Easily!</u></a></li>
</ul></div>

