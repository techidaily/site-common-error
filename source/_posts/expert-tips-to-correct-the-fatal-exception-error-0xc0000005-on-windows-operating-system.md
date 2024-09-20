---
title: Expert Tips to Correct the Fatal Exception Error (0xC0000005) on Windows Operating System
date: 2024-09-16T17:24:55.170Z
updated: 2024-09-20T18:58:41.488Z
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
<li><a href="https://fox-access.techidaily.com/updated-elevate-video-production-excellence-with-kinemasters-green-screen-guide-for-2024/"><u>[Updated] Elevate Video Production Excellence with Kinemaster's Green Screen Guide for 2024</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/command-line-conversations-bash-and-chatgpt/"><u>Command-Line Conversations: Bash and ChatGPT</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-cast-a-windows-desktop-to-a-tv-with-chromecast/"><u>How to Cast a Windows Desktop to a TV With Chromecast</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/how-to-correctly-address-missing-physxloaderdll-files-in-windows/"><u>How to Correctly Address Missing PhysXLoader.dll Files in Windows</u></a></li>
<li><a href="https://win-howtos.techidaily.com/how-to-restore-right-click-capabilities-on-your-windows-10-system/"><u>How to Restore Right-Click Capabilities on Your Windows 10 System</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-stop-my-spouse-from-spying-on-my-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>How to Stop My Spouse from Spying on My Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-your-windows-11-computer-from-randomly-powering-on-by-itself/"><u>How to Stop Your Windows 11 Computer From Randomly Powering On by Itself</u></a></li>
<li><a href="https://common-error.techidaily.com/optimizing-windows-11-how-to-fix-insufficient-memory-warnings/"><u>Optimizing Windows 11 - How to Fix Insufficient Memory Warnings</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-update-unsuccessful-in-warframe-expert-tips-and-tricks/"><u>Resolving 'Update Unsuccessful' In Warframe: Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-ps4-remote-solutions-for-power-charging-issues/"><u>Revive Your PS4 Remote - Solutions for Power-Charging Issues</u></a></li>
<li><a href="https://vp-tips.techidaily.com/step-by-step-guide-activating-movavi-software-on-your-mac/"><u>Step-by-Step Guide: Activating Movavi Software on Your Mac</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-to-get-your-lenovo-camera-up-and-running-again/"><u>Step-by-Step Solutions to Get Your Lenovo Camera Up and Running Again</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-easy-errors-with-apex-legends-anti-cheat-system/"><u>Troubleshooting Easy Errors with Apex Legends Anti-Cheat System</u></a></li>
<li><a href="https://win-amazing.techidaily.com/update-or-install-logitech-brio-camera-drivers-on-your-pc-running-windows-11-8-or-ebx/"><u>Update or Install Logitech BRIO Camera Drivers on Your PC Running Windows 11, 8 or Ebx</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151864/7443" target="_top" id="2151864">
  <img src="//a.impactradius-go.com/display-ad/7443-2151864" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151864/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

