---
title: "Step-by-Step Tutorial: Correcting Corrupt OS Files in Windows 10 and 11"
date: 2024-12-13T02:02:00.627Z
updated: 2024-12-16T23:29:27.492Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Step-by-Step Tutorial: Correcting Corrupt OS Files in Windows 10 and 11"
excerpt: "This Article Describes Step-by-Step Tutorial: Correcting Corrupt OS Files in Windows 10 and 11"
thumbnail: https://thmb.techidaily.com/cfb0e1f2c6527b7d4431251ab8890078af21f0bc88406680edc99866453f0d22.jpg
---

## Troubleshooting and Correcting Error 0X80070091 During Windows 11 System Restore - Solved

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/fm0XhU5H8R4?si=cFPk6XK3X3CQSI7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/omWG4u39lmE?si=yk1AEo_gzDpGjYbl" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
  
## **Fix Two. Rename the WindowsApps folder in WinRE**

1)  

Boot your Windows 10 into WinRE(Windows Recovery Environment)  
How to:  
a)  
Open Settings Window by pressing **Windows** key + **I** key.  
Then click **Update & security**.  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/6.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/qfCSLAhd4FY?si=CUBztmilaeAwl1lw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/hZsnjxeSh1U?si=hZIfzQPDNX5KtOCg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://fox-glue.techidaily.com/new-vrs-role-in-shaping-future-films-for-2024/"><u>[New] VR's Role in Shaping Future Films for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/updated-novice-necessities-your-first-steps-in-gopro-world/"><u>[Updated] Novice Necessities - Your First Steps in GoPro World</u></a></li>
<li><a href="https://extra-resources.techidaily.com/comprehensive-visuals-what-sets-360-apart-for-2024/"><u>Comprehensive Visuals What Sets 360° Apart for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/defeat-windows-update-error-0x8024402c-a-comprehensive-troubleshooting-guide-resolved/"><u>Defeat Windows Update Error 0X8024402c: A Comprehensive Troubleshooting Guide [Resolved]</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-wacom-pen-display-connectivity-problems/"><u>Diagnosing and Repairing Wacom Pen Display Connectivity Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-windows-11-sound-issues-troubleshooting-non-responsive-volume-buttons/"><u>Fix Windows 11 Sound Issues: Troubleshooting Non-Responsive Volume Buttons</u></a></li>
<li><a href="https://printer-issues.techidaily.com/guidelines-to-cure-printer-blank-screens/"><u>Guidelines to Cure Printer Blank Screens</u></a></li>
<li><a href="https://fix-guide.techidaily.com/how-to-fix-the-soft-bricked-honor-magic5-ultimate-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix the Soft Bricked Honor Magic5 Ultimate? | Dr.fone</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-show-wi-fi-password-on-itel-by-drfone-android/"><u>How to Show Wi-Fi Password on Itel</u></a></li>
<li><a href="https://windows11.techidaily.com/resolving-windows-security-fault-in-1011-edition/"><u>Resolving Windows Security Fault in 10/11 Edition</u></a></li>
<li><a href="https://games-able.techidaily.com/sonys-monthly-charge-for-access-to-game-library/"><u>Sony's Monthly Charge for Access to Game Library</u></a></li>
<li><a href="https://common-error.techidaily.com/streamline-your-tasks-essential-tips-for-using-file-explorer-in-windows-1ntegrated-applications-sync-with-google-photos-or-icloud-you-can-access-your-photos72/"><u>Streamline Your Tasks: Essential Tips for Using File Explorer in Windows 1Ntegrated Applications | Sync with Google Photos or iCloud, You Can Access Your Photos From Anywhere and on Any Device.</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-the-challenge-of-error-0x80240017-in-windows-updates-your-comprehensive-guide/"><u>Tackling the Challenge of Error 0X80240017 in Windows Updates – Your Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-oddworld-soulstorm-pc-game-crash-issues/"><u>Troubleshooting Guide for Oddworld: Soulstorm PC Game Crash Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/untangling-error-code-31-in-windows-easy-repair-techniques/"><u>Untangling Error Code 31 in Windows: Easy Repair Techniques</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/watermark-free-video-editing-top-10-online-tools-you-need-to-know-for-2024/"><u>Watermark-Free Video Editing Top 10 Online Tools You Need to Know for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209254604-windows-update-issue-solved-no-more-problems/"><u>Windows Update Issue Solved – No More Problems</u></a></li>
</ul></div>

