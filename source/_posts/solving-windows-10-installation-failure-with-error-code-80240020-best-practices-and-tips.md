---
title: "Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
date: 2025-01-04T23:25:16.634Z
updated: 2025-01-10T18:45:54.042Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
excerpt: "This Article Describes Solving Windows 10 Installation Failure with Error Code 80240020: Best Practices and Tips"
thumbnail: https://thmb.techidaily.com/c616a530c3b86047af7fee8d712f3caf3cb46a3e47132cccfb907573c9519566.jpg
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
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-expanding-digital-presence-stream-to-youtube-plus-additional-platforms/"><u>[New] In 2024, Expanding Digital Presence Stream to YouTube + Additional Platforms</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-dynamic-presenters-discourse-analysis-8th-ver/"><u>[Updated] In 2024, Dynamic Presenter's Discourse Analysis 8Th Ver</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-tips-for-dimming-windows-and-mac-music-volume/"><u>[Updated] Tips for Dimming Windows & Mac Music Volume</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-top-8-iphone-sketchers-exceptional-drawing-apps-reviewed-for-2024/"><u>[Updated] Top 8 iPhone Sketchers Exceptional Drawing Apps Reviewed for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/chrome-clarity-restored-expert-tips-to-resolve-the-unexpected-blackout-issue/"><u>Chrome Clarity Restored: Expert Tips to Resolve the Unexpected Blackout Issue</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-controlling-svchostexes-netsvcs-network-overload-problems/"><u>Effective Remedies for Controlling Svchost.exe's (Netsvcs) Network Overload Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-strategies-to-address-and-resolve-the-troublesome-windows-update-error-0x8024402c/"><u>Effective Strategies to Address and Resolve the Troublesome Windows Update Error: 0X8024402c</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/elevate-your-video-game-on-instagram-with-right-dimensions-for-2024/"><u>Elevate Your Video Game on Instagram with Right Dimensions for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-optimize-your-pc-fixing-high-gpu-use-with-windows-11s-desktop-window-manager/"><u>How To Optimize Your PC: Fixing High GPU Use with Windows 11'S Desktop Window Manager</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-full-guide-to-catch-100-iv-pokemon-using-a-map-on-realme-gt-neo-5-drfone-by-drfone-virtual-android/"><u>In 2024, Full Guide to Catch 100 IV Pokémon Using a Map On Realme GT Neo 5 | Dr.fone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-how-do-you-remove-restricted-mode-on-iphone-13-pro-drfone-by-drfone-ios/"><u>In 2024, How Do You Remove Restricted Mode on iPhone 13 Pro | Dr.fone</u></a></li>
<li><a href="https://review-topics.techidaily.com/online-electronic-signature-for-pdf-v14-document-by-ldigisigner-sign-a-pdf-sign-a-pdf/"><u>Online electronic signature for PDF v1.4 document</u></a></li>
<li><a href="https://windows11.techidaily.com/solutions-for-unstartable-windows-vms-with-vmware/"><u>Solutions for Unstartable Windows VMs with VMware</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-lenovo-mouse-pad-issues-on-windows-11-quick-fix-guide/"><u>Solving Lenovo Mouse Pad Issues on Windows 11: Quick Fix Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/tips-and-tricks-to-rectify-slow-typing-on-your-devices-keyboard/"><u>Tips and Tricks to Rectify Slow Typing on Your Device's Keyboard</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/GPk8_xpN_rA?si=YbAdgsjAKsCn_UsB" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
<!-- affiliate ads end -->

