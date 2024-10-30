---
title: "Troubleshooting: How to Correct an Invalid Directory Error Message"
date: 2024-10-25T16:32:02.633Z
updated: 2024-10-30T17:05:47.380Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Troubleshooting: How to Correct an Invalid Directory Error Message"
excerpt: "This Article Describes Troubleshooting: How to Correct an Invalid Directory Error Message"
thumbnail: https://thmb.techidaily.com/2241cb63c07ba14971fe0574ec2b53b239df58241996fcf78b83d8a047d570ec.jpeg
---

## Troubled by Error 0X80pressure0426 in Windows 11? Here’s How You Can Correct It

Many Windows 10 users are recently experiencing an error “**0x80070426**“. They usually see this error on Windows Defender or Windows Update. If you’re also experiencing it, you’re no doubt very frustrated. But don’t worry! This error is fixable…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

You may not have to try them all; just work your way down the list until you find the one that works for you.**To fix error 0x80070426 on Windows Defender**

1. [**Run System File Checker**](https://tools.techidaily.com/drivereasy/download/)
2. [**Check for software conflicts**](https://tools.techidaily.com/drivereasy/download/)
**To fix error 0x80070426 on Windows Update**

* **[Troubleshoot your Windows Update issue](https://tools.techidaily.com/drivereasy/download/)**

---

### Fix 1: Run System File Checker

Perhaps this error occurs because you’re having issues with your Windows system files. You should run System File Checker to repair these files:

1. Press the**Windows logo key** on your keyboard and type “_cmd_ “.  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd68d188b6f7.png)
2. Right click**Command Prompt** in the list of results, then select**Run as administrator** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/10/img_5bd6a6691c908.jpg)
3. (If you’re using**Windows 7** or an earlier version,**skip** this step.) Type the**following line of command** at Command Prompt and press**Enter** on your keyboard:  
dism.exe /online /cleanup-image /restorehealth  
 Note that this command provides your system with the repair source required by System File Checker. This is done through**Windows Update** . \* If you’re having problems with Windows Update, you should, instead of entering the command above, plug a**Windows installation media** into your computer (you may need to create one with the **[Windows system software](https://www.microsoft.com/en-us/software-download/)**  ), then type the**following command** :  
dism.exe /online /cleanup-image /restorehealth /source:[DRIVE]:\sources\sxs /limitaccess  
 Replace**\[DRIVE\]** with the**drive letter** of your Windows installation media.
4. Wait for the process to be complete.
5. Type the**following line of command** at Command Prompt and press**Enter** on your keyboard:  
sfc /scannow  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf68db7d4d15.png)
6. Wait for the process to be complete.
7. Restart your computer if this is not done automatically.
If this worked for you, great! But if not, then move on to Fix 2, below…

### Fix 2: Check for software conflicts

This error may occur on Windows Defender because of software conflicts. To see if that’s the case for you, try performing a clean boot on your Windows system.

 A**clean boot** is a process that starts your Windows system with only the most essential drivers and programs. By doing it, you can determine what is the cause of your computer problem if it is due to a software conflict.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2105859/7443" target="_top" id="2105859">
  <img src="//a.impactradius-go.com/display-ad/7443-2105859" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2105859/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135407/19272" target="_top" id="2135407">
  <img src="//a.impactradius-go.com/display-ad/19272-2135407" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135407/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

6. Click**OK** .
7. Click**Restart** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Check to see if the error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)

<!-- affiliate ads begin -->
<span id="1304647">
					<video width="240" height="200" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1304647.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/15852-1304647">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1304647.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fthefitville.pxf.io%2Fc%2F5597632%2F1304647%2F15852'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1304647/15852" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

12. Check to see if the error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x80070426 error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
15. Right click**one** (only) **disabled Startup item** , then click**Enable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb439d112a8.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2049390/7443" target="_top" id="2049390">
  <img src="//a.impactradius-go.com/display-ad/7443-2049390" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049390/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

16. Click**OK** and then click**Restart** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037345/7443" target="_top" id="2037345">
  <img src="//a.impactradius-go.com/display-ad/7443-2037345" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037345/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

17. Check to see if the error occurs. If it doesn’t, repeat step**13 to 16**  until you find out the startup item that causes the issue.  
 If there’s any startup item that causes the 0x80070426 error, you should see what program is this item related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.

---

### Fix 3: Troubleshoot your Windows Update issue

If you see a 0x80070426 error on Windows Update, you’re probably having an issue with this component. You should troubleshoot this issue per the instructions on **[this page](https://tools.techidaily.com/drivereasy/download/)** and see if they resolve your problem. Hopefully one of the fixes above worked for you. If you have any questions or suggestions, feel free to leave us a comment below.

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
<li><a href="https://facebook-videos.techidaily.com/new-transform-yourfb-watchlist-with-easy-youtube-video-autoplay-configuration-for-2024/"><u>[New] Transform YourFB Watchlist with Easy Youtube Video Autoplay Configuration for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/2024-approved-fabricate-viral-gifs-via-giphy-portal/"><u>2024 Approved Fabricate Viral Gifs via Giphy Portal</u></a></li>
<li><a href="https://some-skills.techidaily.com/2024-approved-the-finest-9-digital-places-for-harvesting-futuristic-3d-typefaces/"><u>2024 Approved The Finest 9 Digital Places for Harvesting Futuristic 3D Typefaces</u></a></li>
<li><a href="https://technical-tips.techidaily.com/convert-image-files-from-pbm-to-bmp-for-free-on-the-web-with-movavis-tool/"><u>Convert Image Files From PBM to BMP for Free on the Web with Movavi's Tool</u></a></li>
<li><a href="https://common-error.techidaily.com/efficient-strategies-to-fix-delayed-start-up-response-addressing-error-1053/"><u>Efficient Strategies to Fix Delayed Start-Up Response - Addressing Error 1053</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-connectivity-between-a-nonfunctional-bluetooth-keyboard-and-pc/"><u>Expert Tips for Restoring Connectivity Between a Nonfunctional Bluetooth Keyboard and PC</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/express-your-gratitude-essential-phrases-for-travelers/"><u>Express Your Gratitude: Essential Phrases for Travelers</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-game-crashes-with-physxloader-dll-not-found-error/"><u>Fix Your Game Crashes with PhysXLoader DLL Not Found Error</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-nubia-red-magic-8s-proplus-location-without-installing-software-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Nubia Red Magic 8S Pro+ Location without Installing Software? | Dr.fone</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-remove-device-supervision-from-your-iphone-15-plus-by-drfone-ios/"><u>In 2024, Remove Device Supervision From your iPhone 15 Plus</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-solved-move-from-realme-v30-to-ios-not-working-problems-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, Solved Move from Realme V30 to iOS not Working Problems | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/master-your-ps4-settings-a-detailed-walkthrough-to-correcting-failed-nat-types/"><u>Master Your PS4 Settings: A Detailed Walkthrough to Correcting Failed NAT Types</u></a></li>
<li><a href="https://common-error.techidaily.com/print-to-pdf-malfunctioning-in-windows-11-here-are-the-fixes/"><u>Print to PDF Malfunctioning in Windows 11? Here Are the Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-guide-repairing-malfunctioning-usb-input-devices-in-windows-7-environments/"><u>Quick Guide: Repairing Malfunctioning USB Input Devices in Windows 7 Environments</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-cursor-solutions-for-windows-11-touchpad-troubles/"><u>Revive Your Cursor: Solutions for Windows 11 Touchpad Troubles</u></a></li>
<li><a href="https://common-error.techidaily.com/stay-updated-seo-best-practices-evolve-over-time-so-it-is-essential-to-stay-updated-with-google-algorithm-changes-and-industry-trends-to-ensure-youre-optimi39/"><u>Stay Updated: SEO Best Practices Evolve over Time, so It Is Essential to Stay Updated with Google Algorithm Changes and Industry Trends to Ensure You're Optimizing Your Content Effectively.</u></a></li>
<li><a href="https://fake-location.techidaily.com/the-best-8-vpn-hardware-devices-reviewed-on-apple-iphone-7-drfone-by-drfone-virtual-ios/"><u>The Best 8 VPN Hardware Devices Reviewed On Apple iPhone 7 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-when-your-logitech-mouse-scroll-stops-turning/"><u>Troubleshooting Tips for When Your Logitech Mouse Scroll Stops Turning</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/windows-studio-options-beyond-moviemaker-for-2024/"><u>Windows Studio Options Beyond MovieMaker for 2024</u></a></li>
</ul></div>

