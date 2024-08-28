---
title: "Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)"
date: 2024-08-27T13:45:01.012Z
updated: 2024-08-28T13:45:01.012Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)"
excerpt: "This Article Describes Unstick Your Stagnant Windows Update: Proven Techniques for Instant Success (No More Waiting)"
thumbnail: https://thmb.techidaily.com/33c08cf35f6b5e5c15d53520e124508a521ab9ce21cadff2a0841b9ab0ad5414.jpg
---

## How to Successfully Resolve Error Code 0X80ebbbb on Windows Updates - Proven Techniques Inside

**Error 0x8024402c** , occurs when checking for Windows Updates. It could be caused by invalid network settings, update settings and LAN settings. Here in this post, 4 useful fixes to Error 0x8024402c will being shown to you.

## **Fix 1\. Enable Automatic Detect Settings**

 If your computer is not sure how it should connect to the Internet, it would cause Windows Update Error 0x8024402c. In this case, enable Automatic Detect Settings could fix it.

1) Go with the steps below to enable it.

2) Launch Internet Explorer. Click the**settings icon** on the very top right. Then choose**Internet options** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/1-5.png)

 3) Click **LAN settings**  under**Connection** pane.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/2-4.png)

4) Check on Automatically detect settings

![](https://images.drivereasy.com/wp-content/uploads/2017/03/6-1.png)

Now try to install Windows Updates now.

## **Fix 2\. Remove Invalid Characters in Proxy Exception List**

 Keep your proxy settings clean can prevent your system from navigating to many different and unresourceful servers. Go with the steps below to clean your proxy settings.

 1) \~ 3) Follow step 1-3 to open Local Area Network(LAN) settings in Internet Explorer.

 4) Click**Advanced** while**Use a proxy server for you LAN** is ticked on.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/3-2.png)

5) Clear Exceptions box if there were any content in it.

 Then click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/4-1.png)

6) Exit Internet Explorer and run Command Prompt.

Find and click to open Command Prompt from Start menu.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/5-2.png)

7) Run the commands below one by one.

 a) Type **netsh winhttp reset proxy**  and hit **Enter** .

 b) Type**net stop wuauserv**  and hit **Enter** .

 c) Type **net start wuauserv**  and hit **Enter** .

Now try to install Windows Updates now.

## Fix 3\. Change DNS Servers

 If there were any issue of your ISP(Internet service provider), it could also lead to Error 0x8024402c. Change DNS Servers into public one can solve it.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **ncpa.cpl**  in it and click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/7.png)

<!-- affiliate ads begin -->
<a href="https://store.advancedwebranking.com/order/checkout.php?PRODS=4715051&QTY=1&AFFILIATE=108875&CART=1"><img src="https://secure.avangate.com/images/merchant/14edc6ebfdae2e23bbed83d67f50e983/products/33_awr%20logo.png" border="0"></a>
<!-- affiliate ads end -->
2) Now Internet Connection window is open.

Double-click on your active Network Adapter.

 Then click **Properties**  and double-click on **Internet Protocol Version 4 (TCP/IPv4)** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/8.png)

<!-- affiliate ads begin -->
<a href="https://checkout.mirillis.com/order/checkout.php?PRODS=4704640&QTY=1&AFFILIATE=108875&CART=1"> <img src="https://secure.avangate.com/images/merchant/547a5a56d43f6d40f9a6a2f76501d013/products/1_mirillis_action_boxshot_store_1x.jpg" border="0">
	Home Use license is dedicated for personal, non-commercial use only. 
	If Action! is used for commercial gain or to further any commercial purpose, 
	a Commercial Use license is required. Multi-license (volume discount) is intended for single 
 
	company, user or members of the same household. Action! - screen and game recorder</a>
<!-- affiliate ads end -->
3) Locate Use the following DNS server addresses.

 Set**Preferred DNS server** to be**8.8.8.8**

 Set**Alternate DNS server** to be**8.8.4.4**

 **Note:** That’s Google’s public DNS server addresses.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/9.png)

Now try to install Windows Updates now.

<!-- affiliate ads begin -->
<a href="https://shop.systoolsgroup.com/affiliate.php?ACCOUNT=SYSTOOBY&AFFILIATE=108875&PATH=https%3A%2F%2Fwww.systoolsgroup.com%3FAFFILIATE%3D108875%26RESOURCE%3D%2BSysTools%2BOutlook%2BRecovery"><img src="https://www.systoolsgroup.com/box/outlook-recovery.png" border="0"></a>
<!-- affiliate ads end -->
## Fix 4\. Configure Updates Client

If the fixes above didn’t serve you, try this one.

 1) Open**Run** dialog box by pressing Windows logo key + R key together.

 Then type **regedit**  in it and click **OK** .

 Click **Yes**  when prompted by User Account Control.

