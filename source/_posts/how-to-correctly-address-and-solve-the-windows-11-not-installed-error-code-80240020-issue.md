---
title: How to Correctly Address and Solve the 'Windows 11 Not Installed - Error Code 80240020' Issue
date: 2025-01-28T06:48:40.008Z
updated: 2025-01-29T19:09:43.461Z
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/9hsPbiic0O8?si=58mZ2Cu6wicQfsUP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/umvX4ZdWbxk?si=tPXL0-Kzf9SQaY8z" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/K4lRBnNnd9k?si=5e0MbdOz-fF6Ry_k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zAzTErKy6h8?si=vi5z3M9_7fW6qiAJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/B2MlLvGxMwI?si=q_blGjXyJrGtzT8d" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://remote-screen-capture.techidaily.com/new-2024-approved-beat-stress-away-the-ultimate-gaming-list/"><u>[New] 2024 Approved Beat Stress Away The Ultimate Gaming List</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-motion-mastery-top-free-afx-template-collection-for-2024/"><u>[New] Motion Mastery Top Free AFX Template Collection for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-unleash-creativity-with-youtube-list-mix-ups/"><u>[New] Unleash Creativity with YouTube List Mix-Ups</u></a></li>
<li><a href="https://discover-cloud.techidaily.com/best-virtual-camera-tools-unlocking-features-of-live-video-software-like-manycam/"><u>Best Virtual Camera Tools: Unlocking Features of Live Video Software Like ManyCam</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-your-dell-bluetooth-mouse-troubleshooting-steps-when-it-fails/"><u>Fixing Your Dell Bluetooth Mouse: Troubleshooting Steps When It Fails</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-steam-update-not-downloading-issue/"><u>How to Fix Steam Update Not Downloading Issue</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-transformative-audio-techniques-for-media-professionals/"><u>In 2024, Transformative Audio Techniques for Media Professionals</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/in-2024-unveiling-the-best-ways-to-watch-360-videos-on-android/"><u>In 2024, Unveiling the Best Ways to Watch 360 Videos on Android</u></a></li>
<li><a href="https://common-error.techidaily.com/livekernelevent-117-problem-diagnosis-and-repair-methods/"><u>LiveKernelEvent 117 Problem: Diagnosis and Repair Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-touch-interactivity-on-your-pc-top-5-techniques-for-windows-11-users/"><u>Reviving Touch Interactivity on Your PC: Top 5 Techniques for Windows 11 Users</u></a></li>
<li><a href="https://techtrends.techidaily.com/step-by-step-guide-reviving-your-unresponsive-pc/"><u>Step-by-Step Guide: Reviving Your Unresponsive PC</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-combo-keys-stuck-solving-win-shift-and-s-button-issues-on-pcs-with-w10w11/"><u>Windows Combo Keys Stuck? Solving Win, Shift, and S Button Issues on PCs with W10/W11</u></a></li>
</ul></div>

