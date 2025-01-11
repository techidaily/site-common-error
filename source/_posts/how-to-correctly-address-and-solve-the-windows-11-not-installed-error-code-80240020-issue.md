---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2025-01-09T18:14:18.911Z
updated: 2025-01-10T23:39:12.341Z
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
  

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/JMgRzDANfSQ?si=NDy01ntXGGOi1Uxs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/oySc0DiqmKc?si=8pynRzuhlq2RUPZ6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fqBKCGAKHmA?si=OkoaI17nE5qNqTHj" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hXIq2G0nShk?si=5Z4Fwv7ZB6oKWsdd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://facebook-video-footage.techidaily.com/new-2024-approved-bulk-buy-subscribers-cost-effective-growth-strategy/"><u>[New] 2024 Approved Bulk Buy Subscribers Cost-Effective Growth Strategy</u></a></li>
<li><a href="https://fox-http.techidaily.com/updated-2024-approved-fast-track-your-mobile-vids-with-these-tools/"><u>[Updated] 2024 Approved Fast-Track Your Mobile Vids with These Tools</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/2024-approved-harmonizing-visuals-and-sound-in-instagram-videos/"><u>2024 Approved Harmonizing Visuals & Sound in Instagram Videos</u></a></li>
<li><a href="https://tech-revival.techidaily.com/debunking-7-myths-ai-in-text-conversations/"><u>Debunking 7 Myths: AI in Text Conversations</u></a></li>
<li><a href="https://common-error.techidaily.com/enabling-fortnite-on-non-compatible-graphics-cards-in-the-windows-environment-workarounds-and-tweaks/"><u>Enabling Fortnite on Non-Compatible Graphics Cards in the Windows Environment – Workarounds and Tweaks</u></a></li>
<li><a href="https://common-error.techidaily.com/hamachi-trouble-heres-how-you-can-fix-a-stopped-service-error/"><u>Hamachi Trouble? Here's How You Can Fix a Stopped Service Error</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-a-display-driver-that-stopped-then-came-back-online/"><u>How to Troubleshoot a Display Driver That Stopped Then Came Back Online</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-best-3-software-to-transfer-files-tofrom-your-vivo-x100-via-a-usb-cable-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Best 3 Software to Transfer Files to/from Your Vivo X100 via a USB Cable | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-how-to-unlock-a-xiaomi-14-easily-by-drfone-android/"><u>In 2024, How To Unlock a Xiaomi 14 Easily?</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-in-2024-so-without-wasting-time-let-me-show-you-how-to-mask-a-video-in-wondershare-filmora-lets-get-started/"><u>New In 2024, So, without Wasting Time, Let Me Show You How to Mask a Video in Wondershare Filmora. Lets Get Started</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/new-revealing-translation-methods-netflix-subtitle-software-comprehensive-guide-for-2024/"><u>New Revealing Translation Methods Netflix Subtitle Software Comprehensive Guide for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/patched-pubgs-dxgidll-hiccup-with-ease/"><u>Patched PUBG's Dxgi.dll Hiccup with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-windows-10-that-wont-properly-shut-down-and-reopens-instead/"><u>Resolving Issues with Windows 10 that Won't Properly Shut Down and Reopens Instead</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-addressing-challenges-in-directx-visual-processing-unit-creation-failures/"><u>Solution Guide: Addressing Challenges in DirectX Visual Processing Unit Creation Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-an-unresponsive-hp-touchpad-a-step-by-step-guide/"><u>Troubleshooting an Unresponsive HP Touchpad: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-laptop-mic-issues-a-comprehensive-guide/"><u>Troubleshooting and Repairing Laptop Mic Issues: A Comprehensive Guide</u></a></li>
<li><a href="https://win-latest.techidaily.com/ultimate-diy-tutorial-on-building-your-own-live-tv-streaming-system/"><u>Ultimate DIY Tutorial on Building Your Own Live TV Streaming System</u></a></li>
</ul></div>