![](https://images.drivereasy.com/wp-content/uploads/2017/03/10.png)

<!-- affiliate ads begin -->
<h3 id="200610"><a href="https://sentrypc.7eer.net/c/5597632/200610/3022">Parental Control Software</a></h3>
<span class="text-ad-content">
	#1 Rated Parental Control Software.<br/>
	Monitor & Control all PC Activity!<br/>
		<cite style="color:green">sentrypc.com/parental-controls/</cite>
	</span><img height="0" width="0" src="https://sentrypc.7eer.net/i/5597632/200610/3022" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 2) On Regedit Editor window, head to **HKEY\_LOCAL\_MACHINE**  \> **SOFTWARE** \> **Policies**  \>**Microsoft**  \> **Windows**  \> **WindowsUpdate**  \> **AU**

![](https://images.drivereasy.com/wp-content/uploads/2017/03/14.png)

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2097467/26400?prodsku=B700" target="_top" id="2097467"><img src="//a.impactradius-go.com/display-ad/26400-2097467" border="0" alt="" width="640" height="640"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/2097467/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
 3) On the right pane of AU key, double -click on **UseWUServer** , change its value data into**0** .

 Then click **OK** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/15.png)

**Note:** If you can’t find WindowsUpdate, you should create one. Follow the steps below.

 a) Right-click on**Windows**  folder, then choose **New**  \> **Key** .

 And name the new key**WindowsUpdate** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/11.png)

 b) Right-click on**WindowUpdate**  folder, then choose **New**  \> **Key** .

 And name the new key**A** **U** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/12.png)

 c) Right-click on the right pane of AU key, choose**New** \> **DWORD (32-bit) Value**

 Name the new value **UseWUServer** .

