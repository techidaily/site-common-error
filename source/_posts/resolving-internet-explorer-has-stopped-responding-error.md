---
title: Resolving 'Internet Explorer Has Stopped Responding' Error
date: 2024-10-18T05:26:03.226Z
updated: 2024-10-18T18:45:43.939Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving 'Internet Explorer Has Stopped Responding' Error
excerpt: This Article Describes Resolving 'Internet Explorer Has Stopped Responding' Error
thumbnail: https://thmb.techidaily.com/ee671cfb7ee587015883db0a3fbeb82905b8663f1657e5b249344fa4f87d839d.jpg
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
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://imp.i357552.net/c/5597632/994842/11832" target="_top" id="994842">
  <img src="//a.impactradius-go.com/display-ad/11832-994842" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/994842/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2148619/17108" target="_top" id="2148619">
  <img src="//a.impactradius-go.com/display-ad/17108-2148619" border="0" alt="https://techidaily.com" width="100" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2148619/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105870/7443" target="_top" id="2105870">
  <img src="//a.impactradius-go.com/display-ad/7443-2105870" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105870/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-access.techidaily.com/new-2024-approved-navigating-the-smm-landscape-key-steps-to-success/"><u>[New] 2024 Approved Navigating the SMM Landscape Key Steps to Success</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-the-key-to-successful-multi-view-facebook-streaming/"><u>[New] In 2024, The Key to Successful Multi-View Facebook Streaming</u></a></li>
<li><a href="https://some-approaches.techidaily.com/abbyy-at-cebit-conference-2017-showcasing-innovative-software-solutions/"><u>ABBYY at Cebit Conference 2017 - Showcasing Innovative Software Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassed-common-problems-and-solutions-for-windows-unable-to-link-to-event-service/"><u>Bypassed: Common Problems & Solutions for Windows Unable to Link to Event Service</u></a></li>
<li><a href="https://common-error.techidaily.com/1723203946404-cant-send-your-document-to-print-top-tier-tips-for-quick-solutions/"><u>Can't Send Your Document to Print? Top-Tier Tips for Quick Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-common-issues-with-your-usb-mass-storage-devices-a-step-by-step-guide/"><u>How to Fix Common Issues with Your USB Mass Storage Devices: A Step-by-Step Guide</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/in-2024-flv-video-unification-techniques/"><u>In 2024, FLV Video Unification Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-your-laptops-microphone-woes-tips-fixes-and-prevention-strategies/"><u>Solving Your Laptop's Microphone Woes: Tips, Fixes & Prevention Strategies</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/the-ultimate-guide-to-picking-a-streamer-chromecast-vs-roku-face-off/"><u>The Ultimate Guide to Picking a Streamer: Chromecast vs Roku Face-Off.</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/ways-to-find-unlocking-codes-for-honor-100-pro-phones-by-drfone-android/"><u>Ways To Find Unlocking Codes For Honor 100 Pro Phones</u></a></li>
</ul></div>

