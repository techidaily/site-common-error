---
title: Steps to Request Modification Authorization From TrustedInstaller
date: 2024-08-27T13:46:40.331Z
updated: 2024-08-28T13:46:40.331Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Steps to Request Modification Authorization From TrustedInstaller
excerpt: This Article Describes Steps to Request Modification Authorization From TrustedInstaller
thumbnail: https://thmb.techidaily.com/a6af875fb6cb15aafd717b61af0a7acb112fadf86579f433a8538feaaaa997ff.jpg
---

## Urgent Fix Required: Enable Local Authorization Defenses Now

![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-24.png)

Local Security Authority Protection is off

 No need to worry if your Local Security Authority Protection is toggled off: in most cases, it was a UI bug with a certain Windows update patch, meaning that it’s not off, just appears to be off, and you can install another update patch to get it fixed. In other rare cases, you can change your computer settings to get it enabled again. Read on and see how you can fix the Local Security Authority Protection being off problem.

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

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=11224199&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/e09fdffe648a30658a9657bbed7b2388/products/copy_boxshot_lyricvideo.png" border="0">Lyric Video Creator Professional Version</a>
<!-- affiliate ads end -->
## 2\. Modify Registry Editor

 If you’re still seeing the Local Security Authority protection off message even when you’ve turned it ON, please do the following to modify your Registry Editor:

 Incorrectly modifying Registry Editor files could cause severe computer problems, so please make sure that you always create a backup or a restore point for your computer first before you change anything in the Registry Editor.

