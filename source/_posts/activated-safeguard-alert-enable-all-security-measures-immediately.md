---
title: "Activated Safeguard Alert: Enable All Security Measures Immediately!"
date: 2024-10-04T23:41:04.309Z
updated: 2024-10-07T05:49:42.923Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Activated Safeguard Alert: Enable All Security Measures Immediately!"
excerpt: "This Article Describes Activated Safeguard Alert: Enable All Security Measures Immediately!"
thumbnail: https://thmb.techidaily.com/503f764ce718cdd5118d7c5be0e25d96b4338086cc102ad3bcea32f94e910963.jpg
---

## Local Security Defenses Restored – Ensure Safe Operations Today

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

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144278/7443" target="_top" id="2144278">
  <img src="//a.impactradius-go.com/display-ad/7443-2144278" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144278/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

4. If there are_no_ available updates, you’ll see**You’re up to date** like this.![](https://images.drivereasy.com/wp-content/uploads/2023/09/image-21.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068426/7443" target="_top" id="2068426">
  <img src="//a.impactradius-go.com/display-ad/7443-2068426" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068426/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

Then see if the Local Security Authority Protection is still off.

 If so, please download the installation file for KB5007651 from[here](https://www.catalog.update.microsoft.com/Search.aspx?q=KB5007651) , then double-click the installation file to get it installed.

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-25.png)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1975841/19272" target="_top" id="1975841">
  <img src="//a.impactradius-go.com/display-ad/19272-1975841" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1975841/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<a href="https://aligracehair.sjv.io/c/5597632/2115937/19272" target="_top" id="2115937">
  <img src="//a.impactradius-go.com/display-ad/19272-2115937" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115937/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

## 3\. Configure Group Policy Editor

 You can also try to modify your Group Policy Editor for the Local Security Authority protection to be turned on again. To do so:

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key at the same time. Type**gpedit.msc** and hit**Enter** . (If you see “ _Windows cannot find ‘gpedit.msc’. Make sure you typed the name correctly, and then try again._ “, please refer to this post first:[ **\[Fixed\] gpedit.msc Not Found on Windows Home** ](https://tools.techidaily.com/drivereasy/download/)  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-30.png)
3. Go to **Computer Configuration\\Administrative Templates\\System\\Local Security Authority** . Double-click**Configure LSASS to run as a protected process** on the right side.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1959778/19272" target="_top" id="1959778">
  <img src="//a.impactradius-go.com/display-ad/19272-1959778" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1959778/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-32.png)
4. Click**Enable** , then select**Enabled with UEFI Lock** from the drop-down menu. Then click**Apply** and**OK** to save and exit.  

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

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1880927/19272" target="_top" id="1880927">
  <img src="//a.impactradius-go.com/display-ad/19272-1880927" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1880927/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

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
<li><a href="https://fox-boxes.techidaily.com/new-fasttrackpodcastlive-your-straightforward-guide-to-livestreaming-success/"><u>[New] FastTrackPodcastLive Your Straightforward Guide to Livestreaming Success</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-top-3-beyond-youtube-innovative-videostreaming-communities/"><u>[New] In 2024, Top 3 Beyond Youtube Innovative Videostreaming Communities</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/updated-2024-approved-tiny-titans-top-games-anthology/"><u>[Updated] 2024 Approved Tiny Titans' Top Games Anthology</u></a></li>
<li><a href="https://youtube-data.techidaily.com/ed-in-2024-find-your-perfect-match-top-8-mirrorless-cameras-for-live-streams/"><u>[Updated] In 2024, Find Your Perfect Match Top 8 Mirrorless Cameras For Live Streams</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-screenflow-simplified-streamlining-your-video-projects-on-a-mac-for-2024/"><u>[Updated] ScreenFlow Simplified Streamlining Your Video Projects on a Mac for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-immersive-escapes-androidioss-favorite-ar-games/"><u>2024 Approved Immersive Escapes Android/iOS's Favorite AR Games</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-the-ultimate-screen-experience-with-hp-envy-27-display/"><u>2024 Approved The Ultimate Screen Experience with HP Envy 27 Display</u></a></li>
<li><a href="https://hardware-help.techidaily.com/download-and-upgrade-the-corsair-k55-controller-software/"><u>Download and Upgrade the Corsair K55 Controller Software</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-vcruntime140dll-file-missing-issue-a-comprehensive-guide/"><u>Fixing the VCRUNTIME140.dll File Missing Issue: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/immediate-solution-for-non-functioning-keys-on-your-hp-laptop/"><u>Immediate Solution for Non-Functioning Keys on Your HP Laptop</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-reach-and-recognition-viewership-metrics-for-insta-photos/"><u>In 2024, Reach and Recognition Viewership Metrics for Insta Photos</u></a></li>
<li><a href="https://common-error.techidaily.com/lung-adenocarcinoma-is-the-most-common-type-of-lung-cancer-in-non-smokers/"><u>Lung Adenocarcinoma Is the Most Common Type of Lung Cancer in Non-Smokers.</u></a></li>
<li><a href="https://win-amazing.techidaily.com/official-driver-downloads-for-hp-officejet-pro-8715-on-windows-10811/"><u>Official Driver Downloads for HP OfficeJet Pro 8715 on Windows 10/8/11</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-infinite-loading-loop-in-valorant-effective-solutions-inside/"><u>Overcome Infinite Loading Loop in Valorant: Effective Solutions Inside.</u></a></li>
<li><a href="https://common-error.techidaily.com/steam-users-guide-correcting-problems-when-setting-upupgrading-video-games/"><u>Steam User's Guide: Correcting Problems When Setting Up/Upgrading Video Games</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-fix-for-windows-10s-critical-0x800705b4-update-failure-and-how-to-prevent-it/"><u>Step-by-Step Fix for Windows 10'S Critical 0X800705B4 Update Failure and How to Prevent It</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-activating-bluetooth-on-windows-11-and-10-no-more-problems/"><u>Step-by-Step Guide: Activating Bluetooth on Windows 11 and 10 - No More Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-correcting-windows-updates-setup-issues/"><u>Step-by-Step Solutions for Correcting Windows Updates Setup Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-a-surface-device-that-is-plugged-in-but-not-charging/"><u>Troubleshooting Steps for a Surface Device That Is Plugged In But Not Charging</u></a></li>
</ul></div>

