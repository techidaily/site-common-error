---
title: Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
date: 2025-02-24T13:40:44.426Z
updated: 2025-03-02T03:24:58.145Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
excerpt: This Article Describes Fixing 'Red Dead Redemption 2' Memory Issues by Adjusting Virtual Memory Settings
thumbnail: https://thmb.techidaily.com/be26802ef5bb50783815300426404d3fea7e0b5a3f7f648e31ee7c5865304f02.jpg
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
<li><a href="https://fox-direct.techidaily.com/new-future-gaming-top-5-psvr-releases-on-the-horizon-for-2024/"><u>[New] Future Gaming Top 5 PSVR Releases on the Horizon for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-non-google-options-for-augmented-reality-embellishing/"><u>[New] Non-Google Options for Augmented Reality Embellishing</u></a></li>
<li><a href="https://some-approaches.techidaily.com/new-top-10-picture-frames-and-organizers/"><u>[New] Top 10 Picture Frames & Organizers</u></a></li>
<li><a href="https://youtube-tips.techidaily.com/ed-expert-tips-for-converting-your-favorite-videos-into-animated-shareable-gifs-for-2024/"><u>[Updated] Expert Tips for Converting Your Favorite Videos Into Animated, Shareable GIFs for 2024</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/ed-in-2024-ultimate-guide-to-youtube-app-on-iphones-and-androids/"><u>[Updated] In 2024, Ultimate Guide to YouTube App on iPhones and Androids</u></a></li>
<li><a href="https://data-safeguard.techidaily.com/cookiebots-role-in-streamlining-online-marketing-efforts/"><u>Cookiebot's Role in Streamlining Online Marketing Efforts</u></a></li>
<li><a href="https://common-error.techidaily.com/custom-settings-reactivated-overcame-non-responsive-error/"><u>Custom Settings Reactivated – Overcame Non-Responsive Error</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-slow-download-problem-in-league-of-legends-once-and-for-all/"><u>Fixing the Slow Download Problem in League of Legends Once and For All</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-the-troublesome-windows-photo-capture-issue-error-code-0xa00f4292-explained/"><u>How to Fix the Troublesome Windows Photo Capture Issue: Error Code 0xA00F4292 Explained</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-change-your-vivo-s18e-location-on-life360-without-anyone-knowing-drfone-by-drfone-virtual-android/"><u>In 2024, How to Change Your Vivo S18e Location on life360 Without Anyone Knowing? | Dr.fone</u></a></li>
<li><a href="https://video-ai-editor.techidaily.com/noise-reduction-mastery-tips-and-tricks-for-final-cut-pro-x-users/"><u>Noise Reduction Mastery Tips and Tricks for Final Cut Pro X Users</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-windows-10-cannot-be-installed-error-80240020-step-by-step-solutions/"><u>Resolving Windows 10 Cannot Be Installed: Error 80240020 – Step-by-Step Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-solutions-resolve-error-code-0x800f0831-via-windows-updates/"><u>Simple Solutions: Resolve Error Code 0X800f0831 via Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-a-bluetooth-keyboard-that-refuses-to-sync-with-your-personal-computer/"><u>Step-by-Step Solutions for a Bluetooth Keyboard That Refuses to Sync with Your Personal Computer</u></a></li>
</ul></div>

