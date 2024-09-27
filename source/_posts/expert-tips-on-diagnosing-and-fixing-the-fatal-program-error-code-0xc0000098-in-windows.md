---
title: Expert Tips on Diagnosing and Fixing the Fatal Program Error Code 0Xc0000098 in Windows
date: 2024-09-21T18:29:10.853Z
updated: 2024-09-26T18:42:37.877Z
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
<li><a href="https://extra-skills.techidaily.com/2024-approved-kinemasters-guide-to-fluid-film-segments/"><u>2024 Approved Kinemaster's Guide to Fluid Film Segments</u></a></li>
<li><a href="https://extra-hints.techidaily.com/a-new-era-of-visual-clarity-the-10-list-of-top-monitors-for-macs/"><u>A New Era of Visual Clarity The #10 List of Top Monitors for Macs</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/cutting-edge-resume-writing-via-chatgpt-techniques/"><u>Cutting-Edge Resume Writing via ChatGPT Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnose-and-repair-the-problem-of-non-detectable-usb-devices-on-a-windows-11-system/"><u>Diagnose and Repair the Problem of Non-Detectable USB Devices on a Windows 11 System</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-guide-recovering-missing-or-hidden-windows-on-your-pc/"><u>Easy Guide: Recovering Missing or Hidden Windows on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-repairs-for-nonfunctional-lenovo-mouse-pads-in-win11-8-or-7-comprehensive-guide/"><u>Easy Repairs for Nonfunctional Lenovo Mouse Pads in Win11, 8 or 7 – Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-oppo-find-n3-flip-get-deleted-photos-back-with-ease-and-safety-by-fonelab-android-recover-photos/"><u>How to Oppo Find N3 Flip Get Deleted photos Back with Ease and Safety?</u></a></li>
<li><a href="https://android-location.techidaily.com/in-2024-easy-ways-to-manage-your-honor-magic5-ultimate-location-settings-drfone-by-drfone-virtual/"><u>In 2024, Easy Ways to Manage Your Honor Magic5 Ultimate Location Settings | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-dell-laptops-dead-keys-a-step-by-step-guide/"><u>Revive Your Dell Laptop's Dead Keys: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-destiny-2-server-connectivity-problems-a-step-by-step-guide/"><u>Solving Destiny 2 Server Connectivity Problems: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-resolving-logitech-g930-sound-cuts-and-glitches/"><u>Step-by-Step Guide to Resolving Logitech G930 Sound Cuts and Glitches</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/step-by-step-instructions-for-installing-a-racing-steering-wheel-into-your-computer-setup/"><u>Step-by-Step Instructions for Installing a Racing Steering Wheel Into Your Computer Setup</u></a></li>
<li><a href="https://some-tips.techidaily.com/top-tune-tracker-and-manager-android-companion-for-2024/"><u>Top Tune Tracker & Manager, Android Companion for 2024</u></a></li>
</ul></div>

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

