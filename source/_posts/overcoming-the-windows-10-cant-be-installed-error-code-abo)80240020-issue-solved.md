---
title: Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved!
date: 2025-02-24T17:04:44.854Z
updated: 2025-03-01T18:28:55.695Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved!
excerpt: This Article Describes Overcoming the 'Windows 10 Can't Be Installed (Error Code Abo>80240020)' Issue - Solved!
thumbnail: https://thmb.techidaily.com/f411804b07d8feb5757ac6a37c514ffad28202840ac720d56c6054350be2fb61.jpg
---

## Definitive Solutions to Windows 10 Setup Error Code 80240020 - Get Your System Running Now

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
<li><a href="https://facebook-videos.techidaily.com/new-in-2024-facebooks-easy-path-uploading-videos-via-pc-and-android-devices/"><u>[New] In 2024, Facebook's Easy Path Uploading Videos via PC and Android Devices</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-secrets-to-sustaining-high-view-count-in-youtube-videos/"><u>[Updated] Secrets to Sustaining High View Count in YouTube Videos</u></a></li>
<li><a href="https://common-error.techidaily.com/corsair-keyboard-darkness-issue-a-step-by-step-illumination-restoration-method/"><u>Corsair Keyboard Darkness Issue? A Step-by-Step Illumination Restoration Method</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-fixing-a-non-functional-mic-on-your-samsung-playstation-4-console/"><u>Expert Tips for Fixing a Non-Functional Mic on Your Samsung PlayStation 4 Console</u></a></li>
<li><a href="https://win-answers.techidaily.com/fix-your-mass-effect-legendary-launch-problems-with-these-simple-steps/"><u>Fix Your Mass Effect Legendary Launch Problems with These Simple Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/frozen-function-computer-wont-leave-win1110-snooze/"><u>Frozen Function: Computer Won't Leave Win11/10 Snooze</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/get-your-xerox-printing-essentials-free-window-compatible-printer-drivers-here/"><u>Get Your Xerox Printing Essentials: Free Window-Compatible Printer Drivers Here!</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/in-2024-2023-how-to-find-facebook-recently-watched-videos/"><u>In 2024, 2023 | How to Find Facebook Recently Watched Videos?</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/in-2024-how-to-add-transitions-on-inshot-app/"><u>In 2024, How to Add Transitions on Inshot App?</u></a></li>
<li><a href="https://win-amazing.techidaily.com/quick-download-insignia-graphics-driver-software-for-windows-systems/"><u>Quick Download: Insignia Graphics Driver Software for Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/simple-fixes-for-when-your-computer-wont-read-your-usb-flash-drive/"><u>Simple Fixes for When Your Computer Won't Read Your USB Flash Drive</u></a></li>
<li><a href="https://common-error.techidaily.com/skype-microphone-not-working-follow-these-steps-for-a-quick-and-easy-resolution/"><u>Skype Microphone Not Working? Follow These Steps for a Quick and Easy Resolution!</u></a></li>
<li><a href="https://howto.techidaily.com/top-4-android-system-repair-software-for-xiaomi-13t-pro-bricked-devices-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Top 4 Android System Repair Software for Xiaomi 13T Pro Bricked Devices | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-service-failed-to-start-issue-for-user-profiles-in-windows-10-and-11/"><u>Troubleshooting the 'Service Failed to Start' Issue for User Profiles in Windows 10 & 11</u></a></li>
</ul></div>

