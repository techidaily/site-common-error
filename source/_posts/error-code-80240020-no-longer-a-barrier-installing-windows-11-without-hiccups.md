---
title: "Error Code 80240020 No Longer a Barrier: Installing Windows 11 Without Hiccups"
date: 2024-10-04T06:58:45.043Z
updated: 2024-10-06T21:57:11.197Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Error Code 80240020 No Longer a Barrier: Installing Windows 11 Without Hiccups"
excerpt: "This Article Describes Error Code 80240020 No Longer a Barrier: Installing Windows 11 Without Hiccups"
thumbnail: https://thmb.techidaily.com/c45afa71b37443a1f59fe90234d68b3b0e50e4c51b39e47e7a2ccf645d397043.PNG
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
<li><a href="https://screen-recording.techidaily.com/new-in-2024-saving-powerpoint-presentation-to-video/"><u>[New] In 2024, Saving PowerPoint Presentation to Video</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-in-2024-the-ultimate-video-twist-guide-from-portrait-to-panoramic-on-instagram/"><u>[New] In 2024, The Ultimate Video Twist Guide From Portrait to Panoramic on Instagram</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-remove-google-chrome-critical-error-scam/"><u>[Solved] How to Remove Google Chrome Critical Error SCAM</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/ed-amplify-impact-through-effective-video-marketing-on-youtubes-top-5-moves-for-2024/"><u>[Updated] Amplify Impact Through Effective Video Marketing on YouTube's Top 5 Moves for 2024</u></a></li>
<li><a href="https://buynow-tips.techidaily.com/acer-xfa240-assessment-prioritizing-performance-and-utility/"><u>Acer XFA240 Assessment: Prioritizing Performance and Utility</u></a></li>
<li><a href="https://article-posts.techidaily.com/breakthrough-strategies-for-rapid-fb-media-delivery/"><u>Breakthrough Strategies for Rapid FB Media Delivery</u></a></li>
<li><a href="https://common-error.techidaily.com/device-driver-error-resolved-ensuring-full-compatibility-within-wow-and-windows/"><u>Device Driver Error Resolved: Ensuring Full Compatibility Within WoW & Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-guide-to-reconnecting-your-chromecast-for-smooth-streaming/"><u>Effortless Guide to Reconnecting Your Chromecast for Smooth Streaming</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-successfully-set-up-battleye-anti-cheat-problems-solved/"><u>How To Successfully Set Up BattlEye Anti-Cheat: Problems Solved!</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-how-and-where-to-find-a-shiny-stone-pokemon-for-vivo-y27-4g-drfone-by-drfone-virtual-android/"><u>In 2024, How and Where to Find a Shiny Stone Pokémon For Vivo Y27 4G? | Dr.fone</u></a></li>
<li><a href="https://change-location.techidaily.com/reasons-why-pokemon-gps-does-not-work-on-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>Reasons why Pokémon GPS does not Work On Samsung Galaxy S23 FE? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-gaming-halt-quick-fix-for-pc-pauses/"><u>Resolve Gaming Halt: Quick Fix for PC Pauses</u></a></li>
<li><a href="https://tech-hub.techidaily.com/the-core-variations-understanding-nlp-in-relation-to-machine-learning-techniques/"><u>The Core Variations: Understanding NLP in Relation to Machine Learning Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-your-unprintable-pdf-with-these-easy-fixes/"><u>Troubleshoot Your Unprintable PDF with These Easy Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolve-your-airpods-connection-issues-on-windows-11-top-strategies/"><u>Troubleshooting Guide: Resolve Your AirPods Connection Issues on Windows 11 - Top Strategies</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/857865/11832" target="_top" id="857865">
  <img src="//a.impactradius-go.com/display-ad/11832-857865" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/857865/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

