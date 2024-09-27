---
title: "Troubleshooting: How to Resolve Unsupported Platform Error During Intel Serial IO Driver Setup"
date: 2024-09-22T17:17:23.206Z
updated: 2024-09-26T17:52:03.829Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: How to Resolve Unsupported Platform Error During Intel Serial IO Driver Setup"
excerpt: "This Article Describes Troubleshooting: How to Resolve Unsupported Platform Error During Intel Serial IO Driver Setup"
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2111981/7443" target="_top" id="2111981">
  <img src="//a.impactradius-go.com/display-ad/7443-2111981" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2111981/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/1997717/19272" target="_top" id="1997717">
  <img src="//a.impactradius-go.com/display-ad/19272-1997717" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997717/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1997635/19272" target="_top" id="1997635">
  <img src="//a.impactradius-go.com/display-ad/19272-1997635" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1997635/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://common-error.techidaily.com/fixed-high-cpu-usage-by-wudfhostexe-in-windows-11/"><u>[FIXED] High CPU Usage by WUDFHost.exe in Windows 11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/new-in-2024-12-best-vlogging-cameras-with-a-flip-screen/"><u>[New] In 2024, 12 Best Vlogging Cameras with a Flip Screen</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-2024-approved-cutting-edge-mac-hd-screen-and-sound-mastery/"><u>[Updated] 2024 Approved Cutting-Edge Mac HD Screen and Sound Mastery</u></a></li>
<li><a href="https://some-guidance.techidaily.com/effective-methods-to-correct-memory-system-faults-in-windows-11-a-step-by-step-guide/"><u>Effective Methods to Correct Memory System Faults in Windows 11: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-methods-to-rectify-loading-errors-on-the-steam-platform/"><u>Effective Methods to Rectify Loading Errors on the Steam Platform</u></a></li>
<li><a href="https://tech-revival.techidaily.com/exploring-the-pros-and-cons-of-apples-imac-with-a-5k-retina-display-comprehensive-guide/"><u>Exploring the Pros & Cons of Apple's iMac with a 5K Retina Display: Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-the-best-out-of-your-touchscreen-essential-tips-for-windows-10-users/"><u>Getting the Best Out of Your Touchscreen: Essential Tips for Windows 10 Users</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-poco-m6-pro-4g-in-5-easy-ways-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Poco M6 Pro 4G in 5 Easy Ways | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/in-2024-asus-proart-review-pushing-boundaries-in-color-accuracy/"><u>In 2024, ASUS ProArt Review Pushing Boundaries in Color Accuracy</u></a></li>
<li><a href="https://fox-links.techidaily.com/in-2024-streaming-software-showdown-the-verdict-on-wirecast-vs-obs/"><u>In 2024, Streaming Software Showdown The Verdict on Wirecast Vs. OBS</u></a></li>
<li><a href="https://win-forum.techidaily.com/mastering-the-art-of-user-profile-removal-in-microsofts-latest-os/"><u>Mastering the Art of User Profile Removal in Microsoft's Latest OS</u></a></li>
<li><a href="https://common-error.techidaily.com/navigate-through-bluetooth-hurdles-a-comprehensive-fix-for-windows-11-users/"><u>Navigate Through Bluetooth Hurdles: A Comprehensive Fix for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-steam-marketplace-connection-issues-a-step-by-step-guide/"><u>Solving Your Steam Marketplace Connection Issues: A Step-by-Step Guide</u></a></li>
</ul></div>

