---
title: "Windows 10 Setup Fails: Overcome Error Code 80240020 for Successful Installation"
date: 2025-02-27T04:24:49.503Z
updated: 2025-03-02T04:58:09.987Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: "This Article Describes Windows 10 Setup Fails: Overcome Error Code 80240020 for Successful Installation"
excerpt: "This Article Describes Windows 10 Setup Fails: Overcome Error Code 80240020 for Successful Installation"
thumbnail: https://thmb.techidaily.com/99131a0c0da4530303a8f3d5a541a1cf2cb9af3e3d24fd391ca764cff18f1395.jpg
---

## Definitive Solutions to Error 0X802^24200D – Successfully Update Your Windows System Now

If you’re seeing an**error code 0x8024200d**  when performing a Windows update,  you’re not alone. Many Windows users are reporting it. This error code usually appears when they try to update to a new build of the Windows system. The reason behind it is that some updated files are missing or corrupted.

 The good news is you can fix it. You should be able to fix the problem quite easily using one of the solutions we’ve listed below. You may not have to try them all. Just work your way down the list until you find the one that works.

1. [**Running the Windows Update Troubleshooter**](https://tools.techidaily.com/drivereasy/download/)
2. **[Restarting the Windows Update service](https://tools.techidaily.com/drivereasy/download/)**
3. **[Running System File Checker](https://tools.techidaily.com/drivereasy/download/)**
4. **[Downloading updates from Microsoft Update Catalog manually](https://tools.techidaily.com/drivereasy/download/)**

## Method 1: Running the Windows Update Troubleshooter

 You can download and run**the Windows Update Troubleshooter** to automatically diagnose and resolve any issues regarding Windows Update.

**1)** Click **[here](http://aka.ms/diag%5Fwu)**  to download the Windows Update Troubleshooter.

**2)** Double-click the downloaded file (**WindowsUpdate.diagcab** ) to run the troubleshooter, and then click**Next** .

**If your current operating system is Windows 7** , you just need to wait until the troubleshooter finishes the process and shows you the process result.**If your current operating system is Windows 8 or Windows 10** , you may need to follow the steps below.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap3-1.png)

**3)** If there is a more recent version of Windows Update troubleshooter available, click to run it.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap4-2.png)

**4)** In the new version of Windows Update troubleshooter, Click **Next** . The troubleshooter will check the available updates for your machine.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap5-1.png)

**5)** Click **Apply this fix**  to start the update process in the background immediately.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap7.png)

 The troubleshooter will try to fix the issue for you. You can restart your computer and try to perform the Windows update again. If it still doesn’t work, please try the next method.

## Method 2: Restarting the Windows Update service

 You may see this error code if there is something wrong with the Windows Update service. You can try to restart the Windows Update service to resolve this problem. Here’s how to do it:

**1)** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog, then type**services.msc** and press**Enter** to open the Services window.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap13.png)

**2)** Right-click **Windows Update**  and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap14-2.png)

**3)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open **File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to go to the **DataStore**  folder.

`C:\Windows\SoftwareDistribution\DataStore`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap18-2.png)

Please paste it in the address bar.

**4)** Delete all the files in the folder **DataStore** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap20-1.png)

 When all the files are deleted, you shall see “This folder is empty”.

**5)** On your keyboard, press**the Windows Logo Key** and**E** at the same time to open**File Explorer** . Copy the path below and paste it into the address bar, then press **Enter** on your keyboard to open the**Download** folder.

`` `C:\Windows\SoftwareDistribution\Download`

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap21-1.png)

Please paste it in the address bar.

**6)** Delete all the files in the folder**Download** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap22-3.png)

 When all the files are deleted, you shall see “This folder is empty”.

**7)** In the Services window, right-click **Windows Update**  and select**Start** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap24-2.png)

 Go and check Windows Update again to see whether you can perform the Windows update or not. If it still doesn’t work, please try the next method.

## Method 3: Running System File Checker

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue.

**1)**  On your keyboard, press**the Windows Logo Key** and then type**cmd** in the search box. When you see **Command Prompt** in the list of results, right-click it and then select **Run as administrator** . You will be prompted for permission. Click **Ok** to run the **Command Prompt** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap37.png)

**2)** On your keyboard, type the command below and press **Enter** . **If your current operating system is Windows 7, please skip this step.**

DISM.exe /Online /Cleanup-image /Restorehealth

 It may take several minutes for this command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap11.png)

**3)** When this command operation is completed, on your keyboard, type the following command and press **Enter** .

sfc /scannow

It may take some time for the command operation to be completed.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap12-1.png)

**4)** When this command operation is completed, close the **Command Prompt** and run **Windows Update**  again to check whether this method works or not. If you still fail to install updates for your Windows system, please try the next method.

## Method 4: Downloading updates from Microsoft Update Catalog manually

 If all the methods mentioned above still don’t work for you, you can try to download the updates you failed to install from **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  and install them manually.

**1)** On your keyboard, press**the Windows Logo Key** and type**Windows Update** , and then press**Enter** to open Windows Update.

**2)** Click **View update history**  to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.

**3)** Follow the instructions below to view your system type:

**i.** On your keyboard, press**the Windows Logo key** and**R** at the same time to open the Run dialog. Type**cmd** and press**Enter** to open the Command Prompt.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap40.png)

