---
title: "Fixing the 'Call of Duty: WW2' Error Code #4220 - Step-by-Step Instructions"
date: 2024-09-12T16:11:32.826Z
updated: 2024-09-15T16:00:18.955Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the 'Call of Duty: WW2' Error Code #4220 - Step-by-Step Instructions"
excerpt: "This Article Describes Fixing the 'Call of Duty: WW2' Error Code #4220 - Step-by-Step Instructions"
thumbnail: https://thmb.techidaily.com/d4527039f6a1a287d2df17fa899a5ac8403841092ccbbf441a17ff63d6863be1.png
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
<li><a href="https://common-error.techidaily.com/fixed-aoc-usb-monitor-not-working-on-windows-11/"><u>[FIXED] AOC USB Monitor Not Working on Windows 11</u></a></li>
<li><a href="https://facebook-clips.techidaily.com/new-facebook-video-maker-how-to-make-facebook-video/"><u>[New] Facebook Video Maker How to Make Facebook Video</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/new-innovative-mount-tech-for-smooth-sensor-motion/"><u>[New] Innovative Mount Tech for Smooth Sensor Motion</u></a></li>
<li><a href="https://twitter-videos.techidaily.com/updated-transformative-tutorial-turning-vids-on-twitter-into-catchy-animated-memes-gifs-for-2024/"><u>[Updated] Transformative Tutorial Turning Vids on Twitter Into Catchy Animated Memes (GIFs) for 2024</u></a></li>
<li><a href="https://extra-hints.techidaily.com/2024-approved-crafting-captivating-content-with-correct-dimensions/"><u>2024 Approved Crafting Captivating Content with Correct Dimensions</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-correcting-the-unresponsive-spacebar-problem-on-your-windows-10-device/"><u>Diagnosing and Correcting the Unresponsive Spacebar Problem on Your Windows 10 Device</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/explore-the-potential-of-wonder-workshops-dash-a-full-review/"><u>Explore the Potential of Wonder Workshop's Dash: A Full Review</u></a></li>
<li><a href="https://common-error.techidaily.com/1723211342842-facing-printer-issues-with-pdfs-here-are-fast-remedies/"><u>Facing Printer Issues with PDFs? Here Are Fast Remedies!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-scroll-functionality-for-a-non-responsive-touchpad-in-windows-11-computers/"><u>How to Restore Scroll Functionality for a Non-Responsive Touchpad in Windows 11 Computers</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-iphone-15-with-an-apple-watch-and-what-to-do-if-it-doesnt-work-by-drfone-ios/"><u>In 2024, How to Unlock iPhone 15 With an Apple Watch & What to Do if It Doesnt Work</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-windows-10-new-features-at-a-glance/"><u>In 2024, Windows 10 New Features at a Glance</u></a></li>
<li><a href="https://common-error.techidaily.com/1723207435318-troubleshooting-guide-starting-the-hosted-network-in-windows-10-fixed/"><u>Troubleshooting Guide: Starting the Hosted Network in Windows 10 Fixed!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135354/19272" target="_top" id="2135354">
  <img src="//a.impactradius-go.com/display-ad/19272-2135354" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135354/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

