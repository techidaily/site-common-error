---
title: Troubleshooting Steps for Forcing a Shutdown on Windows 11 Systems
date: 2024-11-12T16:08:40.191Z
updated: 2024-11-15T18:03:35.887Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Troubleshooting Steps for Forcing a Shutdown on Windows 11 Systems
excerpt: This Article Describes Troubleshooting Steps for Forcing a Shutdown on Windows 11 Systems
thumbnail: https://thmb.techidaily.com/502bcc92fd452403f6c08525ae02c0d2e78a33616170701a3383a08e8dcec924.jpg
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
<a href="https://coinrule.sjv.io/c/5597632/1958378/18409" target="_top" id="1958378">
  <img src="//a.impactradius-go.com/display-ad/18409-1958378" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://coinrule.sjv.io/i/5597632/1958378/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://aligracehair.sjv.io/c/5597632/2087267/19272" target="_top" id="2087267">
  <img src="//a.impactradius-go.com/display-ad/19272-2087267" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2087267/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<span id="1630055">
					<video width="192" height="320" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1630055.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/18460-1630055">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1630055.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:120px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fcaperobbin.sjv.io%2Fc%2F5597632%2F1630055%2F18460'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1630055/18460" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880944/19272" target="_top" id="1880944">
  <img src="//a.impactradius-go.com/display-ad/19272-1880944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880944/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vimeo-videos.techidaily.com/new-stars-quick-visibility-check/"><u>[New] Star's Quick Visibility Check</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-apowersoft-screen-recording-the-ultimate-pc-guide/"><u>[Updated] In 2024, Apowersoft Screen Recording The Ultimate PC Guide</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-restoring-clear-vision-fixing-iphone-lens-out-of-focus/"><u>2024 Approved Restoring Clear Vision Fixing iPhone Lens Out-of-Focus</u></a></li>
<li><a href="https://common-error.techidaily.com/5-effective-remedies-when-your-dns-server-fails-to-respond/"><u>5 Effective Remedies When Your DNS Server Fails to Respond</u></a></li>
<li><a href="https://program-issues.techidaily.com/batmans-epic-gaming-glitch-heres-how-to-avoid-the-arkham-knight-collapse/"><u>Batman's Epic Gaming Glitch? Here’s How to Avoid the Arkham Knight Collapse</u></a></li>
<li><a href="https://win11.techidaily.com/clearing-graphics-from-windows-search-interface/"><u>Clearing Graphics From Windows Search Interface</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/document-total-screen-content-for-2024/"><u>Document Total Screen Content for 2024</u></a></li>
<li><a href="https://discover-brilliant.techidaily.com/effortlessly-convert-and-import-mtsm2ts-videos-into-adobe-premiere-pro-for-smooth-editing-flow/"><u>Effortlessly Convert and Import MTS/M2TS Videos Into Adobe Premiere Pro for Smooth Editing Flow</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-reactivate-disabled-intel-rst-service-on-your-windows-10-pc/"><u>How to Reactivate Disabled Intel RST Service on Your Windows 10 PC</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-streamlined-signal-synchronizer-for-podcasters/"><u>In 2024, Streamlined Signal Synchronizer For Podcasters</u></a></li>
<li><a href="https://common-error.techidaily.com/input-mismatch-no-more-achieving-optimal-display-compatibility-and-performance/"><u>Input Mismatch No More: Achieving Optimal Display Compatibility & Performance</u></a></li>
<li><a href="https://win-luxury.techidaily.com/interactive-flash-features-for-readers-on-flipbook-creator-flipbuilder-get-started-today/"><u>Interactive Flash Features for Readers on FlipBook Creator (FlipBuilder) – Get Started Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-failed-windows-10-build-1607-feature-update-problems/"><u>Resolving Failed Windows 10 Build 1607 Feature Update Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-rpc-server-unreachable-issue-on-your-windows-pc-a-step-by-step-guide/"><u>Resolving the 'RPC Server Unreachable' Issue on Your Windows PC: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-automatic-boot-up-solutions-for-your-self-starting-windows-11-pc/"><u>Understanding Automatic Boot-Up: Solutions for Your Self-Starting Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-the-mystery-behind-net-framework-35s-error-code-0x800f081f-fixes-inside/"><u>Unraveling the Mystery Behind .NET Framework 3.5'S Error Code 0X800F081F - Fixes Inside</u></a></li>
<li><a href="https://common-error.techidaily.com/what-does-msda80dll-do-on-your-computer-and-how-to-manage-its-storage-safely/"><u>What Does MSDA80.DLL Do on Your Computer, and How to Manage Its Storage Safely?</u></a></li>
</ul></div>

