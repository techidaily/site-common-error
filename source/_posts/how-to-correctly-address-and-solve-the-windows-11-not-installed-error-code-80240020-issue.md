---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2025-02-07T01:19:19.170Z
updated: 2025-02-10T22:35:56.288Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cKRBWf1EDZo?si=CTNd4q450biit4eM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DCARjc5g5VI?si=9OfovbKBrpoJeXTY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/n4cc4BSqJls?si=Hkd9vwQDqeCGN7XG" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YB7Ou4-iKVM?si=7Fq8iUwI8voccMLx" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

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
<li><a href="https://article-posts.techidaily.com/new-bio-engineered-healing-spaces-via-arvr/"><u>[New] Bio-Engineered Healing Spaces via AR/VR</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-premium-power-supplies-for-gopro-hero5-genuine-and-3rd-party/"><u>[New] Premium Power Supplies for GoPro Hero5 Genuine and 3Rd-Party</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-power-of-listening-understanding-your-youtube-audience-for-2024/"><u>[New] The Power of Listening Understanding Your YouTube Audience for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-unveiling-the-top-gopro-models-max-vs-hero-11/"><u>[Updated] Unveiling the Top GoPro Models Max Vs. Hero 11</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/5-youtube-video-editor-alternatives-for-2024/"><u>Best 5 YouTube Video Editor Alternatives for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/critical-windows-update-features-now-fixed-and-operational/"><u>Critical Windows Update Features Now Fixed and Operational</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-storage-after-resolving-the-cyclic-redundancy-check-glitches/"><u>Error-Free Storage After Resolving the Cyclic Redundancy Check Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-0xc000012f-error-in-windows-easily/"><u>How to Fix 0Xc000012f Error in Windows Easily</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-lost-data-of-iphone-6-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of iPhone 6? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-hands-on-crafting-unique-movie-closures-for-pennies/"><u>In 2024, Hands-On Crafting Unique Movie Closures for Pennies</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-battery-wont-charge-master-quick-repairs-to-power-up-again/"><u>Laptop Battery Won't Charge? Master Quick Repairs to Power Up Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-function-to-broken-keys-on-microsofts-latest-operating-systems-win-10-win-11/"><u>Restore Function to Broken Keys on Microsoft's Latest Operating Systems (Win 10 / Win 11)</u></a></li>
<li><a href="https://extra-support.techidaily.com/smoothly-softening-endings-audio-fades-made-simple-with-adobe-premiere-pro-for-2024/"><u>Smoothly Softening Endings Audio Fades Made Simple with Adobe Premiere Pro for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-connecting-your-microsoft-wireless-display-adapter-with-windows-aturate-as-well-as-to-improve-the-efficiency-of-the-model-itself-during-t47/"><u>Step-by-Step Guide: Connecting Your Microsoft Wireless Display Adapter with Windows Aturate, as Well as to Improve the Efficiency of the Model Itself During Training and Inference</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-excessive-svchostexe-cpu-load-in-windows-11/"><u>Step-by-Step Solutions for Excessive Svchost.exe CPU Load in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-and-fix-windows-10-bluetooth-connectivity-problems-fast/"><u>Troubleshoot and Fix Windows 10 Bluetooth Connectivity Problems Fast</u></a></li>
<li><a href="https://discover-deluxe.techidaily.com/unveiling-the-intricacies-of-a-zero-day-exploit-a-comprehensive-guide-by-malwarefox/"><u>Unveiling the Intricacies of a Zero-Day Exploit: A Comprehensive Guide by MalwareFox</u></a></li>
</ul></div>

