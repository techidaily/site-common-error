---
title: Troubleshooting and Repairing a Down DNS Server in Just Four Steps
date: 2024-10-12T23:52:03.195Z
updated: 2024-10-19T00:34:28.772Z
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
  

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139111/17108" target="_top" id="2139111">
  <img src="//a.impactradius-go.com/display-ad/17108-2139111" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139111/17108" style="position:absolute;visibility:hidden;" border="0" />
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
<span id="1975503">
					<video width="128" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1975503.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1975503">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1975503.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:80px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1975503%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1975503/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134491/18498" target="_top" id="2134491">
  <img src="//a.impactradius-go.com/display-ad/18498-2134491" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134491/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925473/19272" target="_top" id="1925473">
  <img src="//a.impactradius-go.com/display-ad/19272-1925473" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925473/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://screen-recording.techidaily.com/new-2024-approved-smooth-operations-screen-recording-basics-for-lenovo-users/"><u>[New] 2024 Approved Smooth Operations Screen Recording Basics for Lenovo Users</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-getting-unstuck-troubleshooting-absent-fb-vids/"><u>[New] In 2024, Getting Unstuck Troubleshooting Absent FB Vids</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-discover-everything-in-stardews-hidden-gem-ginger-isle/"><u>[Updated] 2024 Approved Discover Everything in Stardew's Hidden Gem, Ginger Isle</u></a></li>
<li><a href="https://tech-revival.techidaily.com/boosting-group-discussions-by-incorporating-gpt-3/"><u>Boosting Group Discussions by Incorporating GPT-3</u></a></li>
<li><a href="https://common-error.techidaily.com/diy-solution-correcting-the-monitor-not-receiving-signal-problem-a-step-by-step-tutorial/"><u>DIY Solution: Correcting the 'Monitor Not Receiving Signal' Problem - A Step by Step Tutorial</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-devices-fail-to-sync-on-windows-11/"><u>Effective Fixes for When Your Devices Fail to Sync on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/enhanced-local-safeguards-activated-for-improved-security-measures/"><u>Enhanced Local Safeguards Activated for Improved Security Measures</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-to-restore-movement-in-frozen-mouse-buttons-and-scroll-wheel/"><u>Expert Tips to Restore Movement in Frozen Mouse Buttons and Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-class-not-registered-errors-on-windows-11-solved/"><u>How to Fix 'Class Not Registered' Errors on Windows 11 – Solved!</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-to-mirror-apple-iphone-7-to-windows-10-drfone-by-drfone-ios/"><u>In 2024, How to Mirror Apple iPhone 7 to Windows 10? | Dr.fone</u></a></li>
<li><a href="https://extra-support.techidaily.com/in-2024-sharpening-your-minecraft-landscapes/"><u>In 2024, Sharpening Your Minecraft Landscapes</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/preserving-your-online-reputation-amidst-faux-endorsements-for-2024/"><u>Preserving Your Online Reputation Amidst Faux Endorsements for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-the-issue-effective-fixes-for-windows-11-update-error-code-0x800f0922/"><u>Resolve the Issue: Effective Fixes for Windows 11 Update Error Code 0X800F0922</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209954364-solving-your-logitech-keyboard-malfunction-in-minutes/"><u>Solving Your Logitech Keyboard Malfunction in Minutes</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205992205-troubleshooting-guide-for-non-working-mic-on-steelseries-arctis-5-a-step-by-step-solution/"><u>Troubleshooting Guide for Non-Working Mic on SteelSeries Arctis 5: A Step-by-Step Solution!</u></a></li>
<li><a href="https://win-solutions.techidaily.com/troubleshooting-techniques-to-keep-your-mass-effect-series-smooth-on-console-and-pc/"><u>Troubleshooting Techniques to Keep Your Mass Effect Series Smooth on Console & PC</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/updated-2024-approved-if-youre-not-using-video-yet-now-is-the-time-to-start-in-this-post-well-discuss-the-benefits-of-using-video-for-social-media-marketing/"><u>Updated 2024 Approved If Youre Not Using Video yet, Now Is the Time to Start. In This Post, Well Discuss the Benefits of Using Video for Social Media Marketing and Provide Tips for Getting Started. Keep Reading to Learn More</u></a></li>
</ul></div>

