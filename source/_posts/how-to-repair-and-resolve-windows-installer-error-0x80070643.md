---
title: How to Repair and Resolve Windows Installer Error 0X80070643
date: 2024-10-09T02:25:23.566Z
updated: 2024-10-12T21:17:27.783Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Repair and Resolve Windows Installer Error 0X80070643
excerpt: This Article Describes How to Repair and Resolve Windows Installer Error 0X80070643
thumbnail: https://thmb.techidaily.com/e6d099750c73059d854ce64a05b1f14144b4ddd8add62154acc4588369eca37b.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2105864/7443" target="_top" id="2105864">
  <img src="//a.impactradius-go.com/display-ad/7443-2105864" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105864/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://unicoeye.pxf.io/c/5597632/2148774/18498" target="_top" id="2148774">
  <img src="//a.impactradius-go.com/display-ad/18498-2148774" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2148774/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<span id="1993652">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993652.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993652">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993652.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993652%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993652/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135400/19272" target="_top" id="2135400">
  <img src="//a.impactradius-go.com/display-ad/19272-2135400" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135400/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://fox-friendly.techidaily.com/new-downloading-youtube-subtitled-content-in-3-ways-for-2024/"><u>[New] Downloading YouTube Subtitled Content in 3 Ways for 2024</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/updated-years-best-fb-film-grabs-ranked-8-of-eight-for-2024/"><u>[Updated] Year's Best FB Film Grabs Ranked #8 of Eight for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/dvdmac-mac-mac/"><u>DVDコピーツール・Mac用: 変換してMacに転送が簡単な無料ソフト - Macユーザー必見!</u></a></li>
<li><a href="https://common-error.techidaily.com/eradicating-input-lag-for-a-smoother-experience-with-windows-11-computers/"><u>Eradicating Input Lag for a Smoother Experience with Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-solutions-for-fixing-werfaultexe-errors-in-windows/"><u>Essential Solutions for Fixing werfault.exe Errors in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-this-platform-is-not-supported-while-installing-intel-serial-io-driver/"><u>Fix This Platform Is Not Supported. While Installing Intel Serial IO Driver</u></a></li>
<li><a href="https://tech-revival.techidaily.com/getting-started-with-langchain-large-language-models-the-starters-handbook/"><u>Getting Started with LangChain Large Language Models: The Starter's Handbook</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-miracast-streaming-despite-errors-a-step-by-step-guide/"><u>How to Enable Miracast Streaming Despite Errors: A Step-by-Step Guide</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/how-to-screenshot-on-mac-5-simple-ways-for-2024/"><u>How to Screenshot on Mac - 5 Simple Ways for 2024</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/in-2024-hassle-free-ways-to-remove-frp-lock-on-google-pixel-7a-phones-withwithout-a-pc-by-drfone-android/"><u>In 2024, Hassle-Free Ways to Remove FRP Lock on Google Pixel 7a Phones with/without a PC</u></a></li>
<li><a href="https://fox-glue.techidaily.com/in-2024-optimal-choices-for-endless-data-preservation/"><u>In 2024, Optimal Choices for Endless Data Preservation</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/in-2024-webcam-video-pros-fast-effective-filming-steps/"><u>In 2024, Webcam Video Pros Fast, Effective Filming Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-light-adjustment-feature-on-windows-surprise/"><u>Missing Light Adjustment Feature on Windows Surprise</u></a></li>
<li><a href="https://common-error.techidaily.com/touchpad-lag-or-no-response-heres-how-you-can-resolve-it/"><u>Touchpad Lag or No Response? Here's How You Can Resolve It</u></a></li>
</ul></div>

