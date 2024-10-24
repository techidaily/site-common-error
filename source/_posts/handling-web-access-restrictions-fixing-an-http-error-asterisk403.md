---
title: "Handling Web Access Restrictions: Fixing an HTTP Error Asterisk(403)"
date: 2024-10-22T18:54:31.205Z
updated: 2024-10-24T21:14:03.259Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Handling Web Access Restrictions: Fixing an HTTP Error Asterisk(403)"
excerpt: "This Article Describes Handling Web Access Restrictions: Fixing an HTTP Error Asterisk(403)"
thumbnail: https://thmb.techidaily.com/405adc45ebf84824c8425ce7d2ecb9e77863385d350fb3dba3386c181908ce4e.jpg
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
<li><a href="https://facebook-record-videos.techidaily.com/new-infographics-leveraging-social-media-videos/"><u>[New] Infographics Leveraging Social Media Videos</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-public-domain-zen-soundscape/"><u>[New] Public Domain Zen Soundscape</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-ultimate-step-by-step-guide-to-kinemasters-green-screen-mastery/"><u>[New] The Ultimate Step-by-Step Guide to Kinemaster's Green Screen Mastery</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-the-directory-name-is-invalid-error/"><u>[SOLVED] The Directory Name Is Invalid Error</u></a></li>
<li><a href="https://win-net.techidaily.com/1728464720550-windows-1011/"><u>応急処置:Windows 10/11でディスクを安全に複写する方法</u></a></li>
<li><a href="https://extra-hints.techidaily.com/concealing-identity-select-8-highly-effective-photo-editors-for-2024/"><u>Concealing Identity Select 8 Highly Effective Photo Editors for 2024</u></a></li>
<li><a href="https://win11-tips.techidaily.com/decoding-microsofts-automated-update-protocol/"><u>Decoding Microsoft's Automated Update Protocol</u></a></li>
<li><a href="https://extra-tips.techidaily.com/discover-top-5-cost-free-windows-10-screencast-recorders/"><u>Discover Top 5 Cost-Free Windows 10 Screencast Recorders</u></a></li>
<li><a href="https://common-error.techidaily.com/et3rminate-all-unnecessary-applications-running-in-the-background-that-might-be-hogging-system-resources-which-could-potentially-help-with-driver-installati143/"><u>e.t3rminate All Unnecessary Applications Running in the Background that Might Be Hogging System Resources, Which Could Potentially Help with Driver Installation Issues.</u></a></li>
<li><a href="https://common-error.techidaily.com/effortlessly-resolving-the-windows-11-reboot-cycle-dilemma/"><u>Effortlessly Resolving the Windows 11 Reboot Cycle Dilemma</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-guide-resolving-the-dilemma-of-a-unresponsive-charging-ps4-gamepad/"><u>Expert Guide: Resolving the Dilemma of a Unresponsive Charging PS4 Gamepad</u></a></li>
<li><a href="https://common-error.techidaily.com/fixes-for-persistent-reboot-loop-in-windows-11-and-10-systems/"><u>Fixes for Persistent Reboot Loop in Windows 11 & 10 Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-unseen-troubles-making-western-digitals-my-passport-ultra-visible-again-on-a-windows-pc/"><u>Fixing Unseen Troubles: Making Western Digital's My Passport Ultra Visible Again on a Windows PC</u></a></li>
<li><a href="https://apple-account.techidaily.com/forgot-your-apple-id-password-and-email-from-iphone-13-pro-heres-the-best-fixes-by-drfone-ios/"><u>Forgot Your Apple ID Password and Email From iPhone 13 Pro? Heres the Best Fixes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-unrecognized-external-storage-a-guide-for-wd-my-passport-ultra-in-windows-1011/"><u>How to Resolve Unrecognized External Storage - A Guide for WD My Passport Ultra in Windows 10/11</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/in-2024-unlocking-igtv-success-hashtag-strategies-for-fame/"><u>In 2024, Unlocking IGTV Success Hashtag Strategies for Fame</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-restoring-your-mouses-right-click-in-windows-10/"><u>Step-by-Step Guide to Restoring Your Mouse's Right Click in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-resolving-issues-with-the-at-sign-on-your-device/"><u>Troubleshooting Steps: Resolving Issues with the At Sign on Your Device</u></a></li>
<li><a href="https://tech-savvy.techidaily.com/unraveling-surround-sound-technologies-understanding-the-distinctions-between-dts-and-dolby-digital-plus-a-guide-to-seamless-format-transformation/"><u>Unraveling Surround Sound Technologies: Understanding the Distinctions Between DTS & Dolby Digital, Plus a Guide to Seamless Format Transformation</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2094422/7443" target="_top" id="2094422">
  <img src="//a.impactradius-go.com/display-ad/7443-2094422" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2094422/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

