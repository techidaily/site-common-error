---
title: How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11
date: 2025-01-29T03:50:49.691Z
updated: 2025-01-29T19:50:09.455Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11
excerpt: This Article Describes How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11
thumbnail: https://thmb.techidaily.com/13a2ed7d3d473fc4b094f952faefa5141a38181bbb0354fc87e696c7a5f69650.png
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aIx71tPaWKg?si=lG5OiUe-M6eBJf5b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
On the pop-up window, view on **Boot** pane.  
Then tick on **Safe boot**and click **OK**.  
Click **Restart**, if prompted by system configuration  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/3-1.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/97ydpSmzTJw?si=tFcelmtQX4u-b3u5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/xIP8ktrmOdg?si=zRnjbGzM6PDx2jCq" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/2En1CHbiYwA?si=jZKzTr9EIT2ShjGK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://screen-sharing-recording.techidaily.com/new-in-2024-swift-tips-for-easy-ipad-screen-recordings/"><u>[New] In 2024, Swift Tips for Easy iPad Screen Recordings</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-in-2024-screen-recorder-showdown-top-choices-explored/"><u>[Updated] In 2024, Screen Recorder Showdown Top Choices Explored</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-tapping-into-built-in-screen-recording-features-of-huaweis-mate-and-p-lineup/"><u>[Updated] Tapping Into Built-In Screen Recording Features of Huawei's Mate & P Lineup</u></a></li>
<li><a href="https://extra-resources.techidaily.com/2024-approved-an-in-depth-guide-to-periscope-recording-procedures/"><u>2024 Approved An In-Depth Guide to Periscope Recording Procedures</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-defective-keyboard-letters-solutions-for-windows-1011-devices/"><u>Addressing Defective Keyboard Letters - Solutions for Windows 10/11 Devices</u></a></li>
<li><a href="https://discover-alternatives.techidaily.com/enhance-your-sites-engagement-using-the-power-of-cookiebot-technology/"><u>Enhance Your Site's Engagement Using the Power of Cookiebot Technology</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/modders-and-tutorial-content-leaders-for-2024/"><u>Game Modders & Tutorial Content Leaders for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-re-enable-bluetooth-in-windows-11-swift-solutions-unveiled/"><u>How To Re-Enable Bluetooth in Windows 11: Swift Solutions Unveiled</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-unlock-oppo-a59-5g-phone-pattern-lock-without-factory-reset-by-drfone-android/"><u>How to Unlock Oppo A59 5G Phone Pattern Lock without Factory Reset</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-fixing-windows-11-using-sfc-and-dism-commands/"><u>Mastering the Art of Fixing Windows 11 Using SFC and DISM Commands</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-touchscreen-repair-in-windows-11-discover-these-5-techniques/"><u>Mastering the Art of Touchscreen Repair in Windows 11: Discover These 5 Techniques</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-leading-music-editors-for-iphones-and-android-devices-a-comprehensive-review/"><u>New Leading Music Editors for iPhones and Android Devices – A Comprehensive Review</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-asus-laptops-special-key-combinations-repair-tips-for-malfunctioning-function-keys/"><u>Revive Your ASUS Laptop's Special Key Combinations: Repair Tips for Malfunctioning Function Keys</u></a></li>
<li><a href="https://win-dash.techidaily.com/top-picks-finding-the-perfect-copernic-products-as-gifts/"><u>Top Picks: Finding the Perfect Copernic Products as Gifts</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-skype-microphone-malfunctions-successful-fixes-and-tips/"><u>Troubleshooting Skype Microphone Malfunctions – Successful Fixes and Tips!</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-fixed-why-your-screen-may-not-accept-current-video-signals/"><u>Understanding [FIXED]: Why Your Screen May Not Accept Current Video Signals</u></a></li>
</ul></div>

