---
title: "Gaming Gridlock: Frequent Freezes on OS"
date: 2024-09-25T21:13:10.729Z
updated: 2024-10-02T04:23:32.865Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Gaming Gridlock: Frequent Freezes on OS"
excerpt: "This Article Describes Gaming Gridlock: Frequent Freezes on OS"
thumbnail: https://thmb.techidaily.com/c8505bae3e314a2b381005e22ef6317da32419f0b4525c4f54b2150317447813.jpg
---

## Urgent Fix Required: Enable Local Authorization Defenses Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## Try these fixes to enable the Local Security Authority Protection

 As mentioned, in most cases, your Local Security Authority is off because of a UI bug with a Windows patch, so the first method should be enough to help. If it doesn’t, please move on to methods 2 and 3.

1. **[Install Windows Update patch KB5007651](#m1)**
2. **[Modify Registry Editor](#m2)**
3. **[Configure Group Policy Editor](#m3)**

---

<!-- affiliate ads begin -->
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1584040/17916" target="_top" id="1584040">
  <img src="//a.impactradius-go.com/display-ad/17916-1584040" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1584040/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1938750/19272" target="_top" id="1938750">
  <img src="//a.impactradius-go.com/display-ad/19272-1938750" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1938750/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1886044/19272" target="_top" id="1886044">
  <img src="//a.impactradius-go.com/display-ad/19272-1886044" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1886044/19272" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://jalbum-affiliate-program.sjv.io/c/5597632/1838960/17916" target="_top" id="1838960">
  <img src="//a.impactradius-go.com/display-ad/17916-1838960" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://jalbum-affiliate-program.sjv.io/i/5597632/1838960/17916" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2052062/7443" target="_top" id="2052062">
  <img src="//a.impactradius-go.com/display-ad/7443-2052062" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2052062/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## Bonus tip

 If turning on the Local Security Authority protection doesn’t help to fix your computer problems, you can always try to repair any damaged or corrupted system files, as**the integrity of Windows system files is** essential for proper operation and stability for your computer.

 Tools like **[Fortect](https://tools.techidaily.com/drivereasy/download/)**  can automate the repair process by scanning system files and replacing corrupted ones.

1. [Download](https://tools.techidaily.com/drivereasy/download/) and install Fortect.
2. Open Fortect. It will run a free scan of your PC and give you**a detailed report of your PC status** .  
![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-scan.jpg)
3. Once finished, you’ll see a report showing all the issues. To fix all the issues automatically, click**Start Repair** (You’ll need to purchase the full version. It comes with a**60-day Money-Back Guarantee** so you can refund anytime if Fortect doesn’t fix your problem).  

![](https://images.drivereasy.com/wp-content/uploads/2020/10/fortect-start-repair.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2037335/7443" target="_top" id="2037335">
  <img src="//a.impactradius-go.com/display-ad/7443-2037335" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2037335/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-rev-up-your-video-earning-game-with-vimeo-strategies/"><u>[New] 2024 Approved Rev Up Your Video Earning Game with Vimeo Strategies</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-all-about-farming-on-ginger-isle-for-2024/"><u>[Updated] All About Farming on Ginger Isle for 2024</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-mastering-tiktok-streams-top-4-methods-on-pc/"><u>[Updated] Mastering TikTok Streams Top 4 Methods on PC</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-broadcast-battle-which-platform-wins/"><u>2024 Approved Broadcast Battle Which Platform Wins?</u></a></li>
<li><a href="https://iphone-location.techidaily.com/does-pokegoplusplus-still-work-on-apple-iphone-14-proipad-drfone-by-drfone-virtual-ios/"><u>Does PokeGo++ still work on Apple iPhone 14 Pro/iPad? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-for-handling-windows-11s-0xc1900208-installation-hurdle/"><u>Effective Strategies for Handling Windows 11'S 0xC1900208 Installation Hurdle</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcoming-the-windows-11-cant-be-installed-issue-with-error-code-80240020-solved/"><u>Guide to Overcoming the 'Windows 11 Can't Be Installed' Issue with Error Code 80240020 [Solved]</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-infinix-hot-40-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206395864-how-to-get-your-windows-11-touchpad-working-perfectly-again/"><u>How To Get Your Windows 11 Touchpad Working Perfectly Again.</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-turn-off-overlay-effects-in-nvidia-graphics/"><u>How to Turn Off Overlay Effects in NVIDIA Graphics</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-fingerprint-recognition-problems-heres-how-you-can-repair-it-easily/"><u>Lenovo Fingerprint Recognition Problems? Here's How You Can Repair It Easily!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/mastering-electronics-reliable-reviews-and-tips-by-toms-hardware-experts/"><u>Mastering Electronics: Reliable Reviews and Tips by Tom’s Hardware Experts</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/smoothing-out-aerial-footage-pulsation-for-2024/"><u>Smoothing Out Aerial Footage Pulsation for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fixes-for-the-container-objects-not-listed-error-in-windows-11/"><u>Step-by-Step Fixes for the 'Container Objects Not Listed' Error in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-lenovo-mouse-pad-issues-on-windows-11-8-and-7-effective-solutions/"><u>Troubleshooting Lenovo Mouse Pad Issues on Windows 11, 8 & 7: Effective Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/unveiling-remedies-how-to-revive-your-windows-when-faced-with-a-perplexing-black-barrier/"><u>Unveiling Remedies: How to Revive Your Windows When Faced With a Perplexing Black Barrier</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-11-guide-addressing-the-laptop-not-charging-while-connected-dilemma/"><u>Windows 11 Guide: Addressing the 'Laptop Not Charging While Connected' Dilemma</u></a></li>
</ul></div>

