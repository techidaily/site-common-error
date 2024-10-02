---
title: Expert Tips on Diagnosing and Fixing the Fatal Program Error Code 0Xc0000098 in Windows
date: 2024-09-30T16:51:24.025Z
updated: 2024-10-01T18:59:33.063Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Expert Tips on Diagnosing and Fixing the Fatal Program Error Code 0Xc0000098 in Windows
excerpt: This Article Describes Expert Tips on Diagnosing and Fixing the Fatal Program Error Code 0Xc0000098 in Windows
thumbnail: https://thmb.techidaily.com/a399a44beb5899ba48cdf59ba448623d828236f52b18cfdee70ac40508a6e091.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

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
<li><a href="https://fox-http.techidaily.com/updated-in-2024-top-30-camcorders-eye-level-display-advantage/"><u>[Updated] In 2024, Top 30 Camcorders - Eye-Level Display Advantage</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204301340-bring-forth-the-hidden-touchpad-master-device-manager/"><u>Bring Forth the Hidden Touchpad, Master Device Manager</u></a></li>
<li><a href="https://fox-info.techidaily.com/exclusive-apps-to-record-on-iphone-for-2024/"><u>Exclusive Apps to Record on iPhone for 2024</u></a></li>
<li><a href="https://win11.techidaily.com/how-to-eliminate-windows-task-failure-error-0x8007000f/"><u>How to Eliminate Window's Task Failure Error 0X8007000f</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-overwatch-cannot-find-assets-issue-effectively/"><u>How to Fix 'Overwatch' Cannot Find Assets Issue Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-the-broken-left-shift-keys-on-your-pc-or-laptop/"><u>How to Repair the Broken Left Shift Keys on Your PC or Laptop</u></a></li>
<li><a href="https://buynow-info.techidaily.com/marvels-spider-man-sequel-review-a-deeper-dive-with-miles-morales/"><u>Marvel's Spider-Man Sequel Review: A Deeper Dive with Miles Morales</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-to-fix-the-livekernelevent-error-117/"><u>Step-by-Step Solution to Fix the LiveKernelEvent Error #117</u></a></li>
<li><a href="https://buynow-info.techidaily.com/theta-sc2-revealed-a-small-package-big-imagination/"><u>Theta SC2 Revealed: A Small Package, Big Imagination</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1983588">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1983588.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1983588">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1983588.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1983588%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1983588/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

