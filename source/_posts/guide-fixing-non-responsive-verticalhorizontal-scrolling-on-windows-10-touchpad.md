---
title: "Guide: Fixing Non-Responsive Vertical/Horizontal Scrolling on Windows 10 Touchpad"
date: 2024-10-02T11:17:40.980Z
updated: 2024-10-07T00:55:53.503Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Guide: Fixing Non-Responsive Vertical/Horizontal Scrolling on Windows 10 Touchpad"
excerpt: "This Article Describes Guide: Fixing Non-Responsive Vertical/Horizontal Scrolling on Windows 10 Touchpad"
thumbnail: https://thmb.techidaily.com/5e0a2202e9f4da31ba85b59400bc244193601b11b41dcc123e47e5f9015f53a2.jpg
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
<li><a href="https://fox-hovers.techidaily.com/new-comprehensive-motion-dynamics-synopsis-for-2024/"><u>[New] Comprehensive Motion Dynamics Synopsis for 2024</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-stepping-up-advanced-techniques-for-w11-gamers/"><u>[Updated] Stepping Up Advanced Techniques for W11 Gamers</u></a></li>
<li><a href="https://fox-blue.techidaily.com/2024-approved-how-to-reactivate-your-photo-viewer-in-win-11-proactively/"><u>2024 Approved How to Reactivate Your Photo Viewer in Win 11 Proactively</u></a></li>
<li><a href="https://common-error.techidaily.com/reset-troubles-learn-proven-methods-to-refresh-your-keyboard-today/"><u>Reset Troubles? Learn Proven Methods to Refresh Your Keyboard Today!</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-steps-to-resolve-your-nonfunctional-wi-fi-connection/"><u>Simple Steps to Resolve Your Nonfunctional Wi-Fi Connection</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/the-art-of-framing-making-an-effective-youtube-introductory-vids/"><u>The Art of Framing Making an Effective YouTube Introductory Vids</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-outlook-cannot-reach-microsoft-exchange-server-errors/"><u>Troubleshooting Steps for 'Outlook Cannot Reach Microsoft Exchange Server' Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/uncover-the-answers-total-war-rome-remastered-gameplay-interruptions-solved/"><u>Uncover the Answers: Total War: Rome Remastered Gameplay Interruptions Solved!</u></a></li>
<li><a href="https://hardware-tips.techidaily.com/unveiling-new-gadgets-and-components-at-toms-tech-zone/"><u>Unveiling New Gadgets and Components at Tom's Tech Zone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1982596">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982596.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982596">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982596.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982596%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982596/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

