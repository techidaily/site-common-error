---
title: "Mastering Windows 11 Setup: Fix the Error Code 80240020 Issue"
date: 2024-09-29T17:00:47.840Z
updated: 2024-10-01T19:02:14.754Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Mastering Windows 11 Setup: Fix the Error Code 80240020 Issue"
excerpt: "This Article Describes Mastering Windows 11 Setup: Fix the Error Code 80240020 Issue"
thumbnail: https://thmb.techidaily.com/b9d202f17312addc4751b6c7718b8073b057f0ff78d7cca6ec165bfb76c8c4ca.jpg
---

## How to Fix Windows Update Error Code 0X8024002E Easily

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-855.png)

 A lot of Windows 10 users have reported an error while trying to update their operating system. What usually happens is they fail to install their system updates, and an error code shows up on Windows Update that says “0x8024002e”.

 If this is also happening to you, you’re no doubt very frustrated. But the good news is you should be able to fix it quite easily. We’ve put together some suggestions to help you fix the problem. Here are a few things you can try:

1. **[Reset your Windows Update components](https://tools.techidaily.com/drivereasy/download/)**
2. **[Modify your Windows Update setting in the registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Perform a clean boot](https://tools.techidaily.com/drivereasy/download/)**

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Fix 1: Reset your Windows Update components

 The Windows Update “0x8024002e” error code may occur because its components are corrupted. These components include the services and temporary files and folders associated with Windows Update. You can try resetting these components and see if this fixes your problem.

To reset these components:

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “cmd” in the Run box, then, on your keyboard, press the**Ctrl** ,**Shift** and**Enter** keys at the same time.

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-884.png)

3. If prompted, click**Yes** .
4. In Command Prompt, type the following lines of command and press**Enter** on your keyboard after typing each:

net stop bits
net stop wuauserv
net stop appidsvc
net stop cryptsvc

5. Type these lines of command and press**Enter** after typing each in Command Prompt:

ren %systemroot%\softwaredistribution softwaredistribution.old
ren %systemroot%\system32\catroot2 catroot2.old

6. In Command Prompt, type these commands and press**Enter** after each:

net start bits
net start wuauserv
net start appidsvc
net start cryptsvc

7. Try updating your system with Windows Update, and see if the 0x8024002e error is gone.

 If it is, then you’ve solved your problem. But if not, you may need to…

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144272/7443" target="_top" id="2144272">
  <img src="//a.impactradius-go.com/display-ad/7443-2144272" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144272/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .
4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.
7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148645/16836" target="_top" id="2148645">
  <img src="//a.impactradius-go.com/display-ad/16836-2148645" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148645/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)

<!-- affiliate ads begin -->
<span id="1983545">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983545.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983545">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983545.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983545%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983545/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2036496/19272" target="_top" id="2036496">
  <img src="//a.impactradius-go.com/display-ad/19272-2036496" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2036496/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click**OK** .
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2027162/19272" target="_top" id="2027162">
  <img src="//a.impactradius-go.com/display-ad/19272-2027162" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2027162/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037359/7443" target="_top" id="2037359">
  <img src="//a.impactradius-go.com/display-ad/7443-2037359" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037359/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484939/16446" target="_top" id="1484939">
  <img src="//a.impactradius-go.com/display-ad/16446-1484939" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484939/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)
16. Click**OK** and then click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
 If there’s any startup item that causes the 0x8024002e error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

 Hopefully one of the fixes above helped you fix your 0x8024002e error on Windows Update. If you have any questions or suggestions, you’re more than welcome to leave us a comment below.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://instagram-clips.techidaily.com/new-2024-approved-perfecting-the-picture-perfect-cover-photo-on-instagrams-highlights/"><u>[New] 2024 Approved Perfecting the Picture-Perfect Cover Photo on Instagram's Highlights</u></a></li>
<li><a href="https://fox-glue.techidaily.com/new-2024-approved-unmasked-photos-simple-blur-solutions-with-piscart/"><u>[New] 2024 Approved Unmasked Photos Simple Blur Solutions with PiscArt</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-in-2024-alternatives-to-xsplit-for-digital-media-masters/"><u>[Updated] In 2024, Alternatives to Xsplit for Digital Media Masters</u></a></li>
<li><a href="https://fox-that.techidaily.com/cant-use-ringsilent-mode-on-iphone-fix-it-with-these-easy-steps/"><u>Can't Use Ring/Silent Mode on iPhone? Fix It with These Easy Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-failed-installs-of-windows-11-build-1607-features/"><u>Diagnosing Failed Installs of Windows 11, Build 1607 Features</u></a></li>
<li><a href="https://common-error.techidaily.com/disable-antivirus-software-temporarily/"><u>Disable Antivirus Software Temporarily</u></a></li>
<li><a href="https://tech-hub.techidaily.com/exploring-every-aspect-the-new-era-of-apple-ai-showcased-at-wwdc-24/"><u>Exploring Every Aspect: The New Era of Apple AI Showcased at WWDC '24</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/how-to-get-the-latest-lenovo-t430-drivers-for-smooth-performance-on-windows-1187/"><u>How to Get the Latest Lenovo T430 Drivers for Smooth Performance on Windows 11/8/7</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/in-2024-15-best-strongest-pokemon-to-use-in-pokemon-go-pvp-leagues-for-infinix-smart-7-drfone-by-drfone-virtual-android/"><u>In 2024, 15 Best Strongest Pokémon To Use in Pokémon GO PvP Leagues For Infinix Smart 7 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/internal-structures-like-baffles-and-weirs-can-enhance-sedimentation-by-reducing-turbulence-and-controlling-outflow-rates-for-maximum-contact-time-within-se151/"><u>Internal Structures Like Baffles and Weirs Can Enhance Sedimentation by Reducing Turbulence and Controlling Outflow Rates for Maximum Contact Time Within Settling Zones.</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-a-broken-right-click-a-windows-11-users-manual/"><u>Quick Fixes for a Broken Right Click: A Windows 11 User's Manual</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-missing-bluetooth-on-your-windows-10-device-expert-tips-and-tricks/"><u>Quick Fixes for Missing Bluetooth on Your Windows 10 Device: Expert Tips & Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-msvcp140dll-integrity/"><u>Restoring MSVCP140.dll Integrity</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-restoring-functionality-of-lenovos-biometric-scanner/"><u>Step-by-Step Guide: Restoring Functionality of Lenovo's Biometric Scanner</u></a></li>
<li><a href="https://location-social.techidaily.com/top-7-skype-hacker-to-hack-any-skype-account-on-your-itel-a60s-drfone-by-drfone-virtual-android/"><u>Top 7 Skype Hacker to Hack Any Skype Account On your Itel A60s | Dr.fone</u></a></li>
</ul></div>

