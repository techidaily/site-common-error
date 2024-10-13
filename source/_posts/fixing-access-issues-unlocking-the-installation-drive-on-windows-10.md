---
title: "Fixing Access Issues: Unlocking the Installation Drive on Windows 10"
date: 2024-10-10T21:50:55.264Z
updated: 2024-10-12T21:33:40.357Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing Access Issues: Unlocking the Installation Drive on Windows 10"
excerpt: "This Article Describes Fixing Access Issues: Unlocking the Installation Drive on Windows 10"
thumbnail: https://thmb.techidaily.com/4e54d2ee69e2d3cc5b62664f281e174d4bc506ec5c304888c5062a8c04d6107f.jpg
---

## Fixing Windows 11 Installation Failure: Resolve Error Code 802 #

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
<li><a href="https://facebook-video-share.techidaily.com/new-17-best-lights-and-lighting-equipment-for-youtube-videos-for-2024/"><u>[New] 17 Best Lights and Lighting Equipment for YouTube Videos for 2024</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-in-2024-capture-your-social-face-video/"><u>[Updated] In 2024, Capture Your Social Face Video</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-secrets-to-saving-and-sharing-your-roblox-experience-on-a-mac/"><u>[Updated] Secrets to Saving & Sharing Your Roblox Experience on a Mac</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-unpacking-online-influence-your-channel-versus-competitors-strategies/"><u>[Updated] Unpacking Online Influence Your Channel Versus Competitors' Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/beating-the-100-hurdle-a-step-by-step-fix-to-complete-windows-updates/"><u>Beating the 100% Hurdle: A Step-by-Step Fix to Complete Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/behind-closed-doors-fixing-fortnites-launch/"><u>Behind Closed Doors: Fixing Fortnite's Launch</u></a></li>
<li><a href="https://common-error.techidaily.com/cross-platform-repair-tactics-event-id-1000-error-on-windows-operating-systems-7-to-10/"><u>Cross-Platform Repair Tactics: Event ID 1000 Error on Windows Operating Systems 7 to 10</u></a></li>
<li><a href="https://extra-resources.techidaily.com/cut-to-the-chase-impactful-branding/"><u>Cut to the Chase Impactful Branding</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/evolution-of-innovation-the-top-11-technology-advancements-post-1844/"><u>Evolution of Innovation: The Top 11 Technology Advancements Post-1844</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-repair-and-reactivate-your-bluetooth-mouse-on-a-windows-operating-system/"><u>How to Repair and Reactivate Your Bluetooth Mouse on a Windows Operating System</u></a></li>
<li><a href="https://location-social.techidaily.com/in-2024-how-to-send-and-fake-live-location-on-facebook-messenger-of-your-samsung-galaxy-s23-fe-drfone-by-drfone-virtual-android/"><u>In 2024, How to Send and Fake Live Location on Facebook Messenger Of your Samsung Galaxy S23 FE | Dr.fone</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-which-pokemon-can-evolve-with-a-moon-stone-for-nubia-red-magic-8s-proplus-drfone-by-drfone-virtual-android/"><u>In 2024, Which Pokémon can Evolve with a Moon Stone For Nubia Red Magic 8S Pro+? | Dr.fone</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/maximize-viewership-with-smart-and-stylish-titles/"><u>Maximize Viewership With Smart and Stylish Titles</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-non-compliant-htc-display-lacks-tap-sensitivity/"><u>Resolved: Non-Compliant HTC Display Lacks Tap Sensitivity</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-camera-problems-in-windows-10-a-step-by-step-solution-for-the-surface-pro-4/"><u>Resolving Camera Problems in Windows 10: A Step-by-Step Solution for the Surface Pro 4</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-desktop-inaccessibility-at-cwindowssystem32configsystemprofile-path/"><u>Troubleshooting Desktop Inaccessibility at C: Windows System32 Config SystemProfile Path</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://zebaoaffiliateprogram.pxf.io/c/5597632/2137974/21526" target="_top" id="2137974">
  <img src="//a.impactradius-go.com/display-ad/21526-2137974" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://zebaoaffiliateprogram.pxf.io/i/5597632/2137974/21526" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

