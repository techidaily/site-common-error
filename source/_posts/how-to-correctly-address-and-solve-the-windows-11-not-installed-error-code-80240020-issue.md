---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2025-01-16T21:29:16.263Z
updated: 2025-01-22T16:45:40.674Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/-yZKNLxj3po?si=-RbF6nCJEVlHWP-M" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/_7AYCS7zBU0?si=7R9oIpE4hyEbtk3x" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PD0vq5qAYkw?si=5H3KWtCfUOYg1Nlv" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/U6lCtLUeROA?si=se6OFuis9JpcTGJf" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://video-capture.techidaily.com/new-2024-approved-perfect-planning-how-to-schedule-your-online-teams-virtual-gatherings-google/"><u>[New] 2024 Approved Perfect Planning How to Schedule Your Online Team's Virtual Gatherings (Google)</u></a></li>
<li><a href="https://youtube-web.techidaily.com/uilding-a-strong-foundation-for-advertising-deals-using-famebit-methods-for-2024/"><u>[New] Building a Strong Foundation for Advertising Deals Using FameBit Methods for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-hearing-beginnings-mastering-volume-control-in-adobe-audition-for-2024/"><u>[New] Hearing Beginnings Mastering Volume Control in Adobe Audition for 2024</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/astering-personal-content-management-building-a-structured-watch-later-list/"><u>[New] Mastering Personal Content Management Building a Structured 'Watch Later' List</u></a></li>
<li><a href="https://some-techniques.techidaily.com/2024-approved-exploration-comparison-gopros-hero5-black-and-sessions/"><u>2024 Approved Exploration Comparison GoPro's Hero5 Black & Sessions</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-honor-play-7t-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on Honor Play 7T? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/arrow-key-issues-on-your-keyboard-fix-them-with-these-expert-methods/"><u>Arrow Key Issues on Your Keyboard? Fix Them With These Expert Methods!</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-solutions-for-dealing-with-the-easy-anti-cheat-glitch-in-apex-legends/"><u>Effortless Solutions for Dealing with the Easy Anti-Cheat Glitch in Apex Legends</u></a></li>
<li><a href="https://techidaily.com/how-to-factory-reset-tecno-spark-10c-without-losing-data-drfone-by-drfone-reset-android-reset-android/"><u>How to Factory Reset Tecno Spark 10C without Losing Data | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-d3derrnotavailable-troubleshooting-steps-inside/"><u>How to Overcome 'D3DERR_NOTAVAILABLE': Troubleshooting Steps Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-initial-load-problems-eliminating-the-pitch-black-display-during-launch-of-mhw/"><u>How to Overcome Initial Load Problems: Eliminating the Pitch Black Display During Launch of MHW</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/instagram-economics-a-detailed-blueprint-for-profit-for-2024/"><u>Instagram Economics A Detailed Blueprint for Profit for 2024</u></a></li>
<li><a href="https://techtrends.techidaily.com/july-2024-lineup-of-great-family-flicks-to-enjoy-on-amazon-prime-video/"><u>July 2024 Lineup of Great Family Flicks to Enjoy on Amazon Prime Video</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-guide-to-keep-your-computer-awake-and-alert/"><u>Quick Troubleshooting Guide to Keep Your Computer Awake and Alert</u></a></li>
<li><a href="https://fox-useful.techidaily.com/recognizing-indicators-of-hardware-issues-a-guide-by-yl-computing-and-software-solutions/"><u>Recognizing Indicators of Hardware Issues: A Guide by YL Computing & Software Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-critical-issues-in-call-of-duty-black-ops-4/"><u>Resolving Critical Issues in Call of Duty: Black Ops 4</u></a></li>
<li><a href="https://common-error.techidaily.com/shift-key-malfunction-diagnosis-and-effective-remedies-fixed/"><u>Shift Key Malfunction: Diagnosis and Effective Remedies [FIXED]</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-mystery-ultimate-guide-to-troubleshoot-windows-11-bluetooth-connection-issues/"><u>Solving the Mystery: Ultimate Guide to Troubleshoot Windows 11 Bluetooth Connection Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-your-windows-computers-non-functional-built-in-camera/"><u>Troubleshooting Steps: Resolving Your Windows Computer's Non-Functional Built-In Camera</u></a></li>
</ul></div>

