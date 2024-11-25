---
title: Troubleshooting and Fixing the Notorious 0X80072EFD Error in Windows 10
date: 2024-11-18T17:58:21.671Z
updated: 2024-11-25T00:34:49.976Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing the Notorious 0X80072EFD Error in Windows 10
excerpt: This Article Describes Troubleshooting and Fixing the Notorious 0X80072EFD Error in Windows 10
thumbnail: https://thmb.techidaily.com/cb670c879e89656e881160d22473efee38dda114df0401fe96c31b4cf2882857.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/HMuxjTCMX2E?si=ylRTMJuUstpjLsZc&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/DBMTAJBx-X4?si=sje5pFJXiHzJJGbP&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/MHafwnWSEQk?si=rejNVNpJZH2SqNLy&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG&autoplay=1" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://instagram-video-files.techidaily.com/new-2024-approved-peeling-layers-to-originality-a-guide-for-instagram-photo-search/"><u>[New] 2024 Approved Peeling Layers to Originality A Guide for Instagram Photo Search</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/hy-youtubes-viewer-numbers-matter-more-than-you-think-for-2024/"><u>[New] Why YouTube's Viewer Numbers Matter More Than You Think for 2024</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-investigating-the-financial-benefits-of-each-youtube-watcher/"><u>[Updated] Investigating the Financial Benefits of Each YouTube Watcher</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-oppo-find-x7-ultra-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Oppo Find X7 Ultra? | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/comparing-mobile-vr-gear-top-10-edition/"><u>Comparing Mobile VR Gear - Top 10 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-non-responsive-razor-board-why-isnt-it-lights/"><u>Fixing a Non-Responsive Razor Board: Why Isn't It Lights?</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205836067-fixing-error-message-0x887a0006-in-no-time-easy-solutions-inside/"><u>Fixing Error Message 0X887A0006 in No Time - Easy Solutions Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-persistent-0x800705b4-error-during-updates-in-windows-11/"><u>Fixing the Persistent 0X800705b4 Error During Updates in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-10-kb4056892-installation-issues-a-comprehensive-guide/"><u>How to Fix Windows 10 KB4056892 Installation Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/24-crafting-the-perfect-schedule-for-jobs-and-youtube/"><u>In 2024, Crafting the Perfect Schedule for Jobs & YouTube</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/in-2024-enlarge-social-media-content-with-televisions/"><u>In 2024, Enlarge Social Media Content with Televisions</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-frp-hijacker-by-hagard-download-and-bypass-your-xiaomi-redmi-a2-frp-locks-by-drfone-android/"><u>In 2024, FRP Hijacker by Hagard Download and Bypass your Xiaomi Redmi A2 FRP Locks</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-change-honor-100-pro-location-on-skout-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Honor 100 Pro Location on Skout | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixes-for-a-nonfunctional-corsair-keyboard/"><u>Resolved: Fixes for a Nonfunctional Corsair Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-how-to-fix-slow-downloads-in-lol-complete-guide/"><u>Resolved: How to Fix Slow Downloads in LoL - Complete Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-microphone-problems-in-the-steelseries-arctis-5-headset-a-comprehensive-guide/"><u>Solving Microphone Problems in the SteelSeries Arctis 5 Headset - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-a-non-functional-astro-a40-microphone-resolved/"><u>Troubleshooting a Non-Functional Astro A40 Microphone - Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-do-if-you-cant-delete-text-a-guide-to-fixing-backspace-issues/"><u>What to Do If You Can't Delete Text – A Guide to Fixing Backspace Issues</u></a></li>
<li><a href="https://win-docs.techidaily.com/1728474303685-windows-11/"><u>Windows 11 重置工作站到出廠狀態的詳細方法</u></a></li>
</ul></div>

