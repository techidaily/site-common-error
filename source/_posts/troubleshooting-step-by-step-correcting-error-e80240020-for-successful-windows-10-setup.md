---
title: "Troubleshooting Step-by-Step: Correcting Error E80240020 for Successful Windows 10 Setup"
date: 2025-01-18T20:53:17.335Z
updated: 2025-01-22T18:47:37.523Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting Step-by-Step: Correcting Error E80240020 for Successful Windows 10 Setup"
excerpt: "This Article Describes Troubleshooting Step-by-Step: Correcting Error E80240020 for Successful Windows 10 Setup"
thumbnail: https://thmb.techidaily.com/92459487433dd8191ecb6f79f9b025b7d93038fc1418a5a54e50bbd98af412de.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

![](https://images.drivereasy.com/wp-content/uploads/2017/04/1-2.jpg)
  
A lot Windows 10 users reported that system restore did not complete successfully. And the problem pop-uped as**Error 0x80070091**shown as image above. It’s a good thing that Microsoft has noticed this error and  will update this thread soon. However, if you are Windows 10 Advanced user, you can fix it right now via the methods below. If you’ve faced it, just go with the easy fixes below.  
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/PUDdKOsEN74?si=tkZf-KVinjuwmgx9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/fo4lNZ84x9Q?si=WdcYPZp-9VJnZEnC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then your Windows 10 would get into safe mode.  
  
2)  

Open quick-access menu by pressing **Windows** key + **X** key.  
Then click **Command Prompt(Admin)** to run it as administrator.  
When prompted by User Account Control, click   **Yes.**
  
**![](https://images.drivereasy.com/wp-content/uploads/2017/04/4-2.jpg)**
  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/7JBG_O3Vnh4?si=lUO0fta6YPJ50qjg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/Un9G2_OdSRI?si=vAcGbco8DuWt4ypP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<iframe width="560" height="315" src="https://www.youtube.com/embed/DEqoiNArwjQ?si=oaL_lgnI-RxY5Qy_" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-copyright-compliance-and-photovideo-sharing/"><u>[New] 2024 Approved Copyright Compliance & Photo/Video Sharing</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-uncomplicated-pc-record-functionality/"><u>[New] 2024 Approved Uncomplicated PC Record Functionality</u></a></li>
<li><a href="https://screen-recording.techidaily.com/new-in-2024-discovering-the-best-screen-recording-programs-for-win11/"><u>[New] In 2024, Discovering the Best Screen Recording Programs for Win11</u></a></li>
<li><a href="https://some-techniques.techidaily.com/updated-historical-gems-art-unshackled-by-laws/"><u>[Updated] Historical Gems Art Unshackled by Laws</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-missing-d3dxt939dll-errors-in-windows-expert-solutions-and-tips/"><u>Fixing Missing d3dxt9_39.dll Errors in Windows - Expert Solutions and Tips</u></a></li>
<li><a href="https://extra-tips.techidaily.com/in-2024-c-span-archive-entry-the-free-download-guide/"><u>In 2024, C-Span Archive Entry The Free Download Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/internet-explorer-wont-open-discover-proven-fixes-for-an-instant-solution/"><u>Internet Explorer Won't Open? Discover Proven Fixes for an Instant Solution!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/les-meilleurs-logiciels-de-montage-diaporama-photo-pour-pc-et-mac-le-top-19-de-lannee-202cu/"><u>Les Meilleurs Logiciels De Montage Diaporama Photo Pour PC Et Mac : Le Top 19 De L'année 202Cu</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-2024-approved-stream-your-personal-video-collection-to-chromecast-a-beginners-guide/"><u>New 2024 Approved Stream Your Personal Video Collection to Chromecast A Beginners Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-overcoming-error-8007000e-in-windows-updates/"><u>Quick Solutions for Overcoming Error 8007000E in Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-sound-functionality-in-your-acer-computer-step-by-step-troubleshooting/"><u>Restore Sound Functionality in Your Acer Computer - Step-by-Step Troubleshooting</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-correcting-livekernelevent-error-144-malfunctions/"><u>Step-by-Step Solutions for Correcting LiveKernelEvent Error 144 Malfunctions</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207450866-troubled-by-the-0x80072efd-mistake-on-your-pc-heres-how-to-resolve-it/"><u>Troubled by the 0X80072EFD Mistake on Your PC? Here’s How to Resolve It</u></a></li>
<li><a href="https://fox-http.techidaily.com/unveiling-ultra-details-in-minecraft-games-for-2024/"><u>Unveiling Ultra Details in Minecraft Games for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-v1607-update-installed-incorrectly-steps-for-resolution/"><u>Windows 11 v1607 Update Installed Incorrectly – Steps for Resolution</u></a></li>
</ul></div>

