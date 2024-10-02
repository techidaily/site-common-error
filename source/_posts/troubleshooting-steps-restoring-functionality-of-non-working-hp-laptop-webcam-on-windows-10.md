---
title: "Troubleshooting Steps: Restoring Functionality of Non-Working HP Laptop Webcam on Windows 10"
date: 2024-09-27T22:27:42.100Z
updated: 2024-10-01T16:26:11.234Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Steps: Restoring Functionality of Non-Working HP Laptop Webcam on Windows 10"
excerpt: "This Article Describes Troubleshooting Steps: Restoring Functionality of Non-Working HP Laptop Webcam on Windows 10"
thumbnail: https://thmb.techidaily.com/ec364dbb6168e683e422487379a99c7901eeab42baca05e040ad76d70daee8c3.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2130873/7443" target="_top" id="2130873">
  <img src="//a.impactradius-go.com/display-ad/7443-2130873" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2130873/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135412/19272" target="_top" id="2135412">
  <img src="//a.impactradius-go.com/display-ad/19272-2135412" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135412/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997690/19272" target="_top" id="1997690">
  <img src="//a.impactradius-go.com/display-ad/19272-1997690" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997690/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettifr.pxf.io/c/5597632/2145082/17095" target="_top" id="2145082">
  <img src="//a.impactradius-go.com/display-ad/17095-2145082" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettifr.pxf.io/i/5597632/2145082/17095" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-a-compreayers-guide-to-polishing-youtube-content-via-imovie-editing-techniques/"><u>[New] 2024 Approved A Compreayer's Guide to Polishing YouTube Content via iMovie Editing Techniques</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-integrating-websites-into-your-instagram-presence/"><u>[New] 2024 Approved Integrating Websites Into Your Instagram Presence</u></a></li>
<li><a href="https://games-able.techidaily.com/competing-with-precision-in-tetris-showdowns-phone-style/"><u>Competing with Precision in Tetris Showdowns, Phone Style</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-e80240020-explained-solving-the-windows-10-installation-failure/"><u>Error Code E80240020 Explained: Solving the Windows 10 Installation Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcome-constant-windows-11-system-reboots-instantly/"><u>Guide to Overcome Constant Windows 11 System Reboots Instantly</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-fake-snapchat-location-without-jailbreak-on-apple-iphone-7-plus-drfone-by-drfone-virtual-ios/"><u>How to Fake Snapchat Location without Jailbreak On Apple iPhone 7 Plus | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/mastering-document-management-techniques-for-saving-images-from-word-templates/"><u>Mastering Document Management: Techniques for Saving Images From Word Templates</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11s-0x80072efd-error-a-step-by-step-guide/"><u>Resolving Windows 11'S 0X80072EFD Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-overcoming-nvidia-web-helper-errors/"><u>Troubleshooting Guide: Overcoming NVIDIA Web Helper Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-11-endless-loop-re-starts-effective-solutions-for-a-stable-system/"><u>Troubleshooting Windows 11 Endless Loop Re-Starts - Effective Solutions for a Stable System</u></a></li>
<li><a href="https://android-frp.techidaily.com/ultimate-guide-from-lava-yuva-3-frp-bypass-by-drfone-android/"><u>Ultimate Guide from Lava Yuva 3 FRP Bypass</u></a></li>
<li><a href="https://fox-access.techidaily.com/view-surge-secrets-tutorials-audience-triumph/"><u>View Surge Secrets Tutorial's Audience Triumph</u></a></li>
</ul></div>

