---
title: "Fixing the COD: WW2 Error 4220 Issue for Smoother Gaming Experience"
date: 2024-08-31T17:43:05.920Z
updated: 2024-09-01T17:43:05.920Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Fixing the COD: WW2 Error 4220 Issue for Smoother Gaming Experience"
excerpt: "This Article Describes Fixing the COD: WW2 Error 4220 Issue for Smoother Gaming Experience"
thumbnail: https://thmb.techidaily.com/793c096330c98d4adab9ce93497e7da7cc149b43448e4b8099556dfb4eb4e677.jpg
---

## Resolving Windows 10 Installation Issue: Fixing Error Code 80240020 Once and for All

The**80240020** error happens usually when the Windows 10 files that you downloaded was not complete and the setup process still tried to do the upgrade to Windows 10\. Or it could be that your Windows 10 installation folder is unfinished or corrupted.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/error-code-80240020.jpg)

Luckily, this is an easy question to solve. Please follow the steps below to get this problem fixed. **Step One**1) Navigate to**C:\\$Windows.\~BT**folder. If you cannot see this folder, please make sure that you have checked the hidden items.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/windows-bt-600x427.jpg)

Delete as many files in this folder as you can. You might not be able to delete all the files due to permission issues. 2) Navigate to**C:\\Windows\\SoftwareDistribution\\Download** and delete all the files in this folder. Please note that you don’t have to delete**Download**folder, but rather, you need to delete the content in it.

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2082538/7443" target="_top" id="2082538"><img src="//a.impactradius-go.com/display-ad/7443-2082538" border="0" alt="" width="1200" height="600"/></a><img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2082538/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/08/softwaredistributiondownload.jpg)

3) Type**cmd.exe**in the search box in**Start**panel and right click the option**cmd**and choose**Run as administrator**. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/run-as-administrator.jpg)Click**Yes**at this prompt.

![](https://images.drivereasy.com/wp-content/uploads/2016/08/uac-command-processor.jpg)

<!-- affiliate ads begin -->
<a href="https://store.massmailsoftware.com/order/checkout.php?PRODS=1300375&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/dc87c13749315c7217cdc4ac692e704c/banera_for_partners-15_%281%29.jpg" border="0"></a>
<!-- affiliate ads end -->
4) Type**wuauclt.exe/updatenow**and hit**Enter**key. ![](https://images.drivereasy.com/wp-content/uploads/2016/08/img_57b5394edbd33.png) **Step Two** **Warning**: Before you proceed with this step, please make sure that you have back up your registry first just in case any irreversible errors happen. Refer to this post to see[**how to backup and restore your registry**](https://tools.techidaily.com/drivereasy/download/). 1) Press**Windows key**and**R**at the same time, then type in**regedit**and hit**Enter**. When prompted for administrator permission, click**Yes** to continue.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=37100474&QTY=1&AFFILIATE=108875&CART=1"><img src="https://awario.com/images/pages/index/img-platform-ui-1280@1x.avif" border="0"></a>
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/regedit.png)

2) Then follow the path:   **HKEY\_LOCAL\_MACHINE\\SOFTWARE\\Microsoft\\Windows\\CurrentVersion\\WindowsUpdate\\OSUpgrade**

<!-- affiliate ads begin -->
<a href="https://ancheer.sjv.io/c/5597632/1657301/17326" target="_top" id="1657301"><img src="//a.impactradius-go.com/display-ad/17326-1657301" border="0" alt="" width="1920" height="933"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1657301/17326" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/hkey_local_machinesoftwaremicrosoftwindowscurrentversionwindowsupdateosupgrade-600x394.jpg)

3) On the right side of the pane, right click on the blank spot and select**New > DWORD (32-bit) Value**.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097466/26400?prodsku=B700" target="_top" id="2097466"><img src="//a.impactradius-go.com/display-ad/26400-2097466" border="0" alt="" width="2048" height="1024"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097466/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
![](https://images.drivereasy.com/wp-content/uploads/2016/10/new-dword-32-bit-value-600x396.jpg)

4) Rename the value to**AllowOSUpgrade**. Then double click the value and set the**Value data**to**1**. Then click**OK**to save the change.

