---
title: "Expert Tips: Resolving Stuck Windows 11 Update Loop"
date: 2024-10-23T17:05:17.115Z
updated: 2024-10-30T17:41:13.124Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Expert Tips: Resolving Stuck Windows 11 Update Loop"
excerpt: "This Article Describes Expert Tips: Resolving Stuck Windows 11 Update Loop"
thumbnail: https://thmb.techidaily.com/39eb12846caac832ee1b1d85070e2dd4cb557f02287ca2d451303bdd76b5dd20.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://visual-screen-recording.techidaily.com/new-2024-approved-securing-your-discord-sessions-for-future-viewing/"><u>[New] 2024 Approved Securing Your Discord Sessions for Future Viewing</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/updated-in-2024-24-hour-film-size-gb-measurement-guide/"><u>[Updated] In 2024, 24-Hour Film Size GB Measurement Guide</u></a></li>
<li><a href="https://fox-blue.techidaily.com/updated-in-2024-visual-virtuosity-unleashed-professional-tips-to-elevate-your-photos/"><u>[Updated] In 2024, Visual Virtuosity Unleashed Professional Tips to Elevate Your Photos</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-top-ios-pro-and-plus-free-film-apps-unveiled/"><u>2024 Approved Top iOS Pro & Plus-Free Film Apps - Unveiled</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/download-the-ideal-vlc-app-for-seamless-dvd-experience-no-cost-compatible-with-pc-and-mac-osx/"><u>Download the Ideal VLC App for Seamless DVD Experience – No Cost, Compatible with PC and Mac OSX</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unexpected-when-wd-my-passport-ultra-goes-undetected-by-windows-systems/"><u>Fixing 'Unexpected': When WD My Passport Ultra Goes Undetected by Windows Systems</u></a></li>
<li><a href="https://unlock-android.techidaily.com/forgot-pattern-lock-heres-how-you-can-unlock-xiaomi-redmi-note-13-5g-pattern-lock-screen-by-drfone-android/"><u>Forgot Pattern Lock? Heres How You Can Unlock Xiaomi Redmi Note 13 5G Pattern Lock Screen</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/in-2024-the-essential-guide-to-creating-stunning-boomerangs/"><u>In 2024, The Essential Guide to Creating Stunning Boomerangs</u></a></li>
<li><a href="https://common-error.techidaily.com/laptop-care-101-how-to-restore-functionality-to-an-unresponsive-touchpad/"><u>Laptop Care 101: How to Restore Functionality to an Unresponsive Touchpad</u></a></li>
<li><a href="https://common-error.techidaily.com/missing-component-detected-msvcr71-fixed/"><u>Missing Component Detected: MSVCR71 Fixed</u></a></li>
<li><a href="https://common-error.techidaily.com/1723210914953-resolve-error-code-0x887a0006-with-these-easy-fixes/"><u>Resolve Error Code 0X887A0006 with These Easy Fixes!</u></a></li>
<li><a href="https://network-issues.techidaily.com/stabilizing-screens-on-windows-7-platform/"><u>Stabilizing Screens on Windows 7 Platform</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-nonfunctional-usb-ports-on-your-pc-running-windows-11/"><u>Troubleshooting Nonfunctional USB Ports on Your PC Running Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-unidentified-usb-devices-and-port-resets-on-windows-10/"><u>Troubleshooting Tips for Fixing Unidentified USB Devices and Port Resets on Windows 10</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/updated-weve-handpicked-some-of-the-best-online-reverse-video-makers-in-this-article-to-help-you-make-creative-and-inspiring-reverse-videos-online-for-2024./"><u>Updated Weve Handpicked some of the Best Online Reverse Video Makers in This Article to Help You Make Creative and Inspiring Reverse Videos Online for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207699073-windows-11-youtube-sound-glitches-learn-how-to-tackle-audio-renderer-troubles-effectively/"><u>Windows 11 YouTube Sound Glitches? Learn How to Tackle Audio Renderer Troubles Effectively!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135396/19272" target="_top" id="2135396">
  <img src="//a.impactradius-go.com/display-ad/19272-2135396" border="0" alt="https://techidaily.com" width="160" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135396/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

