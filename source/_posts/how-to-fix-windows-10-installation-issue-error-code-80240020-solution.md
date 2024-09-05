---
title: "How to Fix Windows 10 Installation Issue: Error Code 80240020 Solution"
date: 2024-09-04T20:21:44.448Z
updated: 2024-09-05T20:21:44.448Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes How to Fix Windows 10 Installation Issue: Error Code 80240020 Solution"
excerpt: "This Article Describes How to Fix Windows 10 Installation Issue: Error Code 80240020 Solution"
thumbnail: https://thmb.techidaily.com/da588ad139882f359e01e1480116ed64f1f64c7e5500ad5bb32d29ff957df078.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://digital-screen-recording.techidaily.com/updated-in-2024-advanced-strategies-for-no-sound-recording/"><u>[Updated] In 2024, Advanced Strategies for No-Sound Recording</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-premiere-smart-goggles-craftsmen/"><u>2024 Approved  Premiere Smart Goggles Craftsmen</u></a></li>
<li><a href="https://tech-revival.techidaily.com/building-and-tailoring-your-unique-chatgpt-experience-with-ease/"><u>Building and Tailoring Your Unique ChatGPT Experience with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/bypassing-valorants-stubborn-endless-load-screen-for-smooth-gameplay/"><u>Bypassing Valorant’s Stubborn Endless Load Screen for Smooth Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208786262-chromecast-wont-pair-discover-quick-solutions-for-better-connectivity/"><u>Chromecast Won't Pair? Discover Quick Solutions for Better Connectivity</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206476731-computer-freezes-at-startup-heres-what-you-need-to-know/"><u>Computer Freezes at Startup? Here's What You Need to Know</u></a></li>
<li><a href="https://blog-min.techidaily.com/convert-avchd-files-to-mp4-without-cost-on-windows-11-top-5-methods/"><u>Convert AVCHD Files to MP4 Without Cost on Windows 11: Top 5 Methods</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-repair-nonfunctional-ethernet-setup-in-windows-11-and-7-systems/"><u>Effective Techniques to Repair Nonfunctional Ethernet Setup in Windows 11 & 7 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/eradicating-input-lag-for-a-smoother-experience-with-windows-11-computers/"><u>Eradicating Input Lag for a Smoother Experience with Windows 11 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/essential-solutions-for-fixing-werfaultexe-errors-in-windows/"><u>Essential Solutions for Fixing werfault.exe Errors in Windows</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/facebooks-vanished-video-suggestions-explained-for-2024/"><u>Facebook's Vanished Video Suggestions Explained for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-your-pc-writes-on-kernel32/"><u>Fix Your PC' Writes on Kernel32</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-an-unresponsive-aoc-screen-on-your-windows-10-pc/"><u>How to Fix an Unresponsive AOC Screen on Your Windows 10 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-touchscreen-in-windows-11-5-ways/"><u>How to Fix Your Touchscreen in Windows 11 [5 Ways]</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-the-error-0x8024401c-during-updates-on-windows-11/"><u>How To Overcome The Error 0X8024401C During Updates On Windows 11</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-navigating-days-to-launch-podcasts/"><u>In 2024, Navigating Days to Launch Podcasts</u></a></li>
<li><a href="https://facebook-video-files.techidaily.com/in-2024-stream-and-share-successfully-with-fb-integration/"><u>In 2024, Stream & Share Successfully with FB Integration</u></a></li>
<li><a href="https://some-guidance.techidaily.com/macdvd-winx-dvd-ripper/"><u>Macで安全にDVDをコピー保存: WinX DVD Ripper 使い方ガイド【公式版】</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-technique-efficiently-restarting-your-malfunctioning-keyboard/"><u>Master the Technique: Efficiently Restarting Your Malfunctioning Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/master-the-trick-of-handling-persistent-restarts-on-your-windows-10-device/"><u>Master the Trick of Handling Persistent Restarts on Your Windows 10 Device</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208946528-nvidia-share-unresponsive-here-are-proven-solutions/"><u>NVIDIA Share Unresponsive? Here Are Proven Solutions!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-select-proper-boot-device-glitch-on-your-pc-effective-fixes-unveiled/"><u>Overcome 'Select Proper Boot Device' Glitch on Your PC: Effective Fixes Unveiled</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-error-code-39-issues-in-computer-media-players-tips-and-techniques-for-optical-drive-repair/"><u>Overcoming Error Code 39 Issues in Computer Media Players: Tips and Techniques for Optical Drive Repair</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-game-interruptions-resolving-warframes-pc-bugs/"><u>Overcoming Game Interruptions: Resolving Warframe's PC Bugs</u></a></li>
<li><a href="https://driver-download.techidaily.com/seamless-gaming-access-xbox-wireless-drivers-in-a-single-step/"><u>Seamless Gaming: Access Xbox Wireless Drivers in a Single Step</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-airpods-connection-issues-on-windows-1011-top-tips-for-2-cufflinks/"><u>Solving the AirPods Connection Issues on Windows 10/11: Top Tips for 2 Cufflinks</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-fixing-hp-deskjet-d1nker-printhead-installation-problems-in-multiple-windows-os-versions/"><u>Step-by-Step Guide to Fixing HP Deskjet D1nker Printhead Installation Problems in Multiple Windows OS Versions</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-correcting-misconfigured-elements-in-your-windows-setup/"><u>Step-by-Step Guide: Correcting Misconfigured Elements in Your Windows Setup</u></a></li>
<li><a href="https://techidaily.com/three-methods-to-recover-lost-data-on-vivo-v30-by-fonelab-android-recover-data/"><u>Three methods to recover lost data on Vivo V30</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-broken-usb-connections-in-windows-1011/"><u>Troubleshooting and Fixing Broken USB Connections in Windows 10/11</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-issues-with-pc-and-bluetooth-keyboard-connection/"><u>Troubleshooting Guide: Solving Issues with PC and Bluetooth Keyboard Connection</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-nier-automata-pc-crashes-top-solutions-for-players/"><u>Troubleshooting Nier Automata PC Crashes - Top Solutions for Players</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-stuck-google-chrome-expert-tactics-to-refresh-and-continue/"><u>Troubleshooting Stuck Google Chrome – Expert Tactics to Refresh and Continue</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-teredo-tunneling-overcoming-qualification-challenges/"><u>Troubleshooting Teredo Tunneling – Overcoming Qualification Challenges</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-youtubes-playback-problem-fixing-audio-malfunction-on-windows-10/"><u>Troubleshooting YouTube's Playback Problem: Fixing Audio Malfunction on Windows 10</u></a></li>
<li><a href="https://fake-location.techidaily.com/what-is-geo-blocking-and-how-to-bypass-it-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>What is Geo-Blocking and How to Bypass it On Realme V30T? | Dr.fone</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2068412/7443" target="_top" id="2068412">
  <img src="//a.impactradius-go.com/display-ad/7443-2068412" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2068412/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->