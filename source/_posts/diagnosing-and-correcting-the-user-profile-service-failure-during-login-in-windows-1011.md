---
title: Diagnosing and Correcting the 'User Profile Service' Failure During Login in Windows 10/11
date: 2024-09-24T23:29:56.218Z
updated: 2024-10-02T03:15:02.951Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnosing and Correcting the 'User Profile Service' Failure During Login in Windows 10/11
excerpt: This Article Describes Diagnosing and Correcting the 'User Profile Service' Failure During Login in Windows 10/11
thumbnail: https://thmb.techidaily.com/a4dcf98f3406d7e5d0dc2d2c190aac822aae79b2e5cb3a27a5cb90894f8b169b.jpg
---

## Diagnosing the Disconnected Systems Event Notification Service in Windows - Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2129740/7443" target="_top" id="2129740">
  <img src="//a.impactradius-go.com/display-ad/7443-2129740" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2129740/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7bfcea31f4.jpg)
5. Set the**Startup type** to**Automatic** . Then click **Apply**  \> **OK** .  
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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137413/7443" target="_top" id="2137413">
  <img src="//a.impactradius-go.com/display-ad/7443-2137413" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137413/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1885943/19272" target="_top" id="1885943">
  <img src="//a.impactradius-go.com/display-ad/19272-1885943" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1885943/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2297ff06.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135349/19272" target="_top" id="2135349">
  <img src="//a.impactradius-go.com/display-ad/19272-2135349" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135349/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Restart your computer to see if the error has gone. If the error persists, don’t give up hope, see if the last method could help you…

---

### Fix 4: Uninstall the KB2952664 update

 According to many users’ report, this error could be due to the**KB2952664** Windows Update. If none of the methods above helps you, go with the following steps to**uninstall the KB2952664 update** on your computer:

1. On your keyboard, press the**Windows logo key** and**R** to invoke the Run box.
2. Type**control** and press**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c29a46965.jpg)
3. Select**Uninstall a program** under**Programs** when**View by Category** selected.  

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

Restart your computer to see if the error has gone.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135357/19272" target="_top" id="2135357">
  <img src="//a.impactradius-go.com/display-ad/19272-2135357" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135357/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Fix 5: Remove klhkum.dll

 If you have to reset Winsock tens of times a day, you need to try this method. What you should do is checking whether you have “klhkum.dll” or not.

 klhkum.dll’s description is “**System Interceptors PDK usermode service interceptor** ” and it’s intercepting the system when it shouldn’t.  
 So how to remove it? Follow the guide:

1. Press**Ctrl+Shift+Esc** to open the Task Manager.
2. Click the**Startup** tab and find**klhkum.dll** process.  
![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-52-10.jpg)
3. Right-click on it and choose**Disable** . You can also open its file location and delete it permanently.  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144285/7443" target="_top" id="2144285">
  <img src="//a.impactradius-go.com/display-ad/7443-2144285" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144285/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/12/2020-03-31_18-55-36.jpg)
4. Restart your computer to see if the error has gone.

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
<li><a href="https://common-error.techidaily.com/fixed-xerox-update-error-0x800f020b-in-windows/"><u>[FIXED] Xerox Update Error 0X800f020b in Windows</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-10-must-try-facial-editors-on-iphones-and-samsungs/"><u>[New] 10 Must-Try Facial Editors on iPhones and Samsungs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-examining-youtubes-highlighted-comment-mechanics/"><u>[New] In 2024, Examining YouTube's Highlighted Comment Mechanics</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-primeval-20-anime-series-opener-music/"><u>[New] Primeval 20 Anime Series Opener Music</u></a></li>
<li><a href="https://common-error.techidaily.com/tech-insight-fix-windows-dll-issue/"><u>[Tech Insight] Fix Windows DLL Issue</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/updated-2024-approved-continuous-display-recorder/"><u>[Updated] 2024 Approved Continuous Display Recorder</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-recurring-pc-problems-when-playing-minecraft-dungeons-tips-and-solutions/"><u>Fixing Recurring PC Problems When Playing Minecraft Dungeons: Tips & Solutions</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-fix-xiaomi-redmi-k70-find-my-friends-no-location-found-drfone-by-drfone-virtual-android/"><u>How to Fix Xiaomi Redmi K70 Find My Friends No Location Found? | Dr.fone</u></a></li>
<li><a href="https://win-able.techidaily.com/optimizing-performance-keep-fallout-4-running-smoothly-on-pc/"><u>Optimizing Performance: Keep Fallout 4 Running Smoothly on PC</u></a></li>
<li><a href="https://win-answers.techidaily.com/overcome-downloading-difficulties-for-a-smooth-age-of-empires-iv-installation-experience/"><u>Overcome Downloading Difficulties for a Smooth Age of Empires IV Installation Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-early-morning-glitches-how-to-stop-your-windows-10-from-hanging-at-startup/"><u>Overcome Early Morning Glitches: How To Stop Your Windows 10 From Hanging at Startup</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-your-pcs-unwanted-sleeps-simple-fixes-revealed/"><u>Resolve Your PC's Unwanted Sleeps: Simple Fixes Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-call-of-duty-wwii-mishap-fixing-the-error-code-4220/"><u>Resolving Call of Duty WWII Mishap: Fixing the Error Code 4220</u></a></li>
<li><a href="https://common-error.techidaily.com/restore-your-windows-10-mouses-right-click-functionality-with-these-expert-tips/"><u>Restore Your Windows 10 Mouse's Right-Click Functionality with These Expert Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-smooth-scrolling-expert-advice-for-a-broken-logitech-mouse-wheel/"><u>Restoring Smooth Scrolling: Expert Advice for a Broken Logitech Mouse Wheel</u></a></li>
<li><a href="https://howto.techidaily.com/strategies-for-apps-that-wont-download-from-play-store-on-lava-yuva-2-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Strategies for Apps That Wont Download From Play Store On Lava Yuva 2 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-touchscreen-troubles-try-these-5-solutions/"><u>Windows 11 Touchscreen Troubles? Try These 5 Solutions</u></a></li>
</ul></div>

