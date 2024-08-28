---
title: LSA Safety Measures Fully Operational Again - Secure Your System Now
date: 2024-08-27T13:35:09.357Z
updated: 2024-08-28T13:35:09.357Z
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

<!-- affiliate ads begin -->
<a href="https://newchic.sjv.io/c/5597632/1659704/14420" target="_top" id="1659704"><img src="//a.impactradius-go.com/display-ad/14420-1659704" border="0" alt="" width="728" height="90"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1659704/14420" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

<!-- affiliate ads begin -->
<a href="https://printrendy.pxf.io/c/5597632/1453720/17020" target="_top" id="1453720"><img src="//a.impactradius-go.com/display-ad/17020-1453720" border="0" alt="" width="300" height="250"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1453720/17020" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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

<!-- affiliate ads begin -->
<a href="https://uperfect.sjv.io/c/5597632/1246754/15155" target="_top" id="1246754"><img src="//a.impactradius-go.com/display-ad/15155-1246754" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1246754/15155" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-18.png)
2. Click**Check for updates** , and Windows will scan for any available updates.  
![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-19.png)
<!-- affiliate ads begin -->
<a href="https://purchase.swifdoo.com/order/checkout.php?PRODS=40002580&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/8b932759a5a04ddb34bf79e3f9072e4b/products/3_Product%20box%20white-1024x1024.png" border="0">SwifDoo PDF 2-Year Plan</a>
<!-- affiliate ads end -->
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
<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2075475/7443" target="_top" id="2075475"><img src="//a.impactradius-go.com/display-ad/7443-2075475" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2075475/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
<!-- affiliate ads begin -->
<a href="https://shop.mondly.com/affiliate.php?ACCOUNT=ATISTUDI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.mondly.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BEducational%2B970x90%2B"><img src="https://secure.avangate.com/images/merchant/69c418c33ec2e1a4267fa9bb77fa1428/educational-970x90.gif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<a href="https://martinic.evyy.net/c/5597632/1422856/4482" target="_top" id="1422856"><img src="//a.impactradius-go.com/display-ad/4482-1422856" border="0" alt="" width="580" height="309"/></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4721564&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/c14a8df1e1b4d5297e9cb30cb34d5a00/products/copy_power-tools-48.png" border="0">Power Tools add-on for Google Sheets, 12-month subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  
<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4729642&QTY=1&AFFILIATE=108875&CART=1">Advanced Find and Replace for Google Sheets, Lifetime subscription</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-34.png)
5. Restart your computer for the change to take effect.

 Then see if your Local Security Authority protection can be toggled back on.

---

