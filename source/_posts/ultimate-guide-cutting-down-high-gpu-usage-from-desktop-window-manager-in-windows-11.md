---
title: "Ultimate Guide: Cutting Down High GPU Usage From Desktop Window Manager in Windows 11"
date: 2025-03-01T03:19:34.210Z
updated: 2025-03-02T13:43:19.084Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Ultimate Guide: Cutting Down High GPU Usage From Desktop Window Manager in Windows 11"
excerpt: "This Article Describes Ultimate Guide: Cutting Down High GPU Usage From Desktop Window Manager in Windows 11"
thumbnail: https://thmb.techidaily.com/3a8d29dc752129bc6cecd890184a07ba60927370b95afc8af67003c49b108b72.jpg
---

## Overcome Slow Shutdown Woes in Windows 11 – Effective Strategies Inside

After a day’s work, you click**Shut down** and pack your stuff for leaving. But when you glance at your computer screen, it’s still on the loading screen. You stand and watch it impatiently. Usually, the shutdown process should be taken no more than a few seconds. But when it takes you a lot of time while shutting down, your computer has Windows 10 slow shutdown issue.  
 Don’t worry, you’re not alone. And this issue should be easy to fix.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes

1. [**Disconnect your USB-C device before shut down**](https://tools.techidaily.com/drivereasy/download/)
2. [**Run Power Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
3. [**Disable Fast Startup feature**](https://tools.techidaily.com/drivereasy/download/)
4. [**Repair system files**](https://tools.techidaily.com/drivereasy/download/)
5. [**Registry fix**](https://tools.techidaily.com/drivereasy/download/)

### Fix 1: Disconnect your USB-C device before shut down

![](https://images.drivereasy.com/wp-content/uploads/2019/08/619Rf5BkGlL._SL1273_-1019x1024.jpg)

 USB Type-C sample  
 Photo from Amazon

 Microsoft has confirmed that there’s a new bug which will affect your computer shut down process slowly. The bug in the USB Type-C Connector System Software Interface (UCSI) software may cause a 1 minute delay for Windows 10 to shut down.

**Note** : This bug only affects with Windows shut down, won’t influence normal functionality on your computer. And it will work normally after restarting the system.

The solution for this bug is very simple.

 Disconnect your USB Type-C devices before you shut down your computer. So this bug won’t affect your shutdown process.

### Fix 2: Run Power Troubleshooter

 Windows has built-in troubleshooter to fix some common errors. You can try Power Troubleshooter to fix the slow shut down issue.

1. Press the**Windows logo key + I** to open**Settings** .
2. Click**Update & Security** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/2-3.jpg)
3. Choose**Troubleshoot** in the left pane. Then click**Power** and click**Run the troubleshooter** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/08/power-1.jpg)
4. Follow the on-screen instructions to finish the process.

5. Reboot your computer to apply the changes.

### Fix 3: Disable Fast Startup feature

 If your Fast Startup is enabled, when you shut down the computer, you may encounter slow shutdown or back to the Windows Lock Screen.  
 Fast Startup is supposed to reduce startup time by pre-loading some boot information before your PC shuts off. But when it’s enabled and you shut down the computer, all sessions logged off and the computer enters hibernation. This feature may slow down shutdown speed for your computer.  
 To solve it, you can simply disable the Fast Startup.

1. Press the **Windows logo key + Pause** and click **Control Panel Home** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/07/0-1.jpg)
2. Change **View by Large icons** and click **Power Options** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/07/1-11.jpg)
3. Click **Choose what the power button do** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/07/2-9.jpg)
4. Click **Change settings that are currently unavailable** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/07/3-8.jpg)
5. Make sure you uncheck **Turn on fast startup (recommended)** . Then click **Save Changes** .  

![](https://images.drivereasy.com/wp-content/uploads/2019/07/4-7.jpg)
6. Reboot your computer to apply the changes.

### Fix 4: Repair system files

 The corrupted system file will let the system take more time to shut down your computer. To solve it, you can use System File Checker (SFC) to repair the broken system files.

1. On your keyboard, press the **Windows logo key** and **R** key at the same time to invoke the Run box.
2. Type “cmd” and press **Shift** +**Ctrl** +**Enter** together to open Command Prompt in the administrator mode.  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/command-prompt-1.jpg)  
**Note** : Do **NOT** click OK or just press the Enter key as that won’t allow you to open Command Prompt in the administrator mode.

