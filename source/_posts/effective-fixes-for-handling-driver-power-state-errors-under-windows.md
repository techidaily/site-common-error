---
title: Effective Fixes for Handling Driver Power State Errors Under Windows
date: 2024-09-23T20:14:03.783Z
updated: 2024-09-26T19:03:40.433Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Effective Fixes for Handling Driver Power State Errors Under Windows
excerpt: This Article Describes Effective Fixes for Handling Driver Power State Errors Under Windows
thumbnail: https://thmb.techidaily.com/087d4c396676b014d9cc5b7a27f2781bb19d17612d23e9d7c790aa6a83d75782.jpg
---

## Error 1068 Troubleshooting for Windows Users - Quick Fixes Inside

![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c434dca99.jpg)

 When you attempts to connect your system to a wireless network, if you’re getting the**Error 1068: The dependency service or group failed to start** error on your Windows computer, it could be super frustrating. Don’t worry. You’re certainly not the only one. We’ve seen many users are reporting this issue. More importantly, you can fix it with the solutions here. Read on and see how…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## 3 Fixes for Error 1068

1. **[Restart the WLAN AutoConfig service](https://tools.techidaily.com/drivereasy/download/)**
2. **[Repair your registry](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your network adapter driver](https://tools.techidaily.com/drivereasy/download/)**

### Solution 1: Restart the WLAN AutoConfig service

 This error could happen if the WLAN AutoConfig service isn’t correctly configured on your computer. In this case, you can try to restart the service to solve your problem.

See how to do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**services.msc** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c45b02d97.png)
3. Right-click on**WLAN AutoConfig** to select**Restart** . If the Restart option grayed out, click**Start** instead.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c4e8dc53f.jpg)
4. **Double-click** WLAN AutoConfig.
5. Set the Startup type to**Automatic** . Then**Apply** \>**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90c6c3c4eb5.jpg)

 Reboot your Windows computer and the error should disappear. If you’re prompted the error again, there’re something else you can try…

### Solution 2: Repair your registry

 When your system settings are not configured properly, this error may also occur. You can solve it through repairing your registry.

Here’s how you can do it:

1. On your keyboard, hold down the**Windows logo key** and press**R** to bring up the Run box.
2. Type**regedit** , then press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca32dcfd4.png)
3. Click**Yes** when prompted by User Account Control.  
![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca123ce81.jpg)
4. Go to**HKEY\_LOCAL\_MACHINE** \>**SYSTEM** \>**CurrentControlSet** \>**Services** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90ca74d28b3.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2123729/7443" target="_top" id="2123729">
  <img src="//a.impactradius-go.com/display-ad/7443-2123729" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2123729/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right-click**Dhcp** under the Services section to select**Export** .  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129739/7443" target="_top" id="2129739">
  <img src="//a.impactradius-go.com/display-ad/7443-2129739" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129739/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Give a name for the backup file, say Dhcp backup. Then select a backup address and click**Save** . You can restore the file from this backup if any error occurs during the process below.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cae624a92.jpg)
6. **Double-click** DependOnService on the right pane of Dhcp. Select all the words**except “Afd”** , then**delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc0dde1d6.jpg)
7. Right-click**Eaphost** under the Services section to select**Export** .  
 Give a name for the backup file, say Eaphost backup.Then select a backup address and click**Save** .![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cc80aaff0.jpg)
