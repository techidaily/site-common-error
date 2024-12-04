---
title: "Error Code 0X80072F8F Solved: Expert Tips for Restoring Your Windows 11/10 System's Functionality"
date: 2024-12-03T00:50:57.981Z
updated: 2024-12-04T00:40:40.385Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 0X80072F8F Solved: Expert Tips for Restoring Your Windows 11/10 System's Functionality"
excerpt: "This Article Describes Error Code 0X80072F8F Solved: Expert Tips for Restoring Your Windows 11/10 System's Functionality"
thumbnail: https://thmb.techidaily.com/8f88442ac6dedc419a65e9e8bd02cadcc874f8f080f0e1330c1b328f3cf15bd0.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

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
<iframe width="560" height="315" src="https://www.youtube.com/embed/X18Dq7rV-xI?si=twFfXIPD0TFmC5EM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/XIUatTFH0Zw?si=ZCtoBtIy18y2F5Vc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Q-mXUpVQijU?si=f1MzflPJ8-bD2_iQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  
c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/U_aNKnMTPjo?si=Og_mEt7NP3Fbsg2n" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://some-approaches.techidaily.com/new-the-ultimate-directory-30plus-zero-cost-online-tools-for-visual-effects/"><u>[New] The Ultimate Directory 30+ Zero-Cost Online Tools for Visual Effects</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-2024-approved-essential-guide-to-fixing-srt-export-errors/"><u>[Updated] 2024 Approved Essential Guide to Fixing SRT Export Errors</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-maximize-your-creativity-a-detailed-instruction-manual-for-uploading-videos-on-youtube-for-2024/"><u>[Updated] Maximize Your Creativity A Detailed Instruction Manual for Uploading Videos on YouTube for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-for-restoring-access-when-facing-disconnect-problems-from-a-remote-server/"><u>Effective Techniques for Restoring Access When Facing Disconnect Problems From a Remote Server</u></a></li>
<li><a href="https://extra-information.techidaily.com/from-shipping-secrets-to-surprises-unveiling-new-strategies/"><u>From Shipping Secrets to Surprises Unveiling New Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-do-a-clean-install-of-windows-10-quickly-and-easily/"><u>How to Do a Clean Install of Windows 10, Quickly and Easily!</u></a></li>
<li><a href="https://win-blog.techidaily.com/how-to-restore-the-windows-11-taskbar-when-it-stops-working/"><u>How to Restore the Windows 11 Taskbar When It Stops Working</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-remove-the-lock-screen-fingerprint-of-your-xiaomi-civi-3-by-drfone-android/"><u>In 2024, Remove the Lock Screen Fingerprint Of Your Xiaomi Civi 3</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-unlock-your-infinix-hot-40i-phone-with-ease-the-3-best-lock-screen-removal-tools-by-drfone-android/"><u>In 2024, Unlock Your Infinix Hot 40i Phone with Ease The 3 Best Lock Screen Removal Tools</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/logitech-momo-racing-wheel-download-the-latest-pc-game-drivers-now/"><u>Logitech MOMO Racing Wheel - Download the Latest PC Game Drivers Now!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-persistent-delay-fixing-keyboard-lag-on-windows-10/"><u>Resolving Persistent Delay: Fixing Keyboard Lag on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-steam-server-connectivity-restored/"><u>Troubleshooting Guide: Steam Server Connectivity Restored</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-missing-driver-issues-during-windows-7-installation-process/"><u>Troubleshooting Missing Driver Issues During Windows 7 Installation Process</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-rpc-communication-issue-diagnoses-on-a-windows-machine/"><u>Troubleshooting Steps for 'RPC Communication Issue' Diagnoses on a Windows Machine</u></a></li>
<li><a href="https://solve-marvelous.techidaily.com/ubertragt-ihre-iphone-fotos-auf-ihr-ipad-top-5-losungen-mit-und-ohne-icloud/"><u>Überträgt Ihre iPhone-Fotos Auf Ihr iPad? Top 5 Lösungen – Mit Und Ohne iCloud</u></a></li>
<li><a href="https://common-error.techidaily.com/win11-computers-restart-spontaneously/"><u>Win11 Computers Restart Spontaneously</u></a></li>
</ul></div>

