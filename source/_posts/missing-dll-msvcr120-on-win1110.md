---
title: "Missing DLL: MSVCR120 on Win11/10"
date: 2024-11-08T17:51:54.916Z
updated: 2024-11-15T17:03:34.616Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Missing DLL: MSVCR120 on Win11/10"
excerpt: "This Article Describes Missing DLL: MSVCR120 on Win11/10"
thumbnail: https://thmb.techidaily.com/dc4cacbc8b493fc632f86712912ebd59bbc9ecbefdaf01df729929788c56ed4e.jpeg
---

## Tackling High CPU Drain by svchost.exe on Windows 11: Solved

![](https://images.drivereasy.com/wp-content/uploads/2016/10/svchost-exe-in-task-manager-600x402.jpg)

 If you’re seeing many svchost.exe items hogging your CPU usage, you’re not alone. Many Windows 10 users are reporting this problem. No worries, it’s possible to fix. Here are[4 fixes](#how) for you to sort it out.

### **What is svchost.exe?**

 According to Microsoft,**svchost.exe** is:

> “a generic host process name for services that run from dynamic-link libraries”.

 In simpler words, it’ s a legitimate Windows process when running certain Windows operations. But in certain cases, you may see the **svchost.exe**  process hogging the CPU or memory resources in **Task Manager**  without apparent reasons.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134235/18498" target="_top" id="2134235">
  <img src="//a.impactradius-go.com/display-ad/18498-2134235" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134235/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **How do I fix it?**

 Here are 4 solutions for you to try. You may not need to try them all; just work your way down until you find the one that works for you.

[**1: Scan your computer for viruses**](#1)

[**2: Disable certain svchost.exe services**](#2)

[**3: Empty event viewer log**](#3)

[**4: Troubleshoot Windows Updates issues**](#4)

## **1: Scan your computer for viruses**

 High CPU or memory usage of**svchost.exe** services can be caused by viruses or malicious programs. So run your antivirus program and scan for possible viruses and malicious programs.

 If you find any, uninstall them or remove the viruses completely to see if the problem is fixed.

## **2: Disable certain svchost.exe services**

 Faulty svchost.exe services can also be the cause of the abnormally high CPU usage in your PC. To fix it:

 1) Right-click the taskbar at the bottom of your PC desktop and click **Task Manager** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/task-manager.png)

2) Click **Details** . Right-click the **svchost.exe**  process using high CPU usage and click **Go to service(s)** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/go-to-services-600x417.jpg)

 3) You’ll go to a window with highlighted services that run under the**svchost.exe** process.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/highlighted-services.jpg)

 4) Right-click one of the processes and click **Stop**  to stop it.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-service-in-task-manager.jpg)

 5) Repeat the steps until you locate the faulty process.

 6) Once you find the faulty service, click the **Open Services** button and go to the **Service** window.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/open-services-600x422.jpg)

7) We’re using the **Windows Update**  service as an example. Right-click **Windows Update**  and click **Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/windows-update-properties.jpg)

8) Change the **Startup Type** to **Disable** , then click **OK** and restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/startup-type-disable.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100542/7443" target="_top" id="2100542">
  <img src="//a.impactradius-go.com/display-ad/7443-2100542" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100542/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

9) See if the problem is resolved.

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134247/18498" target="_top" id="2134247">
  <img src="//a.impactradius-go.com/display-ad/18498-2134247" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134247/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **3: Empty event viewer log**

 Large log files in Windows event viewer could cause excessively high usage of CPU or memory. To fix that, you can clear Event Viewer’s log:

 1) On your keyboard, press the **Windows** **logo key** and**R** key at the same time, then type**eventvwr** and press **Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/eventvwr.png)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2002018/7443" target="_top" id="2002018">
  <img src="//a.impactradius-go.com/display-ad/7443-2002018" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2002018/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 2) On the left side of the pane, click **Application** under **Windows Logs**  . On the right side of the pane, click **Clear Log…** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/clear-log-windows-log-application-event-viewer.jpg)

<!-- affiliate ads begin -->
<span id="1982570">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982570.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982570">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982570.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982570%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982570/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Repeat the same procedures to clear the **Security, Setup** and **System** logs.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/security-setup-and-system-log.jpg)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2137394/7443" target="_top" id="2137394">
  <img src="//a.impactradius-go.com/display-ad/7443-2137394" border="0" alt="https://techidaily.com" width="600" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2137394/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4) Restart your computer after this.

## **4: Troubleshoot Windows Updates issues**

 If something is wrong with your Windows Updates settings, svchost.exe will see an abnormal increase as well. To fix it:

 1) On your keyboard, press the **Windows logo key** and**R**  at the same time to open a**Run** command window. Type**services.msc** and press**Enter** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/services-msc.png)

 2) Right-click**Windows Update** and click **Stop** .

![](https://images.drivereasy.com/wp-content/uploads/2016/10/stop-windows-update-service.jpg)

 3) Go to**This PC > Local Disk (C:) > Windows** and delete **SoftwareDistribution** folder. Restart your computer.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/softwaredistribution.jpg)

