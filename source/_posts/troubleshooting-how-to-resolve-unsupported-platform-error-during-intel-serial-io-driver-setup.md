---
title: "Troubleshooting: How to Resolve Unsupported Platform Error During Intel Serial IO Driver Setup"
date: 2024-09-25T03:52:59.052Z
updated: 2024-10-01T16:50:54.961Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: How to Resolve Unsupported Platform Error During Intel Serial IO Driver Setup"
excerpt: "This Article Describes Troubleshooting: How to Resolve Unsupported Platform Error During Intel Serial IO Driver Setup"
thumbnail: https://thmb.techidaily.com/dccea8e74312ef3978115e47791b42d8d3af59ddef7b2d9a4c85759dfb53f1ee.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2105874/7443" target="_top" id="2105874">
  <img src="//a.impactradius-go.com/display-ad/7443-2105874" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105874/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://appsumo.8odi.net/c/5597632/2151888/7443" target="_top" id="2151888">
  <img src="//a.impactradius-go.com/display-ad/7443-2151888" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151888/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

b)  
Click **Recovery**.  
Then scroll down on the right side and click **Restart now** under **Advanced startup** .  
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/7-2.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049379/7443" target="_top" id="2049379">
  <img src="//a.impactradius-go.com/display-ad/7443-2049379" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049379/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

c)  
Click**Troubleshoot** \> **Advanced** \>**Command Prompt**.
  
![](https://images.drivereasy.com/wp-content/uploads/2017/04/11.jpg)
  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
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
<li><a href="https://instagram-video-files.techidaily.com/updated-kick-starting-a-captivating-instagram-live/"><u>[Updated] Kick-Starting a Captivating Instagram Live</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/ed-maximizing-impact-with-creative-video-titles-for-2024/"><u>[Updated] Maximizing Impact with Creative Video Titles for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-survivors-guide-top-6-mc-house-plans/"><u>2024 Approved Survivor's Guide Top 6 MC House Plans</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-top-15-masterpieces-in-stop-motion-cinema-history/"><u>2024 Approved Top 15 Masterpieces in Stop-Motion Cinema History</u></a></li>
<li><a href="https://fox-access.techidaily.com/breaking-boundaries-in-video-content-creation-within-limit/"><u>Breaking Boundaries in Video Content Creation (Within Limit)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/comment-rationaliser-efficientment-la-conversion-h264-en-h265-pour-diminuer-la-taille-du-fichier-sans-compromettre-la-qualite/"><u>Comment Rationaliser Efficientment La Conversion H.264 En H.265 Pour Diminuer La Taille Du Fichier Sans Compromettre La Qualité?</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-guide-to-correcting-your-screens-no-signal-problem-from-diagnosis-to-fix/"><u>Comprehensive Guide to Correcting Your Screen's 'No Signal' Problem: From Diagnosis to Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-dealing-with-the-binkw32dll-not-present-problem/"><u>Expert Advice for Dealing with the Binkw32.dll Not Present Problem</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-oneplus-nord-ce-3-lite-5g-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your OnePlus Nord CE 3 Lite 5G Phone FRP Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-usb-recognition-issues-in-windows-11-no-more-port-reset-failures/"><u>Mastering USB Recognition Issues in Windows 11: No More Port Reset Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-installing-latest-windows-10-build-1607-common-issues-and-fixes/"><u>Trouble Installing Latest Windows 10 Build 1607: Common Issues and Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-correcting-file-access-denied-by-windows/"><u>Troubleshooting Guide for Correcting 'File Access Denied by Windows'</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-success-fix-for-non-responsive-keys-and-typing-malfunctions/"><u>Troubleshooting Success: Fix for Non-Responsive Keys and Typing Malfunctions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-recovering-compromised-configuration-data-on-windows-11/"><u>Troubleshooting Tips: Recovering Compromised Configuration Data on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-successfully-turning-on-bluetooth-in-windows-11-and-10/"><u>Troubleshooting Tips: Successfully Turning On Bluetooth in Windows 11 & 10</u></a></li>
<li><a href="https://win-solutions.techidaily.com/tutorial-eliminare-le-macchie-dal-tuo-album-fotografico-strumenti-per-lediting-delle-foto/"><u>Tutorial: Eliminare Le Macchie Dal Tuo Album Fotografico - Strumenti per L'Editing Delle Foto</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/what-pokemon-evolve-with-a-dawn-stone-for-oppo-a18-drfone-by-drfone-virtual-android/"><u>What Pokémon Evolve with A Dawn Stone For Oppo A18? | Dr.fone</u></a></li>
</ul></div>

