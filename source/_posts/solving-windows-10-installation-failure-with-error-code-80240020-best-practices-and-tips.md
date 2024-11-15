---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2024-11-11T18:17:10.094Z
updated: 2024-11-15T16:59:15.907Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
excerpt: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
thumbnail: https://thmb.techidaily.com/c616a530c3b86047af7fee8d712f3caf3cb46a3e47132cccfb907573c9519566.jpg
---

## Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

![](https://images.drivereasy.com/wp-content/uploads/2016/10/img_58140207aba43-600x394.jpg)

 Your**Windows Update** panel should come out in a couple of seconds. If it won’t open automatically, you can open this panel from Control Panel manually. Then, you should be able to download your Windows 10 from scratch.

The steps above also work if you are having a**80080080** or **8024600A**  error code. Usually the error is common with Windows 8.1 users, but for those who are using Windows 7, this solution applies as well. If the problem still persists, please be patient, Windows update takes time to download the upgrades in the background. If you still could not get this problem fixed, your Windows update tool might be corrupted so the security settings and background process is now malfunctioned. In this case, it is suggested that you burn the DVD or CD or USB flash drive with Windows 10 ISO files in to do the clean install from scratch. If you want to know how to do it, please refer to[this post here](https://tools.techidaily.com/drivereasy/download/) for more information.

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
<li><a href="https://desktop-recording.techidaily.com/new-eyecapture-master-series-version-x/"><u>[New] EyeCapture Master Series - Version X</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-solutions-for-balancing-iphone-hdr-footage-with-advanced-premiere-pro-tools/"><u>[New] Solutions for Balancing iPhone HDR Footage with Advanced Premiere Pro Tools</u></a></li>
<li><a href="https://fox-glue.techidaily.com/updated-in-2024-integrate-sound-and-filter-magic-into-your-windows-10-photos-app/"><u>[Updated] In 2024, Integrate Sound & Filter Magic Into Your Windows 10 Photos App</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-quick-fix-for-iphone-video-length-and-scope-reduction/"><u>[Updated] Quick-Fix for iPhone Video Length & Scope Reduction</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-unboxing-the-power-of-yis-high-definition-cam/"><u>2024 Approved Unboxing the Power of YI's High Definition Cam</u></a></li>
<li><a href="https://fake-location.techidaily.com/best-10-mock-location-apps-worth-trying-on-lenovo-thinkphone-drfone-by-drfone-virtual-android/"><u>Best 10 Mock Location Apps Worth Trying On Lenovo ThinkPhone | Dr.fone</u></a></li>
<li><a href="https://extra-information.techidaily.com/elevate-media-projects-engaging-with-windows-11-movie-maker/"><u>Elevate Media Projects Engaging with Windows 11 Movie Maker</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-rapid-display-changes-in-windows-11-step-by-step-guide/"><u>Fixing Rapid Display Changes in Windows 11: Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-11-power-issues-why-your-plugged-in-laptop-isnt-charging-and-how-to-solve-it/"><u>Resolving Windows 11 Power Issues: Why Your Plugged-In Laptop Isn't Charging & How to Solve It</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tutorial-restoring-corrupt-system-files-in-windows-10-and-11/"><u>Step-by-Step Tutorial: Restoring Corrupt System Files in Windows 10 and 11</u></a></li>
<li><a href="https://common-error.techidaily.com/tackling-rapid-eyes-advanced-tricks-to-stop-flickering-cursor/"><u>Tackling Rapid Eyes: Advanced Tricks to Stop Flickering Cursor</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/tips-and-tricks-to-tell-if-your-iphone-13-mini-is-unlocked-by-drfone-ios/"><u>Tips And Tricks To Tell if Your iPhone 13 mini Is Unlocked</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-intermittent-issues-with-your-wireless-mouse-in-windows-1110/"><u>Troubleshooting Guide: Fixing Intermittent Issues with Your Wireless Mouse in Windows 11/10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-unresponsive-buttons-in-windows-operating-systems-win-10-11/"><u>Troubleshooting Unresponsive Buttons in Windows Operating Systems (Win 10, 11)</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2144279/7443" target="_top" id="2144279">
  <img src="//a.impactradius-go.com/display-ad/7443-2144279" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2144279/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

