---
title: How to Fix a Failing Remote Procedure Call - Comprehensive Guide
date: 2024-09-04T20:20:28.865Z
updated: 2024-09-05T20:20:28.865Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix a Failing Remote Procedure Call - Comprehensive Guide
excerpt: This Article Describes How to Fix a Failing Remote Procedure Call - Comprehensive Guide
thumbnail: https://thmb.techidaily.com/1015d95938322524d6bc75ebe9eaf3943bcb8d4c985b42fd4426ba3493876a07.jpg
---

## Windows 11 Installer Halted by Code 80240020? Here’s the Comprehensive Fix

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
<li><a href="https://youtube-stream.techidaily.com/new-guides-on-creating-cost-free-youtube-beginnings-and-conclusions/"><u>[New] Guides on Creating Cost-Free YouTube Beginnings & Conclusions</u></a></li>
<li><a href="https://fox-links.techidaily.com/new-mastering-metaverse-comedy-crafting-memetic-gold-for-2024/"><u>[New] Mastering Metaverse Comedy  Crafting Memetic Gold for 2024</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/new-ultimate-guide-macbook-cam-filming-basics/"><u>[New] Ultimate Guide  MacBook Cam Filming Basics</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-a-beginners-guide-to-flawless-ipad-screen-saving/"><u>[Updated] A Beginner's Guide to Flawless iPad Screen Saving</u></a></li>
<li><a href="https://fox-boxes.techidaily.com/updated-haste-assessment-of-windows-documents/"><u>[Updated] Haste Assessment of Windows Documents</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/updated-master-the-art-of-technological-advancement-with-this-guide/"><u>[Updated] Master the Art of Technological Advancement with This Guide</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-top-7-best-4k-action-cameras/"><u>2024 Approved  Top 7 Best 4K Action Cameras</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-ffxp-an-in-depth-guide/"><u>2024 Approved  Unveiling FFXP  An In-Depth Guide</u></a></li>
<li><a href="https://location-social.techidaily.com/3-things-you-must-know-about-fake-snapchat-location-on-samsung-galaxy-m34-5g-drfone-by-drfone-virtual-android/"><u>3 Things You Must Know about Fake Snapchat Location On Samsung Galaxy M34 5G | Dr.fone</u></a></li>
<li><a href="https://vp-tips.techidaily.com/bridging-words-to-visuals-the-scriptwriters-craft-for-2024/"><u>Bridging Words to Visuals  The Scriptwriter's Craft for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-walkthrough-repairing-the-black-monitor-problem-for-dell-computer-users/"><u>Complete Walkthrough: Repairing the Black Monitor Problem for Dell Computer Users</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-tackle-videodxgkrnl-fatal-issues-on-windows-machines/"><u>Comprehensive Solutions to Tackle Video_Dxgkrnl Fatal Issues on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-repairing-initialization-errors-for-windows-10-system-settings/"><u>Diagnosing and Repairing Initialization Errors for Windows 10 System Settings</u></a></li>
<li><a href="https://blog-min.techidaily.com/easiest-guide-how-to-clone-itel-a60-phone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>Easiest Guide How to Clone Itel A60 Phone? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/easy-to-fix-windows-update-error-0x80070652/"><u>Easy to Fix Windows Update Error 0X80070652</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-fixes-for-critical-issue-0x8024200d-during-windows-update-process-complete/"><u>Effective Fixes for Critical Issue 0X8024200d During Windows Update Process [COMPLETE]</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-tackling-error-0xc1900208-on-windows-11-updates-solved/"><u>Effective Remedies for Tackling Error 0xC1900208 on Windows 11 Updates [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/error-free-playtime-awaits-correcting-your-origin-game-installation-problems/"><u>Error-Free Playtime Awaits: Correcting Your Origin Game Installation Problems</u></a></li>
<li><a href="https://some-guidance.techidaily.com/estrategias-efectivas-para-desbloquear-contenido-protegido-por-disney-y-copiar-peliculas-de-disco-blu-ray/"><u>Estrategias Efectivas Para Desbloquear Contenido Protegido Por Disney Y Copiar Películas De Disco Blu-Ray</u></a></li>
<li><a href="https://tech-renaissance.techidaily.com/expert-analysis-of-western-digital-data-lifeguard-a-comprehensive-software-diagnostics-review/"><u>Expert Analysis of Western Digital Data Lifeguard: A Comprehensive Software Diagnostics Review</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-frozen-screen-top-tips-for-dealing-with-windows-10-freezes/"><u>Fixing a Frozen Screen: Top Tips for Dealing with Windows 10 Freezes</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-wd-my-passport-ultra-missing-from-windows-device-manager/"><u>Fixing the Issue: WD My Passport Ultra Missing From Windows Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-enabling-bluetooth-connectivity-in-windows-7-solutions-revealed/"><u>Guide: Enabling Bluetooth Connectivity in Windows 7 - Solutions Revealed</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-eliminate-endless-loading-times-on-skyrim-a-solution/"><u>How to Eliminate Endless Loading Times on Skyrim – A Solution</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-androidprocessmedia-has-stopped-on-vivo-y100-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Android.Process.Media Has Stopped on Vivo Y100 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-device-not-detected-problem-fixing-error-code-24-on-windows-os/"><u>How to Overcome 'Device Not Detected' Problem - Fixing Error Code 24 on Windows OS</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-quiet-your-playstation-4-diagnosing-and-repairing-louder-than-usual-fan-sounds/"><u>How to Quiet Your PlayStation 4: Diagnosing and Repairing Louder-Than-Usual Fan Sounds</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-restore-right-click-capabilities-for-mice-on-your-windows-11-pc/"><u>How to Restore Right-Click Capabilities for Mice on Your Windows 11 PC</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-a-surface-device-thats-plugged-in-but-fails-to-charge/"><u>How To Troubleshoot: A Surface Device That's Plugged In But Fails to Charge</u></a></li>
<li><a href="https://screen-mirror.techidaily.com/in-2024-how-can-samsung-galaxy-a54-5gmirror-share-to-pc-drfone-by-drfone-android/"><u>In 2024, How Can Samsung Galaxy A54 5GMirror Share to PC? | Dr.fone</u></a></li>
<li><a href="https://buynow-marvelous.techidaily.com/innovative-wrist-tech-showdown-top-smartwatches/"><u>Innovative Wrist Tech Showdown: Top Smartwatches</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212458133-master-the-art-of-connecting-hdmi-devices-with-a-windows-11-system-no-more-frustrations/"><u>Master the Art of Connecting HDMI Devices with a Windows 11 System: No More Frustrations</u></a></li>
<li><a href="https://win11-tips.techidaily.com/navigating-through-non-functioning-intel-unison-issues-in-windows-11/"><u>Navigating Through Non-Functioning Intel Unison Issues in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/new-world-overcomes-previous-easy-anti-cheat-issues-now-fully-functional/"><u>New World Overcomes Previous Easy Anti-Cheat Issues: Now Fully Functional</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-obstacles-a-fixed-nvidia-error/"><u>Overcoming Obstacles: A Fixed NVIDIA Error</u></a></li>
<li><a href="https://fox-that.techidaily.com/overcoming-problems-with-iphones-6-steps-to-make-guided-access-work-again/"><u>Overcoming Problems with iPhones: 6 Steps to Make Guided Access Work Again</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-problems-with-starting-a-hosted-network-in-windows-11-solutions-and-guidance/"><u>Overcoming Problems with Starting a Hosted Network in Windows 11: Solutions and Guidance</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-overcoming-heathstone-game-lags/"><u>Quick Solutions for Overcoming Heathstone Game Lags</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-troubleshooting-endless-windows-update-progress-at-100/"><u>Resolved: Troubleshooting Endless Windows Update Progress at 100%%</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-connection-errors-in-geforce-experience-settings-retrieval/"><u>Resolving Connection Errors in GeForce Experience Settings Retrieval</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-elevated-cpu-consumption-in-system-idle-process-a-comprehensive-guide/"><u>Resolving Elevated CPU Consumption in System Idle Process: A Comprehensive Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/seamless-folder-navigation-in-windows-10-easy-tips-for-using-file-explorer/"><u>Seamless Folder Navigation in Windows 10 - Easy Tips for Using File Explorer</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-steam-api-dll-errors/"><u>Solutions for Steam API DLL Errors</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-symbol-issues-a-step-by-step-guide/"><u>Solving '@' Symbol Issues: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/speaker-crackling-in-windows-117-solved/"><u>Speaker Crackling in Windows 11/7 [SOLVED]</u></a></li>
<li><a href="https://win-forum.techidaily.com/step-by-step-guide-enabling-wake-on-lan-feature-on-your-pc-running-windows-11/"><u>Step-by-Step Guide: Enabling Wake-on-LAN Feature on Your PC Running Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/streamline-win11s-performance-with-provider-host-fixes/"><u>Streamline Win11's Performance with Provider Host Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208217755-the-ultimate-fix-guide-for-overcoming-error-1068-in-windows-expert-advice-included/"><u>The Ultimate Fix Guide for Overcoming Error 1068 in Windows – Expert Advice Included!</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-complete-battleye-installation-now-running-smoothly/"><u>Troubleshooting Complete: BattlEye Installation Now Running Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-for-a-non-responsive-microsoft-keyboard/"><u>Troubleshooting Guide for a Non-Responsive Microsoft Keyboard</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-missing-device-drivers-on-windows-7-installation/"><u>Troubleshooting Guide: Missing Device Drivers on Windows 7 Installation</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-overcoming-no-pentouch-issues-on-your-monitor/"><u>Troubleshooting Guide: Overcoming 'No Pen/Touch' Issues on Your Monitor</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-fixing-windows-error-0x80n04cf/"><u>Troubleshooting Tips for Fixing Windows Error 0X80n04CF</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unveiling-palm-2-googles-enhanced-ai-linguistic-powerhouse/"><u>Unveiling PaLM 2: Google's Enhanced AI Linguistic Powerhouse</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2100527/7443" target="_top" id="2100527">
  <img src="//a.impactradius-go.com/display-ad/7443-2100527" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2100527/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->