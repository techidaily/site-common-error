---
title: "Origin Gaming Error Solutions: Correcting Setup Problems Smoothly"
date: 2024-10-07T17:29:30.500Z
updated: 2024-10-13T01:28:07.645Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Origin Gaming Error Solutions: Correcting Setup Problems Smoothly"
excerpt: "This Article Describes Origin Gaming Error Solutions: Correcting Setup Problems Smoothly"
thumbnail: https://thmb.techidaily.com/5a47a6a0d1daec39c5712eb645e3012dacc86a9be39fe69eb45844425e13837c.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2094428/7443" target="_top" id="2094428">
  <img src="//a.impactradius-go.com/display-ad/7443-2094428" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094428/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://25home.pxf.io/c/5597632/2148634/16836" target="_top" id="2148634">
  <img src="//a.impactradius-go.com/display-ad/16836-2148634" border="0" alt="https://techidaily.com" width="80" height="31"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148634/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<span id="1975648">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975648.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975648">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975648.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975648%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975648/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043603/7443" target="_top" id="2043603">
  <img src="//a.impactradius-go.com/display-ad/7443-2043603" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043603/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-tips.techidaily.com/iscover-leading-fonts-boosting-your-youtube-thumbnails/"><u>[New] Discover Leading Fonts Boosting Your YouTube Thumbnails</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-the-ultimate-playbook-for-earning-via-youtube-shorts/"><u>[New] In 2024, The Ultimate Playbook for Earning via YouTube Shorts</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-netflix-black-screen-problem/"><u>[Solved] Netflix Black Screen Problem</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-master-your-audio-recordings-5-expert-methods-online-for-2024/"><u>[Updated] Master Your Audio Recordings 5 Expert Methods Online for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-quick-tips-efficiently-upload-windows-video-projects-to-vimeo-for-2024/"><u>[Updated] Quick Tips Efficiently Upload Windows Video Projects to Vimeo for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/a-comprehensive-guide-to-mitigating-svchostexe-network-overload-issues/"><u>A Comprehensive Guide to Mitigating Svchost.exe Network Overload Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/bluetooth-connection-problems-in-windows-10-heres-how-to-fix-them/"><u>Bluetooth Connection Problems in Windows 10? Here's How to Fix Them</u></a></li>
<li><a href="https://common-error.techidaily.com/conquering-the-challenge-easy-solutions-for-overcoming-windows-update-error-0x8024402c/"><u>Conquering the Challenge: Easy Solutions for Overcoming Windows Update Error 0X8024402c</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-remove-forgotten-pin-of-your-huawei-p60-by-drfone-android/"><u>How to Remove Forgotten PIN Of Your Huawei P60</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transform-viewership-elevate-your-live-stream-game-with-just-a-few-supporters/"><u>In 2024, Transform Viewership Elevate Your Live Stream Game with Just a Few Supporters</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-unlocking-the-power-of-smart-lock-a-beginners-guide-for-motorola-g54-5g-users-by-drfone-android/"><u>In 2024, Unlocking the Power of Smart Lock A Beginners Guide for Motorola G54 5G Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-the-semaphore-timeout-exceeded-error-code-0x80070079/"><u>Resolved: Fixing the 'Semaphore Timeout Exceeded' Error Code 0X80070079</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210424449-resolving-no-response-from-your-dns-server-try-these-top-4-tips/"><u>Resolving No-Response From Your DNS Server? Try These Top 4 Tips</u></a></li>
</ul></div>

