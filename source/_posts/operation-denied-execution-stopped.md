---
title: "Operation Denied: Execution Stopped"
date: 2025-02-27T23:59:26.275Z
updated: 2025-03-02T04:20:04.441Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Operation Denied: Execution Stopped"
excerpt: "This Article Describes Operation Denied: Execution Stopped"
thumbnail: https://thmb.techidaily.com/a787c6d843bcaac6bb60600aaa2f37966d7c97dba0770c510351be73e79c7abb.jpg
---

## Windows & System Event Notification Services Connection Problem, Fixed

![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7be8093704.jpg)

 Your computer startup very slow? or you cannot log in Windows on your computer with the standard user account? After you log in with an administrative account, you’re seeing an error saying:

**Failed to connect to a windows services**
  
 **Windows could not connect to the System Event Notification Service service.**

 I know you’re likely frustrating. But don’t worry. Usually it’s easy to solve out. Read on to see how…

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
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2c7bbb7b.jpg)
4. Click View installed updates.  
![](https://images.drivereasy.com/wp-content/uploads/2018/11/img_5bf7c2f3ae739.jpg)
5. Find and right-click the update with KB2952664, then Uninstall.

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
<li><a href="https://screen-activity-recording.techidaily.com/new-unlocking-the-secrets-to-efficient-image-capturing/"><u>[New] Unlocking the Secrets to Efficient Image Capturing</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-the-ultimate-tripod-techniques-for-video-creators/"><u>[Updated] The Ultimate Tripod Techniques for Video Creators</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/2024s-elite-selection-the-premier-wireless-mice-reviewed/"><u>2024'S Elite Selection: The Premier Wireless Mice Reviewed</u></a></li>
<li><a href="https://location-social.techidaily.com/does-oppo-a1-5g-have-find-my-friends-drfone-by-drfone-virtual-android/"><u>Does Oppo A1 5G Have Find My Friends? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/eliminate-the-annoying-not-detected-warning-on-your-usb-devices/"><u>Eliminate the Annoying 'Not Detected' Warning on Your USB Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-error-code-0x80071ac3-how-to-resolve-volume-is-dirty-issues/"><u>Fixing Error Code 0X80071AC3: How to Resolve 'Volume Is Dirty' Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-a-frozen-hdd-in-windows-11-expert-tips-for-disk-health-restoration/"><u>How to Troubleshoot a Frozen HDD in Windows 11: Expert Tips for Disk Health Restoration</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-to-simulate-gps-movement-in-ar-games-on-oppo-f25-pro-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How to Simulate GPS Movement in AR games On Oppo F25 Pro 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-light-failure-solutions-on-macoswindows-systems-quick-guide/"><u>Keyboard Light Failure Solutions on macOS/Windows Systems - Quick Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-iastordatasvc-high-cpu-consumption-issue-in-windows-10/"><u>Solving the IAStorDataSvc High CPU Consumption Issue in Windows 10</u></a></li>
<li><a href="https://win-dash.techidaily.com/step-by-step-guide-adding-animated-gifs-to-your-microsoft-powerpoint-presentations/"><u>Step-by-Step Guide: Adding Animated GIFs to Your Microsoft PowerPoint Presentations</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/transform-your-podcast-ideas-into-proficient-scriptwriting-techniques-samples/"><u>Transform Your Podcast Ideas Into Proficient Scriptwriting (Techniques, Samples)</u></a></li>
<li><a href="https://meme-emoji.techidaily.com/updated-2024-approved-add-emojis-to-videos-on-youtubefacebooksnapchat-step-by-step-guide/"><u>Updated 2024 Approved Add Emojis to Videos on YouTube/Facebook/Snapchat Step by Step Guide</u></a></li>
</ul></div>

