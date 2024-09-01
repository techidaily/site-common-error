---
title: How to Repair a Broken Windows 1N Update Process for Optimal Performance
date: 2024-08-31T17:40:41.074Z
updated: 2024-09-01T17:40:41.074Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Repair a Broken Windows 1N Update Process for Optimal Performance
excerpt: This Article Describes How to Repair a Broken Windows 1N Update Process for Optimal Performance
thumbnail: https://thmb.techidaily.com/bd7c586aade6fed49cfda54f6e705ff08c3876c36db98184cb0c5aec1615decc.jpg
---

## Error 80240020 on Your PC? Here's How to Successfully Install Windows 10

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

<!-- affiliate ads begin -->
<a href="https://shop.incomedia.eu/order/checkout.php?PRODS=39655089&QTY=1&AFFILIATE=108875&CART=1"><img src="https://incomedia.eu/files/images/affiliates/wa/01_WA_728x90.jpg" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

<!-- affiliate ads begin -->
<a href="https://twopages.pxf.io/c/5597632/1873305/18544" target="_top" id="1873305"><img src="//a.impactradius-go.com/display-ad/18544-1873305" border="0" alt="" width="1080" height="1350"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1873305/18544" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://bluettide.pxf.io/c/5597632/2042332/17092" target="_top" id="2042332"><img src="//a.impactradius-go.com/display-ad/17092-2042332" border="0" alt="BLUETTI NEW LAUNCH AC180T" width="960" height="900"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2042332/17092" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

