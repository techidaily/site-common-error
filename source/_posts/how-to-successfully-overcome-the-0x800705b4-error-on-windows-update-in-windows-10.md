---
title: How to Successfully Overcome the 0X800705B4 Error on Windows Update in Windows 10
date: 2024-08-22T19:24:21.648Z
updated: 2024-08-23T19:24:21.648Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Successfully Overcome the 0X800705B4 Error on Windows Update in Windows 10
excerpt: This Article Describes How to Successfully Overcome the 0X800705B4 Error on Windows Update in Windows 10
thumbnail: https://thmb.techidaily.com/596d58530eb9322168d7babcbb9a9489a386dda09536b6b2d4f38f91d6402603.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

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
<li><a href="https://youtube-blog.techidaily.com/n-2024-winning-hearts-an-approach-to-encourage-sign-ups/"><u>[New] In 2024, Winning Hearts  An Approach to Encourage Sign-Ups</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-error-code-0x80073cf9-in-windows-11-store/"><u>[Solved] Error Code 0X80073cf9 in Windows 11 Store</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-insta-twist-techniques-for-turning-photos-into-viral-sensations-on-social-media/"><u>[Updated] 2024 Approved  Insta-Twist Techniques for Turning Photos Into Viral Sensations on Social Media</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-top-10-hilarious-and-emotional-instagram-memes-journey/"><u>[Updated] 2024 Approved  Top 10 Hilarious & Emotional Instagram Memes Journey</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-chroma-mastery-made-easy-a-complete-guide-to-green-screen-filmmaking-for-2024/"><u>[Updated] Chroma Mastery Made Easy  A Complete Guide to Green Screen Filmmaking for 2024</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-boost-video-performance-with-key-seo-tools/"><u>[Updated] In 2024, Boost Video Performance with Key SEO Tools</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/updated-in-2024-capturing-creativity-6-approaches-for-recording-minecraft-games/"><u>[Updated] In 2024, Capturing Creativity  6 Approaches for Recording Minecraft Games</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/1716068801584-updated-in-2024-explore-mp4-recording-tools-today/"><u>[Updated] In 2024, Explore MP4 Recording Tools Today!</u></a></li>
<li><a href="https://eaxpv-info.techidaily.com/updated-in-2024-google-meet-broadcast-simplified-youtube-steps/"><u>[Updated] In 2024, Google Meet Broadcast Simplified  YouTube Steps</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-in-2024-premier-short-frame-gatherer-top-lapses/"><u>[Updated] In 2024, Premier Short Frame Gatherer - Top Lapses</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-perfect-screen-recording-made-simple-and-orderly-for-2024/"><u>[Updated] Perfect Screen Recording Made Simple & Orderly for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-smooth-setup-seamless-screenshots-on-dell-devices-for-2024/"><u>[Updated] Smooth Setup  Seamless Screenshots on Dell Devices for 2024</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/updated-the-instagram-experience-adding-vimeo-videos-for-2024/"><u>[Updated] The Instagram Experience  Adding Vimeo Videos for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-visual-impact-expert-guide-to-crop-your-instagram-content-for-2024/"><u>[Updated] Visual Impact  Expert Guide to Crop Your Instagram Content for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/2024-approved-top-10-picture-frames-and-organizers/"><u>2024 Approved  Top 10 Picture Frames & Organizers</u></a></li>
<li><a href="https://howto.techidaily.com/9-solutions-to-fix-process-system-isnt-responding-error-on-nokia-g22-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>9 Solutions to Fix Process System Isnt Responding Error on Nokia G22 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/advanced-fixes-for-the-infamous-fatal-error-that-plagues-halo-4-ue4/"><u>Advanced Fixes for the Infamous Fatal Error That Plagues Halo 4 UE4</u></a></li>
<li><a href="https://common-error.techidaily.com/advanced-users-demand-missing-visual-tools-return/"><u>Advanced Users Demand Missing Visual Tools Return</u></a></li>
<li><a href="https://common-error.techidaily.com/apex-legends-cheating-glitch-solution-overcome-with-ease/"><u>Apex Legends Cheating Glitch Solution - Overcome with Ease</u></a></li>
<li><a href="https://common-error.techidaily.com/complete-guide-to-resolving-game-crashes-in-total-war-rome-remastered/"><u>Complete Guide to Resolving Game Crashes in Total War: Rome Remastered</u></a></li>
<li><a href="https://common-error.techidaily.com/destiny-2-not-working-fix-connection-errors-to-the-game-servers-here/"><u>Destiny 2 Not Working? Fix Connection Errors to the Game Servers Here!</u></a></li>
<li><a href="https://common-error.techidaily.com/effortless-guidance-navigating-and-fixing-issues-with-file-explorer-in-windows-11/"><u>Effortless Guidance: Navigating and Fixing Issues with File Explorer in Windows 11</u></a></li>
<li><a href="https://common-error.techidaily.com/1723212531349-error-on-your-origin-game-follow-these-steps-to-correct-the-setup-and-enjoy/"><u>Error on Your Origin Game? Follow These Steps to Correct the Setup & Enjoy</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-overcoming-secure-socket-layer-issues-on-the-firefox-platform/"><u>Expert Tips for Overcoming Secure Socket Layer Issues on the Firefox Platform</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/explore-unrestricted-stock-content-in-key-4-video-channels/"><u>Explore Unrestricted Stock Content in Key 4 Video Channels</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-and-troubleshoot-unresponsive-touchpad-scrolling-issues-resolved/"><u>Fix & Troubleshoot: Unresponsive Touchpad Scrolling Issues Resolved</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-malfunctioning-alphabetic-keys-in-microsoft-windows-1er-11-environment/"><u>Fix Malfunctioning Alphabetic Keys in Microsoft Windows 1Er 11 Environment</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-touchpad-back-to-work-fixing-scroll-issues-under-windows-10/"><u>Get Your Touchpad Back to Work: Fixing Scroll Issues Under Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/get-your-windows-11-bluetooth-back-fast-and-effective-fixes/"><u>Get Your Windows 11 Bluetooth Back: Fast and Effective Fixes</u></a></li>
<li><a href="https://fake-location.techidaily.com/how-to-change-spotify-location-after-moving-to-another-country-on-huawei-nova-y91-drfone-by-drfone-virtual-android/"><u>How to Change Spotify Location After Moving to Another Country On Huawei Nova Y91 | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-enable-miracast-on-unsupported-graphics-drivers-a-comprehensive-fix/"><u>How to Enable Miracast on Unsupported Graphics Drivers - A Comprehensive Fix</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-usb-device-unrecognized-error-a-step-by-step-guide/"><u>How to Fix 'USB Device Unrecognized' Error: A Step-by-Step Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-vivo-x100-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Vivo X100</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/identifying-power-users-in-niche-specific-instagram-for-2024/"><u>Identifying Power Users in Niche-Specific Instagram for 2024</u></a></li>
<li><a href="https://review-topics.techidaily.com/in-2024-edit-and-send-fake-location-on-telegram-for-your-vivo-s18-pro-in-3-ways-drfone-by-drfone-virtual-android/"><u>In 2024, Edit and Send Fake Location on Telegram For your Vivo S18 Pro in 3 Ways | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/instantly-fix-solve-no-battery-found-error-with-simple-steps/"><u>Instantly Fix: Solve 'No Battery Found' Error with Simple Steps</u></a></li>
<li><a href="https://android-frp.techidaily.com/is-gsm-flasher-adb-legit-full-review-to-bypass-your-samsung-galaxy-s23-ultra-phone-frp-lock-by-drfone-android/"><u>Is GSM Flasher ADB Legit? Full Review To Bypass Your Samsung Galaxy S23 Ultra Phone FRP Lock</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-touchpad-not-responding-heres-the-definitive-fix-for-windows-users/"><u>Lenovo Touchpad Not Responding? Here's the Definitive Fix for Windows Users</u></a></li>
<li><a href="https://tech-recovery.techidaily.com/mastering-cross-platform-usage-running-android-programs-seamlessly-on-windows-10/"><u>Mastering Cross-Platform Usage: Running Android Programs Seamlessly on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209634368-mastering-the-art-of-fixing-ps4-microphone-failures-top-strategies-inside/"><u>Mastering the Art of Fixing PS4 Microphone Failures – Top Strategies Inside!</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-replacing-missing-xinput13dll-files/"><u>Mastering The Art: Replacing Missing XINPUT1_3.dll Files</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-solution-eliminate-your-pcs-pitch-black-predicament-on-windows-11/"><u>Mastering the Solution: Eliminate Your PC's Pitch-Black Predicament on Windows 11</u></a></li>
<li><a href="https://extra-skills.techidaily.com/on-set-questions-answered-quickly-for-2024/"><u>On-Set Questions Answered Quickly for 2024</u></a></li>
<li><a href="https://hardware-help.techidaily.com/quick-access-to-canon-scanner-drivers-for-windows-download-now/"><u>Quick Access to Canon Scanner Drivers for Windows - Download Now!</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/quickcopy-consultants-thoughts/"><u>QuickCopy Consultants' Thoughts</u></a></li>
<li><a href="https://common-error.techidaily.com/resolve-dns-error-instantly-using-our-4-step-guide/"><u>Resolve 'DNS Error' Instantly Using Our 4 Step Guide</u></a></li>
<li><a href="https://extra-resources.techidaily.com/rewind-with-ease-iphone-video-restoration-methods/"><u>Rewind with Ease  IPhone Video Restoration Methods</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/simple-steps-for-snapping-pics-with-your-logitech-kb/"><u>Simple Steps for Snapping Pics with Your Logitech KB</u></a></li>
<li><a href="https://common-error.techidaily.com/solutions-for-fixing-crc-related-data-errors-effectively/"><u>Solutions for Fixing CRC-Related Data Errors Effectively</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205856724-solved-couldnt-load-plugin-chrome-error-on-windows-10/"><u>Solved: Couldn't Load Plugin Chrome Error on Windows 10</u></a></li>
<li><a href="https://techidaily.com/some-mp4-won-t-play-on-my-redmi-13c-5g-by-aiseesoft-video-converter-play-mp4-on-android/"><u>Some MP4 won't play on my Redmi 13C 5G</u></a></li>
<li><a href="https://youtube-docs.techidaily.com/-for-controlling-video-comment-settings-in-youtube/"><u>Steps for Controlling Video Comment Settings in YouTube</u></a></li>
<li><a href="https://common-error.techidaily.com/steps-to-overcome-mycopg-lan-gameplay-challenges-for-seamless-online-gaming/"><u>Steps to Overcome Mycopg LAN Gameplay Challenges for Seamless Online Gaming</u></a></li>
<li><a href="https://extra-tips.techidaily.com/the-ultimate-listening-experience-how-to-add-podcasts-via-ipadiphone/"><u>The Ultimate Listening Experience  How to Add Podcasts via iPad/iPhone</u></a></li>
<li><a href="https://common-error.techidaily.com/top-5-solutions-for-repairing-a-malfunctioning-touch-screen-on-windows-10/"><u>Top 5 Solutions for Repairing a Malfunctioning Touch Screen on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-and-fixing-popscrackling-sounds-on-your-speakers-for-win-10-or-7/"><u>Troubleshooting and Fixing Pops/Crackling Sounds on Your Speakers for Win 10 or 7</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-resolving-windows-updateinstallation-error-0x80070643/"><u>Troubleshooting Guide: Resolving Windows Update/Installation Error 0X80070643</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-sign-in-issues-user-profile-service-errors-in-windows/"><u>Troubleshooting Sign-In Issues: User Profile Service Errors in Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-symbol-a-guide-to-solving-non-functional-special-characters/"><u>Troubleshooting the '@' Symbol: A Guide to Solving Non-Functional Special Characters</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-windows-10-issues-with-built-in-solutions-the-power-of-sfc-and-dism/"><u>Troubleshooting Windows 10 Issues with Built-In Solutions: The Power of SFC & DISM</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-solution-for-unresponsive-computers-step-by-step-fixes/"><u>Ultimate Solution for Unresponsive Computers – Step-by-Step Fixes</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/understanding-the-windows-11-update-utility-explanation-and-steps-for-removal/"><u>Understanding the Windows 11 Update Utility: Explanation & Steps for Removal</u></a></li>
<li><a href="https://common-error.techidaily.com/unexpected-input-hiatus/"><u>Unexpected Input Hiatus</u></a></li>
<li><a href="https://common-error.techidaily.com/unlocking-bluetooth-capabilities-on-windows-7-easy-fixes-for-users/"><u>Unlocking Bluetooth Capabilities on Windows 7: Easy Fixes for Users</u></a></li>
<li><a href="https://common-error.techidaily.com/xbox-one-controller-unleash-potential-for-pc-play/"><u>Xbox One Controller: Unleash Potential for PC Play</u></a></li>
</ul></div>

<!-- affiliate ads begin -->
<a href="https://estore.zonealarm.com/order/checkout.php?PRODS=38658749&QTY=1&AFFILIATE=108875&CART=1"><img src="https://sc1.checkpoint.com/sc1/za/images/boxes/pa_500.png" border="0">ZoneAlarm Pro Antivirus + Firewall NextGen</a>
<!-- affiliate ads end -->