---
title: Navigating and Repairing Microsoft's Error Code 0X8024402c on Your PC
date: 2024-09-12T16:03:53.044Z
updated: 2024-09-15T16:01:36.518Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Navigating and Repairing Microsoft's Error Code 0X8024402c on Your PC
excerpt: This Article Describes Navigating and Repairing Microsoft's Error Code 0X8024402c on Your PC
thumbnail: https://thmb.techidaily.com/a1aef9ac34b30a9b89c44b4090cc093f70a661d81b3d63d1adb081d4443463d3.jpg
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
<li><a href="https://instagram-clips.techidaily.com/updated-top-insights-on-maximizing-business-engagement-on-insta/"><u>[Updated] Top Insights on Maximizing Business Engagement on Insta</u></a></li>
<li><a href="https://ios-pokemon-go.techidaily.com/9-mind-blowing-tricks-to-hatch-eggs-in-pokemon-go-without-walking-on-apple-iphone-x-drfone-by-drfone-virtual-ios/"><u>9 Mind-Blowing Tricks to Hatch Eggs in Pokemon Go Without Walking On Apple iPhone X | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/evaluating-comfort-and-style-a-thorough-look-at-the-cumuluspro-desk-mat-solution/"><u>Evaluating Comfort and Style: A Thorough Look at the CumulusPRO Desk Mat Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-high-disk-usage-caused-by-microsofts-telemetry-service-in-windows-11-systems/"><u>Fixing High Disk Usage Caused by Microsoft's Telemetry Service in Windows 11 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-how-to-successfully-power-off-your-computer-running-windows-11/"><u>Fixing the Issue: How to Successfully Power Off Your Computer Running Windows 11</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-recover-deleted-data-from-iphone-12-mini-using-stellar-data-recovery-for-iphone-stellar-by-stellar-data-recovery-ios-iphone-data-recovery/"><u>How to Recover Deleted Data from iPhone 12 mini using Stellar Data Recovery for iPhone? | Stellar</u></a></li>
<li><a href="https://tech-revival.techidaily.com/navigating-the-risks-how-to-integrate-chatgpt-wisely-into-mental-health-support/"><u>Navigating the Risks: How to Integrate ChatGPT Wisely Into Mental Health Support</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/real-time-recording-battle-obs-studio-against-fraps-for-2024/"><u>Real-Time Recording Battle OBS Studio Against Fraps for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-step-by-step-guide-to-overcome-the-preparing-to-configure-windows-issue/"><u>Resolved: Step-by-Step Guide to Overcome the 'Preparing to Configure Windows' Issue</u></a></li>
<li><a href="https://tech-revival.techidaily.com/1722062369320-top-7-incredible-chrome-add-ons-for-enhanced-chatgpt-interactions-improve-your-browser-experience-now/"><u>Top 7 Incredible Chrome Add-Ons for Enhanced ChatGPT Interactions: Improve Your Browser Experience Now!</u></a></li>
<li><a href="https://tech-hub.techidaily.com/unlock-the-code-retrieving-your-saved-wlan-passwords-easily-with-windows-11-tricks/"><u>Unlock the Code: Retrieving Your Saved WLAN Passwords Easily with Windows 11 Tricks</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135398/19272" target="_top" id="2135398">
  <img src="//a.impactradius-go.com/display-ad/19272-2135398" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135398/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

