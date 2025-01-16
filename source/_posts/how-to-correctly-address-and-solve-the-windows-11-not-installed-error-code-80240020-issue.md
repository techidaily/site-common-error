---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2025-01-14T16:22:29.975Z
updated: 2025-01-16T16:14:54.509Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Rxyki8-Y630?si=dHLkIxG59zdlZeN0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Xa2_mFu-obA?si=_xDGF1pv-dnuaDOr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/KaqfZcWg5sE?si=LPmSKk7AFp8VxDFD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/5EKBEujWCw4?si=PwVvvervi8OrYaEA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/ASUEYpqSP5E?si=0KOZxrTVexTuUkRn" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://youtube-webster.techidaily.com/024-approved-download-unlimited-mcb-visual-elements/"><u>[New] 2024 Approved Download Unlimited MCB Visual Elements</u></a></li>
<li><a href="https://youtube-data.techidaily.com/n-2024-maximizing-impact-strategies-for-overcoming-video-short-snags/"><u>[New] In 2024, Maximizing Impact Strategies for Overcoming Video Short Snags</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-in-2024-the-right-way-to-pick-spiritual-phone-tunes/"><u>[New] In 2024, The Right Way to Pick Spiritual Phone Tunes</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206482260-geforce-experience-setup-glitch-solved-retrieve-your-custom-configurations-now/"><u>GeForce Experience Setup Glitch Solved - Retrieve Your Custom Configurations Now!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-5-tracking-apps-to-track-xiaomi-civi-3-disney-100th-anniversary-edition-without-them-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, Top 5 Tracking Apps to Track Xiaomi Civi 3 Disney 100th Anniversary Edition without Them Knowing | Dr.fone</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/navigating-your-way-through-vr-headset-selection-is-the-mobile-experience-more-attractive-than-tethered-tech-in-2024/"><u>Navigating Your Way Through VR Headset Selection Is the Mobile Experience More Attractive Than Tethered Tech, In 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-new-world-overcomes-previous-easy-anti-cheat-issues/"><u>Resolved: 'New World' Overcomes Previous Easy Anti-Cheat Issues</u></a></li>
<li><a href="https://win11-tips.techidaily.com/restoring-paste-functionality-in-common-web-browsers/"><u>Restoring Paste Functionality in Common Web Browsers</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206650968-sd-invisible-no-more-find-the-answer-here/"><u>SD Invisible No More, Find the Answer Here</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-resolving-the-win32-app-crash-code-0x00000005/"><u>Step-by-Step Guide: Resolving the Win32 App Crash - Code 0X00000005</u></a></li>
<li><a href="https://common-error.techidaily.com/success-story-restoring-communication-with-a-non-responsive-dhcp-server/"><u>Success Story: Restoring Communication With a Non-Responsive DHCP Server</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-guide-successful-creation-of-d3d-device-after-failure/"><u>Troubleshooting Guide: Successful Creation of D3D Device After Failure</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-high-wudfhostexe-process-load-in-windows-10-systems/"><u>Troubleshooting High WUDFHost.exe Process Load in Windows 10 Systems</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/ultra-portable-moko-collapsible-wireless-keyboard/"><u>Ultra-Portable MoKo Collapsible Wireless Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-common-dll-errors-fix-and-prevention-tips/"><u>Winning Against Windows Common Dll Errors: Fix and Prevention Tips</u></a></li>
</ul></div>

