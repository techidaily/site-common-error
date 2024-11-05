---
title: Diagnostic Policy Service Malfunction? Here's the Solution
date: 2024-11-02T23:44:25.195Z
updated: 2024-11-04T21:31:06.880Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes Diagnostic Policy Service Malfunction? Here's the Solution
excerpt: This Article Describes Diagnostic Policy Service Malfunction? Here's the Solution
thumbnail: https://thmb.techidaily.com/5c9cbb5d30907fc5a8d3f1782668978fcf6f103cacbe9ad11043aa91ad5ce8d7.jpg
---

## Diagnostic Policy Service Malfunction? Here's the Solution

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d3c89abccc.png)

 It seems that the network connection is not good on your Windows computer. So probably you to troubleshoot the network through the Windows Network Diagnostics. But unluckily, you are seeing this error saying before it tells you any network problem as before:

**The Diagnostics Policy Service is not running**

 Rest assured. You’re not alone. Many Windows users have this problem as you. More importantly, we’ve found the answer for you.

Read on this small guide and follow to solve the problem on your Windows.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is Diagnostics Policy Service?

 The Diagnostic Policy Service enables problem detection, troubleshooting and resolution for Windows components on your Windows operating system. If this service is not running, diagnostics will no longer function.

## How do I fix the Diagnostics Policy Service is not running issue?

 Here’re 3 easy and helpful solutions you can try. You may not have to try them all; Just start from the top and work your way down the list until your problem is solved.

1. [Check the Diagnostics Policy Service in the Services window](#solution1)
2. [Give the network service and local service administrator privilege on your Windows](#solution2)
3. [Reinstall your all network adapters](#solution3)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134238/18498" target="_top" id="2134238">
  <img src="//a.impactradius-go.com/display-ad/18498-2134238" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134238/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 1: Check the Diagnostics Policy Service in the Services window

 Since the error message tells you that the service is not running, the first quick solution is to check the service status in the Services window.

Follow these steps：

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**services.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f28bd6d2.png)

<!-- affiliate ads begin -->
<a href="https://imp.i357552.net/c/5597632/1006793/11832" target="_top" id="1006793">
  <img src="//a.impactradius-go.com/display-ad/11832-1006793" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://imp.i357552.net/i/5597632/1006793/11832" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 3) Locate**Diagnostics Policy Service** , right-click on it to select**Start** , if Start grayed out, click**Restart** instead.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f6a9233d.jpg)

 4) Right-click on**Diagnostics Policy Service** again and this time select**Properties** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5f83f0ff4.jpg)

 5) Set its Startup type to**Automatic** . Then click**Apply** \>**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d5fb52fb20.png)

6) Run the Network Diagnostics and see if it goes well.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2012415/19272" target="_top" id="2012415">
  <img src="//a.impactradius-go.com/display-ad/19272-2012415" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2012415/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### Solution 2: Give the network service and local service administrator privilege on your Windows

 This problem could happen due to the service doesn’t have access to run properly. You can easily fix it by giving the services administrator privilege.

 1) Type**cmd** in the search box from the Start menu. Then right-click on**Command Prompt** or**cmd.exe** to select**Run as administrator** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d600a418d0.png)

 2) Type the following commands and press**Enter** after each.

net localgroup Administrators /add networkservice  
  
net localgroup Administrators /add localservice  

 If you’re on**Windows 8** , you’ll need to add a space before “service”. So, the commands for you to type would be:  
 net localgroup Administrators /add network service  
 net localgroup Administrators /add local service

 You should see a message saying**The command completed successfully** after each.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d606b83cd1.png)

 3) Close the Command Prompt window, and run the Network Diagnostics to see if it goes well.

### Solution 3: Reinstall your network adapters

 This error could be also caused by your malfunctioned network adapters. You can try to reinstall your network adapters to solve it.

 1) On your keyboard, press the**Windows logo key** and**R** (at the same time) to invoke the Run command.

 2) Type**devmgmt.msc** and click**OK** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d609d065a4.png)

 3) Double-click**Network adapters** and right-click on your network adapters one by one(if there’re more than one) to select**Uninstall device** .

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60d018c06.jpg)

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134244/18498" target="_top" id="2134244">
  <img src="//a.impactradius-go.com/display-ad/18498-2134244" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134244/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 4） Click**Action** \>**Scan for hardware changes** . Microsoft should then reload the network adapter driver automatically.

![](https://images.drivereasy.com/wp-content/uploads/2018/02/img_5a7d60ec552a4.png)

 5) Run the Network Diagnostics to see if it goes well. If it keeps giving you the error, install the latest driver for your network adapter then.

 You can update your network adapter driver manually by going to your motherboard or computer manufacturer’s website, searching for the most recent correct driver for your network adapter. Be sure to choose only drivers that are compatible with your variant of Windows system.