<!-- affiliate ads begin -->
<a href="https://shop.copernic.com/order/checkout.php?PRODS=41033101&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.2checkout.com/images/merchant/8d30aa96e72440759f74bd2306c1fa3d/Copernic-2023-Affiliate-728x90-Elite.png" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://vp-tips.techidaily.com/new-captivating-viewers-with-visuals-picture-upload-tips-for-2024/"><u>[New] Captivating Viewers with Visuals  Picture Upload Tips for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-alt-tab-not-working/"><u>[Solved] Alt Tab Not Working</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-reset-a-keyboard/"><u>[Solved] How to Reset a Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-the-request-failed-due-to-a-fatal-device-hardware-error/"><u>[SOLVED] The Request Failed Due to a Fatal Device Hardware Error</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-effortless-online-guide-youtube-video-to-gif-magic-no-download/"><u>[Updated] 2024 Approved  Effortless Online Guide  YouTube Video to GIF Magic (No Download)</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-facebooks-premier-video-extraction-tools-for-iphone-and-ipad/"><u>[Updated] 2024 Approved  Facebook's Premier Video Extraction Tools for iPhone & iPad</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-2024-approved-top-5-underwater-gopro-accessories/"><u>[Updated] 2024 Approved  Top 5 Underwater Gopro Accessories</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ed-2024-approved-youtube-triumphs-how-to-turn-your-cell-phone-into-an-editing-machine/"><u>[Updated] 2024 Approved  YouTube Triumphs  How to Turn Your Cell Phone Into an Editing Machine</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-in-2024-uncovering-stardews-depths-with-ginger-island-adventures/"><u>[Updated] In 2024, Uncovering Stardew's Depths with Ginger Island Adventures</u></a></li>
<li><a href="https://common-error.techidaily.com/a-guide-to-restoring-functionality-for-non-working-function-fn-keys-on-dell-laptops/"><u>A Guide to Restoring Functionality for Non-Working Function (Fn) Keys on Dell Laptops</u></a></li>
<li><a href="https://common-error.techidaily.com/audio-alchemy-transforming-laptops-to-detect-headsets/"><u>Audio Alchemy: Transforming Laptops to Detect Headsets</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/become-a-master-of-virtual-persona-design-metaverse-edition-for-2024/"><u>Become a Master of Virtual Persona Design - Metaverse Edition for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/corrective-steps-for-accidental-character-inputs-in-typing/"><u>Corrective Steps for Accidental Character Inputs in Typing</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-intermittent-screen-lock-ups-in-computers/"><u>Diagnosing and Repairing Intermittent Screen Lock-Ups in Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-microsofts-print-to-pdf-not-working-on-windows-11/"><u>Effective Solutions for Microsoft’s Print to PDF Not Working on Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-resolve-windows-file-corruption-issues-ws-10-and-11-edition/"><u>Effective Strategies to Resolve Windows File Corruption Issues - WS 10 & 11 Edition</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-updating-made-simple-overcoming-windows-0x80070652-mishap-with-ease/"><u>Error-Free Updating Made Simple: Overcoming Windows 0X80070652 Mishap with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-overcoming-common-problems-with-your-lenovo-keyboard-not-working/"><u>Expert Advice: Overcoming Common Problems with Your Lenovo Keyboard Not Working</u></a></li>
<li><a href="https://fake-location.techidaily.com/fake-the-location-to-get-around-the-mlb-blackouts-on-realme-10t-5g-drfone-by-drfone-virtual-android/"><u>Fake the Location to Get Around the MLB Blackouts on Realme 10T 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-ctrlplusaltplusdel-issues-ultimate-guide-to-restoring-functionality/"><u>Fixing Ctrl+Alt+Del Issues: Ultimate Guide to Restoring Functionality</u></a></li>
<li><a href="https://hardware-help.techidaily.com/get-the-latest-nvidia-geforce-940mx-graphics-card-driver/"><u>Get the Latest Nvidia GeForce 940MX Graphics Card Driver</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-alternatives-after-disabling-adobe-shockwave-in-chrome/"><u>How To Enable Alternatives After Disabling Adobe Shockwave in Chrome</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-msmpengexe-high-cpu-usage-on-your-windows-10-pc-solution-guide/"><u>How to Fix MsMpEng.exe High CPU Usage on Your Windows 10 PC – Solution Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-release-a-stuck-update-on-legacy-oss-like-windows-seven-latest-techniques-and-solutions-for-better-user-experience-in-the-year-of-our-lord-two-thousa24/"><u>How To Release A Stuck Update On Legacy OSs Like WIndows Seven - Latest Techniques & Solutions For Better User Experience In The Year Of Our Lord Two Thousand And Twenty Four Edition! (Helpful Tips and Troubleshooting Steps.)</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-video-not-detected-problem-on-your-screen-a-detailed-walkthrough/"><u>How to Resolve the 'Video Not Detected' Problem on Your Screen - A Detailed Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/improve-your-computers-efficiency-through-effective-clutter-clearance/"><u>Improve Your Computer's Efficiency Through Effective Clutter Clearance</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-best-3-oneplus-nord-n30-5g-emulator-for-mac-to-run-your-wanted-android-apps-drfone-by-drfone-android/"><u>In 2024, Best 3 OnePlus Nord N30 5G Emulator for Mac to Run Your Wanted Android Apps | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-securely-snap-fb-video-conversations-4-methods/"><u>In 2024, Securely Snap FB Video Conversations [4 Methods]</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/locked-out-of-apple-iphone-se-5-ways-to-get-into-a-locked-apple-iphone-se-by-drfone-ios/"><u>Locked Out of Apple iPhone SE? 5 Ways to get into a Locked Apple iPhone SE</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-fix-handling-and-repairing-hamachi-errors-effectively/"><u>Master the Fix: Handling and Repairing Hamachi Errors Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-install-a-users-guide-to-correcting-error-0x800f081f-on-net-framework/"><u>Mastering the Install: A User's Guide to Correcting Error 0X800F081F on .NET Framework</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/optimal-orientation-top-tripods-for-iphones-and-androids-for-2024/"><u>Optimal Orientation  Top Tripods for iPhones & Androids for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-rdr2-out-of-memory-error-with-this-simple-step-expand-your-page-file/"><u>Overcome 'RDR2 Out Of Memory' Error with This Simple Step – Expand Your Page File</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11-usb-port-issues-a-step-by-step-guide/"><u>Resolving Windows 11 USB Port Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/sequential-binge-viewing-plan-for-the-complete-indiana-jones-series/"><u>Sequential Binge-Viewing Plan for the Complete Indiana Jones Series</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-problem-when-your-sims-4-game-wont-start/"><u>Solving the Problem: When Your Sims 4 Game Won’t Start</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/trouble-with-iphone-7-plus-swipe-up-try-these-11-solutions-by-drfone-ios/"><u>Trouble with iPhone 7 Plus Swipe-Up? Try These 11 Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-bluetooth-issues-on-windows-7-computers/"><u>Troubleshooting and Fixing Bluetooth Issues on Windows 7 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-high-disk-consumption-of-microsoft-compatibility-telemetry-on-windows-10/"><u>Troubleshooting and Fixing High Disk Consumption of Microsoft Compatibility Telemetry on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-minecraft-launch-problems-on-a-windows-pc/"><u>Troubleshooting Guide: Resolving Minecraft Launch Problems on a Windows PC</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-overcoming-steam-bootstrapper-errors-now-resolved/"><u>Troubleshooting Tips for Overcoming Steam Bootstrapper Errors – Now Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-what-to-do-when-you-encounter-a-missing-module-issue/"><u>Troubleshooting: What to Do When You Encounter a Missing Module Issue</u></a></li>
<li><a href="https://program-issues.techidaily.com/unlocking-better-gameplay-a-2023-playbook-to-fix-fallout-76s-fps-lag-problem/"><u>Unlocking Better Gameplay: A 2023 Playbook to Fix Fallout 76'S FPS Lag Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/why-your-smartphone-isnt-charging-even-though-its-plugged-in-fixes-and-tips/"><u>Why Your Smartphone Isn’t Charging Even Though It's Plugged In – Fixes & Tips</u></a></li>
</ul></div>
