---
title: Fix Windows Update Error Code 0X80070002 Quickly & Easily | Expert Guide
date: 2024-10-20T17:11:31.016Z
updated: 2024-10-24T22:50:33.141Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fix Windows Update Error Code 0X80070002 Quickly & Easily | Expert Guide
excerpt: This Article Describes Fix Windows Update Error Code 0X80070002 Quickly & Easily | Expert Guide
thumbnail: https://thmb.techidaily.com/60fe1a74657905b47d054d52197782d9df31df8374f9444c7a6b8dc97d98722a.jpg
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
<a href="https://appsumo.8odi.net/c/5597632/2049387/7443" target="_top" id="2049387">
  <img src="//a.impactradius-go.com/display-ad/7443-2049387" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2049387/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Fix 2: Modify your Windows setting in the registry

 This issue can also be fixes by adjusting a Windows Update setting in the registry. Here is how:

 You may experience serious problems if you don’t modify your registry properly. So be careful for what you’re doing in registry. And in case anything goes wrong, you can back up your registry, which you’ll know how by going through the steps below.

1. Press the**Windows logo key** and**R** on your keyboard at the same time to invoke the Run box.
2. Type “regedit” in the Run box and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-905.png)
3. If prompted, click**Yes** .

<!-- affiliate ads begin -->
<a href="https://versadesk.pxf.io/c/5597632/1815679/21290" target="_top" id="1815679">
  <img src="//a.impactradius-go.com/display-ad/21290-1815679" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://versadesk.pxf.io/i/5597632/1815679/21290" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. On the Registry Editor, click**File** , then select**Export** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-917.png)
5. Select_a place to save your backup copy_ , then click**Save** to save the backup.  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-918.png)
6. Wait for the export process to be complete.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2087394/7443" target="_top" id="2087394">
  <img src="//a.impactradius-go.com/display-ad/7443-2087394" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2087394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Go to _HKEY\_LOCAL\_MACHINE\\Software\\Policies\\Microsoft\\Windows\\WindowsUpdate_ .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-919.png)
8. Double click**DisableWindowsUpdateAccess** .  

<!-- affiliate ads begin -->
<span id="1770526">
					<video width="240" height="480" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1770526.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/20702-1770526">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1770526.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:150px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Ftokenmetrics.sjv.io%2Fc%2F5597632%2F1770526%2F20702'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1770526/20702" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-920.png)
9. Change the**value data** to**0** , then click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/09/image-923.png)

 Now try running Windows Update. If the steps above worked for you, you won’t see the “0x8024002e” error there.

## Fix 3: Perform a clean boot

 Your 0x8024002e error can be caused by software conflicts. And to see if that’s the case for you, you can try performing a clean boot, disabling all non-essential services and startup programs. Then see if the error is gone.

To do so:

1. Press the**Windows log key** and**R** on your keyboard to invoke the Run dialog.
2. Type “**msconfig** ” and press**Enter** on your keyboard.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
3. Click the**Services** tab. Then check**Hide all Microsoft services** (**FIRST** ) and click**Disable all** . After that, click**OK** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb19193a7d5.png)
4. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)
5. Right click**each enabled Startup item** , then click**Disable** . After that, close Task Manager.![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb40476a45c.jpg)
6. Click**OK** .

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880972/19272" target="_top" id="1880972">
  <img src="//a.impactradius-go.com/display-ad/19272-1880972" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880972/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043639/7443" target="_top" id="2043639">
  <img src="//a.impactradius-go.com/display-ad/7443-2043639" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043639/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
10. Click the**Services** tab. Check**Hide all Microsoft services** . Then**enable** **any** disabled service (by**selecting its checkbox** ) and click**OK** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3b3ebfca4.png)
11. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
12. Check to see if the update error occurs. If it doesn’t, repeat step**9 to 11**  until you find out the service that causes the issue. If none of these services is the culprit, try the steps below.  
 If there’s any service that brings up the 0x8024002e error, you should do some research on the Internet to see what program is this service related to. Then contact the vendor of this program or your system for advice, or use an alternative solution.
13. Press the**Windows log key** and**R** on your keyboard. Then type “**msconfig** ” and press**Enter** on your keyboard.  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb16efa1a4f.png)
14. Click the**Startup** tab, then click**Open Task Manager** .![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3e91a6b28.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1896546/19272" target="_top" id="1896546">
  <img src="//a.impactradius-go.com/display-ad/19272-1896546" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1896546/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://video-capture.techidaily.com/updated-critical-analysis-of-the-best-free-video-chat-software-suitable-for-businesses-and-educators/"><u>[Updated] Critical Analysis of the Best Free Video Chat Software Suitable for Businesses & Educators</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-first-home-frontier-top-6-beginner-friendly-mc-abodes/"><u>[Updated] First Home Frontier Top 6 Beginner-Friendly MC Abodes</u></a></li>
<li><a href="https://common-error.techidaily.com/brightening-difficulty-windows-update-issue/"><u>Brightening Difficulty: Windows Update Issue</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/exploring-the-attraction-of-gpt-for-hacking/"><u>Exploring the Attraction of GPT for Hacking</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-overwatch-chatter-breakdowns-effortlessly-with-these-tricks/"><u>Fix Your Overwatch Chatter-Breakdowns Effortlessly with These Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-reactivate-your-quick-search-solving-the-problem-with-windows-plus-shift-plus-s-on-pcs/"><u>Guide to Reactivate Your Quick Search: Solving the Problem with Windows + Shift + S on PCs</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/24-4-creative-ways-to-insert-youtube-content-in-presentations/"><u>In 2024, 4 Creative Ways to Insert YouTube Content in Presentations</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/in-depth-analysis-of-the-oculus-quest-2-superb-value-for-premium-vr-gaming/"><u>In-Depth Analysis of the Oculus Quest 2: Superb Value for Premium VR Gaming</u></a></li>
<li><a href="https://activate-lock.techidaily.com/new-guide-how-to-check-icloud-activation-lock-status-from-your-apple-iphone-12-mini-by-drfone-ios/"><u>New Guide How To Check iCloud Activation Lock Status From Your Apple iPhone 12 mini</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-usb-device-not-accepted-challenge-expert-advice-and-fixes/"><u>Overcoming the 'USB Device Not Accepted' Challenge: Expert Advice and Fixes</u></a></li>
<li><a href="https://extra-hints.techidaily.com/pioneers-panoramas-open-for-all/"><u>Pioneer's Panoramas Open for All</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-eliminating-windows-11-flicker-effect/"><u>Step-by-Step Guide: Eliminating Window's 11 Flicker Effect</u></a></li>
<li><a href="https://win-howtos.techidaily.com/troubleshooting-tips-for-fixing-a-broken-lenovo-print-recognition-feature/"><u>Troubleshooting Tips for Fixing a Broken Lenovo Print Recognition Feature</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-to-successfully-pair-your-xbox-one-controller/"><u>Troubleshooting: Steps to Successfully Pair Your Xbox One Controller</u></a></li>
</ul></div>