<!-- affiliate ads begin -->
<a href="https://store.nero.com/order/checkout.php?PRODS=42296685&QTY=1&AFFILIATE=108875&CART=1"><img src="http://cdnwww.nero.com/nero-com-wAssets/img/banners/2022/video-pp/ScreenshotSlider/Nero-Video-Advanced-editing.JPG" border="0">Simple and intuitive video editing
🎬 Nero Video:
The powerful video editing program for your Windows PC</a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4559731&QTY=1&AFFILIATE=108875&CART=1"><img src="http://www.neowise.com/images/nd-ss-w200.jpg" border="0">NeoDownloader - Fast and fully automatic image/video/music downloader. </a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://store.movavi.com/affiliate.php?ACCOUNT=MOVAVI&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.movavi.com%3FAFFILIATE%3D108875%26RESOURCE%3DMovavi%2BScreen%2BRecorder%2Bbox"><img src="https://mcusercontent.com/0885a03ded3d480dca9287f12/images/f026b149-fc7c-fd54-5f3e-1460bbb19b6b.jpg" border="0"></a>
<!-- affiliate ads end -->
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
<li><a href="https://fox-friendly.techidaily.com/new-perfecting-space-and-system-the-ultimate-preparation-guide-for-2024/"><u>[New] Perfecting Space & System  The Ultimate Preparation Guide for 2024</u></a></li>
<li><a href="https://some-skills.techidaily.com/new-the-mechanics-of-modern-photography-auto-smart-hdr-3-and-4-unveiled/"><u>[New] The Mechanics of Modern Photography  Auto, Smart HDR 3 & 4 Unveiled</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-top-talent-spotlights-inspiring-recruitment-chronicles-1-10/"><u>[New] Top Talent Spotlights  Inspiring Recruitment Chronicles #1-10</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-how-to-fix-kernel32dll-errors-in-windows/"><u>[Solved] How to Fix Kernel32.dll Errors in Windows</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-2024-approved-decoding-the-features-that-make-youtube-premium-special/"><u>[Updated] 2024 Approved  Decoding the Features That Make YouTube Premium Special</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-asmr-app-selection-guide-for-phones-for-2024/"><u>[Updated] ASMR App Selection Guide for Phones for 2024</u></a></li>
<li><a href="https://vp-tips.techidaily.com/updated-expert-analysis-on-slomo-video-softwares-performance/"><u>[Updated] Expert Analysis on SloMo Video Software's Performance</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-fabricate-funny-faces/"><u>[Updated] Fabricate Funny Faces</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-jujutsu-kaisen-in-action-making-memorable-tiktok-videos-for-2024/"><u>[Updated] Jujutsu Kaisen in Action  Making Memorable TikTok Videos for 2024</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-popcorn-projections-thorough-review-of-film-snack-recorder-for-2024/"><u>[Updated] Popcorn Projections  Thorough Review of Film Snack Recorder for 2024</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-unlock-creative-potential-in-tiktok-with-voice-modification-for-2024/"><u>[Updated] Unlock Creative Potential in TikTok with Voice Modification for 2024</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-enhance-your-speaking-skills-no-expense-just-free-tools/"><u>2024 Approved  Enhance Your Speaking Skills – No Expense, Just Free Tools</u></a></li>
<li><a href="https://common-error.techidaily.com/corrective-measures-for-wrp-malfunction-ensuring-smooth-operation-of-windows-maintenece-tasks/"><u>Corrective Measures for WRP Malfunction: Ensuring Smooth Operation of Windows Maintenece Tasks</u></a></li>
<li><a href="https://common-error.techidaily.com/1723206301865-corsair-hs50-headset-mic-problems-heres-how-to-fix-them/"><u>Corsair HS50 Headset Mic Problems? Here's How to Fix Them!</u></a></li>
<li><a href="https://common-error.techidaily.com/detailed-solutions-to-restore-your-dead-or-frozen-laptop-trackpad-functionality/"><u>Detailed Solutions To Restore Your Dead or Frozen Laptop Trackpad Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/diagnosing-and-rectifying-problems-connecting-to-off-site-computers-expert-tips/"><u>Diagnosing and Rectifying Problems Connecting to Off-Site Computers: Expert Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/discover-the-reasons-behind-unprompted-startups-in-windows-11-systems/"><u>Discover the Reasons Behind Unprompted Startups in Windows 11 Systems</u></a></li>
<li><a href="https://extra-tips.techidaily.com/dissecting-intelligence-the-moto-z2-breakdown/"><u>Dissecting Intelligence  The Moto Z2 Breakdown</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-remedies-for-fixing-persistent-restart-problems-in-windows-11-and-10/"><u>Effective Remedies for Fixing Persistent Restart Problems in Windows 11 & 10</u></a></li>
<li><a href="https://common-error.techidaily.com/effective-techniques-to-repair-an-unresponsive-laptop-touchpad/"><u>Effective Techniques to Repair an Unresponsive Laptop Touchpad</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-repairing-a-non-functional-usb-port-on-dell-devices/"><u>Expert Advice for Repairing a Non-Functional USB Port on Dell Devices</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-fixing-the-issue-of-your-computer-keeps-stopping-suddenly/"><u>Expert Advice: Fixing the Issue of Your Computer Keeps Stopping Suddenly</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-how-to-fix-the-persistent-xerox-error-code-0x800f020b-on-windows-machines/"><u>Expert Advice: How to Fix the Persistent Xerox Error Code 0X800F020B on Windows Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/1723209916624-fix-your-laptops-failing-charge-simple-solutions-for-a-full-battery/"><u>Fix Your Laptop's Failing Charge: Simple Solutions for a Full Battery</u></a></li>
<li><a href="https://tech-revival.techidaily.com/from-idea-to-image-da-vincis-top-30-creative-stimuli-for-ai-artists/"><u>From Idea to Image: Da Vinci's Top 30 Creative Stimuli for AI Artists</u></a></li>
<li><a href="https://change-location.techidaily.com/guide-how-to-unbrick-a-bricked-itel-a05s-phone-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Guide How To Unbrick a Bricked Itel A05s Phone | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-repairing-your-windows-11-system-using-sfc-and-deployment-image-servicing/"><u>Guide to Repairing Your Windows 11 System Using SFC and Deployment Image Servicing</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-restoring-steam-privileges-on-corrupted-folders-fixed/"><u>Guide to Restoring Steam Privileges on Corrupted Folders [FIXED]</u></a></li>
<li><a href="https://change-location.techidaily.com/how-can-i-catch-the-regional-pokemon-without-traveling-on-vivo-s17-pro-drfone-by-drfone-virtual-android/"><u>How Can I Catch the Regional Pokémon without Traveling On Vivo S17 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-dx-11-feature-error-for-wwe-2k-battlegrounds-at-level-100-step-by-step-solutions/"><u>How to Fix DX 11 Feature Error for WWE 2K Battlegrounds at Level 10.0 - Step-by-Step Solutions</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-fix-pokemon-go-route-not-working-on-samsung-galaxy-m54-5g-drfone-by-drfone-virtual-android/"><u>How to Fix Pokemon Go Route Not Working On Samsung Galaxy M54 5G? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-unresponsive-google-chrome-prompting-immediate-restart/"><u>How to Fix: Unresponsive Google Chrome Prompting Immediate Restart</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-overcome-errconnectionrefused-illustrated-fixes-for-a-smoother-browsing-experience/"><u>How to Overcome ERR_CONNECTION_REFUSED: Illustrated Fixes for a Smoother Browsing Experience</u></a></li>
<li><a href="https://common-error.techidaily.com/improved-compliance-additional-tactile-feedback-on-display/"><u>Improved Compliance: Additional Tactile Feedback on Display</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-6-proven-ways-to-unlock-vivo-y100t-phone-when-you-forget-the-password-by-drfone-android/"><u>In 2024, 6 Proven Ways to Unlock Vivo Y100t Phone When You Forget the Password</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/24-beginners-blueprint-for-youtube-income-growth/"><u>In 2024, Beginner's Blueprint for YouTube Income Growth</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-can-i-bypass-a-forgotten-phone-password-of-samsung-galaxy-a24-by-drfone-android/"><u>In 2024, Can I Bypass a Forgotten Phone Password Of Samsung Galaxy A24?</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-network-locked-sim-card-inserted-on-your-infinix-note-30-vip-phone-unlock-it-now-by-drfone-android/"><u>In 2024, Network Locked SIM Card Inserted On Your Infinix Note 30 VIP Phone? Unlock It Now</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/in-2024-pro-iphone-hdr-photos-made-easy/"><u>In 2024, Pro iPhone HDR Photos Made Easy</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-swiftly-adjust-video-speeds-a-users-guide-to-youtube-features/"><u>In 2024, Swiftly Adjust Video Speeds  A User's Guide to YouTube Features</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-the-ultimate-guide-to-unlocking-your-apple-iphone-12-mini-on-metropcs-by-drfone-ios/"><u>In 2024, The Ultimate Guide to Unlocking Your Apple iPhone 12 mini on MetroPCS</u></a></li>
<li><a href="https://some-skills.techidaily.com/in-2024-transform-srt-to-video-top-10-free-subtitle-tools/"><u>In 2024, Transform SRT to Video - Top 10 FREE Subtitle Tools</u></a></li>
<li><a href="https://fox-info.techidaily.com/in-2024-unleashing-the-magic-searching-for-photos-on-pexels/"><u>In 2024, Unleashing the Magic  Searching for Photos on Pexels</u></a></li>
<li><a href="https://activate-lock.techidaily.com/in-2024-unlock-your-device-icloud-dns-bypass-explained-and-tested-plus-easy-alternatives-from-apple-iphone-12-by-drfone-ios/"><u>In 2024, Unlock Your Device iCloud DNS Bypass Explained and Tested, Plus Easy Alternatives From Apple iPhone 12</u></a></li>
<li><a href="https://common-error.techidaily.com/mastering-the-art-of-overcoming-remote-server-connection-failures/"><u>Mastering the Art of Overcoming Remote Server Connection Failures</u></a></li>
<li><a href="https://common-error.techidaily.com/no-more-error-code-31-woes-proven-techniques-to-restore-your-windows-stability/"><u>No More Error Code 31 Woes: Proven Techniques to Restore Your Windows Stability</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/quick-remedies-keep-fallout-4-playing-smoothly-on-windows/"><u>Quick Remedies: Keep Fallout 4 Playing Smoothly on Windows</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-issue-unavailability-of-radeon-configuration-utility/"><u>Resolved Issue: Unavailability of Radeon Configuration Utility</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-firefox-security-warnings-a-step-by-step-guide/"><u>Resolving Firefox Security Warnings: A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-the-bad-image-issue-in-windows-11-and-10-a-step-by-step-guide/"><u>Resolving the 'Bad Image' Issue in Windows 11 & 10: A Step-by-Step Guide</u></a></li>
<li><a href="https://tech-revival.techidaily.com/scrutinizing-the-sole-use-of-auto-gpt/"><u>Scrutinizing the Sole Use of Auto-GPT</u></a></li>
<li><a href="https://extra-resources.techidaily.com/standout-80s-visual-tricks-to-enhance-films/"><u>Standout 80S Visual Tricks to Enhance Films</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-overcoming-black-monitor-problems-with-your-dell-pc/"><u>Step-by-Step Solutions for Overcoming Black Monitor Problems with Your Dell PC</u></a></li>
<li><a href="https://common-error.techidaily.com/taming-the-unpredictable-fixing-your-laptops-sudden-off-switches/"><u>Taming the Unpredictable: Fixing Your Laptop's Sudden Off Switches</u></a></li>
<li><a href="https://extra-tips.techidaily.com/top-tactics-for-boosting-vhs-quality-through-digital-tools/"><u>Top Tactics for Boosting VHS Quality Through Digital Tools</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/triumph-over-graphics-gap-win10-plus-nvidia-concordance/"><u>Triumph Over Graphics Gap - Win10 + NVIDIA Concordance</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-error-print-driver-host-crash-on-32-bit-software/"><u>Troubleshooting Error: 'Print Driver Host' Crash on 32-Bit Software</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-making-bluetooth-visible-in-your-pcs-device-management/"><u>Troubleshooting Guide: Making Bluetooth Visible in Your PC's Device Management</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-media-player-sources-not-found-on-windows-machines-solved/"><u>Troubleshooting Media Player Sources Not Found on Windows Machines [Solved]</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-typing-issues-on-windows-11-how-to-repair-non-functional-keys/"><u>Troubleshooting: Typing Issues on Windows 11 – How to Repair Non-Functional Keys</u></a></li>
<li><a href="https://common-error.techidaily.com/ultimate-guide-to-resolve-the-nvidia-web-helper-disappearing-disk-error/"><u>Ultimate Guide to Resolve the Nvidia Web Helper Disappearing Disk Error</u></a></li>
<li><a href="https://common-error.techidaily.com/unlock-the-secrets-to-overcoming-steam-store-connection-problems/"><u>Unlock the Secrets to Overcoming Steam Store Connection Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/unstick-your-stagnant-windows-update-proven-techniques-for-instant-success-no-more-waiting/"><u>Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)</u></a></li>
<li><a href="https://common-error.techidaily.com/unsticking-unresponsive-chrome-expert-tips-on-quick-refresh-techniques/"><u>Unsticking Unresponsive Chrome: Expert Tips on Quick Refresh Techniques</u></a></li>
<li><a href="https://common-error.techidaily.com/upside-down-laptop-screen-troubles-heres-how-to-set-it-right/"><u>Upside Down Laptop Screen Troubles? Here's How to Set It Right</u></a></li>
<li><a href="https://common-error.techidaily.com/warframes-latest-update-hiccup-heres-how-you-can-fix-it-easily/"><u>Warframe's Latest Update Hiccup? Here's How You Can Fix It Easily</u></a></li>
</ul></div>
