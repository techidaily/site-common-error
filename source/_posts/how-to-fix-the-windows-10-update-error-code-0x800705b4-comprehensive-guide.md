---
title: How to Fix the Windows 10 Update Error Code 0X800705b4 – Comprehensive Guide
date: 2024-09-15T18:06:56.013Z
updated: 2024-09-20T19:20:54.011Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix the Windows 10 Update Error Code 0X800705b4 – Comprehensive Guide
excerpt: This Article Describes How to Fix the Windows 10 Update Error Code 0X800705b4 – Comprehensive Guide
thumbnail: https://thmb.techidaily.com/501cfbb0674181793ce2cd8353fd1c77b58868d2c9678fbe9da8ac95eb395e1d.jpg
---

## Comprehensive Guide: Resolve Windows Update Error 0X8024002E Once and For All

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
7. Click**Restart** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/03/img_5abb3516e8887.png)
8. Run Windows Update and see if the “0x8024002e” error occurs. If not, proceed to the**next step** to find out the application or service that causes trouble.**Otherwise** skip all the steps below and try**other** **methods** .
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
<li><a href="https://fox-boxes.techidaily.com/new-2024-approved-detailed-examination-of-djis-latest-uav-inspire-1/"><u>[New] 2024 Approved Detailed Examination of DJI's Latest UAV, Inspire 1</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-directly-posting-tiktok-videos-onto-your-facebook-timeline-for-2024/"><u>[Updated] Directly Posting TikTok Videos Onto Your Facebook Timeline for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/updated-gigglegrid-create-social-media-laughs-in-seconds/"><u>[Updated] GiggleGrid Create Social Media Laughs in Seconds</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-ultimate-showdown-battle-royales-top-titles/"><u>[Updated] Ultimate Showdown Battle Royale's Top Titles</u></a></li>
<li><a href="https://article-tips.techidaily.com/cultivate-chuckle-inducing-visuals-on-giphy-for-2024/"><u>Cultivate Chuckle-Inducing Visuals on Giphy for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-7-sudden-crashes-and-unexpected-freezes-step-by-step-guide/"><u>How to Fix Windows 7 Sudden Crashes and Unexpected Freezes - Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-network-troubleshooting-how-to-correctly-repair-your-pcs-ethernet-connection-for-windows-7-and-10-devotees/"><u>Mastering Network Troubleshooting: How To Correctly Repair Your PC's Ethernet Connection for Windows 7 & 10 Devotees</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/poll-power-players-quintessential-politic-games-for-2024/"><u>Poll Power Players Quintessential Politic Games for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/simplifying-smartphone-productivity-emulate-pc-window-management-for-efficient-task-handling/"><u>Simplifying Smartphone Productivity: Emulate PC Window Management for Efficient Task Handling</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-found-fixing-pixel-format-not-accelerated-lwjgl-exception-error/"><u>Solution Found! Fixing 'Pixel Format Not Accelerated' LWJGL Exception Error</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-getting-your-lenovo-laptops-webcam-back-online/"><u>Step-by-Step Solutions: Getting Your Lenovo Laptop's Webcam Back Online</u></a></li>
<li><a href="https://common-error.techidaily.com/trouble-with-file-explorer-fix-it-swiftly-on-windows-10/"><u>Trouble with File Explorer? Fix It Swiftly on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-fixes-for-non-responsive-brightness-buttons-in-windows-10/"><u>Ultimate Fixes for Non-Responsive Brightness Buttons in Windows 10</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/unlock-a-broader-audience-strategies-for-multistreaming-on-youtube-and-twitch-for-2024/"><u>Unlock a Broader Audience Strategies for Multistreaming on Youtube and Twitch for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-error-0x800f081f-effective-fixes-to-secure-your-net-framework-35-installation-on-windows-systems/"><u>Winning Against Error 0X800F081F – Effective Fixes to Secure Your .NET Framework 3.5 Installation on Windows Systems</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135408/19272" target="_top" id="2135408">
  <img src="//a.impactradius-go.com/display-ad/19272-2135408" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135408/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

