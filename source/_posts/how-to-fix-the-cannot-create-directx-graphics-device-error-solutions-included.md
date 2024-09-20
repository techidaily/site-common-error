---
title: How to Fix the 'Cannot Create DirectX Graphics Device' Error - Solutions Included
date: 2024-09-08T14:11:44.162Z
updated: 2024-09-14T16:05:52.171Z
tags:
  - win11
  - win10
  - win7
categories:
  - CommonErrors
description: This Article Describes How to Fix the 'Cannot Create DirectX Graphics Device' Error - Solutions Included
excerpt: This Article Describes How to Fix the 'Cannot Create DirectX Graphics Device' Error - Solutions Included
thumbnail: https://thmb.techidaily.com/8df3a9bbe5d32c1e5c4eef1f9c5ff4d8504e6e33195196712a21a9cd7ef927c8.jpg
---

## How to Overcome the Recent Discovered Window's 11 Update Databank Flaw - Solutions Included

![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap280-300x215.png)

 If you’re seeing “**Potential Windows Update Database error detected** ” when running the Windows Update Troubleshooter, you’re not alone. Many Windows users are reporting it.

 The good new is you can fix it by yourself. You should be able to fix the problem quite easily using one of the solutions we’ve listed below.

## **Fixes to try**

 You may not have to try them all. Just work your way down the list until you find the one that works.

1. [**Restart your Windows update service**](https://tools.techidaily.com/drivereasy/download/)
2. [**Run the DISM tool**](https://tools.techidaily.com/drivereasy/download/)
3. [**Run the System File Checker**](https://tools.techidaily.com/drivereasy/download/)
4. [**Download updates from Microsoft Update Catalog manually**](https://tools.techidaily.com/drivereasy/download/)
5. [**Perform an in-place upgrade**](https://tools.techidaily.com/drivereasy/download/)
6. [**Pro tip: Want us to fix the problem for you?**](https://tools.techidaily.com/drivereasy/download/)

---

### **Fix 1: Restart your Windows update service**

 You may see this error if there is something wrong with your Windows Update service. Try restarting the Windows Update service and maybe this issue will get resolved. Here’s how to do it:

1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog, then type **services.msc**  and press **Enter**  to open the Services window.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap13-1.png)
2. Right-click **Windows Update** and select **Stop**  if its current status is “Running”. If the Windows Update service is not running, please skip this step.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap281.png)
3. On your keyboard, press **the Windows Logo Key**  and **E**  at the same time to open **File Explorer** .  Copy the path **C:\\Windows\\SoftwareDistribution\\DataStore** and paste it in the address bar, then press **Enter**  on your keyboard to go to the **DataStore**  folder.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap282.png)
4. Delete all the files and folders in the folder **DataStore**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap283.png)
5. Copy the path **C:\\Windows\\SoftwareDistribution\\Download** and paste it in the address bar, then press **Enter**  on your keyboard to open the **Download**  folder.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap284.png)
6. Delete all the files and folders in the folder   **Download**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap285.png)
7. In the Services window, right click **Windows Update** and select **Start**  .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap286.png)

 Perform a Windows update again. If you still fail to perform the Windows update, try the next method.

### **Fix 2: Run the DISM tool**

 This annoying issue is probably caused by the corrupted Windows update files. In this case, running **the Deployment Image Servicing and Management (DISM) tool** may resolve this issue. Just follow the step-by-step instructions to run the DISM tool:

1. On your keyboard, press **the Windows Logo Key**  and **R**  at the same time to open the Run dialog. Type **cmd** and then press **Ctrl** ,**Shift** , and **Enter** on your keyboard   at the same time to**run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run the **Command Prompt** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/1-2.png)
2. On your keyboard, type the command lines below one by one and press **Enter** .  
   1. Dism /Online /Cleanup-Image /ScanHealth  
         * When you run the command mentioned above, the DISM tool will scan all the system files and compare them with official system files. The function of this command line is to see if the system file on your PC is consistent with its official source or not. This command line doesn’t fix the corruption.  
         ![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap29.jpg)  
          It may take several minutes for this command operation to be completed.  
   2. Dism /Online /Cleanup-Image /CheckHealth  
         * When you run the command line**Dism /Online /Cleanup-Image /CheckHealth** , the DISM tool will check whether your Windows 10 image exists corruptions or not. This command line also doesn’t repair the corrupted files.  
         ![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap28.jpg)  
          It may take several minutes for this command operation to be completed.  
   3. **Dism /Online /Cleanup-Image /RestoreHealth**  
         * The command line**Dism /Online /Cleanup-Image /RestoreHealth** tells the DISM tool to try to repair the corrupted files detected. It will replace the corrupted files with the files from official source online.  
         ![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap27.jpg)  
          It may take several minutes for this command operation to be completed.
