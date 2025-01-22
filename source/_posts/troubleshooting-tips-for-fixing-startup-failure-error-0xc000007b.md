---
title: Troubleshooting Tips for Fixing Startup Failure (Error 0Xc000007b)
date: 2025-01-16T17:03:07.086Z
updated: 2025-01-22T18:22:17.268Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Tips for Fixing Startup Failure (Error 0Xc000007b)
excerpt: This Article Describes Troubleshooting Tips for Fixing Startup Failure (Error 0Xc000007b)
thumbnail: https://thmb.techidaily.com/ee3331b3501f448fb98f7a4ee3a53ac099c1c123c857eac1255a179cf5757415.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/aknYnDfODro?si=zONIVzA9FFq0rLOD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/cC-HtDQVoG0?si=nQcoa7q8q2IL8U0m" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/9Sj2QNA-JXI?si=V-_h73iE3VlE214k" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/L603QXgjb3I?si=sMYHfMGy2kNPSHPt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/15TKQ-BOENI?si=Ri4B2AuxAdi0Bglz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://desktop-recording.techidaily.com/2024-approved-advanced-techniques-for-live-action-sims-playback/"><u>2024 Approved Advanced Techniques for Live-Action Sims Playback</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-oneplus-ace-2-pro-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On OnePlus Ace 2 Pro | Dr.fone</u></a></li>
<li><a href="https://howto.techidaily.com/8-solutions-to-solve-youtube-app-crashing-on-itel-p55plus-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>8 Solutions to Solve YouTube App Crashing on Itel P55+ | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/deciding-between-ultrawide-and-uhd-4k-monitors/"><u>Deciding Between UltraWide and UHD 4K Monitors</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-on-fixing-non-responsive-alt-plus-tab-feature-in-windows/"><u>Expert Advice on Fixing Non-Responsive Alt + Tab Feature in Windows</u></a></li>
<li><a href="https://os-tips.techidaily.com/fix-location-not-detected-on-iphone-swiftly-and-simply-a-step-by-step-guide/"><u>Fix 'Location Not Detected' On iPhone Swiftly and Simply – A Step-by-Step Guide</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixes-and-solutions-stop-dread-hunger-game-from-crashing-on-your-computer/"><u>Fixes & Solutions: Stop 'Dread Hunger' Game From Crashing on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-red-screen-of-error-a-step-by-step-guide/"><u>Fixing the Red Screen of Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-resolving-unrecognized-usb-flash-drives/"><u>Quick Solutions: Resolving Unrecognized USB Flash Drives</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/regain-access-to-confidential-snapshots-for-2024/"><u>Regain Access to Confidential Snapshots for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-issues-with-your-windows-11-start-menu-easy-fixes-and-solutions/"><u>Solving Issues with Your Windows 11 Start Menu - Easy Fixes and Solutions!</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/streamline-your-steam-deck-recording-with-this-user-friendly-screencast-app/"><u>Streamline Your Steam Deck Recording with This User-Friendly Screencast App</u></a></li>
</ul></div>

