---
title: "Resolving Errors: A Guide to Repairing 'Internet Explorer Has Stopped Working'"
date: 2024-10-30T07:25:43.845Z
updated: 2024-11-05T04:09:01.232Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Resolving Errors: A Guide to Repairing 'Internet Explorer Has Stopped Working'"
excerpt: "This Article Describes Resolving Errors: A Guide to Repairing 'Internet Explorer Has Stopped Working'"
thumbnail: https://thmb.techidaily.com/ced37c54f6280b48c4cccd59bb3d4e6e75cf48a369ed52226c792a6ec4885ea2.jpg
---

## Deciphering and Resolving Error 0X80070091 for Successful System Restores in Windows 11 - Expert Tips

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
<a href="https://25home.pxf.io/c/5597632/2148643/16836" target="_top" id="2148643">
  <img src="//a.impactradius-go.com/display-ad/16836-2148643" border="0" alt="https://techidaily.com" width="300" height="75"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148643/16836" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151856/7443" target="_top" id="2151856">
  <img src="//a.impactradius-go.com/display-ad/7443-2151856" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151856/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123728/7443" target="_top" id="2123728">
  <img src="//a.impactradius-go.com/display-ad/7443-2123728" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123728/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137205/26400" target="_top" id="2137205">
  <img src="//a.impactradius-go.com/display-ad/26400-2137205" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137205/26400" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://youtube-data.techidaily.com/n-2024-premium-7-video-gear-ideas-for-captivating-vloggers/"><u>[New] In 2024, Premium 7 Video Gear Ideas for Captivating Vloggers</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/new-in-2024-the-great-growers-guide-the-best-farmer-games/"><u>[New] In 2024, The Great Growers' Guide The Best Farmer Games</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-2024-approved-building-a-professional-youtube-presence-via-smartphone/"><u>[Updated] 2024 Approved Building a Professional YouTube Presence via Smartphone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-professionals-take-on-screenflow-pro-macos-experience/"><u>[Updated] 2024 Approved Professional's Take on ScreenFlow Pro macOS Experience</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-navigating-mobile-technology-for-snapchat-archive/"><u>2024 Approved Navigating Mobile Technology for Snapchat Archive</u></a></li>
<li><a href="https://common-error.techidaily.com/demystifying-and-fixing-the-crippling-windows-11-update-glitch-code-0xc190n0028-revealed/"><u>Demystifying and Fixing the Crippling Windows 11 Update Glitch - Code 0Xc190n0028 Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-24-repair-steps-overcoming-device-not-present-issues-in-windows-operating-systems/"><u>Error Code 24 Repair Steps: Overcoming Device Not Present Issues in Windows Operating Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-your-mouse-cursor-in-windows-11-solution/"><u>How to Restore Your Mouse Cursor in Windows 11 [Solution]</u></a></li>
<li><a href="https://win-bits.techidaily.com/impossible-de-localiser-la-page-erreur-404-detectee/"><u>Impossible De Localiser La Page : Erreur 404 Détectée</u></a></li>
<li><a href="https://extra-hints.techidaily.com/in-2024-craft-humor-for-giphy-network/"><u>In 2024, Craft Humor for Giphy Network</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-turn-off-google-location-to-stop-tracking-you-on-honor-magic-5-lite-drfone-by-drfone-virtual-android/"><u>In 2024, How to Turn Off Google Location to Stop Tracking You on Honor Magic 5 Lite | Dr.fone</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/iphone-recovery-unlocked-how-to-reboot-and-start-fresh-with-no-backup/"><u>IPhone Recovery Unlocked: How to Reboot and Start Fresh With No Backup</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-fix-for-microsofts-print-to-pdf-non-function-on-windows-11-computers/"><u>Mastering the Fix for Microsoft's Print to PDF Non-Function on Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/solve-your-xbox-one-connection-issues-how-to-resync-a-non-syncing-controller/"><u>Solve Your Xbox One Connection Issues – How to Resync a Non-Syncing Controller</u></a></li>
</ul></div>

