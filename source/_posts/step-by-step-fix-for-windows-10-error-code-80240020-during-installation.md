---
title: Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation
date: 2024-08-27T13:46:12.255Z
updated: 2024-08-28T13:46:12.255Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation
excerpt: This Article Describes Step-by-Step Fix for Windows 10 Error Code 80240020 During Installation
thumbnail: https://thmb.techidaily.com/9828bf793f93780e9596bdf90064698c2faf8ab4424f88be5c51fa1662b48994.jpg
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
<li><a href="https://youtube-lab.techidaily.com/024-approved-maximize-earnings-navigating-youtubes-partner-program-updates/"><u>[New] 2024 Approved  Maximize Earnings  Navigating YouTube's Partner Program Updates</u></a></li>
<li><a href="https://video-capture.techidaily.com/new-decreasing-obs-stream-quality/"><u>[New] Decreasing OBS Stream Quality</u></a></li>
<li><a href="https://article-posts.techidaily.com/new-how-to-retreat-from-macos-sierras-latest-upgrade-for-2024/"><u>[New] How to Retreat From MacOS Sierra's Latest Upgrade for 2024</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/new-in-2024-elevate-your-gaming-experience-with-these-5-techniques-on-windows-11/"><u>[New] In 2024, Elevate Your Gaming Experience with These 5 Techniques on Windows 11</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-in-2024-enhancing-collaboration-whiteboard-tactics-for-all-zoom-users/"><u>[New] In 2024, Enhancing Collaboration  Whiteboard Tactics for All Zoom Users</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-meme-mastery-top-ten-template-treasures/"><u>[New] Meme Mastery  Top Ten Template Treasures</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-transitioning-video-content-into-stills-with-windows-11/"><u>[New] Transitioning Video Content Into Stills with Windows 11</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-ustream-overview-plus-similar-services/"><u>[New] Ustream Overview + Similar Services</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/updated-elevate-your-fb-campaigns-the-20-premier-video-tactics-for-2024/"><u>[Updated] Elevate Your FB Campaigns  The 20 Premier Video Tactics for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/updated-in-2024-discover-the-best-tools-and-tips-to-accurately-tag-your-videos/"><u>[Updated] In 2024, Discover the Best Tools & Tips to Accurately Tag Your Videos</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/1716069034969-updated-in-2024-essential-open-worlds-you-cant-ignore/"><u>[Updated] In 2024, Essential Open Worlds You Can't Ignore!</u></a></li>
<li><a href="https://some-approaches.techidaily.com/updated-swift-skillz-best-high-speed-games-for-laptopsmobile/"><u>[Updated] Swift Skillz  Best High-Speed Games for Laptops/Mobile</u></a></li>
<li><a href="https://article-files.techidaily.com/updated-visual-storytelling-adding-captions-to-images-in-oses-for-2024/"><u>[Updated] Visual Storytelling  Adding Captions to Images in OSes for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/0x80070490-error-code-in-windows-update-fixed/"><u>0X80070490 Error Code in Windows Update [FIXED]</u></a></li>
<li><a href="https://fox-helps.techidaily.com/2024-approved-photos-with-a-musical-edge-online/"><u>2024 Approved  Photos with a Musical Edge Online</u></a></li>
<li><a href="https://common-error.techidaily.com/access-denied-blizzard-network-down/"><u>Access Denied: Blizzard Network Down</u></a></li>
<li><a href="https://some-approaches.techidaily.com/achieve-seamless-user-experience-with-our-advanced-cookiebot-technology-solutions/"><u>Achieve Seamless User Experience with Our Advanced Cookiebot Technology Solutions</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/all-purpose-capture-software-azs-app-critiques-for-2024/"><u>All-Purpose Capture Software - AZ's App Critiques for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/bypass-the-frustration-of-a-windows-code-28-error-effective-remedies-for-your-device-manager-issues/"><u>Bypass the Frustration of a Windows Code 28 Error - Effective Remedies for Your Device Manager Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-touchpad-scrolling-that-just-wont-work-an-expert-solution/"><u>Comprehensive Fixes for Touchpad Scrolling That Just Won't Work: An Expert Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-fixes-for-windows-update-error-bypassing-error-0x8007001f-easily/"><u>Comprehensive Fixes for Windows Update Error - Bypassing Error 0X8007001F Easily</u></a></li>
<li><a href="https://win11.techidaily.com/digital-artistry-perfecting-subject-isolation-techniques/"><u>Digital Artistry: Perfecting Subject Isolation Techniques</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/does-xiaomi-civi-3-has-native-mkv-support-by-aiseesoft-video-converter-play-mkv-on-android/"><u>Does Xiaomi Civi 3 has native MKV support?</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-solutions-for-overcoming-reset-failed-messages-in-windows-10/"><u>Effective Solutions for Overcoming 'Reset Failed' Messages in Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723201682709-effortless-solutions-to-get-windows-10-bluetooth-working-again/"><u>Effortless Solutions to Get Windows 10 Bluetooth Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-restoring-access-to-systemprofiledesktop-on-windows-systems/"><u>Expert Tips for Restoring Access to Systemprofile\\Desktop on Windows Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-and-restart-overcoming-google-chrome-freeze-scenarios/"><u>Fix and Restart: Overcoming Google Chrome Freeze Scenarios</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-error-495-while-downloadupdating-android-apps-on-lava-blaze-pro-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>How to Fix Error 495 While Download/Updating Android Apps On Lava Blaze Pro 5G | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-recover-from-file-explorer-crashing-on-windows-10-computers/"><u>How to Recover From File Explorer Crashing on Windows 10 Computers</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-resolve-the-0x80070643-error-comprehensive-guide-for-windows-update-fixes/"><u>How to Resolve the 0X80070643 Error: Comprehensive Guide for Windows Update Fixes</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-samsung-galaxy-m34-5g-get-deleted-phone-number-back-with-ease-and-safety-by-fonelab-android-recover-contacts/"><u>How to Samsung Galaxy M34 5G Get Deleted Phone Number Back with Ease and Safety</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-best-compact-cameras-for-1000-or-less-4k/"><u>In 2024, Best Compact Cameras for $1000 or Less (4K)</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/in-2024-forgot-iphone-passcode-again-unlock-apple-iphone-11-pro-max-without-passcode-now-drfone-by-drfone-ios/"><u>In 2024, Forgot iPhone Passcode Again? Unlock Apple iPhone 11 Pro Max Without Passcode Now | Dr.fone</u></a></li>
<li><a href="https://article-helps.techidaily.com/in-2024-premier-recommendations-best-iphone-tones-designers/"><u>In 2024, Premier Recommendations  Best iPhone Tones Designers</u></a></li>
<li><a href="https://extra-skills.techidaily.com/in-2024-removing-vibration-effects-from-drones-recordings/"><u>In 2024, Removing Vibration Effects From Drones' Recordings</u></a></li>
<li><a href="https://common-error.techidaily.com/keyboard-malfunctions-on-windows-1011-heres-how-to-get-it-working-again/"><u>Keyboard Malfunctions on Windows 10/11? Here's How to Get It Working Again!</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-mouse-pad-failure-a-step-by-step-solution-for-windows-users-11-8-and-abreast-of-the-latest-os-updates/"><u>Lenovo Mouse Pad Failure: A Step-by-Step Solution for Windows Users (11, 8 & Abreast of the Latest OS Updates)</u></a></li>
<li><a href="https://common-error.techidaily.com/minecraft-stuck-on-loading-quick-fix-tips-for-windows-users-to-get-it-running-smoothly/"><u>Minecraft Stuck on Loading? Quick Fix Tips for Windows Users to Get It Running Smoothly</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-the-mystery-ultimate-guide-to-fixing-google-chromes-missing-display/"><u>Resolve the Mystery: Ultimate Guide to Fixing Google Chrome's Missing Display</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-the-issue-of-steam-server-accessibility/"><u>Resolved: Fixing the Issue of Steam Server Accessibility</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-overcoming-loadlibrary-issue-fixing-error-87-incorrect-parameter/"><u>Resolved: Overcoming 'LoadLibrary' Issue - Fixing Error 87: Incorrect Parameter</u></a></li>
<li><a href="https://common-error.techidaily.com/revive-a-dead-huion-stylus-top-5-speedy-troubleshooting-tips/"><u>Revive a Dead Huion Stylus: Top 5 Speedy Troubleshooting Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-minecraft-performance-problems-ultimate-guide/"><u>Solving Minecraft Performance Problems: Ultimate Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-correcting-unresponsive-fn-buttons-on-a-dell-device/"><u>Step-by-Step Guide to Correcting Unresponsive FN Buttons on a Dell Device</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solution-for-fixing-the-critical-error-code-0xc0000098-on-your-pc/"><u>Step-by-Step Solution for Fixing the Critical Error Code 0Xc0000098 on Your PC</u></a></li>
<li><a href="https://tech-hub.techidaily.com/step-by-step-solution-to-fixing-the-0x802480-update-failure-in-windows-11/"><u>Step-by-Step Solution to Fixing the '0X802480지오' Update Failure in Windows 11</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/the-hidden-powerhouses-in-your-instagram-toolkit/"><u>The Hidden Powerhouses in Your Instagram Toolkit</u></a></li>
<li><a href="https://common-error.techidaily.com/the-ultimate-fix-for-google-chromes-cache-miss-error-tips-and-tricks-to-get-you-back-online/"><u>The Ultimate Fix for Google Chrome's Cache Miss Error: Tips & Tricks to Get You Back Online!</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/top-10-lava-yuva-3-pro-android-sim-unlock-apk-by-drfone-android/"><u>Top 10 Lava Yuva 3 Pro Android SIM Unlock APK</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-lost-desktop-icons-on-windows-10-solved/"><u>Troubleshooting and Fixing Lost Desktop Icons on Windows 10 [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-solving-hp-laptop-webcam-issues-on-windows-10/"><u>Troubleshooting Guide: Solving HP Laptop Webcam Issues on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-halo-4-ue4-fatal-crashes-expert-solutions-and-tips-for-gamers/"><u>Troubleshooting Halo 4 UE4 Fatal Crashes: Expert Solutions & Tips for Gamers</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-persistent-drive-errors-a-step-by-step-solution-for-windows-11-users/"><u>Troubleshooting Persistent Drive Errors: A Step-by-Step Solution for Windows 11 Users</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-fixes-when-your-razer-keyboard-wont-illuminate/"><u>Troubleshooting: Fixes When Your Razer Keyboard Won't Illuminate</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-fixing-the-persistent-issue-of-error-code-0x8024200d-in-windows-updates/"><u>Understanding & Fixing the Persistent Issue of Error Code 0X8024200D in Windows Updates</u></a></li>
<li><a href="https://common-error.techidaily.com/unraveling-the-mystery-of-fixable-installer-issues/"><u>Unraveling the Mystery of Fixable Installer Issues</u></a></li>
<li><a href="https://common-error.techidaily.com/what-to-try-when-windows-10-ignores-logitech-keyboard-input/"><u>What to Try When Windows 10 Ignores Logitech Keyboard Input</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-strategies-to-supercharge-pcs-gaming-capabilities-on-the-latest-windows-11-update/"><u>Winning Strategies to Supercharge PC's Gaming Capabilities on the Latest Windows 11 Update</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-the-battle-against-unpairing-woes-bluetooth-troubleshooting-techniques-on-windows/"><u>Winning the Battle Against Unpairing Woes: Bluetooth Troubleshooting Techniques on Windows 지대</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://coinrule.sjv.io/c/5597632/1958379/18409" target="_top" id="1958379"><img src="//a.impactradius-go.com/display-ad/18409-1958379" border="0" alt="" width="856" height="508"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1958379/18409" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->