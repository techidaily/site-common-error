---
title: "Fixing the Issue: Why Your DVD Isn't Working on a Windows PC"
date: 2024-09-29T19:11:17.289Z
updated: 2024-10-01T22:25:23.785Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the Issue: Why Your DVD Isn't Working on a Windows PC"
excerpt: "This Article Describes Fixing the Issue: Why Your DVD Isn't Working on a Windows PC"
thumbnail: https://thmb.techidaily.com/c27c29fba053b8832f23b24095348059aefd5880debbcb1a483191d3fe3d1075.jpg
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
<li><a href="https://article-tips.techidaily.com/new-making-every-photo-on-iphone-blurry-with-4-tricks-up-your-sleeve/"><u>[New] Making Every Photo on iPhone Blurry with 4 Tricks Up Your Sleeve</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-intel-rst-service-is-not-running-on-windows-11/"><u>[Solved] Intel RST Service Is Not Running on Windows 11</u></a></li>
<li><a href="https://discord-videos.techidaily.com/updated-in-2024-immerse-in-imagination-the-bestdiscords-10-creations/"><u>[Updated] In 2024, Immerse in Imagination The BestDiscord’s 10 Creations</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/updated-understanding-absence-of-direct-messages/"><u>[Updated] Understanding Absence of Direct Messages</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/4-solution-to-get-rid-of-pokemon-fail-to-detect-location-on-infinix-hot-40i-drfone-by-drfone-virtual-android/"><u>4 solution to get rid of pokemon fail to detect location On Infinix Hot 40i | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/banishing-awakenings-sleep-mode-mastery-in-win11/"><u>Banishing Awakenings: Sleep Mode Mastery in Win11</u></a></li>
<li><a href="https://discover-exclusive.techidaily.com/comment-changer-vite-un-fichier-mkv-en-mp4-sans-pertes-de-definition/"><u>Comment Changer Vite Un Fichier MKV en MP4 Sans Pertes De Définition ?</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-fix-missing-binkw32dll-on-your-pc/"><u>Comprehensive Solutions to Fix Missing binkw32.dll on Your PC</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-restoring-your-dells-broken-usb-interface/"><u>Effective Remedies for Restoring Your Dell's Broken USB Interface</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/in-2024-chromebook-video-editing-mastery-how-to-use-any-app-regardless-of-os/"><u>In 2024, Chromebook Video Editing Mastery How to Use Any App, Regardless of OS</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-how-can-i-use-a-fake-gps-without-mock-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>In 2024, How Can I Use a Fake GPS Without Mock Location On Samsung Galaxy M34 5G? | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-honor-100-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Honor 100 | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/introducing-top-tier-facebook-update-insights-for-2024/"><u>Introducing Top-Tier Facebook Update Insights for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/1723202808950-microsoft-wireless-screen-projector-connectivity-woes-on-windows-10-heres-the-solution/"><u>Microsoft Wireless Screen Projector Connectivity Woes on Windows 10? Here's the Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-the-challenge-of-a-defective-laptop-mic-effective-troubleshooting-techniques/"><u>Overcoming the Challenge of a Defective Laptop Mic: Effective Troubleshooting Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-your-remote-click-with-logitech-fix/"><u>Revive Your Remote Click with Logitech Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/update-your-graphics-driver-to-activate-seamless-screen-mirroring-via-miracast/"><u>Update Your Graphics Driver to Activate Seamless Screen Mirroring via Miracast</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082529/7443" target="_top" id="2082529">
  <img src="//a.impactradius-go.com/display-ad/7443-2082529" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082529/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

