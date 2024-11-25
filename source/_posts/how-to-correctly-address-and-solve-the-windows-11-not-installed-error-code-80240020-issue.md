---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2024-11-18T20:28:52.511Z
updated: 2024-11-24T20:19:09.616Z
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/rdNq2Sp031s?si=3FcJa3dQLraUDHKv&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/cDNwgyE0nbY?si=3k_WBhpIw3WudJot&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/T-ssCD10v2M?si=WVWGNayUiCAkMZzZ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/X4q6gyaEojM?si=ImdFm6Zsr0azykqV&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/S3Th6oa_isA?si=TTQ013BB9beUM4x6&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://vp-tips.techidaily.com/updated-free-frameworks-for-every-movie-epilogue-you-dream/"><u>[Updated] Free Frameworks for Every Movie Epilogue You Dream</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-in-2024-best-eight-high-res-cinematography-systems/"><u>[Updated] In 2024, Best Eight High-Res Cinematography Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/10plus-video-presentation-ideas-to-delight-your-audience/"><u>10+ Video Presentation Ideas to Delight Your Audience</u></a></li>
<li><a href="https://some-approaches.techidaily.com/2024-approved-the-ultimate-list-of-twitter-video-convertors/"><u>2024 Approved The Ultimate List of Twitter Video Convertors</u></a></li>
<li><a href="https://driver-download.techidaily.com/easy-access-to-canon-mx340-printer-drivers-for-recent-windows-versions-windows-1187-downloads-here/"><u>Easy Access to Canon MX340 Printer Drivers for Recent Windows Versions - Windows 11/8/7 Downloads Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-no-playable-source-errors-in-windows-media-player-complete-guide/"><u>Fixing 'No Playable Source' Errors in Windows Media Player - Complete Guide</u></a></li>
<li><a href="https://driver-download.techidaily.com/1722978607292-get-the-newest-geforce-rtx-3080-ti-drivers-for-windows-11-8-and-7-now/"><u>Get the Newest GeForce RTX 지도 3080 Ti Drivers for Windows 11, 8 & 7 Now!</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-find-ispoofer-pro-activation-key-on-vivo-y78plus-t1-edition-drfone-by-drfone-virtual-android/"><u>How to Find iSpoofer Pro Activation Key On Vivo Y78+ (T1) Edition? | Dr.fone</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-nokia-c12-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Nokia C12 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/navigating-and-solving-the-infamous-windows-update-hurdle-code-0x800705b4-in-windows-11/"><u>Navigating and Solving the Infamous Windows Update Hurdle: Code 0X800705B4 in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-stuck-hard-drive-challenges-on-windows-11-easy-fix-solutions-revealed/"><u>Overcoming Stuck Hard Drive Challenges on Windows 11: Easy Fix Solutions Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-windows-11-blue-screen-dilemma-a-comprehensive-guide/"><u>Solving the Windows 11 Blue Screen Dilemma - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-function-key-issues-on-an-asus-laptop/"><u>Troubleshooting & Fixing Function Key Issues on an ASUS Laptop</u></a></li>
<li><a href="https://win-hot.techidaily.com/windows-11c3/"><u>Windows 11でCドライブ空き容量を増やすための3つの最も簡単な方法</u></a></li>
</ul></div>

