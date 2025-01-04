---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2024-12-28T16:27:39.488Z
updated: 2025-01-04T00:12:12.519Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/bofw6eJA7Bg?si=HM2gKZGH4L1otw3e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/lxv4NM-89CU?si=Uj5rOkhrwZ_6QIuW" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-web.techidaily.com/aute-couture-at-home-makeup-tools-and-techniques-for-2024/"><u>[New] Haute Couture at Home Makeup, Tools & Techniques for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-in-2024-efficient-scheduling-techniques-for-effective-google-meeting/"><u>[New] In 2024, Efficient Scheduling Techniques for Effective Google Meeting</u></a></li>
<li><a href="https://common-error.techidaily.com/asus-laptops-resolving-stuck-or-malfunctioning-function-fn-keys-problems/"><u>ASUS Laptops: Resolving Stuck or Malfunctioning Function (Fn) Keys Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-fixes-for-when-your-windows-11-mouse-cant-right-click/"><u>Easy Fixes for When Your Windows 11 Mouse Can't Right-Click</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-windows-1110-endless-reboot-loop-solutions-unveiled/"><u>Fixes for Windows 11/10 Endless Reboot Loop: Solutions Unveiled</u></a></li>
<li><a href="https://android-frp.techidaily.com/hassle-free-ways-to-remove-frp-lock-from-oppo-reno-8t-5g-phones-withwithout-a-pc-by-drfone-android/"><u>Hassle-Free Ways to Remove FRP Lock from Oppo Reno 8T 5G Phones with/without a PC</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-bypass-android-lock-screen-using-emergency-call-on-motorola-moto-g14-by-drfone-android/"><u>How to Bypass Android Lock Screen Using Emergency Call On Motorola Moto G14?</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-10-best-fake-gps-location-spoofers-for-vivo-x-fold-2-drfone-by-drfone-virtual-android/"><u>In 2024, 10 Best Fake GPS Location Spoofers for Vivo X Fold 2 | Dr.fone</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-3-solutions-to-find-your-motorola-moto-g34-5g-current-location-of-a-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, 3 Solutions to Find Your Motorola Moto G34 5G Current Location of a Mobile Number | Dr.fone</u></a></li>
<li><a href="https://techidaily.com/recover-apple-iphone-8-data-from-itunes-backup-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>Recover Apple iPhone 8 Data From iTunes Backup | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-the-ultimate-guide-to-resolving-issues-with-your-corsair-hs50-microphone/"><u>Troubleshooting and Fixing: The Ultimate Guide to Resolving Issues with Your Corsair HS50 Microphone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-what-to-do-if-your-torrent-download-fails/"><u>Troubleshooting Steps: What to Do If Your Torrent Download Fails?</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-woes-effective-solutions-for-error-code-0xc0000098/"><u>Winning Against Windows Woes: Effective Solutions for Error Code 0Xc0000098</u></a></li>
</ul></div>