![](https://images.drivereasy.com/wp-content/uploads/2017/03/13.png)

<!-- affiliate ads begin -->
<a href="https://aofit.pxf.io/c/5597632/1399701/16396" target="_top" id="1399701"><img src="//a.impactradius-go.com/display-ad/16396-1399701" border="0" alt="" width="960" height="300"/></a><img height="0" width="0" src="https://imp.pxf.io/i/5597632/1399701/16396" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->
Now try to install Windows Updates now.

After the fixes above, Windows Update should be good to go now.

* [Windows Update](/tag-search/?tagId=62)


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
<li><a href="https://fox-direct.techidaily.com/new-2024-approved-the-bottom-line-podcasters-earnings-on-average/"><u>[New] 2024 Approved  The Bottom Line  Podcasters' Earnings, On Average</u></a></li>
<li><a href="https://youtube-sure.techidaily.com/024-approved-youtube-studio-optimization-device-agnostic-approaches/"><u>[New] 2024 Approved  Youtube Studio Optimization  Device-Agnostic Approaches</u></a></li>
<li><a href="https://fox-direct.techidaily.com/new-in-2024-apex-gk-quizmasters-video-channel-list/"><u>[New] In 2024, Apex GK Quizmasters' Video Channel List</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-directed-camera-roll-efficient-sync-with-snapchat-features/"><u>[New] In 2024, Directed Camera Roll  Efficient Sync with Snapchat Features</u></a></li>
<li><a href="https://vimeo-videos.techidaily.com/updated-vimeo-mastery-choosing-between-free-and-paid-video-download-solutions/"><u>[Updated] Vimeo Mastery  Choosing Between Free and Paid Video-Download Solutions</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-analyzing-the-boons-and-banes-of-vr-headsets/"><u>2024 Approved  Analyzing the Boons & Banes of VR Headsets</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/2024-approved-olympic-ice-sprints-the-best-of-short-track-skating/"><u>2024 Approved  Olympic Ice Sprints  The Best of Short-Track Skating</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-the-professionals-selection-top-5-drones-ranked/"><u>2024 Approved  The Professionals' Selection  Top 5 Drones Ranked</u></a></li>
<li><a href="https://location-fake.techidaily.com/3-ways-to-fake-gps-without-root-on-realme-12-5g-drfone-by-drfone-virtual-android/"><u>3 Ways to Fake GPS Without Root On Realme 12 5G | Dr.fone</u></a></li>
<li><a href="https://android-unlock.techidaily.com/bypassing-google-account-with-vnrom-bypass-for-vivo-v27e-by-drfone-android/"><u>Bypassing Google Account With vnROM Bypass For Vivo V27e</u></a></li>
<li><a href="https://common-error.techidaily.com/code-28-malfunction-in-windows-explorer-explained-solutions-and-tips/"><u>Code 28 Malfunction in Windows Explorer Explained: Solutions and Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solution-for-dealing-with-failed-attempts-at-accessing-a-remote-server/"><u>Comprehensive Solution for Dealing With Failed Attempts at Accessing a Remote Server</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-strategies-to-overcome-recurring-freezing-errors-on-windows-or-mac-systems/"><u>Comprehensive Strategies to Overcome Recurring Freezing Errors on Windows or Mac Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-advice-for-repairing-error-0x802n4401c-that-hampers-update-process-on-windows-10-and-11-machines/"><u>Expert Advice for Repairing Error 0X802n4401C That Hampers Update Process on Windows 10 & 11 Machines</u></a></li>
<li><a href="https://common-error.techidaily.com/expert-tips-for-repairing-a-broken-internet-explorer-connection/"><u>Expert Tips for Repairing a Broken Internet Explorer Connection</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-failed-to-update-warframe-issue-a-comprehensive-guide/"><u>Fixing the 'Failed to Update Warframe' Issue – A Comprehensive Guide</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-tutorial-to-bypass-your-sony-xperia-5-v-face-lock-by-drfone-android/"><u>Full Tutorial to Bypass Your Sony Xperia 5 V Face Lock?</u></a></li>
<li><a href="https://youtube-lab.techidaily.com/-to-producing-effective-youtube-promo-videos-for-2024/"><u>Guide to Producing Effective YouTube Promo Videos for 2024</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/here-are-some-reliable-ways-to-get-pokemon-go-friend-codes-for-infinix-smart-8-pro-drfone-by-drfone-virtual-android/"><u>Here Are Some Reliable Ways to Get Pokemon Go Friend Codes For Infinix Smart 8 Pro | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-windows-updates-stalled-on-99-or-100-solved/"><u>How to Fix Windows Updates Stalled on 99 or 100%% - Solved!</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-troubleshoot-non-charging-devices-in-windows-7-and-10-systems/"><u>How to Troubleshoot Non-Charging Devices in Windows 7 and 10 Systems</u></a></li>
<li><a href="https://extra-lessons.techidaily.com/in-2024-celebrating-soundtracks-the-ultimate-anime-list/"><u>In 2024, Celebrating Soundtracks  The Ultimate Anime List</u></a></li>
<li><a href="https://common-error.techidaily.com/quick-fixes-for-when-your-pc-mouse-gets-stuck-a-complete-solution/"><u>Quick Fixes for When Your PC Mouse Gets Stuck – A Complete Solution</u></a></li>
<li><a href="https://common-error.techidaily.com/resolving-issues-with-your-windows-stores-cached-data-a-guide/"><u>Resolving Issues with Your Windows Store's Cached Data – A Guide</u></a></li>
<li><a href="https://common-error.techidaily.com/solution-guide-dealing-with-a-hanging-google-chrome-window/"><u>Solution Guide: Dealing with a Hanging Google Chrome Window</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-guide-to-correcting-windows-update-failure-error-0x80070002/"><u>Step-by-Step Guide to Correcting Windows Update Failure (Error 0X80070002)</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-solutions-for-the-non-working-print-screen-button-on-pcs-with-windows-10-or-11/"><u>Step-by-Step Solutions for the Non-Working Print Screen Button on PCs with Windows 10 or 11</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-fix-steam-cannot-write-to-disc-error-swiftly/"><u>Step-by-Step Tips to Fix Steam Cannot Write to Disc Error Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/step-by-step-tips-to-restore-keyboard-functionality-on-login/"><u>Step-by-Step Tips to Restore Keyboard Functionality on Login</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/straightforward-screen-capture-app-win10-edition-for-2024/"><u>Straightforward Screen Capture App, Win10 Edition for 2024</u></a></li>
<li><a href="https://tech-revival.techidaily.com/the-future-is-here-8-ways-artificebot-intelligence-shapes-modern-content-strategies/"><u>The Future Is Here: 8 Ways Artificebot Intelligence Shapes Modern Content Strategies</u></a></li>
<li><a href="https://common-error.techidaily.com/top-8-solutions-overcome-the-persistent-windows-10-update-error-0x800f0922/"><u>Top 8 Solutions: Overcome the Persistent Windows 10 Update Error 0X800F0922</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-correcting-the-unrecoverable-error-1603-during-program-install/"><u>Troubleshooting Guide: Correcting the Unrecoverable Error 1603 During Program Install</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-fixing-freezing-issues-during-windows-10-launch/"><u>Troubleshooting Guide: Fixing Freezing Issues During Windows 10 Launch</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-for-making-bluetooth-appear-in-your-computers-device-manager/"><u>Troubleshooting Tips for Making Bluetooth Appear in Your Computer's Device Manager</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-tips-overcome-the-hurdle-of-error-0x800f0831-using-windows-update-features/"><u>Troubleshooting Tips: Overcome the Hurdle of Error 0X800f0831 Using Windows Update Features</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/ultimate-guides-to-3d-type-exploration/"><u>Ultimate Guides to 3D Type Exploration</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-efficient-techniques-for-removing-audible-elements-from-windows-10-video-content-no-cost-involved/"><u>Updated In 2024, Efficient Techniques for Removing Audible Elements From Windows 10 Video Content (No Cost Involved)</u></a></li>
<li><a href="https://common-error.techidaily.com/usb-device-not-recognized-keeps-popping-up-solved/"><u>USB Device Not Recognized Keeps Popping Up [SOLVED]</u></a></li>
<li><a href="https://common-error.techidaily.com/winning-against-windows-11-keyboard-lag-effective-fixes-revealed/"><u>Winning Against Window's 11 Keyboard Lag - Effective Fixes Revealed</u></a></li>
</ul></div>