3. Type “sfc /scannow” in the window and press **Enter** . Then wait for the verification is 100% complete.  
![](https://images.drivereasy.com/wp-content/uploads/2019/04/Snap4.jpg)
4. Reboot your computer to check the changes.

 If the result indicates that there are broken files exists but SFC can’t fix it, you can turn to Deployment Image Servicing and Management (DISM) Tool for deeper examine and repair.  
 Click [here](https://tools.techidaily.com/drivereasy/download/) for a tutorial on how to use the DISM Tool.

### Fix 5: Registry fix

 If the above fixes can’t help, you can try this one. The corruption of registry files may the reason for the slow shut down issue. You can solve the issue by following the below steps:

1. Press the**Windows logo key + R** to open the Run box.
2. Type “regedit” and press**Enter** to open**Registry Edition** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/registry.jpg)
3. Copy and paste the text into the address bar and press**Enter** .  

 “ **Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control\\Session Manager\\Memory Management** “.
4. Double-click**ClearPageFileAtShutdown** , change the value to**0** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/shut.jpg)
5. Copy and paste the text into the address bar and press Enter.  

 “ **Computer\\HKEY\_LOCAL\_MACHINE\\SYSTEM\\CurrentControlSet\\Control** “.
6. Find**WaitToKillServiceTimeout** file in the right pane. Double click it and set the value between**1000 to 20000** .  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/shut1.jpg)
7. Click**OK** .

8. Reboot your computer to apply the changes.

## Bonus: Update your driver

 If there’re any old or corrupted drivers on your Windows 10 PC, this will cause trouble to your computer. To get a better-using experience and prevent your computer from trouble, it’s important to keep your device drivers up-to-date.

 You can do this manually by downloading the latest drivers from the devices’ manufacturer official website. This will take time and need a litter computer knowledge. If you want to save some time or not confident with drivers, you can use **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  to do it automatically.

1. **[Download](https://tools.techidaily.com/drivereasy/download/)**  and install Driver Easy.
2. Run Driver Easy and click Scan Now button. Driver Easy will then scan your computer and detect any problem drivers. You sound driver is no exception.  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/NVIDIA-18.jpg)
3. Click **Update All** to automatically download and install the correct version of _all_ the drivers that are missing or out of date on your system (this requires the **[Pro version](https://tools.techidaily.com/drivereasy/download/)**  – you’ll be prompted to upgrade when you click Update All).  

**Note** : You can do it for free if you like, but it’s partly manual.  
![](https://images.drivereasy.com/wp-content/uploads/2019/08/NVIDIA-Geoforce.jpg)
4. Reboot your Windows 10 computer and check the issue.

 Hopefully, the above methods can help you to fix your problem. If you have any suggestions or questions, feel free to leave your comments below.

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
<li><a href="https://some-guidance.techidaily.com/new-unpacking-virtual-reality-its-upside-and-downside/"><u>[New] Unpacking Virtual Reality Its Upside & Downside</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-exploring-new-frontiers-in-gaming-recording-tech-for-2024/"><u>[Updated] Exploring New Frontiers in Gaming Recording Tech for 2024</u></a></li>
<li><a href="https://article-posts.techidaily.com/2024-approved-system-requirements-guide-for-the-latest-mac-os-release/"><u>2024 Approved System Requirements Guide for the Latest Mac OS Release</u></a></li>
<li><a href="https://common-error.techidaily.com/defeat-windows-1s10-update-error-code-0x800f0922-with-these-8-expert-fixes/"><u>Defeat Windows 1ˈs10 Update Error Code 0X800F0922 with These 8 Expert Fixes</u></a></li>
<li><a href="https://discover-blog.techidaily.com/enhanced-targeting-with-advanced-cookie-tracking-technology/"><u>Enhanced Targeting with Advanced Cookie Tracking Technology</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-solving-when-hamachi-service-stops-working/"><u>Expert Tips for Solving When Hamachi Service Stops Working</u></a></li>
<li><a href="https://techtrends.techidaily.com/how-to-fix-code-39-errors-in-windows/"><u>How to Fix Code 39 Errors in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-regain-access-to-lost-steam-game-files-complete-solution/"><u>How to Regain Access to Lost Steam Game Files - Complete Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-stop-your-pc-from-starting-automatically-on-windows-11/"><u>How To Stop Your PC From Starting Automatically on Windows 11?</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207884086-resolve-too-many-redirects-error-with-simple-fixes/"><u>Resolve Too Many Redirects Error with Simple Fixes</u></a></li>
<li><a href="https://fox-access.techidaily.com/soundscapes-for-phones-how-to-curate-tamil-ringtone-tracks/"><u>Soundscapes for Phones How to Curate Tamil Ringtone Tracks</u></a></li>
<li><a href="https://fox-blue.techidaily.com/the-evaluation-of-hdr-quality-with-luminance/"><u>The Evaluation of HDR Quality with Luminance</u></a></li>
</ul></div>