**Note:** If you can get access to the Internet on your computer, then download the driver file from another working computer and save it to the USB flash drive. Then you can install the driver on your target computer through the USB drive.

 Alternatively, If you don’t have the time, patience or computer skills to update your network adapter driver manually, you can, instead, do it automatically with **[Driver Easy](https://tools.techidaily.com/drivereasy/download/)**  . Driver Easy will automatically recognize your system and find the correct drivers for your exact network adapter, and your variant of Windows system, and it will download and install them correctly:

 1) **[Download](https://tools.techidaily.com/drivereasy/download/)**   and install Driver Easy.

 2) Run Driver Easy and click the **Scan Now**   button. Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/09/img_59ad30f1e3ff8.jpg)

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/1925468/19272" target="_top" id="1925468">
  <img src="//a.impactradius-go.com/display-ad/19272-1925468" border="0" alt="https://techidaily.com" width="300" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/1925468/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

3) Click the **Update**  button next to a flagged network adapter driver to automatically download and install the correct version of this driver (you can do this with the **FREE** version).

Or click **Update All**  to automatically download and install the correct version of _all_  the drivers that are missing or out of date on your system (this requires the **Pro** version – you’ll be prompted to upgrade when you click Update All).

 Driver Easy requires network connection to update drivers. If your windows can’t access the Internet, please use the Offline Scan feature of Driver Easy to help you.

 4) After updating your network adapter driver, please restart your computer.

 5) Run the Network Diagnostics to see if it goes well.

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
<li><a href="https://screen-video-capture.techidaily.com/new-2024-approved-expert-tips-on-documenting-lol-tournaments/"><u>[New] 2024 Approved Expert Tips on Documenting LOL Tournaments</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/new-explore-the-excitement-of-high-speed-photography-with-iphone/"><u>[New] Explore the Excitement of High-Speed Photography with iPhone</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-premium-asmr-microphones-impressive-audio-at-economical-costs/"><u>[Updated] Premium ASMR Microphones Impressive Audio at Economical Costs</u></a></li>
<li><a href="https://techtrends.techidaily.com/ai-on-a-budget-combining-free-tools-for-cost-effective-solutions/"><u>AI on a Budget: Combining Free Tools for Cost-Effective Solutions</u></a></li>
<li><a href="https://graphic-issues.techidaily.com/brighten-up-your-lenovo-laptops-screen/"><u>Brighten Up Your Lenovo Laptop's Screen</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/capture-the-moment-quick-steps-for-mobile-phone-screenshots-on-snapchat-for-2024/"><u>Capture the Moment Quick Steps for Mobile Phone Screenshots on Snapchat for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/comprehensive-solutions-to-cure-google-chromes-persistent-black-display-problem/"><u>Comprehensive Solutions to Cure Google Chrome's Persistent Black Display Problem</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cyber-solutions-coverage/"><u>Cyber Solutions Coverage</u></a></li>
<li><a href="https://buynow-help.techidaily.com/enhanced-control-with-ipad-mice-top-picks-reviewed/"><u>Enhanced Control with iPad Mice: Top Picks Reviewed</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-the-issue-windows-1011-night-light-feature-wont-start/"><u>Fixing the Issue: Windows 10/11 Night Light Feature Won't Start</u></a></li>
<li><a href="https://common-error.techidaily.com/fixing-windows-device-driver-power-failures-a-comprehensive-walkthrough/"><u>Fixing Windows Device Driver Power Failures - A Comprehensive Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-fix-your-lenovo-mouse-pad-when-it-stops-working-on-any-windows-platform/"><u>How to Fix Your Lenovo Mouse Pad when It Stops Working on Any Windows Platform</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/in-2024-life360-circle-everything-you-need-to-know-on-samsung-galaxy-s21-fe-5g-2023-drfone-by-drfone-virtual-android/"><u>In 2024, Life360 Circle Everything You Need to Know On Samsung Galaxy S21 FE 5G (2023) | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/solved-troubleshooting-and-repairing-stuck-file-explorer-on-windows-10/"><u>Solved! Troubleshooting and Repairing Stuck File Explorer on Windows 10</u></a></li>
<li><a href="https://common-error.techidaily.com/solving-the-ce-34878-0-hacking-glitch-on-your-sony-ps4-console-complete-walkthrough/"><u>Solving the CE-34878-0 Hacking Glitch on Your Sony PS4 Console - Complete Walkthrough</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshoot-steam-disk-readwrite-errors-with-these-easy-tips/"><u>Troubleshoot Steam Disk Read/Write Errors with These Easy Tips</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-wrap-error-fixing-windows-resource-protection-failed-issues/"><u>Troubleshooting WRAP Error: Fixing 'Windows Resource Protection Failed' Issues</u></a></li>
</ul></div>

