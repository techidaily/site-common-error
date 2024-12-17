---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2024-12-15T21:12:43.195Z
updated: 2024-12-16T20:54:12.659Z
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

  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/KdpTAZ9zonQ?si=5Nd5SPW1axA7GPuB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## **Fix One. Rename the WindowsApps folder in Safe Mode**

1)  

Boot your Windows 10 into safe mode:  
How to:  
a)  
Open run dialog box by pressing**Windows** key + **R** key together.  
Then type **msconfig** in the box and hit **Enter**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/2-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1CdWd06fCwc?si=wzg-68q0jAksPRXp" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/BmegThMdrJE?si=rILo1FJb9DgnPljV" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XoC2TGp1PLY?si=iH9xs76NhWn4pP-E" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-content.techidaily.com/new-fundamentals-of-creating-persuasive-social-media-messages/"><u>[New] Fundamentals of Creating Persuasive Social Media Messages</u></a></li>
<li><a href="https://article-tips.techidaily.com/new-in-2024-top-vr-gloves-to-check-out/"><u>[New] In 2024, Top VR Gloves to Check Out</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-master-the-art-of-gaming-best-monitors-and-tvs-for-xbox-series-x/"><u>[New] Master the Art of Gaming Best Monitors & TVs For Xbox Series X</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-expert-techniques-for-streaming-facebook-live-2023/"><u>[Updated] Expert Techniques for Streaming Facebook Live, 2023</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-professional-filmmaking-essentials-ideal-lenses-to-consider/"><u>[Updated] Professional Filmmaking Essentials Ideal Lenses to Consider</u></a></li>
<li><a href="https://win-manuals.techidaily.com/easy-tech-advice-how-to-refresh-windows-with-help-from-yl-software-experts/"><u>Easy Tech Advice: How To Refresh Windows With Help From YL Software Experts</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-mac-camera-not-working-the-easy-way/"><u>Fix Mac Camera Not Working - The Easy Way</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-casting-issues-between-your-devices-on-windows-11/"><u>How to Fix Casting Issues Between Your Devices on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-computer-not-shutting-down-on-windows-11-solutions/"><u>How to Fix Computer Not Shutting Down on Windows 11 - Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/mitigate-resource-misuse-by-wmis/"><u>Mitigate Resource Misuse by WMIs</u></a></li>
<li><a href="https://extra-support.techidaily.com/overcoming-handheld-vibration-secure-your-gopro-movies-for-2024/"><u>Overcoming Handheld Vibration Secure Your GoPro Movies for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/successful-fix-for-video-player-error-message-error-code-224003/"><u>Successful Fix for Video Player Error Message - Error Code 224003</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/the-dos-and-donts-of-youtube-videos-on-twitter/"><u>The Dos and Don'ts of YouTube Videos on Twitter</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/tidy-up-your-pictures-top-10-online-unblur-tools/"><u>Tidy Up Your Pictures Top 10 Online Unblur Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204262425-trouble-with-windows-10-version-1607s-new-features-heres-how-to-fix-it/"><u>Trouble with Windows 10 Version 1607'S New Features? Here's How to Fix It!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-connection-issues-with-your-bluetooth-keyboard-and-computer/"><u>Troubleshooting Guide: Resolving Connection Issues with Your Bluetooth Keyboard and Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-activating-disabled-hosted-wi-fi-networks-on-windows-10/"><u>Troubleshooting Steps for Activating Disabled Hosted Wi-Fi Networks on Windows 10</u></a></li>
</ul></div>