<!-- affiliate ads begin -->
<a href="https://secure.2checkout.com/order/checkout.php?PRODS=4737285&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/b2f83c409ce63012229fb9cd465bdcfe/products/copy_reporting_system.png" border="0">  KoolReport Pro  is an advanced solution for creating data reports and dashboards in PHP. Equipped with all  extended packages , KoolReport Pro is able to connect to various datasources, perform advanced data analysis, construct stunning charts and graphs and export your beautiful work to PDF, Excel, JPG or other formats. Plus, it includes powerful built-in reports such as pivot report and drill-down report which will save your time in building ones. 

 It will help you to write dynamic data reports easily, to construct intuitive dashboards or to build a whole business intelligence cockpit. 

  KoolReport Pro  package goes with Full Source Code, Royal Free, ONE (1) Year Priority Support, ONE (1) Year Free Upgrade and 30-Days Money Back Guarantee. 

  Developer License  allows  Single Developer  to create Unlimited Reports, deploy on Unlimited Servers and able deliver the work to Unlimited Clients. </a>
<!-- affiliate ads end -->
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
<li><a href="https://vimeo-videos.techidaily.com/new-2024-approved-guide-to-successfully-post-movies-made-with-wmm-onto-vimeo/"><u>[New] 2024 Approved  Guide to Successfully Post Movies Made with WMM Onto Vimeo</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/new-2024-approved-mastering-social-media-metrics-the-igtv-hashtag-connection/"><u>[New] 2024 Approved  Mastering Social Media Metrics  The IGTV Hashtag Connection</u></a></li>
<li><a href="https://fox-info.techidaily.com/new-2024-approved-top-visionaries-selecting-the-10-elite-monitors-for-macs/"><u>[New] 2024 Approved  Top Visionaries  Selecting the #10 Elite Monitors for Macs</u></a></li>
<li><a href="https://remote-screen-capture.techidaily.com/updated-quick-recording-visuals-plus-verbal-input-for-2024/"><u>[Updated] Quick Recording  Visuals + Verbal Input for 2024</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/updated-symphony-of-screenshots-incorinas-music-into-social-media-for-2024/"><u>[Updated] Symphony of Screenshots  Incorinas Music Into Social Media for 2024</u></a></li>
<li><a href="https://screen-recording.techidaily.com/updated-the-essential-guide-to-cost-free-cam-screen-recording-apps/"><u>[Updated] The Essential Guide to Cost-Free Cam Screen Recording Apps</u></a></li>
<li><a href="https://common-error.techidaily.com/acquiring-trustedinstaller-consent-to-change-system-files/"><u>Acquiring TrustedInstaller Consent to Change System Files</u></a></li>
<li><a href="https://common-error.techidaily.com/combat-your-desktops-snooze-mode-troubleshoot-and-prevent-involuntary-shutdowns/"><u>Combat Your Desktop's Snooze Mode: Troubleshoot and Prevent Involuntary Shutdowns</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-successfully-completing-your-pending-windows-11-update-issues-addressed/"><u>Expert Tips: Successfully Completing Your Pending Windows 11 Update [ISSUES ADDRESSED]</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-a-non-functional-webcam-on-your-lenovo-laptop-easily/"><u>Fixing a Non-Functional Webcam on Your Lenovo Laptop Easily</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-logitech-g930-headset-audio-issue-steps-and-tips/"><u>Fixing the Logitech G930 Headset Audio Issue: Steps and Tips</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/frp-hijacker-by-hagard-download-and-bypass-your-samsung-galaxy-m14-4g-frp-locks-by-drfone-android/"><u>FRP Hijacker by Hagard Download and Bypass your Samsung Galaxy M14 4G FRP Locks</u></a></li>
<li><a href="https://common-error.techidaily.com/graphics-driver-update-enables-miracast-functionality/"><u>Graphics Driver Update Enables Miracast Functionality</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-overcome-windows-printer-driver-recognition-issues-successfully/"><u>Guide to Overcome Windows Printer Driver Recognition Issues Successfully</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-combat-and-correct-power-surge-events-in-telecommunication-nodes/"><u>How to Combat and Correct Power Surge Events in Telecommunication Nodes</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-a-computer-that-wont-start-solutions-worked/"><u>How to Fix a Computer That Won't Start - Solutions Worked</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-unlock-apple-id-from-your-apple-iphone-13-mini-without-security-questions-by-drfone-ios/"><u>How to Unlock Apple ID From your Apple iPhone 13 mini without Security Questions?</u></a></li>
<li><a href="https://common-error.techidaily.com/lenovo-fn-key-malfunction-heres-how-to-restore-it/"><u>Lenovo Fn Key Malfunction? Here's How to Restore It</u></a></li>
<li><a href="https://common-error.techidaily.com/master-obs-troubleshooting-eradicating-black-screens-in-live-gaming-broadcasts/"><u>Master OBS Troubleshooting: Eradicating Black Screens in Live Gaming Broadcasts</u></a></li>
<li><a href="https://common-error.techidaily.com/1723204655221-monitors-unseen-solutions-abound/"><u>Monitors Unseen, Solutions Abound!</u></a></li>
<li><a href="https://common-error.techidaily.com/overcome-the-stuck-boot-screen-repairing-your-pc-when-it-freezes-on-windows-setup/"><u>Overcome the Stuck Boot Screen: Repairing Your PC When It Freezes on Windows Setup</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-module-not-found-issues-in-development-projects/"><u>Overcoming 'Module Not Found' Issues in Development Projects</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-call-of-duty-wwii-error-4220-easy-solutions-and-troubleshooting-steps/"><u>Overcoming Call of Duty: WWII Error 4220 – Easy Solutions & Troubleshooting Steps</u></a></li>
<li><a href="https://common-error.techidaily.com/overcoming-initialization-issues-in-destiny-2-for-smooth-gameplay/"><u>Overcoming Initialization Issues in Destiny 2 for Smooth Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/protecting-your-data-solving-connection-is-not-secured-on-firefox-quick-guide/"><u>Protecting Your Data: Solving 'Connection Is Not Secured' On Firefox Quick Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-solutions-for-when-your-dns-server-wont-respond-four-key-methods/"><u>Quick Solutions for When Your DNS Server Won't Respond (Four Key Methods)</u></a></li>
<li><a href="https://common-error.techidaily.com/1723205020648-quick-solutions-when-your-hp-laptops-keys-stop-functioning-correctly/"><u>Quick Solutions When Your HP Laptop's Keys Stop Functioning Correctly!</u></a></li>
<li><a href="https://hardware-updates.techidaily.com/setting-up-mono-sound-mode-on-android-phones-for-solo-earbud-listening/"><u>Setting Up Mono Sound Mode on Android Phones for Solo Earbud Listening</u></a></li>
<li><a href="https://extra-skills.techidaily.com/stability-showcase-premium-phone-compatible-tripods-for-2024/"><u>Stability Showcase  Premium Phone-Compatible Tripods for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/support-locked-blizzard-disconnected/"><u>Support Locked: Blizzard Disconnected</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-inputoutput-device-issues-on-your-computer/"><u>Troubleshooting Input/Output Device Issues on Your Computer</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-non-responsive-keys-on-windows-1011-a-step-by-step-guide/"><u>Troubleshooting Non-Responsive Keys on Windows 10/11 - A Step-by-Step Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-non-functional-cameras-in-microsofts-latest-os/"><u>Troubleshooting Steps for Non-Functional Cameras in Microsoft's Latest OS</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-the-error-internet-explorer-has-stopped-working-problem/"><u>Troubleshooting the 'Error: Internet Explorer Has Stopped Working' Problem</u></a></li>
<li><a href="https://common-error.techidaily.com/understanding-and-solving-the-problem-when-your-system-doesnt-boot/"><u>Understanding & Solving: The Problem When Your System Doesn't Boot</u></a></li>
<li><a href="https://common-error.techidaily.com/windows-7-bluetooth-setup-made-simple-your-complete-guide-to-getting-connected/"><u>Windows 7 Bluetooth Setup Made Simple - Your Complete Guide to Getting Connected</u></a></li>
<li><a href="https://common-error.techidaily.com/your-video-card-does-not-support-alpha-blending-fixed/"><u>Your Video Card Does Not Support Alpha Blending [FIXED]</u></a></li>
</ul></div>
