---
title: "Security Patch Applied: Reinforce Device's Internal Identity Validation Protocols"
date: 2024-09-09T16:03:57.971Z
updated: 2024-09-15T16:00:11.853Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Security Patch Applied: Reinforce Device's Internal Identity Validation Protocols"
excerpt: "This Article Describes Security Patch Applied: Reinforce Device's Internal Identity Validation Protocols"
thumbnail: https://thmb.techidaily.com/773b13fe6e17412a9b5b64d4e711163f73a0c0700089624569da26ef89b36362.jpg
---

## Critical LSA Shield Fully Operational: Revamp Your System's Local Security Today

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

## 1\. Install Windows Update patch KB5007651

 The Local Security Authority Protection being off bug was actually a bug that shipped with Windows 11’s March 2023 mandatory security update, patch KB5007651\. Windows then released the updated version of this patch that fixed this problem. So if you still haven’t already, please update your Windows now for the latest patch KB5007651 to install.

To do so:

1. On your keyboard, hit the**Windows** key, then type**check for update** s, then click C**heck for updates** .  

![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
3. If there are available updates, Windows will automatically download them for you. Restart your computer for the update to take effect if needed.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-20.png)
4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

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

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  

<!-- affiliate ads begin -->
<span id="1938141">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1938141.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1938141">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1938141.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1938141%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1938141/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135397/19272" target="_top" id="2135397">
  <img src="//a.impactradius-go.com/display-ad/19272-2135397" border="0" alt="https://techidaily.com" width="180" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135397/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2126493/26400" target="_top" id="2126493">
  <img src="//a.impactradius-go.com/display-ad/26400-2126493" border="0" alt="https://techidaily.com" width="640" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2126493/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-dynamic-interactions-key-to-enhancing-page-visibility/"><u>[New] In 2024, Dynamic Interactions Key to Enhancing Page Visibility</u></a></li>
<li><a href="https://discord-videos.techidaily.com/new-navigating-everyday-chats-smart-reacts-and-replies-discord-for-2024/"><u>[New] Navigating Everyday Chats Smart Reacts and Replies (Discord) for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-enhancing-switch-gaming-with-top-cards-for-2024/"><u>[Updated] Enhancing Switch Gaming with Top Cards for 2024</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/2024-approved-become-a-gif-expert-in-snapchat-today/"><u>2024 Approved Become a GIF Expert in Snapchat Today</u></a></li>
<li><a href="https://common-error.techidaily.com/error-code-24-a-step-by-step-solution-for-missing-devices-in-windows-10-8-and-7/"><u>Error Code 24 - A Step-by-Step Solution for Missing Devices in Windows 10, 8 & 7</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-learn-how-everything-works-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Learn How Everything Works On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/missing-media-magic-no-videos-on-sony-a6400-for-2024/"><u>Missing Media Magic No Videos on Sony A6400 for 2024</u></a></li>
<li><a href="https://ai-video-tools.techidaily.com/new-virtualdub-vs-the-competition-a-comprehensive-review-and-alternative-options-for-2024/"><u>New Virtualdub Vs. The Competition A Comprehensive Review and Alternative Options for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-disabled-wi-fi-functionality-a-comprehensive-guide/"><u>Resolving Issues with Disabled Wi-Fi Functionality: A Comprehensive Guide</u></a></li>
<li><a href="https://driver-download.techidaily.com/step-by-step-guide-to-installing-nvidia-1080-drivers-on-your-windows-10-pc/"><u>Step-by-Step Guide to Installing NVIDIA 1080 Drivers on Your Windows 10 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/technical-guide-to-optimal-playability-why-your-pc-must-have-a-d3d11-graphics-card-compatibility-to-run-the-engine-flawlessly/"><u>Technical Guide to Optimal Playability: Why Your PC Must Have a D3D11 Graphics Card Compatibility to Run the Engine Flawlessly</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-windows-10-laptops-that-wont-charge-despite-being-plugged-in/"><u>The Ultimate Fix for Windows 10 Laptops That Won't Charge Despite Being Plugged In</u></a></li>
<li><a href="https://common-error.techidaily.com/wheel-alignment-keep-your-wheels-properly-aligned-to-reduce-undue-stress-on-suspension-components-misalignment-can-cause-premature-wear-and-potentially-dama141/"><u>Wheel Alignment: Keep Your Wheels Properly Aligned to Reduce Undue Stress on Suspension Components. Misalignment Can Cause Premature Wear and Potentially Damage Other Parts of the Vehicle if Not Addressed Promptly.</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211145723-windows-11-mic-not-working-heres-what-you-need-to-do-next/"><u>Windows 11 Mic Not Working? Here's What You Need to Do Next!</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-at-windows-11-essential-tweaks-to-elevate-your-gaming-capabilities/"><u>Winning at Windows 11: Essential Tweaks to Elevate Your Gaming Capabilities</u></a></li>
</ul></div>

