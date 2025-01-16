---
title: LSA Safety Measures Fully Operational Again - Secure Your System Now
date: 2025-01-13T16:07:24.555Z
updated: 2025-01-16T16:20:01.712Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes LSA Safety Measures Fully Operational Again - Secure Your System Now
excerpt: This Article Describes LSA Safety Measures Fully Operational Again - Secure Your System Now
thumbnail: https://thmb.techidaily.com/533486c883f0e15f79a205d8fe00d7b629c80c76eca7c3b378cb3f9eeb4c0bbe.jpg
---

## LSA Safety Measures Fully Operational Again - Secure Your System Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

## Try these fixes to enable the Local Security Authority Protection

 As mentioned, in most cases, your Local Security Authority is off because of a UI bug with a Windows patch, so the first method should be enough to help. If it doesn’t, please move on to methods 2 and 3.

1. **[Install Windows Update patch KB5007651](#m1)**
2. **[Modify Registry Editor](#m2)**
3. **[Configure Group Policy Editor](#m3)**

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/uSfA74aeYeA?si=HdJSMdeS7HVtS6-j" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/E3yY7lZ-FKA?si=g8VEuExP8GH59B69" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/1rCjQ09iG7s?si=Si1fUBric8MH1VHI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/pejPLJBLmXw?si=WD97jA3doqbMCkCX" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

 If the “Local Security protection is off” notification is still there when you manually install the KB5007651 update, please move on to the next fix.

---

## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/Dn-24B6AURY?si=ErES2KWVnintY6h9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/YezPJZzPJ8Q?si=xF1t4BQHFquzvnzE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/e4Nt2xXXtmE?si=CtKwFry4b0AJXnaN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

 Fortect comes with a 60-day Money-Back Guarantee. If you’re not satisfied with Fortect, you can contact <support@fortect.com> for a full refund.

 Still unsure if Fortect is what you need? Check this [Fortec Review](https://tools.techidaily.com/drivereasy/download/) !

---

 The above is what we have to offer regarding “Local Security Authority protection is off” problem. If you have any other suggestions, please feel free to leave a comment below.

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
<li><a href="https://fox-boxes.techidaily.com/new-the-comedic-journey-an-evaluation-of-goofy-adventures/"><u>[New] The Comedic Journey An Evaluation of 'Goofy Adventures'</u></a></li>
<li><a href="https://screen-capture.techidaily.com/updated-2024-approved-precisionscreenrecorder-capture-anytime/"><u>[Updated] 2024 Approved PrecisionScreenRecorder - Capture Anytime</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-2024-approved-unlocking-the-potential-of-facetime-voice-logging/"><u>[Updated] 2024 Approved Unlocking the Potential of FaceTime Voice Logging</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-in-2024-essential-top-5-iphone-podcast-apps/"><u>[Updated] In 2024, Essential Top 5 iPhone Podcast Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-when-your-pc-wont-exit-windows-10-properly/"><u>Effective Fixes for When Your PC Won't Exit Windows 10 Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-damaged-files-and-directories-that-wont-open/"><u>How to Fix Damaged Files & Directories That Won't Open</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-pokemon-go-joystick-on-vivo-v27-pro-drfone-by-drfone-virtual-android/"><u>How to use Pokemon Go Joystick on Vivo V27 Pro? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-4-methods-to-turn-off-life-360-on-oneplus-open-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, 4 Methods to Turn off Life 360 On OnePlus Open without Anyone Knowing | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-dose-life360-notify-me-when-someone-checks-my-location-on-nokia-c110-drfone-by-drfone-virtual-android/"><u>In 2024, Dose Life360 Notify Me When Someone Checks My Location On Nokia C110? | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-navigating-aspers-methodology-for-sleep-success/"><u>In 2024, Navigating Asper's Methodology for Sleep Success</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-resolving-non-functioning-lenovo-fingerprint-scanner-issues/"><u>Quick Fixes: Resolving Non-Functioning Lenovo Fingerprint Scanner Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-launch-errors-what-to-do-when-minecraft-fails-to-start-in-windows/"><u>Resolving Launch Errors: What to Do When Minecraft Fails to Start in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-common-update-failed-mistakes-in-warframe-a-comprehvee-guide/"><u>Resolving the Common 'Update Failed' Mistakes in Warframe - A Comprehvee Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-steps-fixing-shockwave-flash-issues-on-google-chrome/"><u>Solution Steps: Fixing Shockwave Flash Issues on Google Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-game-related-pc-restarts-on-various-windows-platforms-11-10-7-81-and-eight/"><u>Solving Game-Related PC Restarts on Various Windows Platforms - 11, 10, 7, 8.1 & Eight</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211260772-step-by-step-guide-to-restore-lost-devices-in-overwatch-quick-resolution-tips/"><u>Step-by-Step Guide to Restore Lost Devices in Overwatch - Quick Resolution Tips!</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-9-oppo-reno-8t-5g-monitoring-apps-for-parental-controls-drfone-by-drfone-virtual-android/"><u>Top 9 Oppo Reno 8T 5G Monitoring Apps for Parental Controls | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-solving-your-pcs-persistent-freezing-problem/"><u>Ultimate Guide: Solving Your PC's Persistent Freezing Problem</u></a></li>
<li><a href="https://article-files.techidaily.com/voicing-victory-tactics-in-free-fire-games/"><u>Voicing Victory Tactics in Free Fire Games</u></a></li>
</ul></div>

