---
title: Resolving Stalled Windows 10 Installation for Smooth Upgrades
date: 2024-09-22T22:00:46.912Z
updated: 2024-09-26T19:22:29.450Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Resolving Stalled Windows 10 Installation for Smooth Upgrades
excerpt: This Article Describes Resolving Stalled Windows 10 Installation for Smooth Upgrades
thumbnail: https://thmb.techidaily.com/5c41e214e42161b19b3ba596b247b1528c5c85cbd29aaa92283a320b0b166cc8.jpg
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
<li><a href="https://video-screen-grab.techidaily.com/new-in-2024-securing-skype-conversations-via-obs/"><u>[New] In 2024, Securing Skype Conversations via OBS</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-insights-into-instagrams-maxed-out-videos/"><u>[New] Insights Into Instagram's Maxed-Out Videos</u></a></li>
<li><a href="https://fox-helps.techidaily.com/new-the-art-of-increasing-indoor-ambiance-via-sunlight-for-2024/"><u>[New] The Art of Increasing Indoor Ambiance via Sunlight for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-the-lexicon-of-persuasion-in-business-communication/"><u>[Updated] The Lexicon of Persuasion in Business Communication</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-zd-soft-screen-recorder-key-features-and-review-for-2024/"><u>[Updated] ZD Soft Screen Recorder Key Features and Review for 2024</u></a></li>
<li><a href="https://extra-information.techidaily.com/apple-vs-android-the-face-id-and-galaxy-recognition-race/"><u>Apple Vs. Android The Face ID and Galaxy Recognition Race</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-fixes-for-ps4-network-errors-a-detailed-walkthrough/"><u>Complete Fixes for PS4 Network Errors: A Detailed Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/decoding-the-unspecified-error-a-detailed-walkthrough-on-overcoming-0x80004005-issues/"><u>Decoding the 'Unspecified Error' - A Detailed Walkthrough on Overcoming 0X80004005 Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/enduring-smooth-visuals-in-valorant-a-complete-guide-for-dealing-with-tech-glitches-and-tearing-fixes/"><u>Enduring Smooth Visuals in Valorant: A Complete Guide for Dealing with Tech Glitches and Tearing Fixes</u></a></li>
<li><a href="https://article-files.techidaily.com/funny-ringtones-where-to-download-them-in-2024/"><u>Funny Ringtones Where to Download Them, In 2024</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-how-to-use-phone-clone-to-migrate-your-realme-narzo-60x-5g-data-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, How to Use Phone Clone to Migrate Your Realme Narzo 60x 5G Data? | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/next-level-programming-expert-reviews-on-best-online-tech-classes/"><u>Next-Level Programming: Expert Reviews on Best Online Tech Classes</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-chrome-unresponsiveness-efficient-methods-for-relaunching-your-browser/"><u>Overcome Chrome Unresponsiveness: Efficient Methods for Relaunching Your Browser</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-minecraft-crashes-due-to-faulty-graphics-driver-issues-in-windows-solutions/"><u>Resolving Minecraft Crashes Due to Faulty Graphics Driver Issues in Windows - Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-remedies-to-address-frequent-system-hibernations-on-windows-and-macs/"><u>Simple Remedies to Address Frequent System Hibernations on Windows and Macs</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-pc-connection-issues-with-bluetooth-input-devices/"><u>Step-by-Step Solution for PC Connection Issues with Bluetooth Input Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-when-your-microsoft-surface-wont-charge-even-though-its-connected-step-by-step-solution/"><u>The Ultimate Fix for When Your Microsoft Surface Won't Charge Even Though It’s Connected: Step-by-Step Solution!</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://wigfever.sjv.io/c/5597632/2014851/22899" target="_top" id="2014851">
  <img src="//a.impactradius-go.com/display-ad/22899-2014851" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://wigfever.sjv.io/i/5597632/2014851/22899" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

