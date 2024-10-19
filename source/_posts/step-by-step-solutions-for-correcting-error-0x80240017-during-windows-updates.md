---
title: Step-by-Step Solutions for Correcting Error 0X80240017 During Windows Updates
date: 2024-10-16T03:59:24.467Z
updated: 2024-10-19T02:06:19.795Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Solutions for Correcting Error 0X80240017 During Windows Updates
excerpt: This Article Describes Step-by-Step Solutions for Correcting Error 0X80240017 During Windows Updates
thumbnail: https://thmb.techidaily.com/80c97e26a42ec85426e926d8a619570205ae66ef3c841d342bad4a1013bf8d86.jpg
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
<a href="https://aligracehair.sjv.io/c/5597632/1902319/19272" target="_top" id="1902319">
  <img src="//a.impactradius-go.com/display-ad/19272-1902319" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1902319/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2137411/7443" target="_top" id="2137411">
  <img src="//a.impactradius-go.com/display-ad/7443-2137411" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137411/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043617/7443" target="_top" id="2043617">
  <img src="//a.impactradius-go.com/display-ad/7443-2043617" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043617/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1528700/16446" target="_top" id="1528700">
  <img src="//a.impactradius-go.com/display-ad/16446-1528700" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1528700/16446" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://vp-tips.techidaily.com/new-crafting-your-podcasts-rss-feed-a-step-by-step-guide-for-2024/"><u>[New] Crafting Your Podcast's RSS Feed A Step-by-Step Guide for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-2024-approved-beginners-bible-to-your-youtube-audio-visual-arsenal/"><u>[Updated] 2024 Approved Beginner's Bible to Your YouTube Audio-Visual Arsenal</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-hurdles-getting-oddworld-soulstorm-up-and-running-on-pc-without-crashes/"><u>Beat The Hurdles: Getting Oddworld: Soulstorm Up And Running on PC Without Crashes</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-and-steady-essential-youtube-camera-tech/"><u>Clear and Steady Essential YouTube Camera Tech</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/comprension-y-pronunciacion-de-colores/"><u>Comprensión Y Pronunciación De Colores</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-unknown-usb-device-failures-caused-by-port-reset-errors-in-windows-10/"><u>Diagnosing and Repairing Unknown USB Device Failures Caused by Port Reset Errors in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-images-not-displaying-correctly-on-windows-1011/"><u>How to Resolve Images Not Displaying Correctly on Windows 10/11?</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-microsofts-compatibility-telemetry-using-too-much-memory-in-windows-11/"><u>How to Resolve Microsoft's Compatibility Telemetry Using Too Much Memory in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-0x80240034-issue-during-a-windows-10-upgrade/"><u>How to Resolve the 0X80240034 Issue During a Windows 10 Upgrade</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-easiest-guide-how-to-clone-oppo-a2-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Easiest Guide How to Clone Oppo A2 Phone? | Dr.fone</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/keep-bot-discussions-private-and-safe/"><u>Keep Bot Discussions Private & Safe</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/optimize-gmail-for-video-calls-with-effective-zoom-use/"><u>Optimize Gmail for Video Calls with Effective Zoom Use</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-solutions-eradicate-xeroxs-bothersome-update-error-0x800f020b-in-windows-instantly/"><u>Seamless Solutions: Eradicate Xerox's Bothersome Update Error (0X800f020b) in Windows Instantly</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-4-ways-to-trace-honor-magic-vs-2-location-drfone-by-drfone-virtual-android/"><u>Top 4 Ways to Trace Honor Magic Vs 2 Location | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-fixing-secure-connection-error-in-firefox/"><u>Troubleshooting Tips: Fixing 'Secure Connection Error' In Firefox</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-silencing-a-noisy-ps4-causes-effects-and-remedies/"><u>Understanding & Silencing a Noisy PS4: Causes, Effects, and Remedies</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-webcam-problems-on-windows-effective-strategies-and-solutions/"><u>Unraveling Webcam Problems on Windows: Effective Strategies and Solutions</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-2024-approved-the-ultimate-list-free-4k-video-converters-for-windows-and-mac/"><u>Updated 2024 Approved The Ultimate List Free 4K Video Converters for Windows and Mac</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-the-ipogo-get-you-banned-and-how-to-solve-it-on-infinix-smart-8-hd-drfone-by-drfone-virtual-android/"><u>Will the iPogo Get You Banned and How to Solve It On Infinix Smart 8 HD | Dr.fone</u></a></li>
</ul></div>