8. **Double-click** DependOnService on the right pane of Eaphost. Select all the words and **delete** them.![](https://images.drivereasy.com/wp-content/uploads/2018/09/img_5b90cd67d4334.jpg)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137214/26400" target="_top" id="2137214">
  <img src="//a.impactradius-go.com/display-ad/26400-2137214" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137214/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134243/18498" target="_top" id="2134243">
  <img src="//a.impactradius-go.com/display-ad/18498-2134243" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134243/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Close the Registry Editor window and reboot your Windows computer. Check if the error disappears. If you still see the error, don’t give up hope. Simply move onto next solution.

### Solution 3: Update your network adapter driver

 This problem could be also due to**a corrupted, old or missing network driver** on your system. So you can solve it through updating your network driver.

 Updating drivers require Internet connection on your computer. If your computer can’t access the wireless network, try to connect your computer to a wired network connection or, you can try the[Offline Scan](https://tools.techidaily.com/drivereasy/download/) feature of Driver Easy.

You can update your network driver either manually or automatically.

#### Manual driver update

 You can update your network driver manually by going to the manufacturer’s website for your network adapter, say,**Realtek** , and searching for the most recent correct driver. Be sure to choose only drivers that are compatible with your Windows version.

#### Automatic driver update

 If you don’t have the time, patience or computer skills to update your network driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct driver for your exact network adapter, and your Windows version, and it will download and install them correctly.

 You can click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system. (This requires the Pro version which comes with**full support** and a**30-day money back guarantee** . You’ll be prompted to upgrade when you click Update All.)  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/img_5b891580f3aca.jpg)

<!-- affiliate ads begin -->
<span id="1983552">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983552.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983552">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983552.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983552%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983552/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

You’re done. Feel free to comment below if you have any question.

* [error](https://tools.techidaily.com/drivereasy/download/)
* [Windows](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://article-posts.techidaily.com/new-2024-approved-secrets-of-success-in-capturing-breathtaking-gopro-time-lapse/"><u>[New] 2024 Approved Secrets of Success in Capturing Breathtaking GoPro Time-Lapse</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/updated-resolving-iphone-shot-unfocus-issues-quickly-for-2024/"><u>[Updated] Resolving iPhone Shot Unfocus Issues Quickly for 2024</u></a></li>
<li><a href="https://solve-outstanding.techidaily.com/breakfast-vegetable-omelette-bell-peppers-spinach-mushrooms-with-a-slice-of-whole-grain-toast-herbal-tea/"><u>Breakfast: Vegetable Omelette (Bell Peppers, Spinach, Mushrooms) with a Slice of Whole-Grain Toast; Herbal Tea.</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/discover-the-samsung-galaxy-fit2-your-perfect-on-the-go-wellness-gadget/"><u>Discover the Samsung Galaxy Fit2: Your Perfect On-the-Go Wellness Gadget</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-implemented-overcome-the-this-page-cant-be-shown-barrier/"><u>Fix Implemented! Overcome the 'This Page Can't Be Shown' Barrier</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-recover-when-your-google-chrome-freezes-problem-solved/"><u>How To Recover When Your Google Chrome Freezes – Problem Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207103656-how-to-repair-a-malfunctioning-steam-client-launcher-expert-solutions-inside/"><u>How to Repair a Malfunctioning Steam Client Launcher - Expert Solutions Inside!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-easily-unlock-your-realme-c51-device-sim-by-drfone-android/"><u>In 2024, Easily Unlock Your Realme C51 Device SIM</u></a></li>
<li><a href="https://tech-haven.techidaily.com/narrative-excellence-through-ai-chatgpts-six-pathways/"><u>Narrative Excellence Through AI, ChatGPT's Six Pathways</u></a></li>
<li><a href="https://audio-editing.techidaily.com/new-2024-approved-demystifying-omegle-an-insight-into-free-chat-networks-and-their-protective-features/"><u>New 2024 Approved Demystifying Omegle An Insight Into Free Chat Networks and Their Protective Features</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-system-cannot-allocate-enough-memory-error/"><u>Resolved: Fixing 'System Cannot Allocate Enough Memory' Error</u></a></li>
<li><a href="https://common-error.techidaily.com/reviving-your-clicks-a-guide-to-repairing-a-nonfunctional-logitech-mouse-scroll-wheel/"><u>Reviving Your Clicks: A Guide to Repairing a Nonfunctional Logitech Mouse Scroll Wheel</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-to-repair-non-functioning-usb-connectors/"><u>Simple Solutions to Repair Non-Functioning USB Connectors</u></a></li>
<li><a href="https://win-howtos.techidaily.com/solution-guide-for-missing-d3dcompiler-dll-files-error-code-43/"><u>Solution Guide for Missing D3DCompiler DLL Files (Error Code 43)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-overcoming-minecrafts-opengl-glitches/"><u>Step-by-Step Solutions for Overcoming Minecraft's OpenGL Glitches</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-mousepad-in-windows-operating-systems-solutions-for-windows-1187/"><u>Troubleshooting Non-Responsive Mousepad in Windows Operating Systems - Solutions for Windows 11/8/7</u></a></li>
<li><a href="https://ai-topics.techidaily.com/updated-how-to-generate-speech-from-text-the-top-text-to-speech-converters-for-2024/"><u>Updated How To Generate Speech From Text | The Top Text-to-Speech Converters for 2024</u></a></li>
</ul></div>

