---
title: Troubleshooting and Repairing a Down DNS Server in Just Four Steps
date: 2024-09-12T20:37:07.100Z
updated: 2024-09-15T01:24:42.310Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Repairing a Down DNS Server in Just Four Steps
excerpt: This Article Describes Troubleshooting and Repairing a Down DNS Server in Just Four Steps
thumbnail: https://thmb.techidaily.com/f13aeea6c73457fbc5bbd1b6bff4a0c00a428af0a90b0cd758e49ef9cfc3066d.jpg
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
<li><a href="https://common-error.techidaily.com/1723209147637-solution-expedite-your-pcs-performance-get-rid-of-high-cpu-load-stuck-by-shell-infrastructures/"><u>[Solution] Expedite Your PC's Performance - Get Rid of High CPU Load Stuck by Shell Infrastructures!</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/2024-approved-top-10-royale-arenas-of-thrill/"><u>2024 Approved Top 10 Royale Arenas of Thrill</u></a></li>
<li><a href="https://extra-hints.techidaily.com/craft-a-one-of-a-kind-digital-gag-now-for-2024/"><u>Craft a One-of-a-Kind Digital Gag Now for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/elevate-your-digital-identity-top-101-masterclass-in-personal-bios-for-2024/"><u>Elevate Your Digital Identity Top 101 Masterclass in Personal Bios for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-failed-update-on-your-windows-amoled-version-1803-explained/"><u>How to Fix a Failed Update on Your Windows Amoled - Version 1803 Explained</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-my-apple-iphone-11-pro-location-is-wrong-drfone-by-drfone-virtual-ios/"><u>How to Fix My Apple iPhone 11 Pro Location Is Wrong | Dr.fone</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-ghost-touch-glitch-in-iphones-explore-10-proven-remedies-for-a-smoother-screen-experience/"><u>Overcoming Ghost Touch Glitch in iPhones: Explore 10 Proven Remedies for a Smoother Screen Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/repairing-dells-unresponsive-usb-connector-comprehensive-solutions/"><u>Repairing Dell's Unresponsive USB Connector - Comprehensive Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-valorants-perpetual-launch-loop-issue/"><u>Resolving Valorant's Perpetual Launch Loop Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/skyrims-unending-launch-sequence-solutions-for-a-smooth-start/"><u>Skyrim's Unending Launch Sequence - Solutions for a Smooth Start</u></a></li>
<li><a href="https://apple-account.techidaily.com/tips-and-tricks-for-apple-id-locked-issue-on-iphone-6-by-drfone-ios/"><u>Tips and Tricks for Apple ID Locked Issue On iPhone 6</u></a></li>
<li><a href="https://network-issues.techidaily.com/win11-flickering-now-stable-and-secure/"><u>Win11 Flickering - Now Stable and Secure</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123734/7443" target="_top" id="2123734">
  <img src="//a.impactradius-go.com/display-ad/7443-2123734" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123734/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

