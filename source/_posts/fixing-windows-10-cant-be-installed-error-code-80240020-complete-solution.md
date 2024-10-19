---
title: Fixing Windows 10 Can't Be Installed Error (Code 80240020) - Complete Solution
date: 2024-10-13T04:32:33.297Z
updated: 2024-10-18T20:07:10.809Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing Windows 10 Can't Be Installed Error (Code 80240020) - Complete Solution
excerpt: This Article Describes Fixing Windows 10 Can't Be Installed Error (Code 80240020) - Complete Solution
thumbnail: https://thmb.techidaily.com/e24c6a589d856da0a108fb73ed8aea987528294a85122e6caa68a425ef40bc26.jpg
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
<li><a href="https://eaxpv-info.techidaily.com/new-2024-approved-guide-to-streamlined-subscription-links-for-video-channels/"><u>[New] 2024 Approved Guide to Streamlined Subscription Links for Video Channels</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/new-best-free-webm-players/"><u>[New] Best Free WebM Players</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-2024-approved-effortless-glamour-examples/"><u>[Updated] 2024 Approved Effortless Glamour Examples</u></a></li>
<li><a href="https://common-error.techidaily.com/a-step-by-step-approach-to-fix-your-hardware-driver-for-a-seamless-world-of-warcraft-experience/"><u>A Step-by-Step Approach to Fix Your Hardware Driver for a Seamless World of Warcraft Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-game-launch-issues-how-to-recover-missing-physxloaderdll/"><u>Fix Your Game Launch Issues: How to Recover Missing physxloader.dll</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-activate-and-use-life360-ghost-mode-on-oppo-reno-8t-5g-drfone-by-drfone-virtual-android/"><u>How To Activate and Use Life360 Ghost Mode On Oppo Reno 8T 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-safely-resolve-the-critical-error-warning-in-your-google-chrome-browser/"><u>How To Safely Resolve The Critical Error Warning In Your Google Chrome Browser</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-how-to-track-poco-c51-by-phone-number-drfone-by-drfone-virtual-android/"><u>In 2024, How to Track Poco C51 by Phone Number | Dr.fone</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-the-rich-tapestry-of-ajeys-channel-wealth/"><u>In 2024, The Rich Tapestry of Ajey's Channel Wealth</u></a></li>
<li><a href="https://common-error.techidaily.com/instant-fixes-for-failed-pdf-printer-connections/"><u>Instant Fixes for Failed PDF Printer Connections</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-pc-or-mac-mic-stops-working/"><u>Quick Fixes for When Your PC or Mac Mic Stops Working</u></a></li>
<li><a href="https://facebook.techidaily.com/renewable-rush-at-fb-complete-energy-overhaul-for-the-future/"><u>Renewable Rush at FB: Complete Energy Overhaul for the Future</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-overcoming-windows-update-error-0x800701f/"><u>Step-by-Step Guide: Overcoming Windows Update Error 0X80070#1F</u></a></li>
<li><a href="https://sound-issues.techidaily.com/step-by-step-method-to-amplify-your-pcs-speakers-on-windows-10/"><u>Step-by-Step Method to Amplify Your PC's Speakers on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/top-tricks-to-thaw-your-stuck-windows-11-taskbar-quickly/"><u>Top Tricks to Thaw Your Stuck Windows 11 Taskbar Quickly</u></a></li>
<li><a href="https://android-unlock.techidaily.com/unlocking-the-power-of-smart-lock-a-beginners-guide-for-sony-xperia-5-v-users-by-drfone-android/"><u>Unlocking the Power of Smart Lock A Beginners Guide for Sony Xperia 5 V Users</u></a></li>
<li><a href="https://common-error.techidaily.com/usb-error-no-more-eliminate-device-not-detected-pop-ups-forever/"><u>USB Error No More: Eliminate 'Device Not Detected' Pop-Ups Forever</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135374/19272" target="_top" id="2135374">
  <img src="//a.impactradius-go.com/display-ad/19272-2135374" border="0" alt="https://techidaily.com" width="468" height="60"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135374/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