**ii.**  Type the command line**systeminfo** and press**Enter** to view your system type.  
![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap31-2.png)

 “**X64-based PC** ” indicates that your Windows OS is 64-bit; “**X86-based PC** ” means that your Windows OS is 32-bit.

**4)** Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)**  .

**5)**  Type the update number that you want to download. In this example, type KB 3006137 and then click **Search** .

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap42.png)

**6)** In the list of search results, select the right update for your operating system and click **Download** .

 If your Windows OS is 64-bit, you should download the update whose name contains “**x64-based** ”.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap26-1.png)

**7)** In the pop-up window, click the link to start downloading the updates.

![](https://images.drivereasy.com/wp-content/uploads/2018/07/Snap27.png)

**8)** Double-click the downloaded file and follow the on-screen instructions to install the update.

* [Windows](https://tools.techidaily.com/drivereasy/download/)
* [Windows Update](https://tools.techidaily.com/drivereasy/download/)

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
<li><a href="https://article-knowledge.techidaily.com/new-2024-approved-radiant-photography-with-lightrooms-hdr-magic-merge/"><u>[New] 2024 Approved Radiant Photography with Lightroom's HDR Magic Merge</u></a></li>
<li><a href="https://article-files.techidaily.com/new-adding-depth-to-narratives-through-b-clips-for-2024/"><u>[New] Adding Depth to Narratives Through B-Clips for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/new-in-2024-seamless-integration-of-fb-video-on-tv-screens/"><u>[New] In 2024, Seamless Integration of Fb Video on TV Screens</u></a></li>
<li><a href="https://article-posts.techidaily.com/updated-2024-approved-ultimate-studio-tracker-xvideoexploration/"><u>[Updated] 2024 Approved Ultimate Studio Tracker XVideoExploration</u></a></li>
<li><a href="https://article-tips.techidaily.com/updated-best-15-action-cam-footage-editors/"><u>[Updated] Best 15 Action Cam Footage Editors</u></a></li>
<li><a href="https://common-error.techidaily.com/a-step-by-step-solution-to-restore-your-windows-11-sound-settings-when-the-volume-wont-respond/"><u>A Step-by-Step Solution to Restore Your Windows 11 Sound Settings When the Volume Won't Respond</u></a></li>
<li><a href="https://common-error.techidaily.com/addressing-dns-unresponsive-issues-a-guide-to-fast-fixes-and-solutions/"><u>Addressing 'DNS Unresponsive' Issues: A Guide to Fast Fixes and Solutions</u></a></li>
<li><a href="https://common-error.techidaily.com/bouncing-back-from-non-responsive-google-chrome-problems/"><u>Bouncing Back From Non-Responsive Google Chrome Problems</u></a></li>
<li><a href="https://common-error.techidaily.com/display-compatibility-issue-hdcp-free-screen-resolution/"><u>Display Compatibility Issue: HDCP-Free Screen Resolution</u></a></li>
<li><a href="https://techno-recovery.techidaily.com/exploring-elite-storage-solutions-discover-the-premier-network-servers-and-rack-systems/"><u>Exploring Elite Storage Solutions: Discover the Premier Network Servers and Rack Systems</u></a></li>
<li><a href="https://common-error.techidaily.com/how-to-eliminate-latency-issues-with-your-keyboard-on-windows-10-systems/"><u>How to Eliminate Latency Issues with Your Keyboard on Windows 10 Systems</u></a></li>
<li><a href="https://android-unlock.techidaily.com/how-to-enable-usb-debugging-on-a-locked-gionee-phone-by-drfone-android/"><u>How To Enable USB Debugging on a Locked Gionee Phone</u></a></li>
<li><a href="https://win-answers.techidaily.com/how-to-fix-persistent-issues-with-nioh-2-complete-edition-on-windows/"><u>How to Fix Persistent Issues with Nioh 2 (Complete Edition) on Windows</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/ipogo-will-be-the-new-ispoofer-on-oppo-find-x6-drfone-by-drfone-virtual-android/"><u>iPogo will be the new iSpoofer On Oppo Find X6? | Dr.fone</u></a></li>
<li><a href="https://common-error.techidaily.com/resolved-fixing-insufficient-system-resources-error-to-fulfill-your-service-needs/"><u>Resolved: Fixing 'Insufficient System Resources' Error to Fulfill Your Service Needs</u></a></li>
<li><a href="https://common-error.techidaily.com/1723208982281-ret-proto-oncogene-rearrangements-play-a-significant-role-in-the-development-of-medullary-thyroid-cancer-and-have-therapeutic-implications/"><u>RET Proto-Oncogene Rearrangements Play a Significant Role in the Development of Medullary Thyroid Cancer and Have Therapeutic Implications.</u></a></li>
<li><a href="https://youtube-zero.techidaily.com/ess-video-production-youtube-studios-cutting-edge-editing-for-2024/"><u>Seamless Video Production YouTube Studio's Cutting-Edge Editing for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/strategies-for-addressing-the-device-is-not-ready-error-swiftly/"><u>Strategies for Addressing The Device Is Not Ready Error Swiftly</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-dealing-with-non-responsive-com-surrogate-issues/"><u>Troubleshooting Guide - Dealing with Non-Responsive COM Surrogate Issues</u></a></li>
</ul></div>

