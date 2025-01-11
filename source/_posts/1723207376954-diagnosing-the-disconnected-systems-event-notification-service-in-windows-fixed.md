---
title: Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed
date: 2025-01-06T20:01:52.943Z
updated: 2025-01-10T19:10:40.596Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed
excerpt: This Article Describes Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed
thumbnail: https://thmb.techidaily.com/015ca8337481fa9d7a46737ec3890e681969035749527955b33fb723b973c5c1.jpg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/zXUt81WsQpI?si=W3DKIAsa2-qbGadJ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## Try these fixes

 The methods below have helped other users solve the problem. You may not have to try them all; just work your way down the list until you find the one that works for you.

1. **[Check the setting of System Event Notification Service on your computer](https://tools.techidaily.com/drivereasy/download/)**
2. **[Reset your Winsock Catalog](https://tools.techidaily.com/drivereasy/download/)**
3. **[Update your video card driver](https://tools.techidaily.com/drivereasy/download/)**
4. **[Uninstall the KB2952664 update](https://tools.techidaily.com/drivereasy/download/)**
5. [**Remove klhkum.dll**](https://tools.techidaily.com/drivereasy/download/)

 The following screenshots are from Windows 10\. But you can also follow the steps if you’re having the problem on Windows 7.

### Fix 1: Check the setting of System Event Notification Service on your computer

 You may have the problem due to the incorrect setting of System Event Notification Service.  
 Follow these steps to modify the setting:

1. On your keyboard, hold down the**Windows logo key** and**R** to invoke the Run box.
2. Type**services.msc** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf596c06c.jpg)
3. Right-click**System Event Notification Service** , then select**Restart** . If Restart grayed out, click**Start** instead.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bf9e2c9b8.jpg)
4. Right-click System Event Notification Service again, this time select**Properties** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GU08CQVsZz0?si=V-SvPfzRsQysMS0e" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c08c50e91.jpg)

 Restart your computer to see if the error has gone. If you still see the error, you have something else to try…

---

### Fix 2: Reset your Winsock Catalog

 You very likely have the problem on your computer that joins in a domain network. You could have problem due to some interference of your Winsock Catalog setting.

Follow these steps to reset your Winsock Catalog:

1. On your keyboard, hold down the**Windows logo key** and press**R** to invoke the Run box.
2. Type**cmd** , then press**Shift + Ctrl + Enter** keys together.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c0804d3b9.jpg)
3. An elevated Command Prompt would be open. Type the following command and press Enter.  
**netsh winsock reset**

 Restart your computer to see if the error has gone. If you still see the error, don’t worry, move onto the next methods.  
 If resetting Winsock worked temporarily, you can move to Fix 5.

---

### Fix 3: Update your video card driver

 You could probably encounter this error if the video card driver on your computer is outdated, incompatible or corrupt. So you should**update your video card driver** to see if it fixes your problem. If you don’t have the time, patience or skills to update the driver manually, you can do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to be troubled by the wrong driver you would be downloading, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 steps (and you get**full support and a 30-day money back guarantee** ):

1. [**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.
2. Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c1c42f3f2.jpg)
3. C  lick **Update All** to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  
**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/sn2STvYRVb8?si=Z-XhJJ1Mc-Em5Kqy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GyfJUhsz_AY?si=x2HjoLX1B89oEPgZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/l-SCWTWpegY?si=oxTsHQkIu1v4-I6b" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Restart your computer to see if the error has gone.

---

### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/kiW7sLvL65k?si=IHSeRFsYCrfqpn2o" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 One more tip: If you’re using Kaspersky security software and possibly on Windows 7, you need to turn off Kaspersky manually to fix the issue.

---

 Tada! Hopefully this helps. Feel free to comment below with your own experiences.

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
<li><a href="https://fox-helps.techidaily.com/new-2024-approved-experience-the-magic-of-free-voice-change-for-valorant-gaming/"><u>[New] 2024 Approved Experience the Magic of Free Voice Change for Valorant Gaming</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-harnessing-lut-power-for-free-high-quality-colorization/"><u>[New] Harnessing LUT Power for Free, High-Quality Colorization</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-mastery-in-documentary-writing-essential-techniques/"><u>2024 Approved Mastery in Documentary Writing Essential Techniques</u></a></li>
<li><a href="https://extra-support.techidaily.com/2024-approved-premier-mac-mkv-solvers-list/"><u>2024 Approved Premier Mac MKV Solvers List</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/exploring-the-worthiness-is-chatgpt-plus-an-essential-ai-tool-for-you/"><u>Exploring the Worthiness: Is ChatGPT Plus an Essential AI Tool for You?</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-that-irritatingly-flashing-cursor-on-your-screen-tips-and-tricks/"><u>Fix That Irritatingly Flashing Cursor on Your Screen - Tips and Tricks</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-laptops-charging-issue-instantly-simple-steps/"><u>Fix Your Laptop's Charging Issue Instantly - Simple Steps!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-computer-that-gets-stuck-during-initial-windows-setup/"><u>How to Fix a Computer That Gets Stuck During Initial Windows Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/icue-troubleshooting-made-easy-resolving-undetected-device-errors/"><u>ICUE Troubleshooting Made Easy: Resolving Undetected Device Errors</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-foremost-editing-tools-for-device-developers/"><u>In 2024, Foremost Editing Tools for Device Developers</u></a></li>
<li><a href="https://novels-ebooks.techidaily.com/95635511-9781633410169-love-magic/"><u>Love Magic | Free Book</u></a></li>
<li><a href="https://common-error.techidaily.com/print-screen-key-malfunction-in-windows-1110-solutions-that-work/"><u>Print Screen Key Malfunction in Windows 11/10 – Solutions That Work!</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-error-fixing-print-driver-host-crash-in-32-bit-software/"><u>Resolved: Error Fixing 'Print Driver Host' Crash in 32-Bit Software</u></a></li>
<li><a href="https://win-news.techidaily.com/techniques-optimales-pour-synchroniser-des-fichiers-en-temps-reel-sous-windows-7-8-et-10/"><u>Techniques Optimales Pour Synchroniser Des Fichiers en Temps Réel Sous Windows 7, 8 Et 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-repairing-non-working-usb-ports-on-your-hp-laptop/"><u>Troubleshooting and Repairing Non-Working USB Ports on Your HP Laptop</u></a></li>
</ul></div>