3. Close the Command Prompt when the restore operation completed.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap13.jpg)

 See if you can perform a Windows update. If this issue persists, try running the System File Checker.

### **Fix 3: Run the System File checker**

 System File Checker can scan for corruptions in Windows system files and restore corrupted files. When you fail to install Windows updates, it may be caused by some corruption error. In this case, running System File Checker may help you resolve this issue. Here is how to do it:

1. On your keyboard, press **the Windows Logo Key**  and **R**  at the same time to open the Run dialog. Type **cmd** and then press **Ctrl** ,**Shift** , and **Enter** on your keyboard   at the same time to**run the Command Prompt as administrator** . You will be prompted for permission. Click **Yes**  to run the **Command Prompt** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/1-2.png)
2. On your keyboard, type the command lines below and press **Enter** .  
   * sfc /scannow  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/08/10-1.png)  
    It may take several minutes for this command operation to be completed.
3. Close the Command Prompt when this command operation completed.

 See if you can perform a Windows update or not. If this fix works, then you won’t see this error. If not, you may need to download updates from**Microsoft Update Catalog** manually to resolve this annoying problem.

<!-- affiliate ads begin -->
<a href="https://ephamedtechinc.pxf.io/c/5597632/2137218/26400" target="_top" id="2137218">
  <img src="//a.impactradius-go.com/display-ad/26400-2137218" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://ephamedtechinc.pxf.io/i/5597632/2137218/26400" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Fix 4: Download updates from Microsoft Update Catalog manually**

 If this annoying issue persists, try downloading the updates you failed to install from[**Microsoft Update Catalog**](http://www.catalog.update.microsoft.com/home.aspx) and install them manually.

1. On your keyboard, press   **the Windows Logo Key**  and type **Windows Update** , and then press **Enter**  to open Windows Update.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap292.png)
2. Click **View update history**   to check the updates you failed to install. For example, if you fail to install update KB3006137, you can download the update and install it manually.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap293.png)
3. Follow the instructions below to view your system type:  
   1. On your keyboard, press **the Windows Logo key**  and **R**  at the same time to open the Run dialog. Type **cmd**  and press **Enter**  to open the Command Prompt.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/08/1-2.png)  
   2. Type the command line **systeminfo**  and press **Enter**  to view your system type.  
   ![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap31-2.png)  
    “**X64-based PC** ” indicates that your Windows OS is**64-bit** ; “**X86-based PC** ” means that your Windows OS is**32-bit** .
4. Visit **[Microsoft Update Catalog](http://www.catalog.update.microsoft.com/home.aspx)** .
5. Type the update number that you want to download. In this example, type KB  3006137 and then click **Search** .  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap42.png)
6. In the list of search results, select right update for your operating system and click **Download**  .  

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2123468/16836" target="_top" id="2123468">
  <img src="//a.impactradius-go.com/display-ad/16836-2123468" border="0" alt="https://techidaily.com" width="125" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2123468/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 If your Windows OS is**64-bit** , you should download the update whose name contains “**x64-based** ”.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap26-1.png)
7. In the pop-up window, click the link to start downloading the updates.  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115930/19272" target="_top" id="2115930">
  <img src="//a.impactradius-go.com/display-ad/19272-2115930" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115930/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap27.png)
8. Double-click the downloaded file and follow the on-screen instructions to install the update.

 See if you this issue persists. If it works , you won’t see this error again. If not, try performing an in-place upgrade.

### **Fix 5: Perform an in-place upgrade**

 Performing an in-place upgrade may help resolve some troubles with the system. So maybe performing an in-place upgrade will fix this issue. Try downloading **the Media Creation Tool** and then follow the on-screen instructions to perform an in-place upgrade. Here is how to do it:

1. Click **[here](https://www.microsoft.com/en-us/software-download/windows10)**  to visit the Microsoft official website for downloading Windows 10.
2. Click **Download tool now**  on the web page to download the Media Creation Tool.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap303.png)
3. Double-click the downloaded file to open the media creation tool. Click **Yes**  when you’re prompted for permission.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap295.png)
4. Click **Accept**  when you see the window below.  
![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap305.png)
5. Select**Upgrade this PC now** and click**Next** .  

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2115938/19272" target="_top" id="2115938">
  <img src="//a.impactradius-go.com/display-ad/19272-2115938" border="0" alt="https://techidaily.com" width="120" height="90"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2115938/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

