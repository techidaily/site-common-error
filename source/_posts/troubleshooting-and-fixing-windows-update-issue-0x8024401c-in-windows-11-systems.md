---
title: Troubleshooting and Fixing Windows Update Issue 0X8024401c in Windows 11 Systems
date: 2024-10-27T17:30:28.892Z
updated: 2024-10-30T18:10:33.341Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting and Fixing Windows Update Issue 0X8024401c in Windows 11 Systems
excerpt: This Article Describes Troubleshooting and Fixing Windows Update Issue 0X8024401c in Windows 11 Systems
thumbnail: https://thmb.techidaily.com/6befd60c173a5cd8b8d9dfcf598dea7f7e1558ad2a50419820d4a5c540b52039.jpg
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
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105877/7443" target="_top" id="2105877">
  <img src="//a.impactradius-go.com/display-ad/7443-2105877" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105877/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2135411/19272" target="_top" id="2135411">
  <img src="//a.impactradius-go.com/display-ad/19272-2135411" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135411/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1061528/11832" target="_top" id="1061528">
  <img src="//a.impactradius-go.com/display-ad/11832-1061528" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1061528/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://dhgate.sjv.io/c/5597632/1172027/12108" target="_top" id="1172027">
  <img src="//a.impactradius-go.com/display-ad/12108-1172027" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://dhgate.sjv.io/i/5597632/1172027/12108" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://desktop-recording.techidaily.com/new-2024-approved-the-comprehensive-list-of-webinar-recording-methods/"><u>[New] 2024 Approved The Comprehensive List of Webinar Recording Methods</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-a-step-by-step-guide-to-youtube-image-branding-for-2024/"><u>[Updated] A Step-by-Step Guide to YouTube Image Branding for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/compatibility-checklist-verify-your-system-has-a-d3d11-ready-graphics-unit-for-optimal-performance/"><u>Compatibility Checklist: Verify Your System Has a D3D11-Ready Graphics Unit for Optimal Performance</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/daring-to-dream-mondlylanguages-celebrates-2-years/"><u>Daring to Dream: MondlyLanguages Celebrates 2 Years</u></a></li>
<li><a href="https://common-error.techidaily.com/discovering-the-solution-to-xbox-onpc-issues/"><u>Discovering the Solution to Xbox OnPC Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-missing-desktop-icons-on-windows-11-complete-solution/"><u>Fixing Missing Desktop Icons on Windows 11 - Complete Solution!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-damaged-files-a-complete-fix-guide/"><u>How to Repair Damaged Files: A Complete Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-missing-desktop-for-system-account-on-windows-config/"><u>How To Restore Missing Desktop for System Account on Windows Config</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209060932-hp-laptop-keyboard-malfunction-heres-how-to-fix-it-quickly/"><u>HP Laptop Keyboard Malfunction? Here's How to Fix It Quickly!</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-breaking-down-instagrams-hashtag-system-tips-and-techniques/"><u>In 2024, Breaking Down Instagram's Hashtag System Tips and Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/jump-start-your-dead-laptop-battery-with-these-easy-troubleshooting-steps/"><u>Jump-Start Your Dead Laptop Battery with These Easy Troubleshooting Steps!</u></a></li>
<li><a href="https://driver-download.techidaily.com/lenovo-dock-upgrades-how-to-seamlessly-install-new-device-drivers/"><u>Lenovo Dock Upgrades: How to Seamlessly Install New Device Drivers</u></a></li>
<li><a href="https://win-able.techidaily.com/no-more-crashes-a-comprehensive-tutorial-for-repairing-pacific-drive-stability-issues/"><u>No More Crashes: A Comprehensive Tutorial for Repairing Pacific Drive Stability Issues</u></a></li>
<li><a href="https://fix-guide.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-xiaomi-redmi-12-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Xiaomi Redmi 12 | Dr.fone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/the-motivation-driving-hacker-intrusions-into-chatgpt-user-accounts/"><u>The Motivation Driving Hacker Intrusions Into ChatGPT User Accounts</u></a></li>
<li><a href="https://common-error.techidaily.com/win1011-manage-overloaded-cores/"><u>Win10/11: Manage Overloaded Cores</u></a></li>
<li><a href="https://tech-revival.techidaily.com/witnessing-chatgpts-influence-on-modern-industries/"><u>Witnessing ChatGPT's Influence on Modern Industries</u></a></li>
</ul></div>

