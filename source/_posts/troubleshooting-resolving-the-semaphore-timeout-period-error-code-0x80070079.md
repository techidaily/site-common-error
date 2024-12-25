---
title: "Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079"
date: 2024-12-24T18:19:49.198Z
updated: 2024-12-25T16:56:35.578Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079"
excerpt: "This Article Describes Troubleshooting: Resolving the 'Semaphore Timeout Period' Error Code 0X80070079"
thumbnail: https://thmb.techidaily.com/8a54b5f3957881ee85a4e67f8767270bede7bd83bce45614963bc600bb3e8241.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q_69vX9wnRE?si=FtLxkpRhPORqcMeE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LaGNHfAT92w?si=bvHo1iYK2JBIPtRo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

5)  

When it finish rebooting, run System Restore again.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/g6xXIR_Uh1A?si=TMXzklPEY50MUM05" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/LT4sdZgUvRQ?si=SvQD5FouEzu4UHpJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VxFUhesNCKo?si=Ti0ui6DXYP12sjSs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-friendly.techidaily.com/updated-how-to-zoom-in-on-minecraft-for-2024/"><u>[Updated] How to Zoom in on Minecraft for 2024</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/updated-maintain-anonymity-in-fb-narratives/"><u>[Updated] Maintain Anonymity in FB Narratives</u></a></li>
<li><a href="https://technical-tips.techidaily.com/19-exciting-new-models-enhance-tcls-q-and-s-class-smart-tv-selection/"><u>19 Exciting New Models Enhance TCL's Q and S Class Smart TV Selection</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/best-way-to-stitch-gopro-clips-into-360-videos-for-2024/"><u>Best Way to Stitch GoPro Clips Into 360 Videos for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/crafting-attention-grabbing-facebook-giveaways/"><u>Crafting Attention-Grabbing Facebook Giveaways</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-fixing-lenovo-mouse-pad-problems-across-windows-versions/"><u>Effective Solutions for Fixing Lenovo Mouse Pad Problems Across Windows Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-perpetual-white-screen-on-windows-10-devices/"><u>How to Fix the Perpetual White Screen on Windows 10 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-recover-and-repair-broken-system-elements-in-windows-11-easily/"><u>How to Recover and Repair Broken System Elements in Windows 11 Easily</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-stop-life360-from-tracking-you-on-nubia-red-magic-9-pro-drfone-by-drfone-virtual-android/"><u>How to Stop Life360 from Tracking You On Nubia Red Magic 9 Pro? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-a-xiaomi-civi-3-easily-by-drfone-android/"><u>How To Unlock a Xiaomi Civi 3 Easily?</u></a></li>
<li><a href="https://common-error.techidaily.com/repaired-enable-your-devices-local-authentication-feature-now/"><u>Repaired: Enable Your Device's Local Authentication Feature Now</u></a></li>
<li><a href="https://win-web.techidaily.com/schritt-fur-schritt-anleitung-zum-automatischen-einrichten-von-onedrive-mit-windows-server/"><u>Schritt-Für-Schritt-Anleitung Zum Automatischen Einrichten Von OneDrive Mit Windows Server</u></a></li>
<li><a href="https://common-error.techidaily.com/the-system-cannot-find-the-file-specified-solved/"><u>The System Cannot Find the File Specified [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-guide-to-enable-and-repair-shockwave-flash-support-on-chrome/"><u>The Ultimate Guide to Enable and Repair Shockwave Flash Support on Chrome</u></a></li>
</ul></div>

