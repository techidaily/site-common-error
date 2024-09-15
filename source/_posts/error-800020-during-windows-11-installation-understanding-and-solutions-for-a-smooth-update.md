---
title: "Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update"
date: 2024-09-09T16:02:00.205Z
updated: 2024-09-15T16:02:39.032Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update"
excerpt: "This Article Describes Error 80#0020 During Windows 11 Installation: Understanding and Solutions for a Smooth Update"
thumbnail: https://thmb.techidaily.com/dce6bc9a112b3f049356452f785b8eb72027385ba75d849bd9c5cf60929a80d0.png
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-meet-your-new-record-keeping-companion-the-mycam-cam/"><u>[New] 2024 Approved Meet Your New Record-Keeping Companion The MyCam Cam</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/new-initiating-engagement-start-your-live-on-instagram-for-2024/"><u>[New] Initiating Engagement Start Your Live on Instagram for 2024</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-live-streaming-on-mac-os-costless-option/"><u>[New] Live Streaming on Mac OS - Costless Option</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-unlock-the-potential-of-your-camera-creating-stunning-slow-motion-videos-for-instagram-for-2024/"><u>[New] Unlock the Potential of Your Camera Creating Stunning Slow-Motion Videos for Instagram for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-2024-approved-optimal-obs-configuration-for-budget-pcs/"><u>[Updated] 2024 Approved Optimal OBS Configuration for Budget PCs</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-discover-effortless-pathways-to-dynamic-snaps-for-2024/"><u>[Updated] Discover Effortless Pathways to Dynamic Snaps for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-eliminating-crackling-sounds-from-native-windows-media-center-sound-system/"><u>Diagnosing and Eliminating Crackling Sounds From Native Windows Media Center Sound System</u></a></li>
<li><a href="https://tech-haven.techidaily.com/essential-guide-to-understanding-ai-vocabulary-mastering-29-crucial-terms/"><u>Essential Guide to Understanding AI Vocabulary: Mastering 29 Crucial Terms</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212143161-experience-uninterrupted-updates-on-windows-11-solve-error-code-0x800f0922-using-our-top-fixes/"><u>Experience Uninterrupted Updates on Windows 11: Solve ERROR CODE 0X800F0922 Using Our Top Fixes</u></a></li>
<li><a href="https://blue-screen-error.techidaily.com/fix-volsnapsys-bsod-issues-and-prevent-blue-screen-crashes-on-your-windows-pc/"><u>Fix Volsnap.sys BSOD Issues & Prevent Blue Screen Crashes on Your Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-your-internet-explorer-running-smoothly-again/"><u>How To Get Your Internet Explorer Running Smoothly Again</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-universal-unlock-pattern-for-infinix-note-30-vip-racing-edition-by-drfone-android/"><u>In 2024, Universal Unlock Pattern for Infinix Note 30 VIP Racing Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-fixes-for-the-elusive-error-in-windows-installer-services/"><u>Mastering Fixes for the Elusive Error in Windows Installer Services</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-common-huion-pen-issues-quickly-5-proven-fixes-for-smoother-drawing/"><u>Solve Common Huion Pen Issues Quickly – 5 Proven Fixes for Smoother Drawing</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-to-combat-high-resource-drain-caused-by-wudfhostexe-on-windows-10-systems/"><u>Tips to Combat High Resource Drain Caused by WUDFHost.exe on Windows 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-resolving-minecrafts-opengl-issues-step-by-step-solutions/"><u>Ultimate Guide: Resolving Minecraft's OpenGL Issues - Step by Step Solutions</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2120861/26400?prodsku=Saturn" target="_top" id="2120861">
  <img src="//a.impactradius-go.com/display-ad/26400-2120861" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2120861/26400?prodsku=Saturn" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

