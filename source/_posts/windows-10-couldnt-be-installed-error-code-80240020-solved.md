---
title: Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]
date: 2024-09-10T04:11:58.701Z
updated: 2024-09-15T09:51:26.074Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]
excerpt: This Article Describes Windows 10 Couldn’t Be Installed Error Code 80240020 [Solved]
thumbnail: https://thmb.techidaily.com/ebbfde368b81e7f396fe512ace44b149bef6fef394a1d6fd8cfa20e2c4a0b6c3.jpg
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
<li><a href="https://screen-capture.techidaily.com/new-in-2024-no-cost-android-facetime-replacements-ranked/"><u>[New] In 2024, No-Cost Android FaceTime Replacements Ranked</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/n-2024-ultimate-guide-to-exclusive-youtube-gamers-intros-freepaid/"><u>[New] In 2024, Ultimate Guide to Exclusive YouTube Gamers' Intros (Free/Paid)</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/2024-approved-peeking-beyond-one-camera-limitations/"><u>2024 Approved Peeking Beyond One-Camera Limitations</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/decoding-audio-gear-how-are-home-theater-amplifiers-different-from-stereo-receivers/"><u>Decoding Audio Gear: How Are Home Theater Amplifiers Different From Stereo Receivers?</u></a></li>
<li><a href="https://win-amazing.techidaily.com/1722960010048-get-the-newest-drivers-for-canon-pixma-ts3322-download-here/"><u>Get the Newest Drivers for Canon PIXMA TS3322 - Download Here</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-get-microsoft-print-to-pdf-functionality-running-smoothly-on-your-pc-windows-1011/"><u>How to Get Microsoft Print to PDF Functionality Running Smoothly on Your PC (Windows 10/11)</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/how-to-unlock-iphone-xs-max-online-here-are-6-easy-ways-by-drfone-ios/"><u>How to Unlock iPhone XS Max Online? Here are 6 Easy Ways</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-common-problems-and-fixes-for-the-non-functional-mic-on-steelseries-arctis-5-headset/"><u>Solved: Common Problems and Fixes for the Non-Functional Mic on SteelSeries Arctis 5 Headset</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-why-wont-my-usb-composite-device-work-with-usb-30-troubleshooting-tips-inside/"><u>Solved! Why Won't My USB Composite Device Work with USB 3.0? Troubleshooting Tips Inside</u></a></li>
<li><a href="https://some-approaches.techidaily.com/the-clear-path-to-crisp-videography-on-a-gopro-for-2024/"><u>The Clear Path to Crisp Videography on a GoPro for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/will-pokemon-go-ban-the-account-if-you-use-pgsharp-on-xiaomi-redmi-12-drfone-by-drfone-virtual-android/"><u>Will Pokémon Go Ban the Account if You Use PGSharp On Xiaomi Redmi 12 | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<span id="1424528">
					<video width="864" height="1536" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1424528.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/16446-1424528">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1424528.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:540px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Flaganoo.pxf.io%2Fc%2F5597632%2F1424528%2F16446'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1424528/16446" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