1. Firstly, create a system restore point as instructed here:[How to enable and create restore points in Windows 10](https://tools.techidaily.com/drivereasy/download/) (the screenshots here are from Windows 10, but the instructions work on Windows 11 as well).
2. On your keyboard, press the**Windows** key and the**R** key together. Type**regedit** and hit**Enter** .  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-27.png)
3. Go to the following location:`**Computer\HKEY_LOCAL_MACHINE\SYSTEM\CurrentControlSet\Control\Lsa**`  
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-26.png)
4. On the right side, if you can see **RunAsPPL** , double-click it and change the**Value data** to**2** . Repeat the same with**RunAsPPLBoot** . If you don’t see either of these entries, move on to the next step.  
<!-- affiliate ads begin -->
<a href="https://turtlebeacheu.sjv.io/c/5597632/1996818/23722" target="_top" id="1996818"><img src="//a.impactradius-go.com/display-ad/23722-1996818" border="0" alt="" width="600" height="600"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1996818/23722" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-29.png)
5. If you don’t see**RunAsPPL** or**RunAsPPLBoot** on the right side, right-click the empty area and select**New > DWORD (32-bit) Value** . Name the new entry**RunAsPPL** , then double-click it to change its**Value data** to**2** . Repeat the same to create a new entry named**RunAsPPLBoot** and change its value data to 2.  
<!-- affiliate ads begin -->
<span id="1993650">
					<video width="720" height="300" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993650">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993650.jpeg" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:720px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993650%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993650/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2023/11/image-28.png) [](https://cdn.windowsreport.com/wp-content/uploads/2023/03/regedit%5F1OHPX7onS7.png)
6. Restart your computer for the changes to take effect.

 Then see if the Local Security Authority protection can be turned on now. If the problem still remains, please move on.

---

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2087264/19272" target="_top" id="2087264"><img src="//a.impactradius-go.com/display-ad/19272-2087264" border="0" alt="" width="336" height="280"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2087264/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
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
<a href="https://coinrule.sjv.io/c/5597632/1958374/18409" target="_top" id="1958374"><img src="//a.impactradius-go.com/display-ad/18409-1958374" border="0" alt="" width="300" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958374/18409" style="position:absolute;visibility:hidden;" border="0" />
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
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=2069351&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-24_%282%29.jpg" border="0"></a>
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
<li><a href="https://youtube-data.techidaily.com/024-approved-disruptive-beats-curated-list-of-music-mutators/"><u>[New] 2024 Approved  Disruptive Beats  Curated List of Music Mutators</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/024-approved-navigating-hashtags-for-a-6-figure-view-spike-on-youtube/"><u>[New] 2024 Approved  Navigating Hashtags for a 6-Figure View Spike on YouTube</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-fb-soundbank-freeness-central/"><u>[New] FB Soundbank  Freeness Central</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-in-2024-unveiling-the-secrets-to-dynamic-video-cover-design-in-facebook-space/"><u>[New] In 2024, Unveiling the Secrets to Dynamic Video Cover Design in Facebook Space</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-achieving-livestream-control-fifteen-innovative-techniques-for-2024/"><u>[Updated] Achieving Livestream Control  Fifteen Innovative Techniques for 2024</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-alternative-windows-filmmakers-for-2024/"><u>[Updated] Alternative Windows Filmmakers for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-demystifying-social-engagement-instagram-stories-surveys-for-2024/"><u>[Updated] Demystifying Social Engagement  Instagram Stories Surveys for 2024</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-in-2024-10-best-agricultural-games-for-group-fun/"><u>[Updated] In 2024, 10 Best Agricultural Games for Group Fun</u></a></li>
<li><a href="https://fox-direct.techidaily.com/updated-in-2024-aurora-vs-standard-screens-a-detailed-comparison/"><u>[Updated] In 2024, Aurora vs Standard Screens  A Detailed Comparison</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/2024-approved-harvest-heartbeats-top-farm-games-for-friendly-fun/"><u>2024 Approved  Harvest Heartbeats  Top Farm Games for Friendly Fun</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/2024-approved-uncharted-territory-in-facebooks-meme-landscape/"><u>2024 Approved  Uncharted Territory in Facebook's Meme Landscape</u></a></li>
<li><a href="https://common-error.techidaily.com/a-guide-to-fixing-the-unavailable-module-error-message/"><u>A Guide to Fixing the Unavailable Module Error Message</u></a></li>
<li><a href="https://win-blog.techidaily.com/breakthrough-guide-to-fixing-microsoft-flight-simulator-2020-endless-update-loop/"><u>Breakthrough Guide to Fixing Microsoft Flight Simulator 2020 Endless Update Loop</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-windows-11-upgrade-freeze-solutions-unveiled/"><u>Bypassing Windows 11 Upgrade Freeze - Solutions Unveiled</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/comprehensive-tutorial-altering-pixel-size-of-images-in-windowsmac-os/"><u>Comprehensive Tutorial: Altering Pixel Size of Images in Windows/Mac OS</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/cutting-edge-techniques-for-clear-zoom-captures-for-2024/"><u>Cutting Edge Techniques for Clear Zoom Captures for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/debunking-the-myth-strategies-to-combat-the-notorious-google-chrome-error-ploy/"><u>Debunking the Myth: Strategies to Combat the Notorious Google Chrome Error Ploy</u></a></li>
<li><a href="https://hardware-help.techidaily.com/dts-audio-not-found-troubleshooting-steps-for-missing-sound-device/"><u>DTS Audio Not Found: Troubleshooting Steps for Missing Sound Device</u></a></li>
<li><a href="https://android-location.techidaily.com/easy-ways-to-manage-your-oppo-reno-8t-5g-location-settings-drfone-by-drfone-virtual/"><u>Easy Ways to Manage Your Oppo Reno 8T 5G Location Settings | Dr.fone</u></a></li>
<li><a href="https://mondly-stories.techidaily.com/educators-summit-in-london-uk-bett-2022/"><u>Educators' Summit in London, UK: BETT 2022</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-methods-to-overcome-the-0-stalled-windows-updates/"><u>Effortless Methods to Overcome the 0%% Stalled Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/eradicate-e-sports-embarrassment-fast-solutions/"><u>Eradicate E-Sports Embarrassment - Fast Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-reducing-your-ps4-fan-sounds-without-sacrificing-performance/"><u>Expert Guide: Reducing Your PS4 Fan Sounds Without Sacrificing Performance</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-common-issues-with-unresponsive-wacom-graphics-tables-a-comprehensive-guide/"><u>Fix Common Issues with Unresponsive Wacom Graphics Tables - A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-module-not-found-problem-a-step-by-nstep-approach/"><u>Fixing the 'Module Not Found' Problem: A Step-by-nStep Approach</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-error-troubleshooting-a-failed-driver-configuration-in-user-settings/"><u>Fixing the Error: Troubleshooting a Failed Driver Configuration in User Settings</u></a></li>
<li><a href="https://common-error.techidaily.com/getting-your-evening-screen-tint-back-repairing-windows-1011s-night-light-issues/"><u>Getting Your Evening Screen Tint Back: Repairing Windows 10/11'S Night Light Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-address-a-deficiency-in-xinput13dll/"><u>How to Address a Deficiency in XINPUT1_3.dll</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-msvcp140dll-is-missing-the-right-way/"><u>How to Fix 'MSVCP140.dll Is Missing' The Right Way</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-rpc-server-is-unavailable-error-in-windows/"><u>How to Fix “The RPC Server Is Unavailable” Error in Windows</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-rescue-lost-videos-from-infinix-gt-10-pro-by-fonelab-android-recover-video/"><u>How to Rescue Lost Videos from Infinix GT 10 Pro</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-ps4-network-errors-quickly-a-complete-walkthrough/"><u>How to Resolve PS4 Network Errors Quickly - A Complete Walkthrough</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-5-best-route-generator-apps-you-should-try-on-apple-iphone-13-pro-drfone-by-drfone-virtual-ios/"><u>In 2024, 5 Best Route Generator Apps You Should Try On Apple iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-fake-snapchat-location-on-infinix-hot-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Fake Snapchat Location on Infinix Hot 40 | Dr.fone</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-how-to-watch-hulu-outside-us-on-motorola-edge-40-drfone-by-drfone-virtual-android/"><u>In 2024, How to Watch Hulu Outside US On Motorola Edge 40 | Dr.fone</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-best-android-unlock-software-for-oneplus-open-device-top-5-picks-to-remove-android-locks-by-drfone-android/"><u>In 2024, The Best Android Unlock Software For OnePlus Open Device Top 5 Picks to Remove Android Locks</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-what-is-a-sim-network-unlock-pin-get-your-samsung-galaxy-a54-5g-phone-network-ready-by-drfone-android/"><u>In 2024, What Is a SIM Network Unlock PIN? Get Your Samsung Galaxy A54 5G Phone Network-Ready</u></a></li>
<li><a href="https://common-error.techidaily.com/keep-data-intact-how-windows-11-preserves-file-placement-after-reboot/"><u>Keep Data Intact: How Windows 11 Preserves File Placement After Reboot</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-file-explorer-on-windows-10-simple-troubleshooting-steps/"><u>Mastering File Explorer on Windows 10 - Simple Troubleshooting Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/nvidia-share-unresponsive-here-are-proven-solutions/"><u>NVIDIA Share Unresponsive? Here Are Proven Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-previous-problems-a-working-battleye-anti-cheat-installer/"><u>Overcoming Previous Problems: A Working BattlEye Anti-Cheat Installer</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-ps4-nat-failures-expert-guide-to-a-smooth-online-gaming-experience/"><u>Overcoming PS4 NAT Failures: Expert Guide to a Smooth Online Gaming Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-troubleshooting-tips-when-facing-multiple-screen-problems-on-your-computer/"><u>Quick Troubleshooting Tips When Facing Multiple Screen Problems on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-version-1607-update-failure-during-setup/"><u>Resolving Windows 10 Version 1_607 Update Failure During Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/restoring-functionality-to-stuck-or-broken-fn-key-buttons-on-your-keyboard/"><u>Restoring Functionality to Stuck or Broken Fn Key Buttons on Your Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-fixing-the-logitech-scroll-wheel-malfunction/"><u>Step-by-Step Solution for Fixing the Logitech Scroll Wheel Malfunction</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-tackling-svchostexes-heavy-cpu-load-on-windows-11-systems/"><u>Step-by-Step Solutions for Tackling svchost.exe's Heavy CPU Load on Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/stop-your-pc-from-falling-asleep-simple-fixes/"><u>Stop Your PC From Falling Asleep: Simple Fixes</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/the-complete-guide-to-assembling-youtube-music-collections-onlineapp-wise-for-2024/"><u>The Complete Guide to Assembling YouTube Music Collections Online/App-Wise for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-non-responsive-file-explorer-in-windows-10/"><u>Troubleshooting and Fixing Non-Responsive File Explorer in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-overcoming-common-problems-with-windows-update-installation/"><u>Troubleshooting Tips: Overcoming Common Problems with Windows Update Installation</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/tweet-time-machine-capturing-the-essence-of-twitters-videos/"><u>Tweet Time Machine  Capturing the Essence of Twitter's Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/windowslinux-users-beware-how-to-tackle-unwarranted-high-cpu-usage-from-shell-infrastructures/"><u>Windows/Linux Users Beware – How to Tackle Unwarranted High CPU Usage From Shell Infrastructures!</u></a></li>
</ul></div>
