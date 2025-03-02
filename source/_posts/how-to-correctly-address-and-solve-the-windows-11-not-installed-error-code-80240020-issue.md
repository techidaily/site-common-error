---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2025-02-23T05:06:36.338Z
updated: 2025-03-02T14:10:44.445Z
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
<li><a href="https://visual-screen-recording.techidaily.com/new-in-2024-immediate-screen-shotter-for-chromes/"><u>[New] In 2024, Immediate Screen Shotter for Chromes</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-2024-approved-empower-your-digital-tales-with-complimentary-upgrades/"><u>[Updated] 2024 Approved Empower Your Digital Tales with Complimentary Upgrades</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-the-ultimate-noise-free-recording-strategy-for-2024/"><u>[Updated] The Ultimate Noise-Free Recording Strategy for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-reduce-microsofts-compatibility-telemetry-impact-on-hard-drive-space-and-speed-for-windows-10-users/"><u>How to Reduce Microsoft's Compatibility Telemetry Impact on Hard Drive Space and Speed for Windows 10 Users</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-disabling-iphone-6-parental-restrictions-withwithout-password-drfone-by-drfone-ios/"><u>In 2024, Disabling iPhone 6 Parental Restrictions With/Without Password | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-resolving-sluggish-computer-initialization-issues/"><u>Quick Solutions for Resolving Sluggish Computer Initialization Issues</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/rescatar-datos-del-disco-duro-externo-sin-perder-la-configuracion-original-metodos-efectivos/"><u>Rescatar Datos Del Disco Duro Externo Sin Perder La Configuración Original: Métodos Efectivos</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-struggling-with-windows-updates-fix-error-8007000e-instantly-and-happily/"><u>Stop Struggling with Windows Updates! Fix Error 8007000E Instantly & Happily</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-print-driver-host-stopped-working-for-32-bit-software/"><u>Troubleshooting 'Print Driver Host Stopped Working' For 32-Bit Software</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-resolving-issues-with-backspace-functionality/"><u>Troubleshooting Tips: Resolving Issues with Backspace Functionality</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-face-blur-mastery-a-step-by-step-guide-to-free-video-editing-tools/"><u>Updated In 2024, Face Blur Mastery A Step-by-Step Guide to Free Video Editing Tools</u></a></li>
</ul></div>

