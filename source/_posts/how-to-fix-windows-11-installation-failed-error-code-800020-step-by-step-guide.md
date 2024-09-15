---
title: How to Fix Windows 11 Installation Failed Error Code 80#0020 - Step-by-Step Guide
date: 2024-09-12T16:13:20.307Z
updated: 2024-09-15T16:06:50.152Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix Windows 11 Installation Failed Error Code 80#0020 - Step-by-Step Guide
excerpt: This Article Describes How to Fix Windows 11 Installation Failed Error Code 80#0020 - Step-by-Step Guide
thumbnail: https://thmb.techidaily.com/c48a785cefdb0843c6e76d439ab755593afd7522af39269117f83ccabe84316f.png
---

## Expert Tips for Resolving the 'Windows 10 Couldn't Be Installed (Error Eb80240020)' Dilemma – Step-by-Step Solutions Included

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
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-from-digital-avatars-to-internet-stardom-becoming-a-vtuber/"><u>[Updated] In 2024, From Digital Avatars to Internet Stardom – Becoming a Vtuber?</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/updated-integrated-iptv-accessibility-for-2024/"><u>[Updated] Integrated IPTV Accessibility for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-unlocking-potential-creating-compelling-content-on-your-phone/"><u>[Updated] Unlocking Potential Creating Compelling Content on Your Phone</u></a></li>
<li><a href="https://tech-haven.techidaily.com/how-effective-are-vpns-in-protecting-chatgpt-data/"><u>How Effective Are VPNs in Protecting ChatGPT Data?</u></a></li>
<li><a href="https://ios-location-track.techidaily.com/in-2024-how-to-spy-on-text-messages-from-computer-and-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>In 2024, How to Spy on Text Messages from Computer & Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-device-doesnt-accept-miracast-problem-insights-and-fixes/"><u>Overcoming the 'Device Doesn't Accept Miracast' Problem – Insights & Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-promptly-handling-startup-failure-error-1053-for-system-services/"><u>Resolved Issue: Promptly Handling Startup Failure (Error 1053) for System Services</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/1723807980591-step-by-step-guide-hooking-up-your-laptop-to-a-television-via-hdmi-includes-images/"><u>Step-by-Step Guide: Hooking Up Your Laptop to a Television via HDMI - Includes Images</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-boot-sector-virus-error-code-0xc00000e9-on-windows-pcs/"><u>Step-by-Step Solution for Boot Sector Virus (Error Code 0xC00000E9) on Windows PCs</u></a></li>
<li><a href="https://buynow-info.techidaily.com/the-ultimate-review-unveiling-superiority-of-apples-m1-mac-mini-in-a-competitive-landscape/"><u>The Ultimate Review: Unveiling Superiority of Apple's M1 Mac Mini in a Competitive Landscape</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-complete-solutions-for-total-war-rome-crashes-on-pcmac/"><u>Troubleshooting Complete Solutions for Total War: Rome Crashes on PC/MAC</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1993645">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1993645.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1993645">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1993645.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1993645%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1993645/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