<!-- affiliate ads begin -->
<a href="https://laganoo.pxf.io/c/5597632/1484944/16446" target="_top" id="1484944">
  <img src="//a.impactradius-go.com/display-ad/16446-1484944" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://laganoo.pxf.io/i/5597632/1484944/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## **PRO TIP**

 If, after trying the above, your PC is still hogging by**svchost.exe** programs, it’s time to update your device drivers.

 If you don’t have the time, patience or computer skills to update your drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 Driver Easy will automatically recognize your system and find the correct drivers for it. You don’t need to know exactly what system your computer is running, you don’t need to risk downloading and installing the wrong driver, and you don’t need to worry about making a mistake when installing.

 You can update your drivers automatically with either the FREE or the Pro version of Driver Easy. But with the Pro version it takes just 2 clicks (and you get full support and a 30-day money back guarantee):

 1)[**Download**](https://tools.techidaily.com/drivereasy/download/) and install Driver Easy.

 2) Run Driver Easy and click the**Scan Now** button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21f9606b83.png)

 3) Click the**Update** button next to all flagged devices to automatically download and install the correct version of their drivers (you can do this with the FREE version).

 Or click**Update All** to automatically download and install the correct version of all the drivers that are missing or out of date on your system (this requires the[**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59b21fb4e7c7a.jpg)

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
<li><a href="https://fox-info.techidaily.com/new-optimize-space-compelling-selection-of-20-top-free-cloud-storages-up-to-1tb/"><u>[New] Optimize Space Compelling Selection of 20 Top FREE Cloud Storages (Up To 1TB)</u></a></li>
<li><a href="https://discord-videos.techidaily.com/step-by-step-guidehow-to-stream-on-discord-for-2024/"><u>[Step-by-Step Guide]How to Stream on Discord for 2024</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/2024-approved-perfecting-the-closure-a-practical-guide-to-vimeos-end-credits/"><u>2024 Approved Perfecting the Closure A Practical Guide to Vimeo's End Credits</u></a></li>
<li><a href="https://common-error.techidaily.com/beat-the-update-blues-fixing-critical-bug-0x8024401c-in-windows-11-devices/"><u>Beat the Update Blues: Fixing Critical Bug 0X8024401c in Windows 11 Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-user-profile-service-failure-during-windows-authentication/"><u>Effective Solutions for User Profile Service Failure During Windows Authentication</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-repairing-stuck-keys-on-windows-laptops-and-desktops/"><u>Expert Tips for Repairing Stuck Keys on Windows Laptops and Desktops</u></a></li>
<li><a href="https://common-error.techidaily.com/exploring-sfc-and-dism-tools-for-fixing-windows-10-issues/"><u>Exploring SFC & DISM Tools for Fixing Windows 10 Issues</u></a></li>
<li><a href="https://win-blog.techidaily.com/fixing-utorrent-network-errors-tips-for-reestablishing-peer-links/"><u>Fixing uTorrent Network Errors – Tips for Reestablishing Peer Links</u></a></li>
<li><a href="https://discover-guides.techidaily.com/how-to-fix-down-status-issues-with-the-reddit-mobile-and-pc-apps-across-various-platforms-including-windows-11/"><u>How to Fix 'Down' Status Issues with the Reddit Mobile & PC Apps Across Various Platforms Including Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-handle-missing-classes-on-your-windows-11-system-solution/"><u>How to Handle Missing Classes on Your Windows 11 System [Solution]</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/how-to-use-allshare-cast-to-turn-on-screen-mirroring-on-oneplus-ace-3-drfone-by-drfone-android/"><u>How To Use Allshare Cast To Turn On Screen Mirroring On OnePlus Ace 3 | Dr.fone</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/in-2024-linux-users-guide-best-8-screenshot-apps/"><u>In 2024, Linux Users Guide Best 8 Screenshot Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-art-of-troubleshooting-immediate-csgo-stability-restored/"><u>Master the Art of Troubleshooting: Immediate CSGO Stability Restored</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-common-issues-actions-to-perform-when-a-torrent-wont-download-properly/"><u>Overcoming Common Issues: Actions to Perform When a Torrent Won't Download Properly</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-to-enhance-your-experience-with-windows-10-file-explorer/"><u>Simple Solutions to Enhance Your Experience with Windows 10 File Explorer</u></a></li>
<li><a href="https://some-guidance.techidaily.com/step-by-step-guide-converting-dvds-to-high-quality-hevch265-mp4-format-for-optimal-playback/"><u>Step-by-Step Guide: Converting DVDs to High-Quality HEVC/H.265 MP4 Format for Optimal Playback</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-samsung-galaxy-a14-4g-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Samsung Galaxy A14 4G Users</u></a></li>
<li><a href="https://extra-tips.techidaily.com/which-streaming-application-leads-the-race-wirecast-or-obs/"><u>Which Streaming Application Leads the Race, Wirecast or OBS?</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210036569-windows-11-update-brings-new-cast-features-solve-common-casting-errors-here/"><u>Windows 11 Update Brings New Cast Features - Solve Common Casting Errors Here</u></a></li>
</ul></div>

