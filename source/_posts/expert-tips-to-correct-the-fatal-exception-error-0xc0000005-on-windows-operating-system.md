---
title: Expert Tips to Correct the Fatal Exception Error (0xC0000005) on Windows Operating System
date: 2024-09-08T16:02:42.397Z
updated: 2024-09-15T16:00:41.303Z
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
<li><a href="https://screen-mirroring-recording.techidaily.com/new-grandmaster-gaming-evaluating-the-best-7-total-war-experiences-for-2024/"><u>[New] Grandmaster Gaming Evaluating the Best 7 Total War Experiences for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/new-in-2024-what-is-vimeo-a-peek-at-innovative-content-sharing/"><u>[New] In 2024, What Is Vimeo? A Peek at Innovative Content Sharing</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/new-pinnacle-deskviewers-elite-all-in-one-display-hubs/"><u>[New] Pinnacle DeskViewers Elite All-in-One Display Hubs</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/androids-best-artistic-tools-top-10-creative-graphics-apps/"><u>Android's Best Artistic Tools Top 10 Creative Graphics Apps</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/audience-wow-factor-the-best-camera-lenses-for-youtube-stars-for-2024/"><u>Audience Wow Factor The Best Camera Lenses for YouTube Stars for 2024</u></a></li>
<li><a href="https://facebook.techidaily.com/cultivating-secure-teenage-habits-for-facebook-usage/"><u>Cultivating Secure Teenage Habits for Facebook Usage</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-24-a-step-by-step-solution-for-missing-devices-in-windows-10-8-and-7/"><u>Error Code 24 - A Step-by-Step Solution for Missing Devices in Windows 10, 8 & 7</u></a></li>
<li><a href="https://android-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-from-oneplus-11r-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock from OnePlus 11R Phones with/without a PC</u></a></li>
<li><a href="https://win-amazing.techidaily.com/intel-iris-xe-graphics-drivers-for-windows-11-free-download/"><u>Intel® Iris® XE Graphics Drivers for Windows 11 - Free Download</u></a></li>
<li><a href="https://tech-hub.techidaily.com/mastering-the-art-of-conversation-with-ai-an-introductory-guide-to-chatgpt/"><u>Mastering the Art of Conversation with AI: An Introductory Guide to ChatGPT</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-disabled-wi-fi-functionality-a-comprehensive-guide/"><u>Resolving Issues with Disabled Wi-Fi Functionality: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-print-screen-failure-in-windows-10-and-windows-11-operating-systems/"><u>Resolving Print Screen Failure in Windows 10 and Windows 11 Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/technical-guide-to-optimal-playability-why-your-pc-must-have-a-d3d11-graphics-card-compatibility-to-run-the-engine-flawlessly/"><u>Technical Guide to Optimal Playability: Why Your PC Must Have a D3D11 Graphics Card Compatibility to Run the Engine Flawlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-at-windows-11-essential-tweaks-to-elevate-your-gaming-capabilities/"><u>Winning at Windows 11: Essential Tweaks to Elevate Your Gaming Capabilities</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2136623/26400" target="_top" id="2136623">
  <img src="//a.impactradius-go.com/display-ad/26400-2136623" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2136623/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

