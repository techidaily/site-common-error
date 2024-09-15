---
title: How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11
date: 2024-09-10T03:05:10.187Z
updated: 2024-09-15T09:38:48.633Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11
excerpt: This Article Describes How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11
thumbnail: https://thmb.techidaily.com/13a2ed7d3d473fc4b094f952faefa5141a38181bbb0354fc87e696c7a5f69650.png
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
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
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-elevate-your-social-storytelling-with-added-musicality/"><u>[New] 2024 Approved Elevate Your Social Storytelling with Added Musicality</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-bypassing-influencers-establishing-your-brand-identity-on-tiktok-for-2024/"><u>[Updated] Bypassing Influencers Establishing Your Brand Identity on TikTok for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-poco-c55-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Poco C55 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-diagnosing-and-fixing-non-functional-corsair-keyboard-problems/"><u>Expert Advice on Diagnosing and Fixing Non-Functional Corsair Keyboard Problems</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-i-transferred-messages-from-tecno-spark-go-2023-to-iphone-12xs-max-in-seconds-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>How I Transferred Messages from Tecno Spark Go (2023) to iPhone 12/XS (Max) in Seconds | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-fixing-a-non-responsive-laptop-trackpad-on-windows-10-8-and-7/"><u>Solved: Fixing a Non-Responsive Laptop Trackpad on Windows 10, 8 & 7</u></a></li>
<li><a href="https://extra-tips.techidaily.com/time-tagging-in-picture-editing-software/"><u>Time Tagging in Picture Editing Software</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-0x80240034-glitch-in-windows-11-updates-effective-strategies-for-success/"><u>Troubleshooting the 0X80240034 Glitch in Windows 11 Updates – Effective Strategies for Success</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115909/19272" target="_top" id="2115909">
  <img src="//a.impactradius-go.com/display-ad/19272-2115909" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115909/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