![](https://images.drivereasy.com/wp-content/uploads/2018/08/Snap304.png)
6. Follow the on-screen instruction to perform an in-place upgrade.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139121/17108" target="_top" id="2139121">
  <img src="//a.impactradius-go.com/display-ad/17108-2139121" border="0" alt="https://techidaily.com" width="320" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139121/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

 After upgrading your Windows system, see if you can perform a Windows update. In most cases, you won’t get this annoying issue after upgrading your Windows system.

### Pro tip: Want us to fix the problem for you?

 If none of the fixes above worked, or you just don’t have the time or confidence to troubleshoot the problem for yourself, get us to fix it for you.

 All you need to do is[buy a 1-year subscription to Driver Easy](https://tools.techidaily.com/drivereasy/download/) (just $29.95) and you get free technical support as part of your purchase. This means you can contact our computer technicians directly and explain your problem, and they’ll investigate to see if they can resolve it remotely.

**IMPORTANT:**  Please attach **the URL of this article** when you contact us, so we could help you resolve the problem ASAP. You can expect us to respond within two working days.

 You can contact us easily via the **Driver Easy Feedback tool** . To learn how to use this tool, please visit this link: [https://www.drivereasy.com/help55/feedback/](https://tools.techidaily.com/drivereasy/download/) .

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
<li><a href="https://tiktok-video-recordings.techidaily.com/new-2024-approved-time-saving-strategies-for-efficient-content-engagement-on-tiktok/"><u>[New] 2024 Approved Time-Saving Strategies for Efficient Content Engagement on TikTok</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-unveiling-the-best-audio-recording-options-for-apple-products/"><u>[New] Unveiling the Best Audio Recording Options for Apple Products</u></a></li>
<li><a href="https://video-capture.techidaily.com/2024-approved-how-to-alter-your-macs-snapshot-format/"><u>2024 Approved How to Alter Your Mac's Snapshot Format</u></a></li>
<li><a href="https://common-error.techidaily.com/banish-irritating-pop-ups-and-cracks-in-your-speaker-with-these-solutions-for-windows-11-or-7/"><u>Banish Irritating Pop-Ups and Cracks in Your Speaker with These Solutions for Windows 11 or 7</u></a></li>
<li><a href="https://fox-glue.techidaily.com/compiling-the-best-12-cost-free-video-apps-for-all-platforms-for-2024/"><u>Compiling the Best 12 Cost-Free Video Apps for All Platforms for 2024</u></a></li>
<li><a href="https://common-error.techidaily.com/conquering-monster-hunters-stealthy-foes-eradicating-the-dark-screen-malfunction-when-initiating-gameplay/"><u>Conquering Monster Hunter's Stealthy Foes: Eradicating the Dark Screen Malfunction When Initiating Gameplay</u></a></li>
<li><a href="https://common-error.techidaily.com/fix-hp-laptop-keyboard-issues-fast-and-simple-now-solved/"><u>Fix HP Laptop Keyboard Issues Fast and Simple - Now Solved</u></a></li>
<li><a href="https://common-error.techidaily.com/guide-to-fixing-non-working-dolby-surround-systems-in-windows-11/"><u>Guide to Fixing Non-Working Dolby Surround Systems in Windows 11</u></a></li>
<li><a href="https://apple-account.techidaily.com/how-to-remove-an-airtag-from-your-apple-id-account-on-iphone-11-pro-by-drfone-ios/"><u>How to Remove an AirTag from Your Apple ID Account On iPhone 11 Pro?</u></a></li>
<li><a href="https://win-amazing.techidaily.com/the-arbitration-process-can-be-tailored-to-fit-the-needs-of-the-parties-involved-allowing-for-flexibility-in-scheduling-and-procedural-rules/"><u>The Arbitration Process Can Be Tailored to Fit the Needs of the Parties Involved, Allowing for Flexibility in Scheduling and Procedural Rules.</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-guide-how-to-activate-wi-fi-on-any-gadget/"><u>Troubleshooting Guide: How to Activate Wi-Fi on Any Gadget</u></a></li>
<li><a href="https://common-error.techidaily.com/troubleshooting-steps-for-this-os-is-unsupported-error-when-setting-up-software/"><u>Troubleshooting Steps for 'This OS Is Unsupported Error' When Setting Up Software</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/ultimate-guide-to-screen-grabbers-for-2024/"><u>Ultimate Guide to Screen Grabbers for 2024</u></a></li>
</ul></div>
